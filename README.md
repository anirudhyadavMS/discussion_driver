# Discussion Driver

An interactive facilitation board for brainstorming sessions about User Sync Connectors for Copilot.

## Files

- **discussion_driver.html.html** - The main HTML application with embedded JavaScript
- **questions.json** - Predefined questions in JSON format for programmatic access
- **questions.md** - Predefined questions in Markdown format for human-readable documentation

## Predefined Questions

The application includes predefined questions organized into several categories:

### Motivations (3 items)
Key motivations for user sync connectors:
- OpenAI parity
- AU w. enhanced discovery / virality
- Better response quality

### Value Pillars (3 items)
Three pillars for framing the value proposition:
- Personal AI Assistant for Work
- Team Pilot, Bottom-Up Adoption
- Integrating Personal & Private Data

### Crawl-Walk-Run Phases (3 items)
Phased rollout approach:
- Crawl: Prove value with a focused MVP
- Walk: Expand coverage + enable richer experiences
- Run: Scale, share, and institutionalize

### Discussion Questions (9 items)
Structured questions to guide the brainstorming session:
1. Motivation for user sync connectors
2. How is ChatGPT doing it?
3. Value framing for user sync connectors
4. MVP phasing: Crawl – Walk – Run
5. Which surfaces should we target?
6. Which connectors are we targeting?
7. What is the data ingest model?
8. MVP phases
9. Unifying connectors for Admin + end-user

## Using the Questions

### JSON Format
The `questions.json` file can be used to:
- Load questions programmatically in other applications
- Generate reports or documentation
- Integrate with other tools
- Version control and track changes to questions

### Markdown Format
The `questions.md` file can be used to:
- Share questions in human-readable format
- Reference during meetings
- Include in documentation
- Review and discuss offline

## Using the Application

1. Open `discussion_driver.html.html` in a web browser
2. Enter session name and participant name
3. Navigate through questions using the agenda panel
4. Capture ideas, vote, and track progress
5. Export results as JSON or Markdown

## Features

- **Interactive Question Navigation**: Click through predefined questions
- **Idea Capture**: Add and vote on ideas for each question
- **Timer**: Built-in section timer for time-boxed discussions
- **Export**: Export session data as JSON or Markdown
- **Local Storage**: Automatically saves progress in browser

## Standalone Product

The predefined questions have been separated into standalone files (`questions.json` and `questions.md`) to enable:

1. **Reusability**: Use the same questions across multiple tools
2. **Version Control**: Track changes to questions independently
3. **Documentation**: Easily share and reference questions
4. **Integration**: Import questions into other systems
5. **Customization**: Modify questions without changing the tool code
