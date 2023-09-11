# Ibis project governance

Ibis's governance is inspired by many open source projects that have come
before it, including but not limited to Apache Arrow, Substrait, Dask and
many others.

The closest concrete model to Ibis's governance is the [**liberal contribution** model](https://opensource.guide/leadership-and-governance/#what-are-some-of-the-common-governance-structures-for-open-source-projects).

A major point in that model is:

> the people who do the most work are recognized as most influential, but this
> is based on current work and not historic contributions.

Another important point from that model is:

> Major project decisions are made based on a consensus seeking process
> (discuss major grievances) rather than pure vote, and strive to include as
> many community perspectives as possible.

In addition to the people that work on the Ibis project, the project's
artifacts are the code and documentation that reside in the collection of git
repositories under the `ibis-project` GitHub organization.

## People

The following categories are loose categories of people involved with the Ibis
project.

These categories are not mutually exclusive.

### Users

Users are people using Ibis.

### Contributors

A contributor is someone who contributes code or documentation to the project.
The primary way someone contributes these artifacts is through GitHub Pull
Requests.

After a period of time, contributors are eligible to become committers.

### Committers

A committer is someone who has the ability to make commits to the project
without the approval of other committers or steering committee members, which
includes the ability to approve and merge pull requests.

To become a committer, a person must show sustained activity for a period of at
least six months and be nominated by a steering committee member.

Committers are responsible for things like:

- Code review
- Ensuring that CI remains green
- Helping on board contributors
- Maintaining existing code

Committers who have made a commit to one or more repositories under the
`ibis-project` organization for a period of one year or longer are subject to
having their commit privileges removed.

### Steering committee members

A steering committee member is a committer that shows commitment to the
long-term health of the Ibis project. In addition to the responsibilities of
committers, committee members are responsible for things like:

- Nominating others for steering committee membership status
- Code review
- Handling security reports in a timely manner
- Enforcing the code of conduct
