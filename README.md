# workspace-setup

`https://devhints.io/pacman`

Finding the Download Servers Mirror List By Country
```bash
sudo pacman-mirrors --country Iran
cat /etc/pacman.d/mirrorlist
sudo pacman -Syyu
```

gcc & make
```bash
sudo pacman -S base-devel
```

pip
```bash
sudo pacman -S python-pip
```

Fire up the Open SSH server
```bash
sudo pacman -S openssh
sudo systemctl start sshd
sudo systemctl status sshd
sudo systemctl enable sshd
```

ssh-copy-id
```bash
ssh-copy-id root@91.98.100.118
```

vscode
```json
"python.linting.pylintUseMinimalCheckers": false,
```

jupyter
```bash
python -m venv .env
pip install jupyter
jupyter notebook
ssh -L 8888:localhost:8888 your_server_username@your_server_ip
```

ex. tmux docker nginx vim
