# tgstation Package Archive

Package repository can be found under the gh-pages branch.

## Adding the repostitory

### Debian/Ubuntu

```sh
sudo apt update \
&& sudo apt install -y software-properties-common \
&& sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv B6FD15EE7ED77676EAEAF910EEEDC8280A307527 \
&& sudo add-apt-repository -y "deb https://tgstation.github.io/tgstation-ppa/debian unstable main" \
&& sudo apt update
```
