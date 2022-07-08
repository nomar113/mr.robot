Rio Card Mais

Mifare Classic 4K

Know keys:

- a170d9b59f95
- ff58ba1b4478
- de1fcbec764b
- 81bfbe8cacba
- 3248d5345267

![Rio Card Mais keys](https://github.com/nomar113/mr.robot/blob/master/rio-card-mais/riocard.png)

Run on Linux:

```sh
sudo rmmod pn533
sudo rmmod pn533_usb

mfoc -P 500 -f riocard-keys -O original.dmp
```