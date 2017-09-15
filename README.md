# Backend Challenges microservice project - package.json

Run the server.js file or view the deployed app in https://file-metadata-micro-service.glitch.me

# FreeCodeCamp API: File Metadata Microservice
## User stories:
1. I can submit a FormData object that includes a file upload.
2. When I submit something, I will receive the file size in bytes within the JSON response

**Hint:** You may want to use this package: https://www.npmjs.com/package/multer

## Example query usage:

Upload file from the UI at the root.
```text
https://file-metadata-micro-service.glitch.me
```

## Example query output:

```text
https://file-metadata-micro-service.glitch.me/upload
```

```js
{
"name": "2016-01-26.png",
"size": 258957,
"date": "1/27/2016, 1:30:52 AM",
"file": "1453858252196.png"
}
```

N.B it is used a mLab mongodb database. There are these env variables:

```
MONGOLAB_URI=mongodb://test:test@ds038547.mlab.com:38547/file-metadata
```
To use these variables you should store them in a .env file 