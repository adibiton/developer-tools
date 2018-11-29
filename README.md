# developer-tools
useful development tools

### Create local https server
use the following [gist](https://gist.github.com/dergachev/7028596)
in order to run it anywhere on mac OSX:
 - add new file under /usr/local/bin - e.g. pyhttps
 - add the following to the file:
  #!/usr/bin/env python
  .... (taken from the gist)
 - run chmod +x pyhttps
 - from anywhere on your machine run: pyhttps in order to serve your files over ssl
