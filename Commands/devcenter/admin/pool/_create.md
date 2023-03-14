# [Command] _devcenter admin pool create_

Create a machine pool.

## Versions

### [2023-01-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kZXZjZW50ZXIvcHJvamVjdHMve30vcG9vbHMve30=/2023-01-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.devcenter/projects/{}/pools/{} 2023-01-01-preview -->

#### examples

- Create
    ```bash
        devcenter admin pool create --location "eastus" --devbox-definition-name "WebDevBox" --network-connection-name "Network1-westus2" --pool-name "{poolName}" --project-name "{projectName}" --resource-group "rg1" --local-administrator "Enabled" --stop-on-disconnect grace-period-minutes="60" status="Enabled"
    ```
