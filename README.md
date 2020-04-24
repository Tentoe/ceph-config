# cephadm config

- `sudo ./cephadm bootstrap -c ceph.conf --allow-overwrite --mon-ip 192.168.178.54 --skip-monitoring-stack`
- `sudo ./cephadm rm-daemon -n node-exporter.julia -fsid ... `

## Config

- `sudo ./cephadm shell ceph dashboard set-grafana-api-ssl-verify False`
- `ceph orch device ls --refresh`
- `ceph-volume lvm zap /dev/sdb --destroy`
- `ceph orch apply osd --all-available-devices`
