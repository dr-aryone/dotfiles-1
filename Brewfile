cask_args appdir: "~/Applications"

tap 'homebrew/versions'
tap 'thoughtbot/formulae'

# Install GNU core utilities (those that come with macOS are outdated).
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
brew 'coreutils'
brew 'gnu-sed', args: ['--with-default-names']
brew 'grep', args: ['--with-default-names']

# Install some other useful utilities like `sponge`.
brew 'moreutils'
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed.
brew 'findutils'
# Install GNU `sed`, overwriting the built-in `sed`.
brew 'gnu-sed', args: ['--with-default-names']
# Install Bash 4.
# running `chsh`.
brew 'bash'

brew 'bash-completion2'

# Install `wget` with IRI support.
brew 'wget', args: ['--with-iri']

# Install more recent versions of some macOS tools.
brew 'grep'
brew 'openssh'
brew 'screen'

# Install other useful binaries.
brew 'ack'
brew 'dark-mode'
brew 'git'

brew 'gitsh'
brew 'hub'
brew 'git-lfs'
brew 'imagemagick', args: ['--with-webp']
brew 'lua'
brew 'p7zip'
brew 'pigz'
brew 'webkit2png'
brew 'autojump'
brew 'rbenv'
brew 'pyenv'
brew 'tree'
brew 'tig'
brew 'pgcli'
brew 'ffmpeg'
brew 'awscli'
brew 'direnv'
brew 'bat'

tap 'burntsushi/ripgrep', 'https://github.com/BurntSushi/ripgrep.git'
brew 'ripgrep-bin'

# GNU Calendar to replace cal
brew 'gcal'

# FZF
brew 'fzf'

# Fun Stuff with No Purpose
brew 'asciinema'
brew 'blink1'
brew 'cowsay'
brew 'figlet'
brew 'fortune'
brew 'no-more-secrets'
brew 'watch'

brew 'exercism'
brew 'heroku'

# Tmux
brew 'tmux'
brew 'reattach-to-user-namespace'
brew 'rainbarf'

# Security/Yubikey Stuff
brew 'gpg'
brew 'gpg-agent'
brew 'pinentry-mac'

# Vim Stuff
brew 'nvim'
brew 'ctags'
brew 'editorconfig'
tap 'ValeLint/vale'
brew 'vale'

# TLDR Man Pages
brew 'tldr'

brew 'chromedriver'

cask 'pencil'
cask 'paintbrush'
cask 'dash'
cask 'alfred'
cask 'moom'
cask 'vlc'

# Install Hack Nerd Font
tap 'caskroom/fonts'
cask 'font-hack-nerd-font'
