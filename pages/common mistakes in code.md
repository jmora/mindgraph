tags:: common mistakes
alias:: common mistakes in software engineering, common mistakes in software development

- misuse of [[OOP]]
  id:: 6391fba2-4ec2-45ab-8d33-d55aff1acffb
- excessive nesting
  id:: 6391fbaf-5c6d-4aa1-94b6-54d9eeaea1f2
  collapsed:: true
	- #[[personal opinion]] I still like LogSeq, though
- neglect data structures
  collapsed:: true
	- made worse when discarding standard data structures to favor the ((6391fba2-4ec2-45ab-8d33-d55aff1acffb))
- unnecessarily large scopes
  collapsed:: true
	- Related with ((6391fbaf-5c6d-4aa1-94b6-54d9eeaea1f2))
- no tests
  collapsed:: true
	- no excuses
- unnecessary configuration
  collapsed:: true
	- opposite of: [[convention over configuration]], [[progressive complexity disclosure]]
		-
	-
- documentation over [[clarity]]
- documentation over [[automation]]
- insufficient decoupling, or insufficient [[abstraction]]
- wrong abstraction
  id:: 6393b8b5-7909-41f4-b152-94a5c5739091
  collapsed:: true
	- e.g. make abstractions concrete by giving them unnecessary names
		- e.g. Python can handle duck typing, while Java may need classes with names. Result:
		  * what in Python may be a higher-order function, in Java becomes a package with definitions of interfaces and abstract classes like `AbstractHandlerFactory`, `AbstractHandlerFunction`,...
		  * some Python developers may consider the Java approach to be more “professional” (related: [[impostor syndrome]]) needlessly increasing the [[cognitive load]] to work with a codebase