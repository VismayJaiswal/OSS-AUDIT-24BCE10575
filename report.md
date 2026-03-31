Open Source Software Audit Report

Git – Distributed Version Control System

Student Information

Name: VISMAY JAISWAL
Roll Number: 24BCE10575
Course: Open Source Software
Selected Software: Git

Abstract

This report presents a comprehensive analysis of Git, a distributed version control system extensively used in modern software development. The study covers its background, design principles, internal structure, and role within the open-source ecosystem, particularly in Linux environments.

Along with theoretical understanding, the report includes five shell scripts that demonstrate practical knowledge of Linux commands and open-source tools. The objective of this project is to examine Git’s significance, evaluate its strengths and limitations, and understand how it supports collaborative development. A comparison with proprietary tools is also included to highlight its advantages.

1. Overview of Open Source Software

Open source software refers to programs whose source code is publicly accessible. Users are allowed to view, modify, and distribute the software freely. This model differs significantly from proprietary software, where access to source code is restricted.

The open-source approach promotes collaboration, transparency, and continuous improvement. Developers from across the globe contribute to projects, making them more reliable and innovative.

Open source software is widely used in areas such as:

Operating systems
Web technologies
Programming languages
Databases
Development frameworks

Popular examples include:

Linux
Git
Apache
Python
Mozilla Firefox

For students and developers, open source provides an excellent opportunity to learn by exploring real-world codebases.

2. Introduction to Git

Git is a distributed version control system designed to manage changes in files over time. It is mainly used in software development but can also handle other types of projects.

Git enables users to:

Track file modifications
Collaborate efficiently
Maintain version history
Work with branches
Merge updates seamlessly

Unlike traditional systems, Git allows every user to maintain a complete copy of the repository, making it faster and more reliable.

3. Background of Git

Git was introduced in 2005 by Linus Torvalds during the development of the Linux kernel. Before Git, developers relied on a proprietary tool, which later caused licensing issues.

To overcome these limitations, Git was developed with key objectives such as:

High efficiency
Strong data integrity
Distributed workflow
Flexible branching
Scalability

Since then, Git has become the industry standard for version control.

4. Creator of Git

Linus Torvalds, a renowned software engineer and creator of Linux, developed Git to simplify and improve large-scale project management.

His focus was on performance, simplicity, and reliability. Today, Git is used globally by millions of developers and organizations.

5. Purpose Behind Git Development

Git was designed to address several challenges faced in earlier systems, including:

Slow operations
Limited branching capabilities
Dependence on centralized servers
Poor scalability

By introducing a distributed structure, Git significantly improved development workflows.

6. Git Architecture

Git operates using a distributed model, where each user has a full copy of the repository.

It consists of three main components:

Working Directory – where files are modified
Staging Area – where changes are prepared for commit
Repository – where all versions are stored

Git uses snapshots instead of tracking individual file changes, which enhances efficiency.

7. Key Features of Git

Some of Git’s important features include:

Distributed version control
Efficient branching and merging
High speed performance
Strong data integrity using hashing
Support for large projects
8. Git Workflow

The general workflow in Git includes:

Editing files
Adding changes to staging
Committing updates
Pushing changes to remote repository

This structured approach helps maintain consistency in development.

9. Git vs Centralized Systems

Traditional systems like SVN and CVS follow a centralized approach.

Feature	Git	SVN/CVS
Architecture	Distributed	Centralized
Performance	Faster	Slower
Offline Work	Supported	Limited
Branching	Simple	Complicated

Git offers more flexibility and efficiency compared to centralized systems.

10. Git vs Proprietary Tools

Git competes with proprietary tools such as BitKeeper and Perforce.

Advantages of Git:

Free and open source
Large community support
High adaptability

These factors make Git a preferred choice over paid alternatives.

11. Git in Linux Environment

Git plays a crucial role in Linux-based development. It is extensively used in managing contributions to major open-source projects.

Examples include:

Linux Kernel
GNOME
KDE

Most open-source repositories rely on Git for version control.

12. Installing Git on Linux

Git can be installed using system package managers:

Ubuntu:

sudo apt install git

Fedora:

sudo dnf install git

To verify installation:

git --version
13. Basic Git Commands

Common commands include:

Initialize repository: git init
Clone repository: git clone
Add files: git add .
Commit changes: git commit -m "message"
Push changes: git push
14. Branching and Merging

Git supports multiple branches for parallel development.

Create branch: git branch feature
Switch branch: git checkout feature
Merge branch: git merge feature

This allows developers to work independently without affecting the main codebase.

15. Remote Repositories

Remote platforms enable collaboration among developers.

Popular platforms include:

GitHub
GitLab
Bitbucket

Commands:

Push: git push origin main
Pull: git pull origin main
16. Role in Open Source Development

Git simplifies collaboration by allowing:

Forking repositories
Submitting pull requests
Reviewing code changes

It has become essential for open-source contribution workflows.

17. Shell Script Implementation

This project includes five scripts demonstrating Linux operations:

System Identity Report
Package Inspector
Disk Audit
Log Analyzer
Manifesto Generator
18–22. Script Descriptions

Each script performs a specific task:

System Identity Report: Displays system details
Package Inspector: Checks Git installation
Disk Auditor: Examines directory permissions
Log Analyzer: Searches keywords in logs
Manifesto Generator: Creates custom open-source text
23. Screenshots

All script outputs are documented through screenshots included in the repository.

24. Advantages of Git
Open source and free
Fast and efficient
Supports distributed work
Ensures data security
25. Limitations of Git
Requires initial learning effort
Commands may seem complex for beginners
26. Applications

Git is widely used in:

Software development
Team collaboration
Documentation management
27. Learning Outcomes

This project helped in understanding:

Git concepts and workflow
Open-source principles
Linux shell scripting
28. Conclusion

Git is a powerful and essential tool in modern software development. Its distributed nature and efficiency make it highly suitable for collaborative environments.

This project provided both theoretical knowledge and practical exposure, enhancing understanding of open-source systems and Linux operations.

29. References
Official Git Documentation
Linux Documentation
Open Source Initiative
Author

VISMAY JAISWAL
24BCE10575