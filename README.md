# Docker Image for Selenium By Ruby On Headless Chromium
Image: sinofseven/alpine-selenium-chrome  
Base Image = alpine:edge  
Language = Ruby:2.4.2  
Chromium = 61.0.3163.100  

## How to use
```sh
$ docker run --rm -v $(pwd)/main.rb:/tmp/main.rb sinofseven/alpine-selenium-chrome ruby /tmp/main.rb
```
