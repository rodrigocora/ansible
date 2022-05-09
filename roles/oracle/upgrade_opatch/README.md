## How to call the role
```
  - roles:
    - name: Upgrade opatch in crs_home
     role: ../../roles/oracle/upgrade_opatch
      vars:
        op_user: "oracle"
        op_group: "oinstall"
        op_path: "p6880880_210000_Linux-x86-64.zip"
        op_home: "/u01/oracle/19.3.0"
        ansible_remote_tmp: /tmp
```