---
layout: default
title: Creating a Product Backlog
parent: Getting Started
nav_order: 2
has_children: true
has_toc: false
---

# Creating a Product Backlog

The product backlog is the prioritized list of feature enhancements or fixes for your product or service. The items that need to be delivered first 
appear at the top of the product backlog. The product owner and the development team collaborate review the items in the backlog. 

Large team initiatives are represented in your backlog as epics. Those epics will be broken down into several user stories. Each user story contains one or 
more tasks. Although your group may have multiple initiatives, there is just one product backlog. Users stories for each of the initiatives that you support are prioritized into a single list.
For example, let’s say that your team is building a call center software program. The big initiatives in this project are 1) creating the call center 
operator user interface 2) creating a database to store recordings and 3) creating a reporting tool for operator analytics. 

Each of these initiatives is an epic and contains its own user stories, as represented in the following table:

| User Interface                                                | Database                                             | Reporting Tool                                                       |
|---------------------------------------------------------------|------------------------------------------------------|----------------------------------------------------------------------|
| Create interface to display incoming calls. (UI-1)            | Build time series database store. (D-1)              | Create page to display operator statistics (# calls per hour). (R-1) |
| Create options to answer, transfer, and release calls. (UI-2) | Upload operator profile information.  (D-2)          | Create option to export operator statistics to XLS. (R-2)            |
| Create company directory UI screens. (UI-3)                   | Create API for direct query of reporting data. (D-3) | Create option to email monthly reports. (R-3)                        |

The product backlog for your project is one list that contains all of the user stories from each of the epics. A product owner may prioritize all of the user stories from a single epic (such as creating the database) over the user stories from the other epics (such as the reporting tool), or they might prioritize a mix of the users stories together.

So, the product backlog might look something like this:

| Priority | User Story                                                           |
|----------|----------------------------------------------------------------------|
| 1        | Build time series database store. (D-1)                              |
| 2        | Upload operator profile information. (D-2)                           |
| 3        | Create API for direct query of reporting data. (D-3)                 |
| 4        | Create interface to display incoming calls. (UI-1)                   |
| 5        | Create options to answer, transfer, and release calls. (UI-2)        |
| 6        | Create company directory UI screens. (UI-3)                          |
| 7        | Create page to display operator statistics (# calls per hour). (R-1) |
| 8        | Create option to export operator statistics to XLS. (R-2)            |
| 9        | Create option to email monthly reports. (R-3)                        |

Or, it could look something like this:

| Priority | User Story                                                           |
|----------|----------------------------------------------------------------------|
| 1        | Build time series database store. (D-1)                              |
| 2        | Upload operator profile information. (D-2)                           |
| 3        | Create company directory UI screens. (UI-3)                          |
| 4        | Create interface to display incoming calls. (UI-1)                   |
| 5        | Create page to display operator statistics (# calls per hour). (R-1) |
| 6        | Create options to answer, transfer, and release calls. (UI-2)        |
| 7        | Create API for direct query of reporting data. (D-3)                 |
| 8        | Create option to export operator statistics to XLS. (R-2)            |
| 9        | Create option to email monthly reports. (R-3)                        |

As you are getting started in creating your product backlog (or simply adding items to an existing backlog), you do not have to have items that 
are broken down into small enough chunks to be completed within a sprint. You will break down the large items and prioritize the new user stories 
during backlog refining/grooming, as described later in this section.
