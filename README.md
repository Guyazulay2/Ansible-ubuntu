# Ansible-ubuntu


# Step 1 
    Installing Ansible,
    go to my repository and pull the "install.sh" script.
    
    
# Step 2 
    Setting Up the Inventory File,
    sudo nano /etc/ansible/hosts  #### add here your servers.
    
    
# Step 3
    Testing Connection,
    ansible all -m ping -u root #### show you if server SUCCESS and false.
    

# Step 4 
    Key exchange,
    ssh-copy-id [Server - IP]
    
    
### EOF ### 
