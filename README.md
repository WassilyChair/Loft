# Loft

To permanently delete file:

```
git filter-branch --force --index-filter 'git rm --cached --ignore-unmatch images/*.png' --prune-empty --tag-name-filter cat -- --all
git push --force
```
