


# Children
```dataview
LIST
WHERE contains(file.name, "!DW_Characters") AND file.name != "!DW_Characters"
SORT file.name asc
```

# Tagged
```dataview
LIST
WHERE contains(tags+"[[]]", "!DW_Characters")
SORT file.name desc
```


