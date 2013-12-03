backuper
========

Backup your stuff to s3 through this nice ruby interface

## Installation

```bash
git clone git@github.com:davidjairala/backuper.git
cd backuper
gem install aws-sdk
```

Then setup a config based on config.example.yml and name it config.yml.

## Usage

### List your objects:

```bash
./bu list
```

### Backup some folders:

```bash
./bu backup ~/Dropbox/ ~/Pictures/
```

### Delete an object

```bash
./bu delete object_key
```
