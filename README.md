### x2x
---
https://github.com/dottedmag/x2x

```
```

```sh
git clone https://github.com/dottedmag/x2x; cd x2x
./bootstrap.sh
sudo yum -y install libXext-devel libXtst-devel
./configure
make && sudo make install

git clone https://github.com/dottedmag/x2x; cd x2x
git checkout debian
dpkg-checkbuilddeps
sudo apt install anything-missing
fakeroot debian/rules binary
sudo dpkg --install ../x2x_VERSION.deb
```

```
```


