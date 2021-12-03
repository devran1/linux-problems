happens when i try to update
"W: Some index files failed to download. They have been ignored, or old ones used instead." 

get inside the etc/apt

pushd /etc

cat /usr/share/doc/apt/examples/sources.list > sources.list

then sudo apt-get update
