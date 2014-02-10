Problem this tries to solve
===========================
In WFRP your game character advances through careers. You randomize the initial career and then proceed with choosing the next one by:

1. either paying 100 EXP and selecting one from outgoing careers
2. or paying 200 EXP and selecting any career you want

What I've done is to plug in Neo4J to model careers as graph.

Neo4J v2.0.0
-------------

I've plugged in v2 since:

1. it has GUI out of the box with standalone server, visualization included
2. installation is easy
3. nodes have labels
4. cypher is somewhat more mature now
5. easy Java support

### Installation

Download URL for community edition Neo4J for x64 Unix:
http://www.neo4j.org/download_thanks?edition=community&release=2.0.0&platform=unix&packaging=zip&architecture=x64

Upon installing, follow to bin dir and there are scripts to start / stop standalone server on 7474 port.
