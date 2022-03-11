# mmm-ansible-role-sudo-root
Sudo config for previous direct root access users

- Ensure PermitRootLogin no - mmm-ansible-role-sshd-config 
- Ensure allowed users in wheel group - mmm-ansible-role-groups
- Suggest that users in this group get appropriate ssh keys into place everywhere as user

