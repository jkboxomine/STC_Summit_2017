
# STC Summit 2017
##### May 7 - 10, 2017
##### Gaylord National Resort & Convention Center
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Summit2017_dates.png?raw=true)

# Venue
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Venue.jpg?raw=true)

# Conference Hall
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/ConferenceHall.jpg?raw=true)


# Demo Booth
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/DemoBooth.jpg?raw=true)

# Books
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Books.jpg?raw=true)

# Day 1 - Session #1
## [User Experience Strategies for Winning API Documentation](https://stcsummit2017.sched.com/event/8tj4/user-experience-strategies-for-winning-api-documentation)
### Eric Cressey (Senior UX Content Writer, Symantec)
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day1_Session1.jpg?raw=true)

# API User Experience
## Obstacles in API learning
- Documentation 포함 resource 부족/부적절 > API 구조/설계

## What causes these issues?
- Poor communication
- Lack of writer engagement
- Inadequate technical review

# 1. Make it about Usability

## Usability goes beyond docs
- 30% bugs related to usability
- Development team: missing features, consistency, etc.
- Others => Technical team

## Methods for evaluating usability
1. Heuristic evaluations
1. Usability studies
1. Interview and surveys
1. Collecting user feedback is key

### Heuristic evaluations
- The same factor applied to UI can be good for evaluating documentation
  - Naming: clear, consistent, recognizable
  - Design Consistency
  - Error handling message: clear, informative
  - Efficiency of use

### Usability studies
- Identify documentation and structural issues
- Have develpers come in and use the API
- Encourage them to talk through their action

**=> facilitate feedback from development team**


### Interview and surveys
- Identify user experience and documentation issues
- Quick, easy and cheap
- Use API users to establish metrics and create personas

### Collecting user feedback is key
- Make it part of your process
- Do it as often as you can 
- Record your sesions and take good notes
- Track responses over time

# 2. Be a team player

## Get involved early
- Cultivate relationship with "product owner"
- Ask about 
  - feature roadmap
  - user stories
  - customer requests
  - business logic for integrators

## Position yourself for success
- Study and use the API
- Investigate the tech stack your team uses
- Learn to read code
- Learn code style and naming conventions

## Stay engaged
- Lurk in code reviews and design discussions
- Review API design for usability
- Get high-level API design information => usage information (optimal use of API)
- Get technical feedback early

## Share customer stories
- Listeners feel empathy when they hear personal stories
- Helps your team keep users in mind

** => "User first" mentality **

## Share your wins, too
*People like being part of a winning effort*
- Conditions your team to help you win more
- Creates a user-first team mentality
- Replenishes goodwill

** => "Team Winning Spirit" **

## Use goodwill wisely
- It's a finite resource
- Use it when you ask for stuff from teammates or customers
- Replenish it by being thankful and respectful

# 3. Meet users' needs
## Hierarchy of API user needs
- search
-	simple organization
-		guidance on high-level design
-			code samples and tutorials
-				complete and accurate API reference
				

## Information Architecture
- Separate your reference from your developer's guides
- Example: Google API doc

## Card sorting
*모든 topic을 뽑아서 카드로 만들고 customer한테 보여줘서 sort하게 함*
- Regular method for new information
- Reverse card sorting to validate existing information
- Aim for distinct containers
- Example: Guide vs. Tutorial의 구분

## API reference
- Biggest source of API usability issues
- **SpringRestDocs and Swagger2Markup for REST APIs**
  - unifies outputs for guide / reference
  - automates the process

## Developer's guide
- Getting started section
  - **Minimize "time to first hello world"**
    - Competitive advantage over other API docs
- Use cases, in-depth tutorials, samples
- Business logic

## Interactive testing and samples
- Faster onboarding
- Swagger petstore, Amazon scratchpad, etc.

## Why are samples important?
- 55% of developers learn through code samples
  - *from Write the Docs survey: developers start coding from documentation (copy&patse, etc.)*
- developers don't want to start from scratch

## Types of code samples
- Short samples for demonstrating basics
- Tutorials for in-depth coverage of a specific task in APIs
- Code segments from complete applications

## Code sample formatting tips
- Use a style guide
- Use white space for logical code chunks
- Use comments to discuss code flow & non-obvious concepts
- Make sure samples stand alone and work as formatted!


## Search
- Some people don't browse
- Important even for single-page documentation
- Useful for analytics
- **Lunr.js** is an option if you want to build your own

## Analytics
- Search terms
- Pages visited after search
- User page flows **=> streamlining**
- Page per visit

# 4. Measure everything

## Measure everything
- Keep track of user feedback
- API adoption, customer retention, support escalations
- API documentation analytics
- Get fresh data often

## Metrics provide visibllity
- Problems with the API or documentation
- Implementation
 

# Summary
1. Frame documentation as a usability task
1. Stay engaged in the development process
1. Make sure your documentation meets user needs
1. Measure everything and do it often

# Day 1 - Session #2
## [Documentation Support for an IoT Product: A Case Study](https://stcsummit2017.sched.com/event/8tj9/documentation-support-for-an-iot-product-a-case-study)
### Michael Harvey (Principal tech writer, SAS)
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day1_Session2.jpg?raw=true)

# Introduction
## Internet of Things (IoT)
- A term coined by Kevin Ashton (1999)
- Any kind of device exchanging any kind of signal using sensor, transmitter, etc.

## SAS
- Develops stastical analysis tool for
  - Data analysis
  - Business Intelligence
  
## IoT at SAS
- Industry-level data analysis
  - e.g. oil/gas extraction, water usage monitoring, truck manufacturing
- *Presenter writes document for **Event Stream Processing (ESP)** *

# SAS Event Stream Processing (ESP)
- Set of programming tools to build applications that process and analyze streaming data (events)
- Can perform real-time analytics on that data

## ESP use cases
- Capital markets trading systems 
- Fraud detection and prevention 
- Cyber security analytics
- Operational systems monitoring and management 
- Personalized marketing
- Sensor data monitoring and management

# ESP documents initially inherited
## Overview
- A “continuous query,” with 3 lines of code

## User's guide
- Poorly organized with 
  - Nearly every heading at level 1
  - Pages and pages of C++ code
  - Questionable repetition
- Verbose sentences
- Ambiguous diagram

** => need storytelling **

# Measures for document overhaul

## Learn while writing
- spent weeks annotating the User's Guide
- term arrangements
  - investigated terms that were used in different ways
  - removed some terms
  - edited terms for clarity
- asked pointed questions

## Define audience
- both of 
  - applicaiton developers
  - application users


## Write for programmers
- build on what they do know (no redundancy)
- use terms consistently
- create a logical flow and stick to it
- provide easily accessible reference material

## Build the plane during takeoff
- write, revise, repeat
- correct technical errors in the C++ reference material
  - while handling new material about the XML modeling layer
- learn/incorporate connectors/adapters
- document a completely new UI

## Build trust with development team
- competent SW engineers - not tech. communicators
- explain different roles and value-added by proper documentation
- schedule as much face time
- NEVER compain about the volume of work

## Sweat the technical details
- learn how to read C++ code
- become familiar with different technology
  - **YARN, Apache Camel**
- constantly ask questions

** => research, attempt to understand --> trust/respect **

# What story emerges?

## Streaming Data (Events)
- very different from static data
- an event consist of metadata and field data
  - metadata: opcode + flag
  - field: key, symbol, tray, price
- need a model for actional event

## How do events flow through ESP?
- 이벤트 전달과 관련된 외부/내부 개체를 명확하게 구분
  - event stream publisher/subscriber
  - source/derived window
- 다이어그램이 실제 이벤트 전달을 보여줄 수 있도록 numbering, callout을 추가

# Evolution of documentation
Before | After
------------ | -------------
Flat and dense | Better organized, more accessible, less dense
523p. user guides | Set of self-contained topics in help center


# Bleeding edge meets tech writing 101
- Don’t take it personally (learn)
- Learn before asking (respect, impress)
- Ask (often)
- Rewrite (always)
- Acquire feedback (test, reviews)
- Understand (before publishing)
- Contribute


# What's next?
- for machine builders? : agriculture (ferterlizer), airline (fuel use), ...
- for health care? : remote monitoring, biometric data
- Who owns security in the IoT?

# IoT "end users"
- won't need/read doc.
- won't use SW apps
- consume the analysis of event streams

# Challenges ahead
- continuing to overcome the curse of knowldedge
- connecting the dots for SAS ioT customers - offerings that bundle various SAS products
- building more planes during takeoff

# Q&A
- RESTful API Doc 생성 방법?
  - 자체 정의한 DTD 기반 XML에서 생성
  - 내년에 Swagger로 전환 예정

# Day 1 - Session #3
## [Walk in Your Customer's Shoes: Creating Journey Maps for an Improved User Experience](https://stcsummit2017.sched.com/event/8tiA/walk-in-your-customers-shoes-learn-the-art-of-journey-mapping)
### Michelle M. Gardner (Sr. Info. Developer, Micro Focus International)
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day1_Session3.jpg?raw=true)

# What's a Journey Map?
- tells a story from a user(particular persona)'s perspective 
- about the actions that persona takes
- to accomplish a specific goal

## Steps for creating a journey map
- Know the users and their goals
- Write about the actions they need to take at each stage
- Find out what they would want at each stage
- Satisfy the user's need
- Remove the obstacles


## from a particular point of view
- get to know (delve into) your personas
- don't let assumptions trip you
- "tell each persona's story as an individual journey"

## about actions the persona takes
- action on each stage
- thoughts and feelings
- timeframe
- expectation
- channels
- touchpoints => 단계 별로 도출하면 selling point를 파악할 수 있음
- moments of truth



# When to create a journey map
- plan (best), design, post-processing

# Apply to product design
- Add useful features
- Remove or hide features
- Provide alternatives
- Identify and create scenarios

# Apply to targeted content
- organize content according to the journey
- ensure the interface has the right content at the right time



# Journey mapping process
- Empathize
- Define
- Ideate
- Prototype
- Test

# Effects of journey map
- improve your targeted content and influence the user experience
- at all stages of the design & development process

# Day 1 - Session #4
## [Implementing a Content Strategy Is Like Running 100 Miles: Painful But Possible](https://stcsummit2017.sched.com/event/8tj1/implementing-a-content-strategy-is-like-running-100-miles-painful-but-possible)
### Gavin Austin (Principal Tech. Writer, SalesForce)
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day1_Session4.jpg?raw=true)

# About Salesforce
- develops Customer Relationship Management (CRM) solution in the cloud
- currently 4th largest SW company in the world

# About me
- couldn't run a mile
- unemployable without spellcheck
- leading people scares me and burns my guts

## Nevertheless
- finished western states 100-mile endurance run and many others
- helped motivate, explain, train, and lead a team of 100+ smart, bright, talented, opinionated content creators into a new content strategy

# Content Strategy
- Provides **context**, so that the organization's **vision** can be implemented in an integrated way, to meet **business goals** and project objectives
*from The Language of Content Strategy by Scott Abel & Rahel Anne Bailie*


# What I learned and what this talk is about
1. Pain (discomfort)
1. Relationships
1. Strengths over weaknesses
1. 'Forget tools, hacks, fads'

# 1. get ready to hurt

- Your vision worth the pain?
  - Salesforce 기존 상태
    - 3달마다 있는 release마다 400페이지의 revision history
    - Tech. writer도 찾아 보기 힘든 수만 페이지의 help topics
- Can you make it less painful?
  - make it doable
  - prioritize interactive guides over traditional doc forms
- How many opinions can you tolerate?
- Is there a pain threshold to measure?
  - 20 years of legacy contents
  - 10% at a time (curate, re-write, optimize, SEO modification)
- How will you handle wanting to quit?
  - iterative (update one at a time)

# 2. you can't do it alone
- Who are your mentors?
  - 멘토가 반드시 상급자여야 할 필요는 없다.
  - 동료나 부하의 재능과 지혜로부터 도움을 받고 배울 수 있다.
- Do you need a pacer?
  - for safety first
  - consider health of the team
- Are you asking for help?
  - 러닝 중간에 나타나서 파인애플 주는 부모님 예시 ^^;
- Are you putting tools over people?
  - buy into what you're doing
  - 맨발, 채식주의자 runner 따라하기 비유
- Are you celebrating victories?

# 3. Strength over Weaknesses
- What's your team great at?
  - at SalesForce, no "one size fits all" strategy
- What's your team's biggest weakness?
  - keeping up with growing team
- Did you verify with a proof of concept?
- Are you recovering with breaks?
  - rotate writers for tasks => recharge
- Are you scheduling time (appropriately )for your strengths?
  - 팀원들의 content 작성 능력이 뛰어나더라도 UI text review하는 시간을 갖는다.

# 4. A Finish for you

- Next step?
- Volunteer => Now!

# Q&A
- How did you convince SME?
  - Exceutives understood that content reflects (helps accentuating) the brand of the company (운이 좋은 듯)
  - Working with UX/marketing people can be very helpful.
- Recommended roadmap?
  - 100mile run도 한번에 만들어지지 않았음 (10 -> 20 -> 50 -> 100)
  - Conduct proof of concept (for years)
- CMS/버전 관리 시스템?
  - 개발팀과 align되도록 Perforce 사용

# Day 1 - Session #5
## [Work Global, Live Local](https://stcsummit2017.sched.com/event/8tiB/work-global-live-local)
### Melissa Kulm (Lead Technical Writer, SalesForce) 외 2인
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day1_Session5.jpg?raw=true)

# Learn how to
- Staying visible
- Maintain connection
- Stay focused when working remotely

*참가자 대부분이 remote (또는 재택) 근무 경험, 절반 이상이 현재 remote 근무*

# Stay Visible & Engaged
- speak up, speak often
  - to communicate informally
    - Hangout, Skype, Slack
  - to communicate more formally
    - Collaboration platform (SalesForce Chatter), Wiki, email, 'office hours'
- Managing your career remotely
  - Socialize your work
- Be your best self
  - turbocharge your HW: 웹캠, 헤드폰+마이크, 노이즈 캔슬링
  - check your speed: 인터넷 BW
  - aim for a distraction-free workspace
- make meetings remote-friendly
  - attending
  - running: manner, time

# Maintain connection
- Participate in and foster team culture
  - virtual happy hours
  - be a joiner
  - lunch localy
  - volunteer together
- build good virtual working relationship
  - consider time zone
  - share meeting notes/recordings
- build good F2F working relationship
  - make the most of your team visit
    - plan, plan, plan
    - side-by-side doc/UX reviews, brainstorming

# Stay focused when working remotely
- set aside office space
  - 제안: 사무실과 비슷하게 구성하라
- Groom for success (출근할 때와 같은 몸가짐 마음가짐)
  - no Pajama Syndrome
  - 시간 맞춰 생활 패턴 구성: 다른 팀 식사 시간에 운동 등
- do excercise & manage breaks
- Nurture your social life
- Turn it off
  - 사무실과 마찬가지로 시간 맞춰 업무 마무리, 루틴 유지

# Day 2 - Session #1
## [A Tech Writer, A Map, and an App](https://stcsummit2017.sched.com/event/8tjK/a-tech-writer-a-map-and-an-app)
### Sarah Maddox (Tech. Writer on the Google Maps APIs, Google)
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day2_Session1.jpg?raw=true)

# Tech Comm on a Map
- 전 세계 technical communication 활동을 지도 상에 보여 주는 app
  - [Demo](http://sarahmaddox.github.io/techcomm-map/)
  - [Web app](http://sarahmaddox.github.io/techcomm-map)
  - [Android app](https://goo.gl/twfOKO)

# What's discussed
- App을 개발하게 된 동기
- Data sourcing
- Web app, Mobile app 각각의 개발/배포 과정
- Open Source, Hackathon
- Lessons learned

*=> 세부 사항은 발표 자료 참고*

# 주요 시사점
## Why develop an app?
- understand my audience
- learn the tech
- gain the edge
- create a useful map for the tech comm community
- have fun
**=> gain the edge, take a leap, really need docs & code samples**

## Lessons
### IANAE (I Am Not An Engineer), but...
- technical confidence
- understanding of audience
  - various skill levels / platforms
  - just want to get things done
  - **code samples rule** => Google Maps API 사이트에 반영

# Q&A
- Atlassian vs. Google?
  - Google is intensely developer focused
- What changes are you planning to make?
  - work with UX research group, put together design to improve UX
- How to cover diffenent level of developers?
  - start with rudimentary --> build up
- 'A-Ha' moments from developers?
  - run a Hackathon

# Day 2 - Session #2
## [Hello World! RIP Traditional Content Strategies and Methodologies](https://stcsummit2017.sched.com/event/8tjN/hello-world-rip-traditional-content-strategies-and-methodologies)
### Pam Noreault (Solution Architect, SDL)
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day2_Session2.jpg?raw=true)

# Traditional Content Strategy
## Release-cycle documentation
1. new features, fixes, release = new content
1. publish to PDF or HTML
1. rinse and repeat

## Poll
1. Who does content within some release cycle?
1. Does anyone release content or other deliverables outside of this cycle?

## Questions
- where do we go?
- what do you do?
*=> 구글, 유투브, 포럼, iFixIt, ... (자사 help site는 뒷전으로...)*
-  Why do we stick with the traditional?
*=> 편하다고 계속 사용하지만... end user에게 사용되지 않을 가능성이 커짐*

# Customer-Driven Deliverables
- Strategy
- Goals
  - Proof of Concept (POC)
  - Schedule
  - Content
  - Video
  - Bot driven

# Know your audience
- We claim that knowing our audience ... VERY FEW
- You can't know anybody without spending time with them
- Let's get personal!


*Note: 가령 60개 가량의 언어로 tech/marketing content 번역하는 걸 처리하려면 새로운 전략과 방법론이 필수적임*

# Jump the Gap... Shift... Get out of your comfort zone
- stop doing release-cycle driven content
- engage with your customers
- use UX methodologies: **[usability.gov](https://www.usability.gov/)**
- use social media

# Where to Start?
1. Take inventory: what's important, where this will fit in
1. Do a POC
1. Measure/Report Results
1. Determine Strategy/Schedule/Execute

# Engage
- Listen
- watch
- demo
- question
- look for patterns
- obtain first-hand evidence

# Deploy UX Strategies and Marketing Strategies
- 슬라이드 및 usability 사이트 참조

# Strategy
- develop your content strategy around your customer-engagement cycle (create this)
- determine deliverabls based on need
- create a deliverable schedule and kill it
- report, rinse, repeat

# For real?
- customer-centric deliverables vs. PDFs only

# Your users are your biggest advocaters if you start involving
- Think out of the box
- 새로운 피드백이나 요청이 있으면 화내지 말고 감사하는 마음으로...

##### 참가자 추천 서적
- "More beautiful questions"
- Filter the "What" out of the "How"

# Day 2 - Session #3
## [Generating Web Service API Documentation Automatically from the Source Code](https://stcsummit2017.sched.com/event/9sSk/generating-web-service-api-documentation-automatically-from-the-source-code)
### Ed Marshall (Marshall Documentation Consulting)
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day2_Session3.jpg?raw=true)

# Intro/Agenda
- Then and Now
  - Demos of both
- Principles of good API documentation
- REST API highlights
- Using Swagger as a technical writer


# Then
- 기존 #1: Help authoring tool => PDF
  - API reference 구조 설명
- 기존 #2: JAVA => JAVADOC => HTML Help
  - comments가 의미 있는 내용이어야 하고 업데이트돼야 함

# ... and Now
- Swagger: main player
- RAML: looked promising but seems to be unsupported


# Principles of API Documentation
- Interfaces/classes
- Methods/functions and their parts: parameters and their datatypes
- Return values
- Error messages
- Examples

- Swagger Petstore: actual working API embedded within the Swagger environment
- Swagger 데모
  - 개발 환경에 copy&paste 할 필요 없고...
  - inline WYSIWYG editor가 있음
  - YAML: Yet Another Markup Lang.

# Why use REST APIs for Web services?
- Simpler,  all resources called are specified in the request. 
- Parameters are specified in the request. 
- Use standard HTTP actions for their operations (GET, PUT, POST, or DELETE).
- Identify the categories of data available to the REST API using a URL structure.
- Specify a base URI (URL)

*SOAP는 out of favor*


# Using Swagger as a Tech Writer
- Mock-up server to test your API
- Interactive documentation
- ability to generate SDKs in many languages
- written in YAML/XML. no extensive coding expertise required.

*=> Swagger reference 템플릿 보여줌*

# Summary 
Swagger strength
- Single source of truth
- provides interactive documentation
- generic coding language that produces SDKs for many languages
- actively supported

# Q&A
- zip으로 묶는 등 SDK 생성 자동화 가능?
  - Yes. 하지만 주로 개발자 몫임
- Swagger 단독으로 documentation tool이 될 수 있다고 보는지?
  - 개발팀 등과 협의해서 결정 가능

# Day 2 - Session #4
## [Is DITA Right for You? Scenarios for Considering a Move to DITA](https://stcsummit2017.sched.com/event/8tjV/is-dita-right-for-you-scenarios-for-considering-a-move-to-dita)
### Keith Schengili-Roberts (IXIA Soft)
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day2_Session4.jpg?raw=true)

# Agenda
- Brief history of the development of DITA XML
- The chief advantages of DITA
- Chief reasons why companies move to DITA

*=> 상세 내용은 발표 자료 참조*

# About the presenter
- 발표자가 DITA 표준 위원회 chair이자 다양한 저술, 강연, [사이트](http://www.ditawriter.com/) 운영을 통해 사용 현황을 파악하고 홍보하고 있는 DITA 전문가임

# Q&A
- Framemaker vs. DITA: 개발자가 작성한 Word에서 어떻게 migration하는가?
  - 전반적으로 web based editor로 바뀌는 추세임
- SharePoint를 Content Server로 사용 가능한가?
  - CCMS (Component ~)가 아니라서 DITA를 완전히 지원하기에는 부족함.
- DITA editor/CMS 제품 별로 지원 사항에 크게 차이가 있는데, 파편화 이슈가 우려되지는 않는지?
  - Major 버전 교체 주기를 5년으로 보는데 최신 버전인 v1.3이 이제 1년 남짓 된 상태임
  - "Good ones"(많이 사용되는 우수한 제품으로 이해)는 최신 버전을 반영하기 때문에 큰 문제는 되지 않을 거라고 봄

# Day 2 - Session #5
## [My Android Dreams of Electric Cats: Are You Capturing Your User's Emotive Analytics?](https://stcsummit2017.sched.com/event/8thV/my-android-dreams-of-electric-cats-are-you-capturing-your-users-emotive-analytics)
### Allie Proff (Knowledge Management/Library/TechComm, Boeing)
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day2_Session5_2.jpg?raw=true)

# Introduction
- Analytics measures 'what', not 'why' 
- 'Why' is the emotions


# Emotions > Logic
- rather than mechanical step1, step2, step3
- storytelling rules => engages emotions


# Emotive Analytics 
- The ability to measure a user’s emotions through video, voice, wearables, or text. 

# Affective Processing
- Software that can identify a user’s emotions and provide an emotionally correct response.


# Emotional Design (harder ones) 
- Voice to Text
- Beyond Verbal
- Face Detection
- The anti-face: CV Dazzle
- Affective and Affdex
- Face Analytics
- Milo the Robot
- Hanson Robotics


# How does this affect me?
- Content creation
- Usability and UX
- Help documentation
- Brand building and loyalty
- Customer journey and CX
- Customer service and interaction

# Q&A
- 얼굴 인식 관련 직접 테스트해 보려면 카메라 사용 조심할 것 (프라이버시 이슈)

# Day 3 - Session #1
## [PDF and HTML5 Make Content Truly Omnichannel](https://stcsummit2017.sched.com/event/AJLI/pdf-and-html5-make-content-truly-omnichannel)
### Abhishek Jain (Product Manager, Adobe) 외 1명
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day3_Session1.jpg?raw=true)

# Responsive HTML5 / PDF
- enjoy the best of both world!

## PDF
- available offline
- print ready
- archival tool
- consolidated & complete
- shareable

## (Responsive) HTML5
- online
- mobile friendly
- dynamic / interactive
- searchable
- shareable


# Survey result
- 시사점: mobile friendly output 증가

# PDF => HTML5 (일반적인 시퀀스에 따라)
## Long page
- break into smaller content

## Cross reference and Numbering

## Web based styles and Responsive Content
- CSS
- fonts: online font 이슈
- source format: inherit / override / map
- HTML list
- Responsive: image / table

## Content Navigations
*serial access => random access*
- TOC
- Index
- Glossary
- Bread crumbs
- Browse Sequence
- Search
- Filter: PDF에 비해 더 까다로울 수 있다
- Progressive discovery

## Layout
- Master page
- Layout
  - labels

## Search
- Synonyms
- stop words
- search settings
- sitemaps

## More stuff
- Personalization: Content Filter (집중적으로 질문 나옴)
  - Q: CMS가 conditional tag을 지원한다고 가정하는 것인가?
  - A: 대부분 지원한다...
  - Q: SIEMENS 내부 worldwide CMS에서 제한적인 filtering만 지원해서 문의함
- Context sensitive
- Analytics
- sales, marketing, UX 등과 연계하면서 요구 사항이 다양해짐

# 변환 데모 (FrameMaker 2017)

# Day 3 - Session #2
## [Creating User Documentation in an Agile World](https://stcsummit2017.sched.com/event/8tjg/creating-user-documentation-in-an-agile-world)
### Jane Wilson (Director of Technical Writing, GE Digital)
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Day3_Session2.jpg?raw=true)

# You say Scrum, I say Agile...
- Agile Manifesto, 2001 <= 17명이 ski lodge에서 처음 논의
- waterfall과의 구분점
- Adapt and iterate (보통 2주)
- Self-organizing teams: flat > hierarchical
- transparency and simplicity: 성과 가시화
- Scrum ceremonies: sprint review, etc.
- fail fast

# There was NO discussion on documentation when Agile came out!


# Scrum Team
- Product owner
- Scrum master: facilitator
- Team members

## Technical Writer
- (Usually) specialized member of the scrum team
- starts with lightweight content (prototype?)

## Writers cover multiple scrum teams
- meeting time/frequency/story load 유의


# Documentation Stories
- should reflect all work done by a Technical Writer as part of the scrum team
- Types
  - created by the development team
  - relating to documentation-specific work (less common)

## "Story Points"

## Tips
- Divide work into multiple stories (not a single catch-all story)
- Link a doc story to the related dev features


# Review Time
- Quality Process (InfoDev)
- Review for completeness and flow (scrum team)
- End-to-end review and sign-off by PMs

# Participate in scrum ceremonies!
- Planning
- Daily Stand-ups: changes/dropping
- Sprint Review
- Retrospective

# Keep Calm, (Lean about Agile), and Speak Up
- 참여하고 의견을 얘기해라!

# Q&A
- 유지보수, 고객의견 수렴 방법
  - JIRA 등으로 Doc Bug을 수집
- Story Point 산정 방법
  - 팀에서 small/medium/extra large story 별 point를 부과

# Overall Summary
- Content writing을 UX 관점에서 바라보는 세션이 많았음
  - Usability에 대한 언급이 자주 나옴
  - Tech Writer가 개발팀 이외에 UX, 기획, 마케팅과도 연계해서 content 생성하는 방안 고려
- API 관련 세션
  - 공통적으로 Code Sample의 중요성을 강조함
  - 전반적으로 문서화 관련 실질적인 툴에 대한 내용이 적고 깊이가 얕은 편이었음
  - 특히 Day 2, Session #3는 Swagger 자체 소개 수준에 그침


# Closing session
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/ClosingSession.jpg?raw=true)

# Farewell
![title](https://github.com/jkboxomine/STC_Summit_2017/blob/master/img/Farewell.jpg?raw=true)
