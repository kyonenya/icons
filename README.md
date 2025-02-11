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
