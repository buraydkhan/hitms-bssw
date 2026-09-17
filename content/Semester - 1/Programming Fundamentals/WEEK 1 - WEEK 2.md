# WEEK 1

## Lecture 1  : Introduction to problem solving 

> [!question] What is a program ?
> A **program** is a set of ordered instructions written in a programming language that tells a computer how to perform a specific task or solve a problem.
> Programming -> Planning
> To plan some solution

> [!question] Why is problem solving needed ? is it a crucial skill ?
> Because solving problem is necessary and effective

> [!question]  How to solve a problem ?
> Problem -> Thinking -> Solution
> 5 steps of problem solving :
> Define -> Brainstorm -> Pick -> Implement -> Review

> [!question] Q : If a person needs a tea at morning what should he do ?
> Define : Needing a tea at morning
> Brainstorming : He should make tea by himself
> PIck : Choosing the option
> Implement : Put into his daily life
> Review : He doesnt make a good tea.
> Okay, so we are at the cutting board again , lets try some other option.
> He should buy a machine for it -> Too expensive for him
> Maybe he should quit it -> He can't do it
> Maybe he should ask someone to make his tea -> He doesnt see it as a healthy option.
> Buying it from a hotel -> Too much time is wasted by waiting for tea.
> There isnt one solution to the problem, there are multiple ways to solve it but not everytime it works well. So we keep trying to come up with ways to eaze the process
## Lecture 2 : Von Newmann Architecture

> [!NOTE] **John von Neumann** 
> (1903–1957) was a Hungarian-American mathematician, physicist, and computer scientist who laid the foundational architecture for modern computing.
> - **Von Neumann Architecture:** Proposed the stored-program computer concept in 1945, where both program instructions and data share the same memory space.
> - **CPU Design:** Defined the fundamental structure of the processing unit, comprising the Control Unit (CU), Arithmetic Logic Unit (ALU), and internal registers.
> - **Execution Cycle:** Established the sequential instruction processing pipeline—Fetch, Decode, Execute.
> - **Von Neumann Bottleneck:** Identified the throughput limitation caused by the shared bus between the CPU and memory, which remains a primary focus in modern processor design.
> - **Computing Contributions:** Worked on early digital computers like the ENIAC and IAS machine, advancing numerical analysis, weather prediction models, and nuclear simulation algorithms.

![[licensed-image.jpeg|440]]

> [!NOTE] HIstorical Significance 
> 1. Foundation of modern computing 
> 2. Stored program concept 
> 3. Influence on computer programming 
> 4. Separation of concerns 
> 5. Impact on comnputer science theory

## Lecture 3 : Algorithms and Integrated Development Environment (IDE)

> [!question] What is Algorithm ?
> An **algorithm** is a clear, step-by-step set of rules or logical instructions designed to solve a specific problem or perform a task in a finite number of steps.
> 
> While every algorithm is a set of instructions, not every set of instruction is an algorithm.

Ways to show Algorithm :

- Its like a reciepe 
- It can be in mutual language
- Can be displayed via flowcharts
- Pseudo code 
- Symbolic 

> [!question] What is Integrated Development Environment (IDE) ?
> An **Integrated Development Environment (IDE)** is a single software application that gives programmers all the essential tools they need to write, test, and debug code in one place.
> 
> Instead of opening separate programs to write code, run it, and fix errors, an IDE combines everything into one unified dashboard.

> [!NOTE] Core Components
> What IDE contains  : 
> 
> Code/Text Editor : To write and edit code
> Translator : To translate the programming language. You can either use Compiler or Intepreter.
> 1. Compiler -> Translate the code in batch/bunch of it at once and its good for when you know you don't do that much error, finds out the syntax error. Also saves alot of time. 
> 2. Intepreter -> Translate the code line by line and its good for when you do alot of error, finds out the syntax error. Takes up more time than Compiler.
> Linker : To link all the code in one place
> Loader : Takes that finished executable file from the hard drive, loads it into the computer's RAM, sets up the memory space, and starts its execution.
> Debugger : Helps you to find and fix bugs in your code, especially logical errors.
> 

## Lecture 4 : Programming Languages and Paradigms

> [!NOTE] UNDERSTANDING
> How can Ali communicate with John ?
> With the help of a language 
> What if John is chinese ?
> The information couldnt be shared
> Solution -> Mutual language should be use or translator
> 
> How can Ali communicate with computer ?
> WIth the help of a programming languages or a translator

> [!NOTE] 
> Definition : 
> A **paradigm** is a distinct set of concepts, patterns, or thought frameworks that defines a specific way of viewing, understanding, or doing something within a discipline.
> 
> TASK : PLAN A BIRTHDAY PARTY WITH THE HELP OF PROGRAMMING PARADIGMS
> 
> TYPES OF PARADIGMS :
> 
> Procedural Paradigm : 
> Writing out a step by step checklist
> 1. Choose a venue
> 2. Send out invitations
> 3. Order decorations
> 4. Setup the venue
> 5. Host the party
> 
> Functional Paradigm :
> Outsourcing specific tasks to specialists who return results independently
> 1. findVenue() : FInds a suitable venue based on location, size, and date
> 2. sendInvitations() : Sends invitations and returns a list of attendees
> 3. arrangeCatering() : Orders food and drinks based on the guest list
> 4. decorateVenue() : Sets up decorations at the venue
> 
> Object Oriented Paradigms :
> Assigning tasks to different people and teams who specialize in various areas
> 1. Venue Manager : Responsible for choosing and setting up the venue
> 2. Invitation Team : Manages sending out invites and tracking RSVPs
> 3. Caterer : Handles food and drink orders
> 4. Decor Team : Orders and sets up decoration
> 
> Event-Driven Programming :
> Planning the party based on key events or triggers
> 1. Venue Booked : Once the venue is confirmed, the Invitations Team is notified to send invites
> 2. RSVP Received : When RSVPs come in, the Caterer adjusts the food order
> 3. Data Nearing : A few days before the party, the Decor Team is notified to start setting up

