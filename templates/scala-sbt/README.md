# scala-sbt

Template for the scala programming language with sbt build toolings.
Make sure to listen to 0.0.0.0:80. More likely you will need to increase the
MAX_BUILD_DURATION: openode set-config MAX_BUILD_DURATION 500 depending on your
project size. Further, the minimum RAM should be significant - tested with 1 GB ram.
Note that the image is based on https://hub.docker.com/r/hseeberger/scala-sbt/
which is not an official image (none exists yet).
