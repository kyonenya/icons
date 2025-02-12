# icons

```
sudo apt update
sudo apt install librsvg2-bin
```

```
for file in $(find . -name "*.svg"); do
    rsvg-convert -o "${file%.svg}.png" "$file"
done
```

```
rsvg-convert -w 600 -h 600 -o quotation-pink-light-600.png quotation-pink-light.svg
```
