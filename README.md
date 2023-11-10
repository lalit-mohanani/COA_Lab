KAWS ![](001.png)

**T E S T I N G**

**PREPARED BY**

Saurav Jami (21CS02012) Kumar Saurabh (21CS02010) Lalit Mohanani (21CS02006) Sagnik Basu (21CS02004) Sanjana Yelukati (21CS01067)

**IPC tabulation**

After running the benchmarks provided in the research paper, we obtained the corresponding IPC values as shown in the table below: 



|Benchmarks|LRR|KAWS|KAWS+WS|
| - | - | - | - |
|Hotspot|2314|2419|2451|
|Pathfinder|1756|1787|1826|
|3DCV|256|264|272|
|3MM|250|266|271|
|Avg|1144|1184|1205|

**Graphs**

The corresponding graphs for lrr vs. kaws and that for lrr vs. kaws+ws are given below:

![](002.png) LRR ![](003.png) KAWS

2,500 ![](004.png)

4\.53%![](005.png)

2,000

1\.78%

1,500

3\.49% 1,000

500

3\.13%

6\.4%

0

Hotspot Pathfinder 3DCV 3MM Average

![](006.png) LRR ![](007.png) KAWS+WS

2,500 ![](008.png)

5\.92%

2,000

3\.98%

1,500

5\.33% 1,000

500

6\.25%

8\.4%

0 

Hotspot Pathfinder 3DCV 3MM Average

We observe that kaws provides a susceptible improvement over the standard lrr svcheduler, however that improvement is accentuated by adding warp sharing feature to that as well.
