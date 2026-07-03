# Q5 Explanation

- I inspected available block devices with `lsblk` and reviewed mounted filesystems with `mount`. This provided a clear picture of the storage layout available in the environment.
- I checked disk usage and inode usage with `df -h` and `df -i`. The results showed that storage space and inode capacity are both currently sufficient for the expected workload.
- I documented the observations and recommendations in the report. The main recommendation is to keep monitoring usage and place application data on dedicated storage if the environment scales up.
