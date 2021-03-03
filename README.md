# prisma-bootstrap
Installs prisma enforcer using apoctl in the clouds

## Install
1. Create a supported Linux Instance
1. Run these commands
```bash
curl -o /tmp/bootstrap https://raw.githubusercontent.com/aporeto-se/prisma-bootstrap/master/prisma_bootstrap
bash /tmp/bootstrap
init 0
```
1. Create an AMI from the instance
