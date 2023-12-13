# Install virtualmin

# Step 1
Update the apt packages index

apt update
apt upgrade -y

# Step 2: 
Download the Virtualmin installation script
Install Virtualmin by running the following commands:

wget http://software.virtualmin.com/gpl/scripts/install.sh
chmod a+x install.sh
./install.sh

# Step 3: Access Virtualmin

Once the installation is complete, you can access Virtualmin by opening a web browser and navigating to https://your-server-ip:10000. Replace your-server-ip with the IP address of your server.

Thank you. 
