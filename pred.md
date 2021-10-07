---
id: Qj7Fdmnb0gwBsNLsyKrHE
title: Pred
desc: ''
updated: 1633593196158
created: 1632378179289
stub: true
---


## Candidates

- [ ] hasUnreportedIssues as subProperty of [[pred.hasIssues]] 
- [x] addressesNeed or addressesTopic or solvesProblemsFor
  - [[pred.vs]] [[dbo.related]] 
  - 
  - ended up doing hasApplication 
- [x] originator or creditedTo or (person who gave voice to an idea, name to a concept, may have come up with an aphorism)
  - ended up doing [[as.attributedTo]] and [[dcterms.contributor]]
- [ ] hasQuotes
- hasAuthor as subProperty of creator
- something for way to specify how subjective a statement is
  - e.g. a list of pros and cons might be improved if each element hasContext of a use case, author, point-in-time/version
- `makesClaim` or `canBeSummarized`
  - when reviewing something, to separate my thoughts on the matter from what I think the thing is claiming
- `hasSense` or `hasReferent` is basically a disambiguation 
  - [ ] it's something and it's some closely related thing, i.e., a semiotic-blob


   
## philosophy

- maybe get all the non-verb-form predicates out. consistency and readability over existing standards?
