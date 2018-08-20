### SimoCoin ###

SimoCoin is a decentralized application (Dapp) platform and cryptocurrency which folked from Crypti project.  

SimoCoin provides a full stack solution for deploying truly decentralized applications onto the blockchain. While also providing an excellent user experience for anyone looking to make safe & easy transactions within seconds.  

SimoCoin's very own Dapp store gives consumers the same if not superior interface consumers have come to expect from existing centralized solutions currently dominating the market.  

Each Dapp operates on a separate custom sidechain secured by SimoCoin's own tried and tested version of the Delegated Proof of Stake consensus model.  

For the progressive startup looking for the perfect platform on which to launch their first Dapp. SimoCoin is by far the quickest to deploy and most democratic solution currently in existence.  

Further development of the core protocol is maintained by the SimoCoin Foundation. A dedicated team of developers, entrepreneurs and engineers from across the globe.  

Requires:

* SQLite (version < 3.8.6)
* Node.js (version 0.10.x)
* Npm

## Installation

Clone the repository and run: 

```sh
npm install --production

```

Install frontend:

```
cd public
npm install
bower install
grunt release
```

Install Crypti.js (required for tests):

```
cd test/cryptijs
npm install
```

Frontend build

```sh
cd public
grunt
grunt release -- for release build
```

Run tests:

```sh
npm install -g mocha
mocha
```


## Start

Go to the SimoCoin folder and run:

```sh
node app.js
```

## License 

The MIT License (MIT)

Copyright (c) 2015 Crypti
Copyright (c) 2018 SimoCoin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
