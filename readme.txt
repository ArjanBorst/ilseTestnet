
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


tendermint show-node-id --home ./node0
tendermint show-node-id --home ./node1
tendermint show-node-id --home ./node2
tendermint show-node-id --home ./node3


ilse1:
IP    : 149.210.250.146
NodeID: ee800abeeb692e3f795b107e23ab3f9af817c4ad
Name  : node0

ilse2:
IP    : 149.210.250.238
NodeID: ec98b9d6eaa6a40ad5719ba42d7bf8e016118bcc
Name  : node1

ilse3:
IP    : 93.119.3.62
NodeID: 487c474b5715379bcf7ff9f9a45c9ddfc11e2bcd
Name  : node2

ilse4:
IP    :
NodeID: 35bd47b5a7a9a77c56a46b61210e27d67124fab3
Name  : node3
