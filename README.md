# icons

```
sudo apt update
sudo apt install imagemagick
```

```
for file in $(find . -name "*.svg"); do
    convert "$file" "${file%.svg}.png"
done
```
