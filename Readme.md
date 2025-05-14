# First install node.js
## Download and install NVM
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash

## Add NVM to the current shell session
export NVM_DIR="$HOME/.nvm"

[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

nvm install 14  # Try Node.js 14.x which has fewer dependencies

## Install the latest LTS version of Node.js
nvm install --lts

## Verify installation
node -v

npm -v


# install Marz
## Clone the Marz repository:
git clone https://github.com/Samreay/Marz.git

## Navigate to the Marz directory:
cd Marz

## Install the dependencies:
npm install


# To run Marz:
./marz.sh /path/to/the/spec


# To visualize the spectrum, python 2.* dependent and you need to install SimpleHTTPServer
python2 -m SimpleHTTPServer **** # for visual inspection
