# GitHub-Secret-Tips

## GitHub username from link 
+ Input :
   ```
   https://raw.githubusercontent.com/ShivaShirsath/GitHub-Secret-Tips/main/README.md
   ```
+ Program :
   ```java
   link = "https://raw.githubusercontent.com/ShivaShirsath/GitHub-Secret-Tips/main/README.md";

   link.substring(
     name.indexOf(".com/") + 5,
     (
       name.indexOf(".com/") + 5 
     ) +
     name.substring(
       name.indexOf(".com/")+5
     ).indexOf("/")
   )
   ```
+ Output :
   ```
   ShivaShirsath
   ```

