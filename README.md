# bk
An easy backup utility.

Lets you archive a file or folder without having to
- remember `tar` or `zip` flags
- find a name like `foo2` or `foo (copy 1)`  
- go up the file system to archive current folder

### EXAMPLES

Basic  
`$> bk file.py`  
`$> saved to file_2020-06-05-12-13.py`

Compress  
`$> bk -z file.py`  
`$> saved to file_2020-06-05-12-13.py.zip`  
Or simply  
`$> bkz file.py`  

Archive current folder  
`$/dir> bk .`  
`saved to ../dir_2020-06-05-12-28`
