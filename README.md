# ai-agent
- Buidling an ai agent to do something

### To run the project:

```bash
npm start
# or
bun run index.ts
```

### OpenAI API Key

Create an [API Key from OpenAI](https://platform.openai.com/settings/organization/api-keys) and save it in a `.env` file:

```
OPENAI_API_KEY='YOUR_API_KEY'
```


### Learning Notes
- What are LLMs?
- Transformer architecture foundation
    - [Attention is all you need transformer](https://arxiv.org/abs/1706.03762)
- Inference Process
    - Tokenization and token embeddings
    - Weights in LLMs
- Limitations
    - Context window constraints