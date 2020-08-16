## Unreleased


## 4.2.0.0
On the basis of koa-body 4.2.0, add the support of put to upload image files.
1. Modify the patchKoa option to false by default
2. Add bin option, the default is true
3. Add binlimit option, the default is 1MB
4. When the content-type is not JSON, urlencoded, text or multipart, the body part will be saved as a file. File information in ctx.request.file. and body data will not be written ctx.request.body and ctx.req.body, To ensure safety