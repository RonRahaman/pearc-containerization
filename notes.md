# Opportunies

* Infrastructure and data 
  * Kubernetes:  How to manage bare-metal performance 
  * Utilizaiton and monitoring: Ingesting

* Cost model
  * How do 
  * Kurbernetes existing on LBL:  Lab bears cost of Kubernetes, not really
    user-facing

* Scheduling challenge
  * HPC Cluster vs. on-prem 
  
* Physical storage best practices
  * HPC: Lustre and NFS
  * Kubernetes:  CEPH and VAST
    * Seem likes a black box
    * Options: AWS S3 bucket?  NFS export.  
      - How do you communicate the options to users?  Seems like there needs
        to be a matrix for users to choose

- VMs: LBL allows users to spin up VMs, which is a source of revenue.  
  How does the cost model translate to containers?  
  - E.g.: Have existing 


# Challenges

- User namespace issues exiting physical volumes.  How to provision UIDs 
- 

BioInformatics: Lots of reference data. Users download data to /scratch.
Global project colleciton.  E.g: BLAST database.  On Lustre.  

- Container creation and security
  - How to have scalable solutions
  - Is running uprileged sufficient?
  - Registries?

# Documentation

- Plugging into discussions.  

# Use cases
- Streams of data and ingest; is analysis decoupled.  
  How do we do analysis?  There might be a better file 
  severice for analysis vs ingest
- Lots of parallel read/write operations

- Scheduler: Storage as a resource

GLIBC compatibility on Centos 7 / RHEL 7

# Best practices



