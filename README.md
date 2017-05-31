# AnsibleSysprep
Prepare Windows server to accept Ansible connection during the sysprep
* Create a folder C:\Windows\Ansible
* Place the two files under that folder
* then you can sysprep the Virtual Machine by calling 
%windir%\system32\sysprep\sysprep.exe /oobe /generalize /shutdown /mode:vm /automate:C:\Windows\Ansible\sysprep.xml
