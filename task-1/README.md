1)run nginx pod 

&nbsp;	using config map to change the port 80 to be 82 

&nbsp;	using pv and pvc to map the index.html from our cluster host 

&nbsp;	map it to a service clusterip 

&nbsp;	try to curl it from another nginx port curl PodIp:80 and curl ClusterIp
