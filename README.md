# A-Frame Community

THREE.js and WebXR are fast moving targets. A-Frame core necessarily must remain small to stay manageable. But many other components provide that provide critical functionality to the ecosystem often end up falling behind on maintanence.

This profile is a place to host community-maintained forks of popular projects. 

## guiding principle
Be more permissive/progressive with accepting code than strict about guarantees of reliability with every version; a priority is made on updating to stay current. Carefully verifying that nothing will break is hard, and takes a lot of work. The inability to verify this is often why people never get around to merging those requests. We're trying to be an answer to that problem.

## how we approach merge requests
- give it a solid look
- request a second look if it's complex
- ask the contributor to explain code if needed
- readability matters, but don't focus on style
- it's ok to suggest better ways to reformat code, but default to (1) accepting the request and co-authoring the change directly yourself or (2) making the change separately after their request or (3) pull requesting against the prettifier settings
- merge optimistically; if it later is found that it something, fix it or revert it as needed

## handling disagreements
- add an auto-prettify hook that formats code consistently and eliminates the need for disagreements about style. If you think something is bad style, propose a pull request to the prettyfier that covers it. 
- if a maintainer wants to object to a pull request, they can request a one week period where the maintainers present can vote on it; simple majority wins

## adding repos
if a release hasn't been made for >3 months or if a significant pull request has been ignored for >3 months, then we may consider adding a "community fork" here. Alternatively, an author may request their repo being added here if they want to pass on the maintenance burden; likewise, even an active repo can be added here if the author is open to it and it's agreed that it is significant to the community.

**Have your repo added here is an honor! It means you made something critical to the community, and that others are volunteering to make sure your code stays relevant and keeps being used.**
- we will list very clear credit to the original author and repo
- generally, we'll add the author as a maintainer to the repo; we'd of course love your expertise if you have the time and will to continue to contribute
