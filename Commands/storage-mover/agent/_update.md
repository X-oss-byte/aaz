# [Command] _storage-mover agent update_

Update an Agent resource, which references a hybrid compute machine that can run jobs.

## Versions

### [2023-03-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5zdG9yYWdlbW92ZXIvc3RvcmFnZW1vdmVycy97fS9hZ2VudHMve30=/2023-03-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.storagemover/storagemovers/{}/agents/{} 2023-03-01 -->

#### examples

- agent update
    ```bash
        storage-mover agent update -g {rg} -n {agent_name} --storage-mover-name {mover_name} --description 123
    ```

### [2023-07-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5zdG9yYWdlbW92ZXIvc3RvcmFnZW1vdmVycy97fS9hZ2VudHMve30=/2023-07-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.storagemover/storagemovers/{}/agents/{} 2023-07-01-preview -->

#### examples

- agent update
    ```bash
        storage-mover agent update -g {rg} -n {agent_name} --storage-mover-name {mover_name} --description 123
    ```
