---
layout: default
title: Spring Final Delivery Requirements
---

Due: 2024-06-07T23:59

- [ ] Project README, GitHub Issues and Sprint Boards (3 points)
  - [ ] instructions for (imagine new team-member)
    - [ ] setting up dev environment (environment variables)
    - [ ] testing (test commands / scripts)
    - [ ] managing continuous integration
    - [ ] code style / linting / formatting
  - [x] make sure GitHub repository is up to date on issues and boards
    - [x] do not delete issues
    - [x] concluded issues should be closed with estimates and actuals logged
    - [x] add comments to unfinished issues and log time spent thus far
- [x] Requirements and Design Specification Document (2 points)
  - [x] update tech spec from CSC 308 according to current state of solution
    - [x] Requirement changes and design modifications if applicable
      - [x] requirements
      - [x] user stories
      - [x] design section
    - [x] data schema changes
    - [x] tests
  - [ ] enumerate changes in new section at the top called "Updates From Previous
        Version"
- [ ] Software Tests
  - [ ] Unit/Integration Tests (5 points)
    - [ ] need both, but graded together
    - [ ] 80% branch coverage of model functions
  - [ ] Acceptance Tests (5 points)
    - [ ] automate with end-to-end testing and API testing
    - [ ] Two end-to-end testing scenarios (pertaining the same feature or not)
    - [ ] Two API testing scenarios (one using a GET and another using a POST
          endpoint, pertaining the same feature or not)
    - [ ] accompanied by their acceptance criteria spec following Gherkin language
    - [ ] add acceptance criteria spec of implemented tests to the "Tests" section of
          the Tech Spec
    - [ ] automated acceptance tests need not be in the CI/CD pipeline (run and pass
          locally is okay)
- [ ] CI/CD (5 points)
  - [ ] GitHub Actions for each repo
  - [ ] Build statues badges on top of README
  - [ ] backend should run all the unit/integration test cases for the backend (see
        the previous section about unit/integration testing)
  - [ ] deployment
    - [ ] add URL to README and product spec
- [ ] Overall Implementation (16 points)
  - Have you (as an individual team member) provided enough code contributions over the dev sprints in this quarter?
    - The source code repository is the main source for this assessment.
    - Secondary sources: status reports and the end-of-quarter self/peer evaluation.
  - Has the team shown an evolution of tasks implemented and functionality delivered over the dev sprints in this quarter?
    - The source code repository and my notes from the sprint reviews are the main sources for this assessment.
    - Secondary sources: status reports and the end-of-quarter self/peer evaluation.
  - Has the team delivered enough completed work by the end of the quarter? Is the effort put, overall, equivalent to five dev sprints in our schedule (10 weeks)?
    - The source code repository and my notes from the sprint reviews are the main sources for this assessment. Secondary sources: status reports and the end-of-quarter self/peer evaluation.
  - Does the implementation follow a sound software design with appropriate architecture as planned in this course?
    - The source code repository and my notes from the sprint reviews are the main sources for this assessment.
  - Is the code clean?
    - Is there evidence that the team took care of internal code quality?
    - Or the opposite: Is there evidence that the team was not able to provide a good design (e.g., too many code duplications, too many commented out code, code not following style guidelines, code drifting away from the planned architecture, too many code smells and technical debt).
    - The source code repository is the main source for this assessment.
- [x] Oral Presentation (4 points)
  - 20-25 minutes (including questions)
  - every member speaks
  - [ ] slides and link to team github in canvas assignment
  - slides specification
    - Cover slide
      - Team name
      - App name
      - Participant full names
    - Recall the product vision
      - features implemented
      - features planned but not implemented
    - Recall the tech stack and highlight relevant additional frameworks, libraries, or databases utilized and external services/APIs consumed. Illustrations are welcome here.
    - Product demo (whole scope, not only last sprint work)
      - This should take the most part of your presentation time.
      - Provide examples/inputs with meaningful data. For instance, fill out a profile form with real names, dates, etc. If showing pre-existing data, make sure you populate them with real data, so it looks real in the demonstration. Try to tell a story as you give your demo and use your Personas and User Stories to guide you.
      - Speak (or have someone else speak) while you’re typing or clicking around during the demonstration.
    - Metrics
      - Estimates/actual for all 10 sprints
      - Velocity for all 10 sprints with an average line.
    - Project retrospective
      - What went well and what went not so well (lessons learned) overall (whole quarter).
      - same as above for just sprint 8
      - “Team superpower.” Be creative and try to collectively elect your team’s superpower.
        - It could be related to the process (e.g., planning and executing), team organization (e.g., communication), practices (e.g., version control, branching, code review), and tools (e.g., IDE, Git, linter), or to the product itself (UI, API, documentation, test code, code cleanness, etc.), or both.
        - This item is not graded and it's more like a suggestion than a strict request. I think that would be fun and something to add in this final retrospective that you did not have in the previous ones.
- Additional notes
  1. Individual project grades may differ among members of the same team.
  2. Any questions related to these instructions, please ask the instructor.
