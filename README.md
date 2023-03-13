# Vagrant Slurm Examples

This repository contains Vagrant [vag] configurations to bootstrap simple
test-environments for the Slurm workload management systems [slm]. 

Repository structure:

* [local/](local) - single box with `slurmdctld` & `slurmd` on localhost
* [cluster/](cluster) - multiple boxes with dedicated nodes running `slurmd`

Different Linux distributions, and sources for the Slurm RPM packages:

* Single nodes...
  - [local/ohpc/centos7](local/ohpc/centos7) CentOS 7, OpenHPC 1.3
  - [local/ohpc/centos8](local/ohpc/centos8) CentOS 8, OpenHPC 2
  - [local/epel/centos7](local/epel/centos7) CentOS 7, EPEL 7
  - [local/epel/centos_stream8](local/epel/centos_stream8) CentOS Stream 8, EPEL 8
  - [local/epel/rockylinux8](local/epel/rockylinux8) RockyLinux 8, EPEL 8
* Clusters...
  - [cluster/ohpc/centos7](cluster/ohpc/centos7) CentOS 7, OpenHPC 1.3
  - [cluster/epel/centos7](cluster/epel/centos7) CentOS 7, EPEL 7
  - [cluster/epel/centos8](cluster/epel/centos8) CentOS 8, EPEL 8

### References

[msc] MUNGE  
<https://github.com/dun/munge>  
<https://github.com/dun/munge/wiki/Installation-Guide>

[opc] OpenHPC Project, GitHub  
<https://github.com/openhpc/ohpc/>  
<https://github.com/openhpc/ohpc/releases>  
<http://build.openhpc.community/dist/>

[slm] Slurm  
<https://schedmd.com/>  
https://github.com/SchedMD/slurm  
<https://slurm.schedmd.com/quickstart_admin.html>

[vag] Vagrant  
<https://www.vagrantup.com/>  
<https://github.com/hashicorp/vagrant>  
<https://www.vagrantup.com/docs>

[epl] Fedora Slurm Packages  
<https://src.fedoraproject.org/rpms/slurm>

