# Innovaxion 2024

Welcome to the Generative AI Workshops and Demos Repository dedicated to the exciting world of Generative AI! 🎉

This repository is your go-to resource for today to get access to workshops and demos designed to explore and understand the fascinating concepts surrounding Generative AI. Whether you’re a seasoned AI enthusiast or just starting your journey, you’ll find valuable content here to enhance your knowledge and skills.
What You’ll Find Here
- Workshops: Hands-on sessions that guide you through the fundamentals and advanced topics of Generative AI.
- Demos: Interactive demonstrations showcasing the capabilities and applications of Generative AI technologies.


Why Generative AI?
Generative AI is revolutionizing the way we create and interact with digital content. From generating realistic images and videos to composing music and writing code, the possibilities are endless. This repository aims to demystify these technologies and provide you with the tools to harness their power.

Get Involved
We encourage you to participate, contribute, and share your insights. Whether it’s through code contributions, feedback, or discussions, your involvement is what makes this session thrive.

Thank you for joining us on this exciting journey into the world of Generative AI. Let’s learn, create, and innovate together!


* https://github.com/Azure/intro-to-intelligent-apps/tree/main
The objective of this workshop is to practice realistic AI orchestration scenarios and to learn how to build intelligent apps. At the end of the workshop you will:
  * Know how to use prompt engineering techniques for effective generative AI responses on OpenAI
  * Understand the implications of the usage of tokens and embeddings when interacting with an LLM  ve experience in leveraging AI orchestrators like Langchain/ Semantic Kernel with Azure OpenAI
  * Have evaluated different vector stores like Qdrant or Azure AI Search to enhance LLM responses with your data and context
  * Know how to turn a business scenario with data, context and user input into an intelligent application on Azure

* https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/explore-azure-ai-services-curated-list-of-prebuilt-models-and/ba-p/4230788
Azure AI services provide a comprehensive suite of prebuilt models and demos designed to address a wide range of use cases. These models are readily accessible and allow you to implement AI-powered solutions seamlessly. We have curated and catalogued prebuilt demos available across Azure AI services. We hope this helps you infuse AI seamlessly into your products and services.
* https://github.com/Azure-Samples/azure-sql-db-chatbot In this repo you will find a step-by-step guide on how to use Azure SQL Database to do Retrieval Augmented Generation (RAG) using the data you have in Azure SQL and integrating with OpenAI, directly from the Azure SQL database itself. You'll be able to ask queries in natural language and get answers from the OpenAI GPT model, using the data you have in Azure SQL Database.

* Learning path around Generative AI: [Develop your own custom copilots with Azure AI Studio](https://learn.microsoft.com/en-us/training/paths/create-custom-copilots-ai-studio/?wt.mc_id=ignite23_breakout_collection_azuremktg_AI)

* Learning generative Ai for begiiners : [Generative Ai for beginners](https://github.com/microsoft/generative-ai-for-beginners)
## Pre-requisites

### Resource Providers

Before starting the hands's-on-Labs or workshop, register the following Azure providers on subscription.

In Azure Cloud Shell copy-paste the following code snippet:

``` bash

for service in \
Microsoft.AAD \
Microsoft.Advisor \
Microsoft.AlertsManagement \
Microsoft.ApiManagement \
Microsoft.App \
Microsoft.AppConfiguration \
Microsoft.AppPlatform \
Microsoft.Automation \
Microsoft.AzureActiveDirectory \
Microsoft.BotService \
Microsoft.Cache \
Microsoft.Cdn \
Microsoft.CertificateRegistration \
Microsoft.Communication \
Microsoft.Compute \
Microsoft.ContainerInstance \
Microsoft.ContainerRegistry \
Microsoft.ContainerService \
Microsoft.CognitiveServices \
Microsoft.CostManagementExports \
Microsoft.CustomProviders \
Microsoft.DataCatalog \
Microsoft.DBforMySQL \
Microsoft.DBforPostgreSQL \
Microsoft.DevCenter \
Microsoft.DevOpsInfrastructure \
Microsoft.DomainRegistration \
Microsoft.DocumentDB \
Microsoft.EventGrid \
Microsoft.EventHub \
Microsoft.Insights \
Microsoft.KeyVault \
Microsoft.Logic \
Microsoft.MachineLearning \
Microsoft.MachineLearningServices \
Microsoft.Maps \
Microsoft.ManagedIdentity \
Microsoft.ManagedNetwork \
Microsoft.Management \
Microsoft.Network \
Microsoft.NotificationHubs \
Microsoft.OperationalInsights \
Microsoft.OperationsManagement \
Microsoft.PowerPlatform \
Microsoft.Relay \
Microsoft.Scheduler \
Microsoft.Search \
Microsoft.Security \
Microsoft.ServiceBus \
Microsoft.Sql \
Microsoft.Storage \
Microsoft.VirtualMachineImages \
Microsoft.VSOnline \
microsoft.visualstudio \
Microsoft.Web
do
    az provider register --namespace $service
done
```
