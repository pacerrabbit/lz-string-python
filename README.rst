** This branch is an edited version of lzstring optimized for the use in NextLesson. **
All api remain the same. String concatenations have been replaced with list appending for better performance in parsing interactive lessons data.

lz-string-python
================

lz-string for python 2/3

Based on the LZ-String javascript found here: http://pieroxy.net/blog/pages/lz-string/index.html

Example
-------
::

  >>> import lzstring
  >>> x = lzstring.LZString()
  >>> compressed = x.compressToBase64(u'你好') # 'gbyl9NIA'
  >>> x.decompressFromBase64(compressed) # '你好'

Installation
------------
::

  $ pip install lzstring
