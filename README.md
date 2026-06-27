# TKSS Engineering Suite

X4: Foundations quality-of-life / empire-management mod project.

## Current target
X4 Foundations 9.0

## v0.1 goal
Confirm the extension loads and a Mission Director cue runs.

## v0.2 goal
Add the first real feature: Complete selected station construction.

## Install for testing
Copy the `tkss_engineering_suite` folder into:

`C:\Program Files (x86)\Steam\steamapps\common\X4 Foundations\extensions`

Then enable it in X4 Extensions.

## Debugging
Enable X4 debug logging before testing MD scripts. Add launch option:

`-logfile debuglog.txt -debug all`

Then check:

`Documents\Egosoft\X4\<profile_id>\debuglog.txt`

Search for `TKSS`.

## Development rules
- Back up saves before testing.
- Test one feature at a time.
- Do not edit live saves unless there is no safer route.
- Keep TKSS separate from iseeu0 mods.
