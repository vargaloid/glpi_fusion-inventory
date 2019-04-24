# glpi_fusion-inventory
## ansible-playbook GLPI Fusion-Inventory-agent installation

## Requirements:

 * Debian 8,9 or CentOS 7

## Contains:
 * fusion-inventory_inst.yml - main ansible-playbook

## Usage:
```
      ansible-playbook fusion-inventory_inst.yml -e "hosts=dev.example.com"
```

## Version 1.0

 * Create main ansible-playbook glpi_fusion-inst.yml
 * Testing on Debian 8, CentOS 7
