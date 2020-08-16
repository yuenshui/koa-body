## Unreleased

## 4.2.0.4
Improve unit testing

## 4.2.0.0
On the basis of koa-body 4.2.0, add the support of put to upload image files.
1. Add bin option, the default is true
2. Add binlimit option, the default is 1MB
3. When the content-type is not JSON, urlencoded, text or multipart, the body part will be saved as a file. File information in ctx.request.file. and body data will not be written ctx.request.body and ctx.req.body, To ensure safety