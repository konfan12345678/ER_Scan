# ER_Scan
ER_Scan is a tool for performing encrypted DNS scans. 
It supports various encrypted DNS protocols like DoT, DoH, DoQ, and DoH3.

Usage:
  ER_Scan [flags]
  ER_Scan [command]

Available Commands:
  completion  Generate the autocompletion script for the specified shell
  doh         DNS-over-HTTPS scan
  doh3        DNS-over-HTTP3 scan
  doq         DNS-over-QUIC scan
  dot         DNS-over-TLS scan
  help        Help about any command

Flags:
      --T int           List of numthread for DNS scan (default 1000)
      --b string        Path to the blacklist file for servers to exclude from lookups
      --config string   config file (default is $HOME/.er_scan.yaml)
      --dname string    Use the specified domain name when building scan messages (default "example.com")
  -h, --help            help for ER_Scan
      --in string       Path to the input file, or CIDR
      --o string        Path to the output file
  -q, --q_draft         Enable DoQ draft mode
  -v, --verify          Use strict certificate validation when establishing TLS connections

Use "ER_Scan [command] --help" for more information about a command.
