====== PHP RFC: Adopt Code Of Conduct ======
  * Version: 0.5
  * Date: 2016-01-20
  * Author: Derick Rethans <derick@php.net>
  * Original Author: Anthony Ferrara <ircmaxell@php.net>
  * Status: Reopened
  * First Published at: http://wiki.php.net/rfc/adopt-code-of-conduct

===== Introduction =====

This RFC proposes that the PHP project should adopt a formal code of conduct for its members.

The goal of this code of conduct is to give a clear signal what is expected of contributors and project maintainers, regarding their conduct in discussions on mailing lists, and other related communication channels. More specifically, the expected conduct in discussing language improvements and changes through the RFC process.

This proposal consists of several parts:

  * A general "Code of Conduct", which provides a general overview on what constitutes as unacceptable behaviour
  * A set of guidelines to foster collaboration on proposed language features through RFCs, in addition to the formal RFC process that we already have at https://wiki.php.net/rfc/voting
  * A set of procedures to follow if individuals wish to make complaints if other project members do not follow either the Code of Conduct or the Constructive Collaboration Guidelines.
  * A Contributor Mediation Team to assess and act upon the complaints as received through the above procedures
  * Possibilities for strong action if things really go awry regarding a project member. For example, if project members continue to persistently ignore the Collaboration Guidelines, or violate the Code of Conduct, after several rounds of mediation and/or complaints.

===== Proposal =====

==== Code of Conduct ====

This RFC proposes for the PHP project to adopt [[http://contributor-covenant.org/|version 1.3.0 of the Contributor Covenant]] as a Code of Conduct.

=== Code of Conduct Text ===

Contributor Code of Conduct

As contributors and maintainers of this project, and in the interest of
fostering an open and welcoming community, we pledge to respect all
people who contribute through reporting issues, posting feature
requests, updating documentation, submitting pull requests or patches,
and other activities.

We are committed to making participation in this project a
harassment-free experience for everyone, regardless of level of
experience, gender, gender identity and expression, sexual orientation,
disability, personal appearance, body size, race, ethnicity, age,
religion, or nationality.

Examples of unacceptable behaviour by participants include:

  * The use of sexualized language or imagery
  * Personal attacks
  * Trolling or insulting/derogatory comments
  * Public or private harassment
  * Publishing other's private information, such as physical or electronic addresses, without explicit permission
  * Other unethical or unprofessional conduct

Project maintainers have the right and responsibility to remove, edit,
or reject comments, commits, code, wiki edits, issues, and other
contributions that are not aligned to this Code of Conduct, or to ban
temporarily or permanently any contributor for other behaviours that they
deem inappropriate, threatening, offensive, or harmful.

By adopting this Code of Conduct, project maintainers commit themselves
to fairly and consistently applying these principles to every aspect of
managing this project. Project maintainers who do not follow or enforce
the Code of Conduct may be permanently removed from the project team.

This Code of Conduct applies both within project spaces and in public
spaces when an individual is representing the project or its community.

Instances of abusive, harassing, or otherwise unacceptable behaviour may
be reported by contacting a project maintainer at codeofconduct@php.net. 
All complaints will be reviewed and investigated and will
result in a response that is deemed necessary and appropriate to the
circumstances. Maintainers are obligated to maintain confidentiality
with regard to the reporter of an incident.

This Code of Conduct is adapted from the Contributor Covenant
(http://contributor-covenant.org), version 1.3.0, available at
http://contributor-covenant.org/version/1/3/0/

=== Website Page ===

A page will be created on php.net at //php.net/codeofconduct// that will display the actual language of the code of conduct used above: [[http://contributor-covenant.org/version/1/3/0/code_of_conduct.md|Code Of Conduct]]

==== Constructive Collaboration Guidelines ====

This section presents a loose collection of guidelines that focus on encouraging constructive feedback on language proposals (RFCs). RFCs are  used to introduce new features into the language. Currently, too little time is focussed on improving RFCs; instead a lot of effort exists to torpedo RFCs, attack suggestions and opinions. The point of the RFC process to to **improve** PHP — and the RFCs themselves.

Below are several suggestions:

  * In general, don't send more than one post per hour about a single topic. Do not "rapid-fire" reply to the active topic, but instead take the time to compose and edit the reply containing all the information you wanted to convey.
  * Write clear and unambiguous prose. It is better to be descriptive than to be concise.
  * Write as much as is necessary, but as little as you can get away with. 
  * Suggest improvements to the RFC, don't just shoot it down. When disagreeing, provide substantial reason instead of just saying "no". Try to outline specific points you disagree with and suggest ways of improvement. And remember, you can suggest improvements to an RFC even if you would not vote to support the RFC.
  * Don't use hyperbole to defend your arguments.
  * Don't send a "quick email", especially during a heated debate.
  * Think before you send "reply". Consider how the other party is likely to feel with the content. And, how you would feel if the same text was directed at you. Emotions are important and difficult, especially when you have never met in person.
  * Debate the technical issues, and never attack a person's opinion. People will disagree, so be it.

=== Website Page ===

A page will be created on php.net at //php.net/collaboration-guidelines// that will display the collaboration guidelines as described above.


==== Complaints procedure ====

=== Mailing List ===

A new mailing list will be created at //codeofconduct@php.net// for use in reporting incidents and discussing them internally. This mailing list will be private.

=== Process For Reported Incidents ===

In the event that an incident is reported the following process should be followed:

  * The Community Mediation Team is notified of an incident through //codeofconduct@php.net//
  * The Community Mediation Team should pick a case handler to deal with each specific incident
  * A team member shall document the issue as thoroughly as possible, researching any supporting materials necessary
  * A team member shall make contact with the accused transgressing party and document their side as much as possible
  * A team member shall make every reasonable attempt to mediate and defuse the situation without needing to resort to taking action against the accused

If all reasonable efforts to reach a mediated agreement fail and other action is deemed absolutely necessary as a last resort:

  * The team member makes a recommended course-of-action to the Community Mediation Team
  * The Community Mediation Team will vote internally on the recommended course-of-action (4/5 majority required to affect any action)
  * The Community Mediation Team shall report a redacted summary of the incident and the course-of-action to //internals@php.net//

At all steps the reporter(s) should be kept up to date on the process and recommendations that are made.

During the investigation the reporter(s) should respect the Community Mediation Team's workings, and the privacy of the accused offending party. For example, there should be no public shaming of the accused offending party, nor of the Community Mediation Team's way of handling things before a conclusion by the team is reached.

=== Confidentiality ===

All incidents are to be kept in the strictest form of confidentiality. The Community Mediation Team shall be the only group to know about the reporter and the precise details of any incident. Any communication outside of the team (including fact-finding, investigation, documentation, etc.) shall not include identifying information as to the reporter unless agreed by the reporter or is otherwise public.

Additionally, reasonable attempts shall be made as to the confidentiality to the accused person. This includes transparency reports where no significant action is taken (due to lack of evidence or that the Community Mediation Team determines it wasn't significant enough to warrant action against the accused).


=== Reasonable Person Test ===

To determine if the incident is a violation or not, the Community Mediation Team shall use the [[https://en.wikipedia.org/wiki/Reasonable_person|Reasonable Person Test]]. 

The following four points shall be taken into account for any incident:

  * the foreseeable risk of harm their actions create versus the utility of their actions
  * the extent of the risk so created
  * the likelihood such risk will actually cause harm to others
  * any alternatives of lesser risk, and the costs of those alternatives

Additionally, it shall be assumed that both parties (the accuser and the accused) are acting as reasonable people until proven otherwise. This means that best intentions shall be assumed unless significant evidence to the contrary is found.

Note: reporting an incident does not absolve a person of the requirement to abide by the Code of Conduct. This means that the victim of harassment is not entitled to "harass back". 


==== Community Mediation Team ====

A team of 5 volunteers shall be assembled who will make up the Community Mediation Team.

The team shall consist of:

  * At least one person with commit karma to php-src
  * At least one person **without** any karma to php-src
  * At least one person with commit karma to php-documentation

As long as the preceding three seats are filled, by three different people, there is no karma requirement (wiki or otherwise) for the remaining two seats.

All team members will be elected by RFC vote (requiring 2/3 majority). 

There is no specified term limit, but if either the PHP project or the other members of the Community Mediation Team feel that a specific member is not doing their job, they can be removed by an RFC vote (requiring 50% + 1 to support removal).

=== Transparency ===

Any action taken by the Community Mediation Team shall be reported to internals@php.net, including a summary of the incident and the action taken. The summary of the incident should include supporting evidence and justification for the decision.

Reasonable efforts should be taken to ensure the privacy of the reporting party. The only two exceptions are if the incident was public or if the reporting party agrees to be identified. 

Additionally, once per quarter (every 3 months), the Community Mediation Team shall produce an aggregated report as to the number of times incidents were reported, and the outcomes of the incidents, even if no action was taken.

==== Potential Actions ====

The intention is that nothing in this section will ever be needed. In extreme cases, when the Community Mediation Team finds that a certain project member continues to violate either the Code of Conduct or Constructive Contributing Guidelines, more action **might** be required.

The Community Mediation Team should make every reasonable attempt to defuse the situation without having to resort to action against the accused. This includes establishing a meaningful discussion around the incident, giving the accused transgresser the chance to apologize (privately or publicly, depending on the incident) or determining that no action is necessary even if the Code of Conduct was violated.

In the event that action is required, it may include:

  * Reverting or editing existing commits
  * Rejecting pull requests
  * Reverting or rejecting wiki edits, issues and other contributions
  * Issuing a temporary ban (no more than 7 days)

If the Community Mediation Team (with 4/5th majority as described above) determines that additional action is required, an RFC to the general project is created. Once the RFC is issued, the original temporary ban's lifetime will be tied to the RFC's lifetime (will expire when the vote is finished). All additional action RFCs will require 2/3 majority to affect the ban. However, the original temporary ban shall not include the //internals@php.net// mailing list, provided that the accused party remains civil and reasonably within the Code of Conduct to ensure that they receive a fair representation during the ban discussion.

Additional action may include removal of commit karma, mailing list write access as well as disabling of the associated PHP.net account. Depending on the particular infraction, one, many or all access may be suspended.

A new address/account which is believed to be used by an already banned individual does not require a RFC to effect provided there is reasonable evidence to support the correlation.

Bans (temporary or permanent) should only be used in egregious cases where a pattern of disregard for the Code of Conduct is demonstrated.

=== Appeals ===

Either party may appeal an action by raising the concern to internals@php.net. PHP project members may then vote to overturn or strengthen the action as necessary (votes require 50%+1 to overturn, and 2/3 majority to strengthen the action).

It is worth noting that this may be used as a technique to attempt to disclose the reporter to make them the subject of public scrutiny. Therefore reasonable attempts at confidentiality should be maintained, and the teams (Community Mediation Team and PHP project members) should keep this in mind. 

==== Additional Sections ====

=== Conflict of Interest ===

In the event that a Code of Conduct violation is reported against a Community Mediation Team member, the remaining members shall investigate and raise the concern to internals@php.net, even if they determine no action is to be taken. 

=== Accountability ===

The PHP project voting body has the right to overturn any action taken the Community Mediation Team by vote (50% + 1 required to overturn).

=== Updating Code Of Conduct ===

Any changes to the text of the Code of Conduct, or updating the version of it shall require an RFC with 2/3 majority voting. Any changes to the text of the Contributor Guidelines shall require an RFC with 2/3 majority voting.


===== Examples =====

==== "Representing The Project" ====

=== Activities on a php.net property ===

Activities on a php.net property shall always be considered "representing the project" and hence fall under the jurisdiction of the Code of Conduct and Community Mediation Team. This includes any php.net mailing list. 

=== Activities at a technology conference ===

While at a technology conference, the Code of Conduct is only considered to apply if and only if the person is demonstrably representing the project.

For example, merely speaking at a conference about PHP is not enough to be "representing the project". However, when speaking about the project itself (meaning internals functions, etc), while the talk is occurring the Code of Conduct shall apply.

This is not intended to limit the applicability of the Code of Conduct solely to the duration of the talk, however any violation that happens at a conference shall be assumed to **not** be representing the project unless there is significant and obvious evidence to the contrary.

=== Activities on a social network ===

On social networks, the Code of Conduct is only considered to apply if the context of the conversation makes it clear that the person represents the PHP project.

For example, merely having "PHP contributor" in an about or bio is not enough to be "representing the project". However, a conversation about the PHP project itself (including RFCs, etc) is enough to justify "representation".

=== Other ===

In all cases, if an issue seems reasonably connected to a project matter, the Code of Conduct may apply depending on how strongly the connection is.

For example, if one person is involved in a heated discussion on internals@, and then immediately after starts harassing another participant on another channel with similar tone, the harassment may be considered a violation.

In no case should a casual connection be considered a violation (just because two people are both members of the project is not enough to form a connection).


===== Initial Community Mediation Team =====

This RFC will include a vote for the initial Community Mediation Team. A separate thread will be opened asking for volunteers. 

===== Vote =====

This RFC requires 2/3 majority to pass, as it has a significant impact on the community and project operations.

===== Changelog =====
  * 0.1 - Initial Draft
  * 0.2 - Move to 2/3 majority
  * 0.3 - Significant expansion of the RFC
  * 0.4 - More significant expansion, adding examples
  * 0.5 - Focus more on mediation than punishment. Rename the Conflict Resolution Team to Contributor Mediation Team. Reshuffle content. Added Constructive Collaboration Guidelines.
