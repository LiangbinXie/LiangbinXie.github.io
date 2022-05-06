# Home Page

[Home Page hosted on GitHub](https://LiangbinXie.github.io/) <br>
[GitHub](https://github.com/LiangbinXie/LiangbinXie.github.io)

## Caution

Should not be public!
There is an ssh private key in `.github/workflows/id_rsa` for records.

## Install

- jekyll

```bash
sudo apt-get install ruby-dev
sudo apt-get install ruby-full build-essential zlib1g-dev
sudo gem install jekyll
sudo gem install rouge
```

## Run jekyll

```bash
jekyll serve
```

## Publish

Only `pushing to GitHub` is required. <br>
Then,

1. GitHub action will automatically push to Gitee.
2. GitHub and Gitee pages will automatically build the sites.

### Acknowledgments

This repo is modified from [KordingLab.github.io](https://github.com/xinntao/KordingLab.github.io) for [Kording lab page](http://kordinglab.com/).
