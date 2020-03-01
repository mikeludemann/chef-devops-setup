# chef-devops-setup

A tutorial and example with 'Chef'

## Checklist - Example

```
docker-compose pull

docker-compose up -d

docker exec -it workstation bash

chef-run web1 file hello.txt

ssh web1 cat /hello.txt

ssh web1 ls -l /hello.txt

chef-run web1 file hello.txt content='Hello World!'

ssh web1 cat /hello.txt

chef-run web1 file hello.txt action=delete

ssh web1 cat /hello.txt

...
```

## To be defined and should be complete next time