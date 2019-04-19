---
layout: default
title: "Reading/converting PLW data logger output"
post_author: "Harrington, K."
---

Pico DataLoggers generate output in the PLW format. This is somewhat more compact than an ascii counterpart, but is inconvenient to use.

Download the following jar: [plwreader.jar](https://jitpack.io/com/github/computationalandphysicalsystems/plwreader/1224d0c2ea/plwreader-1224d0c2ea.jar)

Then run it with:

```
java -jar plwreader.jar somefile.plw
```

This will generate an output CSV in the same location as `somefile.plw`, named `somefile.csv`

Reference:
<em>plwreader source</em><strong> available at: [https://github.com/ComputationalAndPhysicalSystems/plwreader](https://github.com/ComputationalAndPhysicalSystems/plwreader)
</em>
