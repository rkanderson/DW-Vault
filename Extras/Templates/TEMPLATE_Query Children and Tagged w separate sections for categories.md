
## Children
```dataview
LIST
WHERE contains(file.name, "<% tp.file.title %>") AND file.name != "<% tp.file.title %>"
SORT file.name asc
```

## Tagged - Topics
```dataview
LIST
WHERE contains(tags+"[[]]", "<% tp.file.title %>") AND startswith(file.name, "!")
SORT file.name asc
```

## Tagged - Sources
```dataview
LIST
WHERE contains(tags+"[[]]", "<% tp.file.title %>") AND startswith(file.name, "💧")
SORT file.name asc
```

# Tagged - Logs
```dataview
LIST
WHERE contains(tags+"[[]]", "<% tp.file.title %>") AND startswith(file.name, "🪵")
SORT file.name desc
```
