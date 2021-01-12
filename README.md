# phrenamer - A photo renaming utility

phrenamer is a very simple POSIX shell script that renames all JPEG files in a 
given directory into a numbered list, adding leading zeroes where needed (i.e.,
'01.jpg', '02.jpg', ..., '99.jpg').

## Usage

phrenamer accepts this syntax:

```
$ phrenamer [-d] [DIR]
```

The DIR argument refers to a directory path where the files to be renamed are 
located. If none is given, phrenamer will operate on the current working 
directory.

phrenamer will look for files with the following extensions: .jpg, .JPG, .jpeg.
It always changes the extension to .jpg.

Use the -d option for a dry run that will *not* rename your files. 

## License

phrenamer is published under an MIT/X11/Expat-type License. See LICENSE file 
for copyright and license details.
