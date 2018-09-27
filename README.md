# DF18 demo for Communities Theming

Simple example of creating a Salesforce Community theme layout with [Material Design Lite](https://getmdl.io/started/index.html)

## Prerequisite
- [SFDX CLI](https://developer.salesforce.com/tools/sfdxcli)
- [Org with Dev Hub enabled](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_enable_devhub.htm)
- (Optional) [VS Code](https://code.visualstudio.com/)
- (Optional) [Salesforce Extensions for VS Code](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode)

## Dev, Build and Test
1. Create a new scratch org with `sfdx force:org:create -f config/project-scratch-def.json -s`
2. Push source to the scratch org with `sfdx force:source:push -u YOUR_SCRATCH_ORG_ALIAS`
3. Create a new Community and set the `default` theme layout component to `mdlThemeLayout`