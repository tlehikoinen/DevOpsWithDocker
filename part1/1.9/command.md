fsutil file createnew text.log 0 && docker run -v "%cd%/text.log:/usr/src/app/text.log" devopsdockeruh/simple-web-service
