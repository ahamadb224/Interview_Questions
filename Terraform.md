20) Within my terraform module, I need to access Azure resources from different subscriptions, what do I need to define?

21) I have two different terraform modules, one module provisions key vault, another one storage account.
    For storage account encryption, encryption key will be stored in key vault, So I will make a call with  this module to make a keyvault for me, and I need to reference the key vault to specify the location for my encryption key. So How can I reference these sources provisioned in module one.

22) I need to create a terraform module, that would be provisioning multiple instances of the same resource.
    I passed the parameter list of names, and within the module I need to be able to just get the name from the list and create a VM.
    get another name and create another VM. What mechanism in terraform, can I use to achieve this?

23) I need to create multiple azure SQL servers, each SQL server should have unique name. and each SQL server in different location.
How would you parameterize this in terraform module or loop this in terraform module, so that each SQL server will get unique name and different location?
