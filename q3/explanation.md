# Q3 Explanation

- I created a regular file, a hard link, and a symbolic link to observe how Linux represents file references. The inode listing showed that the hard link and original file share the same inode, which is the key difference from a symbolic link.
- I used `stat` to collect metadata and confirm the link types. The output showed the hard link had the same inode and link count as the original file, while the symbolic link had its own inode.
- I deleted the original file and tested both links. The hard link still worked because it still referenced the same inode, but the symbolic link failed because its target path no longer existed.
