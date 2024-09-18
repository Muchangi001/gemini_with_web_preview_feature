  # Overview
A bash script that adds web preview feature for the log file of the gemini program.

# Dependencies
gemini program
mdview program for linux
- Installing mdview using snapd : <br>
`bash`
```
git clone https://aur.archlinux.org/snapd.git
cd snapd
makepkg -si
```

```
sudo systemctl enable --now snapd.socket
```

```
sudo systemctl enable --now snapd.apparmor.service
```

```
sudo ln -s /var/lib/snapd/snap /snap
```
