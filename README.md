This is an Ansible skeleton playbook. 

It serves as a starting point for creating Ansible playbooks by providing a basic structure and organization. 

It includes essential directories and files that can be customized and expanded upon to meet specific requirements.


--- 

Push empty folder : 
```bash 
find . -type d -empty -exec touch {}/.gitkeep \;
```

Then delete .gitkeep files : 
```bash 
find . -name ".gitkeep" -type f -delete
```