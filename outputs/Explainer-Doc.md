# Slack Training: A Comprehensive Guide for New Users

## What is Slack?

Slack is a cloud-based collaboration and communication platform designed to replace email and facilitate team communication. It brings all your team's conversations, files, and tools together in one organized workspace, making it easier to stay connected and productive.

**Key Benefits:**
- Reduces internal email by up to 60%
- Creates searchable message history (unlike deleted emails)
- Enables real-time collaboration across distributed teams
- Integrates with 2,000+ third-party apps and tools
- Provides organized, topic-centered discussions through channels

---

## Core Terminology

### Workspace
- A dedicated space for your organization where all communication happens
- Each company typically has one primary workspace
- You can be a member of multiple workspaces (e.g., your company, industry groups, partner organizations)
- Access your workspace via URL: `yourcompany.slack.com`

### Channels
**Public Channels** - Open to everyone in the organization
- Visible in the channel list for all members
- Promotes transparency and knowledge sharing
- Example: `#general`, `#marketing`, `#engineering`

**Private Channels** - Limited access, invitation-only
- Only visible to channel members
- Used for sensitive discussions or specific project teams
- Indicated by a lock icon 🔒

**Shared Channels** - Connect your workspace with external organizations
- Collaborate with clients, partners, or vendors
- Maintain security while enabling external communication

### Direct Messages (DMs)
- Private one-on-one conversations between two people
- Not visible to others in the workspace
- Can also create Group DMs (up to 9 people total)

### Threads
- Organized replies to a specific message
- Keeps conversations focused and reduces channel noise
- Prevents disruption of the main channel conversation
- Only thread participants receive notifications about new replies

### User Groups
- Collections of users organized by role, department, or project
- Mention entire group at once (e.g., `@marketing`, `@developers`)
- Available on paid plans only

---

## Essential Features

### 1. Messaging Basics

**Sending Messages:**
- Type in the message box at the bottom of any channel or DM
- Press `Enter` to send (or enable Send button in preferences)
- Use `Shift + Enter` to create a new line without sending

**Formatting Options:**
- **Bold**: Surround text with `*asterisks*` or press `Ctrl/Cmd + B`
- *Italic*: Surround text with `_underscores_` or press `Ctrl/Cmd + I`
- ~~Strikethrough~~: Surround text with `~tildes~` or press `Ctrl/Cmd + Shift + X`
- Create lists with bullets (*) or numbers
- Quote text with `>` for single lines or `>>>` for multiple lines

**Editing and Deleting:**
- Edit your last message: Press the `Up Arrow` key
- Delete messages: Hover over message → Click three dots → Delete
- Note: Edited messages show "(edited)" indicator

### 2. Mentions and Notifications

**Individual Mentions:**
- `@username` - Notifies a specific person
- They receive a notification even if they're not actively viewing Slack

**Group Mentions:**
- `@channel` - Notifies ALL members of a channel (use sparingly!)
- `@here` - Notifies only ACTIVE/ONLINE members of a channel
- `@everyone` - Notifies all members of #general channel

**Best Practice:** Use group mentions judiciously to avoid notification fatigue.

### 3. Search Functionality

Slack's powerful search helps you find information quickly:

**Basic Search:**
- Click search box (top right) or press `Ctrl/Cmd + F`
- Search across all messages, files, and channels you have access to

**Search Modifiers:**
- `from:@jane` - Find messages from a specific person
- `in:#marketing` - Search within a specific channel
- `has:link` - Find messages containing links
- `before:2024-01-15` - Messages before a specific date
- `after:2024-01-01` - Messages after a specific date
- `"exact phrase"` - Search for exact phrase in quotes

**Combine modifiers:** `from:@jane in:#sales after:2024-01-01`

### 4. File Sharing

**Upload Files:**
- Drag and drop files directly into Slack
- Click the `+` icon next to message box
- Share files from integrated cloud storage (Google Drive, Dropbox, etc.)

**File Management:**
- Preview files directly in Slack
- Comment on files in threads
- Star important files for quick access
- Download files by clicking download icon

### 5. Reactions and Emoji

**Emoji Reactions:**
- Quick way to respond without adding a message
- Hover over message → Click smiley face icon → Select emoji
- Shows who reacted when you hover over the emoji
- Common uses: ✅ (completed), 👀 (seen), 👍 (approved)

**Custom Emoji:**
- Add company-specific emoji for team culture
- Navigate to: Workspace name → Customize Slack → Add Custom Emoji
- Use for inside jokes, team traditions, or visual shortcuts

### 6. Pins and Stars

**Pinned Items:**
- Visible to ALL channel members
- Pin important announcements, guidelines, or resources
- Access pinned items: Click 📌 icon at top of channel
- Use for: Team guidelines, important links, reference documents

**Starred Items:**
- Personal bookmarks visible ONLY to you
- Star messages, files, or entire channels
- Access starred items: Click ⭐ icon at top right
- Use for: Personal to-dos, important references, follow-up items

### 7. Status and Availability

**Set Your Status:**
- Click your profile picture → Set a status
- Examples: "In a meeting", "Working remotely", "On vacation"
- Add emoji for visual indicator
- Set automatic clear time

**Availability Indicators:**
- 🟢 Green dot = Active
- ⚪ Gray dot = Away
- 🔴 Red icon = Do Not Disturb
- 📅 Calendar sync = In a meeting (with calendar integration)

### 8. Do Not Disturb (DND)

**Enable DND:**
- Click bell icon next to your name
- Select time period (30 min, 1 hour, until tomorrow, custom)
- Or use command: `/dnd 2 hours`

**DND Schedule:**
- Set automatic DND during off-hours
- Configure in: Preferences → Notifications → Notification schedule

---

## Slack Apps and Integrations

### What Are Slack Apps?

Apps extend Slack's functionality by connecting your other work tools and automating workflows. With 2,000+ apps available, you can centralize your work in Slack.

**Popular Integration Categories:**
- **Project Management**: Asana, Trello, Jira
- **Customer Relationship Management**: Salesforce, HubSpot
- **File Storage**: Google Drive, Dropbox, OneDrive
- **Video Conferencing**: Zoom, Google Meet
- **Productivity**: Standuply (standups), Polly (polls)
- **Analytics**: Google Analytics, Databox

### Installing Apps

1. Click `+` icon next to "Apps" in sidebar
2. Browse or search for app
3. Click "Install" or "Visit Site to Install"
4. Follow authorization steps
5. Configure app settings for your team

**Note:** Admins may restrict which apps can be installed. If unavailable, request access from your admin.

---

## Workflow Automation

### Slash Commands

Quick actions performed by typing commands in message box:

**Common Commands:**
- `/remind @user to [task] at [time]` - Set reminders
- `/dnd 30 minutes` - Enable Do Not Disturb
- `/msg @username [message]` - Send quick DM from anywhere
- `/mute` - Mute a channel
- `/archive` - Archive current channel
- `/leave` - Leave a channel
- `/collapse` - Collapse all images/videos in channel

### Reminders

**Set Personal Reminders:**
- `/remind me to [task] at [time]`
- Example: `/remind me to review report tomorrow at 9am`

**Set Team Reminders:**
- `/remind #marketing to submit reports every Friday at 5pm`
- Recurring reminders help with regular check-ins

### Workflow Builder

Create custom automated workflows (available on paid plans):
- Onboard new team members automatically
- Collect information via forms
- Send scheduled announcements
- Route requests to appropriate channels

---

## Voice and Video Communication

### Built-in Slack Calls

**Starting a Call:**
- **1-on-1**: Open DM → Click phone or video icon
- **Group/Channel**: Click phone icon at top of channel → Start call
- Supports up to 15 participants (paid plans)

**During a Call:**
- Share your screen for presentations
- Enable video on/off
- Mute/unmute audio
- Invite additional participants mid-call

**Screen Sharing:**
- Click "Share Screen" icon during call
- Select which window or entire screen to share
- Allow others to draw on your screen with pencil tool

### Third-Party Video Apps

Many teams integrate external video tools:
- **Zoom** - Full video conferencing
- **Google Meet** - Calendar-integrated meetings
- **Microsoft Teams** - Cross-platform video

These apps let you start video calls directly from Slack channels.

---

## Best Practices for Effective Communication

### Channel Organization

**Naming Conventions:**
- Use prefixes for easy sorting: `team-`, `proj-`, `feed-`, `temp-`
- Examples:
  - `team-marketing` - Marketing department channel
  - `proj-website-redesign` - Specific project
  - `feed-twitter` - Automated Twitter feed
  - `temp-holiday-party` - Temporary event planning

**Channel Purpose:**
- Always set a clear channel description/topic
- Helps new members understand channel intent
- Access via: Click channel name → Edit topic

**Default Channels:**
- Admins can set which channels new members auto-join
- Typically includes: #general, #announcements, department channel

### Communication Etiquette

**Use Threads:**
- Keep side conversations in threads, not main channel
- Reduces noise for others
- Click "Reply in thread" on any message

**Be Mindful of Mentions:**
- Use `@channel` and `@here` sparingly (emergencies only)
- Prefer `@username` for specific people
- Consider user groups for regular team notifications

**Response Expectations:**
- Slack is asynchronous - don't expect instant replies
- Use DMs for urgent matters
- Set DND when focusing on deep work

**Delete Link Previews:**
- Remove unnecessary link previews to reduce clutter
- Click X on preview after posting link

### Managing Notification Overload

**Custom Notification Settings Per Channel:**
1. Open channel → Click gear icon
2. Select "Notification preferences"
3. Choose:
   - All messages
   - Just mentions
   - Nothing (mute)

**Keyword Alerts:**
- Get notified when specific words are mentioned
- Settings → Notifications → My keywords
- Examples: your name, project names, critical terms

**Mobile vs. Desktop Settings:**
- Configure different settings for mobile devices
- Reduce mobile notifications to mentions/DMs only
- Allows focus time away from desk

**Activity Feed:**
- Click `@` icon (top right) to see all mentions and DMs
- Central place for notifications requiring attention
- Filters out channel chatter

### Organizing Your Sidebar

**Star Important Channels:**
- Click star icon next to channel name
- Starred channels stay at top of sidebar
- Quick access to frequently used channels

**Hide Channels:**
- Leave channels that aren't relevant to your work
- Mute channels you want to stay in but check infrequently
- Preferences → Sidebar → Show only starred and unread

**Sections:**
- Organize channels into custom sections (paid plans)
- Group by project, priority, or department

---

## Keyboard Shortcuts

Master these shortcuts to work faster:

### Navigation
- `Ctrl/Cmd + K` - Quick Switcher (jump to any channel/DM)
- `Ctrl/Cmd + T` - Open Quick Switcher (desktop app)
- `Alt/Option + ↑` - Previous channel
- `Alt/Option + ↓` - Next channel
- `Ctrl/Cmd + Shift + A` - View all unreads

### Messaging
- `Ctrl/Cmd + B` - Bold text
- `Ctrl/Cmd + I` - Italic text
- `Up Arrow` - Edit last message
- `Shift + Enter` - New line (without sending)
- `Ctrl/Cmd + /` - View all shortcuts

### Actions
- `Ctrl/Cmd + F` - Search current channel
- `Ctrl/Cmd + Shift + K` - Open DM menu
- `Esc` - Mark channel as read
- `Shift + Esc` - Mark ALL messages as read

---

## Real-World Use Cases

### 1. Daily Standup Meetings

**Traditional Way:**
- 15-minute in-person meeting every morning
- Time-consuming, especially for distributed teams

**Slack Way:**
- Create `#team-standup` channel
- Use Standuply bot or Slackbot reminders
- Each person posts daily:
  - What I did yesterday
  - What I'm doing today
  - Any blockers
- Asynchronous - respects everyone's schedule
- Searchable history of progress

### 2. Project Collaboration

**Scenario:** Website redesign project with designers, developers, and marketing

**Setup:**
- Create `#proj-website-redesign` channel
- Invite all stakeholders
- Pin important documents (requirements, timeline, mockups)
- Integrate tools:
  - Asana/Trello for tasks
  - Google Drive for design files
  - GitHub for code updates

**Benefits:**
- All project communication in one place
- No lost email threads
- New team members can read full history
- Archive channel when project completes

### 3. Customer Support Coordination

**Scenario:** Support team handling customer inquiries

**Setup:**
- Create `#support-urgent` for critical issues
- Create `#support-general` for routine questions
- Integrate Zendesk/Intercom to post new tickets
- Use emoji reactions for status:
  - 👀 = I'm looking at this
  - ✅ = Resolved
  - 🔄 = In progress

**Benefits:**
- Team visibility on who's handling what
- Quick escalation of urgent issues
- Knowledge sharing on solutions

### 4. Company Announcements

**Scenario:** Share company news, wins, and updates

**Setup:**
- Create `#announcements` channel (announcement-only)
- Only admins can post
- All employees auto-added
- Post company news, policy updates, celebrations

**Benefits:**
- Single source of truth for company news
- No buried emails
- Employees can react and engage
- Searchable archive

### 5. Remote Team Social Connection

**Scenario:** Maintaining team culture with distributed workforce

**Setup:**
- Create social channels:
  - `#watercooler-general` - Random chat
  - `#watercooler-pets` - Pet photos
  - `#wins` - Celebrate accomplishments
  - `#events-local-nyc` - City-specific meetups

**Benefits:**
- Maintains team bonding
- Opt-in participation
- Celebrates team culture
- Reduces isolation of remote work

### 6. Cross-Department Collaboration

**Scenario:** Sales needs marketing materials, IT support

**Setup:**
- Create request channels:
  - `#request-marketing` - Request marketing assets
  - `#request-it` - IT support tickets
- Use threads for each request
- Pin guidelines for submissions

**Benefits:**
- Organized intake system
- Transparent queue
- Easy to track status
- Reduces DM interruptions

---

## Getting Started Checklist

### Week 1: Setup and Basics
- [ ] Join your company workspace
- [ ] Set up complete profile (photo, role, contact info)
- [ ] Set your timezone correctly
- [ ] Join default channels (#general, team channels)
- [ ] Configure notification preferences
- [ ] Install Slack on mobile device
- [ ] Practice sending messages and using threads
- [ ] Try formatting (bold, italic, lists)

### Week 2: Intermediate Skills
- [ ] Join 3-5 relevant channels for your role
- [ ] Star your most important channels
- [ ] Pin an important message in a channel
- [ ] Star a message for personal reference
- [ ] Use search to find old information
- [ ] Set a reminder using `/remind` command
- [ ] React to messages with emoji
- [ ] Start a thread in a busy channel

### Week 3: Advanced Features
- [ ] Install 1-2 relevant apps/integrations
- [ ] Create a custom emoji
- [ ] Set up keyword alerts for your name/projects
- [ ] Configure DND schedule for focused work
- [ ] Share a file with your team
- [ ] Make a voice or video call
- [ ] Use Quick Switcher (Ctrl/Cmd + K) regularly
- [ ] Create a to-do list using stars or pins

### Ongoing Habits
- [ ] Check Activity Feed (@) for mentions daily
- [ ] Use threads for side conversations
- [ ] Keep channels organized (leave irrelevant ones)
- [ ] Set status when away or in meetings
- [ ] Search before asking (information might already exist)
- [ ] Use reactions instead of "+1" messages
- [ ] Archive temporary channels when done

---

## Troubleshooting Common Issues

### "I'm overwhelmed by notifications"
**Solutions:**
- Mute low-priority channels (keep membership but silence notifications)
- Set notifications to "mentions only" for busy channels
- Enable DND during focus time
- Configure mobile to only notify for DMs and mentions
- Use keyword alerts instead of watching all channels

### "I can't find old conversations"
**Solutions:**
- Use search with modifiers: `from:@user in:#channel after:2024-01-01`
- Check if channel was archived (Channels → Show archived)
- Verify you're searching the correct workspace (if you're in multiple)
- Star or pin important messages for future reference

### "Too many channels, can't keep track"
**Solutions:**
- Leave channels that aren't relevant to your work
- Star only your 5-10 most important channels
- Hide all but starred and unread channels in sidebar
- Use sections to group related channels (paid plans)
- Use Quick Switcher (Ctrl/Cmd + K) instead of scrolling

### "Messages getting lost in busy channels"
**Solutions:**
- Use threads for focused discussions
- Pin critical information at top of channel
- Use `@mentions` to ensure specific people see messages
- Consider creating a more specific channel if topic diverges
- Check "All Unreads" view for missed messages

### "Colleagues aren't responding"
**Solutions:**
- They may have notifications muted - check their status
- Use `@mention` to ensure they see your message
- Use DM for truly urgent matters
- Remember Slack is asynchronous - allow response time
- If urgent, escalate to phone call or video

### "Can't remember slash command syntax"
**Solutions:**
- Type `/` to see command suggestions
- Type `/help` for command help
- Use `/shortcuts` to see all keyboard shortcuts
- Bookmark this guide for reference

---

## Security and Privacy Tips

### Protect Your Account
- Enable two-factor authentication (2FA)
- Use a strong, unique password
- Log out of shared/public computers
- Review active sessions regularly (Settings → Sign out all other sessions)

### Respect Confidentiality
- Assume anything in Slack could be shared
- Use private channels for sensitive discussions
- Don't share passwords or credentials in messages
- Be cautious with guest access to specific channels
- Remember: Admins can access all non-DM content

### External Sharing
- Only create external file links when necessary
- Revoke external links when no longer needed
- Clearly mark channels with external guests (e.g., `#external-client-x`)
- Don't share confidential information in external channels

### Data Retention
- Understand your organization's Slack retention policy
- Important documents should be stored in official systems (not just Slack)
- Don't rely solely on Slack for long-term archiving
- Export critical conversations if leaving team

---

## Getting Help

### In-App Resources
- **Slackbot**: Your built-in assistant - ask basic questions
- **Help Menu**: Click "?" icon (top right)
- **Search Help**: Search for your question in Help menu
- **Keyboard Shortcuts**: Press `Ctrl/Cmd + /`

### Company Resources
- **Slack Champions**: Designated power users in your org who can help
- **#slack-help Channel**: Company channel for Slack questions (if exists)
- **IT Support**: Contact for technical issues or access problems
- **Onboarding Buddy**: Assigned teammate for new hire questions

### External Resources
- **Slack Help Center**: [slack.com/help](https://slack.com/help)
- **Slack Community**: Forums with other Slack users
- **Video Tutorials**: Slack's YouTube channel
- **This Guide**: Bookmark for future reference!

---

## Key Takeaways

✅ **Slack replaces email** for internal team communication, reducing inbox overload

✅ **Channels organize conversations** by topic, project, or department - use them liberally

✅ **Threads keep discussions focused** and prevent channel noise

✅ **Search is powerful** - use it before asking repeat questions

✅ **Integrations centralize work** - connect your tools to work in one place

✅ **Notifications need management** - customize per channel and use DND

✅ **It's asynchronous** - don't expect instant replies, respect focus time

✅ **Searchable history** replaces lost emails and tribal knowledge

✅ **Practice makes perfect** - start simple, add complexity as you get comfortable

---

**Remember**: Slack is a tool to enhance communication, not create more work. Start with the basics, build good habits, and gradually adopt advanced features as needed. When in doubt, ask questions in your team's help channel - everyone was new to Slack once!