# my-mp3-tags-writer

### Tagy mojich pesniciek
```
svarozic@SVAROG:/mnt/c/Users/Svarozic/Desktop/test$ mid3v2 -l B.R.O\ -\ Mówiła\ mi.mp3
IDv2 tag info for B.R.O - Mówiła mi.mp3
APIC=cover front, B.R.O - Mówiła mi.jpg (image/jpeg, 118617 bytes)
TALB=SVAROG
TIT2=Mówiła mi
TPE1=B.R.O
TPE2=B.R.O - Mówiła mi
TYER=2018
```


### Bash way 
- `sudo apt-get install python-mutagen`
- `mid3v2 -a "ARTIST2" -A "ALBUM" -t "TITLE2" -g "GENRE" -y 1111 --TPE2 "TPE2" -p "Jala Brat - O kako ne bi.jpg" Jala\ Brat\ -\ O\ kako\ ne\ bi.mp3`


### Java way
- https://github.com/mpatric/mp3agic