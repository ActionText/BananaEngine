# Contributing Guidelines

This document summarizes the most important guidelines for contributing to BananaEngine, whether you are reporting bugs, proposing improvements, submitting pull requests, improving documentation, or contributing to Lunana.

BananaEngine is a project that values quality over quantity. Contributions are reviewed carefully, and contributors are expected to take the time to understand the project, follow its conventions, and submit work that is useful and maintainable.

For more detailed information, see the [BananaEngine Contributing Documentation](https://bananaengine.dev/docs/contributing).

## Table of contents

* [Before contributing](#before-contributing)
* [Reporting bugs](#reporting-bugs)
* [Proposing features or improvements](#proposing-features-or-improvements)
* [Contributing pull requests](#contributing-pull-requests)
* [Code quality](#code-quality)
* [Commits](#commits)
* [Documentation](#documentation)
* [Testing](#testing)
* [Communicating with developers](#communicating-with-developers)
* [Contributors and future projects](#contributors-and-future-projects)

## Before contributing

Before making a contribution, please take the time to understand how BananaEngine works.

Read the relevant documentation, inspect existing implementations, and look at how similar systems are structured before proposing or implementing major changes.

Contributions should be made with the long-term health of the project in mind. A change that works today but makes the engine harder to maintain tomorrow is not considered a successful contribution.

If you are unsure about an approach, discuss it with the developers before spending significant time implementing it.

## Reporting bugs

Bug reports should be submitted through the
[BananaEngine issue tracker](https://github.com/bananaengine/bananaengine/issues).

Before opening an issue, make sure that the problem is reproducible on the latest version of BananaEngine whenever possible.

A useful bug report should include:

* A clear description of the problem.
* Steps required to reproduce it.
* The BananaEngine version being used.
* The platform and relevant environment information.
* Expected behavior.
* Actual behavior.
* A minimal reproduction project or example when applicable.
* Relevant logs, error messages, or screenshots.

Please avoid submitting issues that only contain statements such as "it doesn't work." The more accurately an issue can be reproduced, the easier it is to investigate and fix.

If the issue is a regression, please mention which version worked and which version introduced the problem.

## Proposing features or improvements

Feature proposals should be discussed before significant implementation work begins.

A good proposal should explain:

* What problem the feature solves.
* Why the problem is important.
* How the proposed feature would be used.
* Why the proposed approach is preferable to existing functionality.
* Any potential drawbacks or compatibility concerns.

Not every proposed feature will be accepted.

BananaEngine is intentionally selective about what becomes part of the engine. Features should have a clear purpose and should fit the project's overall design rather than being added simply because they are technically possible.

## Contributing pull requests

Pull requests should contain focused, deliberate changes.

Before submitting a pull request:

1. Make sure the change is actually needed.
2. Discuss significant changes with the developers beforehand.
3. Test the changes thoroughly.
4. Make sure existing functionality has not been unnecessarily affected.
5. Update documentation where appropriate.
6. Keep unrelated changes out of the pull request.

Large changes should generally be divided into smaller, logically independent contributions when possible.

A pull request may be rejected, requested for substantial changes, or closed if its implementation does not meet the project's standards, even if the feature itself is useful.

A contribution does not need to be accepted simply because significant work was put into it.

## Code quality

Code submitted to BananaEngine should prioritize:

* Correctness.
* Readability.
* Maintainability.
* Consistency with existing code.
* Appropriate performance.
* Clear ownership of responsibilities between systems.
* Minimal unnecessary complexity.

Avoid introducing abstractions without a clear reason.

Avoid copying large amounts of existing code when a reusable solution would be more appropriate.

Avoid temporary solutions being submitted as permanent implementations.

If a section of code is difficult to understand, improve the implementation or document the reasoning behind it rather than assuming future contributors will figure it out themselves.

BananaEngine is expected to grow over time. Code should therefore be written with future maintenance in mind.

## Commits

Commits should represent meaningful, stable changes.

Keep commits focused on a single logical change whenever possible.

Commit messages should be concise and descriptive.

A typical commit should begin with an imperative verb, such as:

* `Add texture streaming`
* `Fix physics synchronization`
* `Improve Lunana error reporting`
* `Update editor documentation`
* `Remove deprecated API`

Avoid commits with vague messages such as:

* `update`
* `fix`
* `changes`
* `stuff`
* `working now`
* `final`
* `final 2`

Do not use a series of commits to gradually fix problems that could have been resolved before opening the pull request.

Before submitting a pull request, review your commit history and clean up unnecessary commits when appropriate.

## Documentation

Changes to public APIs, engine systems, editor functionality, Lunana APIs, or other developer-facing functionality should include corresponding documentation.

Documentation should be:

* Accurate.
* Clear.
* Consistent with the existing documentation.
* Written for the intended audience.
* Updated whenever behavior changes.

If a change introduces a new API, explain what it does, how it should be used, and any important limitations.

If an implementation is non-obvious, comments may be appropriate. Comments should explain why something is done rather than simply restating what the code does.

## Testing

Contributors are expected to test their changes before submitting a pull request.

Bug fixes should include a test that verifies the problem has been resolved whenever practical.

New functionality should include appropriate tests where the relevant testing infrastructure exists.

Tests should cover both expected behavior and important failure cases.

A contribution that introduces a regression may be rejected even if the new functionality itself works correctly.

Testing is particularly important for changes to core engine systems, serialization, scripting, physics, rendering, networking, and other systems that can affect large portions of the engine.

## Communicating with developers

For significant changes, feature proposals, architectural discussions, or questions about implementation, use the official
[BananaEngine community channels](https://bananaengine.dev/community).

When discussing a potential contribution, provide enough technical information for others to understand the problem and proposed solution.

Disagreements are expected during technical discussions. Keep discussions focused on the implementation and the project rather than the people involved.

Good technical criticism is welcome. Personal attacks, hostility, or deliberately disruptive behavior are not.

## Contributors and future projects

BananaEngine is being developed with the intention of growing beyond a single project.

Contributors who consistently demonstrate strong technical ability, good judgment, reliability, communication, and attention to detail may be considered for additional opportunities within the BananaEngine ecosystem.

As the project grows, contributors may be invited to participate in larger projects, private development efforts, experimental systems, or other projects associated with BananaEngine.

Contributing does not guarantee an invitation or position.

Selection for these opportunities is based on the quality and consistency of a contributor's work, their ability to collaborate effectively, their understanding of the project, and the level of trust they have established with the development team.

You do not need to contribute a large quantity of code to be noticed. A small, exceptionally well-designed contribution is more valuable than a large number of low-quality changes.

## Final notes

There is no expectation that every contributor will know everything about BananaEngine.

What matters is the willingness to learn, understand the existing systems, ask useful questions, accept feedback, and improve the quality of the project.

Take your time. Review your work before submitting it.

Quality contributions are valued, and contributors who consistently meet the project's standards will have opportunities to take on greater responsibilities as BananaEngine develops.

Thank you for your interest in contributing to BananaEngine.

— The BananaEngine development team
