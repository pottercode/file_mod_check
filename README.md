# file_mod_check
Count the number of files in a directory that were recently created or modified, and list total size of files in each timeframe.

## Why?

Clients recently began reporting intermittent slowdowns on a Samba server and began to suspect some clients were executing massive internal copy commands, or multiple large concurrent ones, which were reducing drive availability for other clients.

file_mod_check is a quick and dirty check for an unexpectedly large volumes of recently created or modified files to help narrow down the issue.
