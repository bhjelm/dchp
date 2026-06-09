# Working Procedures
This document outlines the working procedure for the joint initiative by ISO/IEC JTC1/SC 17 (ISO) WG10 and WG4 and OpenID Foundation (OIDF) DCP WG to harmonize their respective credential exchange protocol (ISO/IEC 18013-5 DeviceRequest/Device Response and OID4VP Authorization Request/Authorization Response) by supporting the coexistence of multiple credential formats (mdoc and SD-JWT VC) for in-person and online.

## Working Group Roles
- Chair is an individual Contributor(s) selected to coordinate the development of the work of the working group as well as to administer the operation of the working group.
- Editor is an individual contributors who administer the development of a Specification by the working group. For example, they are expected to author PRs, review PRs, deal with items related to the spec like IANA registrations, and propose resolutions to comments. (Other WG members may also do these things, but if no one else is willing the responsibility falls to the Editors.)
- A member is any eligible individual who actively participates in the working group.
- A contributor is any Member who contributes to the development of a Specification by the working group.

## Working Group Leadership
- Chair selection process. The functional leaders of the group (co-chairs) must be representatives of either OIDF or ISO, for example, if there is no consensus from both groups on the co-chairs, ISO members could choose to elect one co-chair, whilst OIDF members also elect one co-chair.

## Use of Collaboration Tools
### Communication:
- The group will have a dedicated e-mail distribution list for information from the co-chair(s), meeting minutes, and group announcements, and discussion within the working group. Any member or participant of the group may subscribe to the e-mail distribution list.
- Slack may be used to facilitate quick communication, networking, and collaboration among WG members. 

### Online meetings: 
- Zoom will be used for teleconferences. 

### Technical Development: 
- GitHub will be the primary tool for technical working documents. The GitHub will be public. Any member or participant of the group should establish their own GitHub account and request access (to contribute) by contacting the co-chairs.

## Meetings
- The working group will meet regularly to advance the technical work. Meetings may be conducted at any reasonable time, place, and manner as selected by the working group, with the goal of providing an environment conducive to the working group’s work and to maximize participation. Meeting notification should be distributed at least seven (7) days in advance for online meetings, and six (6) weeks in advance for in-person meetings.
- Members participating in a working group meeting shall follow the Code of Conduct.
- Meeting quorum means a minimum number of parties required for administrative decisions (e.g., approving minutes). Decisions requiring a quorum must be notified at least a week in advance. The specific numbers are defined by the working group, although the SDO sets a minimum (e.g. for OIDF the minimum is 5 but the working group can decide it’s 6 but can’t decide it’s 4). 
- Working group meetings will not conflict with existing OIDF group meetings as is standard practice at OIDF.

## Specification development
### Technical contributions: 
#### Technical submission: 
- The group shall consider draft technical submission for adoption through consensus decision-making.
- Issues: Members should open issues in GitHub to raise topics for discussion by the group and Members should comment in issues to facilitate discussions. Issues the working group decides to close should be marked as ‘pending close’ and not formally closed until 14 days without objections have passed.
- Pull Requests: A GitHub Pull Request should be opened once consensus on all the normative changes has been reached on an issue. If a significant amount of discussion happens on a PR, it may need to be closed and potentially split into multiple issues.
##### Before merging a Pull Request, the following criteria must be met:
- PR has been open 2 weeks, if it is not editorial
- No normative changes to the PR in the last 2 weeks
- Issue or PR discussed in at least 1 WG meeting
- No unresolved comments
- 3 PR approvals (as a gate just to make sure a couple of people have actually fully read the changes)

### Review process:
- The specification should go through the following stages to allow members to review the document and submit comments (see Figure 1):
- Every 2 months a draft will be shared formally with the DCP and WG10. Any feedback on the draft must be given to the joint WG directly. It is assumed that any matters in the document not commented within 6 weeks are acceptable to both WGs. During this periodic review, the WG will continue to advance the specification and address any new comments as they are received from DCP and WG10 members. 
- Before a document is published formally (as final or e.g. as an implementation/implementors draft at OIDF) there is a 6 week period where PR are not merged and participants (both within the WG and within DCP/WG10) are requested to review the entire document and provide comments. Comments are all considered before the spec continues to the formal publishing step. Technical comments will generally not be accepted after the 6 week period. The working group may decide (via the consensus process below) to repeat the 6 week period. The goal is to allow publication if there is consensus on smaller changes, and to consider repeating the review process in case of more significant changes.
- Comment resolution will occur only within the joint WG. It is expected that WG10/DCP accept the decision of the joint WG on those comments, i.e. the members who comment will participate within the joint WG (where the decision is made as per consensus process below).
- It is assumed that in the medium term, all relevant people will be participating in the joint WG and this process can be simplified.

<Figure 1>

## Decisions
- General: All decisions should be made based on group consensus and made in meetings. Important decisions (including the decision to publish) must be tracked in a GitHub issue.
- Consensus process: Consensus decision-making is a collaborative process where the Members of the work together to reach the best possible decision for the group. Consensus does not imply unanimity, although there should be substantial support for consensus decisions. To promote consensus, Chair(s) must ensure consideration and resolution of all legitimate comments of Contributors, and endeavor to facilitate participation of the relevant parties. When assessing consensus, Chair(s) must assess it separately for participants who are members of WG10 and those who are members of the DCP WG, to minimize the likelihood that WG10 and/or DCP do not adopt the work.

## Publication Process
- Once the Review Process described above is complete, the document will be published through the standard SDO process.
- Specification Lifecycle: Updates may be made via repeats of the Review Process, followed by following the SDO process for updating a specification.
- The technical specification will be published by the SDO(s) within whose legal framework the work is done.
The group intends to include a statement like: ‘This specification has been jointly developed by members of ISO/IEC JTC 1/SC 17 WG 10 and members of the OpenID Foundation DCP WG.’
Publications should either include both the OIDF and ISO logos and names, or neither logo nor name. (Except where required by SDO rules, e.g., copyright statement and other legal language.)
- The new protocol's name will be agreed by the group and should not echo existing protocol names or suggest a version extension of one. The specification may, however, reference other protocols that are already published and in use.

## Communication
Outgoing communications regarding the standard and its protocols will be managed by the new working group. Joint statements may, however, be published through whatever channels the SDOs already use.
