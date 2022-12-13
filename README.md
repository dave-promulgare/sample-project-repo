# Project Name
This paragraph is a description of the project.  It should include information on what you are trying to achieve and any background information on the business use case your are working on.  Try to keep this to one or two paragraphs.  Remember that this documentation is intended to look like an actual commercial project and not like a course assignment.

# Requirements

Provide a short description of how you gathered the project requirements for this business use case.  Cite any references and how you used them.

## Problem Statement

The problem statement is used to describe the specific problem that your software solution is trying to solve.  A problem statement is a description of a problem that a company would have in the industry they are in.  For example if a company is in the construction industry, they may have a problem where they have a variety of concrete suppliers and concrete inspectors and they want to track the grades of concrete who inspected it and when, with each supplier and contractor providing their information.  The specific problem might be that the suppliers are claiming that they delivered good concrete, but the inspectors did not inspect it at the right time.  

## Goals

The goals outline what the project is trying to accomplish.  Goals would be things like,  "lower the amount of time to process an order", or "provide end-to-end assurance on the provenance of goods."   For each goal, provide information on how you will measure the goal.

## Stakeholders

This is a list of people or organizations that may be involved with the solution to the problem.  The stakeholder list is often used as starting point for roles within the software solution.

## Restrictions/Rules

When you work out the requirements of the system, you will gather a set of rules and restrictions that you will need to code into your solution.  Some examples could be, "students may only take six courses per term", or "the maximum tokens per project owner is 100". It may be useful to put your rules/restrictions in a table and number them for reference.

## Data

Use this to capture what data needs to be input into the system, what is stored, and what is output.  This data helps you design the data structures for the solution.

## Exceptions

Exceptions are special cases where the restrictions/rules do not apply.  Maybe something like, "students who have enrolled in the special degree may take up to eight courses per term."

## User/Technical Stories

The user stories are intended to gather requirements that speak to the experience that a user would have or to capture what processes need to happen on the technical side.  Here are some examples:

| Story                                                        | Context                                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| The user clicks on the login button to get to the login screen | This is for all users                                        |
| The user is prompted to approve the transaction using their Metamask wallet | Need to have the metamask wallet connected to the app        |
| The system listens for an invoice event emitted by the smart contract | The emit should include the amount, date, invoice #, and customer ID |

# Architecture

The architecture describes how you will be creating the solution to the problem identified in the requirements.  It needs to take in the information gathered in the requirements and to identify the approach being used to take them into account to build the solution.

## Project Description

This section describes the project from the point of view of how you will develop the solution.  It should talk about your overall architectural approach, the design patterns you may be using and any challenges you may see in developing the system.

## Data

In this section you describe the data and data structures you will be using in your code.

## Functions

Provide a list and description of functions that you will need to implement along with input parameters, return types, qualifiers, modifiers, visibility specifiers, and a list of asserts or requires you may use at the top of the function.

## Diagrams

Add in your conceptual diagrams here.  If your solution has a sophisticated workflow, you might want to provide a sequence diagram.  Look at Plant UML as a simple tool to create reusable sequence diagrams (https://plantuml.com/).  For conceptual diagrams, you can use a temporary free diagram tool like Lucid Chart (https://www.lucidchart.com/pages/).

## Technology Stack

In your technology stack, you should specify the blockchain, the development languages and frameworks, as well as any services being used.  This is an opportunity to show off all  of the technology that you have learned and use in your solution.

## Security

Provide a short paragraph that talks about how you have considered security in your architecture in the smart contract, web code, and the technology stack.

# Project Plan

Provide a GANTT chart diagram that shows the tasks, how long they will take and who will be doing them.  You can use a free online gantt chart generator (https://www.onlinegantt.com/#/gantt).  If you don't add a Gantt chart you can provide a table.

| Task                | Description                                                  | Time Estimate | Dependencies                     |
| ------------------- | ------------------------------------------------------------ | ------------- | -------------------------------- |
| Gather requirements | Talk to stakeholders to find out rules                       | 1 day         | Identity stakeholders            |
| Transfer input form | Develop the web form for capturing how many tokens to transfer. | 4 hours       | Create web application framework |





