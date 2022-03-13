
Install Tendermint v0.35.2 and compile
use tendermint v0.35.2

echo export GOPATH=\"\$HOME/go\" >> ~/.bash_profile
echo export PATH=\"\$PATH:\$GOPATH/bin\" >> ~/.bash_profile

git clone https://github.com/tendermint/tendermint.git
cd tendermint

make install
make build

#Check version
tendermint verion
