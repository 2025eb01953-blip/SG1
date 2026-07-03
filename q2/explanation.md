# Q2 Explanation

- I created the secure workspace and populated it with documentation, source, and log folders. This made the project structure clear and separated sensitive project assets by purpose.
- I compared the permissions before and after the changes to show how Linux access control can be tightened. The final permissions of `750` for directories and `640` for files restrict access effectively.
- I checked ownership with `stat` to confirm that the workspace remains owned by the current user. This makes the owner responsible for managing the project content.
- I verified the `umask` value and linked it to the permissions that were applied. The `0022` setting is a standard default that avoids overly permissive file creation.
