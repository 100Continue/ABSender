ABSender
========

ABSender is a Http Sender Use in HTTP Server perf test, is modify from ApacheBench

BUG Fixed(Segmentation Fault):
========

When ApacheBench Sorted on total connect times, would cause writing off the end of the stats array

and report Segmentation Fault. for detail you can visit "http://100continue.iteye.com/blog/1337347"

New Features:
========
a. Support to read the Headers, Cookies, Path, PostData info from file

b. Support in Range Mode

