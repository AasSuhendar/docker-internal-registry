# Internal Docker Registry


Generate Certs using command line bellow
```
openssl req \
  -newkey rsa:4096 -nodes -sha256 -keyout certs/domain.key \
  -x509 -days 365 -out certs/domain.crt
```