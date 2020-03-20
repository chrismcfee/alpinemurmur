# alpinemurmur

git clone this repo

How to build and run:

1. Open port 64738 on both UDP and TCP first

2. cd alpinemurmur dir

3. sudo docker build -t <name> .

4. sudo docker run -p 64738:64738/tcp -p 64738:64738/udp <name>

No source packages necessary as all required packages are found in the package manager for this.
