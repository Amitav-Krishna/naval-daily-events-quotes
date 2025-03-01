# naval-daily-events-quotes
Fetches ten recent news events that happened today and uses Google Gemini LLM to find relevant Naval quotes

## Tasks
### MVP
- [ ] Use google gemini with google search grounding to get 10 events that happened today https://ai.google.dev/gemini-api/docs/grounding?lang=python
- [ ] Create a prompt for gemini to generate relvant naval quotes using the events https://aistudio.google.com/prompts/new_chat
- [ ] create simple frontend to access this script
- [ ] deploy application to be publically available
- [ ] laumch on hackernews, reddit, etc

### SPRINKLES
- [ ] Save in database
- [ ] post daily to twitter, reddit, etc
- [ ] make frontend really nice
- [ ] use database of naval quotes instead of generating on fly
- [ ] use news api instead

## PROJECT DEFINITION
- Web application that fetches ten recent news events that happened today and then uses google gemini LLM to find relevant Naval Ravikant quotes that relate to the events
