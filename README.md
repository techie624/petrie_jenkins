# petrie_jenkins

---

_This is a personal project used to help automate nerd things._

This repo is used to automate the deployment of a Virtual Table Top. This repo is the home of jenkins and uses the host docker service to deploy containers to its host beside the jenkins wrapper container. These automations have been made so I can rapidly automate the deployment of this virtual tabletop to any cloud or local instance.

This system is meant to only help automate and deploy containers in parallel and to use code to create the deployment changes. Jenkins is only the wrapper for the deployment and is used to keep secrets and vars private.

If anyone besides the author ( @techie624 ) would like to use this, copy the ./deploy directory and run it on your debian system that already has docker installed. The `pwd` will become jenkins home and can access it locally on port 80. Start setting up your personal jenkins deployment.