# ansibletest
The workflow for this pipeline:
* Fork to your personal profile
* Clone your personal profile copy onto your local development (your workstation)
* Set this as your upstream repository (origin: your personal; upstream: this one)
* Create new git branch locally
* Create your Ansible Playbook
* Check and test your Ansible Playbook
* Push local branch to origin (your GitHub account)
* Submit PR from your personal GitHub account
* GitHub Actions will --check your playbook (if fails, it will not be considered, you must fix)
* If passes, will display "Playbook Passed" message
* Branch will be merged onto main
* Playbook will be executed and changes will end up on AWS EC2 instance
