## Chapters and code solutions

**Introduction**
- Chapter 1 Introducing Tools and Skills for .NET: [code/Chapter01](code/Chapter01)

**Tools**
- Chapter 2 Making the Most of the Tools in your Code Editor: [code/Chapter02](code/Chapter02)
- Chapter 3 Source Code Management Using Git: [code/Chapter03](code/Chapter03)
- Chapter 4 Debugging and Memory Troubleshooting: [code/Chapter04](code/Chapter04)
- Chapter 5 Logging, Tracing, and Metrics for Observability: [code/Chapter05](code/Chapter05)

**Skills**
- Chapter 6 Documenting Code, APIs, and Services: [code/Chapter06](code/Chapter06)
- Chapter 7 Observing and Modifying Code Execution Dynamically: [code/Chapter07](code/Chapter07)
- Chapter 8 Protecting Data and Apps Using Cryptography: [code/Chapter08](code/Chapter08)
- Chapter 9 Building a Custom LLM-based Chat Service: [code/Chapter09](code/Chapter09)
- Chapter 10 Dependency Injection, Containers, and Service Lifetime: [code/Chapter10](code/Chapter10)

**Testing**
- Chapter 11 Unit Testing and Mocking: [code/Chapter11](code/Chapter11)
- Chapter 12 Integration and Security Testing: [code/Chapter12](code/Chapter12)
- Chapter 13 Benchmarking Performance, Load, and Stress Testing: [code/Chapter13](code/Chapter13)
- Chapter 14 Functional and End-to-End Testing of Websites and Services: [code/Chapter14](code/Chapter14)
- Chapter 15 Containerization Using Docker: [code/Chapter15](code/Chapter15)
- Chapter 16 Cloud-Native Development Using .NET Aspire: [code/Chapter16](code/Chapter16)
- [Aspire 9 upcoming features - Twitter 🧵](https://x.com/davidfowl/status/1840969475367326070)

**Design**
- Chapter 17 Design Patterns and Principles
- Chapter 18 Software and Solution Architecture Foundations
- Chapter 19 Your Career, Teamwork, and Interviews

## Code editors and the solutions

Visual Studio, Rider, and VS Code + C# Dev Kit can use the same code solution files and projects for each chapter, found here: [/code](/code). 

> **Warning!** If you use multiple code editors to open these solutions, be aware that the build process can conflict. This is because Visual Studio has its own non-standard build server that is different from the standard build server used by .NET SDK CLI. My recommendation is to only have a solution open in one code editor at any time. You should also clean the solutions between opening in different code editors. For example, after closing the solution in one code editor, I delete the `bin` and `obj` folders before then opening in a different code editor.

