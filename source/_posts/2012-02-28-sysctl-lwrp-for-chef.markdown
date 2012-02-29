---
layout: post
title: "sysctl LWRP for chef"
date: 2012-02-28 18:25
comments: true
categories:  ["chef", "lwrp", "systems"]

---

About 2 years ago i wrote a hacky ohai plugin to push all sysctl values into node data, and then a crappy recipe that would run an exec if they didn't match values in node-data. A few months back i re-wrote all this to just use an lwrp that would just set these value, and a recipe that would pull them from attributes. So if you want to be able to see what nodes have huge pages enabled or whatnot.

Today I took some time to clean up the readme and release that code for other to hopefully find useful.

* On github [sysctl lwrp cookbook](https://github.com/spheromak/cookbooks/tree/master/sysctl)
* On the community site [jn_sysctl](http://community.opscode.com/cookbooks/jn_sysctl) 


[1]: https://github.com/spheromak/cookbooks/tree/master/sysctl
