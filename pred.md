---
id: Qj7Fdmnb0gwBsNLsyKrHE
title: Pred
desc: ''
updated: 1633586987902
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


- differentiate between notes that represent something (e.g. topics, solutions) and notes that are something (vs, journal)
  - comes down to "is about" something vs "is (a literary) something"?
    - could come down to resources being terms (instead of topics) [[vs.terms-vs-topics]]
      - and contextual terms at that
    - literary because the only things that refer to something and also are the something they refer to (self-referentiality) are
      - literature
      - symbols
      - computer programs (and some pointers?)
      - maybe logical statement
  - using `type` for both seems wrong 
  - article is interesting b/c it can be both
  - this is different that the class-individual confusion
  - how much does it really matter?
  - I guess resources that are something are just a special case (subset)  of the resources that represent something  ^AQ6h3rFksAfc
   
## philosophy

- maybe get all the non-verb-form predicates out. consistency and readability over existing standards?