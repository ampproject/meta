# Working Group best practices

This document describes best practices for the operation of AMP Working Groups.  Working Groups may deviate from these best practices in reasonable ways that work best for the Working Group as long as those changes align with [AMP’s governance policy](../GOVERNANCE.md).

## GitHub repository.
Create an ampproject/wg-{name} GitHub repository (e.g. “ampproject/wg-ui-and-a11y”).
  * Link to this repo from the [ampproject/meta/working-groups/README.md](README.md) file.
  * Use this repo to keep for documentation about the working group, meeting agendas, etc.  **This repo should not contain code.**
  * This repository should contain a README.md with enough information to make it possible to keep track of all work that is happening within the WG and all of the decisions that require the attention of WG members.  This should include:
    * the WG’s mandate from the TSC (e.g. which repositories and parts of the codebase the WG is responsible for)
    * a list of members
    * how the working group operates, including discussion channels, how decisions are made, and how issue labels/GitHub projects are used.

## Slack channel
Create a Slack channel with the same name as the repo (e.g. #wg-ui).  Use this for communication within the WG that doesn’t fit in GitHub issues/PRs.

## Discussions & decisions
  * Adhere to AMP’s [consensus-based decision-making policy](../GOVERNANCE.md#decision-making-policy).
  * Discussions should be held in a public forum and generally allow for asynchronous communication.  GitHub issues/pull requests and Slack work well for this.
  * Determine and document which types of decisions require proactive approval from the WG.  For most WGs, most work should be able to proceed without requiring an affirmative approval of the WG (e.g. code reviews and smaller feature changes) unless specifically requested by someone in the WG.
  * Document how members and non-members of the WG may request that an item be brought to the WG for a decision and how decisions will be documented.  One option is to add issues requiring WG decisions to a “Pending WG Decision” project.
  
## Status updates
  * Publish periodic status updates (ideally at least once every two weeks) so the community can keep up to date on the WG’s work without having to follow all issues/Slack conversations/etc.
    *  These updates should include:
      * what the WG accomplished since the last status update
      * what they are planning on working on before the next status update
      * any lessons the WG learned they’d like to share with others in the AMP community
    * File these updates as issues in the WG’s repo with the label “Type: Status Update.”
  * Each WG will provide a higher-level update to the community/TSC approximately every three months at a Design Review.  See the [Working Group Updates page](https://github.com/ampproject/meta/wiki/Working-Group-Updates) for more information.
  
## Working Group Membership
  * According to [AMP's governance model](https://github.com/ampproject/meta/blob/master/GOVERNANCE.md), the TSC sets the initial membership of each Working Group.  Each Working Group then adjusts its membership as needed using the [consensus-based decision-making policy](../GOVERNANCE.md#decision-making-policy).
  * Although each Working Group may define its own standards for determining Working Group membership, the following is a set of baseline expectations for Working Group members that most Working Groups follow:
    * Members of a Working Group are expected to consistently contribute to the work of the Working Group. Contributions can take many forms, including code contributions, feature/design discussions and helping the community.
    * Working Group members should be actively participating in WG discussions and generally aware of/involved in the work of the WG beyond their own projects.  Members of a WG may bring their own perspective (and the perspective of their employer) into the WG, but their participation in the WG should not be limited to only projects they/their employer prioritize.
    * Working Group membership is generally obtained after someone has been involved in the Working Group at the level expected of a Working Group member, rather than being proactively granted.
  * Working Groups may use other standards for membership, but if they do they should clearly document them.
  * Remember that Working Group membership is not required to participate in discussions, propose ideas, provide feedback on issues/PRs/etc.
