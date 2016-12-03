# Data-Center-Resource-Manager
This is a generalized version of our source code. All publication related settings and algorithms has been removed from the project to improve the general usability.

Please visit https://sites.google.com/site/asmhmahmud/research#dcrm for more information.

Use Netbeans 8.0 or later to execute Java Resource Manager.
The benchmark suite must be installed as directed for optimal performance.


## Summary of the project
This project develops a fully autonomous data center resource management system in Java. This system has been used by many of our papers and projects. This project has two parts: A Java resource management system and a benchmark suite consisting of Hadoop, RUBiS, and Key-Value store. The Java resource management system can control the various features of XenServer such as CPU frequency scaling, virtual machine migration, assignment of VCPUs to virtual machines, turn the servers on/off, log the monitoring data, etc.  The benchmark suite has a custom implementation of Key value store and a scaling module for Hadoop. It also has workload generation system that simulates user activity for Hadoop and Key Value Store.