upzip a file in codespace terminal

```bash
sudo apt install unzip

unzip ./dist.zip -d ./ 
rm -r ./docs
mv dist docs
rm ./dist.zip
```