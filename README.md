# hello-world
My first Git-repo
</br>
My name is Secret

The file db.json can be used for serving mock-data using a "real" http-request.
The file contains JSON, and can be reached using a http-request like:
```
   https://my-json-server.typicode.com/<user>/<repo>/<content of the JSON>
```
eg.
```
   https://my-json-server.typicode.com/Per4Git/hello-world/posts/5
```
 
posts is an array of objects: `[{..},{..},..]`.</br> 
Each object has at least an id-property: `{ "id": 1, "otherProperty": "xxx", .. }`

For the "posts/5"-part, the 5 is not the seqno. in the posts-array.
It is the value of the id-property. 
