**NOTE** that the functionality in this repository has not been tested after splitting from [Kielipankki repository](https://github.com/CSCfi/Kielipankki/).

# Signbank

Currently Signbank is set up manually, but eventually this directory is
intended to contain the full Ansible playbooks for setting up the server.

## Current Functionality

Currently only the following things are managed by Ansible:
- certificate management using ACME
- some very basic (likely not sufficient) Apache configuration
