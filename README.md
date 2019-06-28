# openshift-ha-redis
Openshift Redis HA(High Availability) Mode

You need to insert the following parameter to customize your redis

- redis-sentinel-service.yml
<CLUSTER_IP> : Desired Cluster IP (e.g. 172.30.0.1)

- redis-sentinel-statefulset.yml
<A Valid Redis Image> : A valid Redis Image
  
  
