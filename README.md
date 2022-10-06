# A-Frame Community

THREE.js and WebXR are fast moving targets. A-Frame core necessarily must remain small to stay manageable. But many other components provide that provide critical functionality to the ecosystem often end up falling behind on maintanence. This ends up with an ecosystem of many fractured forks that have to be sorted through to get things working when updates happen.

This github org is a place to host community-maintained forks of popular projects. It works in conjunction with [aframe.wiki](http://aframe.wiki) to be a place for community stewardship of of the ecosystem. This org is just a collective of devs in the a-frame community who give a best effort at helping to keep stuff working. Pull requests are always welcome here!

## how we approach merge requests
Be more permissive/progressive with accepting code than strict about guarantees of reliability with every version; a priority is made on updating to stay current. Carefully verifying that nothing will break is hard, and takes a lot of work. The inability to verify this is often why people never get around to merging those requests. Here, to avoid the stagnation that can result from that approach, we instead focus on not falling behind.

Here's how we'll approach merge requests here:

- give it a solid look
- request a second look if it's complex
- ask the contributor to explain code if needed
- readability matters, but don't focus on style
- it's ok to suggest better ways to reformat code, but default to (1) accepting the request and co-authoring the change directly yourself or (2) making the change separately after their request or (3) pull requesting against the prettifier settings
- merge optimistically; if it later is found that it breaks something, fix it or revert it as needed
- encourage more contributions by making contributing a pleasant experience for the contributor if possible! we're grateful that others are trying to contribute their free work towards the common good

## handling disagreements
- add an auto-prettify hook that formats code consistently and eliminates the need for disagreements about style. If you think something is bad style, propose a pull request to the prettyfier that covers it
- if a maintainer wants to object to a pull request, they can request a one week period where the maintainers present can vote on it; simple majority wins

## adding repos
- if a release hasn't been made for >3 months or if a significant pull request has been ignored for >3 months, then we may consider adding a "community fork" here
- alternatively, an author may request their repo being added here if they want to pass on the maintenance burden
- stuff here makes it easier to find for the community, so if you want to stay as a primary maintainer but get extra help and visibility, that's also an option
- when we add a repo, we fork the _original_ project, then pull request forks and pr branches against the aframe-community fork and review/add them here
- when possible, the best option is to migrate the existing repo, to carry across existing issues and pr's

## adding maintainers
- an informal discussion among current maintainers may lead to an invitation to this org
- generally we invite those who have demonstrated themselves to have relevant competence, are good natured, and uphold the spirit of open source

## maintainer expectations
- there's no obligation to contribute anything; if you are available, great, if you're not, no problem--if you have availability in the future, you're welcome to jump back in
- be excellent and kind to each other and act in the spirit of this document and a good community steward

**Have your repo added here is a sign of appreciation and respect! It means you made something critical to the community, and that others are volunteering to make sure your code stays relevant and keeps being used.**
- we will list very clear credit to the original author and repo
- generally, we'll add the author as a maintainer to the repo; we'd of course love your expertise if you have the time and will to continue to contribute

## Contributors
- To allow things to go smoothly, please [allow maintainers to edit](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/allowing-changes-to-a-pull-request-branch-created-from-a-fork) your PR fork.
