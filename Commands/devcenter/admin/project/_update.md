# [Command] _devcenter admin project update_

Update a project.

## Versions

### [2023-01-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kZXZjZW50ZXIvcHJvamVjdHMve30=/2023-01-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.devcenter/projects/{} 2023-01-01-preview -->

#### examples

- Update
    ```bash
        devcenter admin project update --description "This is my first project." --tags CostCenter="R&D" --name "{projectName}" --resource-group "rg1" --max-dev-boxes-per-user "5"
    ```
