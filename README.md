# CMPG-323-Overview-35030755
This in an overview page for the Project for CMPG 323 where we are enhancing skills across different concepts,tools and technology stacks 

## What repositories will be used
There will be multiple submodules used to manage different git repositories under the same root
There will be git repositories for each project for CMPG 323 which will then be "Linked to this main overview page" thus 5 repositories in total

## Branching Strategy

My branching strategy is to have a Production branch(main branch) which then has a sub branch for other projects so that fixes and changes can be made to those branches before they are commited to the Production branch to ensure that the Production branch is protected and secured. 
Hot fix branches will also be added as necessary to patch and fix odd bugs and to add extra functionality to the already running Production product so that a new product doens't get published with every new iteration of code or changes.
The branch strategy will loosely look like this image

![alt text](https://docs.microsoft.com/en-us/azure/devops/repos/git/media/branching-guidance/featurebranching.png?view=azure-devops)
## Built with
 This section will get populated as more information about project is known.
    ASP.Net
## Ignored files
 .getignore will be storing information that is not needed to the public and ensure that certain files in each project will not be pushed if there are changes that were made to the branch so that only needed files need to be updated when changes are made.
 ignored files are normally files that are machine generated files that can be derived from the repository source.
 File examples that are ignored are personal IDE config files, hidden system files and files generated at run time 
###### Secrets!
Confidential and Sensitive information will be saved via Github Secretss to encrypt and secure the personal information of the repository