# Salmiak
A very VERY simple tool to rename all files and folders so that they play nice with Plex.

## How to install
```
$ pip install salmiak
```
If you get a permissions error then run the following command instead
```
$ sudo -H pip install salmiak
```

## How to use?

```
$ python salmiak.py -h
usage: salmiak.py [-h] [-d] media

Rename files and folders to fit Plex

positional arguments:
  media         Where your mediafiles are

optional arguments:
  -h, --help    show this help message and exit
  -d, --dryrun  Print out the changes without actually doing them
```
