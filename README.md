HTMLParser2
===========

A python html parser which gives back the position of data in tags.
Derived from python's native HTMLParser class.

Usage
===========
Like the original HTMLParser, http://docs.python.org/2/library/htmlparser.html

And there's a new function handle_data_pos(self, data, pos) to give
back the position of the data from the beginning of the first 
feed() call.

