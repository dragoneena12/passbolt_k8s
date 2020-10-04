# passbolt_k8s

## admin
```
kubectl -n passbolt exec -it passbolt-844658658d-m4drp -- su -m -c "/var/www/passbolt/bin/cake passbolt register_user -u your@email.com -f yourname -l surname -r admin" -s /bin/sh www-data
```
