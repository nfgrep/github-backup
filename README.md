# github-backup
A bash script that backs up stuff from github

## Usage
`./backup config.json`  

Where `config.json` looks like:
```json
{
  "directory": "/path/to/backed/up/repos/"
  "token": "$PAT",
  "forks": "true",
  "orgs": "false",
}
```
