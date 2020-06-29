# Deploy Security Optimization Blueprint
To deploy this blueprint you can use Powershell:

**1. Create new blueprint**
```powershell-interactive
Import-Module Az.Blueprint
Connect-AzAccount
Import-AzBlueprintWithArtifact -Name 'SecurityOptimizationBlueprint' -SubscriptionId 'SUBSCRIPTIONID' -InputPath 'c:\SecurityOptBlueprint'
}
```


**2. Publish blueprint**
```powershell-interactive
Import-Module Az.Blueprint
Connect-AzAccount
Import-AzBlueprintWithArtifact -Name 'SecurityOptimizationBlueprint' -SubscriptionId 'SUBSCRIPTIONID' -InputPath 'c:\SecurityOptBlueprint'
}
```

**3. Assign the blueprint to your subscription in the portal**

Go to the blueprint that you have created in the portal and assign it to the subscription, filling the parameters required.
 
 * Go to the blueprint that you have just created.
 <p align="center">
  <img src="./media/blueprint-definition.PNG" width="500" title="">
</p>
 
  * Assign the blueprint to your subscription.
 <p align="center">
  <img src="./media/assign-blueprint-button.PNG" width="500" alt="">
</p>

 * Fill in the parameters.
 <p align="center">
  <img src="./media/assign-blueprint.PNG" width="500" title="">
</p>

  * Wait for the assignment to be succeeded.
 <p align="center">
  <img src="./media/assignment-succeeded.PNG" width="500" title="">
</p>
 
 
 
 
 
 
>  "FastTrack for Azure are “Professional Services” subject to the “Professional Services Terms” in the Online Services Terms and Online Services Data Protection Addendum. This document is provided “AS-IS,” WITHOUT WARRANTY OF ANY KIND. Microsoft disclaims all express, implied or statutory warranties, including warranties of quality, title, non-infringement, merchantability and fitness for a particular purpose. 
