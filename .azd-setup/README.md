# AZD Template Setup 

This README documents the steps taken to setup and configure an AZD template for provisioning a Foundry project with hosted agents - using GitHub Copilot CLI assistance.

## 1. Baseline Repo

The initial repo was cleaned up to leave only the following files. 
- The `data/zava` folder contains 425 products from the Zava catalog - with a 50-item subset saved as `product-paints.csv`
- 

```bash

# Boilerplate files for OSS 
CODE_OF_CONDUCT.md  
LICENSE  
SECURITY.md  
SUPPORT.md  

# Data files for 2 scenarios
#  Contoso Outdoors - focus on Hiking/Camping products
#  Zava Retail - focus on DIY products
data/
    contoso/  
    zava/

# Development Enviornment 
.devcontainer/
    devcontainer.json
requirements-dev.txt

# Documentation
README.md  
```

---