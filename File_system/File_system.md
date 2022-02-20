# Mount
## To mount a linux remote sever on MacOS
- To install `sshfs` and `macFUSE` on https://osxfuse.github.io/
  Note that brew does not provide the latest version of `sshfs`.
- On terminal,
  ```
  fuser -c /Users/jihun/Life3 # To assign a mount point in MacOS
  sshfs jihun@xxx.xx.xx.xx:/home/jihun /Users/jihun/Life1 # To connect through sshfs protocol
  ```
- 
