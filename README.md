# admin_assistant
The Admin Assistant allows Splunk admins to monitor data ingestion and onboarding, RBAC config, user onboarding, and more! Dashboard panels are powered by internal logs, the Splunk REST API, and reporting commands.

## Installation
Install pre-requisite visualization apps on search heads or search head cluster:
- Sankey Diagram
- Timeline Viz
- Punchcard
- Parallel Coordinates Diagram

Install on Splunk search heads. No knowledge objects other than views are required for Admin Assistant. Two Options are available:

- Install using git:

  `git clone https://github.com/tmannel/admin_assistant`
  
- Install from the .spl file in this repository:

  github.com/tmannel/admin_assistant/install/admin_assistant.spl

## Roadmap
Introspection on indexers, search heads, heavy forwarders. Top talkers of errors and likely source.

## Author
Tim Mannel, Splunk Solutions Engineer

## License
Admin Assistant is free!
