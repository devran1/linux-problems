happens when i try to update
"W: Some index files failed to download. They have been ignored, or old ones used instead." 

get inside the etc/apt

pushd /etc

cd apt

cat /usr/share/doc/apt/examples/sources.list > sources.list

then paste those for python

deb http://archive.ubuntu.com/ubuntu bionic main universe

deb http://archive.ubuntu.com/ubuntu bionic-security main universe 

deb http://archive.ubuntu.com/ubuntu bionic-updates main universe


sudo apt-get update

sudo apt-get remove python #removes python2


sudo apt-get install python3

```
sudo add-apt-repository ppa:deadsnakes/ppa

sudo apt install python3.7
```

sudo apt-get install python3-pip

sudo pip3 install virtualenv #if that doesn't work try pip

sudo pip install virtualenv 


virtualenv name

source name/bin/activate

python --version # be sure it is python3

(inside the environment I can use pip not pip3)
