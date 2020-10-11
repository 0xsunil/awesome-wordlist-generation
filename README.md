# Awesome Wordlist Generation Techniques

## One liners
```
amass intel -whois -d http://example.com |gau -subs | qsreplace -a |cut -d / -f4- |sort -u |tee wordlist.txt
```
Credits: [nullenc0de](https://twitter.com/nullenc0de)

```
echo "http://example.com" | waybackurls | cut -d "/" -f 4,5 | sed 's/?.*//' | sort -u 
```
Credits: [ofjaaah](https://twitter.com/ofjaaah)


## Tools
| No. | Tool Name | Creator(s) |
|-----|-----------|------------|
|1.| [getjswords.py](https://github.com/m4ll0k/Bug-Bounty-Toolz/blob/master/getjswords.py) | [m4ll0k2](https://twitter.com/m4ll0k2)|
|2.| [wordlist_generator](https://github.com/SomeKirill/wordlist_generator) | [SomeKirill](https://github.com/SomeKirill) |
|3.| [python-wordlist-generator](https://github.com/agusmakmun/python-wordlist-generator) | [agusmakmun](https://github.com/agusmakmun)|


## Talks/Videos
| No. |Title of Talk/Video | Credits |
| ----|--------------------| --------|
|1.| [Who, What, Where, When, Wordlist](https://www.youtube.com/watch?v=W4_QCSIujQ4) | [tomnomnom](https://twitter.com/TomNomNom) |
|2.| [Creating Wordlists for Hacking, Pentesting & Bug Bounty Hunting Using Seclists, Bigquery, and More!](https://www.youtube.com/watch?v=QGbTaxtEQlg) | [nahamsec](https://twitter.com/NahamSec) |
|3.| [Hunting for Javascript! (bug bounty, scripthunter, jsmon, getjswords, urltracker, wfuzz and more)](https://youtu.be/nkznsNxDM5k?t=120) | [stokfredrik](https://twitter.com/stokfredrik), [r0bre](https://twitter.com/r0bre), [m4ll0k2](https://twitter.com/m4ll0k2) |

