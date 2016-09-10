# CodeIgniter 3 Scaffold

Simple scaffold generator for codeigniter 3.1.0 now using Twitter Bootstrap templates!

## Instalation

This scaffold is a gem of Ruby, then you need to have Ruby installed on your machine.

See the following command sequence to install this gem:

```
gem install rubyzip
gem install codeigniter3-scaffold
```

## Usage

    codeigniter3-scaffold [options...]
      -h, --help show this help
      -i, --init unzip a codeigniter 3.1.0 installation in the current dir
      -s, --scaffold <model-name> field1:string field2:text field3:integer, and so on..


## Pre-setup

* After running 'codeigniter3-scaffold --init':
  * Open 'application/config/config.php' and set-up the 'base_url' property;
  * Open 'application/config/database.php' and set-up your database settings;

* After running 'codeigniter3-scaffold --scaffold [options...]'
  * Go to 'application/migrations' and run the generated script into your database;


* Have fun =)


## Copyright

Copyright (c) 2016 universidadecodeigniter.
