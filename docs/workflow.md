# Workflow for Using Template

## Creating New Project

This template should only be used for making your own child template which you customize with deployment information relevant to your environment.

### Registry Type

#### Azure Container Registry

##### If Using Auth Mode 'Admin Credentials via Pipeline Variable'

1. In the Azure Portal, open the ACR, then go to `Settings > Access keys`
1. Make sure `Admin user` is checked, then copy the value for `password`
1. In Azure DevOps, open and edit the pipeline
1. Click the Variables button, then create a variable as follows:
    * Name: `AcrPasswordSecret`
    * Value: The password you copied above
    * Keep this value secret: `Checked`
1. Click OK, then Save
