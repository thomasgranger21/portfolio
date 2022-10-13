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

### File Structure
- `_includes`: Parts of an HTML document that are separated for clarity or to aid reuse.
- `_layouts`: Repeated HTML structure used across several different pages.
- `_pages`: HTML content that is displayed for specific URLs.
- `_projects`: A Jekyll "collection" to hold HTML content for projects. Automatically output to pages.
- `assets`: Images, PDFs, files.
- `css`: CSS
- `js`: JS
- `index.html` The root HTML file. Displayed at `websitedomain.com`.
