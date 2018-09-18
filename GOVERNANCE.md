# Governance

## Glossary

* **Advisory Committee.**  A group of people with representation from a variety of AMP's constituencies including Users, End-users and Collaborators who provide advice to the Technical Steering Committee.

* **Collaborators.**  People who have been granted write-access to ampproject repositories.

* **Contributors**.  People who have opened a pull request or an issue, or commented on an issue. Contributors are granted certain permissions on the repositories to make it easier to participate--e.g. assigning issues, attaching labels to issues, etc.

* **Users.** Developers who use AMP but haven’t contributed to it (yet).

* **End-users**. People who consume content distributed using the AMP format.

* **Owners**.  People who are most familiar with a particular set of code and who have been granted the power (by Owners at a higher level) for approving changes to that code.  AMP will use a system similar to [Chromium's OWNERS](https://chromium.googlesource.com/chromium/src/+/master/docs/code_reviews.md#OWNERS-files) system.  The AMP Project will follow Chromium's [expectation for owners](https://chromium.googlesource.com/chromium/src/+/master/docs/code_reviews.md#expectations-of-owners).

* **Technical Steering Committee (TSC).**  A group of people who set AMP's technical & product direction.

* **Working Group Facilitator.**  A member of the Working Group designated by the TSC who is responsible for facilitating the consensus-based decision making process and acting as a representative to the TSC from the Working Group.

* **Working Groups (WG)**.  A group of people who have a familiarity and interest in a given area; may be cross-cutting (e.g. "Documentation") or focused on a given area (e.g. "Ads & Analytics" or "Runtime").  These are formally recognized by the TSC, but may form informally.

## Governance Structures

### Advisory Committee (AC)

#### Role

The Advisory Committee provides perspective and advice to the Technical Steering Committee.

#### Membership
* Membership on the Advisory Committee shall include representatives from major AMP constituencies (Collaborators, Contributors, Users and End-Users) who are committed to fulfilling AMP's vision and mission.
* Membership on the Advisory Committee is not time limited.
* The target size of the Advisory Committee is 6-12 members, but there is no fixed size.
* Once established the Advisory Committee sets its own membership through the consensus-based process.
* No more than ⅓ of the Advisory Committee should be from one employer.
* The Advisory Committee will designate a Facilitator from among its members for the purposes of facilitating the consensus-based decision-making process.

### Technical Steering Committee (TSC)

#### Role

* The TSC's primary role is setting AMP's technical & product direction based on the [project guidelines](https://www.ampproject.org/about/amp-design-principles/).
* Creates a product roadmap in consultation with the Working Groups.
* Creates Working Groups and sets the initial membership & Facilitator of the Working Groups.  The TSC may initiate the creation of Working Groups or a group of people with a common interest may request recognition as a Working Group.
* Approves new Collaborators.
* Sets and maintains the project guidelines.
* Sets and maintains the project’s feature and bug fix process.
* Enforces the Code of Conduct.
* The TSC may designate entities to perform legal, security and privacy reviews of AMP code/features.
* Decisions within the TSC follow the decision-making policy, and are facilitated by the Facilitator or their designate.

#### Membership

* The TSC shall be composed of members with significant experience contributing to AMP on a technical and product level.
* Membership on the TSC is not time-limited.
* The target size of the TSC is 6-12 members, but there is no fixed size.
* Once established the TSC sets its own membership through the consensus-based process.
* The TSC shall have a goal of having no more than ⅓ of the TSC from one employer.  Given the requirement that membership in the TSC requires recognized technical and/or product experience with AMP this may not be feasible at the time the TSC is formed, but the TSC should actively work towards this goal.
* Entities (such as a company) may be granted seats on the TSC.  In these cases certain conditions may be placed on the seat (such as maintaining committed resources to the project). The entity may designate the individual representing the entity at the TSC and may change this individual at their discretion.
* The TSC will designate a Facilitator from among its members for the purposes of facilitating the consensus-based decision-making process.

### Working Groups

#### Role
* A Working Group is a segment of the community with knowledge/interest in specific areas of AMP (e.g. UI, Runtime, Infrastructure, documentation) recognized by the TSC.
* The TSC defines each Working Group's mandate, which may include responsibility for certain AMP features, systems and/or code.  A Working Group generally operates independently on the area(s) in which it has a mandate while adhering to AMP's project guidelines, vision/mission and technical/product roadmaps.
* Each Working Group is made up of a set of Collaborators with knowledge/interest in that particular area + other interested parties.
* Each Working Group may have a Facilitator as designated by the Technical Steering Committee.  The Facilitator is responsible for:
  * Facilitating consensus-based decisions within the Working Group.
  * Representing the Working Group to the TSC.
  * Choosing designate(s) from within the Working Group for these responsibilities as needed.
* Decisions within Working Groups follow the decision-making policy, and are facilitated by the Facilitator or their designate.

#### Membership
* The TSC creates Working Groups and assigns initial members.  Membership should include some Committers but may include other interested parties.
* A Working Group may add or remove members by using the consensus-based approach.
* It is acceptable & expected that groups of people with a common interest will work together without requiring a formal Working Group.  These groups may choose to be officially recognized as a Working Group by making a proposal (including its purpose and proposed membership) to the TSC.
* The TSC may disband/reorganize Working Groups as needed.


## Community Roles

* Owners
  * Have write access to ampproject repositories and may approve PRs for areas in which they are OWNERs.
  * Are expected to regularly participate in code reviews and design review discussions (offline and in the weekly design reviews).
  * Requirements to be an Owner:
    * Demonstrated familiarity of AMP's code base and design philosophy.
    * Demonstrated deep expertise of their particular area of ownership.
    * The AMP Project will follow Chromium's [expectation for owners](https://chromium.googlesource.com/chromium/src/+/master/docs/code_reviews.md#expectations-of-owners).
    * Owners of an area may approve other owners at or below their area of expertise following the normal PR process.

* Collaborators
    * Have write access to ampproject repositories and may merge approved PRs.
    * Assign issues/PRs and add labels.  (If GitHub allowed we'd allow any member of the AMP Project to perform these actions.
    * Requirements to be a Collaborator:
      * Demonstrated familiarity of AMP's code base and design philosophy.  This can be shown through the submission of significant PRs, the performance of thorough code reviews and the participation in design discussions over time.
      * The TSC approves new Collaborators and may remove Collaborators (e.g. if they become inactive or are no longer performing their responsibilities).

* Contributors
  * Create issues (bug reports, Intent-to-implements, etc.)
  * Join/participate in discussions on Slack, forums, design reviews, etc.
  * Contributors are granted permissions to facilitate community involvement, including the ability to be assigned issues.


## Decision making policy

* Decisions in AMP's Advisory Committee, TSC and Working Groups should be made using a [consensus-based approach](https://en.wikipedia.org/wiki/Consensus-seeking_decision-making) (similar to the [approach used by Node.js](https://nodejs.org/en/about/governance/#consensus-seeking-process) and [JS Foundation](https://github.com/JSFoundation/TAC/blob/master/TAC-Charter.md#section-8-decision-making)).
  * When discussions have appeared to reach a consensus, the Facilitator will ask if there are any objections to the apparent consensus.  A member may call for a closing or tabling vote, but this should only happen as a last resort.  With the agreement of two other members of the group the vote will be held, otherwise the consensus-seeking process will continue.
  * When votes are called:
    * The vote should be set at a time that allows a reasonable amount of time for those in the group to attend.  This time should be announced publicly.
    * Anyone who is unable to attend at the time of the vote can register their vote early.
    * They will be simple majority votes except for changes to Advisory Committee or TSC membership which requires a ⅔ vote.
  * For decisions made within a Working Group every effort should be made to resolve issues within the Working Group itself; issues that cannot be resolved within the Working Group may be escalated to the TSC.

* Decisions made by the Advisory Committee, TSC and Working Groups must be publicly documented (unless they cannot be for legal or security reasons).

* Decisions should be made through asynchronous communication channels. In the case where they are not—such as over video conference or during face to face meetings—a reasonable period of time should be allowed for objections to be made before the decision is ratified.

* A decision may be revisited if new technical information becomes available.

* The Advisory Committee, TSC and Working Groups may hold calls, video conferences, and face to face meetings. These meetings shall be announced sufficiently in advance with a published agenda. A mechanism by which the community can propose items for the agenda shall be provided.
