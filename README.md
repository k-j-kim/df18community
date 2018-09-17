# DF18 demo for Communities Theming

Simple example of creating a Salesforce Community theme layout with Material Design Lite (MDL)

## Prerequisite
- Have a Dev Hub authorized with ability to create new scratch orgs

## Dev, Build and Test
1. Create a scratch org with `sfdx force:org:create -f config/project-scratch-def.json -s`
2. Push source to the scratch org with `sfdx force:source:push -u YOUR_SCRATCH_ORG_ALIAS`
3. Create a new Community and set the `default` theme layout to `mdlThemeLayout`

## Resources
- [SFDX](https://developer.salesforce.com/tools/sfdxcli)
- [Salesforce Extensions for VS Code](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode)