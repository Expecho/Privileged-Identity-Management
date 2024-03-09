# Overview of Privileged Identity Management

Privileged Identity Management provides time-based and approval-based role activation to mitigate the risks of excessive, unnecessary, or misused access permissions on resources that you care about. Here are some of the key features of Privileged Identity Management:

- Provide just-in-time privileged access to Microsoft Entra ID and Azure resources
- Assign time-bound access to resources using start and end dates
- Require approval to activate privileged roles
- Enforce multifactor authentication to activate any role
- Use justification to understand why users activate
- Get notifications when privileged roles are activated

# Contents of this repository

This repository contains a set of [Polyglot Notebooks](https://github.com/dotnet/interactive#readme) which can be used to bulk edit the PIM role settings using automation. Managing PIM settings for a large number resources is a time consuming task when done using the Azure Portal as it lacks bulk editing features. Each notebook in this repository is designed to bulk edit PIM settings for a specific resource type. The notebooks are written in C# and can be run in on your local machine using [Visual Studio Code](https://code.visualstudio.com/) and the [Polyglot Notebook extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode).

All notebooks can also handle assigning eligible roles to groups or individual users in bulk mode.

There is also a [Kusto](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/) query then can be used to generate an overview of PIM requests and approvals for auditing purposes.
