# Functional Overview

This repository will be the home for all of the functional defintions and use cases that will be explored and validated as part of the pilot phase for the new 'Chain to Ecosystem' pilot during 2020.

The initial document that outlined the approach can still be found here:

[SEM - Moving from a Chain to an Ecosystem](https://github.com/stichtingsem/functional-overview/raw/master/documents/sBDL%20-%20Moving%20from%20a%20Chain%20to%20an%20Ecosystem%20-%20v2.docx)

## Rationale

This repository is split into the documents that provide a functional overview for how the ecosystem works, with definitions of the high level services, actors, data entities and use cases.

The initial intent is to guide the prototype / validation stage of the process, and keep the work streams aligned through the summer of 2020.  This repository may evolve into the basis for the standards related to the services and APIs.

We are using Github to ensure that all work and discussions are held completely in the open, and that the source code for any example services or data exchanges are held and versioned alongside any of the functional documentation.

## Scope of Pilot

The scope of the pilot in June 2020 is focusing on the use cases OA.3 and OA.4 (ordering and access), the other use cases will be explored in further phases.

## Structure

 Documents | description
-----------|---
 [Services](/services)  |  Description of the services that can be provided by any or all participants.
 [Roles](/roles)     |  Description of roles that exist to perform actions in and across the [services](/services).
 [Use Cases](/use-cases) |  Description of high level processes, and then smaller steps within a process to allow for functional and technical design, testing and validation.
 [Entities](/entities) |  Overview of data entities exchanged as part of the use cases.
[Glossary](glossary.md) |  Definition of key terms.

## Functional track documentation

The functional track consisted of a representatives from distributors (TLN, Iddink), publishers (ThiemeMeulenhoff, Noordhoff) and SIS/LMS providers (Magister, Topicus). 

To understand user problems. For this we used a document describing assumptions, scenarios and scripts to be tested with users.
- [Document with assumptions, scenarios and scripts](https://docs.google.com/document/d/1INANV13mkSVTCpcQbIa_IYDOLMzcUa9tBX7xkkapujA/edit?usp=sharing)

In the first half of July 2020 we conducted five qualitative interviews with users, both Teachers and LMC's. We created wireframes for these scenarios. 
- [Wireframe scenario 1](https://xd.adobe.com/view/b968ebdc-44b2-4058-ac3c-100da4ca0c66-ec3b/)
- [Wireframe scenario 2](https://xd.adobe.com/view/dee50525-5c36-4f5c-a6d1-a0dace226409-8bb6/)
Because we were testing scenarios that were pre-competitive, the solutions shared in these interviews proved to be too abstract and so led to confused users. We did get a better understanding of the issues that users were experiencing and decided to pivot our approach to a survey.

To come to a survey, we started out discussing all observed user issues in both interviews and input from SEM-participants. From the long-list we started clustering double entries and ranked the issues on importance and relevance. We converted the issues to problem statements. Next, we added broad solutions derived from the SEM ecosystem design. In the compiled user survey, users are asked to identify with specific roles (teachers, LMS, etc) to only present relevant questions to users. Further, users are asked whether they agree a solution resolves the stated issue. The survey has been approved by the Steering Committee and SEM Board.    
- [List of user issues for survey](https://docs.google.com/spreadsheets/d/1tzkGO8-g5i4NEa_VzCS9KSnUBlt8qaq-65KyhsHWVxs/edit#gid=0/)
- [User survey] (https://forms.gle/Gq31vWQWCQv8dHxKA)

## Process for making changes

The working practices of this group will follow typical processes of technology standard groups and open source projects.

- All documentation (where possible) will be in plain text files in a repository like this one.  This makes it accessible for all and easy to version control and track changes over time.
- To make changes, please take a local copy of the files, make the changes, and submit them back as a [pull request](https://lab.github.com/githubtraining/reviewing-pull-requests).  This ensures that discussion can occur in the open on any change before it is agreed, and we maintain a clear and transparent history once the process begins.
- You can make small changes using the web editor, but you still need to submit your changes via a pull request.
- Pull requests will be reviewed by an agreed group of reviewers for each stream (TBD).
- If you would just like to start a discussion, please create an [issue](https://github.com/stichtingsem/functional-overview/issues) in this repository.

## Working with Markdown & Github

If you are not familiar with either Markdown or Github, it is best you start with some quick reads:

- [Introduction to Github](https://lab.github.com/githubtraining/introduction-to-github)
- [Using Markdown](https://lab.github.com/githubtraining/communicating-using-markdown)
- [Pull Requests](https://lab.github.com/githubtraining/reviewing-pull-requests)

### Free Editors and Tools

- [Github Desktop Client](https://desktop.github.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Zettlr Markdown Editor](https://www.zettlr.com/)
