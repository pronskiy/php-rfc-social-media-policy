# PHP RFC: Social Media and Marketing Communications Policy

* Version: 1.4
* Date: 2026-05-18
* Author: Roman Pronskiy (roman@pronskiy.com)
* Status: Draft
* First Published at: https://wiki.php.net/rfc/social-media-policy
* Companion Policy PR: https://github.com/php/policies (branch `social-media`)

## Introduction

The PHP project maintains official accounts on several social media platforms,
but it has no formal policy governing those accounts. Credentials are held by
individual community members, posting decisions are ad hoc, and there is no
defined process for adding, retiring, or recovering accounts.

This RFC proposes adopting a formal Social Media and Marketing Communications
Policy. **The policy text is provided as a companion pull request to the
[`php/policies`](https://github.com/php/policies) repository.** Approving this
RFC adopts that policy document.

## Problem Statement

The PHP project currently maintains official accounts on Twitter/X
([@official_php](https://twitter.com/official_php)), Mastodon
([@php@fosstodon.org](https://fosstodon.org/@php)), and LinkedIn
([@phpnet](https://www.linkedin.com/company/phpnet/)). These accounts operate
without a formal governance framework, which has produced concrete problems:

* **No defined custody.** Credentials are held by individual community members.
  There is no formal mechanism to transfer credentials or to compel a transfer
  when a holder becomes unavailable.
* **No succession planning.** If a credential holder steps down or becomes
  unresponsive, the project has no documented path to recover or replace the
  account.
* **No defined content process.** There is no agreed-upon mechanism for the
  community to request, approve, or coordinate official communications.
* **No accountability structure.** Posting decisions — including the decision
  not to post — currently rest with whichever individual holds the
  credentials, regardless of project-level intent.

The Twitter/X account illustrates the cost of these gaps in practice. It has
approximately 109,000 followers but has been silent since June 4, 2024 — not
as a result of a project decision, but because the credential holder ceased
posting unilaterally. Multiple requests to share credentials, transfer
custody, or enable automated posting (as is already done for Mastodon within the same requests) have
not been accommodated, and no formal mechanism exists to resolve the
situation.

This RFC does not propose any specific outcome for the Twitter/X account.
It proposes a policy under which such outcomes become deliberate,
documented, and reversible — rather than the result of inaction or
unilateral choices by individual credential holders.

## Proposal

This RFC proposes adopting a formal Social Media and Marketing Communications
Policy for the PHP project. The policy text is provided as a companion pull
request to the [`php/policies`](https://github.com/php/policies) repository.

The policy establishes:

* **Scope.** The official list of platforms is defined in the policy file and
  changes by pull request. Text-based platforms (Twitter/X, Mastodon,
  LinkedIn, and similar) are in scope; video platforms are explicitly out of
  scope.
* **Principles.** Reach, automation, neutrality, shared stewardship, and
  transparency.
* **Account custody — PHP Infrastructure Team.** Credentials for all official
  PHP social media accounts are held by the Infrastructure Team, with a
  minimum of three (3) holders per account, secure storage, documented
  succession, and responsibility for automation and technical operations.
* **Content authority — PHP Social Media Team.** A new, open-volunteer team
  drawn from the PHP community decides what is posted, when, and in what
  tone. Membership is self-organized; the roster is public and maintained
  in the policy file via pull request.
* **Optional delegation to the PHP Foundation.** The Social Media Team MAY
  delegate marketing initiatives or curated content to the PHP Foundation,
  with delegation recorded publicly and revocable at any time. Delegation
  does not transfer credential custody.
* **Content categories.** Automated content (releases, security advisories,
  RFC voting results, PHP.net news entries) requiring no per-post approval;
  curated content requiring Social Media Team approval; marketing
  initiatives; and prohibited content.
* **Account transition.** A defined procedure for inventory, credential
  transfer, and recovery upon adoption.
* **Adding and removing official accounts.** A defined, ongoing procedure
  for creating, retiring, or recognizing accounts after adoption.

Operational details are defined in the policy document itself, in keeping
with the PHP project's practice of locating process definitions in
[`php/policies`](https://github.com/php/policies).

### Why This Division of Responsibilities

The policy assigns credential custody to the PHP Infrastructure Team and
content authority to a new, open-volunteer PHP Social Media Team. This
reflects:

1. **Custody belongs with infrastructure expertise.** Account credentials are
   sensitive technical assets. The Infrastructure Team already handles
   credentials for project systems, has secure storage and succession
   practices, and is the appropriate custodian.
2. **Content benefits from a broader, lower-barrier group.** Deciding what
   to post does not require system-administration access. Opening this role
   to volunteers from the PHP community lets members with relevant experience
   contribute without first joining the Infrastructure Team.
3. **Clear accountability.** Custody questions go to the Infrastructure
   Team; content questions go to the Social Media Team. Each team is
   responsible for the function it is best suited to perform.
4. **Optional Foundation involvement.** The Social Media Team MAY delegate
   specific responsibilities — particularly marketing initiatives — to the
   PHP Foundation, drawing on the Foundation's staff and developer-relations
   experience when useful, without making Foundation involvement structurally
   required.
5. **Reversibility.** The policy may be amended by a future RFC, including
   changes to team structure or delegation if the community concludes a
   different arrangement is preferable.

### Alternative Considered: Foundation as Content Authority

An earlier draft of this RFC named the PHP Foundation as the content
authority. This was replaced by an open-volunteer Social Media Team because:

* Making the Foundation a structurally required content authority creates a
  dependency on an external organization for a project-level function.
* An open-volunteer team lowers the barrier to participation and keeps
  content decisions inside the PHP project's own governance.
* The Foundation may still contribute via explicit, revocable delegation
  when the Social Media Team finds it useful.

If the community prefers a different structure, this RFC can be amended
during discussion.

## Backward Compatibility

This RFC establishes a new policy and does not affect any existing PHP
functionality or code.

## Impact on Existing Account Holders

Current holders of official PHP social media credentials will be asked to:

1. Transfer credentials to the Infrastructure Team's secure storage.
2. Join the Social Media Team if willing and interested in content
   decisions, and/or join the Infrastructure Team if they wish to retain
   custody.
3. Acknowledge the Social Media Team's content authority and the
   Infrastructure Team's custody role going forward.

No individual's contributions or historical stewardship are diminished by this
policy. The intent is to formalize and extend existing practices, not to
criticize past volunteers.

## Frequently Asked Questions

### Who holds the credentials?

The PHP Infrastructure Team. A minimum of three (3) Infrastructure Team
members hold credentials for each official account, with documented
succession and emergency-access procedures. Social Media Team members do
not hold credentials by virtue of that role.

### Who is on the Social Media Team initially?

The initial roster will be populated upon adoption, with current credential
holders willing to participate as well as additional volunteers from the
PHP community. The roster is public and maintained in the policy file.

### How does someone join the Social Media Team?

A prospective member proposes themselves to the existing team. The team
agrees on its own internal process for accepting or declining new members.
Members should have a demonstrated connection to the PHP community —
contributions to php-src, the documentation, the infrastructure, a PHP user
group, or comparable involvement.

### What is the PHP Foundation's role under this policy?

None by default. The Social Media Team MAY delegate specific responsibilities
to the PHP Foundation — for example, drafting marketing campaigns or curating
content — but is not structurally required to involve the Foundation.
Delegation is recorded publicly and revocable at any time. Delegation never
transfers credential custody.

Separately, individual PHP Foundation staff or members MAY volunteer to join
the Social Media Team in a personal capacity, subject to the same membership
criteria as any other volunteer. In that case they participate as individual
team members, not as representatives of the Foundation.

### What if the Social Media Team and Infrastructure Team disagree?

The policy assigns content authority to the Social Media Team and custody
to the Infrastructure Team. The Infrastructure Team executes posting on
behalf of the Social Media Team for non-automated content; its role is
technical execution, not content review. Significant cross-team disputes
SHOULD be raised on the internals mailing list.

### How are accounts added or removed?

The policy defines an "Adding and Removing Official Accounts" procedure.
Routine additions and retirements are decided by the Social Media Team
(custody is established by the Infrastructure Team) and recorded via pull
request to the policy file. Retirements of accounts with established public
reach SHOULD be announced on the internals mailing list before acting; the
community MAY request an RFC if it considers a retirement a project-level
decision.

### Can this arrangement be changed?

Yes. The policy may be amended by a future RFC with 2/3 majority approval.
Updates to the team roster and routine Scope changes do not require an RFC.

### Can individuals still post about PHP on their personal accounts?

Yes. The policy governs only official PHP project accounts. Community members,
Foundation staff, and core developers are encouraged to continue personal
advocacy for PHP.

## Proposed Voting Choices

A single yes-or-no vote on the policy as a whole, requiring 2/3 majority.

## References

* Companion policy PR: https://github.com/php/policies (branch `social-media`)
* [PHP Policies Repository](https://github.com/php/policies)
* [The PHP Foundation](https://thephp.foundation/)

## Changelog

* 2026-04-30: Initial draft.
* 2026-05-18 (v1.1): Policy substance moved to a companion PR in
  [`php/policies`](https://github.com/php/policies) per project convention.
  Removed embedded policy appendix, the "pending link removal" subsection,
  and the "if this RFC does not pass" subsection.
* 2026-05-18 (v1.2): Briefly considered combining custody and content into a
  single open-volunteer team.
* 2026-05-18 (v1.3): Reverted to a split model. Credential custody retained
  by the PHP Infrastructure Team; content authority held by a new
  open-volunteer PHP Social Media Team; PHP Foundation has no structural
  role, only optional delegation.
* 2026-05-18 (v1.4): Refocused the RFC on the policy itself. Removed the
  engagement-data section, "Why This Matters", and "On Twitter/X
  Ownership" advocacy sections. Condensed the Problem Statement to the
  governance gap, retaining a single illustrative reference to the
  Twitter/X account's custody and dormancy as a concrete example.
