## How to call the role
```
  roles:
    - name: Apply patch
      role: ../../roles/oracle/apply_patches
      vars:
        patch_temp_dir: "/u01/oracle/stage"
        patch_id: "33810130"
        patch_filename: "p33810130_190000_Linux-x86-64.zip"
        oracle_home_patch: "/u01/grid/19.3.0"
        ansible_remote_tmp: "/tmp"
        vRun_analyze_only: false
```