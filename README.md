# Check Point Ansible Proxy Integration

## Overview

This repository enhances the Check Point Ansible Collection by integrating the Proxy API feature for Check Point Security Gateways through the Management Server. The Proxy API enables the Management Server to forward API requests to designated gateways, eliminating the need to address each gateway individually.

For detailed information about the Proxy API feature, refer to the [Check Point R81.20 Security Management Administration Guide](link-to-guide).

 ![image](https://github.com/nilsujma-dev/Check-Point-Ansible-Proxy-Integration/assets/114651180/0a9dc69f-2a64-4511-bb95-01e28f0049af)


**Note:** The Proxy API feature is currently available through direct API calls and hasn't been officially incorporated into the Check Point Ansible Collection. This repository addresses this gap by introducing necessary modifications in the `checkpoint.py` file located in the `httpapi` module of the collection.

## Integration Process

### Step 1: Options Selected

1. **Source Code:** 

The revised code introduces a significant enhancement – the 'target gateway' option. This addition allows the specification of a designated gateway to receive API requests, leveraging the Management Server's Proxy API feature. This modification expands the module's capabilities, aligning with advanced network management requirements and enabling more precise API interactions.

## How to Use

1. Clone this repository.
2. Navigate to the `httpapi` module in the `checkpoint.py` file.
3. Implement the modifications and replace current version of `httpapi`
4. Follow the standard Ansible playbook execution process with the enhanced Check Point Ansible Collection.

Feel free to contribute, explore the source code, and make improvements. Your contributions are valuable in enhancing the capabilities of Ansible for managing Check Point Security Gateways.

## Contributors

- Nils Ujma
- Jonas Rosenboom
- George Lucan
