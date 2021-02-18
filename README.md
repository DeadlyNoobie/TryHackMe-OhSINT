# OhSINT

## tryhackme

### [ohsint](https://tryhackme.com/room/ohsint)

**Download the jpg Don't try to open it right away. Always keep this in mind.**

**Let's start with strings**

```
strings image.jpg
```

```
binwalk -e image.jpg
```

```
steghide extract -sf image.jpg
```

```
exiftool image.jpg
```

**Let us start with a google image search and we don't find anything about image more than we know already so we execute above commands**

**with exiftool we find very interesting info**

**we found out it's location**

**Next intersting thing we found out is Copyright**

**We google for copyright and we get more info about it.**

![]()

**We see here his blog his twitter and his github we get into all three to get some information from each**


What is this users avatar of?

![]()

```
Take a look at his twitter
```

What city is this person in?

```
Take a look at his github
```

Whats the SSID of the WAP he connected to?

```
On his twitter bssid is posted so search for this on wigle.net
```

What is his personal email address?


What site did you find his email address on?

Where has he gone on holiday?

```
Above three questions you can refer to the sites we already know.
```

What is this persons password?

```
Peek into Source code of his blog
```
