# vscode_chromebook

# Download and install code-server
## 1 Download the latest release 
https://github.com/coder/code-server/releases/
```
wget -v https://github.com/coder/code-server/releases/download/v4.9.1/code-server_4.9.1_amd64.deb
```

## 2 Install
```
sudo apt install ./code-server_4.9.1_amd64.deb
```

## 3 Remove .deb
```
rm code-server_4.9.1_amd64.deb
```

# Run code-server
```
code-server
```

The Chrome navigator will ask by a password, but it can obtained with
```
more ~/.config/code-server/config.yaml
```

To improve usability (remove address and navigation bars), "install" the code-server page by pressing the install icon on Chrome browser!

# References
[Making VSCode run faster on Chromebooks](https://medium.com/samsung-internet-dev/making-vscode-run-faster-on-chromebooks-1591ee5e885b)