Football research often starts with a player name, a profile link and information spread across different sources. I wanted to explore how that research could be easier to revisit and update.

For my capstone project, I built Scout Signal: a tested football scouting research prototype using n8n, OpenAI, SerpApi, Pinecone and Google Sheets.

It accepts pasted text or a Transfermarkt link, researches the player and produces a short profile. Valid research is automatically stored in Pinecone so it can be retrieved later. Decision makers can also choose to save a player to a Google Sheets review shortlist.

The retrieval workflow brings stored research together with fresh searches to check what may have changed. Keeping research storage separate from the decision to shortlist a player was an important part of the design.

This project gave me practical experience connecting AI tools, designing workflows and thinking carefully about identity, source quality and uncertainty. The repository includes both workflow exports, execution screenshots and a setup guide.

Scout Signal is a prototype supporting human decisions. It still needs broader evaluation, and its outputs need to be checked against their sources.

I’d welcome feedback from people working in football analytics, scouting and AI automation.

Project: https://github.com/KKallias/scout-signal

#FootballAnalytics #AI #n8n #RAG #CapstoneProject
