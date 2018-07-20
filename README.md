## .atom backup
**Update packages:**
`apm list --installed --bare > packages.list`

**Restore packages:**
`apm install --packages-file packages.list` or `apm install 'cat packages.list'`
