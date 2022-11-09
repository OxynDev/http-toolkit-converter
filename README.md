# HTTP TOOLKIT CONVENTER

Convert http toolkit string to python httpx request

![Logo](https://media.discordapp.net/attachments/1006892478361784390/1039992321342709861/fdgdgdfgdf.png?width=1438&height=671)
## Installation 

Install my-project with npm

```python
import htconv

res = htconv.ColventerHttp().convert("""METHOD: POST
URL
https://graphigo.prd.dlive.tv/
HEADERS
accept:
application/json
accept-encoding:
gzip
connection:
Keep-Alive
content-length:
418
content-type:
application/json; charset=utf-8
host:
graphigo.prd.dlive.tv
user-agent:
okhttp/4.9.2
x-apollo-cache-do-not-store:
false
x-apollo-cache-fetch-strategy:
NETWORK_ONLY
x-apollo-cache-key:
c246592c6b4efd023acdeba5e1dd3032
x-apollo-expire-after-read:
false
x-apollo-expire-timeout:
0
x-apollo-operation-id:
cb0be2578fe8f5192e35c3ff4069e8b6c8b0f117b788dc43f63a1465a2948a5c
x-apollo-operation-name:
IsBlockedRegion
x-apollo-prefetch:
false
x-dlive-mid:
00000000-2ac5-add0-ffff-ffffef05ac4a
x-dlive-mtype:
android
x-dlive-mversion:
1.16.44""")

print(res)
```
```
headers = {
    "accept:": "application/json",
    "accept-encoding:": "gzip",
    "connection:": "Keep-Alive",
    "content-length:": "418",
    "content-type:": "application/json; charset=utf-8",
    "host:": "graphigo.prd.dlive.tv",
    "user-agent:": "okhttp/4.9.2",
    "x-apollo-cache-do-not-store:": "false",
    "x-apollo-cache-fetch-strategy:": "NETWORK_ONLY",
    "x-apollo-cache-key:": "c246592c6b4efd023acdeba5e1dd3032",
    "x-apollo-expire-after-read:": "false",
    "x-apollo-expire-timeout:": "0",
    "x-apollo-operation-id:": "cb0be2578fe8f5192e35c3ff4069e8b6c8b0f117b788dc43f63a1465a2948a5c",
    "x-apollo-operation-name:": "IsBlockedRegion",
    "x-apollo-prefetch:": "false",
    "x-dlive-mid:": "00000000-2ac5-add0-ffff-ffffef05ac4a",
    "x-dlive-mtype:": "android",
    "x-dlive-mversion:": "1.16.44"
}
httpx.post('https://graphigo.prd.dlive.tv/',headers=headers)
