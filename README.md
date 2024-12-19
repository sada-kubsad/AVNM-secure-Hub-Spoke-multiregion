# AVNM-secure-Hub-Spoke-multiregion
AVNM H&amp;S multi-region with AFW in the hub

![Network topology diagram](images/secure-hub-spoke-multi-region-topology.png)

To run, edit terraform.tf and add:
```
provider "azurerm" {
  features {   
  }
  subscription_id = "SubscriptionID Goes here"
}
```
