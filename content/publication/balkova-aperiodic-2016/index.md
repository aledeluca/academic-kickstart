+++
title = "Aperiodic pseudorandom number generators based on infinite words"
date = 2016-09-01
authors = ["Ľubomira Balková", "Michelangelo Bucci", "Alessandro De Luca", "Jiří Hladký", "Svetlana Puzynina"]
publication_types = ["2"]
abstract = """
In this paper we study how certain families of aperiodic infinite
words can be used to produce aperiodic pseudorandom number
generators (PRNGs) with good statistical behavior. We introduce
the *well distributed occurrences* (WELLDOC) combinatorial
property for infinite words, which guarantees
absence of the lattice structure defect in related
pseudorandom number generators. An infinite word $u$ on a $d$-ary
alphabet has the WELLDOC property if, for each factor $w$ of $u$,
positive integer $m$, and vector $\\mathbf v\\in \\mathbb Z_{m}^{d}$, there
is an occurrence of $w$ such that the Parikh vector of the prefix
of $u$ preceding such occurrence is congruent to $\\mathbf v$
modulo $m$. (The Parikh vector of a finite word $v$ over an alphabet
$\\mathcal A$ has its $i$-th component equal to the number of occurrences of the
$i$-th letter of $\\mathcal A$ in $v$.)
We prove that Sturmian words, and more generally
Arnoux-Rauzy words and some morphic images of them, have the WELLDOC
property. Using the TestU01 and
PractRand statistical tests, we moreover show
that not only the lattice structure is absent, but also other
important properties of PRNGs are improved when linear
congruential generators are combined using infinite words having
the WELLDOC property."""
featured = true
publication = "*Theoretical Computer Science*"
tags = ["Arnoux-Rauzy words","Linear congruential generators","Morphic images of AR words","Well distributed occurrences"]
url_pdf = "https://arxiv.org/pdf/1311.6002.pdf"
url_custom = [{name = "Scopus", url = "https://www.scopus.com/inward/record.uri?eid=2-s2.0-84995580487&doi=10.1016%2fj.tcs.2016.07.042&partnerID=40&md5=9f36efa9ac62506cbbbf9e94284fa138"}]
doi = "10.1016/j.tcs.2016.07.042"
+++
