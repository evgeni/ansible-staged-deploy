# ansible-staged-deploy

Ansible playbook that clones a repository and if there were changes deploys
to a staging environment first, and on second run (and no new changes) to
production.
