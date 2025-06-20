# fabric-ai-calculator
Estimating Microsoft Fabric Copilot and AI costs. Made by Sandeep Pawar. www.fabric.guru

These are only estimates, always refer to the official Microsoft documentation.
Feel free tp create a PR if you would like to contribute. 

https://pawarbi.github.io/fabric-ai-calculator/

Below pricing is used. Pricing as of 06/11/2025

| Experience | CU(s)/1000 tokens Input | CU(s)/1000 tokens Output |
|------------|--------------------------|--------------------------|
| Copilot | 100 | 400 |
| Data Agent | 100 | 400 |
| AI Functions (GPT-4o-mini) | 5.04 | 20.17 |
| GPT-4o-2024-08-06 Global | 84.03 | 336.13 |
| GPT-4o-mini | 5.04 | 20.17 |
| ~~GPT-4 (32K context)~~ | ~~2016.81~~ | ~~4033.61~~ |
| ~~GPT-3.5-Turbo (16K context)~~ | ~~16.81~~ | ~~50.42~~ |
| text-embedding-ada-002 | 3.36 | 0 |

Copilot requests are classified as background jobs and spread over 24 hours. AI Functions and Open AI models can be background or interactive depending on how the notebook is run.

Note: GPT-4 and 3.5 are no longer supported.
## References:
- https://learn.microsoft.com/en-us/fabric/data-science/ai-services/ai-services-overview
- https://learn.microsoft.com/en-us/fabric/fundamentals/copilot-fabric-consumption
- https://learn.microsoft.com/en-us/fabric/fundamentals/copilot-fabric-overview
- https://blog.fabric.microsoft.com/en-us/blog/17673?ft=All
- https://blog.fabric.microsoft.com/en-us/blog/fabric-copilot-pricing-an-end-to-end-example-2?ft=All
