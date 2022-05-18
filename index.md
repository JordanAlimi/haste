## Haste Calculator

### New cast time from haste increase
```markdown
New Cast Time = Old Cast Time / (1 + (Haste Rating / 1576))
```

Old cast time: <input type="text" id="oldCastTime1" name="oldCastTime1"> 
Added haste rating: <input type="text" id="hasteRating" name="hasteRating"> 
New cast time: {{ hasteRating | divided_by: 1576 }}

### Haste rating needed for desired cast time
```markdown
Haste Rating = 1576 x ((Old Cast Time / Desired Cast Time) - 1 ))
```

Old cast time: <input type="text" id="oldCastTime2" name="oldCastTime2">
Desired cast time: <input type="text" id="desiredCastTime" name="desiredCastTime">
Needed haste rating: <div>N/A</div>