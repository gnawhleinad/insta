command-line interface for [instapaper.com]

[instapaper.com]: https://instapaper.com

### setup

```bash
$ pyenv install
$ pip install -r requirements.txt
```

### usage

command   | functionality
--------- | -------------
`send`    | send articles to kindle
`archive` | archive all articles

```bash
$ ./insta --username hodor --password Ho1dthed00r send && \
  ./insta --username hodor --password Ho1dthed00r archive
sent successfully!
archived successfully!
```
