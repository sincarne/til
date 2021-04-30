To pretty-print the `json` results of a WordPress REST API call at the command line, pipe the results through `jq`:

`curl http://site.com/wp-json/wp/v2/pages | jq '.'`
