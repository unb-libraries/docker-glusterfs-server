# unblibraries/glusterfs-server
Docker container : Our standard glusterfs storage server. Persistent storage required.

## Usage
```
docker run \
       --rm \
       --name glusterfs-server \
       -v /gluster-bricks
       unblibraries/glusterfs-server
```

## License
- unblibraries/glusterfs-server is licensed under the MIT License:
  - http://opensource.org/licenses/mit-license.html
- Attribution is not required, but much appreciated:
  - `Gluster storage server by UNB Libraries`
