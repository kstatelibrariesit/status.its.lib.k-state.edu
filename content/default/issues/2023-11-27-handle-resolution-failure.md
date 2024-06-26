---
title: Handle Resolution Failure

draft: false

# Full date: 2019-03-29 17:26:09
date: 2023-11-27 08:30:00

# Status: "resolved" | "in_progress" | "scheduled"
status: "resolved"

# This message will be taken out of the flow of events
# and displayed at top of page or below the header
# as long as its status is marked as in_progress
# pinned: (empty) | top | belowheader
pinned: 

# Duration for "scheduled" issues: Raw text, ie 5mn, 1h, 1 hour,..
duration: 30 minutes

# Max severity: will be displayed when issue is resolved, in the past events section
# Max_severity: ok | disrupted | down | monitoring | maintenance
max_severity: disrupted

# Current severity: used for current issue display
# current_severity: ok | disrupted | down | monitoring | maintenance
current_severity: disrupted

# Full date: 2019-03-29 17:26:09
resolved_on: 2023-11-27 12:55:00

# Affected components, must use exact names defined in site config
affected:
  - K-REx

twitterFeed: 
enableComments: false

## Do not change
section: issue

# Short code available in content to display current date
# in a short format. For instance for issue updates.

# {{< track "2019-03-26 15:31:06" >}}
# {{< track "" >}}

## Enter below issue description and subsequent updates if any
---
Currently the SSL Certificate for hdl.handle.net has been revoked, so some browsers are stopping access to the the site. This impacts both K-REx and any site that utilizies the Handle Service from CNRI.

We have reached out to their support, and are waiting for a response.

> This is resolved.  We haven't yet finalized the root cause analysis, but the most likely explanation is a mistake made by us while requesting a new certificate, which had been scheduled for update early in December.  We apologize for the inconvenience.
