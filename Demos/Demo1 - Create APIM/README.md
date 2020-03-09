# Demo1 - Creating an Azure API Management

1. Sign into the [Azure portal](https://portal.azure.com/learn.docs.microsoft.com) and then click on the **Create a resource**

1. Click on **Integration** and then **API Managment** or in the search box type `api management` and click on the **create** button.

1. In the API Management service blade type in the following details:

    | Field | Details |
    | ----- | ------- |
    Name | apim-conference-demo[random number]; the random number is to ensure the name is globally unique.
    Subscription | Select the subscription you want to use from the dropdown.
    Resource group | Click on **Create new** to create a new resource group and give it a name of rg-apim-demo
    Location | Select from the list and choose a location that is close to you. For me I choose: `(Canada) Canada Central`
    Organization name | Provide the name of your organization that will be used in the Developer Portal and in all emails.
    Administrator email | Provide an administrator email that will receive all system notifications sent from API Management.
    Pricing tier | Select `Consumption` from the dropdown.
    Enable Application Insights | For this demo you dont need to enable this.

1. Then click on the **Create** button

Deployments for the Consumption tier is very quick at a minute. However if you select any of the other tiers it can take a while to complete (30min).

When the deployment is done you can take a look at your API Management instance.

In our next demo we'll walk through importing an API.