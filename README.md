this is corrent playbook with proper indentations: 

- name:
  hosts: all
  tasks:
      copy:
        - name:
          src: opt/index.html
          dest: /var/www/html
