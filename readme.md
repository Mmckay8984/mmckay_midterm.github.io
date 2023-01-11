How to build the project

Azure:
1. Create Azure Static Web page, follow this tutorial: https://techcommunity.microsoft.com/t5/educator-developer-blog/host-your-website-on-azure-static-web-apps-for-free/ba-p/3579709
2. Basically just sign up, create a resource group in Azure
3. Click create static web page (azure service)
4. Link your github repo, and select branch, etc
5. Deploy (github workflow will automatically deploy app to web server)
6. DONE!
7. Can monitor the service in Azure, take down/up. A workflow will trigger on push to master branch, and auto-build/deploy to Azure Service.
