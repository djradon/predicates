---
id: s2AA4w4SyPFu44ylTFLQH
title: instanceOf
desc: the subject is a concrete example of a Class
updated: 1671306625349
created: 1633270478774
---


- [[p.alsoKnownAs]] isA, is a, is an instance of the class
- [[p.hasDomain]] [[c.Resource]]
- [[p.hasRange]] [[c.Class]]
- [[c.Sphere]] [[sphere.Ontological]] 
- [[p.equivalentPredicate]] [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type)
- [[p.inverseOf]] ???
  - [ ] important thing to have a name for, maybe "hasInstance"  or classOf
    - maybe not so important, when do classes need to refer to their instances? backlinks provides inventory 
  - sometimes things (topics primarily/only) can be classes, without being Classes.
  

## instanceOf Discussion

- changed because 
  - "instanceOf" underscores that the subject is not a Class
  - it feels like, colloquially, "type" is ambiguous between hasType and isTypeOf; the latter can mean  something more like subClassOf
- isA is nice and compact, but maybe feels ambiguous for classes, e.g. "[a] digital garden is a website" 
- 

## log

- [x] #gd replace all in-Class occurences of instanceOf referring to other classes with subClassOf
  [[2022.12.12]] there was only one... [[c.DSL]]