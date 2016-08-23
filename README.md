== Mining github data

== Goals

TBD

== Scientific Sources

http://2014.msrconf.org/program.php?#data_showcase_teasers
Conference on Mining Software Repositories - just a lot of names for googling
http://ghtorrent.org/halloffame.html  - just a lot of names for googling

http://help.sentiment140.com/for-students/ - sentiment analysis for twitter

http://www.kdd.org/kdd2016/papers/files/rfp0218-groverA.pdf - node2vec



== Source Code
https://github.com/nelsonic/github-scraper - Scraper writen on JS
https://github.com/aditya-grover/node2vec/ node2vec - gensim

https://github-ranking.com/

== Big Query
https://blog.jessfraz.com/post/analyzing-github-pull-request-data-with-big-query/ - query examples
https://medium.com/google-cloud/analyzing-github-issues-and-comments-with-bigquery-c41410d3308#.tslwen5gt Analyzing GitHub issues and comments with BigQuery

http://stackoverflow.com/questions/tagged/github-archive
https://www.igvita.com/slides/2012/bigquery-github-strata.pdf


== Ideas
Recomender system for contributors
Contributor vs Owner - True Skill(http://trueskill.org/, http://www.moserware.com/assets/computing-your-skill/The%20Math%20Behind%20TrueSkill.pdf), PR - probability 
Sentiment analysis using emoji 
LDA - for project description, for pullrequests, commit messages
Analysis of transition to new languages
Ego graph of githubers (node2vec) - calc distance between users
stargazers metrics - cause of rising
Probability of starting collaboration on repo. Estimate number of contributors.
Auto - awesome clustering, create awesome list for topics
Detect unmaintained repositories

== Topics for investigations

BigQuery price
AWS price
Spark GraphX

== Recomender systems

https://www.insight-centre.org/sites/default/files/publications/2016sac.pdf -Measuring Semantic Distance for Linked Open Data-enabled Recommender Systems 


== Interesting events on github

https://github.com/PowerShell/PowerShell/pull/1901#issuecomment-240840910
