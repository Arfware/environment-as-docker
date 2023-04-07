# Jenkins


## Troubleshooting


### Write Permission Error
If you got persistence volume writing rights error:

1. Navigate mapped volume in terminal:
```sh
cd /var/docker_volumes/ci_cd/jenkins/home
```

2. Change directory owner
```sh
chown -R 1000:1000 .
```