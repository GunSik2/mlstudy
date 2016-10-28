# Windows 10 Env

## cygwin
- apt-cyg 
```
./setup-x86_64.exe -q --packages=bash,vim,wget
wget rawgit.com/transcode-open/apt-cyg/master/apt-cyg
install apt-cyg /bin
```

- python3
```
apt-cyg install wget curl gcc-core g++ libzmq-devel libzmq5 python3 python3-zmq libfreetype-devel
```

- pip
```
wget https://bootstrap.pypa.io/get-pip.py
python3 get-pip.py
```

### Anaconda
- Downoload tool: https://www.continuum.io/downloads
