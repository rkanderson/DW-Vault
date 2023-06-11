
# Children
```dataview
LIST
WHERE contains(file.name, "!Players") AND file.name != "!Players"
SORT file.name asc
```

# Tagged
```dataview
LIST
WHERE contains(tags+"[[]]", "!Players")
SORT file.name desc
```
