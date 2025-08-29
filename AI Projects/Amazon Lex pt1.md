<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a Chatbot with Amazon Lex

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-ai-lex1)

**Author:** Maximus Soares  
**Email:** maximus@nextwork.org

---

## Build a Chatbot with Amazon Lex

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-ai-lex1_505be5b8)

---

## Introducing Today's Project!

### What is Amazon Lex?

Amazon Lex is a chatbot service that allows you to create your own bot, and customise it's responses. 

### How I used Amazon Lex in this project

We used Amazon Lex today by selecting a voice, that responds to a users text for given words. We added in custom fallbackintents that give variable responses of fallback intent when the confidence threshold for the intent classification was below 0.4

### One thing I didn't expect was...

I didn't expect that AWS has implemented GenAI lex chatbot services. So I am curious to try these out.

### This project took me...

This project took me 40mins

---

## Setting up a Lex chatbot

I created my chatbot from scratch with Amazon Lex. 

While creating my chatbot, I also created a role with basic permissions because later in the project series we are going to call on AWS Lambda. Amazon Lex needs permission to call other services on my behalf. 

In terms of the intent classification confidence score, I kept the default value of 0.40. This means that if the bot has a 40%, or more, confidence in interpreting the users response - it will return an answer. Otherwise, it will return an error.

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-ai-lex1_97dc2351)

---

## Intents

Intents are what your user is trying to achieve by speaking to the chatbot. Eg if I ask Alexa to set a timer, my intent is to set a timer. 

I created my first intent, WelcomeIntent, to welcome the user and ask how the bot can help them. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-ai-lex1_505be5b8)

---

## FallbackIntent

I launched and tested my chatbot, which could respond successfully if I enter phrases that are within 0.4 of my intent classification score. 

Intent FallbackIntent is fulfilled` when I entered "good morning". This error message occurred because it wasn't within the 0.4 intent classification score of the words I provided in sample utterances.

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-ai-lex1_505be5b8)

---

## Configuring FallbackIntent

FallbackIntent is a default intent in every chatbot that gets triggered when the bot is less sure than the intent classication threshold. 

I wanted to configure FallbackIntent because I want to help users input in the correct information so they can get a response.

---

## Variations

To configure FallbackIntent, I inputted in closing response messages + variations. 

I also added variations! What this means for an end user is they won't always see the same fallback intent response. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-ai-lex1_c4fc89af)

---

## Initial Responses

---

---
