# install

```bash
sudo apt install python3-pip # when no module named pip occard.
python3 -m pip install --user qmk
```

# setup 

```bash
echo 'PATH="$HOME/.local/bin:$PATH"' >> $HOME/.bashrc && source $HOME/.bashrc # ubuntu bag fix
qmk setup

qmk config user.keyboard=crkbd
qmk config user.keymap=noypeban
```

# update

```bash
qmk compile
qmk flash # wls2ではうまくいかなかったのでqmk toolboxを使った
```

