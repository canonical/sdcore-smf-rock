# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-smf_2.0.2_amd64.rock docker-daemon:sdcore-smf:2.0.2
docker run sdcore-smf:2.0.2
```
