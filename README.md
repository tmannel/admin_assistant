# admin_assistant
The Admin Assistant allows Splunk admins to monitor data ingestion and onboarding, RBAC config, user onboarding, and more! Dashboard panels are powered by internal logs, the Splunk REST API, and reporting commands.

## Installation
Install pre-requisite visualization apps on search heads or search head cluster:
- Sankey Diagram

Install on Splunk monitoring console and/or search heads. No knowledge objects other than views are required for Admin Assistant. Two Options are available:

- Install using git into the apps directory:

```
  cd $SPLUNK_HOME/etc/apps
  git clone https://github.com/tmannel/admin_assistant
```
- Download the .spl package and upload via the Splunk UI:
[link to .spl](https://adminassistantpackage.s3.amazonaws.com/admin_assistant.spl)

## Roadmap
Introspection on indexers, search heads, heavy forwarders. Clustering insights.

## Author
Tim Mannel, Splunk Solutions Engineer

## License
Admin Assistant is licensed under the GNU Public Livense v3 free of charge.
