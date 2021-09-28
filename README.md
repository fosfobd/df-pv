## df-pv

based off from: https://github.com/yashbhutwala/kubectl-df-pv

A tool to see df for persistent volumes in k8s.

### Installation
`go install`
remember to include your golang /bin folder in your PATH:
`export PATH=$PATH:$GOPATH/bin`

### Usage
```
  df-pv [flags]

Flags:
  -h, --help               help for df-pv
  -n, --namespace string   if present, the namespace scope for this CLI request (default is all namespaces)
  -v, --verbosity string   log level; one of [info, debug, trace, warn, error, fatal, panic] (default "info")
```
