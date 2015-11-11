# udpout
Starts a UDP server and spits out any received data through stdout

## Usage
    Usage: udpout [options]

    Options:

    -h, --help      output usage information
    -V, --version   output the version number
    -p, --port <n>  port to have the server listen on

### Example
`udpout -p 9000 >> out.txt`
With the above, any data sent to the `udpout` process at the port `9000` will be written into out.txt