# Alpine Linux Jump Box and NAT AMI Build

For a bastion host/ Jump box we have chosen a minimal Alpine Linux distro.
We don't need  a lot of packages on these hosts.This is immutable infra.
If we feel that this box has been compromised, simply destroy it and provision another.

If an AMI has been created it will be echo'd to stdout and also to ami.created file

