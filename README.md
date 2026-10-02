# WanderBot-an-AI-travel-concierge

building using Strands SDK, wrap it in a BedrockAgentCoreApp entrypoint and ship it to Amazon Bedrock AgentCore Runtime with the built-in calculator tool wired in. 

To do:
1. Instantiate a minimal Strands Agent backed by a BedrockModel - Wrap an agent as a deployable service using BedrockAgentCoreApp and @app.entrypoint
2. Plug a built-in Strands tool (calculator) into the agent with a single import
3. Iterate locally with agentcore dev and deploy with agentcore deploy
