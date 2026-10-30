a gentoo overlay that fixes spotify

```
doas emerge --ask app-eselect/eselect-repository dev-vcs/git
```
```
doas eselect repository add local-overlay git https://github.com/dmel6/local-overlay.git
```
```
doas emerge --sync local-overlay
```
