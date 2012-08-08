This comparer will use the native StrCmpLogicalW method to sort a list of strings in a manner that is Natural, Logical, Humanized or whatever you choose to call it.

usage:
<pre>
var mylist = new List<string>();
mylist.Sort(new NaturalStringComparer());
</pre>

*Done!*
