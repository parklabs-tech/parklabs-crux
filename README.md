# ParkLabs.tech Crux Repository

## About

Collection of build scripts for packages I created for Crux 3.8

## Usage

clone this repo with:

```git clone https://github.com/parklabs-tech/parklabs-crux /usr/ports/parklabs-crux```

Add the following line to ```/etc/prt-get.conf```:

```prtdir /usr/ports/parklabs/crux```

It should come before any other prtdir entries as it overrides default packages in many cases - however if you prefer default packages from crux, you can load it after and it *should* work, but I can't promise anything.
