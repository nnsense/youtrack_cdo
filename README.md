YouTrack "Cloud Dev Ops" templates, useful for Cloud Engineering teams using Youtrack to manage their requests.<br>
I've been working for a company where YouTrack was used to manage projects, and for DevOps ticketing.<br>
YouTrack isn't really a good choice, it is a "bug tracking tool", not a proper ticketing system.<br>
Because of that, I've developed a couple of workflows to help us making YT a bit more useful.<br>

**NOTE**: This modules have been developed and used on **YouTrack 2018.2 (Build 43208)**, I'm not entirely sure they would work on any other version but, since
      the syntax didn't change that much, you can probably adapt them for your version. If you do that, please share it with me :).

### Modules:

**cdo_deployments**: This is a template to force a description if a field "Deployment type" is chosen. Note that you need to create the field on YT before using this module. 

**cdo_restricted_assignee**: This module restrict the change of the Assignee field to the team itself. Prevent people to randomly assign the ticket, skipping our "traige" 

**cdo_send-to-slack**: This is forwarding any ticket (new or changed) to slack

**cdo_send-to-slack_new_comment**: Same as send-to-slack, this forward new comments instead.
