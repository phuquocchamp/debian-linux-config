# Oh my zsh.

<p align="center"><img src="https://s3.amazonaws.com/ohmyzsh/oh-my-zsh-logo.png" alt="Oh My Zsh"></p>

## Cài đặt ZSH.

```bash
sudo apt install zsh
```

> Phải cài đăt zsh trước khi cài framework ohmyzsh.

## Cài đặt Oh my ZSH.

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Cài đặt plugins.

**autosuggesions plugin**

```bash
  git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
```

**zsh-syntax-highlighting plugin**

```bash
  git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```

**zsh-fast-syntax-highlighting plugin**

```bash
  git clone https://github.com/zdharma-continuum/fast-syntax-highlighting.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/plugins/fast-syntax-highlighting
```

**zsh-autocomplete plugin**

```bash
  git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git $ZSH_CUSTOM/plugins/zsh-autocomplete
```

## Thêm các plugin vào file config của zsh --> .zshrc

**1. Mở .zshrc**

```bash
  nvim ~/.zshrc
```

**2. Tìm đến dòng bắt đầu bằng**

```bash
  plugins=(git)
```

**3.Thay thế dòng trên bằng dòng dưới đây**

```bash
  plugins=(git zsh-autosuggestions zsh-syntax-highlighting fast-syntax-highlighting zsh-autocomplete)
```

## References

- [Oh my ZSH](https://github.com/ohmyzsh/ohmyzsh)
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
- [zsh-fast-syntax-highlighting](https://github.com/zdharma/fast-syntax-highlighting)
- [zsh-autocomplete](https://github.com/marlonrichert/zsh-autocomplete)
