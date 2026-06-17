# Overview
Oiva is a self-hosted, open-source service for AI-assisted incident investigation. When a production alert fires, Oiva receives it via a webhook and launches an investigation that queries the team’s existing observability stack and Git repositories. During its investigation, Oiva sends live updates to the user's dedicated Slack channel. A structured incident report with a hypothesis, supporting evidence, and next steps is provided upon completion, easing the on-call engineer’s cognitive load by compressing the initial context-gathering phase.

Oiva leverages a multi-agent system built on the Mastra agent framework, keeps durable incident state in PostgreSQL, deploys on AWS ECS/Fargate, and is instrumented with OpenTelemetry for obsevability, evals and testing.


## The Oiva Team
[Jonathan McNair](https://github.com/unlikelykoala) | Software Engineer

[Steven Valenziano](https://github.com/svalenziano) | Software Engineer

[Valerie Racine](https://github.com/v-racine) | Software Engineer

[Tiia Rikama](https://github.com/tiiarikama) | Software Engineer

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
