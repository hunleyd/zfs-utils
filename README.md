zfs-utils
===============

Various ZFS-related scripts for cron-based housekeeping

The scripts are:
<br>
+ zfs_check - check the health of all ZFS pools
+ zfs_check_capacity - check all pools for 80% usage or less
+ zfs_check_errors - check each pool for reported error corrections
+ zfs_scrub - ensure weekly scrubs are happening on all pools
<br>
+ zfs_autoscrub - do a weekly scrub on all pools

Usage
-----
Simply drop the files in /etc/cron.{hourly,weekly}, edit to taste, and enjoy.

Requirements
------------
Gentoo
<br>GNU Bash
<br>sys-fs/zfs

Bugs
----
Find a bug? Please create an issue here on GitHub at:
https://github.com/hunleyd/zfs-utils/issues

Twitter
-------
Keep up to date on announcements and more by following Doug on Twitter, <a href="http://twitter.com/hunleyd">@hunleyd</a>

Authors
-------
**Douglas J Hunley**
+ G+: http://goo.gl/sajR3
+ Twitter: http://twitter.com/hunleyd
+ GitHub: http://github.com/hunleyd

Copyright and license
---------------------
Copyright 2013 Douglas J Hunley.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work
except in compliance with the License. You may obtain a copy of the License in the
LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the
License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
either express or implied. See the License for the specific language governing
permissions and limitations under the License.
