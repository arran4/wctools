WCTools is a collection of Wing Commander Editing Tools.

The tools are written for Linux, but they can be compiled/run on Windows. Only the C/C++ Standard Libraries are used. This is to keep dependencies light and maintain maximum portability.

To compile for windows type make windows. You will need mingw. I am using i686-w64-mingw32-g++ on Debian Linux 12 Bookworm.

- wctre is a Privateer/Wing Commander 3/4 .tre file extractor tool. 
  - Supports Extracting Privateer/Strike Commander/Armada data.
  - .XTRE detection is working, extraction of WC3/4 data is in progress

Special Thanks to Mario 'HCL' Brito for reverse engineering and documenting these game formats. His documentation is available from his website at hcl.solsector.net. 
