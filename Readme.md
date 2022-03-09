### Image Build & Run
`docker build -t envoy:local .`
`docker run --rm -d -p 10000:10000 -p 9901:9901 envoy:local`

### Envoy Listener
localhost:10000

### Envoy Admin
localhost:9901