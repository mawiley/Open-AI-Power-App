# Open AI Power App
This is a Power App I'm using to test out Open AI endpoints and configuration. I'll continue to add more scenarios.

## Configuring Open AI Connector
I created a customer connector from the following source (built by Robin Rosengrün). The published version inside Power Platform didn't have the image generation endpoint published yet.

https://github.com/microsoft/PowerPlatformConnectors/tree/dev/independent-publisher-connectors/OpenAI

You also need an API key from openai.com.
> Format for API key when you create the connector is: "Bearer YOUR_API_KEY" (the word "Bearer" a blank and the actual API_KEY)

###### App UI
<image src="screen-text-completion.png" style="height:350px;" />
<image src="screen-image-generation.png" style="height:350px;" />
