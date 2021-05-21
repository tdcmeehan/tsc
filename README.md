# Presto Technical Steering Committee (TSC)

The Presto TSC will be responsible for all technical oversight of the open source Project. 

## Presto Technical Charter

The Presto Technical Charter is located in [CHARTER.md](CHARTER.md)

## Collaboration Tools

### Mailing List

The TSC for Presto Foundation can be reached at their [mailing list](https://lists.prestodb.io/g/presto-tsc).

### Slack

The Presto Foundation maintains a [Slack Workspace](https://join.slack.com/t/prestodb/shared_invite/enQtNTQ3NjU2MTYyNDA2LTYyOTg3MzUyMWE1YTI3Njc5YjgxZjNiYTgxODAzYjI5YWMwYWE0MTZjYWFhNGMwNjczYjI3N2JhM2ExMGJlMWM) for communication and collaboration. The [Presto Foundation Slack Workspace](https://join.slack.com/t/prestodb/shared_invite/enQtNTQ3NjU2MTYyNDA2LTYyOTg3MzUyMWE1YTI3Njc5YjgxZjNiYTgxODAzYjI5YWMwYWE0MTZjYWFhNGMwNjczYjI3N2JhM2ExMGJlMWM) is open for anyone to join. 

Once you join the The [Presto Foundation Slack Workspace](https://join.slack.com/t/prestodb/shared_invite/enQtNTQ3NjU2MTYyNDA2LTYyOTg3MzUyMWE1YTI3Njc5YjgxZjNiYTgxODAzYjI5YWMwYWE0MTZjYWFhNGMwNjczYjI3N2JhM2ExMGJlMWM), you can participate in any public channels.

### Calendars and Meetings

The Presto Foundation maintains a [public calendar](https://calendar.google.com/calendar/embed?src=linuxfoundation.org_vrjlva5b0u73ps75fvnv5sasi4%40group.calendar.google.com&ctz=America%2FChicago) for TSC meetings. These meetings are open for anyone to join.

Because we work in a highly distributed environment and will rarely meet in person, participants are encouraged to use video as appropriate.

### CLA

Everyone must sign the Presto CLA prior to making a contribution. You may either sign the CLA on your own, or your company can sign it for you. At a high level, if you aren't covered by a CLA, you will be notified the first time you open a PR. Please see our [documentation on the process](./CLA.md).

## Members

The TSC voting members are initially the [Project’s Committers](https://github.com/prestodb/.github/blob/master/CONTRIBUTING.md).

INSERT HERE THE TSC MEMBER TABLE

INSERT HERE THE COMMITTER MEMBER TABLE

Per the [Technical Charter](CHARTER.md), when there are less than six related companies represented on the TSC, the employees of each company may only submit one vote on TSC decisions where voting is required.

### Term of TSC voting members

The Presto TSC seeks to balance the energy and enthusiasm of new members with the stability provided by long-term members.  As such, TSC voting members will serve three-year terms, after which they will be eligible for re-election.  There is no limit to the number of times an individual may run for an open seat.

To provide balance, the terms of TSC members will be adjusted so that roughly 1/3 of seats are elected each year.  If the classes become unbalanced, then the TSC shall designate the appropriate number of seats as one-year terms at the first opportunity to fix the imbalance.

For simplicity, membership terms will be aligned to the calendar year, and will run from January 1st to December 31st of the following year. Initially, the TSC shall randomly designate 1/3 of the seats to be one-year terms, 1/3 of the seats to be two-year terms, and the remainder shall be three-year terms.


### Becoming a TSC Member

The Technical Charter specifies that TSC voting members are initially the Presto committers.  Prior to each election, the TSC will determine the number of available seats and [solicit nominations from the community](./nominations/README.md).  The TSC has primary responsibility for ensuring there are sufficient candidates to fill each available seat.

#### Eligibility

Beginning with the 2021 election, any member of the technical community may stand for election to the TSC.

#### Nominating procedure

The TSC shall announce the number of the seats and the nominating procedures on the [presto-dev mailing list](https://lists.prestodb.io/g/presto-dev) by October 15th.

Nominations and self-nominations shall be sent to the [presto-dev mailing list](https://lists.prestodb.io/g/presto-dev) by November 15th.

#### Election procedure

The existing Presto TSC members (including the class whose term expires at the end of the year) shall vote using the [Condorcet method](https://civs.cs.cornell.edu/) by December 1st, subject to the voting requirements outlined in the [charter](CHARTER.md#3-tsc-voting).

The incoming class shall be announced by December 15th, and their term will begin January 1st of the following year.

### Changing the composition of the TSC

Per the [Charter](CHARTER.md), the TSC may change the maximum number of TSC members by supermajority vote.  In general, the TSC will attempt to make changes to the maximum number of voting members at election time, to ensure the classes remain balanced.

### Resignation of TSC voting members

If a member resigns, the remaining TSC voting members may select a replacement.  This individual will serve out the remainder of the original member's term.

## Policies and procedures

The Presto TSC is governed by the [Technical Charter](CHARTER.md).  The Charter provides a foundational structure for the TSC on topics such as its scope, how to make decisions, and how to make changes to itself.  At the same time, it grants the TSC a high degree of freedom when determining how to implement the policies of the Presto Foundation.

The following policies and procedures have been adopted by the TSC.

### Making decisions

Per the [charter](CHARTER.md), wherever possible the TSC will attempt to make decisions by consensus.  In circumstances where consensus is not possible or if a vote is explicitly required, a majority (or higher, if required by the governance) of TSC voting members must approve in order for the action to proceed.  Votes will be taken over email, and documented in the next meeting.

### Merging PRs into the TSC repository

Pull requests that do not change the charter or governance of the TSC can be merged into this repository provided the following conditions have been met:

* There are no outstanding objections
* There are two approvals by TSC members
* The PR has been open for at least 72 hours

Pull requests that change governance of the TSC (excluding the charter) must be open for at least 14 days, unless consensus is reached in a meeting with quorum of voting members.

Pull requests that change the charter of the TSC must meet any requirements in the [charter](CHARTER.md).

If consensus cannot be reached, a pull request may still be landed after a vote by the Voting members to override outstanding objections.

### Fast-Tracking PRs

Special exception is made for pull requests seeking to make any of the following changes to this repository:

- Errata fixes.
- Editorial changes.
- Meeting minutes.
- Updates to team lists.
- Doc fixes.

Charter changes cannot be fast-tracked.

To propose fast-tracking a pull request, apply the ***fast-track*** label. Then add a comment that TSC members may upvote. If someone disagrees with the fast-tracking request, remove the label. Do not fast-track the pull request in that case.

The pull request may be fast-tracked if two TSC members approve the fast-tracking request. To land, the pull request itself still needs two TSC member approvals.

TSC members may request fast-tracking of pull requests they did not author. In that case only, the request itself is also one fast-track approval. Upvote the comment anyway to avoid any doubt.

### IP Policy

The [Presto Foundation IP policy](https://github.com/prestodb/tsc/blob/master/CHARTER.md#8-intellectual-property-policy) is defined in the [charter](CHARTER.md), and it applies unless an exception is explicitly approved by the TSC.

#### Copyright notices

Presto Foundation follows the [community best practice](https://www.linuxfoundation.org/blog/2020/01/copyright-notices-in-open-source-software-projects/) of not requiring contributors to add a notice to each file.

#### SPDX

Contributors are encouraged (but not required) to adopt the practice of including [SPDX short form identifiers](https://spdx.org/ids-how) in their files.
