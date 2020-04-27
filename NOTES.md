# Notes

## switch between projects

case:

```
Error from server (Forbidden): pods is forbidden: User "arturictus@gmail.com" cannot list resource "pods" in API group "" in the namespace "kafka": No policy matched.
Required "container.pods.list" permission.
```

I switched config but kube user does not change

```
gcc
[compute]
region = europe-west1
zone = europe-west1-d
[core]
account = apanach@meetsam.io
disable_usage_reporting = false
project = janus-156310

Your active configuration is: [default]
```
