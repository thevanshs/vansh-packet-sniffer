# vansh-packet-sniffer
- To run this code you need a linux os with libpcap and openssl.
- clone this file through terminal.
--> now run these command in series and if you encounter any error try to resolve that error
cd libtins
mkdir build
cd build
cmake ../ (run it as sudo if you encounter permission errors)
make
sudo make install
sudo make tests
sudo make test
Till now if everything is fine then youn are set to use this packet sniffer
cd example
now you can run anything through the list with commond ./(your example).
