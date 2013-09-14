Edit this page to describe your Submission.

## Which Categories Best Fit Your Submission and Why?
    ### Submission Categories
    * Best New Monkey
    * Best New Feature
    * Best Contribution to Operational Tools, Availability, and Manageability
    * Best Portability Enhancement
    * Best Usability Enhancement
        + update configuration and management of Cassandra nodes. Feature List below.
## Describe your Submission
    ## Hector is analagous to Priam, in that acts as a configrator and monitor for a Cassandra Node.
    ## Configuration ( is handled through settings/config.py )
    * Features
        + Status of Node. If Node is not running provides possible log error message.
        + Start/Restart of Cassandra process.
	+ Set/Reset Cassandra Configuration Yaml (supports Cassandra version(s) 1.1, 1.2) 
        + Provide latest snapshot-id.
        + Create snapshot.
        + Restore from snapshot.
        + Cassandra Configuration Management
	+ Bootstrap Cassandra install, from install.sh*
	+ Documentation is viewable from a hector service under /docs http path, or from source by viewing hector/docs/index.html.
## Provide Links to Github Repo's for your Submission
    + https://github.com/seanmccully/hector


> *Tested with Ubuntu 13.04, Fedora 17,19, CentOS 6.4
