---
permalink: /
layout: default-rules
---
View [RULES HISTORY](https://github.com/dashincubator/dash-incubator-app/commits/master/rules.md)

# Dash Incubator Rules V2.0

# Contents

1. [Dash Incubator](#1-dash-incubator)
2. [Bounties](#2-bounties)
3. [Contributing](#3-contributing)
4. [Admins](#4-admins)
5. [Funds](#5-funds)
6. [Resources](#6-resources)

# 1 Dash Incubator

[Dash Incubator](https://rules.dashincubator.app/) is an open-source, blockchain funded Application that redistributes Dash issued from Superblocks to users who complete [Bounties](#2-bounties) proposed by the Dash community.

Fund allocation and management is decentralized across [Admin](#4-admins) users who are incentivized with a % of the Dash they award on Bounties.

The Incubator is classified as an [open-source DFO](#14-full-transparency), meaning that all internal operations of the Incubator are conducted in the public domain at all times.  This includes how work is proposed, selected, specified, developed, tested, approved, which users are completing or managing work, what rewards they are allocating or receiving and all internal decision making.

All work produced by the Incubator, known as Output, including the Incubator app software itself is open-source and licensed under MIT License.

All handling and allocation of Incubator [funds](#5-funds) can be publicly verified down to user-task level via the Dash Blockchain itself in realtime. 

## 1.1 Mission

Our mission is to grow Dash's ease-of-use, utility and adoption, by finding, supporting and funding the most promising developers and entrepreneurs to build and grow Dash.

## 1.2 Dash Vision

Our vision for Dash is to become the number 1 Cryptocurrency for every-day payments in the world, by constantly innovating the fastest, easiest-to-use and most cost-effective trustless internet money at global scale.

## 1.3 Strategy

[Admins](#4-admins) will allocate funding in support of our [Dash Vision](#12-dash-vision) using the following priorities, in order of highest importance first.

1. Funding and kickstarting the development of dApps and user adoption of Dash Platform to grow Dash adoption
2. Prioritizing Social, Video, E-commerce, Retail, Identity Security, Payments, P2P commerce dApps
3. Funding development that improves onboarding for Platform users
4. Funding development that improves and sustains the Incubator itself
5. Enabling and promoting user growth and adoption of Dash as a mainstream fiat currency payments alternative
6. Funding Protocol development to support and implement the Incubator's Strategy when needed
7. Funding the development of tools and resources that aid developers, users and providers of Dash Platform
8. Funding promotion of Platform related features and dApps to developers and end-users
9. Funding the raising of Proposals to support and implement the Incubator’s Strategy
10. Kickstarting Incubator forks with synergistic Strategies to improve competition and decentralization within the DFO ecosystem

Work that is not aligned to these priorities, or would be done at the expense of higher priority work, will not be funded within the Incubator.

In some cases where activities are borderline in terms of alignment with the Incubator's strategy, Admins may choose to kickstart certain projects, which means initiating, but then looking to hand them off to 3rd parties to fund and monetize their longer-term development, including raising individual Proposals to accomplish that. 

## 1.4 Full-Transparency

To ensure that the Incubator's processes and information remain fully open-source and encourage the same standard for other DFOs in Dash, we introduce the following criteria for an **Open-Source DFO** classification that the Incubator implements:

1. All funding receipts and expenditure are tracked
2. All work systems and their data are public
3. All work preparation is public
4. All work output is public
5. All people and their work and rewards are public
6. All rules governing the Incubator and decisions made based on those rules are public

The only exception would be user credentials, i.e. their login passwords (which won't be needed when the Incubator App moves onto Dash Platform)

## 1.5 Users

There are several levels to classification of Incubator App users as follows:

- Users - anyone who accesses the Incubator App or it's underlying data
- Members - any user who has signed up to create an account on the App
- Contributors - members who have been awarded at least one [Task Claim](#25-claims)
- Admins - contributos with rights to create and manage Bounties, and earn commission from Task rewards
- PO - the Admin who is designated to raise Proposals to the Dash network on behalf of the Incubator 

> Currently all Users can be found as the members of our [Trello board](https://trello.com/b/FPJzDcok/dash-incubator-app)

## 1.6 Network Contract

This document contains the Rules that define the terms between [Dash Incubator](#1-dash-incubator) and the [Dash Network](https://docs.dash.org/en/stable/governance/understanding.html#) for how any funding awarded to the Incubator by the Network will be used.

When coupled with Incubator's [full transparency](#14-full-transparency) policy, anyone can trustlessly audit how well the Incubator is meeting the commitments of these terms in realtime, including verifying the use of all funding via the Dash blockchain itself down to a user/task level.

We refer to the transparent implementation of the terms defined in this document in return for the funding provided from Dash Network as the Network Contract.

The Incubator is required to abide by the Network Contract at all times, however, it is not required to abide by any contracts between 3rd parties to which the Incubator was not subject to the agreement or consideration of.

The authoritive source for the Rules are contained in a single document hosted on [Github](https://github.com/DashIncubator/dash-incubator-rules/blob/master/rules.md), with updates to the Rules (enacted as new commits) taking effect immediately.

## 1.7 Legal

The Incubator is an open-source application and not a legal entity and as such doesn’t own any assets, including any rights to any output, nor does the Incubator apply any restrictions on contributors usage of their own Task output, apart from the requirement that all output must be open-sourced under MIT license.

The only funding the Incubator App receives is in the form of Dash tokens issued directly from the Dash blockchain, which it redistributes to users who complete tasks defined and approved by Admins who agree to operate in accordance with the Rules defined in this document.

The Incubator does not handle, hold or pay fiat currency and all rewards are issued in Dash tokens as incentives for creating some open-source output, at the sole discretion of Incubator Admins, and without any agreement or action to purchase or procure any assets, intellectual property or labor.

# 2 Bounties

A Bounty in the Incubator means a collection of work that can be completed by contributors for a reward, such as development or promotion on Dash or improving the Incubator itself.

Bounties are first proposed as Concepts by the community, and there are four [types](#22-bounty-types) of bounty that can be created, each containing a series of [Tasks](#22-bounty-types) that are managed by the bounty's [Admin](#4-admins) who earns commission on all rewards the bounty creates.

## 2.1 Concepts

All Bounties start as a Concept that is [proposed](#31-proposing-concepts) to the Incubator by a community member.

Concepts are proposals for some work that the Incubator should fund as a Bounty, that provide enough detail about the value proposition and requirements of the work to be able to complete it.

Admins create a Bounty for each Concept they Accept that they then Own, meaning they have the rights to manage and earn commission from its delivery.

[Admins](#4-admins) can [Accept](#435-processing-task-claims) any Concept that meets our [Concept Acceptance Criteria](#411-concept-acceptance-criteria) on a first-come first-serve basis.

Once accepted, the user who created the Concept is automatically assigned as a [Stakeholder](#23-bounty-stakeholders) of the corresponding bounty.

## 2.2 Bounty Types

When a Bounty is created from a Concept by an Admin, they assign one of four types for the new Bounty that determine how work will be structured:

- **Projects** develop products such as a decentralized app built on Dash (DApps), tools for the community or improvements to the Dash Protocol itself.
- **Services** provide ongoing work that involves provision of some service, such as website hosting, code maintenance, or a recurring role within the Incubator.
- **Jobs** are one-off pieces of work, such as finding bugs or fixing a github issue.
- **Programmes** are collections of Project, Service or Job Bounties that coordinate large pieces of work

> All Bounties in the Incubator are represented by a Card on the [Trello Board](#https://trello.com/b/FPJzDcok/dash-incubator-app). The Bounty's type is represented by the column the Card is in on the Board.  Meta Bounties are shown with the pink label on the Card's front cover.

## 2.3 Bounty Stakeholders

For some bounties, Admins may wish to regularly solicit the views of subject area experts, Dash Core Group developers, or other key stakeholders as part of the decision making process when defining bounty tasks. 

Whilst bounty administration remains under the Admins of the bounty, a record of these Stakeholders, the nature of their interest, and the circumstances under which they should be consulted, may be added to the Bounty data.

> On Trello, the stakeholder usernames are added to the Card's description in a Stakeholders section by the primary or secondary Admin, including any additional information on the context for their involvement.

## 2.4 Tasks

A Task is the basic unit-of-work in the Incubator and represents a piece of work a Contributor can produce for a specified reward within a particular Bounty.

Tasks are defined by [Admins](#4-admins) and can completed by any user after [reserving](#33-reserving-tasks) the tasks with the Admin, or in the case of [Job](#22-bounty-types) tasks, completed without reservation.

Each Task must define some quantifiable Output (a document, commit, etc) that a user can produce to be eligible to [Claim](#25-claims) the specified reward.

There are three types of Task available within any Bounty:

- [Concept Tasks](#241-concept-tasks) - the initial creation of a Concept that results in the creation of a new Bounty
- [Specification Tasks](#242-specification-tasks) - work that provides the detail necessary to define Production Tasks
- [Production Tasks](#243-production-tasks) - work related to Tasks required to complete Project, Service and Job bounties
- [QA Tasks](#244-qa-tasks) - work that assures the quality of Production Tasks

> Each Task Type is represented as named Checklists on the Bounty’s Trello Card, except for Concept Tasks, which are implicitly created when a Concept is Accepted by an Admin.

### 2.4.1 Concept Tasks

A Concept Task is defined as the [submission of new Concept](#31-proposing-concepts) by an Incubator user.

The Reward for a Concept is considered to be approved as soon as the new Bounty is created once the Concept is approved.

Note that several Bounties can be created from a single Concept, however, the Concept reward is only paid the first time the Concept is accepted.

### 2.4.2 Specification Tasks

Specification Tasks define how [Production Tasks](#243-production-tasks) should be completed and QA'd.

The output is usually a document such as a Design Requirements doc, Functional Specification, or any resource that enables output relating to achieving the Value Proposition of the Bounty to be produced effectively.

Admins measure the quality of the Specification in terms of its fitness for purpose, adequate detail level to determine Production Tasks to implement it.

### 2.4.3 Production Tasks

Production Tasks are the actual output of a Bounty that deliver the value proposition. 

Usually Production Tasks output some code or a working product, but if the Bounty is for example a research project, the Production Tasks could output documents or analysis, or anything that satisfies the goals of the Bounty.

### 2.4.4 QA Tasks

Quality Assurance tasks validate and test that Production Tasks (Project, Service or Job) meet their [Specification](#242-specification-tasks).

Most tasks in Projects, Services and Jobs should require related QA tasks, which should be created at the time of the Work Task, so that there is a clear metric of what the Work task needs to achieve, and how the QA (and the Admin that approves the QA’s claim) can validate that.

QA Tasks must reference the relevant Spec or Production Task and produce some QA report output.

> It is recommended to use the [QA Report Template](https://docs.google.com/document/d/1FCIPJTGGNe-bmjEadO1QtJIvNI5L93Dgv0UeJ6lJzaM/edit) unless the admin requests an alternative format.

## 2.5 Claims

A Claim is the process of a user signalling that they have completed a [Task](#24-tasks) and wish to receive the Task's stated reward.

Users who complete Tasks can claim the specified reward from the [Admin](#4-admins) who owns the Task using the [Claims process](#34-claiming-tasks).

Once a Task Claim is approved by an Admin, the Task Reward should be awarded to the claimant to the Dash address they specified in the Claim within 7 days, to allow for manual validation and processing.

## 2.6 Rewards

Incubator is a pure-Dash fund meaning all rewards for approved Claims are awarded in Dash.

Each type of [Task](#24-tasks) offered by the Incubator has limits on the min/max rewards an Admin may [price](#433-pricing-tasks) on a Task as defined below.

The Admin % is an added commission that an Admin earns for Approving a Claim on a Task when it's Awarded, plus a [commission bonus](#441-commission-bonuses) based on the Admin's level of activity.

### 2.6.1 Price List

<table>
  <tr>
   <td><strong>Task Type</strong>
   </td>
   <td><strong>Approval Criteria</strong>
   </td>
   <td><strong>Amount</strong>
   </td>
   <td><strong>Admin %</strong>
   </td>
  </tr>
  <tr>
   <td>Concept Task
   </td>
   <td>Valid Specification
   </td>
   <td>0.5 Dash
   </td>
   <td>10% - 15%
   </td>
  </tr>
  <tr>
   <td>Specification Task
   </td>
   <td>Valid Specification
   </td>
   <td>0.1-5 Dash
   </td>
   <td>10% - 15%
   </td>
  </tr>
  <tr>
   <td>Production Task (Project, Service, Programme)
   </td>
   <td>QA Complete
   </td>
   <td>0.1-20 Dash
   </td>
   <td>10% - 15%
   </td>
  </tr>
  <tr>
   <td>Production Task (Job)
   </td>
   <td>Valid Job (to Spec or QA)
   </td>
   <td>0.1-10 Dash
   </td>
   <td>10% - 15%
   </td>
  </tr>
  <tr>
   <td>QA Task
   </td>
   <td>Valid QA Report
   </td>
   <td>0.1-5 Dash
   </td>
   <td>10% - 15%
   </td>
  </tr>
</table>

# 3 Contributing

Contributing to the Incubator involves completing [Tasks](#24-tasks) on [Bounties](#2-bounties) to earn [Rewards](#26-rewards).

A reward can also be earned by proposing a Concept for new Bounties that get accepted by an [Admin](#4-admins).

All work produced at the Incubator must be open-sourced under MIT license before any rewards can be paid, to satisfy the Incubator's [full-transparency](#14-full-transparency) requirements.

## 3.1 Proposing Concepts

Anyone can create a [Concept](#21-concepts) by signing up to the Incubator and submitting a [New Concept Template](https://trello.com/c/6XAuy9DW/94-request-new-concept).

Any [Admin](#4-admins) can [Accept](#435-processing-task-claims) a Concept that meets our [Concept Acceptance Criteria](#411-concept-acceptance-criteria), meaning they create a new [Bounty](#2-bounties) for it that they become the owner of.

The [Concept Reward](#261-price-list) is paid to the Dash address listed in the Concept if and when it is accepted by any of the Admins.

>- To propose a Concept, add a comment on the [New Concept Card](https://trello.com/c/6XAuy9DW/94-request-new-concept) on Trello.  
>- To chat with Admins about a Concept or its acceptance, join the [DashDevs Discord](https://discord.gg/mU79ZWx) and ask on the #dash-incubator channel.

## 3.2 Completing Job Tasks

Job Tasks on Bounties are open to be claimed by anyone without needing to reserve the task.

To claim a reward on a Job task, use the [Claims process](#34-claiming-tasks)

## 3.3 Reserving Tasks

Any tasks other than Jobs can be reserved.  This means that you can agree with the Task's Admin to have exclusive rights to claim the Task until the due date.  

To reserve a task, leave a comment for the Admin of the Bounty that Task is part of, so that they can assign the task to you, and/or discuss the Task details and negotiate the reward.

Once you have completed the Task, use the [Claims process](#34-claiming-tasks) to claim the reward.

If a claim isn't made by the due date, the Admin can extend the date, or has the option to reserve the Task to someone else.

> To be able to Reserve a Task please join as a Member of our Trello Board by leaving a comment on our [Member Signup Card](https://trello.com/c/VlpK4dgl/95-member-signup).

## 3.4 Claiming Tasks

Once you have completed the work for a Task you can make a [Claim](#25-claims) for the reward on the Task, by providing the following information:

1. Link to the source for the tasks output (specific PR or commit for Github code)
2. Link to any deploy links relevant to the output (e.g. a URL for a website)
3. Specify a valid Dash address to receive the reward, or set to [NULL](#341-null-claims) to decline the reward.

Once your Claim has been created it will [processed](#435-processing-task-claims) by an admin.

> To create a Claim on Trello, leave a comment on the Bounty's [Trello Card](https://trello.com/b/FPJzDcok/dash-incubator-app) specifying the number and type of the Task you are claiming, along with the source links and your Dash address

### 3.4.1 Null Claims

In some cases, users wish to decline rewards for some reason.

This is strongly discourage as incentives are how Incubator maintains a high level of creativity, productivity, and quality of output, and Claims themselves are how we track and account for work completion in the App.

However, to support the requirement, we introduced the option to create a Null Claim.

Therefore users who wish to decline rewards still need to make Claim to signify and enable tracking of a Task's completion, but they can set the claim's Dash address to 'NULL' to signify that the actual reward is declined and therefore won't be awarded.

> To create a Null Claim in Trello, simply enter the term 'NULL' in place of a Dash address on the relevant [Claim comment](#42-claiming-tasks).

# 4 Admins

Admins are a second-tier of users in the Incubator who are incentivized to manage Bounties by earning a [commission](#26-rewards) on all Tasks completed within the Bounty.

As all work (and spending) is structured as a Bounty within the Incubator, and Bounties can relate to working on the Incubator itself and be both managed and produced by Admins, they represent a decentralized layer of users who manage every aspect of the Incubator.

Admins are peers, each with control of their own share of the Incubator's funds that they can use to create and manage bounties that incentivize Contributors to produce output for the Incubator.

Admins have additional rights to appoint other Admins and to maintain the Rules defined in this document, which define all aspects of how the Incubator should operate, which they are each responsible for implementing correctly.

> On Trello, the board is configured to only allow Admins to create and edit cards, including defining and assigning tasks to Board members. Any user can comment on cards to interact with Admins about the bounties they're managing.

## 4.1 Accepting Concepts

Bounties are created via the Acceptance of a user-submitted [Concept](#31-concepts) by an Admin.

 - A Bounty is only created from a Concept approval, and always refers back to a single Concept
 - Any Admin can Accept a new Concept but must validate that it meets our [Concept Acceptance Criteria](#411-concept-acceptance-criteria)
 - Admins do not need permission from or consensus between other Admins to accept a Concept
 - Admins can submit new Concepts themselves, but need another Admin to Accept them.
 - Once a Concept is Approved, an implicit Claim for the Concept Task reward is considered to be approved automatically

> - In Trello, Admins formally Accept by manually creating the Bounty card and replying to the user's comment on the [New Concept Card](https://trello.com/c/6XAuy9DW/94-request-new-concept) to inform them and link the new Bounty card.
> - The Admin should also add an entry to the Awarded Claims sheet, using the user's details and Dash address from the Concept they submitted

### 4.1.1 Concept Acceptance Criteria

Admins must judge Concepts they wish to Accept against the following criteria:

 - Involve work that's in-scope to our [Strategy](#13-strategy)
 - Provide value that supports our [Dash Vision](#12-dash-vision)
 - Be primarily related to Dash Platform, or involve work that supports Dash Platform
 - Provide a clear Value Proposition that is likely to add value to Dash
 - Provide enough detail on requirements to achieve the state goals
 - Be technically feasible using the current Dash Protocol or some unreleased but known iteration of it
 - Be unique within the existing set of Concepts & Bounties already added to the Incubator, i.e. not a duplicate or very similar scope to an existing active Bounty
 - Involve costs likely to be not more than 10% of Incubator's monthly funding allocations

## 4.2 Bounty Management

### 4.2.1 Creating Bounties

Bounties are created exclusively by Admins who [Accept](#435-processing-task-claims) a community-submitted Concept and consequently become the [Owner](#422-bounty-ownership) of the Bounty.

Admins must ensure the following information is correct on new Bounties they create:

1. Set themselves as the Owner of the card
2. Set the correct Bounty type field (either Project, Specification, Job or Programme)
3. Link the Concept the Bounty was created from, in the Concept Doc field
4. Set the Description text to the Value Proposition section defined in the Concept.
5. Optionally appoint a Secondary Admin for the Bounty

> In Trello, Bounty ownership is designated by assigning the Admin user as the Member of the card on the top left below the card title.  When two Admins are assigned to the card, the secondary Admin is designated by putting their Trello username into the Secondary Admin field on the card.

### 4.2.2 Bounty Ownership

The Admin who created a Bounty is given the rights as the Owner of that Bounty, also known as the Primary Admin of the Bounty.

The Bounty Owner has exclusive rights to edit the Bounty's fields, define Tasks and process resulting Claims, and change the Bounty's Status.

The Bounty Owner may transfer ownership to another Admin at any time.

> In Trello, Ownership is determined by the Admin who is a Member of the Card and who's username isn't specified in the Secondary Admin field.  

### 4.2.3 Secondary Admins

The Bounty Owner can optionally appoint a Secondary Admin to the Bounty, enabling a maximum of two Admins to manage a bounty at one time.

Secondaries cannot edit the Bounty's details but can create their own set of Tasks within the Bounty independently from the Bounty Owner's Tasks, and process Claims on those and receive their Admin Reward.

The Bounty's Owner Admin can transfer the Secondary alot to a different Admin at any time, or remove the Secondary altogether without their agreement, however, the removed Secondary will still retain control of any Tasks they owned on the Bounty.  

Secondaries can leave a Bounty or transfer the secondary position to another Admin who agrees at any time.

> In Trello, Bounty Owners can appoint Secondaries on a Card by entering their name in the Secondary Admin field and assigning them as a Member of the Card. 

### 4.2.4 Forking Bounties

Apart from creating a new Bounty from a Concept, Admins have another option to fork a Bounty, by creating a new Bounty that shares the original Concept but modifies the outcome in some significant way, known as a Concept Fork.

> In Trello, a fork can be created from a Bounty's Card by just making a new Card and linking the Concept that both Card's share in the Concept Doc custom field of the card.  

## 4.3 Task Management

### 4.3.1 Creating Tasks

Admins can create [Tasks](#24-tasks) on any Bounty that they're the current Owner or Secondary Admin of.

When creating the Task, the Admin sets the Description, which must provide enough info to allow someone to complete the work, either in the description itself or by linking a Specification.

The due-date is the date whereby if a Claim is not made for the Task, the Admin has the option to cancel the task or reassign the user at the Admin's discretion.

> When defining a Task in Trello, the Admin will chose the correct Checklist for the task type, and specify the following information:
>1. A Task Number, which is the sequential number of the Task in the relevant Checklist
>2. A Description, summarising the broad requirements by  a short definition is needed.
>3. An amount of Dash for the Reward.  This can be negotiated between the Admin and prospective users
>4. The name of the Admin who created the Task, known as the Task Owner
>5. When reserving a Task for a user, specify the due-date and assign the Trello user as the member on the Task
>
> This information should be in the Task description in the format:
>
>```[taskId]) [taskDescription](AdminUsername)([amount] DASH)```

### 4.3.2 Task Ownership

When either the Primary or Secondary Admin defines a [Task](#24-tasks) they become the Owner of that Task.

A Task owner has exclusive rights to:

- Edit or complete the Task 
- Process Claims on those Tasks and therefore receive the Admin reward on any awarded Claims.  
- Transfer Ownership of the Task to another Admin
- Optionally, the Admin can set Task ownership to 'Open', meaning the other Admin on the bounty is free to process the Claim and receive the commission reward

If an Admin leaves a Bounty, for example via Owner transfer or removal of a secondary, the leaving Admin retains ownership of their own Tasks after they left, until they are completed or they decide to transfer their ownership to another Admin.

If a Task has an unprocessed Claim for more than 5 days with no response to the user from the Admin, the other Admin on the Bounty can take ownership of the Task to process the Claim and receive the commission reward.

> On Trello, Admin ownership is designated by the name of the Admin user in the Task description.
> Secondly, any Task without an Admin username in the description is considered to be 'open', meaning the other Admin on the card can process it and receive the reward.

### 4.3.3 Pricing Tasks

Pricing on a Task is decided by the Admin who owns the Task.

Tasks should be priced on what is the minimum reward level needed to incentivize a contributor to deliver it, which factors in who is available to do the work, any unique skills / quality considerations, and not a factor of how long the Task will take or how much it would cost outside of the Incubator.

Fiat values should be taken into consideration, but Tasks shouldn't be repriced if the fiat value changes radically, unless not doing so would prevent completion of the Task.

If fiat values of Dash change significantly, this should be reflected when pricing new tasks, or repricing Job Tasks (which aren't reserved for users).

### 4.3.4 Reserving Tasks

Except for [Job](#22-bounty-types) Bounty types, Admins must assign Tasks to a specific user for the Task to be considered Active.

Admins can arrange reservations and negotiate the Task's terms with the user within the comments or via private communication, but once the Task is reserved to the user, the terms are considered agreed and are public information.

> On Trello, Tasks are represented by Checklists on the Bounty's Card, and are reserved by setting the Member setting to the user who reserved the Task and setting a date in the Due Date field.

### 4.3.5 Processing Task Claims

When a user completes a Task, they create a [Claim](#25-claims) that the [Task Owner](#432-task-ownership) Admin needs to process to decide if the Claim can be Approved, if QA is needed, or if there are issues that need to be resolved.

Approved Claims on Tasks go into the [Awarded Claims List](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0) from which the reward will be sent to the claimant.

If a Contributor wants to dispute a Claim decision, they can ask for a second opinion, in which case the other Admin on the Bounty, or any other Admin if the Bounty only has one Admin, can provide a second assessment.

Ultimately, decisions on whether some output meets the requirements specified in the Task definition are the sole discretion of the Admin who owns the Task.

> In Trello, Admins can Approve a Claim by ticking the Task's Checkbox and leaving a comment on the Bounty card as follows:
>
>```Claim Approved: [@username][checklistName]([taskIds])([amount] Dash)```
>
>For example:
>
>```Claim Approved: @somedev Production Tasks (1,2) (1 Dash)```
>
>Admins must then enter the details into the [Awarded Claims List](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0), filling in all columns and double checking the user’s payment address and reward amount, to enable the claim to be awarded.

## 4.4 Admin Rewards

Admins are incentivized via a baseline reward as a % commission on all Claims that they award on Bounty Tasks that they own, using the rates defined in the [Price List](#26-rewards), plus additional [commision bonuses](#441-commission-bonuses) for the most active Admins.

Admins can earn additional rewards by completing Bounty Tasks themselves, provided they are defined and approved by another Admin, in other words, Admin's can't set and price their own work, but they can set and manage work for each other if needed.

Admin rewards for commission on tasks don't require formal claims, they are issued automatically to a Bounty Admin when the associated Tasks are awarded via the [Awarded Claims List](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0).

Note that Admins can also opt to decline rewards by creating a [Null Claim](#341-null-claims) on their commision within a Task Claim.

> To set a Null Claim on their Commission Reward, an Admin should enter their Dash address as 'NULL' in the Claim in the [Awarded Claims List](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0)

### 4.4.1 Commission Bonuses

Each individual Admin's commission is variable based on the number of [Task Claims](#25-claims) they Approved in the previous 30 days (including "today"). There are 3 Tiers of commissions an Admin can earn: 10%, 12%, 15%

<table>
  <tr>
   <td><strong># of Claims Approved</strong>
   </td>
   <td><strong>Commission Rate</strong>
   </td>
  </tr>
  <tr>
    <td>0 - 14
    </td>
    <td>10%
    </td>
  </tr>
  <tr>
    <td>15 - 29
    </td>
    <td>12%
    </td>
  </tr>
  <tr>
    <td>30 +
    </td>
    <td>15%
    </td>
  </tr>
</table>  

Each Commission Bonus is based on the Tier that the Admin’s previous 30 days contributions fall into. The "next" tier of commission is effective immediately once an Admin crosses the threshold, and is effective for all claims as long as the Admin stays within the Tier.

For example:

- Admin Alice has processed 10 claims in the past 30 days (including today). If Alice processes 5 additional claims today, Alice will be eligible for a 12% commission on the 5th claim (and any additional claims).
- Admin Bob has processed 34 claims in the past 30 days, but 7 of those were processed exactly 30 days ago. If Bob processes claims today, each of those will earn 15%. If Bob does not process at least 2 claims today, his commission rate will be 12% for claims processed tomorrow until his 30 day count is 30 or more again, at which point Bob will return to a 15% commission.
- Admin Carol has processed 9 claims in the past 30 days. Today Carol processes 21 claims. For the first 5 claims Carol processes today the commission is 10%. For the next 15 (claims 15 - 29) the commissions is 12%. The final claim Carol processes has a 15% commission.

## 4.5 Governance

Admins are responsible for Governance of the Incubator which is implemented via appointing or removing Admins, or updating these Rules.

An Admin Quorum is required in both cases, which means that >= 51% agree (or <=49% don't object>) to Admin appointments / removals or changes to the Rules.

# 5 Funds

## 5.1 Proposals

The App is funded from a series of [Proposals](https://docs.dash.org/en/stable/governance/understanding.html) submitted to the Dash Network on a quarterly basis, with all spending of those funds commissioned and tracked by Admins within the Bounty System itself and settled via transactions on the Dash blockchain that anyone can verify.

The amount requested might vary based on the general scale and reserves the Admins feel the Incubator should target but not to deliver specific projects or milestones as there is no centralized planning to do so in the Incubator.

When certain projects arise that require additional funding, individual proposals may be raised for those.

## 5.2 Budgets

All funds will be received to the published [Incubator Wallet](#63-accounting) address(s) and will be pooled across proposals as a single rolling-budget available to Admins to allocate to Bounties.

The funds the PO requests from the Dash Network are purely to top-up the Incubator Wallet and increase the overall budget available to Admins to spend.

Incubator is a pure-Dash fund meaning that rewards are denominated only in Dash.  Therefore any fluctuations in the fiat price of Dash will only reflect the pricing of new [Tasks](#24-tasks) by Admins and prior agreements made in Dash are not renegotiated or adjusted.

## 5.3 Proposal Owner

The Proposal Owner (PO) is the Admin who creates [Proposals](#64-proposals) to the Dash Network for and on behalf of the Incubator, and handles (but isn't liable for) custody and transactions of the Dash received on behalf of Admins.

The PO agrees to use funds solely for the purposes of awarding [Task Claims](#25-claims) from users that were approved by Admins inline with the Rules in this document.

The PO role is intended to be a temporary role, until the Incubator can be implemented as a fully decentralized Dapp in future, with Proposal Dash awarded to a Contract on Dash Platform and distributed autonomously using code.

Before the full Dapp implementation, and before fully decentralized mechanisms are innovated to ensure that all users are adhering to these Rules and operations of the App are as efficient as possible, the PO is currently granted some additional rights equivalent to a 'super-user' within the App as follows:

 - Appoint or transfer Primary or Secondary Admin positions on a Bounty
 - Pause/Unpause a Bounty or some of the Tasks
 - Appoint or remove Admins from the Incubator
 - Create Tasks on bounties when Primary/Secondary aren't available
 - Mediate updates to these Rules
 - Any other actions to enforce adherence to these rules

 If the Proposal Owner needs to exercise any of these rights, they must leave a comment (e.g. on Trello or Github depending on the action) detailing the action and explaining the reasons as to why an action was taken.

The Proposal Owner can be replaced through a vote where at least 51% of Admins vote for a new Admin to be the PO.  If that occurs, the newly elected PO will assume all PO responsibilities and the existing PO will transfer all funds from the Proposal Wallet to a wallet controlled by the new PO.

> The Proposal Owner role is incentivized by a [Service Bounty](https://trello.com/c/pjOIKxyc/100-dash-incubator-proposal-owner) defined within the Incubator app itself.

## 5.4 Auditing

As an [Open-source DFO](#14-full-transparency), anyone can perform a full public audit of the Incubator at any time, to check that all work is being conducted as per these Rules, and verify the rewards issued to individual Incubator users for that work via the Dash blockchain.

Below we provide guidelines on how to audit the Incubator from a financial and work perspective, but people can devise their own audit strategies as they deem fit.

### 5.4.1 Auditing Accounts

Every Dash of funding spent by the Incubator must be accounted for via a [Task Claim](#25-claims) approved by an [Admin](#4-admins) with an associated transaction on the Dash blockchain.

Therefore we can verify that the total funds spent listed on the [Dash Blockchain](https://insight.dash.org/insight/address/XbFb9b1qaoLykngDbUwBVBFwSHuwQRhSqc) tally to total task claims awarded in the [Awarded Claims List](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0) to ensure that funds aren't being spent from the wallet arbitrarily.

 - Total funds spent via the Blockchain is equal to the total Dash sent minus the total Dash received from the [Incubator Wallet](#63-accounting).
 - Total funds spent on awarded Task Claims is equal to the total Dash spent in columns H (Reward) and N (Admin reward) in the [Awarded Claims List](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0).

Note that each Task lists the transaction id, which can also be parsed individually to verify the total amount.

### 5.4.2 Auditing Work

All work must be conducted inline with the Rules in this document and in the public domain.  Therefore anyone can audit the rules and how well the work being conducted in the Incubator is adhering to these rules at any time.

As a guideline, the following aspects of work are key areas to ensure the Rules are being implemented effectively.

 - Admins are pricing work fairly
 - Admins are interpreting the rules effectively
 - Concepts being approved are inline with the [Strategy](#13-strategy)
 - Quality of output is sufficient for rewards
 - Task deadlines and due dates are being managed effectively

# 6 Resources

Below are links to all resources needed to access, fork or audit every aspect of the Incubator App, to satisfy our [full transparency](#14-full-transparency) requirements.

## 6.1 App

<table>
  <tr>
   <td><strong>Resource</strong>
   </td>
   <td><strong>Link</strong>
   </td>
  </tr>
  <tr>
   <td>Website
   </td>
   <td><a href="https://dashinc.app">dashincubator.app</a>
   </td>
  </tr>
  <tr>
   <td>Website Source
   </td>
   <td><a href="https://github.com/DashIncubator/dash-incubator-app">github.com/DashIncubator/dash-incubator-app</a>
   </td>
  </tr>
  <tr>
   <td>Rules Source
   </td>
   <td><a href="https://github.com/DashIncubator/dash-incubator-rules/blob/master/rules.md">github.com/DashIncubator/dash-incubator-rules</a>
   </td>
  </tr>
  <tr>
   <td>Discussion:<a href="https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit?usp=sharing"> </a>
   </td>
   <td><a href="https://discord.gg/mU79ZWx">DashDevs Discord</a>
   </td>
  </tr>
</table>

## 6.2 Data

<table>
  <tr>
   <td><strong>Resource</strong>
   </td>
   <td><strong>Link</strong>
   </td>
  </tr>
  <tr>
   <td>Backend (Trello)
   </td>
   <td><a href="https://trello.com/b/FPJzDcok/dash-incubator-app">Dash Incubator App</a>
   </td>
  </tr>
</table>

## 6.3 Accounting

<table>
  <tr>
   <td><strong>Resource</strong>
   </td>
   <td><strong>Link</strong>
   </td>
  </tr>
  <tr>
   <td>Wallet
   </td>
   <td><a href="https://insight.dash.org/insight/address/XbFb9b1qaoLykngDbUwBVBFwSHuwQRhSqc">XbFb9b1qaoLykngDbUwBVBFwSHuwQRhSqc</a>
   </td>
  </tr>
  <tr>
   <td>Accounts<a href="https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit?usp=sharing"> </a>
   </td>
   <td><a href="https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit?usp=sharing">Awarded Claims Spreadsheet</a>
   </td>
  </tr>
</table>

## 6.4 Proposals
<table>
  <tr>
   <td><strong>Resource</strong>
   </td>
   <td><strong>Link</strong>
   </td>
  </tr>
   <tr>
   <td>Phase 1
   </td>
   <td><a href="https://www.dashcentral.org/p/dash-platform-incubator"> dash-platform-incubator</a>
   </td>
  </tr>
  <tr>
   <td>Phase 2
   </td>
   <td><a href="https://www.dashcentral.org/p/dash-platform-incubator-phase-2"> dash-platform-incubator-phase-2</a>
   </td>
  </tr>
  <tr>
   <td>Phase 3
   </td>
   <td><a href="https://www.dashcentral.org/p/dash-platform-incubator-phase-3">dash-platform-incubator-phase-3</a>
   </td>
  </tr>
  <tr>
   <td>Phase 4
   </td>
   <td><a href="https://www.dashcentral.org/p/dash-platform-incubator-phase-4">dash-platform-incubator-phase-4</a>
   </td>
  </tr>
  <tr>
   <td>2021 Q1
   </td>
   <td><a href="https://www.dashcentral.org/p/dash-incubator-2021-q1">dash-incubator-2021-q1</a> 
   </td>
  </tr>
</table>
