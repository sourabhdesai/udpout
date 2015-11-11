# udpout
Starts a UDP server and spits out any received data through stdout

## Usage
    Usage: udpout [options]

    Options:

    -h, --help      output usage information
    -V, --version   output the version number
    -p, --port <n>  port to have the server listen on

**MUST Specify the port with the -p option**. Otherwise, process will exit with a failure status code and won't output anything into stdout.

### Example
`udpout -p 9000 >> out.txt`
With the above, any data sent to the `udpout` process at the port `9000` will be written into out.txt