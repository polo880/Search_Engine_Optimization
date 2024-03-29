 # Search_Engine_Optimization #

 ## Algorithm
use google search result and its subpage to establish WebTree and estimate Keywords score. Rank all page depend on sumation of Subpages Scores.

based on the algorithm, We provide two kind of services:
1. Search suggestion : Keyword related to client input and business analysis.
2. Result pages : pages more relevent to business analysis and client search.

## main Web Page
client can type in the search middle in the middle, and The request will be transfered to backend for ranking.
![Web_Page](https://github.com/polo880/Search_Engine_Optimization/assets/93720757/37ac0770-f169-4f80-b5d9-a411510bf173)

## Search result
Web pages relevent to business analysis, and search sugesstion.

![Web_Search](https://github.com/polo880/Search_Engine_Optimization/assets/93720757/2f0819dc-d963-4c20-a1b5-2623ca4ec3bd)

## Backend System diagram

![System_Design](https://github.com/polo880/Search_Engine_Optimization/assets/93720757/66f2ff00-85c4-4b4c-8c75-6d557dc82201)
 
## Webpage Schematic diagram
Take each web page as a node, and each node has a score calculated by Keywords appearing in the page.
The summation of all sub tree scores is root score. We will rank pages based on root score.

![投影片1](https://github.com/polo880/Search_Engine_Optimization/assets/93720757/ea332a3c-2ab8-4093-96a3-f7db592927c0)


