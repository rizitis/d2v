***d2v.py*** is a converter from systemd services to *SysVinit* script for *Slackware* use.

Also export an output.txt with more information for manually configs if needed.

Simple to use:

```
python3 d2v.py /etc/systemd/system/some-service.service /path/ouput
```
*2 files will be in the output, one is the SysVinit script and the other is an explanation file.txt for manually setups if needed...
Assume: groups ,dependencies, etc...*

*You can see the simple and complex service files and check the ouput with the same name...*



