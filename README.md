# agrox
a web enum python module

### fuzzing Example 
```python
from argox.argo import Argo

argo = Argo("https://github.com/PUFF")
data = argo.fuzzer()
print(data)

```
### Install
* pip install AGROX

### Dns Enum Example 
```python
from argox.argo import Argo

argo = Argo(url)
print(argo.DnsEnum())
```

### portscan Example 
```python
from argox.argo import Argo

def scan(host,url):
    argo = Argo(url)
    return argo.scanport(host,debug=False)

host = input("Enter host ip")
url = input("Enter host url")
print(scan(host,url))

```
