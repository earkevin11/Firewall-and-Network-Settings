# Firewall-and-Network-Settings for Azure Storage Accounts

- Users can change firewall settings and allow access from all networks or only selected networks


# Add a service endpoint on a virtual network of the virtual machine
- Add service endpoint for Microsoft.Storage for the virtual network

# Go back to Azure Storage account and add the existing virtual network
- This virtual network has the service endpoint

# Try to access the Storage account and its contents via the Storage Explorer
- It should work as you are now connected via the Service Endpoint
