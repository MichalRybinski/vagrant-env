# vagrant-env

This repo holds sample vagrantfile(s), which allows to run initial dev env for specific project inside it. It's build over virtualbox.

1. Download VirtualBox 6.* & install it
2. Download Hashicorp Vagrant & install it
3. Run `mkdir vagrant_dir` (where vagrant shared folder and holder for vagrantfile will be placed)
4. Place the file in a directory just created and make sure you `cd` to that directory. Rename the file to 'Vagrantfile' and make it executable ( `sudo chmod +x Vagrantfile` )
5. Run `vagrant up`
6. Run `vagrant ssh`

Please refer to Vagrant documentation for more details.
