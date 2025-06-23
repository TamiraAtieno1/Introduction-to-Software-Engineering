# Agile Software Development

## Agile Methods
- Were created as a result of Dissatisfaction with the overheads involved in software design methods of the 1980s and 1990s.
- These methods:

  1.Focus on the code rather than the design
  
  2. Are based on an iterative approach to software development
     
  4. Are intended to deliver working software quickly and evolve this quickly to meet changing requirements.
  
- The aim of agile methods is to reduce overheads in the software process (e.g. by limiting documentation) and to be able to respond quickly to changing requirements without excessive rework.

###Thee principles of Agile methods
![image](https://github.com/user-attachments/assets/9466e258-7d45-4a37-95c7-e86bff254060)




### Rapid software development
- Specification, design and implementation are inter-leaved
- System is developed as a series of versions with stakeholders involved in version evaluation
- User interfaces are often developed using an IDE and graphical toolset.

### Problems with Agile Methods
It can be difficult to keep the interest of customers who are involved in the process.
Team members may be unsuited to the intense involvement that characterises agile methods.
Prioritising changes can be difficult where there are multiple stakeholders.
Maintaining simplicity requires extra work.
Contracts may be a problem as with other approaches to iterative development.

### Plan driven and Agile development
Plan-driven development
  A plan-driven approach to software engineering is based around separate development stages with the outputs to be produced at each of these stages planned in advance.
  Not necessarily waterfall model – plan-driven, incremental development is possible
  Iteration occurs within activities. 
Agile development
  Specification, design, implementation and testing are inter-leaved and the outputs from the development process are decided through a process of negotiation during the software development process.
  Plan-driven development
A plan-driven approach to software engineering is based around separate development stages with the outputs to be produced at each of these stages planned in advance.
Not necessarily waterfall model – plan-driven, incremental development is possible
Iteration occurs within activities. 
Agile development
Specification, design, implementation and testing are inter-leaved and the outputs from the development process are decided through a process of negotiation during the software development process.

![image](https://github.com/user-attachments/assets/1cb84718-dcf0-497e-bbc4-a52d2161e927)

### Teechnical, human and organizational issus
Most projects include elements of plan-driven and agile processes. Deciding on the balance depends on:
  Is it important to have a very detailed specification and design before moving to implementation? If so, you probably need to use a plan-driven approach.
  Is an incremental delivery strategy, where you deliver the software to customers and get rapid feedback from them, realistic? If so, consider using agile methods.
  How large is the system that is being developed? Agile methods are most effective when the system can be developed with a small co-located team who can communicate informally. This may not be possible for large systems that require larger development teams so a plan-driven approach may have to be used. 

### What type of system is being developed? 
Plan-driven approaches may be required for systems that require a lot of analysis before implementation (e.g. real-time system with complex timing requirements).
What is the expected system lifetime? 
  Long-lifetime systems may require more design documentation to communicate the original intentions of the system developers to the support team. 
What technologies are available to support system development? 
  Agile methods rely on good tools to keep track of an evolving design
How is the development team organized? 
  If the development team is distributed or if part of the development is being outsourced, then you may need to develop design documents to communicate across the development teams. 
Are there cultural or organizational issues that may affect the system development? 
  Traditional engineering organizations have a culture of plan-based development, as this is the norm in engineering.
How good are the designers and programmers in the development team?
   It is sometimes argued that agile methods require higher skill levels than plan-based approaches in which programmers simply translate a detailed design into code
Is the system subject to external regulation? 
  If a system has to be approved by an external regulator (e.g. the FAA approve software that is critical to the operation of an aircraft) then you will probably be required to produce detailed documentation as part of the system safety case.

### Extreme Programming
Perhaps the best-known and most widely used agile method.
Extreme Programming (XP) takes an ‘extreme’ approach to iterative development. 
New versions may be built several times per day;
Increments are delivered to customers every 2 weeks;
All tests must be run for every build and the build is only accepted if tests run successfully.

### XP and Agile Practices
Incremental development is supported through small, frequent system releases.
Customer involvement means full-time customer engagement with the team.
People not process through pair programming, collective ownership and a process that avoids long working hours.
Change supported through regular system releases.
Maintaining simplicity through constant refactoring of code.

### Extreme Programming release cycle
![image](https://github.com/user-attachments/assets/e1e3a3c8-74c1-4dd2-a2e2-0e49c4fe3952)

### Extreme Programming practices

### Requirement scenarios
In XP, a customer or user is part of the XP team and is responsible for making decisions on requirements.
User requirements are expressed as scenarios or user stories.
These are written on cards and the development team break them down into implementation tasks. These tasks are the basis of schedule and cost estimates.
The customer chooses the stories for inclusion in the next release based on their priorities and the schedule estimates.

### XP and change
Conventional wisdom in software engineering is to design for change. It is worth spending time and effort anticipating changes as this reduces costs later in the life cycle.
XP, however, maintains that this is not worthwhile as changes cannot be reliably anticipated.
Rather, it proposes constant code improvement (refactoring) to make changes easier when they have to be implemented.

### Refactoring
Programming team look for possible software improvements and make these improvements even where there is no immediate need for them.
This improves the understandability of the software and so reduces the need for documentation.
Changes are easier to make because the code is well-structured and clear.
However, some changes requires architecture refactoring and this is much more expensive.

### examples of refactoring
Re-organization of a class hierarchy to remove duplicate code.
Tidying up and renaming attributes and methods to make them easier to understand.
The replacement of inline code with calls to methods that have been included in a program library.

### Key points
Agile methods are incremental development methods that focus on rapid development, frequent releases of the software, reducing process overheads and producing high-quality code. They involve the customer directly in the development process.
The decision on whether to use an agile or a plan-driven approach to development should depend on the type of software being developed, the capabilities of the development team and the culture of the company developing the system.
Extreme programming is a well-known agile method that integrates a range of good programming practices such as frequent releases of the software, continuous software improvement and customer participation in the development team.
















