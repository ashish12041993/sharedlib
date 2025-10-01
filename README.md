config.project = project name

config.env = environment (dev, staging, prod)

config.buildCmd, config.testCmd, config.deployCmd = customizable commands

🔹 Step 3: Configure in Jenkins

Go to Manage Jenkins → Configure System → Global Pipeline Libraries

Add library name: jenkins-shared-library

Point it to your Git repo.
