# How to Deploy DeepSeek-R1 on Inferia in just few clicks

*Complete step-by-step guide to deploying DeepSeek-R1 model on Inferia platform with production-ready APIs*

DeepSeek-R1 is one of the most powerful reasoning models available today, but deploying it traditionally requires complex infrastructure setup, GPU management, and extensive DevOps knowledge. With Inferia, you can have DeepSeek-R1 running in production with a fully compatible API endpoint in just a few clicks.

This guide walks you through the entire process, from connecting your wallet to making your first API call.

## What You'll Need

- A Phantom wallet (takes 2 minutes to set up if you don't have one)
- A small amount of SOL for the deployment (typically $0.50-2.00 for testing)
- Some NOS tokens: Inferia is powered by the Nosana network and requires NOS tokens for compute resources. You'll need both SOL and NOS tokens in your wallet for deployment. Learn more about [NOS tokens on CoinMarketCap](https://coinmarketcap.com/currencies/nosana/)
- Your favorite code editor or API testing tool

## Step 1: Connect Your Wallet

Head to [inferia.ai](https://inferia.ai) and you'll see the wallet connection interface. Click "Connect Wallet" and select Phantom from the options.

![Wallet connection interface](https://github.com/user-attachments/assets/67e7ecae-c80d-4ea7-9e05-6fa0001330b0)

If you don't have Phantom installed, the browser will guide you through the quick setup process. Once connected, you'll see your wallet address displayed in the top right corner.

## Step 2: Find DeepSeek-R1 in the Model Catalog

The platform organizes models into families to make finding what you need easier. You can use the search bar to find "DeepSeek-R1".

![Model families interface](https://github.com/user-attachments/assets/080170aa-5cef-482b-a77c-a8efaa5df7dd)

DeepSeek-R1 will be prominently displayed with key information like model size:
<img width="1116" height="788" alt="image" src="https://github.com/user-attachments/assets/9433bd00-1dda-4cc6-8f93-04c437ae2272" />

## Step 3: Configure Your Deployment

Click on DeepSeek-R1 7B and you'll see the configuration screen. The platform automatically selects optimal settings for DeepSeek-R1, including the right GPU type and memory allocation.

![Configuration interface](https://github.com/user-attachments/assets/847c9d3b-2299-44e0-860e-f002c9f21bfe)

For DeepSeek-R1, the platform typically recommends:
- NVIDIA 3090 GPU
- Standard inference settings that work well for most reasoning tasks

You can adjust the deployment duration (we recommend starting with 30 minutes for testing) and modify advanced parameters if needed.

## Step 4: Approve the Transaction

Once you click "Deploy", your Phantom wallet will open with a transaction approval request. The amount shown covers your selected deployment time.

![Transaction approval popup](https://github.com/user-attachments/assets/ca916818-b428-4e34-b46a-51245cc1c4e5)

Click "Approve" to proceed. Remember, if you shut down the deployment early, any unused time is automatically refunded to your wallet.

## Step 5: Watch Your Deployment Go Live

The deployment process happens in real-time with full transparency. You'll see:

- Model weights downloading
- Container initialization and configuration
- Network setup and endpoint creation
- Health checks confirming everything is working

![Control panel](https://github.com/user-attachments/assets/07ef4c30-520f-4467-95d8-6161b50eccc7)

For DeepSeek-R1 7B, the entire process typically completes in 3-5 seconds, depending on current network conditions.

## Step 6: Your chat interface and Production API is Ready

When deployment completes, you get a complete production setup:

- **OpenAI-compatible API endpoint** - works with existing OpenAI code
- **Interactive chat interface** - test the model directly in your browser by clicking visit chat button:
  
  <img width="1542" height="833" alt="image" src="https://github.com/user-attachments/assets/2799ddae-b9f3-47cf-8d2c-f81cd38111c5" />

- **Real-time monitoring** - track usage, costs, and performance
- **Parameter controls** - adjust temperature, max tokens, and other settings

![API documentation](https://github.com/user-attachments/assets/4f70240f-9f73-4db6-815f-ceb053440d4b)

## Testing DeepSeek-R1

The built-in chat interface lets you immediately test DeepSeek-R1's reasoning capabilities. Try asking it complex problems that require step-by-step thinking:

**Good test prompts for DeepSeek-R1:**
- "Solve this logic puzzle: How many r's in strawberry?"
- "Explain the reasoning behind sin90 is 1"
- "Break down this problem step by step: N-Queens Problem"

## Using the API in Your Code

The API works exactly like OpenAI's, so integration is straightforward. Here's how to connect:

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://apilink/v1",
    api_key="sh-dummmy"  # could be annything as this is just your personal deployment
)

response = client.chat.completions.create(
    model="deepseek-r1",
    messages=[
        {"role": "user", "content": "Explain quantum entanglement step by step"}
    ],
    temperature=0.7,
    max_tokens=1000
)

print(response.choices[0].message.content)
```

The same pattern works in JavaScript, curl, or any other HTTP client:

```bash
curl -X POST "https://apilink/v1/chat/completions" \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer dummykey" \
  -d '{
    "model": "deepseek-r1",
    "messages": [{"role": "user", "content": "What is 2+2?"}],
    "temperature": 0.7
  }'
```

## Managing Your Deployment

The control panel gives you complete visibility and control:

- **Real-time Logs** - see request volume, response times etc
- **Time extensions** - add more time with one click
- **Early shutdown** - stop anytime and get automatic refunds

![Deployment management](https://github.com/user-attachments/assets/0efdd25e-8a7a-4f85-8524-32980925e081)

## Getting Your Refund

Finished testing early? No problem. Click "Shutdown Deployment" and confirm. Within seconds, unused time is calculated, SOL and Nos are returned to your wallet automatically.

![Refund confirmation](https://github.com/user-attachments/assets/a4ef221c-0f22-4e7d-b229-01eaafd9c385)

## Tips for Using DeepSeek-R1 Effectively

**Reasoning Tasks**: DeepSeek-R1 excels at problems requiring step-by-step logic. Give it complex scenarios and ask it to "think through this step by step."

**Temperature Settings**: Start with 0.7 for balanced creativity and consistency. Lower to 0.1-0.3 for more deterministic reasoning, raise to 0.8-1.0 for more creative problem-solving.

**Prompt Engineering**: DeepSeek-R1 responds well to clear instructions about the type of reasoning you want. Be specific about whether you need mathematical proof, logical deduction, or creative problem-solving.


## Next Steps

Now that you have DeepSeek-R1 running, you can:

- Integrate it into your application using the OpenAI-compatible API
- Experiment with different reasoning tasks to understand its capabilities  
- Scale up your deployment time for production workloads
- Explore other models in the Inferia catalog

The same deployment process works for any model in our catalog, so you can easily test alternatives or deploy multiple models for different use cases.

---

*Ready to deploy DeepSeek-R1? Head to [inferia.ai](https://inferia.ai) and get started in under 60 seconds.*
