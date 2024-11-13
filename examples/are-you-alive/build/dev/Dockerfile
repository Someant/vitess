FROM golang:1.23.2
RUN go install github.com/cespare/reflex@latest
COPY reflex.conf /reflex.conf
COPY entrypoint.sh /entrypoint.sh
COPY endpoints.yaml /endpoints.yaml
ENTRYPOINT ["/entrypoint.sh"]
