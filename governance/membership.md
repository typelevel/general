## Typelevel membership criteria and process

Typelevel has two levels of project membership: projects can have an "incubator member" status or a "full member"
status.

### Incubator membership

The intention is that the criteria for incubator status be quite lax, and a strong emphasis is placed on
the collective responsibility of Typelevel members for helping new incubatees move to full membership status.

1. There must be a consensus amongst the project's stakeholders that they want to join Typelevel.
2. The project must be willing to support the Typelevel code of conduct or something equivalent.
3. The project should be aiming to promote pure, typeful, idiomatic functional programming in Scala.
4. If the primary output of the project is software artefacts then it should aim to complement them with accessible,
idiomatic documentation.

The process for joining is as follows,

1. An issue must be created in this issue tracker proposing Typelevel membership for the project.
2. Criteria (1) and (2) should be verified.
3. Suitability of the project for joining Typelevel, and the suitability of Typelevel membership for the project,
should be discussed constructively.
4. If there are no unaddressed objections to the projects joining Typelevel after a period of one week, then it will
move into the incubator stage.

Note that,

+ The project does not need to be nominated by an existing Typelevel member.
+ At the time of joining, the project does not have to fully exemplify pure, typeful, idiomatic functional
programming. There is, however an expectation that it will aim to move in that direction during an incubation period.
Typelevel members are expected to encourage and help with that development.

### Full membership

In addition to the incubator criteria full member projects must satisfiy the following additional criteria,

* The project should exemplify pure, typeful, idiomatic functional programming. It should not be deeply rooted in
things such as side-effects and mutation - put differently, it should be fairly easy for those working in pure
functional code bases to bring in your library. Mutation and other side-effecting properties is not
strictly forbidden, but should have a good documented reason for doing so (e.g. performance, limitation of the
language, etc.).
* Documentation for the code should (a) exist (b) be machine checked so as to enforce all documentation is up to date.
* There must be at least one active maintainer of the project who will field pull requests, issues, questions, etc.
* There much be some versioning scheme that communicate binary and/or source compatibility.

The process for full membership is as follows,

1. An issue must be created in this issue tracker proposing full membership for the project.
2. The criterai listed above should be verified.
3. Suitability of the project for becoming a full member should be discussed constructively.
4. If there are no unaddressed objections to the projects full membership after a period of one week, then it will
become a full member.

Note that,

+ Full membership status implies a degree of endorsement of the project by the other full members of Typelevel.
+ The criteria listed above should be actively maintained and if they cease to hold and that isn't rectified with a
reasonable period then the projects membership might revert to incubator status or revoked.
