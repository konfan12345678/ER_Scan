# ER_Scan
ER_Scan is a versatile tool designed for encrypted DNS scanning. It facilitates scanning using various encrypted DNS protocols such as DoT, DoH, DoQ, and DoH3.

## Usage:
ER_Scan [flags]
ER_Scan [command]

## Available Commands:
- `completion`: Generate the autocompletion script for the specified shell
- `doh`: Perform a DNS-over-HTTPS scan
- `doh3`: Perform a DNS-over-HTTP3 scan
- `doq`: Perform a DNS-over-QUIC scan
- `dot`: Perform a DNS-over-TLS scan
- `help`: Get help about any command

## Flags:
- `--T int`: Number of threads for DNS scan (default 1000)
- `--b string`: Path to the blacklist file for servers to exclude from lookups
- `--config string`: Specify the configuration file (default is $HOME/.er_scan.yaml)
- `--dname string`: Use the specified domain name when building scan messages (default "example.com")
- `-h, --help`: Get help for ER_Scan
- `--in string`: Path to the input file or CIDR
- `--o string`: Path to the output file
- `-q, --q_draft`: Enable DoQ draft mode
- `-v, --verify`: Enable strict certificate validation when establishing TLS connections

For more information about a specific command, use:
- `ER_Scan [command] --help`
