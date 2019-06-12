# ProgrammingInHaskell2ndCoCalc

Example codes in Programming in Haskell (2nd ed) by Graham Hutton, via IHaskell Jupyter Notebook.

Starting from a fresh [cocalc-docker](https://github.com/sagemathinc/cocalc-docker/)

## HOWTO install IHaskell
### run as root
```
curl -sSL https://get.haskellstack.org/ | sh
apt-get install -y python3-pip git libtinfo-dev libzmq3-dev libcairo2-dev libpango1.0-dev libmagic-dev libblas-dev liblapack-dev
```

### in cocalc project terminal
Clone [IHaskell](https://github.com/gibiansky/IHaskell/) and go inside the directory.
```
cd ~
git clone https://github.com/gibiansky/IHaskell.git
cd IHaskell
stack install
ihaskell install --stack
mkdir -p ~/.stack/global-project
cd ~/.stack/global-project
ln -s ~/IHaskell/.stack-work
cd ~
```

## use Jupyter Classic for IHaskell notebooks
for some reason syntax highliting for Haskell only seem to work in Jupyter Classic
