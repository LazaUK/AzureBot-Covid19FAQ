# QnA Bot, to support your team with the latest answers on the vital topics of interest. Costing you nothing, i.e. gratis!

<p align="center">
  <img src="/images/chatbot.png">
</p>

With coronavirus pandemic now spreading across the world and, unfortunately, claiming human lives, it's really vital to provide people with the up-to-date information on the latest learnings and recommendations from the reliable health authority sources.

With certain cities or even countries now in a lockdown mode, more and more people start to practice social distancing and work from home. Social anxiety and new ways of working can be challenging during periods of uncertainty. So, affected or worried people may require advice on how to stay healthy (physically and methally), while being isolated.

Chatbot is a paltform which can be particularly useful here. You can select specific sources to feed its knowledge base. Make your bot operate 24 x 7. Support multiple languages. And easily activate relevant channels, to communicate with your users in the apps of their choice: be it Web interface, MS Teams, Slack, Telegram or something else.

Sounds interesting ? If yes, just follow some simple steps below to create your own bot, train it on the frequently asked questions (FAQ) from the leading health organisations and make it then work on your external Web site (with template for a demo Web site provided) and internal MS Teams chats.

> **Note**: Solution described here requires access to an Azure subscription. Microsoft Azure is one of many cloud platfoms, offering chatbot building and hosting capabilities. Depending on your preferences and access options, as an alternative, you may build similar bot solutions on top of [Amazon's Lex](https://aws.amazon.com/lex/) or [Google's Dialogflow](https://dialogflow.com/) platforms as well.

## Covid-19 FAQ bot in minutes:
Building QnA bot is extremely easy and you indeed can enable access to your knowledge base via bot in minutes.
1. First of all, open [QnA Maker Web site](https://www.qnamaker.ai/), sign-in with your Microsoft account and then click "Create a knowledge base" option;
![Step1.1](/images/step1_1.png)
2. Next, click "Create a QnA service" button in "Step 1" as shown below;
![Step1.2](/images/step1_2.png)
3. You will be re-directed to your Azure subscription. Fill in the template form, and make sure to set pricing tier for "QnA Maker service" to **F0**, and for the supporting Azure Search service to **F**, if you want to host your Bot components for **free**. Then click "Create" button;
![Step1.3](/images/step1_3.png)
4. Azure will start deployment of the relevant resources in your target resource group. If successful, you should get notification similar to this;
![Step1.4](/images/step1_4.png)
5. By default, App service plan for the Web component is set to a chargeable S1 pricing tier. To switch to the free pricing tier, open your app service plan (you can find it by the resource type in your resource group), select "Scale Up (App Service plan)" on the left navigation bar, click "Dev/Test" tab, select **F1** pricing tier and then click "Apply button as shown below;
![Step1.5](/images/step1_5.png)
6. Now, return to our QnA Maker Web site and click "Refresh" button in "Step 2";
![Step1.6](/images/step1_6.png)
7. Once refreshed, you should be able to find your newly created QnA Maker service in the right Azure subscription. Also, you can select now the target language for your QnA service (set to "English" in example below);
![Step1.7](/images/step1_7.png)
8. Give a meaningful name to your Knowledge Base (KB) in "Step 3";
![Step1.8](/images/step1_8.png)
9. In "Step 4" you can specify sources to feed your knowledge base. It can be populated from Web sites (containing FAQ), uploaded from files (e.g., in PDF, MS Word, MS Excel, etc. formats) or typed manually. For this example, I'm populating my KB with Covid-19 FAQs from the [World Health Organisation](https://www.who.int/news-room/q-a-detail/q-a-coronaviruses) and [UK National Health Service (NHS) Trust](https://www.ulh.nhs.uk/covid-19-latest-staff-updates-and-faqs/) Web sites;
![Step1.9](/images/step1_9.png)
10. In "chit-chat" section you may choose "personality" for your bot, so that it can answer some additional small talk questions. This will enrich your KB with additional question/answer details, so you bot may respond to various greetings, as an example;
![Step1.10](/images/step1_10.png)
11. Now, in "Step 5", you can click "Create your KB" button, to setup your knowledge base and populate it with the data from the configured sources;
![Step1.11](/images/step1_11.png)
12. Once created, you will see a window like this with the content of your new KB.
![Step1.12](/images/step1_12.png)
13. You may test bot's knowledge base, by clicking "->Test" button, then typing your question and pressing "Enter".
![Step1.13](/images/step1_13.png)
14. If happy with your bot's answers, click "Save and train", then switch to "Publish" tab and click "Publish" button.
![Step1.14](/images/step1_14.png)
15. In the new window, click "Create Bot" button.
![Step1.15](/images/step1_15.png)
16. You will be re-directed to your Azure subscription, where you can set the pricing tier of your Azure Bot Service to **F0** (free one) and the click "Create" button.
![Step1.16](/images/step1_16.png)
17. 

## Embed your bot into Web site

## Enable your bot in MS Teams
