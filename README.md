## Prevent the dock from moving to the bottom of a screen by accident
```bash
defaults write com.apple.Dock autohide-delay -float 5 && killall Dock
```
