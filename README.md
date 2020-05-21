# What Are Postman Collections
This Repository contains postman collections. Postman Collections are a group of saved requests you can organize into folders.

These are known as Conditional workflows.
Each workflow is named and uses scripts to pass data between API requests and build workflows that mirror your actual API use case
This can help you understand the 'Happy Path' of our APIs and this can assist you in getting a handle on how the APIs work and be an invaluable tool in architecting your integration with Nuapay.

# Get Postman
Download postman from https://www.postman.com/downloads/

# Importing Postman Collections

You can import your Postman data (e.g. collections) as well as your API specifications directly into the app.
To import your data into Postman, click Import in the upper-left corner of the Postman app. Select fodler and point to this cloned repository.

![Import a collection](media/import.png?raw=true)

# Confirm step

You will be presented with a summary page not unlike the page below. Note that you will see both a collection and an environment. The environment will allow you to configure items like your credentials to interact with the API environment (Production/Sandbox). To signup for sandbox access go to the [Nuapay Sandbox Signup](https://www.nuapay.com/en/request-api-sandbox/) page.

![Confirm the import](media/confirm-import.png?raw=true)

# Success

If everything went to plan you will see the collect in your workspace.

![Sucessful Import](media/collection.png?raw=true)

# Setup the Environment
Once you’ve successfully imported the collection

*STEP 1* - Select the imported environment from the drop-down (located on the top-right of the Postman application).  
*STEP 2* - Click the Eye icon.  
*STEP 3* - Click Edit.  

![Edit The Environment](media/edit.png?raw=true)

# Make Your Changes

The MANAGE ENVIRONMENTS dialog box is displayed.

Specify your apiKey in the CURRENT VALUE text box:

![Example Environment](media/save.png?raw=true)

Thats it use the collections to interact with the APIs.

