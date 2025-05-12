# kubernetes2025

#for creation of images
1. docker build --progress=plain -t vnflask:0.1 . // --progres=plain gives detailed output include --no-cache if you want to do a fresh build of image
2. docker run -d -p 3006:80 vnflask:0.1 // any port can be used instead of 3006
