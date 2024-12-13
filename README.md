# AVNM-secure-Hub-Spoke-multiregion
AVNM H&amp;S multi-region with AFW in the hub

![Network topology diagram](images/secure-hub-spoke-multi-region-topology.png)

To run, edit the terraform.tf to add:

provider "azurerm" {
  features {   
  }
  subscription_id = "SubscriptionID Goes here"
}
