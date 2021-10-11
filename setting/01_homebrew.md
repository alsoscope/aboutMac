20211011

01_homebrew


------
homebrew 설치


맥 big sur 는 기본 zsh 터미널
cd /opt
sudo mkdir homebrew

//root 권한 설정
sudo chown -R $ 유저명 /opt/homebrew
cd homebrew

obassamba@hope-MacBookAir homebrew % /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
Warning: The Ruby Homebrew installer is now deprecated and has been rewritten in
Bash. Please migrate to the following command:
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

==> Installation successful!

==> Next steps:
- Run these two commands in your terminal to add Homebrew to your PATH:
    echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/obassamba/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"
- Run `brew help` to get started’

Brew -h

설치완료

기본 zsh 외의 부가기능 사용은 iTerm2 및 oh My ZSH 설치

ref https://medium.com/harrythegreat/oh-my-zsh-iterm2로-터미널을-더-강력하게-a105f2c01bec
ref https://gist.github.com/nrubin29/bea5aa83e8dfa91370fe83b62dad6dfa
