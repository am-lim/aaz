# [Command] _devcenter admin network-connection run-health-check_

Triggers a new health check run. The execution and health check result can be tracked via the network connection health check details.

## Versions

### [2023-01-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kZXZjZW50ZXIvbmV0d29ya2Nvbm5lY3Rpb25zL3t9L3J1bmhlYWx0aGNoZWNrcw==/2023-01-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.devcenter/networkconnections/{}/runhealthchecks 2023-01-01-preview -->

#### examples

- Run health check
    ```bash
        devcenter admin network-connection run-health-check --name "uswest3network" --resource-group "rg1"
    ```
