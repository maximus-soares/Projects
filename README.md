<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# How to Use DeepSeek

**Project Link:** [View Project](http://learn.nextwork.org/projects/ai-llm-deepseek)

**Author:** Maximus Soares  
**Email:** maximus@nextwork.org

---

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/ai-llm-deepseek_kkkkkkkk)

---

## Introducing Today's Project!

In this project, I will demonstrate a range of features on the new LLM Deepseek. I'm doing this project to learn how to download Deepseek locally and compare it's features and performance to ChatGPT. 

### Tools and concepts

Services I used were DeepSeek, Ollama, Chatbox AI, and ChatGPT. Key concepts I learnt include temperature in AI models, parameters in models, and the downsides of running a webapp. After reviewing DeepSeek and OpenAI, I personally preferred ChatGPT. 

### Project reflection

This project took me approximately 2 hours. The most challenging part was honestly my interent speeds struggling to download the apps. It was most rewarding to start using DeepSeek in ChatBox AI. 

I did this project to learn how to use DeepSeek which is very in demand at the moment. This project met my expectations and even exceeded them! 

---

## Exploring DeepSeek

DeepSeek is an LLM that has recently made headlines. Their R1 model gained attention for outperforming most current models on the market despite being made for a fraction of the costs. The R1 model reasons and shows thinking of it's steps and process

While you could access DeepSeek over the web app, some concerns are the app requires constant internet connection, has latency issues, and processes queries through external servers. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/ai-llm-deepseek_aaaaaaaa)

---

## Ollama and DeepSeek R1

Ollama is a tool that allows you to host LLMs that are open source on your local machine. It handles the download process and allows you to control the temperature. 

You won't be able to find OpenAI models in Ollama because OpenAI's models are not open sourced. 

I tested using DeepSeek offline by using it in my local terminal with wifi off and observed the DeepSeek model thinking/"reasoning". You can also see 'think' tags in the terminal because in this case the prompt I asked was simple.

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/ai-llm-deepseek_gggggggg)

---

## DeepSeek R1 Sizes

DeepSeek R1 has different model sizes, including 7b. The model sizes are defined by parameters, which means that the model can handle more complex tasks (however this is dependent on how well the model is trained). 

The R1 model you choose to run locally depends on the amount of storage space I have on my machine. Having different model sizes help with running R1 locally because we can adjust based on our needs. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/ai-llm-deepseek_iiiiiiii)

---

## Chatbox

To complete my local setup, I installed Chatbox to my local machine. My Chatbox settings use Ollama API as the default to host the Deepseek model. 

I tested a lower parameter R1 model size, using the prompt "How many r's in the word strawberry?". The results given were incorrect, as the output said 2 r's instead of 3. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/ai-llm-deepseek_kkkkkkkk)

---

## Temperature Settings

The temperature setting in an LLM determines the randomness or creativity output of an LLM. To see this in action, I have used this prompt "Create a recipe for a dessert that includes avocados, chocolate, and sea salt." to compare results. 

I started a third chat with ChatGPT to compare the temperate of the two responses. ChatGPT's analysis will also help me understand how temperature is determined. 

ChatGPT quickly figured out which piece was generated with a high temperature, because the first response appears to be generated at a higher temperature, showing more randomness and creative (though sometimes inconsistent) elements. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/ai-llm-deepseek_aregearg)

---

## DeepSeek vs. OpenAI

 I decided to compare DeepSeek R1 with OpenAI by running a task that requires both Python knowledge and physics principles to create a ball that bounces in real-time. 

To test ChatGPT's response, I ran the script in Trinket.  ChatGPT's results were very solid. A ball animation bouncing around a square worked perfectly, maybe just a little laggy but teh physics seems relatively accurate. 

Compared to ChatGPT's performance, I thought DeepSeek's response was rather mediocre. The ball was not following a path that made sense and would change directions randomly. I prioritise accuracy, so in this case ChatGPT wins the point. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/ai-llm-deepseek_dfgbewrwq3)

---

## Token Efficiency

---
