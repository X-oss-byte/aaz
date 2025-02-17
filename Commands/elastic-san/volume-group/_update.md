# [Command] _elastic-san volume-group update_

Update a Volume Group.

## Versions

### [2021-11-20-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lbGFzdGljc2FuL2VsYXN0aWNzYW5zL3t9L3ZvbHVtZWdyb3Vwcy97fQ==/2021-11-20-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.elasticsan/elasticsans/{}/volumegroups/{} 2021-11-20-preview -->

#### examples

- Update a Volume Group.
    ```bash
        elastic-san volume-group update -e {san_name} -n {vg_name} -g {rg} --tags "{key2011:cccc}" --protocol-type None --network-acls "{virtual-network-rules:["{id:{subnet_id_2},action:Allow}"]}"
    ```

### [2022-12-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5lbGFzdGljc2FuL2VsYXN0aWNzYW5zL3t9L3ZvbHVtZWdyb3Vwcy97fQ==/2022-12-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.elasticsan/elasticsans/{}/volumegroups/{} 2022-12-01-preview -->

#### examples

- Update a Volume Group.
    ```bash
        elastic-san volume-group update -e {san_name} -n {vg_name} -g {rg} --tags "{key2011:cccc}" --protocol-type None --network-acls "{virtual-network-rules:["{id:{subnet_id_2},action:Allow}"]}"
    ```
