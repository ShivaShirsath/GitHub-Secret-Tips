# GitHub-Secret-Tips

## GitHub username from link 

```java
name.substring(
  name.indexOf(".com/") + 5,
  (
    name.indexOf(".com/") + 5 
  ) +
  name.substring(
    name.indexOf(".com/")+5
  ).indexOf("/")
)
```

