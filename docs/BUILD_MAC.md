
# Install, Build and Run for MacOS

## Local Install

#### 1. Install Homebrew - package manager for macOS.

See [official manual](https://brew.sh/) or run command

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

#### 2. Install Jekyll - static site generator.

See [official manual](https://jekyllrb.com/docs/installation/macos/) or run commands

```
brew install chruby ruby-install xz
ruby-install ruby 3.1.3
```

This will take a few minutes, and once it’s done, configure your shell to automatically use `chruby`:

```
echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
echo "chruby ruby-3.1.3" >> ~/.zshrc # run 'chruby' to see actual version
```

If you’re using Bash, replace `.zshrc` with `.bash_profile`. If you’re not sure, read this external guide to [find out which shell you’re using](https://www.moncefbelyamani.com/which-shell-am-i-using-how-can-i-switch/) or run command

```
echo $0
```

re-run terminal, install Jekyll and Bundler

```
gem install jekyll bundler
```


#### 3. Install ImageMagick - tool for editing and manipulating digital images.

```
brew install imagemagick
```

## Local Build and Run

#### 1. Go to local folder.

```
cd ~/Repos/Hermes/
```

#### 2. Install gems.

```
bundle install
```

#### 3. Build the site and make it available on a local server.

```
bundle exec jekyll serve
```

Or pass the `--livereload` option to `serve` to automatically refresh the page with each change you make to the source files:

```
bundle exec jekyll serve --livereload
```

#### 4. Browse to localhost

http://localhost:4000
