# [Command] _devcenter admin pool update_

Update a machine pool

## Versions

### [2023-01-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kZXZjZW50ZXIvcHJvamVjdHMve30vcG9vbHMve30=/2023-01-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.devcenter/projects/{}/pools/{} 2023-01-01-preview -->

#### examples

- Update
    ```bash
        devcenter admin pool update --devbox-definition-name "WebDevBox2" --pool-name "{poolName}" --project-name "{projectName}" --resource-group "rg1" --stop-on-disconnect status="Disabled"
    ```
