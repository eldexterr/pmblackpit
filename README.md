# How to Play
**1.** Download the patch file from https://github.com/eldexterr/pmblackpit/releases <br/>
**2.** Get a vanilla paper mario US rom in .z64 format (other formats can be converted to .z64 here https://hack64.net/tools/swapper.php) <br/>
**3.** Patch the .z64 here with https://hack64.net/tools/patcher.php <br/>
<br/>
<br/>
# How to Compile (For Editing Source Code)
#### **Note:** Black Pit uses Star Rod 0.3.2

**1.** In your Star Rod's files go to:
```
 /database/types/misc.txt
```
**2.** Add this as a new line and save:
```
.Default = 0
```
**3.** In your Star Rod's files go to:
```
 /database/types/battle/elements.txt
```
**4 .** Add this as a new line and save:
```
Mystery00000000 = 0
```
**5.** In your Star Rod's files go to:
```
 \database\types\partners.enum
```
or here if applicable:
```
 \globals\enum\partners.enum
```
**6 .** Add this as a new line and save:
```
0 = Empty
```
After all this you should be able to compile with Star Rod 0.3.2\
\
![](https://cdn.discordapp.com/emojis/866747027299500073.png)
