## Sprints/Milestones
We have weekly sprints and therefore weekly milestones. Every monday, we have a sprint meeting, where we plan and discuss the next weeks sprint. A sprint, starts after the sprint planning meeting and ends before the next sprint planning meeting. So this means sprints go from Monday to Monday. 

## Product Development Pipelines
### New
All issues that are created enter the New pipeline. This pipeline should be cleared out after our weekly product standup meeting.

### Icebox
These are issues that don’t have a home. They are low priority issues that we want to get to in the future. We should not work on these issues and they should not take up any of our resources.
 
### Backlog
This is the new “ready”. Items in backlog are the current milestones’ focus. Product standup meetings should fill this pipeline. Sometimes while working on Backlog issues, we derive new issues as requirements to complete a Backlog Issue — those should be placed in Backlog.

Although it’s possible to derive new issues, we shouldn’t make this a habit because it skews the current milestone and means we didn’t spec backlog enough in the first place. Do this sparingly. If this becomes an issue then we need to spend more time planning.

### In Progress
This is what is in work by collaborators. This is our highest priority and where our focus should be.
 
### QA/Review
This is where an issue is code reviewed and checked in a production-like environment. For now, a local environment is ok. But in the future, staging environments will be required as a last line of defense before code is deployed to production.

If an issue fails any check, we push the issue back in to progress.

### Closed
The issue has passed QA/Review and meets requirements. Done.
