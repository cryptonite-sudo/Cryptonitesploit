# Cryptonite Tool

Cryptonitesploit


***

# About Cryptonite Toolkit

```Cryptonite Tool is a set of tools to provide Netwave 
and GoAhead IP webcams attacks. Cryptonite Tool is a 
powerful tool for webcams penetration testing.
```

***

# Install
```
1.sudo pip3 install -r requirements.txt

2.sudo python3 Cryptonite.py
```

# Cryptonite Tool execution

```
To run Cryptonite  Tool you should 
execute the following command.
```

> Cryptonite

```
usage: Cryptonite [-h] [-b [1|2]] [-o <output_path>] [--timeout <timeout>]
               [-t <tasks>] [-c <count>] [-q | -v]
               [-a <ip:port> | -i <input_file> | --shodan <api> | --zoomeye <api>]
               [-u] [--version]

optional arguments:
  -h, --help            show this help message and exit
  -b [1|2], --brand [1|2]
                        Choose the brand of IP webcam. (1)Netwave, (2)GoAhead.
  -o <output_path>, --output <output_path>
                        Output to the specified path.
  --timeout <timeout>   Timeout in seconds.
  -t <tasks>, --task <tasks>
                        Run tasks number of connects in parallel.
  -c <count>, --count <count>
                        The number of IP you want to get.
  -q, --quiet           Quiet mode.
  -v, --verbose         Verbose mode.
  -a <ip:port>, --address <ip:port>
                        IP and port of the webcam.
  -i <input_file>, --input <input_file>
                        List of webcams addresses.
  --shodan <api>        Attack through Shodan.
  --zoomeye <api>       Attack through ZoomEye.
  -u, --update          Update Cryptonite Tool.
  --version             Show Cryptonite Tool version.
```

***

# Cryptonite Toolkit examples

## Example of attacking a single webcam
    
> Cryptonite -b 1 -i 192.168.1.100:80 -v  

## Example of attacking webcams from a file

> Cryptonite -b 2 -l iplist.txt -v

## Example of attacking webcams through Shodan

> Cryptonite -b 2 -v --shodan PSKINdQe1GyxGgecYz2191H2JoS9qvgD

FROM GEORGIA
