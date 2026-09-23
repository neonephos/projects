# NeoNephos Foundation Project Lifecycle Policy

Version 2

## Policy Revision Process

Revisions to the NeoNephos Foundation Project Lifecycle Policy (the "Policy") can be initiated by any member of the Technical Advisory Council (TAC) or the Governing Board of the NeoNephos Foundation (the "Foundation"). Proposed changes should be documented and circulated among both the TAC and the Governing Board for review and discussion. To enact a revision, a simple majority vote of both the TAC and the Governing Board is required, ensuring collaborative oversight and consensus.

All updates to the policy are recorded and communicated to stakeholders to maintain transparency. This process allows the policy to remain adaptable and responsive to the evolving needs of the Foundation and its projects.

## Overview

This governance policy describes how an open-source project can formally join the NeoNephos Foundation via the Project Proposal Process. It describes the Stages a project may be admitted under, the criteria and expectations for each stage, and the Acceptance Criteria for progressing from one stage to another. It also describes the Annual Review Process through which those changes will be evaluated and made.

Project progression - the movement from one stage to another - allows projects to participate at the level that is most appropriate for them given where they are in their lifecycle. Regardless of stage, all NeoNephos Foundation projects benefit from closer alignment with existing projects, and from access to mentorship, support, and Foundation resources.

Capitalized terms not otherwise defined in this Project Lifecycle Policy have the meanings ascribed to them in the NeoNephos Foundation Directed Fund Charter. A "simple majority vote" is defined in this document as an affirmative vote of more than half of the votes cast. A "supermajority vote" is defined in this document as an affirmative vote of at least 2/3 of all active representatives eligible to vote.

## Roles and Groups

The following definitions apply to roles and groups referenced in this document. Additional details may be specified in the NeoNephos Foundation Directed Fund Charter.

* **Governing Board (GB)**: This board oversees the Foundation.
* **Technical Advisory Council (TAC)**: The Foundation's TAC includes TSC representatives from all Technical Projects and representatives of the Premier Members.
* **Technical Project**: Any project that is part of the NeoNephos Foundation.
* **TAC Project**: A Technical Project that has been granted voting privileges within the TAC.
* **Technical Steering Committee (TSC)**: Each project is managed by a TSC. The project defines how the TSC operates. A TSC appoints a project representative to the TAC who speaks on behalf of the project.
* **TAC Sponsor**: A TAC sponsor is a Premier Member or TAC Project that supports the application of a new project, champions the project within the TAC, and provides mentorship as needed.
* **Maintainer**: A maintainer is a person who has been granted commit access to the project repository and is responsible for managing contributions, releases, and other aspects of project maintenance. The project defines how maintainers are promoted and what their responsibilities are.
* **End Users**: End users are people, groups, or organizations that use the released artifacts of NeoNephos projects.
* **Organization**: An organization is a company, non-profit, or other entity that contributes to the project or sends maintainers on their behalf. Where boundaries between organizations are unclear, the TAC will determine what constitutes a distinct organization on a case-by-case basis.

## Technical Charter and Intellectual Property (IP) Transfer

All Technical Projects must have a complete Technical Charter that has been approved by the Linux Foundation Europe.

Technical Projects must also agree to transfer any relevant trademarks and assets (source code repository, social media accounts, domain names, etc.) to Linux Foundation Europe for the benefit of the NeoNephos Foundation, and to assist in filing for any relevant unregistered ones.

This is a requirement for all stages of the project lifecycle, including the Sandbox Stage.

## Project Proposal Process

### Introduction

This governance policy sets forth the proposal process for projects to be accepted into the NeoNephos Foundation. The process is the same for both existing projects that seek to move into the NeoNephos Foundation and new projects to be formed within the NeoNephos Foundation.

### Project Proposal Requirements

Projects must be formally proposed. Project proposals submitted to the NeoNephos Foundation should provide the following information to the best of their ability:

* Project name
* Project description (what it does, why it is valuable, origin and history)
* List of adopters, case studies, and testimonials (optional)
* Description of how contributors are promoted to committer status
* Statement on alignment with the NeoNephos Foundation mission
* Link to current Code of Conduct (if one is already adopted)
* Project licenses
* Source control repositories
* Issue tracker
* External dependencies (including licenses)
* Release methodology and mechanics
* Names of initial committers, if different from those submitting the proposal
* Brief description of the project’s leadership team and decision-making process
* Link to any documented governance practices
* List of the project's official communication channels (Zulip, Slack, Discord, Matrix, mailing lists, etc.)
* Link to the project’s website
* Links to social media accounts
* Existing financial sponsorship
* Infrastructure needs or requests

### Project Acceptance Process

* Projects must submit a formal Project Proposal as described on the NeoNephos Foundation website.
* Projects must find a TAC Sponsor to champion the project and provide mentorship as needed.
* Projects must provide a Technical Charter and approve and complete the transfer of any relevant trademarks and assets to the NeoNephos Foundation (see [Technical Charter and Intellectual Property (IP) Transfer](#technical-charter-and-intellectual-property-ip-transfer)).
* Projects must present their proposal at a TAC meeting.
* The TAC may ask for changes to bring the project into better alignment with the NeoNephos Foundation. The project must make these changes to progress further.
* The project must satisfy the requirements of its initial stage. The TAC will determine the appropriate initial stage; the project may apply for a different stage via the review process.
* Projects must be accepted per the Approval Process outlined for the initial stage of the project.

## Stages: Definitions and Expectations

Every NeoNephos Foundation project has an associated maturity level called a Stage.

The five stages are:

* **Sandbox**: Projects that are early-stage and experimental, with unproven direction, not intended for production use, and time-limited to one year.
* **Incubation**: Projects with a clear purpose and committed direction that are building toward maturity, but without a large or established community.
* **Growth**: Projects that are actively working toward the Graduated Stage with a defined growth plan, supported by multiple organizations and demonstrated adoption.
* **Graduated**: Projects that are mature and production-ready, with broad adoption and balanced governance.
* **Emeritus**: Projects that have reached or are nearing end-of-life, are no longer in active development, and are not recommended for new production use.

### Stage Progression

Projects are assigned to a stage and progress through stages based on two major factors:

* The size and diversity of the project community.
* The level of project adoption.

Projects can request a stage progression at any time, and the TAC will evaluate the request based on the criteria outlined in this policy. The TAC may also initiate a stage review for a project if it determines that a project’s current stage may no longer be appropriate.

When progressing to a new stage, a project must satisfy the acceptance criteria of that stage as well as all acceptance criteria of every prior stage.

When a new project joins or a project progresses to a new stage, the TAC will publicly document the rationale for the stage assignment or progression, including the evidence considered and how it was evaluated.

#### Project Community and TSC

Projects often begin small, led by a group from a single organization. As they mature, they are expected to cultivate a larger, stable, and more diverse community. The goal is to maintain balance among contributing organizations so that, over time, no single organization holds a majority of TSC seats. This helps ensure the project is not controlled by any one entity.

The TAC will assess the activity of a project’s community and maintainers, for example, during stage progression or as part of regular reviews. Because projects and communities vary widely and are in different lifecycle stages, these assessments are conducted on a case-by-case basis. Factors the TAC may consider include, but are not limited to:

* Release history
* The number and quality of commits
* The number of contributions and activities of maintainers
* Communication on mailing lists and other channels
* The number of issues opened and closed
* Response times to issues and pull requests
* Other indicators of community health and activity

#### Project Adoption

Adoption by other open-source projects, commercial products or entities, and end users can indicate a project’s success and impact. As such, it is a factor in determining the appropriate stage for a project and in justifying progression to a more mature stage.

Projects are encouraged to maintain a public `ADOPTERS.md` file in their repository that lists known adopters and to provide a straightforward, public process for adopters to add themselves or request removal (e.g., via a pull request or issue). This file should be easy to find from the project’s website or README. Projects may also provide a dedicated web page showcasing their adopters, case studies, and testimonials.

Measuring adoption can be challenging due to the nature of a project, the audience it serves, and the use cases it supports. Moreover, adoption does not always correlate with the depth or criticality of usage, and terminology around usage levels can be ambiguous. In some cases, adopters may not be able to disclose their use of a project.

Therefore, the TAC will assess, on a case-by-case basis, whether the evidence of adoption presented is adequate in quality and scope for each project and stage.

### Sandbox Stage

#### Definition

The Sandbox Stage is for projects whose value or direction has not yet been established. These are exploratory efforts, and the TAC believes they are worth pursuing, but the project has not yet demonstrated the intent or readiness to progress through the full lifecycle. Projects may enter the Sandbox Stage with no more than a high-level proof-of-concept or conceptual proposal. The Sandbox Stage is a time-limited space to experiment, validate, and build an initial community; it is not intended as a permanent stage.

##### Examples

* New projects that may only have a proof-of-concept.
* Experimental projects that are worthwhile to pursue in the eyes of the TAC.

##### Expectations

Projects should remain in the Sandbox Stage for no more than one year, unless the TAC grants an extension. Sandbox projects are experimental, and their outputs are not intended for production use. Projects that release production-ready artifacts should transition to a more mature stage. Projects that do not progress may be moved to the Emeritus Stage.

##### Acceptance Criteria

To be considered for the Sandbox Stage, the project must meet the following requirements:

* A Project Proposal must be submitted (see [Project Proposal Process](#project-proposal-process)).

##### Approval Process

Once the above Acceptance Criteria have been satisfied, the project must receive a simple majority vote of the TAC.

##### Benefits

Sandbox projects can prominently display on their website/README their status as a NeoNephos Foundation Sandbox Project. They can be mentioned on the NeoNephos Foundation website, publications, other promotional materials, and presentations to support building a community. Projects at the Sandbox Stage will receive support from the NeoNephos Foundation to facilitate the project’s progression toward the next stage.

### Incubation Stage

#### Definition

The Incubation Stage is for projects that have a clear purpose and a realistic path toward becoming a mature NeoNephos Foundation project. Unlike Sandbox Stage projects, Incubation projects are not experimental - they have committed to a direction and intend to progress toward the Growth or Graduated Stages. The Incubation Stage provides a neutral home to foster community development and deeper alignment with the Foundation while the project builds toward maturity.

##### Examples

* New projects that are designed to extend one or more NeoNephos Foundation projects with functionality or interoperability libraries.
* Independent projects that fit within the Foundation mission and offer a new approach to existing technical problem areas (or aim to address a previously unmet need).
* Projects commissioned or sanctioned by the NeoNephos Foundation.
* Any project that realistically intends to join the Growth or Graduated Stages in the future and wishes to establish the groundwork for that transition.

##### Expectations

End users should evaluate Incubation projects with care, as this stage does not set requirements for community size, governance, or production readiness. Projects that do not demonstrate progress toward a more mature stage may be moved to the Emeritus Stage.

##### Acceptance Criteria

To be considered for the Incubation Stage, the project must meet the following requirements:

* For new projects, a Project Proposal must be submitted (see [Project Proposal Process](#project-proposal-process)).
* Existing projects must request to be considered for the Incubation Stage.
* The project must have a code repository containing an initial implementation beyond proof-of-concept stage.
* Demonstrated adoption (see [Project Adoption](#project-adoption)) by at least one end user, commercial entity, or open-source project is encouraged but not required.

##### Approval Process

* The project must submit a request to the TAC for consideration to move to Incubation Stage.
* The TAC will consider this request in an upcoming TAC meeting after the TAC has had sufficient time to review the request. The TAC may request that the project present at an upcoming TAC meeting, outlining how the project has satisfied the Acceptance Criteria described above.
* The project must receive a simple majority vote of the TAC to move to Incubation Stage.

##### Benefits

Incubation projects can prominently display on their website/README their status as a NeoNephos Foundation Incubation Project. They can be mentioned on the NeoNephos Foundation website, publications, other promotional materials, and presentations to support building a community. Projects at the Incubation Stage will receive support from the NeoNephos Foundation to facilitate the project’s progression toward the Growth Stage.

### Growth Stage

#### Definition

The Growth Stage is for projects that are interested in reaching the Graduated Stage and have identified a growth plan for doing so. Growth Stage projects will receive mentorship from the TAC and are expected to actively develop their community of contributors, governance, and project documentation, and to meet the other criteria identified in the growth plan that contribute to broad success and adoption.

To support their active development, projects in the Growth Stage have a higher level of access to Foundation resources, which will be agreed upon and reviewed annually; the project's progress toward its growth plan goals will also be reviewed annually. The TAC may ask the project to move to the Incubation Stage if progress on the plan significantly slows or stops.

##### Examples

* Projects that are on their way to becoming, or are very likely to become, Graduated projects.
* Projects that have developed new growth targets or other community metrics for success.
* Projects that are looking to create a lifecycle plan (maintainer succession planning, contributor programs, version planning, etc.).
* Projects that need more active support from the Foundation or TAC mentorship to reach their goals.

##### Expectations

Projects in the Growth Stage are generally expected to move out of the Growth Stage within two years. Depending on their growth plans, projects may move between Incubation Stage, Growth Stage, and Graduated Stage as needed.

##### Acceptance Criteria

* For new projects, a Project Proposal must be submitted (see [Project Proposal Process](#project-proposal-process)).
* Existing projects must request to be considered for the Growth Stage.
* Demonstrated adoption (see [Project Adoption](#project-adoption)) by at least one end user, commercial entity, or open-source project, indicating the project is beyond the early stage.
* The project has at least three active maintainers from at least two different organizations.

##### Approval Process

* The project must submit a request to the TAC for consideration to move to Growth Stage.
* The TAC will consider this request in an upcoming TAC meeting after the TAC has had sufficient time to review the request. The TAC may request that the project present at an upcoming TAC meeting, outlining how the project has satisfied the Acceptance Criteria described above.
* The project must receive a simple majority vote of the TAC to move to Growth Stage.

##### Benefits

Projects at the Growth Stage will receive support from the NeoNephos Foundation to facilitate the project’s progression toward the Graduated Stage. They can be featured on the NeoNephos Foundation website, publications, other promotional materials, and presentations to support moving to the Graduated Stage.

### Graduated Stage

#### Definition

The Graduated Stage is for projects that have reached their growth goals and have entered a stable phase of ongoing development, maintenance, and long-term support. Graduated Stage projects are commonly used in enterprise production environments and have large, well-established project communities.

##### Examples

* Projects that have publicly documented release cycles, have a project-specific definition of Long-Term Support ("LTS"), and plan for executing the LTS strategy.
* Projects that have themselves become platforms for other projects.
* Projects that are able to attract a healthy number of committers on the basis of their production usefulness, not merely on the size of their developer community or public profile.
* Projects that have several high-profile or well-known end-user implementations.

##### Expectations

Graduated Stage projects are expected to actively participate in TAC proceedings, and as such have a binding vote on TAC matters requiring a formal vote, such as the election of a TAC representative. They receive ongoing financial and marketing support from the Foundation, and are expected to cross-promote the Foundation in the context of their project activities.

##### Acceptance Criteria

* For new projects, a Project Proposal must be submitted (see [Project Proposal Process](#project-proposal-process)).
* Existing projects must request to be considered for the Graduated Stage.
* Demonstrated adoption (see [Project Adoption](#project-adoption)) by multiple end users, commercial entities, or open-source projects, indicating the project has achieved significant traction.
* The project has at least six active maintainers from at least two different organizations.
* No single organization holds a majority of TSC seats.

##### Approval Process

* The project must submit a request to the TAC for consideration to move to Graduated Stage.
* The TAC will consider this request in an upcoming TAC meeting after the TAC has had sufficient time to review the request. The TAC may request that the project present at an upcoming TAC meeting, outlining how the project has satisfied the Acceptance Criteria described above.
* The project must receive a supermajority vote from the TAC and the Governing Board to move to the Graduated Stage.
* Projects may move directly from Incubation to Graduated, bypassing the Growth Stage, if they can demonstrate sufficient maturity and have met all Graduated Stage criteria.

##### Benefits

Projects at the Graduated Stage are considered "TAC Projects" as defined in the NeoNephos Foundation Directed Fund Charter, and receive all the rights and benefits therein, including the right to appoint a voting member to the TAC.

They are featured on the NeoNephos Foundation website, publications, other promotional materials, and presentations.

### Emeritus Stage

#### Definition

Emeritus projects are projects that the maintainers feel have reached or are nearing end-of-life. Emeritus projects have contributed to the ecosystem, but are not necessarily recommended for modern development, as more actively maintained alternatives may exist. The Foundation appreciates the contributions of these projects and their communities, and the role they have played in advancing the open-source ecosystem.

##### Examples

* Projects that are "complete" by the maintainers' standards.
* Projects that do not plan to release major versions in the future.

##### Expectations

Projects in this stage are not in active development. Their maintainers may infrequently monitor their repositories, and may only push updates to address security issues, if at all. Emeritus projects should clearly state their status and what any user or contributor should expect in terms of response or support. If there is an alternative project the maintainers recommend, it should be listed as well.

##### Acceptance Criteria

Projects may be granted Emeritus status via a supermajority vote from the TAC and with approval from the project TSC. In cases where the project has no TSC, only a supermajority vote from the TAC is required.

##### Benefits

For projects at the Emeritus Stage, the NeoNephos Foundation will continue to hold the IP and any trademarks and domains, but the project does not draw on Foundation resources.

## TAC Representation and Voting Rights

Representatives from all projects may attend TAC meetings and participate in TAC activities regardless of their stage.

As defined in the NeoNephos Foundation Directed Fund Charter, TAC Projects have voting rights on TAC matters. All Graduated Stage projects are TAC Projects. Projects in the Sandbox, Incubation, and Growth Stages do not have voting rights unless separately promoted to TAC Project status, but their representatives are encouraged to attend and participate in discussions.

## Annual Review Process

The TAC shall develop an Annual Review Process to determine whether projects are in the stage that accurately reflects their needs and goals.

Projects do not need to apply for or pass an annual review in order to remain in their current stage. Instead, the TAC will initiate a stage progression vote as needed, per the approval requirements listed for each Stage above.