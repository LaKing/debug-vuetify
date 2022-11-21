A simple build in the  dist folder. Served with httpd. 
The vuetify logo gives a 404.
GET http://localhost/src/assets/logo.svg [HTTP/1.1 404 Not Found 0ms]

```yarn create v1.22.17
[1/4] Resolving packages...
[2/4] Fetching packages...
[3/4] Linking dependencies...
[4/4] Building fresh packages...
success Installed "create-vuetify@1.0.4" with binaries:
      - create-vuetify
[############] 12/12
Vuetify.js - Material Component Framework for Vue

✔ Project name: … vuetify-project
✔ Use TypeScript? … No / Yes
✔ Would you like to install dependencies with yarn, npm, or pnpm? › yarn

◌ Generating scaffold...
◌ Installing dependencies with yarn...

yarn install v1.22.17
info No lockfile found.
[1/4] Resolving packages...
[2/4] Fetching packages...
[3/4] Linking dependencies...
[4/4] Building fresh packages...
success Saved lockfile.
Done in 6.41s.
```

```
yarn run v1.22.17
warning package.json: No license field
$ vite build
vite v3.2.4 building for production...
✓ 154 modules transformed.
dist/assets/materialdesignicons-webfont.861aea05.eot     1214.57 KiB
dist/assets/materialdesignicons-webfont.e52d60f6.woff2   376.33 KiB
dist/assets/materialdesignicons-webfont.48d3eec6.woff    548.61 KiB
dist/assets/materialdesignicons-webfont.bd725a7a.ttf     1214.36 KiB
dist/index.html                                          0.41 KiB
dist/assets/webfontloader.b777d690.js                    12.42 KiB / gzip: 4.98 KiB
dist/assets/index.2cee2cdc.js                            113.41 KiB / gzip: 42.42 KiB
dist/assets/index.cc613bb7.css                           566.77 KiB / gzip: 81.32 KiB
Done in 3.76s.

```
