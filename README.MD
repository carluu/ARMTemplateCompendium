# Compendium of ARM Templates

## Folder Structure

The structure is broken down as follows:
Level 1: Resource Provider
Level 2: Resource Type

Within a resource type, there are the following folders:
- reference
> Contains a copy of the latest schema

- scripts
> Contains helpful scripts related to the provider

The resource type folder also contains:
- deploy_xxx.json - This is the ARM template that deploys resources as per the file name
- deploy_xxx.parameters.json - The parameters file template
- deploy_xxx.paramaters.local.json - Should be used to actually store your parameters to avoid checking anything private into source control (ignored by Git)