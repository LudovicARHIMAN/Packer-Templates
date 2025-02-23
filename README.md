# Packer-Templates

A Repository to store and share my packer tempaltes for my ProxmoxVE server. 

## credentials.pkr.hcl

Do not forget to create a credential file so packer will be able connect to your ProxmoxVE


```hcl
proxmox_api_url = "https://0.0.0.0:8006/api2/json"  # Your Proxmox IP Address
proxmox_api_token_id = "GENERATED_API_TOKEN-ID"  # API Token ID
proxmox_api_token_secret = "GENERATED_API_Secret"

```
