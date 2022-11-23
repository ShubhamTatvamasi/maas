# maas

Install Maas:
```bash
sudo snap install maas
sudo snap install maas-test-db
```

Initialize Maas:
```bash
sudo maas init region+rack --database-uri maas-test-db:///
```
