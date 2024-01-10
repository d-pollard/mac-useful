## Prevent the dock from moving to the bottom of a screen by accident
```shell
$ defaults write com.apple.Dock autohide-delay -float 5 && killall Dock
```
## Clear the DNS cache
```shell
$ sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder
```
