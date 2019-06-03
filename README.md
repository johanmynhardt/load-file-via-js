# load-file-via-js
Example to load file via JS.

Generate Certificate
====

```
~/example $ openssl req -new -x509 -keyout server.pem -out server.pem -days 365 -nodes
```


Serve via python:
====

```
~/example $ SERVER_IP=<ip-on-local-network>; python ./simple-https-server.py

```


Open browser
====

```
~/example $ open https://<ip-on-local-network>:4443
```
