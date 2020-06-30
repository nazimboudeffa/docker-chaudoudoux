## Docker for Chaudoudoux Server

I use this repo for this build https://github.com/stefanvangastel/docker-cakephp

## Install

We are also working on the v1.0 with CakePHP and still with ubuntu/apache/php/mysql or simply xampp

First install https://docs.docker.com/toolbox/toolbox_install_windows/

Or go directly and install the latest https://github.com/docker/toolbox/releases

As my first HDD Drive is called C:/ and contain an SSD with only the Windows OS I Add `D:\Program Files\Docker` Toolbox to my Windows 10 PATH

Got to the folder and double click on `start` it will open a command shell

Clone the repo and tape in the terminal you get after start this command `docker build -t ubuntu/chaudoudoux .`

Once done run `docker run -d -p 80:80 ubuntu/chaudoudoux:latest`

Simply connect to the ip you find in Kitematic `http://192.168.99.100/`

You should obtain something like this https://retromatrix.tumblr.com/post/622355485200433152/how-to-run-chaudoudou-docker

![Do not touch my Chaudoudoux](https://media.giphy.com/media/iiahIfaRyM4qp8QNoX/giphy-downsized-large.gif)
