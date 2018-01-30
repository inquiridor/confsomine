# confsomine
All configs I need for my personal use.

## ~/emacs.files:

* **.spacemacs** 
	  
  spacemacs personal config

* **RUN THIS COMMAND TO INSTALL EMACS DEPENDENCIES AND TO CONFIGURE IT**
	
  $ sudo apt install libgif-dev libtiff-dev libjpeg-dev libxpm-dev libgnutls-dev libpng-dev libncurses-dev libgtk-3-dev libwebkitgtk-3.0-dev xinit xorg-server-source xserver-xorg build-essential texinfo libx11-dev libxpm-dev libjpeg-dev libpng-dev libgif-dev libtiff-dev libgtk2.0-dev libncurses-dev libxpm-dev automake autoconf
	
  $ ./configure --with-xwidgets --with-x-toolkit=gtk3

## ~/jupy.files:

* **.jupyter_notebook_config.py**

  jupyter notebook's personal config

* **RUN THIS COMMAND AND COPY THE .py FILE TO .jupyter**
	
  $ jupyter notebook --generate-config

## Personal Needed Software

* **Postgress in Debian distros**

  $ sudo apt-get install postgresql postgresql-contrib libpq-dev

* **Redis in Debian distros**

  $ sudo apt-getupdate
  $ sudo apt-getinstallbuild-essential tcl

  cd /tmp

  curl -O http://download.redis.io/redis-stable.tar.gz

  tar xzvf redis-stable.tar.gz
  cd redis-stable
  make
  sudo make install

* **ANSIBLE**
  [Ansible](https://www.ansible.com/)

* **VAGRANT**
  [Vagrant](https://www.vagrantup.com/)

* **NodeJS installation via binary archive**
  [NodeJS](https://github.com/nodejs/help/wiki/Installation)

* **Flash Player**
  $ sudo apt install pepperflashplugin-nonfree

* **ALSAMIXER: volume controller**
  $ alsamixer
  
* **ARandR: multimonitors**
  $ sudo apt install arandr
