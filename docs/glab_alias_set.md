## glab alias set

Set an alias.

### Synopsis

Set an alias.

```
glab alias set <alias name> '<command>' [flags]
```

### Examples

```
$ glab alias set createissue 'glab create issue --title "$1"'
$ glab createissue "My Issue" --description "Something is broken."
# => glab create issue --title "My Issue" --description "Something is broken."

```

### Options

```
  -h, --help   help for set
```

### SEE ALSO

* [glab alias](glab_alias.md)	 - Create, list and delete aliases

###### Auto generated by spf13/cobra on 25-Aug-2020
