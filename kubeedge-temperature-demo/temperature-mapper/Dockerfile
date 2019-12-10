FROM ubuntu:16.04
RUN mkdir -p /temperature-mapper
COPY ./ /temperature-mapper
WORKDIR  /temperature-mapper
RUN go build
ENTRYPOINT ["/temperature-mapper/temperature-mapper"]
