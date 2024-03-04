2024-03-04 14:41:15,747 7f060d5f3000 INFO Non-zero exit code 22 from /usr/bin/docker run --rm --ipc=host --stop-signal=SIGTERM --ulimit nofile=1048576 --
net=host --entrypoint /usr/bin/ceph --init -e CONTAINER_IMAGE=quay.io/ceph/ceph:v18 -e NODE_NAME=n1 -e CEPH_USE_RANDOM_NONCE=1 -v /var/log/ceph/1748dfa2-
da35-11ee-9c13-1ba219ca3d2f:/var/log/ceph:z -v /tmp/ceph-tmpheap3mz4:/etc/ceph/ceph.client.admin.keyring:z -v /tmp/ceph-tmp53xf5m9x:/etc/ceph/ceph.conf:z
 quay.io/ceph/ceph:v18 orch host add n1 192.168.1.173
2024-03-04 14:41:15,747 7f060d5f3000 INFO /usr/bin/ceph: stderr Error EINVAL: check-host failed:
2024-03-04 14:41:15,748 7f060d5f3000 INFO /usr/bin/ceph: stderr /usr/bin/python3: can't open file '/var/lib/ceph/1748dfa2-da35-11ee-9c13-1ba219ca3d2f/cep
hadm.8c89112927b45a1984d03fb02785df709234bdb856619c217e1ad5d54aebef2b': [Errno 2] No such file or directory
2024-03-04 14:41:15,749 7f060d5f3000 ERROR Error: Failed to add host <n1>: Failed command: /usr/bin/docker run --rm --ipc=host --stop-signal=SIGTERM --ul
imit nofile=1048576 --net=host --entrypoint /usr/bin/ceph --init -e CONTAINER_IMAGE=quay.io/ceph/ceph:v18 -e NODE_NAME=n1 -e CEPH_USE_RANDOM_NONCE=1 -v /var/log/ceph/1748dfa2-da35-11ee-9c13-1ba219ca3d2f:/var/log/ceph:z -v /tmp/ceph-tmpheap3mz4:/etc/ceph/ceph.client.admin.keyring:z -v /tmp/ceph-tmp53xf5m9x:/etc/ceph/ceph.conf:z quay.io/ceph/ceph:v18 orch host add n1 192.168.1.173: Error EINVAL: check-host failed:
/usr/bin/python3: can't open file '/var/lib/ceph/1748dfa2-da35-11ee-9c13-1ba219ca3d2f/cephadm.8c89112927b45a1984d03fb02785df709234bdb856619c217e1ad5d54aebef2b': [Errno 2] No such file or directory
