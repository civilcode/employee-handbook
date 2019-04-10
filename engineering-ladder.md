# Engineering Ladder

## Introduction

The purpose of the CivilCode Engineering Ladder is to help resolve issues[^1] such as:

- “I’m not growing here professionally.”
- “I don’t know what I need to do to grow in my role.”
- “I don’t understand why that person got promoted and I didn’t.”
- “The feedback my lead gives me isn’t actionable.”

It outlines a career path for a Business Application Developer. An [Engineering Ladder](https://kickstarter.engineering/the-kickstarter-engineering-and-data-team-ladder-96996c3b327) is not a new concept and and we have leveraged the efforts from others who have explored this territory before us. However, the CivilCode adopts a specific domain language and structure from other sources including:

- Society for Industrial Organizational Psychology (SIOP) task force on competency modelling
- [Essence Kernel and Language](http://semat.org/documents/20181/57862/formal-18-10-02.pdf/866c80c0-cdc8-488b-bcf8-0c67cb60b5d7)

The ladder is composed of a number of levels consisting of:

- Competencies: the abilities, capabilities, attainments, knowledge, and skills necessary to do a certain kind of work [^2]; the body of the competency describes these in more detail
- Definition: a definition for the competency
- Knowledge: facts, information, and skills acquired through experience or education; these are described as topics; i.e. knowledge areas
- Capabilities: the expection of a developer's abilities based on their level; the capability is phrased in a way to complete the sentence: "A developer is capable of..."

## Caveats

It is important to be realistic and understand that no model is perfect, and neither is this one. There are a couple of important points to know:

- A developer at a specific career level may not have attained the extent of all the abilities listed, but has reached a level of capability that justifies their position.
- A developer at a career level will be asked to perform abilities beyond their expected capability to help them grow professionally.
- This is a guide only, and it's our current best guess to help set expectations. We would hate this to be a document to examined as a line item in an order, the importance is the essence of the competencies expected at each career level.

## Career Levels

### Junior Developer

As a Junior Developer you are starting or in the early stages of your career. You are solidifying your understanding of core software development concepts and learning the CivilCode Method, platform and tools.

You have a dedicated mentor to guide you through our _way-of-working_ and to help you build the competencies required to move to the next ladder.

### Intermediate Developer

As an Intermediate Developer you demonstrate a proficiency in core software development concepts and the CivilCode Method. Your focus is now on mastering topic such as Domain-Driven Design and Algebraic Data Types (ADT's).

You contribute to projects by designing and implementing features with your team members, while helping to improve our method congruent with CivilCode's Values. You also participate in other areas of the business, such as pre-sales & community activities.

### Senior Developer

As a Senior Developer you have mastered the CivilCode Method, platform and tools. You are a go-to expert in one of our Knowledge Domains such as Domain-Driven Design. You are able to mentor Junior Developers and provide guidance to Intermediate Developers.

### Lead Developer

TBD - Leading projects, capable of high-level management responsibilities

# Resources

These resources are mentioned throughout this document:

- [CivilCode Method](https://github.com/civilcode/playbook/tree/master/method)
- [Developer Guides](https://github.com/civilcode/acme-platform/tree/master/guides)

# Platform and tools

The CivilCode platform for Business Applications composes of:

- Elixir/OTP
- Phoenix/Ecto
- Postgres
- Docker
- Heroku

We also use these tools:

- Git
- MacOS

# Competencies

## Business Analysis

This competency encapsulates the ability to understand and model our clients' needs and transform them into an agreed upon and consistent set of requirements.

### Knowledge

- Domain Modelling
- Event Storming
- Story Mapping
- Algebraic Data Types (ADT's)

### Capabilities

A __Junior Developer__ is capable of:

- learning concepts and techniques of the competencies
- learning the CivilCode Method
- attending and observing discovery sessions

An __Intermediate Developer__ is capable of:

- actively uses the modelling tool on features
- attending discovery sessions and participating by taking notes and asking questions

A __Senior Developer__ is capable of:

- mentoring other developers on the concepts and techniques
- reviewing artifacts produced by other developers

A __Lead Developer__ is capable of:

- managing the domain language is used on projects
- leading activities to drive requirements and scope projects

## Software Development

This competency encapsulates the ability to design and program effective business applications following the standards and norms agreed upon at CivilCode.

### Knowledge

- Domain-Driven Design (DDD)
- Functional Programming (FP)
- Test-Driven Development (TDD)
- Specification by Example (SBE)
- Platform and Tools
- Coding
- Pair Programming

### Capabilities

A __Junior Developer__ is capable of:

- demonstrating an understanding of some software development concepts
- writing tests first
- writing correct and clean code with guidance
- participating in pair programming sessions
- learning and applying the platform and tools used at CivilCode
- submitting small pull requests
- finding the right balance between persevering on a problem and asking for help
- participating in code reviews
- becoming familiar with standards from the _Developer Guides_

A __Intermediate Developer__ is capable of:

- demonstrating an understanding of _DDD_ concepts
- reviewing code
- identifying issues related to coding standards and design approaches
- identifying refactorings (code duplication, naming, file structure, ...)
- writing correct and clean code with limited guidance
- following standards documented in our _Developer Guides_
- participating in technical design of features
- learning quickly and makes steady progress without the need for constant feedback from more senior developers
- being proficient with our platform and tools
- assisting in the decomposing of a features into smaller units
- making pragmatic design decisions; identifying risks, trade-offs, and alternative solutions to be considered
- possessing empathy with the end-user and uses it to guide decision-making
- identifying problems with requirements (lack of clarity, inconsistencies, limitations)

A __Senior Developer__ is capable of:

- writing consistently high-quality code
- demonstrating a knowledge of industry trends
- being an expert in one area of software development
- identifying and proactively tackles technical debt

A __Lead Developer__ is capable of:

- ensuring features are completed as specified without micromanaging

## Leadership and Communication

This competency enables a person to inspire and motivate a group of people to achieve a successful conclusion to their work and to meeting their objectives.

### Knowledge

- Verbal Communication
- Written Communication
- Presentations
- Diplomacy
- Facilitation
- Teamwork
- Collaboration Tools
- Knowledge Transfer
- Documentation

### Capabilities

A __Junior Developer__ is capable of:

- accepting feedback graciously and learns from everything
- asking for feedback early in order to reduce risk and deliver value early
- clarifying  assumptions, needs, requirements and goals upfront to minimize rework
- providing basic status updates, e.g. slack checkouts
- soliciting feedback from others and is eager to improve upon their own performance
- sharing ownership of the codebase
- communicating with their team
- documenting their work (i.e. descriptive PRs, READMEs, entries to Wiki, code)
- communicating with mindfulness and empathy, assuming the best intent from others
- handling change with maturity
- contributing in team meetings and to the CivilCode culture

A __Intermediate Developer__ is capable of:

- interacting with the Product Owner, e.g. asking questions, requesting feedback
- offering timely, helpful and actionable feedback to prevent others guess the status, e.g. reviews, retrospective, follow-up messages in issues, status updates, progress
- identifying and documenting R&D issues
- collaborating effectively with team members
- contributing to the community through initiatives such as open-source projects, training, meetups, presentations and blogs

A __Senior Developer__ is capable of:

- including others in decision-making tasks
- setting an example for giving effective feedback
- identifying problems and risks with their own work and others
- communicating technical decisions (e.g. ADRs)
- communicating effectively with other team members and clients
- mentoring other developers via pairing, design review and code review

A __Lead Developer__ is capable of:

- communicating timelines, scope and technical concerns to their clients
- making independent decisions for the team
- guiding others on the team through change
- coaching others on the team towards mindful communication
- seeking to understand, mediate, and resolve conflict
- proactively identifying and addressing potential roadblocks before they impact the team

## Management

This competency encapsulates the ability to coordinate, plan, and track the work done yourself and the team.

### Knowledge

- Feature-Driven Development (FDD)
- Project Delivery
- Project Management
- Process Improvement
- Professional Development
- Recruiting

### Capabilities

A __Junior Developer__ is capable of:

- learning the CivilCode Method.

An __Intermediate Developer__ is capable of:

- being proficient in the CivilCode Method
- delivery features from design to deployment
- prioritizing work appropriately, avoiding unimportant details
- not making the same mistakes twice, rarely
- avoiding disproportionate attention on small unimportant things
- implementing the simplest thing first
- focusing on productivity and efficiency; avoiding wasting their clients' and/or peers' time
- delivering work with less supervision

A __Senior Developer__ is capable of:

- mastering the CivilCode Method
- improving the CivilCode Method
- contributing to CivilCode with minimal direction or oversight
- participating in the hiring process
- actively learning how to handle difficult management situations

A __Lead Developer__ is capable of:

- managing independently
- delivering value to their clients
- practicing Feature-Driven Development and manages development accordingly
- producing work products resulting from Discovery Sessions
- tracking resource usage on projects using our reporting tools
- informing their clients on progress
- clarifying requirements with their clients
- ensuring developers are producing value for their clients
- contributing to the career development of others
- meeting regularly with direct reports and managing performance
- leading recruiting efforts for their team

{TO-DO}

# Definitions

- Ability: possession of the means or skill to do something, talent, skill, or proficiency in a particular area
- Knowledge: facts, information, and skills acquired through experience or education
- Attainments: the action or fact of achieving a goal towards which one has worked
- Skill: a particular ability; the ability to do something well

# Notes

[^1]: https://suechoeblog.com/2016/11/10/why-im-obsessed-with-competency-matrices-or-how-competency-matrices-help-your-employees-to-learn-and-your-company-to-scale/)
[^2]: http://semat.org/documents/20181/57862/formal-18-10-02.pdf/866c80c0-cdc8-488b-bcf8-0c67cb60b5d7
