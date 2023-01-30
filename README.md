# learn-k6

Install K6
- sudo gpg --no-default-keyring --keyring /usr/share/keyrings/k6-archive-keyring.gpg --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys C5AD17C747E3415A3642D57D77C6C491D6AC1D69
- echo "deb [signed-by=/usr/share/keyrings/k6-archive-keyring.gpg] https://dl.k6.io/deb stable main" | sudo tee /etc/apt/sources.list.d/k6.list
- sudo apt-get update
- sudo apt-get install k6

Report
https://k6.io/docs/get-started/results-output/

K6 Extensions
- go installation: https://go.dev/doc/install
  - follow path instructions to set go/bin to the $PATH
- check go version: `go version` 
  - check $GOPATH
  - if not set `export GOPATH=/usr/local/go`
- install extension https://k6.io/docs/extensions/get-started/bundle/

Influxdb
- https://github.com/grafana/k6/issues/1883#issuecomment-791248840
- https://k6.io/docs/results-output/real-time/influxdb-grafana/
