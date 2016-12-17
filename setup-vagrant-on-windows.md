# Setting up vagrant on windows

## install software
```
gitbash from git-src
virtual box
vagrant
```

## set work dir
```

# store vagrant machines
mkdir /I/vagrant

# store box file, big files
mkdir /I/vagrant/boxes

```


## init one machine
```
$ mkdir -p /I/vagrant/precise64
$ cd /I/vagrant/precise64


# this command download a box precise64 file, it's too slow, 
#so we ctrl+c and grab the url download it use download tools
$ vagrant init hashicorp/precise64
```

## download box file
```
https://atlas.hashicorp.com/hashicorp/boxes/precise64/versions/1.1.0/providers/virtualbox.box

# change name
mv virtualbox.box /I/vagrant/boxes/hashicorp-precise64-virtualbox.box
```

## add the downloaded box file to local repo
```
git-bash$ vagrant.exe box add hashicorp/precise64 /I/vagrant/boxes/hashicorp-precise64-virtualbox.box

```


## start first machine
```
$ vagrant.exe up
```

## connect into the vm 
```
$vargant.exe ssh
```


