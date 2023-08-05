
## Children Notes
```dataview
LIST
WHERE contains(file.name, "<% tp.file.title %>") AND file.name != "<% tp.file.title %>"
SORT file.name asc
```

## Tagged Notes
```dataview
LIST
WHERE contains(tags+"[[]]", "<% tp.file.title %>")
SORT file.name asc
```

## Secret Zone 👀
```spoiler-block
SECRETS!
```
