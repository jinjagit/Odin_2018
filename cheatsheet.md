|                                command                                 |                           description                         |
|------------------------------------------------------------------------|---------------------------------------------------------------|
| UNIX and LINUX commands:                                               |                                                               |
| ls -a                                                                  | list files, including hidden                                  |
| ls -lhs                                                                | list files, human-readable filesizes, sorted by size          |
| ln a.txt b.txt                                                         | hard link source file(a) to a newly created file (b)          |
| ln -f a.txt b.txt                                                      | force link when b,txt already exists                          |
| ln -s a.txt b.txt                                                      | create symbolic link                                          |
| mkdir -p a/b/c                                                         | make nested directories                                       |
| cp a.txt b.txt foo                                                     | copy multiple files to directory 'foo'                        |
| cp -Rv foo bar                                                         | copy contents of directory 'foo' to directory 'bar' (verbose) |
| cp -f a.txt b.txt                                                      | force overwrite of b with a                                   |
| cp -i a.txt b.txt                                                      | confirm each overwrite                                        |
| rm -v a.txt                                                            | delete a.txt (verbose)                                        |
| mv -v a.txt b.txt                                                      | move file (verbose)                                           |
| ls -a ~ ║ grep _                                                       | pipe output of ls -a ~ to grep (finds files containing '_')   |
| ls -a ~ ║ grep _ ║ sed "s/__/-/g"                                       | as above + replace all '_' to '-'                             |
| testing git commit | zzz |








