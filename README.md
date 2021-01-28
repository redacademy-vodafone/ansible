# ansible
Vodafone Red Academy - Ansible Course

    [Setup]
    - git clone https://github.com/redacademy-vodafone/ansible.git
    - cd ansible
    - python3 -m venv VENV
    - source VENV/bin/activate
    - pip install --upgrade pip
    - pip install ansible==2.9.9
    - ansible --version
    - pip install -r requirements.txt
    - #pip install --upgrade -r requirements.txt 
    - git clone https://github.com/ktbyers/ansible_helpers
    - cd ansible_helpers/
    - nano requirements.txt
    - pip install -r requirements.txt 
    - git clone https://github.com/napalm-automation/napalm-ansible
    - cd napalm-ansible/
    - pip install napalm
    - git clone https://github.com/networktocode/ntc-ansible
    - cd ntc-ansible/
    - python setup.py install

    [Cisco Device|Config]
      enable
      conf t
      interface gi 0/0
      no shut
      end
      write