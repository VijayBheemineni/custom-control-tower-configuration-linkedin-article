# Description

This repo contains code for customizations, which we want to implement across all AWS accounts using  "CfCT"(Customizations for Control Tower).

# Prerequisites

- Install Control Tower
- Make sure you AWS permission have full access
- Build "CFCT" infrastructure using [Cloud Formation template] (https://raw.githubusercontent.com/aws-solutions/aws-control-tower-customizations/refs/heads/main/customizations-for-aws-control-tower.template) as documented in the steps below. CFCT version will be mentioned in the stack output variable 'CustomControlTowerSolutionVersion'. This repo code had been tested with 'v2.7.3'
- Setup Github OIDC on AWS account