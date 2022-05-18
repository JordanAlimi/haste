## Haste Calculator

### New cast time from haste increase
```markdown
New Cast Time = Old Cast Time / (1 + (Haste Rating / 1576))
```

Old cast time: <input type="text" id="oldCastTime1" name="oldCastTime1"></br>
Added haste rating: <input type="text" id="hasteRating" name="hasteRating">

### Haste rating needed for desired cast time
```markdown
Haste Rating = 1576 x ((Old Cast Time / Desired Cast Time) - 1 ))
```

Old cast time: <input type="text" id="oldCastTime2" name="oldCastTime2"></br>
Desired cast time: <input type="text" id="desiredCastTime" name="desiredCastTime">