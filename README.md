```
apm list -bi | sed -e 's/@[0-9.]*$//g' > packages.txt 
```

```
apm install --packages-file packages.txt
```
