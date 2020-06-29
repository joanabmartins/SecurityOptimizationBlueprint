# Deploy Security Optimization Blueprint
To deploy this blueprint you can use Powershell:

- Create new blueprint
```powershell-interactive
Import-Module Az.Blueprint
Connect-AzAccount
Import-AzBlueprintWithArtifact -Name 'SecurityOptimizationBlueprint' -SubscriptionId 'SUBSCRIPTIONID' -InputPath 'c:\SecurityOptBlueprint'
}
```


- Publish blueprint
```powershell-interactive
Import-Module Az.Blueprint
Connect-AzAccount
Import-AzBlueprintWithArtifact -Name 'SecurityOptimizationBlueprint' -SubscriptionId 'SUBSCRIPTIONID' -InputPath 'c:\SecurityOptBlueprint'
}
```

- Assign the blueprint to your subscription
Go to the blueprint that you have created in the portal and assign it to the subscription, filling the parameters required.

 :::image type="content" source="./media/blueprint-definition.PNG" alt-text="Go to the blueprint created in the previous steps" border="false":::

 :::image type="content" source="./media/assign-blueprint-button.PNG" alt-text="Click on assign" border="false":::
 
 :::image type="content" source="./media/assign-blueprint.PNG" alt-text="Fill all the details and parameters" border="false":::
 
 
 "FastTrack for Azure are “Professional Services” subject to the “Professional Services Terms” in the Online Services Terms and Online Services Data Protection Addendum. 
 
 
> This document is provided “AS-IS,” WITHOUT WARRANTY OF ANY KIND. Microsoft disclaims all express, implied or statutory warranties, including warranties of quality, title, non-infringement, merchantability and fitness for a particular purpose. 
