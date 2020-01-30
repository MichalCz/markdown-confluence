### Configure 

cat ~/.config/mark
username = "user.name@domain.com" 
password = "123"
base_url = "https://workspace.atlassian.net/wiki"

## Sync
```bash
./mark -f test.md  --debug --trace
```

## Issues

- Images and docs integration (should be github markdown compatible to a good degree)
- How to make it clear docs are readonly in confluence and keep the link to source
- Do not update page if it is the same content
