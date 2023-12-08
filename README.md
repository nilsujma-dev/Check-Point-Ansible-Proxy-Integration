Overview
This repository enhances the Check Point Ansible Collection by integrating the Proxy API feature for Check Point Security Gateways through the Management Server. The Proxy API enables the Management Server to forward API requests to designated gateways, eliminating the need to address each gateway individually.

For detailed information about the Proxy API feature, refer to the Check Point R81.20 Security Management Administration Guide.

Note: The Proxy API feature is currently available through direct API calls and hasn't been officially incorporated into the Check Point Ansible Collection. This repository addresses this gap by introducing necessary modifications in the checkpoint.py file located in the httpapi module of the collection.
