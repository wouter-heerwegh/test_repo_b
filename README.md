# Workflow testing

This repo is the parent and will contain a submodule `test_repo_a`.

I should make workflows for the following:
- If a submodule is added --> add a dispatch workflow if it doesn't exist.
- Create or update a repo variable to indicate which repos should be notified of submodule changes
- add a repo token to have correct permissions
- Make a pr if a submodule is updated
  - this should only be 1 pr for all submodules, and all submodules should be listed in the pr body
