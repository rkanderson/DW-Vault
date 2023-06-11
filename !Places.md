
# Children
```dataview
LIST
WHERE contains(file.name, "!Places") AND file.name != "!Places"
SORT file.name asc
```

# Tagged
```dataview
LIST
WHERE contains(tags+"[[]]", "!Places")
SORT file.name desc
```
