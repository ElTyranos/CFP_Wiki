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

## Artifacts triggers
CFP has an in-built artifact system which you can catch to make your own mod compatible with CFP. Currently, only historical artifacts are setup.

You can find all informations in : `\common\scripted_triggers\CFP_artifacts_triggers.txt`