---
id: s2AA4w4SyPFu44ylTFLQH
title: instanceOf
desc: the subject is a concrete example of a Class
updated: 1647827798362
created: 1633270478774
---
- [!] replace all in-Class occurences of instanceOf referring to other classes with subClassOf

- [[p.alsoKnownAs]] isA, is a, is an instance of the class
- [[p.hasDomain]] [[c.Resource]]
- [[p.hasRange]] [[c.Class]]
- [[p.instanceOf]] [[c.Pred]] 
- [[p.equivalentPredicate]] [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type)
- [[p.inverseOf]] ???
  - [ ] important thing to have a name for, maybe "hasClass" or "generalizationOf" or classOf or "hasType"
  - sometimes things (topics primarily/only) can be classes, without being Classes.
  - 

## instanceOf Discussion

- changed because 
  - "instanceOf" underscores that the subject is not a Class
  - it feels like, colloquially, "type" is ambiguous between hasType and isTypeOf; the latter can mean  something more like subClassOf
- isA is nice and compact, but maybe feels ambiguous for classes, e.g. "[a] digital garden is a website" 
- 
