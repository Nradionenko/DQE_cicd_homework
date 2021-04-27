# DQE_cicd_homework
Workflow:
1. Main = development branch
2. All features developed within features

Whenever main branch is merged, build is triggered in Jenkins and python tests are executed.

Preprod release: at 1.30am on 1st and 15th of every month main branch is checked-out to preprod_release branch
Prod release: at 1.30am on 20th of every month preprod_release branch is checked-out to prod branch
