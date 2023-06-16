# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-smf_1.3_amd64.rock docker-daemon:sdcore-smf:1.3
docker run sdcore-smf:1.3
```