tail.py - python implementaion of tail linux utility

Usage:
```
  tail.py <number of lines> <log file> 
```

Example: 
```
 evgeny ~/Projects/tail > ./tail.py 10 apache_log_example.log
--apache_log_example.log--
64.242.88.10 - - [07/Mar/2004:17:28:45 -0800] "GET /twiki/bin/oops/TWiki/ResetPassword?template=oopsmore¶m1=1.4¶m2=1.4 HTTP/1.1" 200 11281
64.242.88.10 - - [07/Mar/2004:17:29:59 -0800] "GET /twiki/bin/view/TWiki/ManagingWebs?skin=print HTTP/1.1" 200 8806
64.242.88.10 - - [07/Mar/2004:17:31:39 -0800] "GET /twiki/bin/edit/Main/UvscanAndPostFix?topicparent=Main.WebHome HTTP/1.1" 401 12846
64.242.88.10 - - [07/Mar/2004:17:35:35 -0800] "GET /twiki/bin/view/TWiki/KlausWriessnegger HTTP/1.1" 200 3848
64.242.88.10 - - [07/Mar/2004:17:39:39 -0800] "GET /twiki/bin/view/Main/SpamAssassin HTTP/1.1" 200 4081
64.242.88.10 - - [07/Mar/2004:17:42:15 -0800] "GET /twiki/bin/oops/TWiki/RichardDonkin?template=oopsmore¶m1=1.2¶m2=1.2 HTTP/1.1" 200 11281
64.242.88.10 - - [07/Mar/2004:17:46:17 -0800] "GET /twiki/bin/rdiff/TWiki/AlWilliams?rev1=1.3&rev2=1.2 HTTP/1.1" 200 4485
64.242.88.10 - - [07/Mar/2004:17:47:43 -0800] "GET /twiki/bin/rdiff/TWiki/AlWilliams?rev1=1.2&rev2=1.1 HTTP/1.1" 200 5234
64.242.88.10 - - [07/Mar/2004:17:50:44 -0800] "GET /twiki/bin/view/TWiki/SvenDowideit HTTP/1.1" 200 3616
64.242.88.10 - - [07/Mar/2004:17:53:45 -0800] "GET /twiki/bin/search/Main/SearchResult?scope=text®ex=on&search=Office%20*Locations[^A-Za-z] HTTP/1.1" 200 7771
```
