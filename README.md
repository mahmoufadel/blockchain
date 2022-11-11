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
- [Architectural Styles vs. Architectural Patterns vs. Design Patterns](https://herbertograca.com/2017/07/28/architectural-styles-vs-architectural-patterns-vs-design-patterns)
- [Monolithic vs. Microservices Architecture](https://articles.microservices.com/monolithic-vs-microservices-architecture-5c4848858f59)
- [Software Architecture: Patterns for Developers](https://www.linkedin.com/learning/software-architecture-patterns-for-developers)
- [Microservices Foundations](https://www.linkedin.com/learning/microservices-foundations)
- [Service-Oriented Architecture](https://www.ibm.com/cloud/learn/soa)
- [Serverless Architecture](https://martinfowler.com/articles/serverless.html)
- [What is a serverless microservice ](https://www.cloudflare.com/learning/serverless/glossary/serverless-microservice)
- [.NET Microservices: Architecture for Containerized .NET Applications](https://docs.microsoft.com/en-us/dotnet/architecture/microservices)
- [Breaking a Monolith into Microservices](https://www.linkedin.com/learning/software-architecture-breaking-a-monolith-into-microservices)
- [Serverless Architecture](https://www.linkedin.com/learning/serverless-architecture/understand-serverless)
- [How to Create Application Architecture Diagram Online? ](https://geekflare.com/create-application-architecture-diagram)
*****************************
Layered Architectures
- [Layered Architecture / N-Layer Architecture](https://www.oreilly.com/library/view/software-architecture-patterns/9781491971437/ch01.html)
- [﻿Clean architecture tutorial: Design for enterprise-scale apps](https://www.educative.io/blog/clean-architecture-tutorial)
- [Clean Architecture with ASP.NET Core 3.0 • Jason Taylor • GOTO 2019](https://www.youtube.com/watch?v=dK4Yb6-LxAk)
- [CleanArchitecture](https://github.com/jasontaylordev/CleanArchitecture)
- [Clean Architecture with ASP.NET Core 6](https://www.youtube.com/watch?v=lkmvnjypENw)
- [Domain-Driven Design within Layered Architectures](https://archfirst.org/domain-driven-design-6-layered-architecture)
- [Comparison of Domain-Driven Design and Clean Architecture Concepts](https://khalilstemmler.com/articles/software-design-architecture/domain-driven-design-vs-clean-architecture/)
- [Software Architecture AntiPatterns](https://sourcemaking.com/antipatterns/software-architecture-antipatterns)
- [Spaghetti Code](https://sourcemaking.com/antipatterns/spaghetti-code)
- [The Logical vs the Physical: Layered Architecture](https://www.freekpaans.nl/2016/02/the-logical-vs-the-physical-business-rules/)
- [Clean Architecture by Robert C. Martin](https://bookz.lab.epam.com/details/clean-architecture/9780134494166)
- [The Concept of Domain-Driven Design Explained](https://medium.com/microtica/the-concept-of-domain-driven-design-explained-3184c0fd7c3f)
- [DDD, Hexagonal, Onion, Clean, CQRS, … How I put it all together](https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together)
- [N-Tier / N-Layer Architecture](https://www.linkedin.com/pulse/n-tier-n-layer-architecture-swapnil-baxi)
- [Anemic Domain Model vs Full Domain Model](https://martinfowler.com/bliki/AnemicDomainModel.html)
- [The Anemic Domain Model is not an Anti-Pattern, it’s a SOLID design](https://blog.inf.ed.ac.uk/sapm/2014/02/04/the-anaemic-domain-model-is-no-anti-pattern-its-a-solid-design/)
*****************************
RESTful Web API
- [REST Architectural Constraints](https://restfulapi.net/rest-architectural-constraints/)
- [Statelessness in REST APIs](https://restfulapi.net/statelessness/)
- [Caching REST API Response](https://restfulapi.net/caching/)
- [REST API Versioning](https://restfulapi.net/versioning/)
- [Create web APIs with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/web-api)
- [ASP.NET Core web API documentation with Swagger / OpenAPI](https://docs.microsoft.com/en-us/aspnet/core/tutorials/web-api-help-pages-using-swagger)
- [Best practices for REST API](https://stackoverflow.blog/2020/03/02/best-practices-for-rest-api-design)
- [REST Resource Naming Guide](https://restfulapi.net/resource-naming/)
- [Use web API analyzers](https://docs.microsoft.com/en-us/aspnet/core/web-api/advanced/analyzers)
- [Richardson Maturity Model](https://martinfowler.com/articles/richardsonMaturityModel.html)
- [REST vs RPC: What problems are you trying to solve with your APIs?](https://cloud.google.com/blog/products/application-development/rest-vs-rpc-what-problems-are-you-trying-to-solve-with-your-apis)
- [Why your APIs should be entity-oriented](https://cloud.google.com/blog/products/api-management/why-your-web-apis-should-be-entity-oriented)
- [gRPC vs REST: Understanding gRPC, OpenAPI and REST and when to use them in API design](https://cloud.google.com/blog/products/api-management/understanding-grpc-openapi-and-rest-and-when-to-use-them)
- [ASP.NET Core 2: Building Cross-Platform Back-End Systems](https://bookz.lab.epam.com/details/modern-api-design-aspnet-core-2-building-cross-platform-back/9781484235188)
- [RESTful API Design Patterns and Best Practices](https://bookz.lab.epam.com/details/hands-restful-api-design-patterns-and-best-practices-design/9781788992664)
- [Welcome to OData](https://docs.microsoft.com/en-us/odata/overview)
- [OData Connected Service](https://docs.microsoft.com/en-us/odata/connectedservice/getting-started)
- [Practical REST API Guide](https://github.com/drminnaar/ranker)
- [Why HATEOAS is useless and what that means for REST](https://medium.com/@andreasreiser94/why-hateoas-is-useless-and-what-that-means-for-rest-a65194471bc8)

*********************************
Message Based Architecture. Message Broker
- [Message-oriented Architectures](https://blogs.msmvps.com/peterritchie/2011/07/14/message-oriented-architectures)
- [Asynchronous message-based communication](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/architect-microservice-container-applications/asynchronous-message-based-communication)
- [Message Driven vs Event Driven](https://developer.lightbend.com/docs/akka-platform-guide/concepts/message-driven-event-driven.html)
- [Message Brokers](https://www.ibm.com/cloud/learn/message-brokers)
- [5 use cases of message brokers. When you should consider adopting a message broker in your system?](https://tsh.io/blog/message-broker/)
- [List of message broker software](https://en.wikipedia.org/wiki/Message_broker#List_of_message_broker_software)
- [RabbitMQ Tutorials](https://www.rabbitmq.com/getstarted.html)
- [APACHE KAFKA QUICKSTART](https://kafka.apache.org/quickstart)
- [What is Azure Service Bus?](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview)
- [How to handle typical event-driven architecture failures](https://searchapparchitecture.techtarget.com/tip/How-to-handle-typical-event-driven-architecture-failures)
- [Understanding Failure Modes in Message and Event-based Systems](https://multithreaded.stitchfix.com/blog/2017/08/21/handling-messaging-failures/)

**************************
Security. Authentication & Authorization
- [Authentication and Authorization ](https://auth0.com/docs/get-started/identity-fundamentals/authentication-and-authorization)
- [Authorization basics](https://docs.microsoft.com/en-us/azure/active-directory/develop/authorization-basics)
- [Role-based access control for application developers](https://docs.microsoft.com/en-us/azure/active-directory/develop/custom-rbac-for-developers)
- [Modern Authentication - Rob Moore (video, 1h)](https://www.youtube.com/watch?v=X6a9bjNutEw)
- [Identity management](https://en.wikipedia.org/wiki/Identity_management)
- [Identity and Access Management Primer](https://curity.io/resources/learn/iam-primer)
- [Identity and Access Management: Technical Overview (video, 20m)](https://www.youtube.com/watch?v=Tcvsefz5DmA)
- [OAuth 2.0 and OpenID Connect (video, 1h)](https://www.youtube.com/watch?v=996OiexHze0)
- [OAuth 2.0 & OpenID Connect (OIDC): Technical Overview (video, 20m)](https://www.youtube.com/watch?v=rTzlF-U9Y6Y)
- [SAML 2.0: Technical Overview (video, 20m)](https://www.youtube.com/watch?v=SvppXbpv-5k)
- [Security tokens](https://docs.microsoft.com/en-us/azure/active-directory/develop/security-tokens)
- [ID Token and Access Token: What's the Difference?](https://auth0.com/blog/id-token-access-token-what-is-the-difference/)
- [Microsoft identity platform access tokens](https://docs.microsoft.com/en-us/azure/active-directory/develop/access-tokens)
- [Microsoft identity platform ID tokens](https://docs.microsoft.com/en-us/azure/active-directory/develop/id-tokens)
- [Microsoft identity platform refresh tokens](https://docs.microsoft.com/en-us/azure/active-directory/develop/refresh-tokens)
- [Configurable token lifetimes in the Microsoft identity platform (preview)](https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-configurable-token-lifetimes)
- [Diagrams of All The OpenID Connect Flows](https://darutk.medium.com/diagrams-of-all-the-openid-connect-flows-6968e3990660)
- [The Right Flow for the Job: Which OAuth 2.0 Flow Should I Use?](https://dzone.com/articles/the-right-flow-for-the-job-which-oauth-20-flow-sho)
- [What Is and How Does Single Sign-On Authentication Work?](https://auth0.com/blog/what-is-and-how-does-single-sign-on-work)
- [Introduction to Multi-Factor Authentication (MFA)](https://www.securid.com/blog/what-is-mfa/)
- [Overview of ASP.NET Core authentication](https://docs.microsoft.com/en-us/aspnet/core/security/authentication)
- [Introduction to authorization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/introduction)
- [Mastering Identity and Access Management with Microsoft Azure](https://bookz.lab.epam.com/details/mastering-identity-and-access-management-microsoft-azure/9781785889448)
- [API Authentication – Tokens vs Sessions](https://www.baeldung.com/cs/tokens-vs-sessions)
- [What really is the difference between session and token based authentication](https://dev.to/thecodearcher/what-really-is-the-difference-between-session-and-token-based-authentication-2o39)
- [Prevent Cross-Site Request Forgery (XSRF/CSRF) attacks in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/anti-request-forgery)
- [Prevent open redirect attacks in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/preventing-open-redirects)
- [Prevent Cross-Site Scripting (XSS) in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/cross-site-scripting)
- [Diagrams And Movies Of All The OAuth 2.0 Flows](https://darutk.medium.com/diagrams-and-movies-of-all-the-oauth-2-0-flows-194f3c3ade85)
- [Demystifying OAuth Flows](https://frontegg.com/blog/oauth-flows)
- [Welcome to IdentityServer4 (latest)](https://identityserver4.readthedocs.io/en/latest/index.html)
- [Duende IdentityServer v6 Documentation](https://docs.duendesoftware.com/identityserver/v6)
- [Azure Active Directory (SaaS solution – use your MSDN subscription)](https://azure.microsoft.com/en-us/services/active-directory/#overview)
- [AWS Identity and Access Management (IAM)](https://aws.amazon.com/iam)
- [Auth for All](https://www.okta.com/developers)
- [Auth0](https://auth0.com/developers)

**************************
API Gateways
- [Pattern: API Gateway / Backends for Frontends](https://microservices.io/patterns/apigateway.html)
- [Backends for Frontends pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/backends-for-frontends)
- [The API gateway pattern versus the Direct client-to-microservice communication](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/architect-microservice-container-applications/direct-client-to-microservice-communication-versus-the-api-gateway-pattern)
- [Overview. 14 Open Source and Managed API Gateway for Modern Applications](https://geekflare.com/api-gateway)
- [Ocelot Documentation](https://ocelot.readthedocs.io/en/latest/introduction/bigpicture.html)

**************************
Advanced Logging and Tracing
- [Serviceability (computer)](https://en.wikipedia.org/wiki/Serviceability_(computer)%20%C2%A0)
- [Observability](https://www.ibm.com/cloud/learn/observability)
- [What is the difference between Logging, Tracing & Profiling?](https://greeeg.com/differences-between-logging-tracing-profiling)
- [Logging in a distributed environment. Correlation contexts. ](https://systemadminspro.com/logging-in-a-net-microservice-environment/%C2%A0)
- [Application Performance Monitoring (APM) tools. Overview. ](https://solutionsreview.com/network-monitoring/best-application-performance-monitoring-tools/%C2%A0)
- [Azure Application Insights overview ](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview)
- [Dependency Tracking in Azure Application Insights](https://docs.microsoft.com/en-us/azure/azure-monitor/app/asp-net-dependencies#automatically-tracked-dependencies%C2%A0)
- [Distributed Tracing. Telemetry correlation in Application Insights ](https://docs.microsoft.com/en-us/azure/azure-monitor/app/correlation)
- [Status: OpenTelemetry Tracing Specification](https://opentelemetry.io/status)
- [OpenTelemetry .NET reaches v1.0 ](https://medium.com/opentelemetry/opentelemetry-net-reaches-v1-0-e7c5e975fd44)
- [open-telemetry](https://github.com/open-telemetry/opentelemetry-dotnet)

**************************
GraphQL API
- [Understanding RPC, REST and GraphQL](https://apisyouwonthate.com/blog/understanding-rpc-rest-and-graphql)
- [A no nonsense GraphQL and REST comparison](https://www.youtube.com/watch?v=vgm_uGmspMI)
- [GraphQL .NET Servers & Clients](https://graphql.org/code/#c-net)
- [Introduction to GraphQL (official guide)](https://graphql.org/learn/)
- [Introduction to GraphQL (hotchocolate)](https://chillicream.com/docs/hotchocolate/)
- [GraphQL Best Practices](https://graphql.org/learn/best-practices/)
- [Course: API Development in .NET with GraphQL](https://learn.epam.com/detailsPage?id=7c9ee1ea-3a2f-4387-8644-2570002e9241)
- [DataLoader | ChilliCream GraphQL Platform](https://chillicream.com/docs/hotchocolate/fetching-data/dataloader)
- [GraphQL .NET (graphql-dotnet.github.io)](https://graphql-dotnet.github.io/docs/guides/dataloader/)
- [Books: Learning GraphQL](https://bookz.lab.epam.com/details/learning-graphql-declarative-data-fetching-fast-modern-apps/9781492030713)
- [Books: Learning GraphQL [RU]](https://bookz.lab.epam.com/details/graphql-yazyk-zaprosov-dlya-sovremennyh-veb-prilozhenij/9785446111435)
- [Wrapping a REST API in GraphQL](https://graphql.org/blog/rest-api-graphql-wrapper)
- [DataLoader – Source code walkthrough](https://youtu.be/OQTnXNCDywA)

**************************
Code Quality. Metrics & Tools
- [Why source code quality is crucial?](https://www.rabitse.com/blog/why-source-code-quality-is-crucial/)
- [What is Static Analysis? An Explanation for Everyone](https://blog.ndepend.com/static-analysis-explanation-everyone/)
- [Code quality rules](https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/quality-rules/)
- [Overview of source code analysis](https://docs.microsoft.com/en-us/visualstudio/code-quality/roslyn-analyzers-overview?view=vs-2019)
- [How to enforce a consistent coding style in your projects](https://www.meziantou.net/how-to-enforce-a-consistent-coding-style-in-your-projects.htm)
- [The Roslyn analyzers I use in my projects](https://www.meziantou.net/the-roslyn-analyzers-i-use.htm)
- [Seven reasons that Roslyn-based Code Analysers are awesome](https://blog.tdwright.co.uk/2018/12/10/seven-reasons-that-roslyn-based-code-analysers-are-awesome/?preview=true)
- [Static Code Analysis for your .NET projects](https://worldwildweb.dev/static-code-analysis-for-your-net-projects)
- [EditorConfig: The Key to Consistent Coding Style in Visual Studio](https://www.synergex.com/editorconfig-key-to-consistent-coding-style/)
- [Code style rules](https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/style-rules/)
- [Distribution of a Common EditorConfig File to Multiple .NET Projects](https://devzone.channeladam.com/notebooks/languages/dotnet/editorconfig-distribution/)
- [Create portable, custom editor settings with EditorConfig](https://docs.microsoft.com/en-us/visualstudio/ide/create-portable-custom-editor-options/)
- [dotnet format](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-format)
- [C# code style by EditorConfig in .NET 5 SDK and beyond](https://developers.mews.com/c-code-style-by-editorconfig-in-net-5-sdk-and-beyond/)
- [Top 7 Static Code Analysis Tools](https://dzone.com/articles/top-7-static-code-analysis-tools)
- [Sonarqube: What it is and why to use it?](https://www.loginradius.com/blog/async/sonarqube/)
- [How to Use SonarQube — Effective Usage of Static Analysis](https://www.objectivity.co.uk/blog/how-to-use-sonarqube-static-code-analysis/)
- [Get Started with Git Hooks](https://medium.com/@f3igao/get-started-with-git-hooks-5a489725c639)
- [8.3 Customizing Git - Git Hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
- [pre-commit](https://pre-commit.com/)
- [dotnet](https://github.com/dotnet/format)
- [Embedding dotnet format in your development cycle](https://gsferreira.com/archive/2022/embedding-dotnet-format-in-your-development-cycle/)
- [What are quality gates and why should you have them?](https://www.tacticalprojectmanager.com/project-quality-gates)
- [Quality Gates — A must have thing for the code analysis process](https://medium.com/@tarunprakash/quality-gates-a-must-have-thing-for-the-code-analysis-process-75b33d6b49dc)
- [Agile Software Development: Code Quality](https://learn.epam.com/detailsPage?id=c4912271-69e1-4506-a646-5bde24c58c71)
************************
CI/CD
- [Continuous integration vs. delivery vs. deployment](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)
- [What is CI/CD? Continuous Integration & Continuous Delivery](https://www.katalon.com/resources-center/blog/ci-cd-introduction)
- [CONTINUOUS INTEGRATION](https://www.thoughtworks.com/continuous-integration)
- [What is Continuous Integration? 11 Key Practices and Principles](https://dzone.com/articles/what-is-continuous-integration-11-key-practices-an)
- [Branching Strategies](https://launchdarkly.com/blog/git-branching-strategies-vs-trunk-based-development)
- [Six Strategies for Application Deployment](https://thenewstack.io/deployment-strategies)
- [Intro to deployment strategies: blue-green, canary, and more](https://dev.to/mostlyjason/intro-to-deployment-strategies-blue-green-canary-and-more-3a3)
- [CI/CD tools](https://www.linkedin.com/learning/continuous-integration-tools)
***********************
SDLC. Estimations
- [Software Development Life Cycle (SDLC)](https://www.linkedin.com/learning/software-development-life-cycle-sdlc/waterfall-model-brief-overview)
- [Software Development Life Cycle (SDLC) [Section 2]](https://www.linkedin.com/learning/software-development-life-cycle-sdlc/scrum-overview)
- [Agile Software Development](https://www.linkedin.com/learning/agile-software-development/scrum-introduction)
- [Agile Software Development [Section 2]](https://www.linkedin.com/learning/agile-software-development/lean-history)
- [Agile Development: KPIs for the Scrum Teams](https://medium.com/swlh/agile-development-kpis-for-scrum-teams-a84a0381d469)
- [The Most Important Lean KPIs You Need to Track for Your Business](https://kanbanize.com/blog/lean-kpis-for-business)
- [6 Scaled Agile Frameworks – Which One Is Right For You?](https://www.digite.com/blog/scaled-agile-frameworks/)
- [Agile Software Development: Transforming Your Organization](https://www.linkedin.com/learning/agile-software-development-transforming-your-organization/start-with-your-teams)
- [Estimation Techniques - Overview](https://www.tutorialspoint.com/estimation_techniques/estimation_techniques_overview.htm)
- [Top 8 Agile Estimation Techniques (Explained with Examples)](https://www.netsolutions.com/insights/how-to-estimate-projects-in-agile)
- [Agile software engineering techniques](https://www.linkedin.com/learning/agile-software-development/extreme-programming-xp)
- [Software estimation - demystifying the black art](https://bookz.lab.epam.com/details/software-estimation-demystifying-black-art/9780735605350)
- [Agile Estimating and Planning](https://www.amazon.com/Agile-Estimating-Planning-Mike-Cohn/dp/0131479415)
- [Agile Estimating](https://www.youtube.com/watch?v=37zfyncCpkA)
- [Advanced Topics in Agile Planning](https://www.youtube.com/watch?v=D2r2KryYAaY)
- [Agile at Work: Planning with Agile User Stories](https://www.linkedin.com/learning/agile-at-work-planning-with-agile-user-stories/planning-with-user-stories)
- [Software Design: From Requirements to Release](https://www.linkedin.com/learning/software-design-from-requirements-to-release/going-from-requirements-to-release)
