# How to install and configure orchent with oidc-agent

## Step 1: install oidc-agent

Packages for Debian and Ubuntu are available at http://repo.data.kit.edu/ or ...
We recommend to include the apt repository:

- install the repository key:
  ````
  sudo apt-key adv --keyserver hkp://hkps.pool.sks-keyservers.net --recv-keys ACDFB08FDC962044D87FF00B512839863D487A87
  ````
- install the repository - choose one of the following lines depending on your distribution:
     ````
     sudo add-apt-repository "deb http://repo.data.kit.edu/debian/stable ./"
     sudo add-apt-repository "deb http://repo.data.kit.edu/debian/stretch ./"
     sudo add-apt-repository "deb http://repo.data.kit.edu/debian/testing ./"
     sudo add-apt-repository "deb http://repo.data.kit.edu/debian/buster ./"
     sudo add-apt-repository "deb http://repo.data.kit.edu/ubuntu/16.04 ./"
     sudo add-apt-repository "deb http://repo.data.kit.edu/ubuntu/xenial ./"
     sudo add-apt-repository "deb http://repo.data.kit.edu/ubuntu/18.04 ./"
     sudo add-apt-repository "deb http://repo.data.kit.edu/ubuntu/bionic ./"
     ````
 - install the `oidc-agent package:
     ````
     sudo apt-get update
     sudo apt-get install oidc-agent
     ````

The following video shows the installation steps on Ubuntu 16.04

[![asciicast](https://asciinema.org/a/j29geDDy5MkDBChRh90XMBrdd.svg)](https://asciinema.org/a/j29geDDy5MkDBChRh90XMBrdd)

## Step 2: configure oidc-agent

....

[![asciicast](https://asciinema.org/a/A8lR6N4VrBN2hbsD2Lz2qH3gs.svg)](https://asciinema.org/a/A8lR6N4VrBN2hbsD2Lz2qH3gs)


## Step 3: Install and configure orchent

....

[![asciicast](https://asciinema.org/a/YlylPeub6UzgAwVlU8VH183T8.svg)](https://asciinema.org/a/YlylPeub6UzgAwVlU8VH183T8)

