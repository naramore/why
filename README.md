# Software Development References
## Keynotes

- [Simple Made Easy](https://www.infoq.com/presentations/Simple-Made-Easy)
- [Without Resilience, Nothing Else Matters](https://www.youtube.com/watch?v=ktBlGj5gGUY&t=139s)

  1. If you application is not running, it is providing **ZERO** value
  2. Therefore, resilience should be very important
  3. Resilience is not something easily appended to an application, it must be designed with resilience in mind

- [The Value of Values](https://www.infoq.com/presentations/Value-Values)
- [Programming with Hand Tools](https://youtu.be/ShEez0JkOFw)
- [On Abstraction](https://youtu.be/x9pxbnFC4aQ)
- [Stuart Halloway - Narcissistic Design](https://www.youtube.com/watch?v=LEZv-kQUSi4)
- [REBL - Stuart Halloway](https://www.youtube.com/watch?v=c52QhiXsmyI)
- [John Hughes - Testing the Hard Stuff and Staying Sane](https://www.youtube.com/watch?v=zi0rHwfiX1Q)
- [Fred Hebert - Operable Erlang and Elixir](https://youtu.be/OR2Gc6_Le2U)

  > Monitoring generally tells you only whether something is wrong, but not
  > what is wrong, nor why it is wrong. It is ultimately knowing that the
  > system has a fever, but not knowing what the disease is.
  >
  > The identification of a fault is more generally resolved through
  > observability. Whereas monitoring asks "how are you doing?", observability
  > asks "what are you doing?".
  >
  > Observability comes from control theory—self-regulating systems such as
  > speed control on a car, or flight stabilizers in airplanes. The gist of
  > observability according to control theory is that by looking at the outputs
  > of a system, you can infer its internal state. This results in the same view,
  > but now you know what's inside
  >
  > [Operable Software](https://ferd.ca/operable-software.html)

## Important

- [Is Quality Worth the Cost?](https://martinfowler.com/articles/is-quality-worth-cost.html)
- [Operable Software](https://ferd.ca/operable-software.html)
- [Zero-Bug Software Development](https://medium.com/qualityfaster/the-zero-bug-policy-b0bd987be684)
- [The Beautiful Mess](https://cutlefish.substack.com/)
- [North Star Playbook](https://amplitude.com/north-star/)
- [Spine Model](https://spinemodel.info/)
- [Simon Sinek](https://simonsinek.com/)
  - [Find Your WHY](https://simonsinek.com/find-your-why/?ref=mainNav)
  - [Learn to Lead](https://simonsinek.com/learn-to-lead/?ref=mainNav)
  - [Transform Your Culture](https://simonsinek.com/transform-your-culture/?ref=mainNav)
  - [The Infinite Game](https://simonsinek.com/the-infinite-game)
- [Rich Hickey - Hammock Driven Development](https://melreams.com/2017/05/rich-hickey-hammock-driven-development/)

  Hammock Driven Development is a strategy for solving hard problems.

  > Here’s my recap of one of the talks from that list, Hammock Driven
  > Development by Rich Hickey. In it he describes his process for solving
  > hard problems, which is obviously a huge part of what programmers do and
  > is probably useful for just about anyone else too.
  >
  > [Rich Hickey - Hammock Driven Development](https://melreams.com/2017/05/rich-hickey-hammock-driven-development/)

  1. State the problem.
      - Say it out loud.
      - Talk with team member about it.
      - Write it down if nothing else.
  2. Understand the problem
      - What do you know already (facts, context, constraints)?
      - What don’t you know?
      - Are there related problems?
          - Hint: there are.
      - Your problem is almost certainly not unique in the history of the world.
      - And if you’re going to bother to figure all that stuff out, write it down!
  3. Be discerning.
      - Not everything is awesome!
      - Look for problems in your proposed solutions and try to solve those too right away up front.
      - Do you think there aren’t any tradeoffs in your proposed solution?
          - Not likely...
          - It’s much more likely you’re missing something.
      - You should have questions
          - Nobody knows everything!
          - If you don’t have questions, you’re missing something.
      - Write all this stuff down too.
  4. More input better output.
      - You can’t connect things you don’t know about.
      - Read in and around your space 
          - Not just your exact problem, also similar stuff so that you can let that simmer and let your brain make connections.
      - Look (critically!) at other solutions too.
          - Great solutions can come from tearing apart someone else’s idea.
  5. Tradeoffs.
      - Everybody says design is about tradeoffs, but...
          - You need to look at at least two possible solutions and figure out what’s good and bad about those things before you can really say you made a tradeoff.
      - Write this down too!
          - You may be seeing a theme here :)
  6. Focus.
      - This is where the hammock comes in.
      - The computer is a prime source of distractions
          - You need to get away from the computer if you want to focus.
      - Loading up your background mind and then letting it work.
      - Leave the problem alone for a while and let your background mind do its thing.
  7. (Optional) Don’t stay stuck.
      - If you have another problem to work on, do that when you feel stuck instead of just sitting there and staying stuck.
      - If you don’t have another problem or really need to stay focused on your current one...
          - Gather more input
          - Talk with more people if you can
          - And go through the whole process again

  See [Rich Hickey - Hammock Driven Development](https://melreams.com/2017/05/rich-hickey-hammock-driven-development/)
  and [Hammock Driven Development](https://www.youtube.com/watch?v=f84n5oFoZBc)
  for more detail.

- [The Hitchhiker's Guide to the Unexpected](https://ferd.ca/the-hitchhiker-s-guide-to-the-unexpected.html)
- [Designing Data-Intensive Applications: Chapter 1. Reliable, Scalable, and Maintainable Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/ch01.html)
- [Define Roles By What Each Person Increasingly Knows](https://jessitron.com/2020/07/29/define-roles-by-what-does-each-person-increasingly-knows/)
- [The Philosophy of Infrastructure & SRE](https://engineering.dollarshaveclub.com/the-philosophy-of-infrastructure-sre-9875e71019b4)
- [Gall's Law](https://en.wikipedia.org/wiki/John_Gall_(author)#Gall's_law)

  > "A complex system that works is invariably found to have evolved from 
  >  a simple system that worked. A complex system designed from scratch 
  >  never works and cannot be patched up to make it work. You have to 
  >  start over with a working simple system."
  >
  > John Gall (1975) Systemantics: How Systems Really Work and How They Fail p. 71

- [Things You Should Never Do, Part 1](https://www.joelonsoftware.com/2000/04/06/things-you-should-never-do-part-i/)
- [How Software Companies Die](https://gist.github.com/drawcode/e86fb28d0d58b12f73e9fc8cfd1ffbca)

## Design, Development & Testing

- [The Twelve-Factor App](https://12factor.net/) are a series of highly applicable,
language-independent qualities and practices that are valuable in developing
applications and services. There *will* be overlap between many 12-Factor points
and the goals list above, but considering this is a well-known and adopted standard,
it deserves explicit mention.

  1. [Codebase](https://12factor.net/codebase) - One codebase tracked in revision control, many deploys
  2. [Dependencies](https://12factor.net/dependencies) - Explicitly declare and isolate dependencies
  3. [Config](https://12factor.net/config) - Store config in the environment
  4. [Backing Services](https://12factor.net/backing-services) - Treat backing services as attached resources
  5. [Build, Release, Run](https://12factor.net/build-release-run) - Strictly separate build and run stages
  6. [Processes](https://12factor.net/processes) - Execute the app as one or more stateless processes
  7. [Port Binding](https://12factor.net/port-binding) - Export services via port binding
  8. [Concurrency](https://12factor.net/concurrency) - Scale out via the process model
  9. [Disposability](https://12factor.net/disposability) - Maximize robustness with fast startup and graceful shutdown
  10. [Dev/Prod Parity](https://12factor.net/dev-prod-parity) - Keep development, staging, and production as similar as possible
  11. [Logs](https://12factor.net/logs) - Treat logs as event streams
  12. [Admin Processes](https://12factor.net/admin-processes) - Run admin/management tasks as one-off processes

- [Agile Values](https://agilemanifesto.org/)

  - **Individuals and Interactions** Over Processes and Tools
  - **Working Software** Over Comprehensive Documentation
  - **Customer Collaboration** Over Contract Negotiation
  - **Responding to Change** Over Following a Plan

- [Agile Principles](https://agilemanifesto.org/principles.html)

  - Our highest priority is to satisfy the customer through early and continuous deliveryof valuable software.
  - Welcome changing requirements, even late in development. Agile processes harness change for the customer's competitive advantage.
  - Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale.
  - Business people and developers must work together daily throughout the project.
  - Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.
  - The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.
  - Working software is the primary measure of progress.
  - Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.
  - Continuous attention to technical excellence and good design enhances agility.
  - Simplicity--the art of maximizing the amount of work not done--is essential.
  - The best architectures, requirements, and designs emerge from self-organizing teams.
  - At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.

- [Test Driven Development](https://martinfowler.com/bliki/TestDrivenDevelopment.html)
  - Test driven development is focused more on the implementation loop of the development process, and is summarized as follows:
    - Write a test for the next bit of functionality you want to add.
    - Write the functional code until the test passes.
    - Refactor both new and old code to make it well structured.

- [Objects and Data Structures](https://blog.cleancoder.com/uncle-bob/2019/06/16/ObjectsAndDataStructures.html)
- [Execution in the Kingdom of Nouns](https://steve-yegge.blogspot.com/2006/03/execution-in-kingdom-of-nouns.html)
- [Best Software Engineering Principles](https://dev.to/luminousmen/what-are-the-best-software-engineering-principles--3p8n)
- [Principles of Modern Application Development](https://www.nginx.com/blog/principles-of-modern-application-development/)
- [Our Development Philosophy: Architecture, Design Patterns and Programming Principles](https://www.git-tower.com/blog/dev-philosophy-1/)
- [Our Development Philosophy: Collaboration & Testing](https://www.git-tower.com/blog/dev-philosophy-2/)
- [Test Quality in CI/CD](https://www.sealights.io/blog/test-quality-in-ci-cd-expert-roundup/)
- [Step Away from the Computer or Hammock-driven Development](https://github.com/matthiasn/talk-transcripts/blob/master/Hickey_Rich/HammockDrivenDev.md)
- [Mutation Testing](https://en.wikipedia.org/wiki/Mutation_testing)

## Architecture

- [Software Architecture Guide](https://martinfowler.com/architecture/)
- [Little Architecture](https://blog.cleancoder.com/uncle-bob/2016/01/04/ALittleArchitecture.html)
- [The Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
- [Architectural Decision Records](https://adr.github.io/)
- [How to Build Observable Distributed Systems](https://qconlondon.com/system/files/presentation-slides/qcon_london_-_building_observable_distributed_systems.pdf)
- [Branching Patterns](https://martinfowler.com/articles/branching-patterns.html)
- [What Color is Your Function?](http://journal.stuffwithstuff.com/2015/02/01/what-color-is-your-function/)

## Object Orientation

- [In Defense of the SOLID Principles](https://blog.ndepend.com/defense-solid-principles/)
- [The Principles of Object-Oriented Design](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
- [Object Orientation is an Expensive Disaster which Must End](http://www.smashcompany.com/technology/object-oriented-programming-is-an-expensive-disaster-which-must-end)
- [Object Oriented Programming: The Trillion Dollar Disaster](https://medium.com/better-programming/object-oriented-programming-the-trillion-dollar-disaster-92a4b666c7c7)
- [Why Functional Programming Matters](https://hackernoon.com/why-functional-programming-matters-c647f56a7691)

## Blogs

- [Clean Coder](https://blog.cleancoder.com/)
- [Martin Fowler's Blog](https://martinfowler.com/)
  - [Consumer-Driven Contracts: A Service Evolution Pattern](https://martinfowler.com/articles/consumerDrivenContracts.html)
  - [Testing Strategies in a Microservice Architecture](https://martinfowler.com/articles/microservice-testing/)
  - [Test Driven Development](https://martinfowler.com/bliki/TestDrivenDevelopment.html)
  - [Bounded Context](https://martinfowler.com/bliki/BoundedContext.html)
- [Aphyr - Strong Consistency Models](https://aphyr.com/posts/313-strong-consistency-models)
- [Discord Engineering](https://blog.discord.com/tagged/engineering)
- [Dollar Shave Club Engineering](https://engineering.dollarshaveclub.com/)
- [Joe Armstrong - Erlang and other stuff](https://joearms.github.io/#Index)
- ["My Bad Opinions"](https://ferd.ca/)
- [Lambda the Ultimate](http://lambda-the-ultimate.org/)
- [Ramblings from Jessie](https://blog.jessfraz.com/)
- [Very Big Things - Towards Maintainable Elixir](https://medium.com/very-big-things)
  - [The Development Process](https://medium.com/very-big-things/towards-maintainable-elixir-the-development-process-205ee257c109)
  - [The Core and the Interface](https://medium.com/very-big-things/towards-maintainable-elixir-the-core-and-the-interface-c267f0da43)
  - [Boundaries](https://medium.com/very-big-things/towards-maintainable-elixir-boundaries-ba013c731c0a)
  - [The Anatomy of a Core Module](https://medium.com/very-big-things/towards-maintainable-elixir-the-anatomy-of-a-core-module-b7372009ca6d)
  - [Testing](https://medium.com/very-big-things/towards-maintainable-elixir-testing-b32ac0604b99)

Git, Datalog and TerminusDB:
- [Git Internals - Git Objects](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects)
- [Git Compression of Blobs and Packfiles](https://gist.github.com/matthewmccullough/2695758)
- [Introduction to Datalog](https://x775.net/2019/03/18/Introduction-to-Datalog.html)
  - [Datalog Materialization](https://www.cs.ox.ac.uk/people/boris.motik/pubs/mnph19maintenance-revisited.pdf)
  - [Datalog Inference Algorithms](https://www.ics.uci.edu/~welling/teaching/271fall09/FOLinference271-f09.pdf)
- [TerminusDB Delta Encoding](https://terminusdb.com/t/papers/terminusdb-git.pdf)
  - [HDT Specs](https://www.rdfhdt.org/technical-specification/)
  - [Rank and Select Queries](https://users.dcc.uchile.cl/~gnavarro/algoritmos/ps/wea05.pdf)
  - [High-Order Entropy-Compressed Text Indexes](http://pages.di.unipi.it/grossi/PAPERS/sodaconf03FINAL-LATEST.pdf)
  - [Exchange and Consumption of Huge RDF Data](https://dataweb.infor.uva.es/wp-content/uploads/2012/02/eswc2012.pdf)

## Tools

- [Cloud Native Computing Foundation](https://www.cncf.io/)
- [GitHub](https://github.com/)
  - [Gitpod](https://www.gitpod.io/)
  - [Codespaces](https://github.com/features/codespaces)
  - [Actions](https://github.com/features/actions)
  - [Codacy](https://www.codacy.com/)
  - [Codecov](https://codecov.io/)
  - [Dependabot](https://dependabot.com/)
  - [GitGuardian](https://www.gitguardian.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
  - [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  - [Remote](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
  - [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
  - [CodeTour](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.codetour)
- [GraphQL](https://graphql.org/)
- [Pact](https://pact.io/)
- [Elixir](https://elixir-lang.org/)
  - [Erlang Worldview](https://en.wikipedia.org/wiki/Erlang_(programming_language)#Processes)
  - [Phoenix Framework](https://phoenixframework.org/)
    - [The Road to 2 million Websocket Connections](https://www.phoenixframework.org/blog/the-road-to-2-million-websocket-connections)
  - [Managing Two Million Webservers](https://joearms.github.io/index.html#2016-03-13%20Managing%20Two%20Million%20Webservers)
  - [How Discord Scaled Elixir to 5,000,000 Concurrent Users](https://blog.discord.com/scaling-elixir-f9b8e1e7c29b)
- [Clojure](https://clojure.org/)
  - [Jepsen](http://jepsen.io/)
  - [Pathom](https://github.com/wilkerlucio/pathom)
  - [Datomic](https://www.datomic.com/)
    - [Unofficial Guide to Datomic Internals](https://tonsky.me/blog/unofficial-guide-to-datomic-internals/)
  - [edn](https://github.com/edn-format/edn)
  - [eql](https://github.com/edn-query-language/eql)
  - [transit](https://github.com/cognitect/transit-format)
- [Open Telemetry](https://opentelemetry.io/)
  - [Jaeger](https://www.jaegertracing.io/)
- [Kubernetes](https://kubernetes.io/)
  - [Helm](https://helm.sh/)
  - [Draft](https://draft.sh/)
  - [Rancher](https://rancher.com/)
- [Docker](https://www.docker.com/)
- [Prometheus](https://prometheus.io/)
  - [Thanos](https://thanos.io/)
  - [Cortex](https://github.com/cortexproject/cortex)
- [Sysdig](https://sysdig.com/)
- [Extended Berkley Packet Filters](http://www.brendangregg.com/ebpf.html)
- [osquery](https://osquery.io/)
- [Grafana](https://grafana.com/)
- [InfluxDB](https://www.influxdata.com/)
- [Elasticsearch](https://www.elastic.co/)
  - [Fluentd](https://www.fluentd.org/)
  - [Kibana](https://www.elastic.co/kibana)
- [Sentry](https://sentry.io/welcome/)
- [Jenkins X](https://jenkins-x.io/) (the stuff below unnecessary?)
  - [Acyl](https://github.com/dollarshaveclub/acyl)
  - [Jenkins](https://www.jenkins.io/)
  - [Concourse](https://concourse-ci.org/)
- [Vault](https://www.vaultproject.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Redis](https://redis.io/)
- [RabbitMQ](https://www.rabbitmq.com/)
- [Kafka](https://kafka.apache.org/)
- [Docker Security Benchmark](https://github.com/docker/docker-bench-security)
- [Kubernetes Security Benchmark](https://github.com/mesosphere/kubernetes-security-benchmark)
- [TerminusDB](https://terminusdb.com/)
- [Operator Framework](https://operatorframework.io/)
- [KubeLinter](https://github.com/stackrox/kube-linter)
- [Falco](https://github.com/falcosecurity/falco)
