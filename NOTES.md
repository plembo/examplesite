# Create A Website for $12
Chris Stayte, on YouTube. Playlist:

https://www.youtube.com/playlist?list=PL-Kz5P-mYdMgAJDmRJquyMHfdaIOD-3oj

## Building a Website Using Hugo

https://youtu.be/c7vpcqA6SEQ

```bash
$ hugo new site mysite

$ cd mysite
```

Top-level structure will look like:

```bash
$ cd mysite
$ ls -l

archetypes
config.toml
content
data
layouts
resources
static themes
```

Chosen theme, [hugo-casper-two](https://github.com/eueung/hugo-casper-two), is no longer in [Hugo Themes](https://themes.gohugo.io/) but can still be downloaded from github.

```bash
$ pwd
mysite
$ git clone https://github.com/eueung/hugo-casper-two themes/casper-two
```
