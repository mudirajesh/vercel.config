# vercel.config

#### vercel.json for backend

```
{
    "version" : 2,
    "name" : "Full Stack",
    "builds" : [
        {
            "src" : "./index.js",
            "use" : "@vercel/node"
        }
    ],
    "routes" : [
        {
            "src" : "/(.*)",
            "dest" : "/"
        }
    ]
}

```