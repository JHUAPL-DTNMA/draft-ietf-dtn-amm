Prerequisites to building can be installed on Ubuntu with:
```
sudo apt-get install -y cmake python3-pip python3-wheel ruby xmlstarlet aspell
sudo pip3 install abnf xml2rfc pyang mako
sudo gem install cddl
```
and then the document can be built with
```
cmake -S . -B build/default
cmake --build build/default
```
finally opened with
```
xdg-open build/default/draft-*.html
```
