---
title: Outage in data center for phoenix

draft: false

# Full date: 2019-03-29 17:26:09
date: 2022-07-14 09:00:00

# Status: "resolved" | "in_progress" | "scheduled"
status: "resolved"

# This message will be taken out of the flow of events
# and displayed at top of page or below the header
# as long as its status is marked as in_progress
# pinned: (empty) | top | belowheader
pinned: 

# Duration for "scheduled" issues: Raw text, ie 5mn, 1h, 1 hour,..
duration:

# Max severity: will be displayed when issue is resolved, in the past events section
# Max_severity: ok | disrupted | down | monitoring | maintenance
max_severity: down

# Current severity: used for current issue display
# current_severity: ok | disrupted | down | monitoring | maintenance
current_severity: ok

# Full date: 2019-03-29 17:26:09
resolved_on: 2022-07-15 21:10:00

# Affected components, must use exact names defined in site config
affected:
  - Phoenix

# If set and the status is in_progress, this feed will be embedded
# in the event display. Leave empty for no Twitter feed.
# Possible URL formats:
# See:  https://help.twitter.com/en/using-twitter/embed-twitter-feed
#
# - Profile: Display public Tweets from any user on Twitter:
#    https://twitter.com/weeblrpress
#  
# - Likes: Show all Tweets a specific user has marked as likes.
#    https://twitter.com/TwitterDev/likes
#
# - List: Show Tweets from public Lists that you own and/or subscribe to.
#    https://twitter.com/TwitterDev/lists/national-parks
# 
# - Collection: Show Tweets from a curated collection.
#    https://twitter.com/TwitterDev/timelines/539487832448843776
#
# - Moment: Show Tweets from a public moment.
#    https://twitter.com/i/moments/625792726546558977
#
twitterFeed: 

# Enable Disqus commenting on this page. This will only works if 
# you added your Disqus identifier in the global config.yml file
# under the disqusShortname option.
# enabledDisqus: true | false
enableComments: false

## Do not change
section: issue

# Short code available in content to display current date
# in a short format. For instance for issue updates.

# {{< track "2019-03-26 15:31:06" >}}
# {{< track "" >}}

## Enter below issue description and subsequent updates if any
---
Update 7/25/22 at 9:10PM
Access has been restored to Phoenix. Please submit a ticket if you run into any issues.

Updated 7/15/22 at 11:56AM:
The cooling in the datacenter has recovered at this time. I am currently running the disk integrity checks as a precaution, and expect this to finish later this afternoon.


Original Message:
Phoenix storage will be unavailable as the data center where it is stationed has no cooling due a leak in the main campus chilled water loop near Ward Hall.  They do not have an expected repair, and this may linger through the weekend.   

This effects individuals that mount the following drives:

* K:  KSULDigitalProject
* L: digitalmonographs
* M: metadata
* N: CADS
* Q: DigitalProjectUsers (working directories)
* R:  home directories
* T: halefirearchives
* U:  uasc
* V:  butlerlab
