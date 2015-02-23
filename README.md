#Vagrant blog tutorial

Repository to illustrate [How to use Vagrant for local web development](http://blog.osteel.me/posts/2015/01/25/how-to-use-vagrant-for-local-web-development.html "How to use Vagrant for local web development").

##Get it running

Clone the project:

    git clone git@github.com:osteel/vagrant-blog-tutorial.git

Download VirtualBox at [https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads "VirtualBox - Downloads") (*"platform packages"*) and install it.  
Download Vagrant at [https://www.vagrantup.com/downloads.html](https://www.vagrantup.com/downloads.html "Vagrant - Downloads") and install it.

From the project root, run:

    vagrant up

Edit the `hosts` file of your machine, add:

    192.168.68.8    vagrant-test.local.com

Open your browser and visit http://vagrant-test.local.com


For the full tutorial, please visit [How to use Vagrant for local web development](http://blog.osteel.me/posts/2015/01/25/how-to-use-vagrant-for-local-web-development.html "How to use Vagrant for local web development").