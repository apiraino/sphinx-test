To reproduce the issue, run:

`make clean && tox -r`

if in `requirements.txt` we have `sphinx==1.7.1` the [callable](https://docs.python.org/2/library/functions.html#callable) object will not be correctly linked.

Use `sphinx==1.6.7` to pin a working version.
