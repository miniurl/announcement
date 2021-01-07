# announcement
Announcement for Miniurl.id website

[Miniurl.id](https://miniurl.id) website is serving as URL shortening website since July 1st 2020. Our hosting has suspended twice because of [some visitors](https://github.com/miniurl/IPs#ips) submitted [phishing and dangerous URLs](https://github.com/miniurl/hosts#hosts). We have used these several domain to prevent further suspension:

- rl.rf.gd (Suspended)
- iurl.rf.gd (Suspended)
- mnurl.xyz (Suspended)
- mrl.6te.net

We have decided to use third party URL shortening service such as [is.gd](https://github.com/miniurl/is.gd-api) and [v.gd](https://github.com/miniurl/v.gd-api). We are considering to shutdown the service. MiniURLs that are shortened before November 14th 2020 12:00 UTC can be accessed by 'miniurl.id' domain and 'mrl.6te.net' domain and MiniURLs that are shortened after that time only can be accessed by 'mrl.6te.net' domain. You can get the unshortened URl using '[https://preview.miniurl.id/{SHORTENED_URL}](https://preview.miniurl.id/)', for example [https://preview.miniurl.id/github](https://preview.miniurl.id/github).

## Contact Me
- [info@miniurl.id](mailto:info@miniurl.id)
- [@miniurl@mstdn.io](https://mstdn.io/web/accounts/635422) > Three dots icon > Direct message @miniurl

## Secure Communication
[PGP Public Key](https://raw.githubusercontent.com/miniurl/announcement/main/pgpkey.txt)
```
gpg --keyserver pgp.ocf.berkeley.edu --recv-key 55631D36DCE666A27E430520F98B070C74C4AC68
```
or
```
curl -sf https://raw.githubusercontent.com/miniurl/announcement/main/pgpkey.txt | gpg --import
```
