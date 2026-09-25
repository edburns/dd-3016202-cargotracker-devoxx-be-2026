## Metadata

- Parent SharePoint folder: [link](https://microsoft.sharepoint.com/:f:/r/teams/JavaatMicrosoft/Shared%20Documents/Forms/AllItems.aspx?id=%2Fteams%2FJavaatMicrosoft%2FShared%20Documents%2FEvents%2Fnon%2Dmicrosoft%2Downed%2Devents%2F2026%2Fdd%2D3016202%2Ddevoxx%2Dbelgium%2Fdd%2D3017207%2Dcopilot%2Dsdk%2Dworkshop&p=true&share=cgpyEbX1%5F9j6TZxN7oTte6e4EgUCzzIS8ZaMSqUpDI589G2uTQ).
- SharePoint: [link](https://microsoft.sharepoint.com/:t:/r/teams/JavaatMicrosoft/Shared%20Documents/Forms/AllItems.aspx?id=%2Fteams%2FJavaatMicrosoft%2FShared%20Documents%2FEvents%2Fnon%2Dmicrosoft%2Downed%2Devents%2F2026%2Fdd%2D3016202%2Ddevoxx%2Dbelgium%2Fdd%2D3017207%2Dcopilot%2Dsdk%2Dworkshop%2Fdd%2D3017207%2Dcopilot%2Dsdk%2Dworkshop%2Dabstract%2Emd&parent=%2Fteams%2FJavaatMicrosoft%2FShared%20Documents%2FEvents%2Fnon%2Dmicrosoft%2Downed%2Devents%2F2026%2Fdd%2D3016202%2Ddevoxx%2Dbelgium%2Fdd%2D3017207%2Dcopilot%2Dsdk%2Dworkshop&p=true&share=cQpXbFvbKPFySpyzf7qyS5m2EgUCTeR9Uivw6s8%5FZH7kLQQAmQ).
- GitHub repo: [dd-3016202-cargotracker-devoxx-be-2026](https://github.com/edburns/dd-3016202-cargotracker-devoxx-be-2026).

## Title

10 boring reasons why Java is the best ecosystem for agentic development

## Description 

I was about ten years into my Java career when I had spoken at enough conferences, and befriended enough speakers, that my sense for the hype cycle had been sharpened by the collective skepticism of the speaker jet-set. That was two decades ago. We've all heard the latest hype about what AI agents can do well. Less hyped is what can go wrong: non-determinism, DRY violations, hallucinated APIs, token cost, unreviewable code, and code reviews that start to improve the code, only to keep going until the code is actually broken.

This talk makes the case that it's the time-honed boring things about Java that keep the agents honest. Successful agentic development maximizes agent strengths — speed, breadth, fearless exploration, tolerance for boilerplate — while backstopping their weaknesses: non-determinism, dependency sprawl, inconsistent error handling, and code that works but nobody wants to maintain.

Here are the 10 boring reasons:
1. Type system
2. Testing ecosystem
3. Backwards compatibility culture
4. Deep static analysis
5. Build system maturity and dependency management
6. Code formatting and style enforcement
7. Virtual threads and structured concurrency
8. Observability stack
9. JVM performance tuning
10. Breadth of deployment options

For each, I'll show the specific agentic failure mode it addresses. I'll close with a practical checklist for making your Java development process agent-safe, and tie it up with the message that to move forward, you have to go back.


## Elevator pitch

About me:

1. I've been prominent in the Java world for over two decades.
2. I'm currently responsible for the GitHub Copliot SDK for Java.
3. I've survived at least three rounds of layoffs at Microsoft since this whole AI thing started. They only keep people who know how to wrangle clankers. I made the cut.
4. I first spoke at Devoxx when it was JavaPolis.

About the content: 

I've successfully built and internally use an agentic system to maintain the Java GitHub Copilot SDK. Here's what I learned.

1. Need to keep context bounded.
2. Need to use multiple kinds of agents, in different systems, with different system prompts and success criteria.
3. Need to use CLIs to tie the tools together.
4. Java isn't accidentally good at this — its boring qualities are exactly what agent-wrangling demands

Most agentic dev content right now is Python-first. Devoxx attendees deserve to hear this case from someone building it in Java.

