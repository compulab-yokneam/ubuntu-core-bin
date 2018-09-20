# ubuntu-core-bin

## Creat image file
Simply clone this repository, and make use of `cat` an `zx`:
```
~$ git clone https://github.com/compulab-yokneam/ubuntu-core-bin.git
~$ cd ubuntu-core-bin
~/ubuntu-core-bin $ rm -rf *.md5; cat cl-som-imx7.img.xz_0* | xz -dc > cl-som-imx7.img
```
