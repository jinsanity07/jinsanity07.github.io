upzip a file in codespace terminal

```bash
sudo apt install unzip

unzip ./docs.zip -d ./ 
rm -r ./docs
mv dist docs
rm ./docs.zip
```