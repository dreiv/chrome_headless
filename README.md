`$ docker build -t chrome-headless .`

`$ docker run -it --rm -p=0.0.0.0:9222:9222 --name=chrome-headless -v /tmp/chromedata/:/data chrome-headless`
