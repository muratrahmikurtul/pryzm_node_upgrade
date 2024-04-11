```
  cd $HOME
  wget https://storage.googleapis.com/pryzm-zone/core/0.13.0/pryzmd-0.13.0-linux-amd64
  sudo mv pryzmd-0.13.0-linux-amd64 pryzmd
  sudo chmod +x pryzmd
  
  mkdir -p $HOME/.pryzm/cosmovisor/upgrades/v0.13/bin
  mv pryzmd $HOME/.pryzm/cosmovisor/upgrades/v0.13/bin/
  rm -rf build
```
