# azure-resume
Marjy's resume in Azure <!-- http://www.marjyg.website/ -->

## Steps [link to challenge](https://cloudresumechallenge.dev/docs/the-challenge/azure/)

- AZ-900 Certification ✅
- HTML & CSS ([using Bootstrap template](https://startbootstrap.com/theme/resume)) ✅ 
- JavaScript - visitor counter [using count api](https://countapi.xyz)
- Static website - [link](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website)
- HTTPS / Azure CDN - [Link](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-custom-domain-name?tabs=azure-portal#map-a-custom-domain-with-https-enabled)
- DNS / Azure DNS - Point a custom DNS domain name to the Azure CDN endpoint (domain purchased ✅)
- Database - use the [Table API](https://docs.microsoft.com/en-us/azure/cosmos-db/table/introduction) of [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction), [serverless capacity mode](https://docs.microsoft.com/en-us/azure/cosmos-db/serverless)
- API - create an API that accepts requests from your web app and communicates with the database. use [Azure Functions with an HTTP trigger](https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-http-webhook)  
- Python - write code for above [Azure SDK](https://github.com/Azure/azure-sdk-for-python)
- Tests - [test your code](https://realpython.com/python-testing/)
- IaC - create [ARM template](https://docs.microsoft.com/en-us/azure/azure-functions/functions-infrastructure-as-code) on [consumption plan](https://azure.microsoft.com/en-us/resources/templates/function-app-create-dynamic/)
- Source Control - use this repo so you can update front and backend
- CI/CD - backend [GH Actions ](https://help.github.com/en/actions/getting-started-with-github-actions/about-github-actions) to push updates to ARM template or Python code. After tests pass, app should get packaged and deployed to Azure
- CI/CD - frontend - create 2nd repo and GH actions to push new website code, and blob auto-updates
- write blog post <!-- https://wordpress.com/home/learnwithmarjy.wordpress.com -->

