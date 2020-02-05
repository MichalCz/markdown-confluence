# Playground

For testing markdown to Confluence integration.
Based on https://github.com/kovetskiy/mark

### Configure 

```bash
cat ~/.config/mark
username = "user.name@domain.com" 
password = "123"
base_url = "https://workspace.atlassian.net/wiki"
```

## Sync
```bash
pipe-git-updated xargs -n 1 ./mark --debug --trace -f
```

## Issues

- Images and docs integration (should be github markdown compatible to a good degree) (https://github.com/kovetskiy/mark/issues/9)
- How to make it clear docs are readonly in confluence and keep the link to source
- Do not update page if it is the same content
