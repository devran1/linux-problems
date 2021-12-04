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

then sudo apt-get update
