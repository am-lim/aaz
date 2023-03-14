# [Command] _devcenter admin attached-network list_

List the attached network connections configured for a dev center or a project.

## Versions

### [2023-01-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kZXZjZW50ZXIvZGV2Y2VudGVycy97fS9hdHRhY2hlZG5ldHdvcmtz/2023-01-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.devcenter/devcenters/{}/attachednetworks 2023-01-01-preview -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.devcenter/projects/{}/attachednetworks 2023-01-01-preview -->

#### examples

- List by dev center
    ```bash
        devcenter admin attached-network list --dev-center-name "Contoso" --resource-group "rg1"
    ```

- List by project
    ```bash
        devcenter admin attached-network list --project-name "{projectName}" --resource-group "rg1"
    ```
