---
name: list
description: List all available CoreMem mems in the user's account.
disable-model-invocation: true
---

List the user's CoreMem mems.

Call `list_mems` and present the results as a clean list showing each mem's name and slug. Note the total count. Do not show IDs.

If $ARGUMENTS is provided, filter the list to mems whose name contains that string.
