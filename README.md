# subutai-goofys

## Subutai Blueprint which mounts directroty to S3 storage

```shell

wget https://github.com/kahing/goofys/releases/latest/download/goofys

cat ~/.aws/credentials

[default]
aws_access_key_id = accessKey     
aws_secret_access_key = secretKey 

mkdir /mnt/mountpoint

./goofys --endpoint=http://minio5.envs.subut.ai:8080 my1 /mnt/mountpoint

```
