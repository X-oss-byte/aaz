# [Command] _network application-gateway frontend-ip update_

Update a frontend IP address.

## Versions

### [2022-05-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2FwcGxpY2F0aW9uZ2F0ZXdheXMve30=/2022-05-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/applicationgateways/{} 2022-05-01 properties.frontendIPConfigurations[] -->

#### examples

- Update a frontend IP address.
    ```bash
        network application-gateway frontend-ip update --gateway-name MyAppGateway --name MyFrontendIp --private-ip-address 10.10.10.50 --resource-group MyResourceGroup
    ```

### [2023-02-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2FwcGxpY2F0aW9uZ2F0ZXdheXMve30=/2023-02-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/applicationgateways/{} 2023-02-01 properties.frontendIPConfigurations[] -->

#### examples

- Update a frontend IP address.
    ```bash
        network application-gateway frontend-ip update --gateway-name MyAppGateway --name MyFrontendIp --private-ip-address 10.10.10.50 --resource-group MyResourceGroup
    ```
