# Check Point Ansible Proxy Integration

## Overview

This repository enhances the Check Point Ansible Collection by integrating the Proxy API feature for Check Point Security Gateways through the Management Server. The Proxy API enables the Management Server to forward API requests to designated gateways, eliminating the need to address each gateway individually.

For detailed information about the Proxy API feature, refer to the [Check Point R81.20 Security Management Administration Guide](link-to-guide).

**Note:** The Proxy API feature is currently available through direct API calls and hasn't been officially incorporated into the Check Point Ansible Collection. This repository addresses this gap by introducing necessary modifications in the `checkpoint.py` file located in the `httpapi` module of the collection.

## Integration Process

### Step 1: Options Selected

1. **Source Code:** [Check Point Ansible Management Collection on GitHub](https://github.com/nilsujma-io/checkpointgaiaproxy)

The revised code introduces a significant enhancement – the 'target gateway' option. This addition allows the specification of a designated gateway to receive API requests, leveraging the Management Server's Proxy API feature. This modification expands the module's capabilities, aligning with advanced network management requirements and enabling more precise API interactions.

## How to Use

1. Clone this repository.
2. Navigate to the `httpapi` module in the `checkpoint.py` file.
3. Implement the modifications specified in the code to enable Proxy API integration.
4. Follow the standard Ansible playbook execution process with the enhanced Check Point Ansible Collection.

Feel free to contribute, explore the source code, and make improvements. Your contributions are valuable in enhancing the capabilities of Ansible for managing Check Point Security Gateways.

## Contributors

- Nils Ujma
- Jonas Rosenboom
- 

## License

This project is licensed under the [MIT License](link-to-license).
