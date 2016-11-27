TODO: find good example!

If elements are boolean: just count them, so this algorithm doesn't apply.

If elements are e.g int: what good is the majority? If an element covers 49% of the set it's still extremely significant, but this won't hit it.

Requirements:
- relatively large pool of values, otherwise a map with counts is just as good
- lots of data, otherwise we'd just sort it
- preferably streaming
