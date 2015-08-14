# idle3-tools
This linux/unix utility can be used to remove or set the infamous idle3 timer found on recent Western Digital Hard Disk Drives. Shamelessly copied (and git-ified) from http://idle3-tools.sourceforge.net/

For the lastest WD MyPassport drives, if your WD drive is at /dev/sdd, then:
hdparm -J /dev/sdd
./idle3ctl --force --ignore_errors -d /dev/sdd
hdparm -J /dev/sdd

It works despite of all errors.
