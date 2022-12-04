extract and launch.  
for linux: `chmod u+x dump_projector.run`, `./dump_projector.run aaa.exe aaa.swf`  
for Windows: `"dump_projector.exe" "aaa.exe" "aaa.swf"`  

if you don't want any output redirect the `STDOUT` and `STDERR` to `/dev/null` in linux, or `NUL` in Windows,  
using `1>` and `2>`  
exit code (`$?` linux, `%ErrorLevel%` Windows) is `0` (success), or `1` (failed).  

