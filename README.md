# set-conf-via-ssh
A small bash script to configure a list of nodes via ssh

## address list
Edit [address-list](https://github.com/riconem/set-conf-via-ssh/blob/master/address-list) you want to connect with.

## commands
Edit [commands](https://github.com/riconem/set-conf-via-ssh/blob/master/commands) to add your commands you want to run.

Example: Cisco commands
```
sh run
conf t
do sh ip int brief
end
```
Example: Linux commands
```
cd
ls -a
```
## ssh settings
Configure your ssh settings in [set-conf-via-ssh](https://github.com/riconem/set-conf-via-ssh/blob/master/set-conf-via-ssh)

## execute
```
./set-conf-via-ssh
```
