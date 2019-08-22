# From c1
* Attribute selector syntax is tricky. Memorise it
element[attribute^=pattern]
eg.
input[name^=anthony]

matches
<input type='text' name='anthony' value=''>
and
<input type='text' name='anthonynolan' value=''>
but not
<input type='text' name='jamesanthony' value=''>
