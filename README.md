---
description: This set of templates demonstrates how to set up Foundry Agent Service with virtual network isolation using User Assigned Managed Identity authentication for the AI Service with private network links to connect the agent to your secure data.
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: network-secured-agent
languages:
- bicep
---

# Foundry Agent Service: Standard Agent Setup with E2E Network Isolation and User Assigned Identity

## Overview
This infrastructure-as-code (IaC) solution deploys a network-secured agent environment with private networking and role-based access control (RBAC) and **User-assigned identity**. Standard setup supports private network isolation through utilizing **Bring Your Own Virtual Network (BYO VNet)** approach, also known as **custom VNet support with subnet delegation.**
---