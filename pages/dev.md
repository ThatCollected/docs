# Collected Dev Server

## Run with local content

1. `cd assets`
2. `collected dev . -p 5555`
3. View <http://localhost:5555> in your browser

## How it works

- Indexes all files within a directory.
- Watches for changes.
- Serves with correct content types.
- e.g. `/text/plain/edeaaff3f1774ad2888673770c6d64097e391bc362d7d6fb34982ddf0efd18cb` loads contents of `abc.txt`

## Use cases

- For local development. Manage content in a directory, instead of needing to upload it to the cloud.
