# ansible_projects
This repository contains various types of Ansible projects.

## Usage

### 1. Clone the Repository
```bash
git clone https://github.com/yamangit/ansible_projects.git
```

### 2. Make python environment
```bash
cd ansible_projects
python3 -m venv ansibleenv
source ansibleenv/bin/activate
pip install ansible 
```

### 3. Run the user_add_with_ssh Project

```bash
cd user_add_with_ssh
ansible-playbook playbook.yml --ask-becom-pass
```
   
