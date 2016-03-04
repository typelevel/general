Dave Gurnell's notes from the Governance Session at the Typelevel US Summit:

# Agenda

- Discussion about Typelevel's aims and purposes, decision making process, and general constitution
- Should there be a non-profit Typelevel coorporate entity?
- What are Typelevel's aims and purposes?
- How should we reach out to the wider Scala community?
- How can we be more diverse?
- Can/should Typelevel have a "group voice"?

# Discussion about Typelevel's aims and purposes, decision making process, and general constitution

Erik:

- We should be supporting the community who want to do principled FP in Scala.
- Lots of aspects: better documentation, support, codes of conduct, etc.
- Not making the best the enemy of the good... do everything in proportion to its importance.
- About incubator projects:
  - permissiveness is good
  - it's more important to let people in whose goals are aligned with Typelevel than having arguments about minutiae
  - avoid legal-style arguments about functional purity etc

Miles:

- One of Typelevel's goals should be to share ideas and code
  - We should aim to depend on each others' projects
  - Strive towards some sense of binary compatibility
- Need learning resources that are going to work for people

Miles:

- We need transparency to ensure we're representing peoples' opinions

Lars:

- We need processes in place for governance to make things transparent

Erik:

- If everyone here is in agreement about the main goals of Typelevel,
  we can more onto governance.

Chris Hodapp:

- We're lacking some types of documentation
- "Idiomatic and accessible learning resources and documentation"
  should encompass more than the docs we have
- "Accessible" should include putting stuff in easy-to-find locations

Person A (forgot their name -- apologies):

- Do we have requirements for licenses?

Lars:

- No. Not currently, although all libaries share a set of core licenses

Michael Pilquist:

- The first goal ("pure, typeful, functional programming in Scala")
  can be interpreted too strongly

Erik:

- Yes. I write a lot of impure code.
- We should qualify it so it's received in the right light.
  (TODO: Catch up with Erik about his precise phrasing... I missed it)

Lars:

- Stew: can you inform us how Debian works?

Stew:

- Debian operates completely in the open
- There is a dictator at the top in an elected position
- The top person delegates to autonomous committees
- The committees run things unless they're overridden by a
  heavyweight vote process (with GPG signing and so on)
- Votes are avoided unless really necessary because they're so heavy

- We've generally been pretty good about design.
- With Cats we've always invited people... anyone...
  to come with comments/requirements
- The only time we've taken a wrong turn is where
  we've tried to do things behind closed doors
- My main recommendation is that we
  publicise decisions widely and encourage feedback

Miles:

- That works well for code (an optimistic strategy,
  adding features to code and asking for feedback later)
- The problem with that approach for many non-technical decisions
  (e.g. negotiations with Lightbend / EPFL)
  is that some things have to be decided behind closed doors

Erik:

- Sounds like we're moving into the corporate voice agenda point here...
  let's step back for a minute
- Do people think we should in general make decisions with small teams,
  and only bring voting in when we need to?

Chris:

- It's possible to not have an official process for this kind of thing,
  but let that process form fluidly around specific problems.

Lars:

- A process I've used in the past involves time-limited discussion.
  Allow comments for two weeks, and then lock the thread and
  see if we can find consensus.
- Should we give project maintainers votes on Typelevel policy decisions?

Erik:

- We should open it wider than that.
  Anyone who has contributed to any project can have a vote.
- But we should have a rough consensus model in which we don't
  need to wait for everyone to vote to resolve an issue.

Stew:

- Agreed. We should set a very low bar -- involve more people.
  How about including people who have made SO posts about projects,
  i.e. people helping in that way as well as actually writing code?

(There's a general consensus here that we should involve anyone
 who is involved in some way.)

Miles:

- Ok - do we have enough here to form a process around this?

Chris Hodapp:

- We need to make this decision subject to the same decision making process.
  We need to ask the mailing list for comments on this decision.

Miles:

- Ok. Can someone raise an issue for this?

Dave Gurnell:

- We need a defined communication channel for governance proposals and decisions.
- Something persistent. Gitter is too transient.

Lars/Erik:

- Let's use Github issues/PRs against github/typelevel/general for decisions,
  and Gitter for discussion

Rob:

- We should kill the mailing list. No-one uses it any more.
- Can we raise a PR on the typelevel/general github to this effect?

Lars:

- I'll do that now.

Jon:

- Where do we use Gitter and where do we use Slack?

Miles:

- Slack is just for organising the Summits.
- For the Summits we needed to have private conversations about,
  e.g., programme selection.
- Nearly all other discussion should be on Gitter.



# Can/should Typelevel have a "group voice"?

Erik:

- What should the process be if people want to run a Summit?

Person B (forgot their name -- apologies):

- They should propose it, Typelevel should agree to it,
  and then they should be fairly autonomous.

Cody:

- What would the process be if there was a CoC violation?
  We can't have that conversation in the open.
- We need trusted individuals who people can go to.
- There are examples like: CoC violations at Summits,
  CoC violations on mailing lists, etc

Miles:

- A larger issue is... what if there's a larger problem
  with a Typelevel library, and we have to talk to the maintainers
  about the library's ongoing involvement with Typelevel?

Erik/Stew:

- Should we have an elected representative board?
- People without much power,
  but authorised to act on behalf of Typelevel
  and consult the community if the situation demands it?
- A group that people can go to to report violations,
  who are trusted to deal with things fairly.
- Board members will have to maintain confidentiality
  at the discretion of the persion reporting a CoC violation.

Cody:

- We already have that on the web site:
  Miles, Erik, Stew, and Cody are all named contacts.



# Should there be a non-profit Typelevel coorporate entity?

Miles:

- One main motivation for this is in organising Summits,
  where we need a bank account to run funds through.
- Should we set up an entity for this kind of thing?
  How do we pick what to do, how does it work?

Jon:

- Typically, in a charity situation, you'd have govenors.
  These aren't necessarily the same people running the organisation.

Miles:

- We're not talking about a charity, though.
  We're talking about a not-for-profit.

Stew:

- With Debian, there are Debian special interest groups that run in each country.
- Those companies run local events.
- There's also a company in the US called SPI who run events like the Summits.

(We're out of time here. We agree to continue this discussion on github/typelevel/general.)
