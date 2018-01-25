# OpenStack Cloud Computing Cookbook - Fourth Edition
This is the code repository for [OpenStack Cloud Computing Cookbook - Fourth Edition](https://www.packtpub.com/virtualization-and-cloud/openstack-cloud-computing-cookbook-fourth-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788398763), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
This is the fourth edition of the industry-acclaimed OpenStack Cloud Computing Cookbook, created by four recognized OpenStack experts. It has now been updated to work with the latest OpenStack builds, using tools and processes based on their collective and vast OpenStack experience.

OpenStack Open Source Cloud software is one of the most used cloud infrastructures to support a wide variety of use cases, from software development to big data analysis. It is developed by a thriving community of individual developers from around the globe and backed by most of the leading players in the cloud space today. We make it simple to implement, massively scalable, and able to store a large pool of data and networking resources. OpenStack has a strong ecosystem that helps you provision your cloud storage needs. Add OpenStack's enterprise features to reduce the cost of your business.

This book will begin by showing you the steps to build up an OpenStack private cloud environment using Ansible. You'll then discover the uses of cloud services such as the identity service, image service, and compute service. You'll dive into Neutron, the OpenStack Networking service, and get your hands dirty with configuring networks, routers, load balancers and more.

You’ll then gather more expert knowledge on OpenStack cloud computing by managing your cloud's security and migration. After that, we delve into OpenStack Object storage and you’ll see how to manage servers and work with objects, cluster, and storage functionalities. Finally, you will learn about OpenStack dashboard, Ansible, Keystone, and other interesting topics.


## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
# Shared infrastructure parts
shared-infra_hosts:
 controller-01:
 ip: 172.29.236.110
 controller-02:
 ip: 172.29.236.111
 controller-03:
 ip: 172.29.236.112
# Compute Hosts
compute_hosts:
 compute-01:
 ip: 172.29.236.113
 compute-02:
 ip: 172.29.236.114
```

To use this book, you will need access to computers or servers that have hardware virtualization capabilities. Familiarity of Linux and accessing Linux servers using SSH is expected.
To set up the lab environment described at the end of Chapter 1, Installing OpenStack with Ansible, you will need to install and use Oracle’s VirtualBox and Vagrant. You can access details of how to set up your computer using VirtualBox and Vagrant by visiting 
https://github.com/OpenStackCookbook/vagrant-openstack.

## Related Products
* [OpenStack Cloud Computing Cookbook - Third Edition](https://www.packtpub.com/virtualization-and-cloud/openstack-cloud-computing-cookbook-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781782174783)

* [OpenStack Cloud Computing Cookbook - Second Edition](https://www.packtpub.com/virtualization-and-cloud/openstack-cloud-computing-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781782167587)

* [OpenStack Cloud Computing Cookbook](https://www.packtpub.com/virtualization-and-cloud/openstack-cloud-computing-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781849517324)

