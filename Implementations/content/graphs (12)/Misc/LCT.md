# 5

  * Splay Tree
    * Notes
      * [Paper](https://www.cs.cmu.edu/~sleator/papers/self-adjusting.pdf)
      * [Splay Tree Presentation](https://web.stanford.edu/class/archive/cs/cs166/cs166.1146/lectures/08/Slides08.pdf)
  * Link Cut Tree
    * Notes
      * [Link-Cut Tree](http://courses.csail.mit.edu/6.851/spring12/scribe/L19.pdf)
      * [Subtree Queries Tutorial](https://codeforces.com/blog/entry/67637)
    * Problems
      * SPOJ
        * [DYNACON1](https://www.spoj.com/problems/DYNACON1/)
          * technically, LCT isn't needed because the queries are offline
        * [DYNALCA](https://www.spoj.com/problems/DYNALCA/)
      * CF
        * [Silence's Sounds](https://codeforces.com/contest/1109/problem/F)
          * test connectivity
        * [Tree or not Tree](https://codeforces.com/contest/117/problem/E)
          * tree + one edge
        * [Old Driver Tree](https://codeforces.com/contest/1172/problem/E)
        * [Pastoral Oddities](https://codeforces.com/contest/603/problem/E)
          * path + subtree queries
      * USACO Camp
        * [The Applicant](https://probgate.org/viewproblem.php?pid=578)
          * tree + one edge
        * [Cows Play on a Tree](https://probgate.org/viewproblem.php?pid=259)
          * HLD or LCT with Treap
      * Other
        * [Balanced Tokens (Eric Zhang)](https://www.hackerrank.com/contests/pwshpc-online-round/challenges/pwsh-tokens/problem)
        * [Dynamic Tree Test (Easy)](https://dmoj.ca/problem/ds5easy)
        * [Dynamic Tree Test](https://dmoj.ca/problem/ds5)
          * Requires operations on subtrees in addition to those from the easy version
        * [CEOI Treasure Hunt](https://cses.fi/174/list/)
          * get k-th parent
        * [CERC 17 D](https://codeforces.com/gym/101620)
          * LCT not needed, but can directly apply solution from "The Applicant"
