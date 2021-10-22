
## Meeting Details

- **Date/Time:** Month Date, Year @ 9:00pm UTC / 5:00pm ET
- **Location:** [Discord SIG-Operations Voice Room](https://discord.gg/79NRgDuhT4)
- **Moderator:** Finchy
- **Note Taker** lmbr-pip (Pip)

## SIG Updates

**What happened since the last meeting?**
- No updates given, due to break

## Meeting Agenda
[Agenda](https://github.com/o3de/sig-operations/issues/17)

* Future meetings, time ranges, Frequency
* Public Assets and downloads
* Update on Discord Partner status
* YouTube Channel Update (URL)
* Update on Branding Kit
* SIG Charter update
* Ownership of o3de.org Website inc Documentation search support, robots.txt management
* Automation of review and merge for Github repos

**Discuss agenda from proposed topics**

## Outcomes from Discussion topics

Future Meetings:
* Aim to hold more regular meetings.
* Vote is to keep every other Thursday 2pm for now

Public Assets for Download
* Where can we store assets?
* sig-docs-community Have someone setting up an assets repro currently. 
    - owner will be #sig-docs-community
    - Expect update on data by Oct 29th

Q: Are downloadable assets in scope for SIG
	- no, owned by #sig-docs-community as its content.

Discord partner Application (Discord Perks)
- Managed by Royal as he's the admin owner of O3DE on discord
- Declined by Discord for unknown reasons, need to return and re-apply in 90 days
- Can then have custom invite banners and custom urls to invite folks to O3DE.

Q: Does the sig-ops have power to manage Discord?
- Don't need to go to Royal for everything, we can raise with maintainers and Royal when required

YouTube Channel Update (URL)
Q: Can we change the url to get a vanity url for the You Tube Channel?
- We do have one but it only shows on certain routes: https://www.youtube.com/c/Open3DEngine. Seems to be YouTube issue as to when channel name vs id is used.
Q: Do we use the vanity url in docs and other places we own?
- Unsure, buy seems so


Branding Kit
- If users want to publish their own video, useful to have common branding assets?
- Should be owned by marketing committee and sig-docs-community
- Action Item: To followup with channels


Charter Discussion
(includes discussion on search, robots.txt etc)

What is in scope for the SIG?
Operations is dedicated to the operation and integration of tools to run github/discord/groups and other related community tools. It is not related to engine code.

The aim of operations is to own and create automations that remove monotony of repeatable tasks, includes:

* YouTube is owned by an "infrastructure group". Content is responsibility in sig-docs-community
* Discord
* Discord Bots
* Issue manipulation such as GitHub actions
* Any automation not tied to code/builds

Are we responsible for website? No
- Is it sig-docs-community? WHo owns the infrastructure?
- Infrastructure is mostly owned by build so stack is owned
	- Netlify manages the stack currently, who owns the management? #sig-build owns access to the stack.
- Docs community owns content on the stack 
- Seems cross-cutting with sig-docs-community 

Instance management for automation is cross cutting with #sig-build 
- If infra management is to much for #sig-build then that would need to be revisited.

Who handles the plugins for GitHub like DCO
- would be under the remit of #sig-operations

Should code for the website live under sig-docs?
- Anything that runs on the website such as search integration, javascript widgets
- Not a sig docs issue as not related to content.
- Functionality or tools to manipulate content could be #sig-operations

Would this include the management of robots.txt - its config file but not a tool
- Seems like this maybe cross-cutting with #sig-build as this is configuration
- sig-build is responsible for making the change 

Automation review and management of GitHub repros?
* Need to make RFC for this
* Are there tools for this? Assume this part of the RFC.

Contributions to tools will help flush out the charter.


## Action Items

* Followup with marketing etc about branding kits (finchy)
* Schedule future meetings and add to O3DE calendar (finchy)
* Get update for assets repro (next meeting (stramer [Amazon]))
* Need to update issues templates for SIG. Meeting agenda template had SIG-BUILD as title. See https://github.com/o3de/sig-operations/blob/main/.github/ISSUE_TEMPLATE/Meeting-Agenda-Template.md and theres no standard maintainer promotion issue template ie https://github.com/o3de/sig-core/blob/main/.github/ISSUE_TEMPLATE/Reviewer_Maintainer_Nomination.md (DMcP-Amazon)
* Create a discussion thread for charter updates to aid discussion (lmbr-pip)
* Folks to bring issues / RFCS for automation tools now that meetings are established (community)

## Open Discussion Items

Are we responsible for processes? 
- For example RFCs archiving. No thats is a TSC governance issue 

Do we need public triage process? 
- Will triage issues in public SIG meeting due to low volume. Will revisit as volume/needs increase.

