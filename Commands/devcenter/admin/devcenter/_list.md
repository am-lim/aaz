# [Command] _devcenter admin devcenter list_

List all devcenters in a subscription or resource group.

## Versions

### [2023-01-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kZXZjZW50ZXIvZGV2Y2VudGVycw==/2023-01-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.devcenter/devcenters 2023-01-01-preview -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.devcenter/devcenters 2023-01-01-preview -->

#### examples

- List by resource group
    ```bash
        devcenter admin devcenter list --resource-group "rg1"
    ```

- List by subscription
    ```bash
        devcenter admin devcenter list
    ```
