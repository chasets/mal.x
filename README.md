# mal.x
Learn mal in smaller steps than kanaka's version. 

So, here is my plan. I want to make a super minimal version of mal, kind of following allong with Norvig (https://norvig.com/lispy.html). So, the "game" is a little different than kanaka's. Rather than try to implement from scratch, I want to be able to explain (and understand) a minimal interpreter and then add features to it. 

I _think_ that a very early version (maybe 0.2 or 0.3) would be able to be useful in that it would have interop, without macros, without multiple structures, without error handling, etc. But, with interop, we could add features to be able to call APIs and write mini languages to connect to databases, run sql, and call web APIs. 

Then, we can use that simplified version to learn other languages (like one of kanaka's original uses). Keeping the structure the same as orginal will help with that. 

The first commit will be mostly a copy of the current (August 2019) python version of mal (with my improvements to the math operators). Then, I'll strip as much away as possible, leaving kanaka's structure. Then, try to understand / explain what is left. 


