# Future plc downloader [![Build Status](https://travis-ci.org/Metalnem/future-plc-downloader.svg?branch=master)](https://travis-ci.org/Metalnem/future-plc-downloader) [![Go Report Card](https://goreportcard.com/badge/github.com/metalnem/future-plc-downloader)](https://goreportcard.com/report/github.com/metalnem/future-plc-downloader) [![license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://raw.githubusercontent.com/metalnem/future-plc-downloader/master/LICENSE)

This command line tool gives you the option to download Future plc magazine issues from your digital library. For more details visit the blog post
[Removing Edge Magazine DRM](https://mijailovic.net/2017/01/22/removing-edge-magazine-drm/).

## Downloads

[Windows](https://github.com/Metalnem/edge-magazine-downloader/releases/download/v1.0.0/edge-magazine-downloader-win64-1.0.0.zip)  
[Mac OS X](https://github.com/Metalnem/edge-magazine-downloader/releases/download/v1.0.0/edge-magazine-downloader-darwin64-1.0.0.zip)  
[Linux](https://github.com/Metalnem/edge-magazine-downloader/releases/download/v1.0.0/edge-magazine-downloader-linux64-1.0.0.zip)

## Usage

```
$ ./future-plc-downloader
Usage of Future plc downloader:
  -name
    	Magazine name
  -email string
    	Account email
  -password string
    	Account password
  -uid string
    	Account UID
```

## Example

```
$ ./future-plc-downloader -name Edge -email user@example.org -password secret123 
```