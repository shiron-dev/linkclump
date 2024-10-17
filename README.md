# Linkclump

**This repository was forked from [benblack86/linkclump](https://github.com/benblack86/linkclump)**

## Support

Support is not provided as this is a free extension.

## Installation

Install it by visiting the [chrome web store](https://chrome.google.com/webstore/detail/linkclump/lfpjkncokllnfokkgpkobnkbkmelfefj).

## Build

The build process uses ant (run `ant` at the command line) and will run tests and create a zip file that can be uploaded to the chrome store. From docker:

```
docker run --mount type=bind,source="$(pwd)",target=/app frekele/ant:1.10.3-jdk8u111 ant -f /app/build.xml
```
