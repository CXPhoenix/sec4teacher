#
```
root@kali:~/Downloads/steg-1# pdftotext -help
pdftotext version 0.71.0
Copyright 2005-2018 The Poppler Developers - http://poppler.freedesktop.org
Copyright 1996-2011 Glyph & Cog, LLC
Usage: pdftotext [options] <PDF-file> [<text-file>]
  -f <int>             : first page to convert
  -l <int>             : last page to convert
  -r <fp>              : resolution, in DPI (default is 72)
  -x <int>             : x-coordinate of the crop area top left corner
  -y <int>             : y-coordinate of the crop area top left corner
  -W <int>             : width of crop area in pixels (default is 0)
  -H <int>             : height of crop area in pixels (default is 0)
  -layout              : maintain original physical layout
  -fixed <fp>          : assume fixed-pitch (or tabular) text
  -raw                 : keep strings in content stream order
  -htmlmeta            : generate a simple HTML file, including the meta information
  -enc <string>        : output text encoding name
  -listenc             : list available encodings
  -eol <string>        : output end-of-line convention (unix, dos, or mac)
  -nopgbrk             : don't insert page breaks between pages
  -bbox                : output bounding box for each word and page size to html.  Sets -htmlmeta
  -bbox-layout         : like -bbox but with extra layout bounding box data.  Sets -htmlmeta
  -opw <string>        : owner password (for encrypted files)
  -upw <string>        : user password (for encrypted files)
  -q                   : don't print any messages or errors
  -v                   : print copyright and version info
  -h                   : print usage information
  -help                : print usage information
  --help               : print usage information
  -?                   : print usage information
```
