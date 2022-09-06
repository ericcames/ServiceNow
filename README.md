# ServiceNow and Ansible Automation Platform
### ServiceNow Credential Setup
[ Automation Hub -> General usage patterns -> Using modules from Automation Controller](https://console.redhat.com/ansible/automation-hub/repo/published/servicenow/itsm/docs/general_usage_patterns "Using modules from Automation Controller")  
    ***Input configuration***  
    ---    
    fields:  
        - id: SN_HOST  
            type: string  
            label: Snow Instance  
        - id: SN_USERNAME  
            type: string  
            label: Username  
        - id: SN_PASSWORD  
            type: string  
            label: Password  
            secret: true  
    required:  
        - SN_HOST  
        - SN_USERNAME  
        - SN_PASSWORD  