# mastodon-administration

This repository is intended as a **PLACEHOLDER** for http://www.mastodonadmin.com/ and primarly used to structure the data.

## Language and conduct

Lets keep it in the spirit of Mastodon and be inclusive and safe.
I suggest we use the <https://github.com/mastodon/mastodon/blob/main/CODE_OF_CONDUCT.md> as a starting point.

## Audiance 

What do we know from our audiance?
Which level do they have?
What do they intend to do?

> **NOTE**: The levels are just a grouping mechanism and they start with assuming the reader has no knowledge. But other than that it's just a list of things that required explenation

- Level 0: Never heard about mastdon or Fediverse
    - Level 0A: No prior knowledge about social media
    - Level 0B: Familiar with social media
    - DevWouter: I'm a bit conflicted whether or not we should target this group because of the sheer amount of knowledge and skills "administering a mastodon server" requires. On the otherside I don't want to gatekeep.
- Level 1: Familiar with Mastodon, but no administration or moderation background
    - Possible goal: Teach basic fediverse background
    - Possible goal: Teach basic security (SSH, 2FA, HTTPS, DNS-security)
    - Possible goal: Teach setup own server (hosting, DNS, tell them what they should expect cost-wise)
    - Possible goal: Teach moderation (What about complex social situation?)
        - Maybe get inspiration from <https://discord.com/moderation>?
    - Possible goal: Teach basic administration (mail, spam, memory management, limiting signup, diagnostics, tootctl, et cetera)
    - Possible challange: Each environment is different (CPU/IO/Memory bound, different S3 stuff, different mail providers, et cetera)
    - Possible goal: How to verify your new instance is working?
    - (Do we want tutorials) 
- Level 2: Familiar with Mastodon and administration background
    - Possible goal: Teach updating
    - Possible goal: Teach how to scale up/down (docker, kubernetes, etc)
    - Possible goal: Teach how to handle large scale spam, doxxing
    - Possible goal: Teach how to create a crew
    - Possible goal: Teach how to handle the finance side (how to handle donations, most likely need to include some law/tax stuff)
    - Possible goal: Teach exit-strategy
    - Possible goal: Teach basic
    - Subject: Announcements
    - Subject: Emojis
    - Subject: Server rules
- Level 3: Advanced moderation
    - Possible goal: How to handle spam reports from other servers
    - Possible goal: How to improve performance (sidekiq)
    - Possible goal: Invites, Trends, blocking IP, blocking domains, helping the users
    - Possible goal: Audit the moderation
    - Possible goal: What to backup? When to backup? Where to backup?
    - Possible goal: What to restore? When to restore? Where to restore?
    - Possible goal: Recovering from fatal
    - Subject: Webhooks
    - Subject: Relays
    - Subject: Searching all content (elastic search)
    - Subject: Tor
- Level X: Customization
    - Styling

