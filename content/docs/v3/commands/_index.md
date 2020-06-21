---
title: 'Commands'
weight: 200
---

# Aggregator CLI Commands


 Verb               | Use
--------------------|----------------------------------------
logon.azure         | Logon into Azure. This must be done before other verbs.
logon.ado           | Logon into Azure DevOps. This must be done before other verbs.
install.instance    | Creates a new Aggregator instance in Azure. 
add.rule            | Add a rule to existing Aggregator instance in Azure.
map.rule            | Maps an Aggregator Rule to existing Azure DevOps Projects, DevOps events are sent to the rule.
list.instances      | Lists Aggregator instances in the specified Azure Region or Resource Group or in the entire Subscription.
list.rules          | List the rules in an existing Aggregator instance in Azure.
list.mappings       | Lists mappings from existing Azure DevOps Projects to Aggregator Rules.
invoke.rule         | Executes a rule locally or in an existing Aggregator instance.
configure.instance  | Configures an existing Aggregator instance (currently the Azure DevOps authentication).
configure.rule      | Change a rule configuration (currently only enabling/disabling).
update.rule         | Update the code of a rule and/or its runtime.
unmap.rule          | Unmaps an Aggregator Rule from a Azure DevOps Project.
remove.rule         | Remove a rule from existing Aggregator instance in Azure, removing any mapping to the Rule.
uninstall.instance  | Destroy an Aggregator instance in Azure, removing any mapping to the Rules.
help                | Display more information on a specific command.
version             | Display version information.

You can see a few Command examples in [Sample Aggregator CLI usage](command-examples/).