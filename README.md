# URL PATH FINDER

[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)

Find interesting website paths and subdomains via terminal.

  - Robots.txt parser
  - Use your wordlist
  - For Legal Purposes Only


### Installation

Pfinder requires [Python](https://www.python.org/) 3.x+ to run.

Install the dependencies to run the script.

```sh
$ git clone https://github.com/lithg/URL-PATH-FINDER.git
$ pip3 install -r requirements.txt
$ python3 pfinder.py -u <url> -l <wordlist> --robots --sub
```

### Arguments

Instructions on how to use them in your own terminal are linked below.

| Args | Default | Required |
| ------ | ------ | ------  |
| -u, -url | None | Yes |
| -l, -list | paths.txt | No |
| --robots | False | No |
| --sub | False | No |


### Example

Parsing Robots.txt:
```sh
$ python pfinder.py -u http://example.com -l wordlist.txt --robots
```

Searching directories + subdomains:
```sh
$ python pfinder.py -u http://example.com -l wordlist.txt --robots --sub
```

Show help:
```sh
$ python pfinder.py -h
```

### Todos

- [x] Robots.txt parser
- [x] Subdomain finder
- [x] Script progress
- [x] Show response code
- [x] Timing
- [ ] Graphic User Interface

### Screenshots

[![P|Finder](https://i.imgur.com/Kw8PL3G.png)](https://github.com/lithg/URL-PATH-FINDER/)

[![P|Finder](https://i.imgur.com/1GbjjHB.png)](https://github.com/lithg/URL-PATH-FINDER/)
