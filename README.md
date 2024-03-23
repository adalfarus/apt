# aptll (Aplustools linking library)
 Makes the typing and switching versions easier than ever!


### Switching aplustools version
```python
from apt import aptll

# This will restart python with the current script after the 
aptll.change_version("0.1.3.6")  #  new version is installed.
```

### aplustools modules
Work as usual, just typing info from advanced editors won't work.
```python
from apt.package.timid import TimidTimer

timer = TimidTimer()
print(timer.end())
```
