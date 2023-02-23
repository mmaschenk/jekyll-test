To develop the site do the following:

### One time setup

Run these commands once per system where you develop (requires root access)

```
% sudo apt install ruby ruby-dev
% sudo gem install jekyll bundler
```

### Repo installation setup

Set the following environment variable (you may want to add this line to the end of your ~/.bashrc file):

```
export BUNDLE_PATH=~/.gems
```

Run this command after cloning this project to local disk:

```
% bundle install
```

### Jekyll server start

Run this command to run jekyll while you edit the content files. It will output the URL where you can view the resulting website:

```
bundle exec jekyll serve --config _config.yml,
_config_dev.yml
```
