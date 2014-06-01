aoj -- The Simple AOJ Submitter
============================

Installation
------------

* Clone this repository

    $ git clone https://github.com/okaoka/Acme-AOJ

* Install CPAN modules

```
    $ cpanm WebService::Simple  
    $ cpanm Config::Pit  
    $ cpanm YAML  
    ...  
```

* Copy aoj file to the bin directory

```
    $ mkdir -p $HOME/.aoj/bin  
    $ cp -p aoj $HOME/.aoj/bin  
```

* Open your .bashrc and edit $PATH like this 

```
    export PATH=$HOME/.aoj/bin:$PATH

```
* Then add EDITOR variable

```
    export EDITOR=emacs
```

* Update your .bashrc

```
    $ source ~/.bashrc
```

* Tell your Account to the Config::Pit

```
    $ ppit set aoj
```

* Then edit following variables
 * tabwidth ... being used when tab is converted into white space
 * user ... set your user id
 * password ... set your password
 * lang ... set your defalut languages

 * Example

```
    --- 
    "lang": 'C++'  
    "password": 'hogehogefugafuga'  
    "tabwidth": 8  
    "user": 'hogehoge'  
```

Usage
-----

See

    $ aoj --help
