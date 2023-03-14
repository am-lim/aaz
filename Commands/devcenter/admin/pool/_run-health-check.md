# [Command] _devcenter admin pool run-health-check_

Triggers a refresh of the pool status.

## Versions

### [2023-01-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kZXZjZW50ZXIvcHJvamVjdHMve30vcG9vbHMve30vcnVuaGVhbHRoY2hlY2tz/2023-01-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.devcenter/projects/{}/pools/{}/runhealthchecks 2023-01-01-preview -->

#### examples

- Run health check
    ```bash
        devcenter admin pool run-health-check --name "{poolName}" --project-name "{projectName}" --resource-group "rg1"
    ```
