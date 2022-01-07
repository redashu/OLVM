# OLVM

## ON OEL 7.x 

### update software 

```
yum-config-manager --enable ol7_latest
yum update -y
```

### Installing OVirt engine 

```
 yum install oracle-ovirt-release-el7 -y
 yum-config-manager --enable repository
 yum-config-manager --disable ovirt-4.2
 yum-config-manager --disable ovirt-4.2-extra
 yum install ovirt-hosted-engine-setup -y
 yum install ovirt-engine-appliance -y

```

