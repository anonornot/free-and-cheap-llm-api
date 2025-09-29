## Free LLM APIs
Platform | Platform Type | Deal Type | Cost | Models | Rate limit | Requirement/Cons | Guide |
:----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | 
[Google Vertex](https://cloud.google.com/vertex-ai) | Provider | Sign up | Free 300$ for 3 months | Gemini models | — | Phone number/Billing information required | — 
[AWS Bedrock](https://aws.amazon.com/) | Provider | Sign up | Free 200$ for 6 months | Claude models | — | Phone number/Billing information required | [Rentry](https://rentry.co/oo66akom) 
[Sambanova](https://sambanova.ai/) | Provider | Sign up | Free 5$ | [DS and smaller models](https://docs.sambanova.ai/docs/en/models/sambacloud-models) | 60 RPD | Phone number required | [Guide ↓](#how-to-use-custom-apis) 
[AtlasCloud](https://www.atlascloud.ai/) | Provider | Sign up | Free 0.1$ (daily) | [Most RP models](https://www.atlascloud.ai/models/list) | —  | — | [Guide ↓](#how-to-use-custom-apis) 
[Groq](https://groq.com/) | Provider | Sign up | Free Tier | [Kimi K2 and smaller models](https://console.groq.com/docs/rate-limits#rate-limits) | 10K TPM | Super low rate limits | [Guide ↓](#how-to-use-custom-apis) 
[NVIDIA NIM](https://build.nvidia.com/explore/discover) | Provider | Sign up | Free Tier | [DS models, Kimi K2, Qwen 3](https://build.nvidia.com/search/models?q=chat+OR+text-to-text) | 40RPM (?) | Phone number required/Queue system | [Reddit](https://reddit.com/r/SillyTavernAI/comments/1lxivmv/nvidia_nim_free_deepseek_r10528_and_more/)
[LLM7](https://llm7.io/) | Provider | Sign up | Free Tier | [DS models, GPT models, Qwen 3](https://api.llm7.io/v1/models) | 20 RPS & 150 RPM | Quantized (?) | [Guide ↓](#how-to-use-custom-apis)
[Akash](https://akash.network/) | Provider | Sign up | Free Tier | [DS V3.1, gpt-oss-120b, Qwen 3](https://chatapi.akash.network/documentation) | — | — | [Guide ↓](#how-to-use-custom-apis) 
[Parasail](https://www.parasail.io/) | Provider | Application | Free 10$ | [DS models, Kimi K2, GLM 4.5](https://www.saas.parasail.io/pricing) | — | Billing information required | No support on ST [Guide ↓](#how-to-use-custom-apis) 
[Routeway](https://routeway.ai/) | Gateway | Waitlist | Free tier | [R1T2, Kimi K2, GLM 4.5, GPT-4.1](https://routeway.ai/models) | 20 RPM & 200 RPD | Early development | [Guide ↓](#how-to-use-custom-apis) 
[Vercel](https://vercel.com) | Gateway | Sign up | Free 5$ | [Most RP models (except Opus)](https://vercel.com/ai-gateway/models) | — | Billing information required | [Guide ↓](#how-to-use-custom-apis) 

## Cheap LLM APIs
Platform | Platform Type | Deal Type | Cost | Models | Rate limit | Cons | Guide |
:----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | 
[Chutes](https://chutes.ai/) | Provider | Subscription | 3$/month | DS models, Kimi K2, Qwen 3, GLM 4.5 | 300 RPD | — | [Guide ↓](#how-to-use-custom-apis) 
[NanoGPT](https://nano-gpt.com) | Gateway | Subscription | 8$/month | [DS models, Kimi K2, Qwen 3](https://nano-gpt.com/subscription) | 2000 RPD | — | [Guide ↓](#how-to-use-custom-apis) 
[Openrouter](https://openrouter.ai/) | Gateway | One time deposit | Deposit 10$ once | [DS models, Kimi K2, Qwen 3 and more](https://openrouter.ai/models?max_price=0) | 1000 RPD | Rate limit errors | [Guide ↓](#how-to-use-custom-apis) 
[LLMGateway](https://llmgateway.io/) | Gateway | One time deposit | Deposit 5$ once | [R1T2, Kimi K2, GLM 4.5, GPT-4.1](https://llmgateway.io/models) | 20 RPM | Some providers are in early development | [Guide ↓](#how-to-use-custom-apis) 


*DS means Deepseek*

___

# How To Use Custom APIs? 

#### JanitorAI

1. Go to **Your chat → API Settings → Proxy → Add Configuration** 
2. Name your proxy and enter the model name you want to use 
3. Enter the Base URL and click on **Add /chat/completions**
4. Enter your API key
5. Click on **Add Configuration** and **Save Settings**

![](https://files.catbox.moe/ddz6eu.png)

### Base URLs: 

Platform | Base URL | 
:----: | :----: |
| Sambanova  | `https://api.sambanova.ai/v1` | 
| AtlasCloud  | `https://api.atlascloud.ai/api/v1`  |
| Groq  | `https://api.groq.com/openai/v1`  |
| NVIDIA  | `https://integrate.api.nvidia.com/v1` |
| LLM7  | `https://api.llm7.io/v1` |
| Akash | `https://chatapi.akash.network/api/v1` |
| Parasail | `https://api.saas.parasail.io/v1` | 
| LLMGateway  | `https://api.llmgateway.io/v1` |
| Vercel  | `https://ai-gateway.vercel.sh/v1`  |
| NanoGPT  | `https://nano-gpt.com/api/v1`  |
| Openrouter  | `https://openrouter.ai/api/v1`  |
| Routeway  | `https://api.routeway.ai/v1` |
___
# If you have any questions/problems, feel free to DM me on reddit.
# u/Minimum-Analysis-792
___
