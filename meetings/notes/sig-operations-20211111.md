## Meeting Details

- **Date/Time:** November 11, 2021 @ 2pm PST
- **Location:** [Discord SIG-Operations Voice Room](https://discord.gg/79NRgDuhT4)
- **Moderator:** seapip
- **Note Taker** Finite_State

Attendees:

DMcP-Amazon
Finite_State
seapip
Sergio Rojas
Tony B
stramer

## Sig Updates

Maintainers have been added to the repo: @seapip, @stramer.
Sig/operations tag added to o3de repo.

## Meeting Agenda

- Potential issue discovered with Discord audio and video sharing.  Refer to thread `How to improve Discord screen...` in Discord channel #sig-ui-ux.
(Did not address item during meeting)

## Action Items

-  Investigate server default streaming settings.
- Request TSC guidance on sig scope. Specifically, whether and in what capacity the sig should address cross-cutting issues.
- Further charter refinements.

**Website Ownership**
Ownership of the o3de.org website and if sig-operations is responsible for any pieces. This is cross-cutting from sig-security about who is responsible for the security and frameworks used to host content.

Policy for RFC archiving
Policy for abandoned Github issues
Changes to Github autolabeling
DCO-Validation for additional operations
Long-Term credential management

**Automation of review and merge management on Github repos**
c/o @Stramer

We have a problem with community reviewing that's currently seriously affecting docs and will affect engineering eventually. Infrastructure issue with GitHub, caused between https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/approving-a-pull-request-with-required-reviews (PRs with required write/admin reviewers) and https://docs.github.com/en/organizations/organizing-members-into-teams/managing-code-review-assignment-for-your-team (round-robin assignment by org team). Codeowners must have WRITE permissions (https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners) which we cannot give to community memebers.

Summary:

Nobody who is a community reviewer can ever be auto-assigned, which is debatably an issue.
Nobody who is a community reviewer can get a green check to approve merge, meaning 2 write/admin privs MUST green check to pass.
