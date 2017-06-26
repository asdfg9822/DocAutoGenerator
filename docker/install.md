curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
apt-get install -y nodejs
apt-get install -y build-essential

git clone https://github.com/asdfg9822/polymer-doc-generator.git
cd polymer-doc-generator/

npm install

/usr/bin/node main.js