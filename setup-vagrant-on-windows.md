# Setting up vagrant on windows

## install software
```
gitbash
virtual
vagrant
```

## set work dir
```

# store vagrant machines
mkdir /I/vagrant

# store box file, big files
mkdir /I/vagrant/boxes

```

## download box file
hashicorp/precise64

## add box file
```
git-bash$ vagrant.exe box add hashicorp/precise64 /I/vagrant/boxes/hashicorp-precise64-virtualbox.box

```

## start first machine
```
$ cd /I/vagrant/precise64
$ vagrant.exe up
```

## connect into the vm 
```
$vargant.exe ssh
```


