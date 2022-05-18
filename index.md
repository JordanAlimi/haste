## Haste Calculator

### New cast time from haste increase
```markdown
New Cast Time = Old Cast Time / (1 + (Haste Rating / 1576))
```

<input type="text" id="oldCastTime1" name="oldCastTime1"><input type="text" id="hasteRating" name="hasteRating">

### Haste rating needed for desired cast time
```markdown
Haste Rating = 1576 x ((Old Cast Time / Desired Cast Time) - 1 ))
```

<input type="text" id="oldCastTime2" name="oldCastTime2"><input type="text" id="desiredCastTime" name="desiredCastTime">