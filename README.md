# Ansible code to install and compile custom modules. 

An Ansible code that custom compiles the following components on RedHat/CentOS as being the normal user.

## Prerequisites to be installed in all the nodes to support the compilation without any issues:
    * expat-devel-2.1.0-10.el7_3.x86_64 
    * libtool-2.4.2-22.el7_3.x86_64
    * m4-1.4.16-10.el7.x86_64
    * bison-3.0.4-2.el7.x86_64
    * bzip2-1.0.6-13.el7.x86_64
    * flex-2.5.37-6.el7.x86_64
    * intltool-0.50.2-7.el7.noarch
    * openssl-1.0.2k-16.el7.x86_64
    * gcc-c++-4.8.5-36.el7.x86_64
    * unzip-6.0-19.el7.x86_64
    * zip-3.0-11.el7.x86_64
    * openssl-devel-1.0.2k-16.el7.x86_64
    * gcc-gfortran.x86_64
    * java-1.8.0-openjdk-devel
               
## Prerequisite entries needs to be done to ldconfig
    /data1/Source/db-4.7.25/build_unix/.libs/
    /data1/apps-install/lib
    /data1/apps-install/lib64
    /data1/apps-install/usr/lib
    /data1/apps-install/include
    /data1/DB/lib
    /data1/DB/include
    /data1/openldap/lib
    /data1/Python-2.7.5/lib


## License
MIT / BSD

## Author Information
This YAML was created in 2019 by [Akhil Sambasivan](http://www.linkedin.com/in/akhilsambasivan)
