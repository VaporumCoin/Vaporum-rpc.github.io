# Komodo RPC Documentation Generator

This tool extracts and formats the help text for each of the Komodo RPC calls. 

See the `script` directory for the `komodo.go` script that generates the output and template.

### How to use

Ensure that you have Go installed and a working and running `komodod` instance and that the `komodo-cli` executable is available in `/usr/bin/komodo-cli` (or update the path to your komodo-cli executable in `komodo.go`). From the `script` directory simply run `go run komodo.go` and the documentation will be produced for all Komodo RPC calls and styled according to the template in `template.html`.
