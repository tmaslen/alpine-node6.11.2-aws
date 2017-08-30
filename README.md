# alpine-node6.11.2-aws

Docker image based on Alpine with Node 6.11.2, NPM 3.10.10 and AWS-CLI 1.11.142.

```console
$ docker run --rm tmaslen/alpine-node6.11.2-aws aws --version
aws-cli/1.11.142 Python/2.7.12 Linux/4.9.41-moby botocore/1.7.0

$ docker run --rm tmaslen/alpine-node6.11.2-aws node -v
v6.11.2

$ docker run --rm tmaslen/alpine-node6.11.2-aws npm -v
3.10.10
```