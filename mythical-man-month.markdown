# The Mythical Man-Month

# The Tar Pit

- The programming project converges more slowly the nearer one gets to the end, whereas one expects it to converge faster as one approaches the end.

# **The Mythical Man-Month**

- More programming projects have gone awry for lack of calendar time than for all other causes combined.
- Partitioning a task among multiple people requires extra communication effort, training, and intercommunication.
- Because we are uncertain about our scheduling estimates, we often lack the courage to defend them stubbornly against management and customer pressure.
- Adding manpower to a late project makes it later.
- Adding people to a software project increases the total effort necessary in three ways: the work and disruption of repartitioning itself, training the new people, and added intercommunication.

Rule of thumb for scheduling a software task: 

1/3 planning & design

1/6 coding

1/4 component test and early system test

1/4 system testing

1. The fraction developed for planning is larger than normal. Even so, it is barely enough to produce a detailed and solid specification, and not enough to include research or exploration of totally new techniques.
2. Half of the schedule is devoted to debugging completed code is much larger than average.
3. The part that is easy to estimate, such as coding, is given only 1/6 of the schedule.

# The Surgical Team

- Organizing as a surgical team is a radical attack on all aspects. It is really the long-run answer to the problem of flexible organization.
- Very good professional programmers are ten times as productive as poor ones, at the same training and two-year experience level.
- A small sharp team is best; as few minds as possible.
- A team of two, with one leader, is often the best use of minds(note God’s plan for marriage).
- A small sharp team is too slow for really big systems.

## Surgical team

- Instead of each member cutting away on the problem, one does the cutting and the others give him every support that will enhance his effectiveness and productivity.

### **Surgeon, chief programmer**

will define the functional and performance specifications, designs the program, codes it, tests it, and writes its documentation.

needs great talent, ten years of experience, and considerable systems and application knowledge whether in applied mathematics, business data handling, etc.

### Copilot, alter ego of the surgeon

able to do any part of the job of the surgeon, but is less experienced.

right-hand man to the surgeon.

his main responsibility is to share in the design as a thinker, discussant, and evaluator.

the surgeon tries ideas on him but is not bound by his advice.

often represents his team in discussions of function and interface with other teams.

knows all the code intimately.

researches alternative design strategies.

obviously serves as insurance against disaster to the surgeon.

may even write code, but he is not responsible for any part of the code.

### Administrator

handles money, people, space, and machines, and interfaces with the administrative machinery of the rest of the organization.

should be a full-time job only if the project has substantial legal, contractual, reporting, or financial requirements because of the user-producer relationship. Otherwise, one administrator can serve two teams.

### Editor

takes the draft or dictated manuscript produced by the surgeon and criticizes it, reworks it, provides it with references and bibliography, nurses it through several versions, and oversees the mechanics of production.

### Two secretaries

The administrator and the editor will each need a secretary; the administrator’s secretary will handle project correspondence and non-product files.

### Program clerk

responsible for maintaining all the technical records of the team in a programming-product library. 

is trained as a secretary and has responsibility for both machine-readable and human-readable files.

all computer input goes to the clerk, who logs and keys it if required. The output listings go back to him to be filed and indexed. The most recent runs of any model are kept in a status notebook; all previous ones are filed in a chronological archive.

### Tool-smith

responsible for ensuring the adequacy of the basic service and for constructing, maintaining, and upgrading special tools, mostly interactive computer services needed by his team.

### Tester

devises system test cases from the functional specs, and an assistant who devises test data for day-by-day debugging.

plan testing sequences and set up the scaffolding required for component tests.

### Language lawyer

can find a neat and efficient way to use the language to do difficult, obscure, or tricky things.

often will need to do small studies (2~3 days) on good technique.

<aside>
💡 Make all computer runs visible to all team members. Identify all programs and data as team property; not private property.

</aside>

# **Aristocracy, Democracy, and System Design**

<aside>
💡 Conceptual integrity is the most important consideration in system design.

</aside>

- To achieve conceptual integrity, a design must proceed from one mind or a small group of minds that agree.
- **Separation of architectural effort from implementation** is a very powerful way of getting conceptual integration on very large projects(small ones too).
- If a system is to have conceptual integrity, someone must control the concepts. There is no need for an apology.
- A conceptually integrated system is faster to build and test.
- Much of software architecture, implementation, and realization can proceed in parallel.

<aside>
💡 The separation of architectural effort from implementation is a very powerful way of getting conceptual integrity on very large projects.

</aside>

The conceptual integrity of a system determines its ease of use. Good features and ideas that do not integrate with a system’s basic concepts are best left out.

The total creative effort involves three distinct phases: architecture, implementation, and realization.

# **The Second-System Effect**

The Architect must:

- remember that the builder has the inventive and creative responsibility for the implementation; so the architect suggests, not dictates.
- always be prepared to suggest a way of implementing anything he specifies, and be prepared to accept any other way that meets the objectives as well.
- deal quietly and privately with such suggestions.
- be ready to forego credit for suggested improvements.

# **Passing the Word**

- Even when a design team is large, the results must be reduced to writing by one or two, in order that the mini-decisions to be consistent.
- There is a need for both a formal definition of a design for precision and a prose definition for comprehensibility.
- One of the formal and prose definitions must be standard, and the other derivative.

<aside>
💡 It is imperative to log all communications, record them, and publish them.

</aside>

### A P**roject Manual**

is a necessary tool.

is the external specification of the product.

describes and prescribes every detail of what the user sees.

the chief product of the architect.

must not only describe everything the user does see, including interfaces; but must also refrain from describing what the user does not see.

**Conferences**

- Weekly half-day conference of all the architects, plus official representatives of the hardware and software implementers, and the market planners. The chief system architect presides.

- Anyone can propose problems or changes, but proposals are usually distributed in writing before the meeting. A new problem is usually discussed for a while. 

- The emphasis is on creativity, rather than a mere decision. The group attempts to invent many solutions to problems, then a few solutions are passed to one or more of the architects for detailing into precisely worded manual change proposals.

- Bi-annual supreme court sessions, lasting typically two weeks. 

- Those present include not only the architecture group and the programmers’ and implementers’ architectural representatives, but also the managers of programming, marketing, and implementation efforts.

# **Why did the Tower of Babel Fail?**

- The Tower of Babel project failed because of a lack of communication and of its consequent, organization.
- Team members should communicate with one another in as many ways as possible: informally through regular project meetings with technical briefings, and via a shared formal project workbook.
- The purpose of the organization is to reduce the amount of communication and coordination necessary.
- Organization embodies division of labor and specialization of function in order to obviate communication.

### **Project Workbook**⭐⭐⭐⭐⭐

- All the documents of the project need to be part of this structure. This includes objectives, external specifications, technical standards, internal specifications, and administrative memoranda.
- Needs to be designed carefully and early.
- Each team member should be able to see all the workbook material.
- Timely updating is of critical importance.
- Pay close attention to changes since previous editions.

Tree-like programming organization(essentials to be effective):

1. a mission
2. a producer
3. a technical director or architect
4. a schedule 
5. a division of labor
6. interface definitions among the parts

# **Ten Pounds in a Five-Pound Sack**

- Set total size budgets as well as resident-space budgets; set budgets on backing-store accesses as well as on sizes.
- Define exactly what a module must do when you specify how big it must be.
- All during implementation, the system architects must maintain continual vigilance to ensure continued system integrity.
- Fostering a total-system, user-oriented attitude may well be the most crucial function of the programming manager.

Two things managers can do to help their team make good space-time trade-offs:

1. Ensure they are trained in programming techniques.
2. Recognize that programming has a technology, and components need to be fabricated.

Every project needs a notebook full of good subroutines or macros for queuing, searching, hashing, and sorting. For each such function, the notebook should have at least two programs, the quick and the squeezed. The development of such technology is an important realization task that can be done in parallel with system architecture.

# **The Documentary Hypothesis**

- A small number of documents become the critical pivots around which every project’s management revolves. These are the manager’s chief personal tools.
- Even on a small project, the manager should from the beginning formalize such sets of documents.
- Each document itself serves as a checklist and database.
- The project manager’s chief daily task is communication, not decision-making; the documents communicate the plans and decisions to the whole team.

Documents for university department:

- objectives
- course descriptions
- degree requirements
- research proposals
- class schedule and teaching assignments
- budget
- space allocation
- assignment of staff and graduate students

very similar to:

Software project

- objectives
- manual
- internals documentation
- schedule (time allocations)
- budget
- space allocations
- organization chart (people allocations)

Documents for a software project

The concerns of any management task are what, when, how much, where, and who.

What: objectives. This defines the need to be met and the goals, desiderata, constraints, and priorities.

What: product specifications. This begins as a proposal and ends up as the manual and internal documentation. Speed and space specifications are critical parts.

When: schedule.

How much: budget.

Where: space allocation.

Who: organization chart.

**Why have Formal Documents?**

1. Only when one writes do the gaps appear and the inconsistencies protrude. This distinguishes fuzzy, unclear policies from clear, exact ones.
2. The documents will communicate the decisions to others. The manager will be continually amazed that policies he took for common knowledge are totally unknown to some members of his team.
3. Gives the manager a database and checklist. By reviewing them periodically he sees where he is, and he sees what changes of emphasis or shifts in direction are needed. 

# **Sharp Tools**

- The manager of a project needs to establish a philosophy and set aside resources for the building of common tools, and at the same time recognize the need for personalized tools.
- System debugging should be done at night or later at the end of the day.

**Program libraries** 

1. A master program library should be divided into 1. a set of individual playpens 2. a system integration sub-library, currently under system test 3. a released version. ⇒ Formal separation and progression give control.
2. All the code tested or under test is kept in this library, both source code and assembled load modules. The library is divided into sub-libraries with different access rules.
3. Each group or programmer has an area where he keeps copies of his programs, his test cases, and the scaffolding he needs for component testing.
4. When the component is ready for integration he passes a copy over to the manager of the larger system, who put this copy into a system integration sub-library. Now the original programmer cannot change it, except with the permission of the manager.
5. From time to time a system version will be ready for wider use. Then it will be promoted to the current version sub-library. This copy is sacrosanct, touched only to fix major bugs.
6. Two notions are important here: 1. control - the idea of program copies belonging to managers who alone can authorize their change. 2. formal separation & progression - from the playpen to integration, to release.

Documentation system

Among all tools, the one that saves the most labor may well be a computerized text-editing system, operating on a dependable vehicle. ex: cloud-based doc open to all readers and editors; Google Word doc, Notion, etc.

# **The Whole and the Parts**

One should begin system debugging only after the pieces seem to work (vs. bolting it together and trying in order to smoke out the interface bugs; vs. starting system debugging when the component bugs are fully known but not fixed) This is especially true for teams.

Top-down design(Niklaus Wirth) is a design procedure which had been used for years by the best programmers.

Identify design as a sequence of refinement steps. One sketches a rough task definition and a rough solution method that achieves the principal result. Then one examines the definition more closely to see how the result differs from what is wanted, and one takes the large steps of the solution and breaks them down into smaller steps. Each refinement in the definition of the task becomes a refinement in the algorithm for the solution, and each may be accompanied by a refinement in the data representation. = modules.

“I am persuaded that top-down design is the most important new programming formalization of the decade.”

The important point, and the one vital to constructing bug-free programs, is that one wants to think about the control structures, not as individual branch statements. This way of thinking is a major step forward. 

# **Hatching a Catastrophe**

How does one control a big project on a tight schedule? The first step is to have a schedule. Each list of events, called milestones, has a date.

Milestones must be concrete, specific, measurable events, defined with knife-edge sharpness.

A programmer will rarely lie about milestone progress, if the milestone is so sharp he cannot deceive himself.

Chronic schedule slippage is a morale-killer. If you miss one deadline, make absolutely sure you make the next one.

Hustle is an essential gift of great players and great teams. It is the characteristic of running after than necessary, moving sooner than necessary, and trying harder than necessary.

A plans and controls team is invaluable for a large project. It has no authority except to ask all the line managers when they will have set or changed milestones, and whether milestones have been met.

One must have review techniques by which true status becomes known to all players. For this purpose, a milestone schedule and completion document is the key.

# **The Other Face**

- Teachers and managers have by and large failed to instill in programmers an attitude about documentation that will inspire for a lifetime, overcoming sloth and schedule pressure.
- This failure is due to the lack of show on how to document effectively.

**Useful prose description**

1. purpose. What is the main function, and the reason for the program?
2. environment. On what machines, hardware configurations, and operating system configurations will it run?
3. domain and range. What domain of input is valid? What range of output can legitimately appear?
4. functions realized and algorithms used. Precisely what does it do
5. input-output formats precise and complete
6. operating instructions, including normal and abnormal ending behavior, as seen at the console and on the outputs
7. options What choices does the user have about functions?
8. Exactly how are those choices specified?
9. running time. How long does it take to do a problem of a specified size on a specified configuration?
10. accuracy and checking. How precise are the answers expected to be? What means of checking accuracy are incorporated?

**Test cases**. It Falls into three parts of the input data domain:

1. Mainline cases that test the program’s chief functions for commonly encountered data.
2. Barely legitimate cases that probe the edge of the input data domain, ensuring that the largest possible values, smallest possible values, and all kinds of valid exceptions work.
3. Barely illegitimate cases that probe the domain boundary from the other side, ensuring that invalid inputs raise proper diagnostic messages.

Components of the overview of the program:

1. A flow chart or subprogram structure graph.
2. Complete descriptions of the algorithms used, or else references to such descriptions in the literature.
3. An explanation of the layout of all files used.
4. An overview of the pass structure, the sequence in which data or programs are brought from tape or disk, and what is accomplished on each pass.
5. A discussion of modifications contemplated in the original design, the nature and location of hooks and exits, and a discursive discussion of the ideas of the original author about what modifications might be desirable and how one might proceed. His observations on hidden pitfalls are also useful.  

**Self-documenting program**

1. Use a separate job name for each run, and maintain a run log showing what was tried, when, and the results. If the name is composed of a mnemonic part and a numerical suffix, the suffix can be used as a run number, tying listings and logging together. This technique requires a new job card for each run, but they can be made up in batches, duplicating the common information.
2. Use a program name that is mnemonic but also contains a version identifier. That is assume there will be several versions.
3. Incorporate the prose description as comments on the procedure.
4. Refer to standard literature to document basic algorithms wherever possible. This saves space, usually points to a much fuller treatment than one would provide, and allows the knowledgeable reader to skip it with confidence that he understands you.
5. Show the relationship to the book algorithm: a) changes b) specialization c) representation
6. Declare all variables. Use mnemonic names. Use comments to convert DECLARE into a complete legend. Note that it already contains names and structural descriptions, it needs only to be augmented with descriptions of purpose. By doing so, one can avoid repeating the names and structural descriptions in a separate treatment.
7. Mark the initialization with a label.
8. Label statements in groups to show correspondence to the statements in the algorithm described in the literature.
9. Use indenting to show structure and grouping.
10. Add logical flow arrows to the listing by hand. They are very helpful in debugging and changing. They may be incorporated in the right margin of the comments space and made part of the machine-readable text.
11. Use line comments or remarks on anything that is not obvious. If the techniques above have been used, these will be short and fewer in number than is customary.
12. Put multiple statements on one line, or one statement on several lines to match thought-grouping and to show correspondence to other algorithm descriptions.

In the documentation for use by program modifiers, tell why things are like they are, rather than merely how they are. The purpose is the key to understanding.

# **No Silver Bullet - Essence and Accident**

- any software system should be grown by incremental development.
- The system should first be made to run, even though it does nothing useful except call the proper set of dummy subprograms.
- Then, bit by bit it is fleshed out, with the sub-programs in turn being developed into actions or calls to empty stubs in the level below.

# **The Mythical Man-Month after 20 years**

There needs to be a need for the separation of architecture from implementation and realization.

⇒ Choose a manager and a separate architecture. 

Write down the attributes of the expected user set:

- who they are
- what they need
- what they think they need
- what they want

Write down explicit guesses for the attributes of the user set. (It is far better to be explicit and wrong than to be vague.)

> The top performers’ space is quieter, more private, and better protected against interruption.
>
