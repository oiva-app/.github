# Overview
Oiva is a self-hosted, open-source service for AI-assisted incident investigation. When a production alert fires, Oiva receives it via a webhook and launches an investigation that queries the team’s existing observability stack and Git repositories. During its investigation, Oiva sends live updates to the user's dedicated Slack channel. A structured incident report with a hypothesis, supporting evidence, and next steps is provided upon completion, easing the on-call engineer’s cognitive load by compressing the initial context-gathering phase during a live incident.

At its core, Oiva is a cloud-neutral application that runs in a container and connects to a relational database. To streamline startup for new users, we include a fully provisioned deployment option on Amazon Web Services (AWS), defined with Terraform. Oiva's agentic loop leverages a multi-agent system built on the Mastra agent framework. The application is instrumented with OpenTelemetry for obsevability, evals and testing.

To get to know Oiva better, visit our [website](https://oiva-app.github.io/) and [case study](https://oiva-app.github.io/case-study/).

## Using Oiva
- To get started, visit [Oiva's Main Page](https://github.com/oiva-app/oiva)
- To deploy Oiva with ease using our provisioned AWS infrastructure, visit our [Terraform Deployment Guide](https://oiva-app.github.io/get-started/manual-setup/)
- To read more about Oiva's agent component, visit our [Agent Documentation](https://github.com/oiva-app/oiva/blob/main/src/agent/README.md)
- To discover the observed applications used for testing and evaluating Oiva, visit our [Three Services Demo App](https://github.com/oiva-app/three-services-demo-app) and forked [OpenTelemetry Astronomy Shop Demo App](https://github.com/oiva-app/opentelemetry-demo)


## The Oiva Team
[Jonathan McNair](https://github.com/unlikelykoala) | Software Engineer | Atlanta, GA

[Steven Valenziano](https://github.com/svalenziano) | Software Engineer | Durham, NC

[Valerie Racine](https://github.com/v-racine) | Software Engineer | Sparks, NV

[Tiia Rikama](https://github.com/tiiarikama) | Software Engineer | San Jose, CA

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
