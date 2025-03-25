## <p align = "center">Yuri Zhuravel

**<p align = "center">Back-end Scala Engineer | High-load microservices | DevOps on AWS infra**

<div><p align = "center"><a href="https://www.linkedin.com/in/yurizhuravel">linkedin.com/in/yurizhuravel</a></div>

I have eight years of enterprise experience with high-load Scala microservices on resilient, scalable and cost-effective cloud infrastructure. Now returning from a short family career break, I am ready to design, build and maintain your back-end services and CI/CD in a permanent or contractor position.

In my most recent role at ITV, I worked through complete lifecycles (from initial design to final decommission) of several big projects primarily written in functional Scala. As well as creating and updating them, my particular focus was on designing a convenient and efficient CI/CD from code to prod on complex and flexibly scalable AWS infrastructure, while paying extra attention to keeping the cloud costs in check.

I'm a career-changer who plunged into commercial coding rather late in life. Before that, I used to be a Formula One team member, BBC journalist and team lead, interpreter and due diligence analyst. My interest in programming brought me to Makers Academy, a leading developer bootcamp for solid foundation in modern software engineering practices. Subsequent years of commercial experience with a top global bank and the UK's biggest commercial broadcaster gave me invaluable insights into how complex software systems are designed, delivered, scaled and maintained.

---
### <p align = "center">What I can do:</a>

#### Microservices and lambdas in functional Scala

I consider microservice architecture to be a good match for complicated systems, allowing for flexibility, independent scalability and maintenance. **Scala**, with a robust JVM foundation as well as modern functional toolset, has proved to be dependable and resilient for that. It can also be successfully used in lambdas, with some limiting considerations, primarily the size - that's why lately I've started looking at Go when more lightweight and simple solution are enough. I'd also used Clojure for enterprise microservices and liked it, but my experience with it was a while back.

<b>Tech:</b> Functional Scala (Cats); Elm for frontend; Go for quick scripting and lightweight tooling needs, AWS lambdas JVM or Scala.js flavour; GraphQL APIs; Clojure (a while ago); Github Actions, Docker, Jenkins, Terraform on the CI and infra side; various DBs but mostly Postgres; RabbitMQ, SQS/SNS and Kafka messaging; logging, metrics and dashboards based on Splunk, Kibana and Grafana; Gatling for load testing etc

#### Devops and CI/CD

My very first commercial experience quickly showed that constantly delivering small auto-tested incremental changes is highly effective even in a very conservative and regulated banking environment with limited scope for CI change. Having realised that, I turned attention to devops practices and, in my time with ITV, I delivered two major releases of our CI/CD setup from the dev side, working with platform engineers to align our approaches and iron out wrinkles.

<b>Tech:</b> GitHub Actions, AWS infra, Docker, Kubernetes, Jenkins, Terraform, Splunk

#### AWS cloud cost control

A big issue for enterprise cloud users these days. At ITV, I was in a small task force dedicated to getting as much relevant data from AWS Cost Explorer API as possible, and then using it to scale and adjust our cloud utilisation to minimise resource overbooking and unnecessary costs

Tech: AWS Cost Explorer API, Scala and Go lambdas, Prometheus as service metrics source, output to Splunk 

#### Agile

A much-abused term, often heard in the least agile environments imaginable. I am a big fan of it when practiced properly: daily stand-ups with the dev team and product owners, continuous release cycle, regular retros and well-maintained ticketing system do wonders for team productivity.

Tech: Kanban with Trello, Jira etc

#### TDD

Once a dedicated believer in red-green-refactor and 100% test coverage, I now came to realise that it is not always possible to religiously adhere to this approach in real life with its strict time/budget constraints and pressing business needs. However, given an opportunity, I'd always write tests.

#### Teamwork

I have considerable experience of working in and leading diverse multilingual teams under tight deadlines and with multiple stakeholder interests involved.

---
### <p align = "center">Work experience and stack in more detail:

**ITV | London, UK** (Feb 2018 - Aug 2024)<br>
*Core Engineer*

**Dev side:**<br>
* Modern functional Scala/Cats microservices driven by endpoints or listening to messages on RabbitMQ (legacy), AWS SQS/SNS (when a 3rd party doesn't do Kafka), or Kafka (preferred)
* cron jobs, same as above but schedule-driven to minimise AWS costs, or
* event-driven lambdas either in ScalaJS (legacy maintenance), native JVM (main bulk), and Golang (recent, and I love it for the purpose)
* Aiven-hosted Kafka and terraform provider, with in-house Kafka management and templating (using Dhall) 
* Primarily Postgres DBs, or Dynamo where key-value store is enough
* Elm for basic front-end
* Varnish for own quick caching when needed / Akamai for heavy lifting
* REST or GraphQL APIs (writing own / integrating with 3rd parties)
* Gatling for load testing
* Prometheus/Kibana/Grafana for metrics
* Splunk for usage monitoring and operational alerting
* GitHub Actions for testing/packaging code as Docker images and delivering to AWS EKS, which is the handover point for:


**Ops side:**<br>
* Kubernetes with event-driven autoscaler running Docker containers on AWS infra
* Current GHA/Jenkins CI: Docker images fetched from EKS and orchestrated by Kubernetes/Karpenter/KEDA on AWS S3. Fast, reliable up- and downscaling triggered by CPU/memory/endpoint load/kafka load/schedule and suchlike
* Legacy Jenkins CI: JVM fat jars deployed directly onto S3 instances with an in-house blue/green deployment tool written in Scala
* Modular management of terraform components/ AWS roles/ permissions for devs and for code
* Making sure that all of the above is as backwards compatible as possible
* Killing old stuff with fire, because:

**AWS Cloud Cost Optimisation:**<br>
To keep the AWS costs in check, I wrote a usage monitoring tool running as a deployment in Kubernetes clusters and scraping CPU/memory usage data from Prometheus there, as well as costs data directly from AWS Cost Explorer

---

**HSBC Global Banking And Markets | London, UK** (Nov 2016 - Oct 2017)<br>
*Digital Transformation Software Developer*

 Primary language: Clojure. Our team delivered an integration solution which linked Evolve, an award-winning FX platform based on microservices architecture and built under devops and agile principles, with HSBCNet - one of the most-used corporate payments applications in the world. To this end, we developed a new suite of microservices and modified existing legacy code to use them.

---

**Makers Consultants** (Nov 2016 - Jan 2018)<br>
*Software Development Consultant*<br>
I've been one of the first software consultants employed by Makers Academy when the company decided to branch into this line of services.

---

**BBC World Service (Russian)** (2000 - 2016 with breaks in between)    
*Journalist / Senior Producer / Video Lead*

**Celebro Media** (2014 - 2015)   
*Head of News*

**Marussia Motors/ Marussia Virgin Racing** (2011 - 2012)    
*Head of International Communications / F1 Team Liaison*  

**Muz-TV (Moscow)** (1998 - 2000)   
*Chief News Editor*

**UTV (Belfast)** (1995)   
*PR executive*

### <p align = "center">Where I studied</a>

#### Makers Academy (June 2016 to September 2016)

- Pair programming, independent learning and problem-solving
- OOP, Agile, TDD, SOLID, MVC
- Software Craftsmanship
- Ruby, Rails, Javascript, Node.js
- Unity 3D with C# scripting
- RSpec, Capybara, Jasmine, Mocha, Zombie, Unity Test Tools

#### Moscow State University for International Relations (1991 to 1998 - with a career development break)

- Law
- German and English
- LLB and an additional postgrad specialist degree in International Trade Law
#### BBC professional certificates

- Training for Trainers
- Leadership
- Recruitment: Fair Selection

### <p align = "center">Other stuff</a>

- Professional stills and video filming
- Video editing with Adobe Premiere, Final Cut Pro X and Quantel QEdit
- Photo processing with Adobe Photoshop and Lightroom
- Enterprise news and content management tools (ENPS, BBC CPS, TopCat, Jupiter)

#### Languages

Russian, English, a bit of German and Belarussian

#### And finally

I like drums, disc golf and things on two wheels, motorised or not
