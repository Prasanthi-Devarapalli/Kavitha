Quickstart: Get started with Language Studio
Article
07/22/2022
3 minutes to read
4 contributors


Language Studio is a set of UI-based tools that lets you explore, build, and integrate features from Azure Cognitive Service for Language into your applications.

Language Studio provides you with a platform to try several service features, and see what they return in a visual manner. It also provides you with an easy-to-use experience to create custom projects and models to work on your data. Using the Studio, you can get started without needing to write code, and then use the available client libraries and REST APIs in your application.

Get started using Language Studio
To use Language Studio, you will need an Azure Language resource for authentication. You can also use this resource to call the feature REST APIs and client libraries. Follow these steps to get started.
![image](https://user-images.githubusercontent.com/112709511/195115812-8b5ebb8c-d53f-4058-8818-4f34e11cadf4.png)


 Important

The setup process and requirements for custom features are different. If you're using one of the following custom features, we recommend using the quickstart articles linked below to get started more easily.

Conversational Language Understanding
Custom Text Classification
Custom Named Entity Recognition (NER)
Orchestration workflow
Create an Azure Subscription. You can create one for free.

Log into Language Studio. If it's your first time logging in, you'll see a window appear that lets you choose a language resource.

A screenshot showing the resource selection screen in Language Studio.

Select Create a new language resource. Then enter information for your new resource, such as a name, location and resource group.

 Tip

When selecting a location for your Azure resource, choose one that's closest to you for lower latency.
We recommend turning the Managed Identity option on, to authenticate your requests across Azure.
If you use the free pricing tier, you can keep using the Language service even after your Azure free trial or service credit expires.
A screenshot showing the resource creation screen in Language Studio.

Select Done. Your resource will be created, and you will be able to try the different features offered by the Language service. For example, select Find linked entities.

A screenshot showing the main screen in Language Studio.

This feature has a section for entering text, uploading a file, or choosing a text sample to demonstrate how the feature works. To try the demo, you will need to choose a resource and acknowledge it will incur usage according to your pricing tier.

A screenshot showing a feature in Language Studio
![image](https://user-images.githubusercontent.com/112709511/195115312-45bbf13e-e3f4-4f58-a65c-8deee6568cae.png)

![image](https://user-images.githubusercontent.com/112709511/195115240-734607c4-2a0b-4b70-b115-0dc53b2bc98a.png)


After sending text, you'll be able to see a visualization, along with the JSON response. At the bottom of the page, you'll see next steps and the cURL command for the API request you just sent.

A screenshot showing the result of a feature in Language Studio
![image](https://user-images.githubusercontent.com/112709511/195115183-2691caf4-f526-482d-a4b3-a172e2fad1d2.png)


Language Studio pre-configured features
The Language service offers multiple features that use prebuilt, pre-configured models for performing various tasks such as: entity linking, language detection, and key phrase extraction. See the Azure Cognitive Service for Language overview to see the list of features offered by the service.

Each of these features has a demo-like experience inside Language Studio that lets you input text, and presents the response both visually, and in JSON. These demos help you quickly test these prebuilt features without using code.
![image](https://user-images.githubusercontent.com/112709511/195115382-fae58edb-c364-41b1-9404-1114e393bd3b.png)


Language Studio customizable features
The Language service also offers multiple features that let you create, train, and deploy custom models to better fit your data. For example, custom content classification and custom question answering. For features with customization, Language Studio offers workflows that let developers and subject matter experts build models without needing machine learning expertise.

Clean up resources
If you want to clean up and remove a Cognitive Services subscription, you can delete the resource or resource group. Deleting the resource group also deletes any other resources associated with it.

Portal
Azure CLI
 Tip

In Language Studio, you can find your resource's details (such as its name and pricing tier) as well as switch resources by:

Selecting the Settings icon in the rop-right corner of the Language Studio screen).
Select Resources
You can't delete your resource from Language Studio.

Next steps
Go to the Language Studio to begin using features offered by the service.
For more information and documentation on the features offered, see the Azure Cognitive Service for Language overview.
Recommended content
What's new in Azure Cognitive Service for Language? - Azure Cognitive Services
Find out about new releases and features for the Azure Cognitive Service for Language.
Model Lifecycle of Language service models - Azure Cognitive Services
This article describes the timelines for models and model versions used by Language service features.
Quickstart - create a conversations language understanding project - Azure Cognitive Services
Use this article to quickly get started with Conversational Language Understanding
