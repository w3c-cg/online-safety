# [DRAFT] Online Safety Community Group Charter

This Charter is a work in progress. To submit feedback, please raise issues in the [online-safety repository](https://github.com/w3c-cg/online-safety) where the Charter is being developed.

* **This Charter:** {TBD: URI}  
* **Previous Charter:** {TBD: URI}  
* **Start Date:** {TBD: date the charter takes effect}  
* **Last Modified:** {TBD: date of last modification}

## Goals

The mission of this group is to provide a discussion forum about the technical and architectural considerations for online safety, including safety for children online. While many see a particular interest in bolstering safety for vulnerable populations such as children, safety is important to all users of the Web.

This CG expects to support the following goals (among others):

* developing a shared understanding of age-based content restriction considerations;
* deepening insights into technical mechanisms (e.g., zero-knowledge proofs, device-enforcement): their* capabilities, limitations, and deployment considerations;
* modeling threats to online safety, including harassment, unwanted contact, distressing content, disclosure of* personal information (including "doxxing") and other forms of abuse, especially to vulnerable or marginalized people;
* analyzing how technological choices influence privacy, freedom of expression, Internet fragmentation, and* centralization;
* sharing relevant resources, such as research papers and policy documents;
* identifying and incubating technical standards work (if any) for addressing these issues.


## Scope of Work

The scope includes discussions of technical mechanisms and considerations for online safety, which may extend to sociotechnical aspects. 

An example topic would be architectures and mechanisms to enable age-based restrictions to content online, as a potential tool for supporting children's online safety. Proposed regulations for online safety often suffer from lack of understanding about available technologies, including their capabilities, limitations, and implications. For example, choices made in support of age-gating systems may have significant effects on global networks and their end users, impacting human rights as well as core architectural principles. This topic and the potential for a community group was discussed at (among other places), [W3C TPAC 2025](https://www.w3.org/2025/11/12-age-restrictions-minutes.html), [W3C Breakouts Day 2026](https://docs.google.com/document/d/15n0Cv_NPkn3SIPJxvUEhJWXL0YgFfsJRIRZO35psYLE/edit?tab=t.0) and the [Privacy Working Group](https://github.com/w3c/privacywg/blob/main/minutes/2026/privacywg-20260416.md#aob), and follows conversation at the [IAB/W3C Workshop on Age-Based Restrictions on Content Access in 2026](https://www.ietf.org/archive/id/draft-iab-agews-report-02.html), and [with the W3C Technical Architecture Group](https://github.com/w3ctag/meetings/blob/gh-pages/2026/telcons/01-26-minutes.md#age-restrictions-on-the-web). The amount of attention indicates that technologists and other interested parties are seeking a forum where these issues can be examined in depth, among a diverse group of experts.

This group may publish specifications and other types of reports, either as incubation for future standardization or as information or feedback for stakeholders, including policymakers, interested in online safety. Previously published [W3C Statements](https://www.w3.org/policies/process/#w3c-statement) may provide useful guidance and context for further work including the Privacy Principles (on [vulnerability](https://www.w3.org/TR/privacy-principles/#vulnerability), [guardians](https://www.w3.org/TR/privacy-principles/#guardians), [device administrators](https://www.w3.org/TR/privacy-principles/#device-administrators), [protection from abusive behavior](https://www.w3.org/TR/privacy-principles/#protecting-web-users-from-abusive-behaviour)) and Ethical Web Principles (on [harm to society](https://www.w3.org/TR/ethical-web-principles/#noharm), [healthy community](https://www.w3.org/TR/ethical-web-principles/#community), [universal access](https://www.w3.org/TR/ethical-web-principles/#allpeople), [privacy](https://www.w3.org/TR/ethical-web-principles/#privacy) and [free expression](https://www.w3.org/TR/ethical-web-principles/#expression)).

### Out of Scope

Primarily non-technical aspects of online safety, such as debates about exactly what should be considered "adult content", are out of scope.

Research on evaluations of online safety and safety measures are likely better suited to research groups and academic venues. Links to such work could be shared, such as papers relevant to the group's interests, but research would not be carried out directly in this Community Group.

Policy statements about supporting online safety are out of scope. The Community Group will seek to re-direct general feedback on policy proposals to more appropriate venues, including policymakers actively considering these topics.

## Deliverables

The Community Group may decide to adopt deliverables, including specifications or non-normative reports, where such deliverables are within the Scope of Work and have sustained interest from both editors and other participants.

The chairs will update the charter to reflect decisions to adopt or remove deliverables, or to update descriptions and timelines.

### Specifications

_for example, age range signaling / age check specification_

### Non-Normative Reports

The group may produce other Community Group Reports within the scope of this charter that are not Specifications, such as use cases, requirements, or white papers.

_for example, threat model or requirements for age assurance on the web_

### Test Suites and Other Software

The group **may** produce test suites to support the specifications. See the GitHub `LICENSE` file for test suite contribution licensing information.

## Dependencies or Liaisons

The subject matter of this group is relevant to others working in security, privacy, and digital identity, accessibility, online social interaction as well as fundamental web architecture. The Community Group plans to seek feedback from such groups as the Privacy Working Group, Security Working Group, Federated Identity Working Group, Verifiable Credentials Working Group, Social Web Community Group, the Accessible Rich Internet Applications Working Group, the Accessibility Guidelines Working Group, the Browser Testing and Tools Working Group and the TAG.

The Community Group plans to seek feedback from other standard-setting bodies and organizations working on related topics, including at least:

* [WHATWG](https://whatwg.org/)
* IEEE and ISO Working Groups related to age verification and parental controls
* [Internet Architecture Board](https://www.iab.org/) ([RFC 9998](https://datatracker.ietf.org/doc/rfc9998/); [IAB Statement on Age-Based Restrictions and Online Safety](https://datatracker.ietf.org/doc/statement-iab-statement-on-age-based-restrictions-and-online-safety/) ), or any related IETF or IRTF groups

The Community Group will also seek input from audiences outside of technical standard-setting bodies, including at least:

* young people
* policymakers
* adult content providers

## Community and Business Group Process

The group operates under the [Community and Business Group
Process](https://www.w3.org/community/about/process). Terms in this
Charter that conflict with those of the Community and Business Group
Process are void.

As with other Community Groups, W3C seeks organizational licensing
commitments under the [W3C Community Contributor License Agreement
(CLA)](https://www.w3.org/community/about/process/cla/). When people
request to participate without representing their organization's legal
interests, W3C will in general approve those requests, with the
following understanding: W3C will seek and expect an organizational
commitment under the CLA starting with the individual's first request
to make a contribution to a group [Deliverable](#deliverable). The
section on [Contribution Mechanics](#contrib) describes how W3C
expects to monitor these contribution requests.

The [W3C Code of Conduct](https://www.w3.org/policies/code-of-conduct/) and [W3C Antitrust and competition policy](https://www.w3.org/policies/antitrust-2024/) apply to participation in this group.

## Work Limited to Charter Scope

The group will not publish specifications on topics other than those listed under [Specifications](#specifications). See below for [how to modify the charter](charter_change).

## Contribution Mechanics

Substantive contributions to specifications can only be made by Community Group Participants who have agreed to the [W3C Community Contributor License Agreement (CLA)](https://www.w3.org/community/about/process/cla/).

Reports other than Specifications published by this group should use the [W3C Software and Document License](https://www.w3.org/copyright/software-license-2023/) where possible.

Community Group participants agree to make all contributions in the GitHub repository the group is using for the particular document — e.g., via pull requests, issues, or comments on existing issues. 

All GitHub repositories attached to the Community Group must contain a copy of the [CONTRIBUTING](https://github.com/w3c/licenses/blob/main/CG-CONTRIBUTING.md) and [LICENSE](https://github.com/w3c/licenses/blob/main/CG-LICENSE.md) files.

## Transparency

The group will conduct all technical work in public. If the group uses GitHub, technical work will occur in its GitHub repositories (and not privately on mailing lists).

Meetings may be restricted to Community Group participants, but a public summary or minutes must be posted to the group's public mailing list or as an issue on GitHub.

_TODO: Chatham House Rule meetings were suggested as an option for some sensitive discussions, but may not be compatible with the transparency expectations we have for working W3C meetings. We could suggest that separate workshops and events might be held under Chatham House Rule, or that the CG could choose to hold specially scheduled meetings under Chatham House Rule, for discussion purposes but not to develop the specifications._

The Community Group will often work asynchronously, using Slack, GitHub and the mailing list. Editors may meet separately to work through issues on deliverables. Group meetings will be scheduled and rotated to accommodate global participation and equity.

## Decision Process

This group will seek to make decisions where there is consensus. 
Chairs will assess consensus, and use a Call for Consensus to allow multi-day online feedback for a proposed course of action. 
After discussion and due to consideration of different opinions, a decision should be publicly recorded.

If substantial disagreement remains (e.g., the group is divided) and
      the group needs to decide an Issue in order to continue to make
      progress, the Group will choose an alternative that had
      substantial support (with a vote of participants if
      necessary). Individuals who disagree with the choice are
      strongly encouraged to take ownership of their objection by
      taking ownership of an alternative fork. This is explicitly
      allowed (and preferred to blocking progress) 
      to let implementation experience inform which spec is
      ultimately chosen by the group to move ahead with.

Any decisions reached at any meeting are tentative and should be
      recorded in a GitHub Issue for groups that use GitHub and
      otherwise on the group's public mail list. Any group participant
      may object to a decision reached at an online or in-person
      meeting within 7 days of publication of the decision provided
      that they include clear technical reasons for their
      objection. The Chairs will facilitate discussion to try to
      resolve the objection according to this decision process.

It is the Chairs' responsibility to ensure that the decision process
      is fair, respects the consensus of the CG, and does not
      unreasonably favor or discriminate against any group
      participant or their employer.

## Chair Selection

Participants choose their Chair(s) and can replace them at any time. However, if 5 participants (no two from the same organization) call for an election, the group must use the following process, consulting the Community Development Lead on election operations:

* Participants announce their candidacies. Participants have 14 days to
      announce their candidacies, but this period ends as soon as all
      participants have announced their intentions. If there is only one
      candidate, that person becomes the Chair. If there are two or more
      candidates, there is a vote. Otherwise, nothing changes.

* Participants vote. Participants have 21 days to vote for a single
      candidate, but this period ends as soon as all participants have
      voted.  The individual who receives the most votes, no two from
      the same organization, is elected chair. In case of a tie,
      RFC3797 is used to break the tie. An elected Chair may appoint
      co-Chairs.

Participants dissatisfied with the outcome of an election may ask the
      Community Development Lead to intervene. The Community
      Development Lead, after evaluating the election, may take any
      action including no action.

If there has not been an election, Chairs should poll the group at least once a year, and initiate the election process unless there is consensus for the current Chairs to continue.

## Amendments to This Charter

The group can decide to work on a proposed amended charter, editing
the text using the [Decision Process](#decision) described above.  The
decision on whether to adopt the amended charter is made by conducting
a 30-day vote on the proposed new charter. The new charter, if
approved, takes effect on either the proposed date in the charter
itself, or 7 days after the result of the election is announced,
whichever is later. A new charter must receive 2/3 of the votes cast
in the approval vote to pass. 

The group may adopt, remove or update deliverables by the simpler group decision
process rather than this charter amendment process.
