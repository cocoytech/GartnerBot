# Gartner Bot

### This sample incorporates the following:
- QnA Maker for injested FAQ intelligent search
- LUIS for natural language intent extraction
- Dispatch to create one cohesive LUIS model used to determine which QnA Maker knowledge base or LUIS model to query
- Agent Handoff to route end-user to a live agent when the user's intent or question cannot be addressed

## Azure Services Architecture
![Bot Service Architecture](https://github.com/rob-derosa/GartnerBot/blob/master/assets/bot_service_architecture.png?raw=true)
 

#### This sample incorporated code from the following sources:
- [Intermediator Sample](https://github.com/tompaana/intermediator-bot-sample)
- [Bot Message Routing Component](https://github.com/tompaana/bot-message-routing)