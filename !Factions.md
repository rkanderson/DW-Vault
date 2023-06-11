
# Children
```dataview
LIST
WHERE contains(file.name, "!Factions") AND file.name != "!Factions"
SORT file.name asc
```

# Tagged
```dataview
LIST
WHERE contains(tags+"[[]]", "!Factions")
SORT file.name desc
```
