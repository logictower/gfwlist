## This is fork from [gfwlist](https://github.com/gfwlist/gfwlist) edit for my personal use

file gfwlist.txt is base64 compressed file  

```
# use following comand to decompress 
openssl base64 -d -in gfwlist.txt -out list.txt
# update list.txt
# use following comand to compressed
openssl base64 -in list.txt | tr -d '\r' > gfwlist_v2.txt 
```
