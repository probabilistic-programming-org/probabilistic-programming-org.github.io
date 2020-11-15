---
title: "ProbProgs"
date: 2020-11-14T21:04:18-05:00
draft: false
---
# Probabilistic-Programming.org

This website serves as a repository of links and information about probabilistic programming languages, including both academic research spanning theory, algorithms, modeling, and systems, as well as implementations, evaluations, and applications.  If you would like to contribute to this site, please contact  [Daniel Roy](http://danroy.org/). The site is still under construction: please help us link to relevant projects and research!

## News

- **Dec 2014** Third NIPS Workshop on Probablistic Programming. See [workshop website](http://probabilistic-programming.org/wiki/NIPS*2014_Workshop) for details as they appear.
- **Oct 2014** Microsoft has released their R2 tool, [download here](http://research.microsoft.com/en-us/downloads/40e37dc8-1337-43e9-88af-03eabf591208/).

### Join the mailing list 

The [probabilistic-programming mailing list](http://lists.csail.mit.edu/mailman/listinfo/probabilistic-programming) hosted at CSAIL/MIT hopes to support discussion between researchers working in the area of probabilistic programming, but also to provide a means to announce new results, software, workshops, etc.   The mailing list is fashioned after the popular "uai" mailing list.

## The probabilistic programming approach

Probabilistic graphical models provide a formal lingua franca for modeling and a common target for efficient inference algorithms. Their introduction gave rise to an extensive body of work in machine learning, statistics, robotics, vision, biology, neuroscience, artificial intelligence (AI) and cognitive science. However, many of the most innovative and useful probabilistic models published by the AI, machine learning, and statistics community far outstrip the representational capacity of graphical models and associated inference techniques. Models are communicated using a mix of natural language, pseudo code, and mathematical formulae and solved using special purpose, one-off inference methods. Rather than precise specifications suitable for automatic inference, graphical models typically serve as coarse, high-level descriptions, eliding critical aspects such as fine-grained independence, abstraction and recursion.

PROBABILISTIC PROGRAMMING LANGUAGES aim to close this representational gap, unifying general purpose programming with probabilistic modeling; literally, users specify a probabilistic model in its entirety (e.g., by writing code that generates a sample from the joint distribution) and inference follows automatically given the specification. These languages provide the full power of modern programming languages for describing complex distributions, and can enable reuse of libraries of models, support interactive modeling and formal verification, and provide a much-needed abstraction barrier to foster generic, efficient inference in universal model classes.

We believe that the probabilistic programming language approach within AI has the potential to fundamentally change the way we understand, design, build, test and deploy probabilistic systems.  This approach has seen growing interest within AI over the last 10 years, yet the endeavor builds on over 40 years of work in range of diverse fields including mathematical logic, theoretical computer science, formal methods, programming languages, as well as machine learning, computational statistics, systems biology, probabilistic AI.

## Academic Research

*Please see our [collection of research articles on probabilistic programming](/research)*

A growing body of literature studies probabilistic programming from an array of perspectives.  The individual project pages linked below often contain lists of publications, although we aim to collect these in our own master list as well.  A related but distinct body of work is that of <a href="https://web.archive.org/web/20141221190829/http://en.wikipedia.org/wiki/Approximate_Bayesian_computation" class="external text" title="http://en.wikipedia.org/wiki/Approximate_Bayesian_computation">Approximate Bayesian Computation (ABC)</a>, which focuses on likelihood-free methods, developed originally to tackle statistical queries  in population genetics but now applied more broadly.  The website for the <a href="https://web.archive.org/web/20141221190829/http://www.i-like.org.uk/index.html" class="external text" title="http://www.i-like.org.uk/index.html">i-Like research programme</a> links to a number of very interesting articles.  Another related area of research is <a href="https://web.archive.org/web/20141221190829/http://en.wikipedia.org/wiki/Statistical_relational_learning" class="external text" title="http://en.wikipedia.org/wiki/Statistical_relational_learning">Statistical Relational Learning</a>, which is in general interested in distributions on structured spaces (e.g., models of first order languages) where there may be uncertainty in the number and types of objects.

<h2>Existing probabilistic programming systems</h2>

{{ range where .Site.Pages "Section" "systems" }}
   {{ .Title }}
{{ end }}

