# Content Creation Guide

This guide will help you create markdown content for news articles, projects, and events using our custom templates.

## Table of Contents
1. [Date Format](#simplified-date-format)
2. [News and Posts](#news-articles)
3. [Projects](#projects)
4. [Events](#events)

## Simplified Date Format

To make dates you can use this format: `YYYY-MM-DD`. For example, October 20, 2024, would be written as `2024-10-20`.


## News and Posts

To create news and  posts, use the following template:

```markdown
+++
title = "Your Article Title"
date = "YYYY-MM-DD"
draft = false
description = "A brief description of your news article."
tags = ["Tag1", "Tag2", "Tag3"]
authors = ["", "", ""]
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
authors = ["Ahmad", "Amir"]

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
authors = ["", "", ""]

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
authors = ["Ahmad", "Amir"]

+++

Detailed project information goes here...
```

## Events

For event pages, use this template:

```markdown
+++
title = "Your Event Title"
date = "YYYY-MM-DD"
draft = false
description = "A brief description of your event."
event_date = "Month DD, YYYY"
event_time = "HH:MM AM/PM"
location = "Event Location"
organizer = "Event Organizer"
registration_link = "https://example.com/register"
tags = ["Tag1", "Tag2", "Tag3"]
authors = ["", ""]

+++

Your event details go here.
```

### Example:

```markdown
+++
title = "Tech Innovators Meetup"
date = "2024-10-20 "
draft = false
description = "Join us for an exciting meetup of tech innovators in Casablanca. Network with like-minded professionals and learn about the latest trends in technology."
event_date = "November 15, 2024"
event_time = "6:00 PM"
location = "TechHub Casablanca, 123 Innovation Street, Casablanca"
organizer = "Morocco Tech Association"
registration_link = "https://example.com/register-tech-meetup"
tags = ["Meetup", "Technology", "Networking", "Casablanca", "2024"]
authors = ["Ahmad", "Amir"]

+++

Detailed event information, agenda, and speaker bios go here...
```

For events, make sure to fill out all the relevant fields like `event_date`, `event_time`, `location`, `organizer`, and `registration_link` to provide comprehensive information to  visitors.
