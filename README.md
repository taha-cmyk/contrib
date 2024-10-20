# Content Creation Guide

This guide will help you create markdown content for news articles, projects, and events using our custom templates.

## Table of Contents
1. [Simplified Date Format](#simplified-date-format)
2. [News Articles](#news-articles)
3. [Projects](#projects)
4. [Events](#events)

## Simplified Date Format

To make date entry easier, you can now use a simple format: `YYYY-MM-DD`. For example, October 20, 2024, would be written as `2024-10-20`.

For the `date` field in the content headers, you can use this simple format, and our system will automatically convert it to the required full date-time format.

If you need to specify a time, you can add it after the date like this: `YYYY-MM-DD HH:MM`. For example, `2024-10-20 14:30` for 2:30 PM on October 20, 2024.

## News and Posts

To create news and  posts, use the following template:

```markdown
+++
title = "Your Article Title"
date = "YYYY-MM-DD"
draft = false
description = "A brief description of your news article."
tags = ["Tag1", "Tag2", "Tag3"]
+++

Your post content goes here.
```

### Example:

```markdown
+++
title = "Oracle Opening in Morocco"
date = "2024-10-19"
draft = false
description = "Oracle announces its official opening in Morocco, expanding its footprint in North Africa. This move is set to boost the tech ecosystem in the region and provide new opportunities for local talent."
tags = ["Oracle", "Morocco", "Tech News", "2024", "North Africa"]
+++

Full article content goes here...
```

## Projects

For project pages, use this template:

```markdown
+++
title = "Your Project Title"
date = "YYYY-MM-DD"
draft = false
description = "A brief description of your project."
maintainers = ["Maintainer 1", "Maintainer 2"]
project_link = "https://github.com/yourusername/your-project"
tags = ["Tag1", "Tag2", "Tag3"]
+++

Your project details go here.
```

### Example:

```markdown
+++
title = "A Cloud Provider for Moroccan Developers"
date = "2024-10-19"
draft = false
description = "An innovative cloud provider project tailored to meet the unique needs of Moroccan developers and startups."
maintainers = ["Alice Smith", "Bob Johnson"]
project_link = "https://github.com/yourusername/my-awesome-project"
tags = ["Cloud", "Morocco", "Developers", "Startups", "Tech"]
+++

Detailed project information goes here...
```

## Events

For event pages, use this template:

```markdown
+++
title = "Your Event Title"
date = "YYYY-MM-DD HH:MM"
draft = false
description = "A brief description of your event."
event_date = "Month DD, YYYY"
event_time = "HH:MM AM/PM"
location = "Event Location"
organizer = "Event Organizer"
registration_link = "https://example.com/register"
tags = ["Tag1", "Tag2", "Tag3"]
+++

Your event details go here.
```

### Example:

```markdown
+++
title = "Tech Innovators Meetup"
date = "2024-10-20 10:00"
draft = false
description = "Join us for an exciting meetup of tech innovators in Casablanca. Network with like-minded professionals and learn about the latest trends in technology."
event_date = "November 15, 2024"
event_time = "6:00 PM"
location = "TechHub Casablanca, 123 Innovation Street, Casablanca"
organizer = "Morocco Tech Association"
registration_link = "https://example.com/register-tech-meetup"
tags = ["Meetup", "Technology", "Networking", "Casablanca", "2024"]
+++

Detailed event information, agenda, and speaker bios go here...
```

Remember to replace the placeholder text and values with your actual content. The `date` field can now be in the simple `YYYY-MM-DD` format, or `YYYY-MM-DD HH:MM` if you need to specify a time.

For events, make sure to fill out all the relevant fields like `event_date`, `event_time`, `location`, `organizer`, and `registration_link` to provide comprehensive information to  visitors.