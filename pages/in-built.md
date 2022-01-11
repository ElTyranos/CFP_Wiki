---
layout: default
---

# In-built systems

## Check if CFP is running
You can then detect if CFP is running with this trigger :

```
cfp_loaded_checker = {
    trigger_if = { cfp_is_loaded = yes }
    trigger_else = { always = no }
}
```

You can then use this trigger at your convenience in your code.

_NB: This does not return any "missing trigger" error if CFP is not loaded. However, you should not use `cfp_is_loaded = yes` alone._
