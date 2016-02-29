Ensures image built on same infra as underlying rocker images

Revise:

* edit Dockerfile
* tag (with tag matching regex rev[0-9.] )
* push --tags
