# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-smf_1.4.2_amd64.rock docker-daemon:sdcore-smf:1.4.2
docker run sdcore-smf:1.4.2
```