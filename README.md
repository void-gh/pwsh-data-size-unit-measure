# Background
Size conversion in PowerShell is pretty straight forward. If you have a number in
bytes and want to convert it into MB, or GB, it is as simple as typing 12345/1GB, or
12345/1MB in PowerShell prompt or script.
  
The problem comes when you want to convert a value from something other than bytes to
something else, and being able to properly handle either base 10 (KB, MB, GB, etc.),
or base 2 (KiB, MiB, GiB, etc.) size notations correctly.
  
Another issue is that you may want to be able to control the precision of the returned
result (e.g. 0.95 instead of 0.957870483398438).
  
This script easily handles conversion from any-to-any (e.g. Bits, Bytes, KB, KiB, MB,
MiB, etc.) It also has the ability to specify the precision of digits you want to
recieve as the output.

# Origin
The design ideal originally inspired from a post by Techibee posted on July 7, 2014
http://techibee.com/powershell/convert-from-any-to-any-bytes-kb-mb-gb-tb-using-powershell/2376

It has been expanded upon from there.

# Installation
Download, or clone, the Convert-DataSizeUnitOfMeasure.ps1 script and read the cmdlet based help
documentation for information on how to use this script.
