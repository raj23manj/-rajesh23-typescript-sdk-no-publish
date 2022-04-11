{
  "name": "@rajesh23/typescript-sdk-no-publish",
  "version": "1.0.0",
  "description": "",
  "main": "./build/index.js",
  "types": "./build/index.d.ts",
  // this is used only when npm publis is done, it buils there on the registry
  "files": ["build/**/*"],
  "scripts": {
    "build": "tsc",
    "clean": "del ./build/",
    "postinstall": "tsc --outDir ./build"
  },
  "keywords": [],
  "author": "rajeshmanjunath",
  "license": "ISC",
  "devDependencies": {
    "del-cli": "^4.0.1",
    "typescript": "^4.6.3"
  }
}
