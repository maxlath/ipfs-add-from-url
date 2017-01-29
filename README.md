# ipfs-add-from-url
A command line executable to add a file to IPFS from a URL instead of a file path

## Install
**Globally**
```sh
npm install -g ipfs-add-from-url
# Use anywhere
ipfs-add-from-url https://inventaire.io/public/icon/120.png
```

**In a project**
```sh
npm install ipfs-add-from-url --save
# Use directly from npm scripts
ipfs-add-from-url https://inventaire.io/public/icon/120.png
# Or using the relative path from the command line
./node_modules/.bin/ipfs-add-from-url https://inventaire.io/public/icon/120.png
```
