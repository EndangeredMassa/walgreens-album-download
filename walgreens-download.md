
# Download Walgreens Albumb

```js
all=[]; document.querySelectorAll('.assetImg').forEach(i => all.push(i.src)); all.join('\n');
```


```sh
sed -i 's/height=200/height=96/g' urls.txt

wget -i urls.txt --content-disposition 
```

Example Alubm: http://photo.walgreens.com/library/photos?website=walgreens_us&cobrand=walgreens&locale=en_US#state=%7B%22pgvw%22%3A%22swmsav%22%2C%22aid%22%3A40006183543060%2C%22oid%22%3A10546920%2C%22dc%22%3A%22SFO%22%7D
