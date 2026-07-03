# Q4 Explanation

- I inspected the shell's open files with `lsof` and by listing `/proc/$$/fd`. This showed that the shell had opened `app.log` as file descriptor 3, which is a clear example of how Linux tracks open files.
- I tested output redirection by sending a directory listing to `stdout.txt` and an error message to `stderr.txt`. The results confirmed that standard output and standard error can be separated or combined on demand.
- I also checked resource limits with `ulimit -a`. The large open-file limit indicates that the environment is configured to support many simultaneous file handles for processes and services.
