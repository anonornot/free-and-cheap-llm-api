## Free LLM APIs
Platform | Platform Type | Deal Type | Cost | Models | Rate limit | Requirement/Cons | Guide |
:----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
[Google Vertex](https://cloud.google.com/vertex-ai) | Provider | Sign up | Free 300$ for 3 months | Gemini | — | Phone number - Credit card - Billing information | —
[AWS Bedrock](https://aws.amazon.com/) | Provider | Sign up | Free 200$ for 6 months | Claude | — | Phone number - Credit card - Billing information | [Rentry](https://rentry.co/oo66akom)
[Sambanova](https://sambanova.ai/) | Provider | Sign up | Free 5$ | [DS and smaller models](https://docs.sambanova.ai/docs/en/models/sambacloud-models) | 60 RPD | Phone number | [Guide↓](#how-to-use-custom-apis)
[Parasail](https://www.parasail.io/) | Provider | Application | Free 10$ | [DS, Kimi K2, GLM 4.5](https://www.saas.parasail.io/pricing) | — | Billing information | [Guide↓](#how-to-use-custom-apis) 
[Vercel](https://vercel.com) | Gateway | Sign up | Free 5$ | [Most RP models (except Opus)](https://vercel.com/ai-gateway/models) | — | Credit card | [Guide↓](#how-to-use-custom-apis) 
[AtlasCloud](https://chatapi.akash.network) | Provider | Sign up | Free 0.1$ (daily) | [Most RP models](https://www.atlascloud.ai/models/list) | —  | — | [Guide↓](#how-to-use-custom-apis) 
[Electronhub](https://www.electronhub.ai/) | Provider | Sign up | Free tier + Free 0.25$ (daily)| [DS, GPT, Kimi K2, Qwen 3 and smaller models](https://api.navy/#models) | 7 RPM | — | [Guide↓](#how-to-use-custom-apis) 
[Groq](https://groq.com/) | Provider | Sign up | Free Tier | [Kimi K2 and smaller models](https://console.groq.com/docs/rate-limits#rate-limits) | 10K TPM | Super low rate limits | [Guide↓](#how-to-use-custom-apis) 
[NVIDIA NIM](https://build.nvidia.com/explore/discover) | Provider | Sign up | Free Tier | [DS, Kimi K2 and smaller models](https://build.nvidia.com/search/models?q=chat+OR+text-to-text) | 40RPM (?) | Phone number - Queue system | [Reddit](https://reddit.com/r/SillyTavernAI/comments/1lxivmv/nvidia_nim_free_deepseek_r10528_and_more/)
[Akash](https://chatapi.akash.network) | Provider | Sign up | Free Tier | [DS V3.1, gpt-oss-120b, Qwen 3](https://chatapi.akash.network/documentation) | — | — | [Guide↓](#how-to-use-custom-apis) 
[Nebulablock](https://www.nebulablock.com/) | Provider | Sign up | Free Tier | [DS and smaller models](https://console.nebulablock.com/serverless) | — | Credit card | [Guide↓](#how-to-use-custom-apis) 
[NavyAI](https://api.navy/) | Provider | Sign up | Free Tier | [Most RP models](https://api.navy/#models) | 25 RPM & 500K TPD | Sign in with Discord | [Guide↓](#how-to-use-custom-apis) 
[LLM7](https://llm7.io/) | Provider | No sign up | Free Tier | [DS, GPT-5 and smaller models](https://api.llm7.io/v1/models) | 1 RPS & 45 RPM | Quantized (?) | [Guide↓](#how-to-use-custom-apis)
[ai.is-a.dev](https://ai.is-a.dev) | Provider | No sign up | Free Tier | [DS and LLama models](https://ai.is-a.dev/models) | — | Quantized (?) | [Guide↓](#how-to-use-custom-apis)


## Cheap LLM APIs
Platform | Platform Type | Deal Type | Cost | Models | Rate limit | Cons | Guide |
:----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | 
[Chutes](https://chutes.ai/) | Provider | Subscription | 3$/month | DS models, Kimi K2, Qwen 3, GLM 4.5 | 300 RPD | — | [Guide↓](#how-to-use-custom-apis) 
[NanoGPT](https://nano-gpt.com) | Gateway | Subscription | 8$/month | [DS, Kimi K2, Qwen 3](https://nano-gpt.com/subscription) | 2000 RPD | — | [Guide↓](#how-to-use-custom-apis) 
[Openrouter](https://openrouter.ai/) | Gateway | One time deposit | Deposit 10$ once | [DS, Kimi K2, Qwen 3 and more](https://openrouter.ai/models?max_price=0) | 1000 RPD | Rate limit errors | [Guide↓](#how-to-use-custom-apis) 
[LLMGateway](https://llmgateway.io/) | Gateway | One time deposit | Deposit 5$ once | [R1T2, Kimi K2, GLM 4.5, GPT-4.1](https://llmgateway.io/models) | 20 RPM | Some providers are in early development | [Guide↓](#how-to-use-custom-apis) 

*DS: Deepseek models (R1 0528, V3 0324 and V3.1)*

*GPT: Mostly GPT-5, gpt-oss and 4o mini models* 

*Claude: Sonnet 3.5/3.7/4/4.5 and Opus 4/4.1 models* 

*Gemini: Gemini 2.0/2.5 Pro and Flash models* 

*Smaller models: LLama, Mistral and quantized open-source models* 

*?: "not sure"*

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
| Parasail | `https://api.saas.parasail.io/v1` | 
| Vercel  | `https://ai-gateway.vercel.sh/v1`  |
| AtlasCloud  | `https://api.atlascloud.ai/api/v1`  |
| Electronhub | `https://api.electronhub.ai/v1` |  
| Groq  | `https://api.groq.com/openai/v1`  |
| NVIDIA NIM | `https://integrate.api.nvidia.com/v1` |
| Akash | `https://chatapi.akash.network/api/v1` |
| Nebulablock | `https://api.nebulablock.com/api/v1` | 
| NavyAI | `https://api.navy/v1` |  
| LLM7  | `https://api.llm7.io/v1` |
| ai.is-a.dev  | `https://ai.is-a.dev` |
| Chutes  | `https://api.chutes.ai/v1`  |
| NanoGPT  | `https://nano-gpt.com/api/v1`  |
| Openrouter  | `https://openrouter.ai/api/v1`  |
| LLMGateway  | `https://api.llmgateway.io/v1` |
___
# If you have any questions/problems, feel free to DM me on reddit.
# u/Minimum-Analysis-792
___
