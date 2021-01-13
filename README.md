> Hop Community Data 

# Tools to work with Hop Community data 

Apache Hop (Incubating) has a very active community of users and contributors.

This repository holds a variety of tools to work with community related data for the Hop community

## Project Variables 

* mattermost_url (default: `https://chat.project-hop.org`): url to connect to your Mattermost server. 
* target_dir: folder where output files will be written to

## Mattermost 

`mattermost/pl_get_mattermost_messages.hpl`: creates an archive dump of all Mattermost channels the archivebot has access to

Parameters: 
* mm_token: your Mattermost token. Use `mattermost/pl_get_mattermost_token.hpl` to retrieve your token. 

## JIRA

`jira/pl_load_jira_with_jql_query.hpl`: creates a pipe separated (asciidoc) dump of all jira tickets in the last month. This is used as a starting point to list all work that has been done in the last month for the Hop monthly roundups. 

