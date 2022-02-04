DEMO Technical  Requirements : 

1. Permanent NFS mounts in all K8S Cluster Nodes : 

in /etc/fstab
      [NFS_SERVER_FQDN]:/home/obj/k8s_shared_storage  /u01/app/oracle nfs defaults 0 0
      [NFS_SERVER_FQDN]:/opt/config  /opt/config nfs defaults 0 0




