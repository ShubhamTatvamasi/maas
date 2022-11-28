# openstack

https://charmhub.io/openstack-base

Setup MAAS:
```bash
sudo snap install maas-test-db
sudo snap install maas --channel=3.1/stable
sudo maas init region+rack --maas-url http://10.0.0.2:5240/MAAS --database-uri maas-test-db:///
sudo maas createadmin --username admin --password ubuntu --email admin@example.com --ssh-import lp:shubhamtatvamasi
sudo maas apikey --username admin > ~ubuntu/admin-api-key
```
