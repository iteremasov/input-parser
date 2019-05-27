## Input Parser

#### Description

This repo contains a CLI tool for parsing user input provided in a txt file by patterns provided in a different txt file in 3 different modes.

_____________________________________________________________
#### How to setup 

**Prerequisites to be installed:**
1. node.js v10+
2. npm 6+
3. OS Ubuntu 14+

**Installing:**
1. Clone this repo:
`git clone https://github.com/iteremasov/input-parser.git`
2. Go to repo dirname:
`cd input-parser`
3. Install deps:
`npm ci`

#### How to use

`./parse -i path/to/input.txt -p path/to/patterns.txt -m 1|2|3`
to get  more info:
`./parse --help`
