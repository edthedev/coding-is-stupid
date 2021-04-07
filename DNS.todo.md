
Working through this guide:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

Check status here:
https://github.com/edthedev/coding-is-stupid/settings

Then here:

Edward.delaporte.us is successful:

```bash
PS /mnt/c/Users/delaport> dig edward.delaporte.us +nostats +nocomments +nocmd

; <<>> DiG 9.11.5-P4-5.1+b1-Debian <<>> edward.delaporte.us +nostats +nocomments +nocmd
;; global options: +cmd
;edward.delaporte.us.           IN      A
edward.delaporte.us.    1798    IN      CNAME   edthedev.github.io.
edthedev.github.io.     3599    IN      A       185.199.108.153
edthedev.github.io.     3599    IN      A       185.199.109.153
edthedev.github.io.     3599    IN      A       185.199.110.153
edthedev.github.io.     3599    IN      A       185.199.111.153
```

book.edthe.dev is not.
```bash
PS /mnt/c/Users/delaport> dig book.edthe.dev +nostats +nocomments +nocmd
; <<>> DiG 9.11.5-P4-5.1+b1-Debian <<>> book.edthe.dev +nostats +nocomments +nocmd
;; global options: +cmd
;book.edthe.dev.                        IN      A
edthe.dev.              1579    IN      SOA     dns1.registrar-servers.com. hostmaster.registrar-servers.com. 1617731543 43200 3600 604800 3601
PS /mnt/c/Users/delaport>
```