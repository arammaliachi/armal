## Relevant contributions to the open source community

[Author at Microsoft Azure DevOps Blog](https://devblogs.microsoft.com/devops/author/varmal/)

#### Published articles in Microsoft DevBlogs:  
:heavy_check_mark: [Understanding delta file changes and merge conflicts in Git pull requests](https://devblogs.microsoft.com/devops/understanding-delta-file-changes-and-merge-conflicts-in-git-pull-requests/) - Published.  

#### Changes to official Microsoft docs:  
- MicrosoftDocs/vsts-docs [Build Xamarin apps](https://docs.microsoft.com/azure/devops/pipelines/ecosystems/xamarin?view=azure-devops&tabs=yaml)  
Elaborated on the process of generating an ipa package for Xamarin.iOS when compiling using Azure Pipelines. Elaborated on the signing & provision process for iOS applications.  
:heavy_check_mark: Status: Published. [Link](https://github.com/MicrosoftDocs/vsts-docs/pull/4657) to pull request.

- MicrosoftDocs/vsts-docs [Build GitHub repositories](https://docs.microsoft.com/azure/devops/pipelines/repos/github?view=azure-devops&tabs=yaml)  
Pointed out that the GitHub Azure Pipelines application is not capable of producing the required webhooks to enable pull requests triggers for continuous delivery in Azure release Pipelines. Suggested the reader that if pull request triggers for CD are needed, he/she needs to switch connection to an OAuth/PAT- based.  
:heavy_check_mark: Status: Published. Reviewed by Steve Danielson - Senior Content Developer [Link](https://github.com/MicrosoftDocs/vsts-docs/pull/3904) to pull request.

- MicrosoftDocs/vsts-docs [Build pipeline triggers](https://docs.microsoft.com/azure/devops/pipelines/build/triggers?view=azure-devops&tabs=yaml)  
Example given of pull request triggers. Elaborated on when and why will a pipeline trigger with pull request triggers will fire. We receive a lot of support requests of customers claiming un-wanted builds or pipelines not triggering as expected.  
:heavy_check_mark: Status: Published. Reviewed by Steve Danielson - Senior Content Developer [Link](https://github.com/MicrosoftDocs/vsts-docs/pull/4553) to pull request.

- MicrosoftDocs/vsts-docs [Git Limits](https://docs.microsoft.com/azure/devops/repos/git/limits?view=azure-devops)  
Elaborated on the fact that the 5gb limit for push operations against an Azure Repos Git repository does not include files being tracked as part of Git LFS (explicitly asked by a customer).  
:heavy_check_mark: Status: Published. Reviewed by Steve Danielson - Senior Content Developer [Link](https://github.com/MicrosoftDocs/vsts-docs/pull/6039) to pull request.

- MicrosoftDocs/vsts-docs [Add stages, dependencies & conditions](https://docs.microsoft.com/azure/devops/pipelines/process/stages?view=azure-devops&tabs=yaml#conditions)  
After internal discussion with Azure DevOps product group came up with the following conclusion: UI designer pipelines didn’t have multiple jobs until YAML shipped, hence advanced conditions (stage/job scoped) are only supported in YAML pipelines.  
:heavy_check_mark: Status: Published. Reviewed by Kristine Toliver [Link](https://github.com/MicrosoftDocs/vsts-docs/pull/7171) to pull request.

