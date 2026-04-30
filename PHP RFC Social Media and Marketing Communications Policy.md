# PHP RFC: Social Media and Marketing Communications Policy

* Version: 1.0  
* Date: 2026-04-30  
* Author: Roman Pronskiy (roman@pronskiy.com)  
* Status: Draft  
* First Published at: http://wiki.php.net/rfc/social-media-policy

## Introduction

PHP is one of the most widely used programming languages in the world. Despite this remarkable success, PHP has long been perceived by parts of the broader tech community as declining or "dead" – a narrative that is demonstrably false but nonetheless persists.

One significant factor contributing to this perception gap is PHP's lack of coordinated marketing and communications efforts. While individual community members, conferences, and the PHP Foundation actively promote PHP through various channels, the official PHP project itself has no formal policy governing its presence on social media or other communication platforms.

This RFC proposes establishing a formal policy for PHP's official social media presence and marketing communications, ensuring that the PHP project can effectively communicate with its community and the broader technology ecosystem.

## Problem Statement

### The Current Situation

PHP currently maintains several official social media accounts, most notably:

* **Twitter/X ([@official\_php](https://twitter.com/official_php))**: \~109,000 followers, last post: Jun 4, 2024. The account is silent not due to a project decision but because the individual credential holder ceased posting unilaterally. Multiple requests to share credentials, transfer custody, or enable automated posting (as is done for Mastodon) have not been accommodated. Under current practice, no formal mechanism exists to compel transfer or define succession.
* **Mastodon ([@php@fosstodon.org](https://fosstodon.org/@php))**: \~5,000 followers, automated release announcements  
* **LinkedIn ([@phpnet](https://www.linkedin.com/company/phpnet/))** : \~225,000 followers, semi-actively updated by Kalle / The PHP Foundation members

The disparity is stark. The Twitter account, with over 100,000 followers – a substantial audience for any programming language – has been silent for nearly two years. Meanwhile, the Mastodon account operates with automated posting, demonstrating that minimal-effort communication is both technically feasible and operationally sustainable.

### Engagement

Apart from followers, we can use PHP’s analytics data as a proxy metric to estimate engagement acquired from different social media.

For April 2026, the data looks as follows:  

| Social Network | Visits |  Share |
|----------------|-------:|-------:|
| YouTube        |  5,373 | 33.66% |
| Reddit         |  2,915 | 18.26% |
| X/Twitter      |  2,102 | 13.17% |
| StackOverflow  |  2,068 | 12.96% |
| Facebook       |  2,048 | 12.83% |
| LinkedIn       |    675 |  4.23% |
| Telegram       |    205 |  1.28% |
| Hacker News    |    166 |  1.04% |
| Vkontakte      |    154 |  0.96% |
| Sourceforge    |     98 |  0.61% |
| Instagram      |     58 |  0.36% |
| Mastodon       |     37 |  0.23% |
| Workplace      |     16 |  0.10% |
| V2EX           |     15 |  0.09% |
| Bluesky        |     14 |  0.09% |
| Threads        |     12 |  0.08% |

Among platforms in scope of this policy, X/Twitter accounts
for 13.17% of social referral traffic, more than LinkedIn (4.23%)
and Mastodon (0.23%) combined. This traffic is generated despite
the X account being dormant since June 2024. An active automated
account would expand reach.

### Why This Matters

1. **Perception shapes reality**: When developers research PHP, a dormant official Twitter account with the last activity from almost two years ago reinforces the "PHP is dead" narrative, regardless of the language's actual vitality and continued development.  
     
2. **Missed communication opportunities**: PHP 8.5 was released in November 2025 with significant new features. The official Twitter account with its 109,000 followers said nothing. This represents a missed opportunity to reach developers who may have been unaware of PHP's continued evolution.  
     
3. **Community frustration**: There have been repeated requests from the PHP community for better marketing and communication. This RFC responds to those requests with a concrete, actionable proposal.  
     
4. **Competitive disadvantage**: Other programming languages actively maintain their social media presence. Python, TypeScript, and Go all have active official communications. PHP's silence is conspicuous by comparison.

### The Governance Gap

Currently, credentials for official PHP social media accounts are held by individual community members without clear governance policies. While these individuals have historically acted in good faith, the absence of formal policy creates several issues:

* No defined process for posting decisions  
* No mechanism for the community to request or approve communications  
* No succession planning if credential holders become unavailable  
* No accountability structure for the community at large

## Proposal

This RFC proposes adopting a formal Social Media and Marketing Communications Policy for the PHP project. The specific policy text will be submitted to https://github.com/php/policies after RFC approval.

### Core Principles

The policy is built on the following principles:

1. **Representation**: PHP should maintain an official presence on any platform with significant reach to developers.  
     
2. **Automation first**: Where feasible, communications should be automated to minimize volunteer burden and ensure consistency.  
     
3. **Neutrality**: Official PHP communications should focus on the language itself, releases, security advisories, and community events — not on platform politics or endorsements.  
     
4. **Shared stewardship**: Credentials for official accounts should be held by multiple trusted community members, with clear succession policies.  
     
5. **Transparency**: Policies governing official communications should be documented and publicly available.

### Governance Structure

This policy establishes clear roles and responsibilities for PHP's official communications:

#### Infrastructure Team: Account Custody

The PHP Infrastructure Team is responsible for:

* Holding credentials for all official PHP social media accounts  
* Maintaining secure credential storage with multiple authorized holders (minimum three)  
* Implementing and maintaining automation for cross-platform posting  
* Ensuring credential succession when holders step down  
* Technical operations: posting, account recovery, platform compliance

This is a purely technical and operational role. The Infrastructure Team executes communications but does not determine content strategy.

#### PHP Foundation: Content Authority

The PHP Foundation is designated as the decision-maker for PHP's official communications:

* **Content decisions**: The Foundation determines what gets posted on official channels, including messaging, timing, and tone  
* **Strategic direction**: The Foundation advises on platform presence, audience strategy, and communications priorities  
* **Marketing initiatives**: Any proactive marketing efforts beyond automated announcements are delegated to the Foundation  
* **Consultation**: The Foundation serves as consultant to the PHP project on all marketing and communications matters

This separation ensures that those with marketing expertise and organizational capacity (the Foundation) drive content decisions, while technical implementation remains with the Infrastructure Team.

#### Why This Division of Responsibilities?

1. **Expertise alignment**: The Foundation has staff experienced in developer relations and marketing. The Infrastructure Team has expertise in systems and automation.  
     
2. **Organizational capacity**: Marketing requires sustained attention and strategic thinking. The Foundation, as an organization with staff, can provide this more reliably than individual volunteers.  
     
3. **Clear accountability**: With defined roles, it's clear who is responsible for what. Content questions go to the Foundation; technical issues go to Infrastructure.  
     
4. **Separation of concerns**: Account credentials and content
   decisions follow different operational logic. Custody belongs
   with infrastructure expertise; content belongs with
   communications expertise.
     
5. **Scalability**: As PHP's communications needs grow, the Foundation can scale its marketing efforts without requiring changes to account custody.

#### Alternative Considered: Joint Content Committee

An alternative considered was a joint committee composed of Foundation
representatives and volunteer Internals contributors. This was rejected
in favor of the current proposal for the following reasons:

- The Foundation already has accountability to the PHP community
  through its membership and governance.
- Adding an elected internals component would create elections,
  terms, and replacement procedures that increase governance
  overhead disproportionate to the scope (which is operational
  communications, not project direction).
- The Foundation's content decisions remain subject to community
  oversight via future RFCs that can amend this policy.

If the community prefers the joint-committee model, this RFC can be
amended during discussion to incorporate it.

### Platforms and Scope

#### Text-Based Platforms (In Scope)

The following platforms have significant developer audiences and can be served with automated or low-effort text-based communications:

| Platform  | Audience Size    | Status                 | Proposed Action                     |
|:----------|:-----------------|:-----------------------|:------------------------------------|
| Twitter/X | \~109K followers | Dormant since Jun 2024 | Reactivate with automation          |
| Mastodon  | \~5K followers   | Active (automated)     | Continue current approach           |
| LinkedIn  | \~225K followers | Active (not automated) | Automate, continue current approach |

#### Video Platforms (Out of Scope)

Platforms such as YouTube, TikTok, and Instagram require significant resources for video content creation that the PHP project does not currently have. These platforms are explicitly out of scope for this RFC but may be addressed in future proposals if resources become available.

### Content Types and Authority

#### Automated Content (No Approval Required)

The following content types are suitable for fully automated cross-platform posting, requiring no per-post approval:

* Release announcements (major, minor, patch versions)  
* Security advisories and CVE announcements  
* RFC voting results  
* Conference and event announcements

These are triggered automatically by project events (release announcements, security commits, vote closures).

#### Curated Content (Foundation Authority)

The following content types require Foundation approval before posting:

* Milestone announcements  
* Anniversary and celebration posts  
* Blog post promotions  
* Any other non-automated content

#### Marketing Initiatives (Foundation Led)

Any proactive marketing efforts beyond the above categories are delegated to the PHP Foundation:

* Coordinated campaigns  
* Responses to industry narratives  
* Developer outreach initiatives  
* Cross-promotion with ecosystem projects

The Foundation may pursue such initiatives at its discretion, coordinating with the Infrastructure Team for technical execution.

### Implementation

#### Technical Approach

The Mastodon account already mostly operates under the model proposed by this RFC: automated posting via GitHub Actions for releases, no per-post overhead. It demonstrates that the proposed model is technically feasible and operationally sustainable. 

Following the Mastodon model, automated posting will be implemented via GitHub Actions and Pull Requests where possible.

#### Credential Management

* Minimum three (3) Infrastructure Team members shall hold credentials for each official account  
* Credentials shall be stored securely with documented access procedures  
* When a credential holder steps down, replacement shall be coordinated within 30 days  
* Emergency access procedures shall be documented and tested

#### Transition Plan

Upon adoption of this RFC:

1. The Infrastructure Team will inventory all accounts currently
   representing PHP officially across platforms.
2. Current credential holders will be requested to transfer
   credentials to Infrastructure Team secure storage within 60
   days.
3. If a credential holder declines or does not respond within 60
   days, the Foundation and Infrastructure Team will jointly
   determine whether to:
   a. Petition the platform for account recovery (where supported);
   b. Establish a new official account on that platform;
   c. Mark the original account as non-official on PHP.net.
4. For platforms where no current account exists (e.g., Bluesky),
   the Foundation may direct creation of an official account once
   this policy is in effect.

#### If This RFC Does Not Pass

If this RFC fails, the project will continue without formal
governance over communications. In that case, individual platform
decisions (including the pending X/Twitter link removal) should
each go through their own RFC, with the understanding that each
such decision creates ad-hoc precedent rather than systematic
policy.

## Addressing Platform Concerns

### On the Pending Link Removal

A separate RFC and PR propose removing the X/Twitter link from PHP.net on
the basis that the account is dormant. This RFC takes the position that
the link should not be removed at this time, on procedural rather than
substantive grounds:

1. The dormancy resulted from a unilateral action by one credential
   holder, not from a project decision. Removing the link ratifies that
   outcome retroactively and treats the absence of governance as
   equivalent to a project consensus.

2. The link represents a project-level commitment. Allowing one
   individual to effectively undo it through inaction sets a precedent
   that any credential holder can force project-wide outcomes by
   becoming non-responsive.

3. Once governance is in place, the question of whether to maintain
   each platform becomes a content decision within a defined process.
   At that point, removing or keeping the link reflects an actual
   project decision and can be made on its merits.

This RFC therefore proposes that link-removal questions be deferred
until the governance framework is adopted.

### On Twitter/X Ownership

The relevant question is not whether PHP endorses platform ownership
— maintaining a presence on X/Twitter does not endorse X/Twitter's
ownership any more than maintaining a GitHub presence endorses
Microsoft's. 

By maintaining presence across multiple platforms (X/Twitter, Mastodon, LinkedIn), PHP avoids dependence on any single platform and reaches developers wherever they prefer to be.

Major open-source projects and organisations (TypeScript, Golang, OpenJS Foundation, Python Software Foundation, Apache Foundation, Linux Foundation) maintain X/Twitter accounts.

That said, this RFC does not require PHP to maintain an X presence.
It establishes a process. If the PHP Foundation, operating under the
content authority defined here, determines that X is no longer an
appropriate channel for PHP communications, the Foundation can pause
or end posting. The decision becomes accountable, documented, and
reversible — rather than the result of one person's inaction.

## Backward Compatibility

This RFC establishes a new policy and does not affect any existing PHP functionality or code.

## Impact on Existing Account Holders

Current holders of official PHP social media credentials will be asked to:

1. Transfer credentials to the Infrastructure Team's secure storage  
2. Participate in the new governance structure if willing and if they are Infrastructure Team members  
3. Acknowledge the Foundation's content authority going forward

No individual's contributions or historical stewardship are diminished by this policy. This RFC seeks to formalize and extend existing practices, not to criticize past volunteers.

## Frequently Asked Questions

### Why give content authority to the PHP Foundation?

The Foundation has the organizational structure, staff, and expertise to make consistent, strategic communications decisions. The Foundation's mission—supporting PHP—aligns perfectly with effective PHP marketing.

### What if the Foundation decides to discontinue posting on a platform like X?

The Foundation's content authority includes the discretion to pause
or end official posting on any platform when it determines doing so
serves PHP's communications goals or community interests. Such a
decision would be documented and reversible. The point of this
framework is that platform decisions become deliberate,
accountable, and revisitable — not the result of inaction or
unilateral choices by individual credential holders.

### Does the Foundation control the accounts?

No. The Infrastructure Team holds credentials and operates the accounts. The Foundation decides what content gets posted. This is similar to how a marketing department works with an IT department: marketing decides the message, IT manages the systems.

### What if the Infrastructure Team disagrees with Foundation content decisions?

The policy establishes the Foundation as the content authority. The Infrastructure Team's role is technical execution, not content approval. If significant concerns arise about specific content, they should be raised with the Foundation board directly.

### Can this arrangement be changed?

Yes. This policy can be amended by a future RFC with 2/3 majority approval. The community retains ultimate authority over PHP project policies.

### What about platform-specific content?

Automated posts will be adapted to platform conventions (e.g., character limits, hashtag practices) but will contain equivalent information across all platforms. Platform-specific strategies beyond basic adaptation are at the Foundation's discretion.

### Can individuals still post about PHP on their personal accounts?

Absolutely. This policy governs only official PHP project accounts. Community members, Foundation staff, and core developers are encouraged to continue personal advocacy for PHP.

### Doesn't the PHP Foundation already do marketing?

The Foundation markets itself and promotes PHP through its own channels. This RFC specifically addresses the *official PHP project accounts* (like @official\_php), which are distinct from the Foundation's accounts. This policy creates a formal relationship where the Foundation also guides the project's official communications.

### Does the Foundation have capacity for this?

The Foundation employs developers and engages staff and volunteers
with experience in developer relations and communications. Most content
under this policy is automated (releases, security, votes), with
curated content and marketing initiatives within the Foundation's
existing operational scope. The policy does not require the
Foundation to expand staffing; it formalizes responsibilities the
Foundation is already structurally suited to carry out.

## Proposed Voting Choices

A single yes-or-no vote on the policy as a whole, requiring 2/3 majority.

## References

* [RFC: PHP.net Analytics Collection](https://wiki.php.net/rfc/phpnet-analytics)  
* [RFC: Policy on 3rd party code](https://wiki.php.net/rfc/third-party-code)  
* [PHP Policies Repository](https://github.com/php/policies)  
* [The PHP Foundation](https://thephp.foundation/)  
* [@official\_php on Twitter/X](https://twitter.com/official_php)  
* [@php on Fosstodon](https://fosstodon.org/@php)

## Changelog

* 2026-04-30: Initial draft

---

## Appendix A: Proposed Policy Document

*To be added to [https://github.com/php/policies](https://github.com/php/policies)*

```
# Social Media and Marketing Communications Policy

## Purpose

This policy governs the PHP project's official presence on social media and other
communication platforms, establishing clear roles for account custody and content
authority.

## Scope

This policy applies to all accounts officially representing the PHP project,
including but not limited to:
- Twitter/X (@official_php)
- Mastodon (@php@fosstodon.org)
- LinkedIn (@phpnet)

## Principles

1. **Reach**: PHP shall consider maintaining presence on all platforms with significant developer audiences.
2. **Automation**: Communications shall be automated where feasible.
3. **Neutrality**: Communications shall focus on PHP, not platform politics.
4. **Shared Stewardship**: Multiple credential holders shall manage each account.
5. **Transparency**: This policy shall be public and versioned.

## Roles and Responsibilities

### Infrastructure Team: Account Custody

The Infrastructure Team is responsible for:
- Credential custody (minimum 3 holders per account)
- Secure credential storage and succession
- Automation implementation and maintenance
- Technical posting operations

### PHP Foundation: Content Authority

The PHP Foundation is responsible for:
- Content decisions (what, when, messaging, tone)
- Strategic communications direction
- Marketing initiatives beyond automated content
- Consultation on communications matters

## Content Guidelines

### Automated Content (No Approval Required)
- Release announcements
- Security advisories
- RFC voting results

### Curated Content (Foundation Approval Required)
- Conference/event announcements
- Documentation milestones
- Celebrations and anniversaries
- Blog post promotions

### Marketing Initiatives (Foundation Led)
- Coordinated campaigns
- Narrative responses
- Developer outreach
- Ecosystem cross-promotion

### Prohibited Content
- Political statements unrelated to PHP
- Commercial endorsements of products or services unrelated to PHP
- Personal opinions presented as PHP's official position
- Code of Conduct violations
- Personal grievances or interpersonal disputes between contributors

## Implementation

Automated posting via GitHub Actions, extending the existing Mastodon model
to all platforms.

## Amendments

This policy may be amended by RFC with 2/3 majority approval.
```
