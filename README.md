ansible-role-crystal-reports
=========

Upload and Install Crystal Reports on Server

## Requirements
------------



## Role Variables
--------------
Available variables are listed below, along with default values (see `defaults/main.yml`):

  local_src: "/tmp"
  crystal_rpt_exe: "BINARY.EXE"
  remote_dest: "C:/Temp"
  response_file: "response.ini"
  cr_install_dir: "C:/Program Files (x86)/SAP BusinessObjects/"
  cr_product_key: "LICENSEKEY"
  cr_registered_co: "COMPANYNAME"
  cr_registered_user: "USERNAME"


## Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: ansible-role-crystal-reports }

## License
-------

BSD

