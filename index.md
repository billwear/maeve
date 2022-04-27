# thoughts on jq
The `jq` program is a filter: nothing more, nothing less.  It takes an input and produces an output.  Depending upon how you define the output, what `jq` spits out might nothing to do with the input whatwoever.

That said, `jq` is generally designed to operate on a stream of JSON data.  Output is a stream of JSON data, unless you cause some fancy formatting to happen.  Fancy formatting usually means employing some CLI tools that are *not* `jq`. 
