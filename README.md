# Delete AWS Route53 Hosted Zones

Bulk delete Route 53 hosted zone with all contained Record Sets

### usage :

1. Delete records for all domain in a file
```
aws-route-delete -f domain_list.txt         
````

2. Delete domain/s as parameter
```
aws-route-delete -p example.com example2.com
```

#### for verbose output
```
aws-route-delete -vf domain_list.txt
aws-route-delete -vp example.com example2.com 
```


[originally written at](https://sookocheff.com/post/bash/parsing-bash-script-arguments-with-shopts/)