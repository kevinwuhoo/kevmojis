Fetched from http://doge2048.com/img/212/ using wget, resized using gifsicle,
and renamed manually.

```bash
wget -r -nH -nd -np -R index.html* http://doge2048.com/img/212/
gifsicle --resize 128x128 --batch doge-*.gif
```
`
