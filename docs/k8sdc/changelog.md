# Changelog
___

## 0.0.17
___

* Implemented `k8sdc pull` command.
* Implemented `k8sdc hosts` command.
* Implemented Docker registry mirror.
* Implemented Namespace creation.
* Implemented timezone configuration and NTP clients on nodes.  *NTP Server not yet implemented*.
* Updated Docker install so that `yum` is used.
* Updated Docker so that it uses the Docker registry mirror.
* Updated `helm` to version 2.0.0.
* Fixed `helm` location bug.
* Refactored `group_vars` files.
* Updated the Centos Vagrant box for provider Virtualbox to be version 1610.01.
* Removed `utilities` directory.
* Updated the following image versions for *Solution* *cs1_cluster_services*.
	* kubedns-amd64 = 1.9
	* kube-dnsmasq-amd64 = 1.4
	* exechealthz-amd64 = v1.2.0
* Implemented assertion that version 7 of Redhat/CentOS is used for the base components.
* Updated Install document.
* Other minor updates and fixes.