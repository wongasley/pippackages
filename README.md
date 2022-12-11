# pippackages

```
pip3 install flask 
pip3 install ravenrpc
pip3 install ipfshttpclient==0.8.0a2
pip3 install flask-pagination
pip3 install pyrebase
pip3 install pymongo[srv]
pip3 list --outdated --format=freeze | grep -v '^\-e' | cut -d = -f 1 | xargs -n1 pip3 install -U
```
