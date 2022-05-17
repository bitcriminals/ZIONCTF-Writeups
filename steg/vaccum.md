We were given a site with lyrics of a song and a submit button.First i thought we had to diff the lyrics in the site with the original song but it didn't work.Then, i realised that the chall name was vaccum which suggest towards whitespace steg  but for that we had to get the text file.Also, I saw some weird spacing in the file.So, after a bit of searching i found that that the original file used unicode steg which is a technique to hide zero width chars within words.So, used a online tool and got the hidden mssg.

**0nest3pcl0ser**


Submitted the hidden mssg in the website and it downloaded the song lyrics in a text file for me.Then, I used stegsnow and extracted the  flag
```
stegsnow  -C will_you_take_that_road.txt

```
**flag:zionctf{Wh1t3_spac3s_are_s0_fun_hsa7815gij}**