# My nvim config

## How to install

1. Clone AstroVim

```
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
```

2. Clone this repo to /lua/user

```
git clone https://github.com/jfetero/astronvim_config.git ~/.config/nvim/lua/user
```

3. Start AstroVim

```
nvim  --headless -c 'autocmd User PackerComplete quitall' -c 'PackerSync'
```
