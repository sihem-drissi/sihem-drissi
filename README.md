<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,100:A78BFA&height=160&section=header" width="100%"/>

# Sihem Drissi

**AI Engineer (in progress) · RAG · LLM apps · Agents**

[LinkedIn](YOUR_LINKEDIN_URL) · [Portfolio](YOUR_PORTFOLIO_URL) · [Email](mailto:youremail@example.com)

</div>

<br>

## about

M.Sc. in Data Science, currently job-hunting, based in Algeria. I got into AI through the data science route — cleaning messy datasets, fixing leaky pipelines — and moved toward the layer above it: how you actually turn an LLM into something reliable people can use.

I don't just want to call an API and call it done. I want to know what's happening in the layer under the layer I'm working in — why a retrieval step returns the wrong chunk, why an agent loop gets stuck, what breaks when you move from a notebook to something with real traffic.

<br>

## where I'm spending my time

| area | what that means for me right now |
|---|---|
| **generative AI** | LLM apps, prompting, actually reading how Transformers work instead of trusting the abstraction |
| **RAG** | embeddings, vector search, retrieval that returns the *right* context, not just *a* context |
| **agents** | tool use, multi-step workflows, the ones that don't fall apart outside the happy path |
| **AI engineering** | APIs, model serving, the plumbing between "it works in my notebook" and "it works" |
| **deployment** | Docker, cloud AI, LLMOps |

<br>

## projects

### Bawsala — Arabic LLM tutor
Built to teach in Arabic, not translate English answers into it. This is where I actually learned RAG isn't a library you import — it's a design problem: how you chunk, what you retrieve, how you keep the model grounded instead of confidently making things up.
→ [repo](https://github.com/)

### Stack Overflow salary prediction
A full regression pipeline I rebuilt more times than I'd like to admit — target encoding, tuned ensembling, bootstrap confidence intervals instead of one number pretending to be certain. Proof I can do the unglamorous data work everything else gets built on.
→ [kaggle](https://kaggle.com/)

### Sentube — YouTube sentiment analysis
Wanted to know if comments actually matched the vibe of the video. Turns out, not always.
→ [repo](https://github.com/)

### CNN fake image classifier
A model trained to catch AI-generated images. Felt like the right thing to build in this decade.
→ [repo](https://github.com/)

<br>

## how I think about an AI system

Not just "the model." The whole thing.

```
                 user
                   │
                   ▼
              application
                   │
        ┌──────────┼──────────┐
        ▼          ▼          ▼
       LLM        RAG       agent
        │          │          │
        └──────────┼──────────┘
                   ▼
                  API
                   │
                   ▼
              deployment
```

RAG specifically, the way I keep coming back to it:

```
documents → chunking → embeddings → vector search
                                          │
                                          ▼
                                  relevant context
                                          │
                                          ▼
                                        LLM
                                          │
                                          ▼
                                grounded response
```

<br>

## stack

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,huggingface,fastapi,docker,git,gcp&theme=dark" />

`LLMs` `RAG` `Vector Search` `Embeddings` `Agents` `FastAPI` `Docker` `LLMOps`

<br>

## a few things I actually believe

- Understand it before you abstract it away
- A working, imperfect system teaches you more than a perfect plan
- The model is one piece — the system around it is the actual engineering
- I'd rather be honest about what I don't know yet than fake it

<br>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,100:A78BFA&height=100&section=footer" width="100%"/>
</div>
