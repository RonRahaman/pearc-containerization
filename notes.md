# Opportunies

# Challenges

## Storage Issues

### Physical storage best practices

  * HPC: Lustre and NFS
  * Kubernetes:  CEPH and VAST
    * Options: Example: AWS S3 bucket with  NFS export.  
      - How do you communicate the options to users?  Seems like there needs
        to be a matrix for users to choose

### Importing existing volumes

User namespace issues exiting physical volumes.  How to provision UIDs 

### Using reference data

BioInformatics
* Lots of reference data
* Gathering data in one place rather than downloading separate images
* How would multiple containers share that data

## Security
- Container creation and security
  - How to have scalable solutions?  Vulnerability scanners
    in registries?  Criteria for trust?
  - Is running unprileged sufficient?

# Documentation

- Plugging into discussions.  

# Use cases

### Different storage strategies for different workflows
- Streams of data and ingest vs. decoupled analysis
- Ideal: concurrently

### Storage as a resource
- Storage as a resource

### OS Library compatibility
- GLIBC compatibility on Centos 7 / RHEL 7

# Best practices

- Ultimate goal.  How to get 



