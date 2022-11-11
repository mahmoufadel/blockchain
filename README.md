What was good and should be recognized
DEVELOPMENT EXPERIENCE AND KNOWLEDGE
- Define good quality code: Clean code, well defined requirements were mentioned, tested, patterns
- Understands why patters are important,
- Memory management explained in the good level, large object heap, GC, generations were mentioned
- He explained some about the token based authentication.
- Familiar with some techniques to avoid to use stolen tokens.
- He was able to explain how they integrated Angular and Xamarin clients with the API, but in the same time I think that not the best way to do that.
- Familiar with Redis cache, he was able to explain a scenario where it can be used, and what are the limitations.
- He knows some cloud design patterns and he was able to explain in details the circuit breaker.
- He has experience with CQRS design pattern as well, he mentioned benefits to use it.

+ .net core vs .net fw 
-- good points mentioned (DI being part of .net core, simpler, open source, lightweight, etc)
+ mentioned JIT - was able to describe the mechanics behind in high level
+ mentioned kestrel
+ mentioned good points for good quality code (patterns, clean code, tests, etc)
+ patterns - mentioned a few like strategy, singleton, etc
+ mentioned overuse of patterns as a potential negative
+ was able to elaborate on .net memory management in good detail
+ good comparison between value vs ref types
+ was able to elaborate on large object heap
+ was able to write up linq Where() signature (ext method, predicate, func, generics)

+ authentication - would implement it via a separate service
+ showed decent knowledge of JWT bearer token auth
+ angular-xamarin-api app explained in good detail
+ good architecture diagram understanding has been presented
+ good caching solutions and concepts have been mentioned
+ cloud patterns - mentioned message bus (rabbit MQ)
+ was able to explain curcuit breaker pattern
+ was able to explain CQRS on a good detail

Quality
- Quality gates in CI/CD: Explained correctly some of the elements and mentioned SonarQube, unit tests.
- Experienced with code review process.
- Unit testing: F.I.R.S.T explained.

ROLES PLAYED ON A PROJECT
- How to convince customer about automation testing: good points mentioned from the technical perspective, however for a non-technical person, it might have not been convincing enough

SOFTWARE PROCESS KNOWLEDGE
+ quality gates on CI pipeline - mentioned sonar
+ good practices mentioned for code reviews
+ mentioned pair programming
+ how to estimate unknown - mentioned and explained spike, tech debt
+ how to manage deadline - mentioned prioritizing, deciding on what gets delivered with the customer/PO
+ unplanned work - mentioned the strategy of planning for unplanned work buffer into each sprint

CUSTOMER RELATIONS
+ Missed deadline: He was able to handle this situation in a good way.
+ always involves customer's representatives and stakeholders when making decisions decisions like changing scope of sprint, or prioritizing deliverables
+ gave decent response on how to handle complaints from the customer's-side

LANGUAGE ABILITY
+ good enough English skills presented, however there's always room for improvement, so keep practicing

*****

DEVELOPMENT EXPERIENCE AND KNOWLEDGE
- Compare .NET f/w and .NET core, but mentioned only performance, DI containers, middlewares, some differences in usage. Was not able to explain how .NET Core application can be run on Linux. He could not convince me that he understands the differences in depths
- How AWS lambda can run .NET Core code.
- Value vs reference types .explained to junior: He mentioned value types are immutable, which is not true, but depends on the implementation, mentioned record but it's reference type.
- Finalize vs dispose vs destructor
- Linq Where: Was very slow, but at the end he was able to define something which can be a kind of Where signature.
- Number of stacks: He mentioned we have only one, but that is not true.
- He was able to explain what is implemented by lambda functions on his project, but doesn't know why it is a lambda and why not for e.g. Eventbridge.
- API gateway vs proxy service: He was not able to explain what is the difference between the responsibilities of these two components.
- He is not familiar with diagramming tools too much, does not use UML (only sketches), could not enumerate diagram types
- Not familiar with static architecture diagram.
- could not convincingly explain how AWS lambdas can run asp .net app (in general, could not convincingly explain how .NET Core can run on Linux, or other platforms)
- could not mention an antipattern (like singleton itself being both a pattern and antipattern as well)
- did not mention the performance penalty of copying of value types when reassigning
- could not elaborate on finalization queue and destructor - in the aspect of IDisposable
- missed clarity on number of stack (per thread)
- could not elaborate on tools for measuring unit test quality (like mutation tests)
- could not elaborate on Expression<>
- could not go details of of AWS lambdas
- proxy vs api-gateway - could not provide a detailed comparison
- could not mention diagram types for representing data flow
- could not list any cloud/architectural design pattern on his own

ROLES PLAYED ON A PROJECT
- how to convince customer about automation testing: good points mentioned from the technical perspective, however for a non-technical person, it might have not been convincing enough

SOFTWARE PROCESS KNOWLEDGE
- Scope changes: he'd handle scope change by reserving capacity in each sprint for unknown work, but there are many other ways to handle scope changes in a better way than constantly calculate with a placeholder.

- quality gates: just like with earlier topics, good technical points have been mentioned, however a D4 is more likely to talk with non-technical people, thus needs to have the ability to explain topics in a less technical way
- for quality gates he should have mentioned topics like (manual) testing, code reviews, UAT, etc

Reliability:
- Underperforming team: Needs more investigation and actions to improve performance of the team before escalation to the PM

Architectural Styles and Patterns
- https://www.linkedin.com/learning/microservices-foundations
- 
- [a link](https://martinfowler.com/articles/serverless.html)

