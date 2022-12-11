# pippackages

```
pip install flask 
pip install ravenrpc
pip install ipfshttpclient==0.8.0a2
pip install flask-pagination
pip install pyrebase
pip install pymongo[srv]
pip list --outdated --format=freeze | grep -v '^\-e' | cut -d = -f 1 | xargs -n1 pip3 install -U
```
