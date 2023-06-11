
# Children
```dataview
LIST
WHERE contains(file.name, "!Monsters") AND file.name != "!Monsters"
SORT file.name asc
```

# Tagged
```dataview
LIST
WHERE contains(tags+"[[]]", "!Monsters")
SORT file.name desc
```
