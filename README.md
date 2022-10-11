# Thomas Granger's Portfolio
## About
*Todo*

## Development
### Installation (Mac)
Install homebrew:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Install rbenv:
```
brew install rbenv
```

Load rbenv by default:
```
echo 'eval "$(rbenv init -)"' >> ~/.zshrc
```

Open a new terminal window, then run:
```
rbenv install 3.1.2

rbenv global 3.1.2
```

Then, install bundler:
```
gem install bundler
```

Then, in the repository folder, run:
```
bundle
```
### Development
To start the dev server, run:
```
bundle exec jekyll serve --livereload
```

Then, you can visit the dev site at `localhost:4000`.
