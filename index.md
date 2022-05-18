forms:
  - to: jhvanderschee@gmail.com
    subject: New submission!
    redirect: /
    form_engine: formspree
    placeholders: false
    fields: 
      - name: name
        input_type: text
        placeholder: Name
        required: true
      - name: email
        input_type: email
        placeholder: Email address
        required: true
      - name: sex
        input_type: radio
        placeholder: male
        required: true
      - name: sex
        input_type: radio
        placeholder: female
        required: true
      - name: message
        input_type: textarea
        placeholder: Message
        required: false
      - name: terms
        input_type: checkbox
        placeholder: I accept the terms and conditions
        required: true
      - name: submit
        input_type: submit
        placeholder: Submit form
        required: true

## Haste Calculator

### New cast time from haste increase
```markdown
New Cast Time = Old Cast Time / (1 + (Haste Rating / 1576))
```

{% if page.forms[0] %}{% include form.html form="1" %}{% endif %}

### Haste rating needed for desired cast time
```markdown
Haste Rating = 1576 x ((Old Cast Time / Desired Cast Time) - 1 ))
```

Old cast time: <input type="text" id="oldCastTime2" name="oldCastTime2">
Desired cast time: <input type="text" id="desiredCastTime" name="desiredCastTime">
Needed haste rating: <div>N/A</div>