git filter-branch --force --index-filter \
'git rm --cached --ignore-unmatch demo.mp4' \
--prune-empty --tag-name-filter cat -- --all


