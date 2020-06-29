# Write-up

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

1. **Cost** (per month)
* VM - For a Basic tier 2 GB RAM, 1 core, 10 GB storage 500 MXN.
* App Service - 1.75 GB RAM, 1 core, 10 GB storage 1000 MXN, more expensive but have to do less work.

2. **Scalability**
* VM - It is scalable.
*App Service - Provides scalability as well.

3. **Availability**
* VM - Traffic manager is provided br Azure.
* App Service - Traffic manager is provided br Azure.

4. **Workflow**
* VM - More work on your side, not necesarilly harder, but it will certainly take more time, steps or maintenance.
* App Service - It is Easier, specialized.

The principal task is to have the web app running and app service would be the best solution as it can be independent of the environment where it has to run and we just have to manage the updates and infrastructure.
Keeping in mind various aspects such as costs, scalability, availability, and workflow, web app which is deployed to Microsoft Azure using Azure pipelines with GitHub is better than Virtual Machine.


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

* Python web app was integrated with the app service and was further integrated with GitHub to simplify the task. VM would have been a preference if there was a need to code python app.

* If there was a need to gain access to the configuration files, once the app is running, VM would have a better option as it supports access.

* Other than VM, container solution can also be considered as an option as it has a web server a separate service from the web app.

* According to this particular project using App Service is still a better option than VM.