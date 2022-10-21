# Vaporum RPC Documentation Generator

This tool extracts and formats the help text for each of the Vaporum RPC calls. 

See the `script` directory for the `vaporum.go` script that generates the output and template.

### How to use

Ensure that you have Go installed and a working and running `vaporumd` instance and that the `vaporum-cli` executable is available in `/usr/bin/vaporum-cli` (or update the path to your vaporum-cli executable in `vaporum.go`). From the `script` directory simply run `go run vaporum.go` and the documentation will be produced for all Vaporum RPC calls and styled according to the template in `template.html`.
