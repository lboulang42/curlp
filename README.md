# curlp
Little script to use curl with proxies without having to deal with arguments

## Install

Make sure you have curl installed

`sudo apt install curl`

Clone the repo then :

`chmod +x ./curlp ./proxytester`

For convenience moove the scripts to somewhere else in PATH like : 

`mv ./curlp ~/.local/bin/ && mv ./proxytester ~/.local/bin/`

## How To Use

Use curlp exactly like curl :

`curlp ip:port:auth:pass https://something.com`

For the proxies tester just do : 

 `proxytester ~/PATH/TO/PROXIES/FILE.txt`

## Notes

Currently curlp is just an alias to support http proxies format ip\:port\:auth:path. 
