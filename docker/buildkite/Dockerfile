FROM golang:1.11.1

# RUN apt-get update && apt-get install -y --no-install-recommends \
# 		gettext-base \
# 		libyaml-dev \
# 		openjdk-8-jre \
# 		python \
# 		python-dev \
# 		python-pip \
#         python-setuptools \
# 	&& rm -rf /var/lib/apt/lists/*

# RUN pip install ccm

# RUN go get -u github.com/golang/dep/cmd/dep
# RUN go get -u github.com/Masterminds/glide
# RUN go get -u golang.org/x/lint/golint
# RUN go get github.com/axw/gocov/gocov
# RUN go get github.com/mattn/goveralls
# RUN go get golang.org/x/tools/cmd/cover
# RUN ccm create test -v 3.9 -n 1 -s


# The golang Docker sets the $GOPATH to be /go
# https://github.com/docker-library/golang/blob/c1baf037d71331eb0b8d4c70cff4c29cf124c5e0/1.4/Dockerfile
RUN mkdir -p /go/src/github.com/dmetzgar/golang-docker-example
WORKDIR /go/src/github.com/dmetzgar/golang-docker-example
