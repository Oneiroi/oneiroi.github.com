Recovering files using scalpel
==============================

Usage: scalpel -c /path/to/config/file.conf -o /output_files_here /path/to/device


For files not in your .conf
===========================

Get header: xxd -l 0x04 /path/to/similar_file.ext
Get footer: xxd -s -0x04 /path/to/similar_file.ext

Compare multiple files to check for common header and footer data.

Config file entry
-----------------

qcow2    y    100000000    QFI\xfb

<ext>    <case_sensitive y/n>  <max carve size in bytes>    <HEADER>    <FOOTER>

* max carve can be a range denoting min:max or just min: 
* header and footer may be specified as regex patterns using // delimeters.
* i've noted with qcow2 at least footer varies between images, as such I chose to forgo this.

Working with LVM
================

* pvscan: record VolGroup and size
* lvscan: record path matching VolGroup and size previous.

i.e.

scalpel -c /etc/qcow.conf -o /test /dev/vg_piwhhost2/lv_home

Whilst this works it is far more sensible to boot using a live distro and cerate an image of this volume for processing off the device instead of "online" carving.
