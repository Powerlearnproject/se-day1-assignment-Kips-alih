[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18366954&assignment_repo_type=AssignmentRepo)
# SE_Day1
Software Engineering Day1 Assignment

#Part 1: Introduction to Software Engineering

Explain what software engineering is and discuss its importance in the technology industry.
This is a discipline that applies engineering principles to the design, development, maintenance, testing, and evaluation of software and systems.
It is essential in ensuring that the technology we use is efficient, reliable, secure, and able to evolve with time.


Identify and describe at least three key milestones in the evolution of software engineering.
The Birth of Software Engineering (1960-1970): The formalization of practices and the recognition of the need for structured software development.
The Waterfall Model (1970s): The introduction of a linear, stage-based approach to software development, marking a significant attempt to structure the software development lifecycle.
The Agile Revolution (1990s-2000s): The creation of the Agile Manifesto, leading to the adoption of flexible, iterative approaches to software development.
List and briefly explain the phases of the Software Development Life Cycle.
- Planning - identify the software requirement or purpose and scope.
- Requirement analysis - identify the final user specification. 
- Design - building the framework. 
- Coding - converting software design into tangible code.
- Testing - examine the software for any bugs and glitches


Compare and contrast the Waterfall and Agile methodologies. Provide examples of scenarios where each would be appropriate.
Waterfall methodology -
- Linear and sequential, each phase is completed before moving on. 
- Low flexibility after the project starts
- Testing is done after coding is complete.
- Heavy documentation required
- Low customer involvement	, mainly at the start and end


Agile methodology - Iterative and incremental, with multiple cycles (sprints). 
- High flexibility, adapts to changing requirements. 
- Regular customer feedback is incorporated into every sprint. 
- Testing is continuous and done after each iteration.
- Light documentation, focusing on working software
- Iterative, flexible, incremental


Describe the roles and responsibilities of a Software Developer, a Quality Assurance Engineer, and a Project Manager in a software engineering team.

Software Developer
- Writing Code: Developing software by translating requirements and design specifications into functional code.
- Designing Software: Collaborating with the team to design the architecture and components of the software.
- Debugging and Troubleshooting: Identifying and fixing bugs or issues in the code during the development phase or reported after release.
- Testing Code: Writing unit tests and performing initial tests to ensure that the code behaves as expected.
- Collaboration: Working closely with QA Engineers, Project Managers, and other developers to understand requirements and address challenges throughout the development process.
- Documentation: Documenting code and technical specifications to ensure that the software can be maintained and understood by others in the future.

Quality Assurance Engineer 
- Collaborate with stakeholders to understand and clarify software requirement.
- Create development standards and procedures for the programmers to follow
- Confirm that the software meets the requirement before deployment. 
- Analyse the product to identify bugs and suggest changes to make them more efficient. 
- Develop and execute automation scripts using open source tools.
  
Project Manager
- Project Planning
- Task Scheduling and Resource Management
- Risk Management
- Stakeholder Communication
- Tracking Progress
- Quality and Budget Control
- Facilitating Collaboration


Discuss the importance of Integrated Development Environments (IDEs) and Version Control Systems (VCS) in the software development process. Give examples of each.
An Integrated Development Environment (IDE) is a software application that provides comprehensive tools for developers to write, test, and debug their code. Example is Visual Studio Code (VS Code)
Importance in Software Development:
- Streamlined Workflow: IDEs provide developers with a single environment where they can write code, compile it, debug it, and test it.
- Code Assistance: Features like syntax highlighting, auto-completion, and error detection make coding faster and help reduce errors by providing real-time feedback.
- Debugging Tools: IDEs typically come with powerful debugging tools that allow developers to step through code, set breakpoints, inspect variables, and monitor program execution in real time. This makes finding and fixing bugs much easier.
- Integration with Other Tools: IDEs often support integration with build systems, version control systems, testing frameworks, and deployment tools.
- Customization and Extensibility: Many IDEs support plugins or extensions, allowing developers to tailor the environment to their specific needs or project requirements.


A Version Control System (VCS) is a tool used to track and manage changes to source code and files over time. Example of Version Control Systems is Git. 
Importance in Software Development:
- Collaboration: Version control allows multiple developers to work on the same codebase simultaneously without overwriting each other's changes.
- Tracking Changes: VCS records the history of changes made to the codebase, making it easy to understand what changes were made, when, and by whom.
- Code Backup and Recovery: With VCS, developers can revert back to earlier versions of the code if something breaks.
- Branching and Merging: Version control allows developers to create branches for new features or bug fixes.
- Code Reviews: VCS supports code review processes by enabling developers to create pull requests or merge requests, where code changes can be reviewed by peers before they are merged into the main project.
- Integration with CI/CD: Many modern VCS tools integrate with Continuous Integration/Continuous Deployment (CI/CD) pipelines, enabling automated testing, building, and deployment whenever changes are committed to the repository.


What are some common challenges faced by software engineers? Provide strategies to overcome these challenges.
- Rapid technological advancement places considerable pressure on software engineers to stay current.
 Solution: adopting continuous learning practices and using agile methodologies to adapt to emerging trends, keeping their skills sharp in an ever-evolving industry. -
- Time Constraints - Software engineering is a demanding and time-intensive field, often requiring engineers to work under high pressure to meet tight deadlines.
 Solution: adopt agile methodologies, such as Scrum, to streamline workflows by dividing large projects into manageable sprints 
- Limited Infrastructure - limited high-performance software engineering tools and computing platforms and inefficient data storage architectures. 
 Solution: Software engineers must rely heavily on a robust infrastructure to perform their jobs effectively.
- Changing Software Requirements - Software requirements are often dynamic and subject to frequent changes, making it challenging for engineers to design and develop solutions that meet users' needs while accounting for future updates and bug fixes. 
Solution: engineers can adopt approaches like agile development, which emphasizes iterative progress and adaptability, and modular design, which enables flexibility by breaking systems into manageable, independent components.
- Software Security - Programming secure software is a complex and challenging task. 
Solution: research ways to defend against hacking, malware, phishing, insider and third-party threats
- Software Accessibility and Usability - Overly complex software can frustrate or confuse users. 
Solution: Use scalable architecture, Emphasize reliability.


Explain the different types of testing (unit, integration, system, and acceptance) and their importance in software quality assurance.
Unit Testing:
This involves testing individual components or functions of an application in isolation to ensure they behave correctly. Unit testing improves code reliability and supports safer refactoring of code.

Integration Testing:
This focuses on verifying that different components or modules of the application work together as expected.This type of testing is critical to check whether interfaces between modules are functioning properly. Integration tests help prevent integration issues that might not appear during unit testing.

System Testing:
This tests the entire application as a whole to ensure it meets all functional and non-functional requirements.System testing is essential for identifying issues that could impact the overall performance or usability of the system.

Acceptance Testing:
This verifies that the software meets the business requirements and is ready for release. It is typically performed by end-users or stakeholders to confirm that the product satisfies their needs. Acceptance testing builds confidence among users and stakeholders that the system is ready for production use.

#Part 2: Introduction to AI and Prompt Engineering


Define prompt engineering and discuss its importance in interacting with AI models.
Prompt engineering refers to the process of designing and refining input prompts to effectively interact with AI models. It enables users to guide the AI to generate the most relevant and contextually appropriate responses.


Provide an example of a vague prompt and then improve it by making it clear, specific, and concise. Explain why the improved prompt is more effective.
Vague Prompt: "Tell me about computers."
Improved Prompt: "Explain the main components of a personal computer and how they work together." 
Improves prompt is a specific, clear, and concise 
