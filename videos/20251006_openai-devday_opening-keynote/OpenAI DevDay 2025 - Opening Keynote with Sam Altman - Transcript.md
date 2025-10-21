# Transcript: OpenAI DevDay 2025 Opening Keynote with Sam Altman

**Date:** October 6, 2025
**Event:** OpenAI DevDay 2025
**Location:** Fort Mason, San Francisco
**Speaker:** Sam Altman, CEO, OpenAI

---

## Opening Remarks - Sam Altman

[00:27] Thank you. Good morning, and welcome to Dev Day. Thanks for being here in San Francisco, the city where we started and where we are committed to building the future of AI.

[00:43] It's been almost two years since our first dev day. We, but most importantly, all of you, have come a long way since then. Back in 2023, we had 2 million weekly developers and 100 million weekly ChatGPT users. We were processing about 300 million tokens per minute on our API. And that felt like a lot to us at least at the time.

[01:04] Today, four million developers have built with OpenAI. More than 800 million people use ChatGPT every week, and we process over 6 billion tokens per minute on the API, thanks to all of you. AI has gone from something people play with to something people build with every day.

[01:21] Before we get started with all of today's announcements, we want to do something fun. On the screen behind me are the names of the developers in the room who have built apps on our platforms that have crossed some big milestones. 10 billion tokens processed, 100 billion, even 1 trillion. Let's give them a round of applause.

[01:49] On behalf of all of us at OpenAI, thank you for doing such incredible work. You are the ones pushing the future forward, and seeing what you've already done makes us so excited about what comes next.

[01:59] While it's exciting to celebrate how far you all have come, we are still so early on this journey. So today we're going to focus on what matters most to you all, which is making it easier to build with AI. We've been listening to developers, hearing where you get stuck, what you want us to build next so that you can build more things.

[02:17] We've got four things for you today. We're going to show you how we're making it possible to build apps inside of ChatGPT and how we can help you get a lot of distribution. We're going to show you how building agents is going to be much faster and better. You'll see how we're making it easier to write software, taking on the repetitive parts of coding so you can focus on systems and creativity. And underneath all of this, we'll give you updates to models and APIs to support everything you want to build.

[02:48] We think this is the best time in history to be a builder. It has never been faster to go from idea to product. You can really feel the acceleration at this point.

---

## Apps Inside ChatGPT

[02:55] So to get started, let's take a look at apps inside of ChatGPT. We want ChatGPT to be a great way for people to make progress, to be more productive, more inventive, to learn faster, to do whatever they're trying to do in their lives better. We have been continuously amazed by the creative ways that people use it.

[03:13] Since our first Dev Day, we've been working to try to figure out how to open up ChatGPT to developers. And we've tried things like GPTs, we've adopted standards like MCPs, and we've made it possible for developers to connect ChatGPT to more and more applications. Some of this stuff has worked, some of it hasn't, but we've learned a lot along the way.

[03:32] And today we're going to open up ChatGPT for developers to build real apps inside of ChatGPT. This will enable a new generation of apps that are interactive, adaptive, and personalized that you can chat with.

[03:45] So to build them, today we're launching the Apps SDK, which will be available in preview starting today. With the Apps SDK, you get the full stack. You can connect your data, trigger actions, render a fully interactive UI, and more. The Apps SDK is built on MCP. You get full control over your back-end logic and front-end UI. We've published the standard so that anyone can integrate the Apps SDK.

[04:10] When you build with the Apps SDK, your apps can reach hundreds of millions of ChatGPT users. We hope this will be a big deal for helping developers rapidly scale products. Thank you.

[04:31] If a user is already subscribed to your existing product, they'll be able to log in right from the conversation. And in the future, we're going to support many ways to monetize, including the new Agentic Commerce Protocol that offers instant checkout right inside of ChatGPT.

[04:45] So let's take a look at a few examples. When someone's using ChatGPT, you'll be able to find an app by asking for it by name. For example, you could sketch out a product flow for ChatGPT and then say Figma, turn the sketch into a workable diagram. The Figma app will take over, respond, and complete the action. You can also then launch FigJam from ChatGPT if you want to iterate further.

[05:09] We're also making apps discoverable right in the conversation. So when a user asks for something, we can surface a relevant app as a recommendation. Maybe a user says they need a playlist for their party this weekend. ChatGPT could then recommend building it in Spotify. It's an easy way to find the right app or have the right app presented to you at the right time. And there will be a whole bunch of new ways for developers to get discovered.

[05:31] So now, rather than just talk about this, I'd like to invite Alexei to the stage and we will show you a live demo.

---

## Apps SDK Demo - Alexei

[05:42] Hi, I'm Alexi, a software engineer on ChatGPT working on Apps SDK. I'm super excited to showcase some of the first apps users will be able to interact with today. The magic of these apps is combining their rich interactive visuals with the power of ChatGPT.

### Coursera App Demo

[05:58] Let's start with Coursera. Let's say I don't spend enough time thinking about machine learning at work and I want to learn more. I could ask the Coursera app in ChatGPT to help me learn more about this. I can say, Coursera, can you teach me something about machine learning?

[06:19] Since this is my first time using Coursera in ChatGPT, I'll need to consent to connect. The next time I use it, I'll be able to dive in immediately. You'll notice I asked ChatGPT for the Coursera app directly, but ChatGPT can also suggest apps if relevant to the conversation.

[06:43] Apps in ChatGPT by default are displayed inline and can support anything that you can render on the web, like this video shown here. Apps SDK also supports picture in picture or expanding to a full screen layout.

[06:57] So now that I have my course up, let's play the video. Playing the video immediately pins it to the top of my screen, which is really helpful for something like Coursera because you can access your conversation while watching the video.

[07:11] Let's skip ahead a little bit and say I want to go a little bit deeper on something mentioned in the video. I can ask ChatGPT, can you explain more about what they're saying right now.

[07:28] Apps SDK provides an API to expose context back to ChatGPT from your app, ensuring that the model always knows about exactly what your user is at right now. We're calling it talking to apps, and it's really part of the magic here. I'm super excited about how learning with ChatGPT, one of our top use cases, is continuing to get better. And with apps and the apps SDK, you can unlock richer educational experiences for users around the world.

[07:55] So here, ChatGPT responded and explained that the instructor is talking about data preparation steps before training a machine learning model. And then it breaks it down in simple terms for me. I don't need to explain what I'm seeing in the video. ChatGPT sees it right away.

[08:09] So here I was able to connect to Coursera's app, discover and start playing a course, and directly engage with the video through text, all within my existing ChatGPT conversation. Pretty cool.

### Canva App Demo

[08:20] Users also love being creative in ChatGPT. Here I have a conversation where I've been brainstorming some ideas to help my younger sibling's dog walking business. We've gone back and forth a few times, and now it's time to make this into a reality.

[08:35] I'm pretty happy with some of the names here, so let's take this walk this wag name. And now I'm gonna ask Canva to turn that into a poster. I can say, Canva, can you make me a poster with the walk this wag name? I want it to be colorful, whimsical, bright and I prefer oops, I asked Coursera for a typing course too, maybe. I prefer sans serif fonts. Cool. Send that off.

[09:10] And now in the background, Canva is generating posters based on the context from my conversation. Canva is great at creating assets like this, and now you can kick it off directly from ChatGPT. Whether you're making professional marketing assets for OpenAI or just a fun demo for Dev Day, Canva is right there in the conversation as you work.

[09:31] Apps SDK, as Sam mentioned, is built on MCP, an open standard we've loved building on at OpenAI. And if you have an existing MCP, it's really quick to enhance it with the app's SDK. All you have to do is add a resource that returns HTML, and the app would be able to be up everywhere ChatGPT is distributed across web and mobile.

[09:56] As you can see, this is a live demo, so we're experiencing a little bit of latency, but here we go. Canva has returned four poster examples to us. We see them in line, just like the Coursera video, as well as ChatGPT kind of explaining what it's done for us.

[10:10] But we can explore another modality in Apps SDK, which is full screen. I click an asset and the app requests full screen. We are able to focus on a specific asset. And from here, I can see it in more detail. I can ask ChatGPT to request changes, maybe visual tweaks, just like with our image generation experience.

[10:28] But since we're in San Francisco and it's Dev Day, let's ask Canva to convert this into a pitch deck. I can say, Canva, can you please make this poster into a pitch deck? We're trying to raise a seed round for dog walking. I'll send that off, and since now Canva is going to make us a couple of slide decks, it may take a moment. So in the interest of time, we'll move on to show one more demo while that loads.

### Zillow App Demo

[10:59] Say the dog walking business is going really well and we want to expand to another city. I can ask ChatGPT, based on our conversations, what would be a good city to expand the dog walking to. ChatGPT, of course, knows what we've been talking about. Super enthusiastically, says Pittsburgh. Great.

[11:23] Now I can invoke the Zillow app to say, please show me some homes for sale there. And now ChatGPT is talking to Zillow to fetch the latest housing data, and we'll get an interactive map embedded in ChatGPT. And we'll explore how the full screen experience there goes.

[11:43] So we have our map, gorgeous loading state, and boom, we have a bunch of homes here. It also looks like our slide decks are done, so we'll go back to those in a moment. But this map is a little hard to see in the inline view, so I can click a specific home and open it full screen.

[12:05] And now we have most of the Zillow experience embedded in ChatGPT. You can request a tour, all the actions that you would expect from Zillow. But we have a lot of options here, and it's kind of hard to parse. So I can ask ChatGPT: can you filter this to just be three bedroom homes with a yard? For the dog, of course.

[12:24] ChatGPT will talk to Zillow again. And because the app is in full screen, it can now just update the data that's provided to it without needing to create a new instance. We see ChatGPT came back. We get the message overlaid here. If I click that, I can view my conversation over the Zillow app and even open it to the full height. Cool.

[12:45] Let's zoom in and find a specific home we may be interested in. Now, because the Zillow app is exposing context back to ChatGPT, it knows what I'm looking at. I can ask for more information about this home, like How close is this to a dog park?

[13:02] ChatGPT is able to compose the context from Zillow with other tools at its disposal, like search. So it's able to give more information about this home. From here, I could invoke other Zillow tools, maybe find out the affordability of it, but it'll provide the best answer every time.

[13:19] This is a great example of how dynamic an experience with Apps SDK can be. This all started from an inline map, and now we're able to go back and forth between talking to the app, asking ChatGPT questions, or just using the Zillow experience.

### Canva Slides

[13:31] Let's check back in on those slide decks. So if I pop back over into this conversation, see Canva has given us a few options here. Like the look of this blue, so if we open that up, we now see the slides in full screen, and I can see all the beautiful slides that Canva has generated for me.

[13:50] When I'm ready, I can just like the posters, I could ask for follow-up edits. And when I'm ready, I can open this in Canva to get the real slides out and hopefully close the seed round.

[14:06] So there it is, the magic of apps in ChatGPT, conversations that unite the intelligence of ChatGPT with your favorite products, resulting in truly novel experiences. I'm so excited to keep building this with all of you. Can't wait to see what you do with it. Now back to Sam for more on apps.

---

## Apps SDK Launch Details - Sam Altman

[14:28] That was awesome. Thanks, Alexi. That was great. It's very hard to type and talk in front of a bunch of people at the same time, so you did very well.

[14:37] We're excited for you to try out the apps that you saw in the demos, along with a few more from these launch partners. They'll be available in ChatGPT today. And this is just the beginning. We're going to roll out more apps from partners in the weeks ahead.

[14:49] For developers, the Apps SDK is available in Preview to start building with today. Our goal is to get this in your hands early, hear your feedback, build it together with you. And then later this year, developers will be able to submit apps for review and publication.

[15:04] We'll also release a directory that users can browse. In addition to discovery and conversation, any apps that meet the standards provided in our developer guidelines will be eligible to be listed. Apps that meet higher standards for design and functionality will get featured more prominently, including in the directory and suggested as apps and conversations.

[15:23] We've published a draft of the developer guidelines along with the Apps SDK, so you'll know what to expect. And we'll share more on monetization from apps soon. We'd also love your feedback about what you'd want. This should be an exciting new chapter for developers and for ChatGPT users. So that was apps, and we hope everyone loves it. Thank you.

---

## AgentKit Introduction - Sam Altman

[15:48] So next we want to talk about building agents and how we're going to make this simpler and more effective. AI has moved in the last couple of years from systems that you can ask anything to systems that you can ask to do anything for you. And we're starting to see this through agents, software that can take on tasks with context, tools, and trust.

[16:07] But for all the excitement around agents and all the potential, very few are actually making it into production and into major use. It's hard to know where to start, what frameworks to use, and there's a lot of work. There's orchestration, eval loops, connecting tools, building a good UI. And each of these layers adds a lot of complexity before you know what's really going to work.

[16:28] Clearly, there's a ton of energy and the opportunity is very real. So we've talked to thousands of teams, many of them in this room, who are building agents to reimagine how work gets done. And we've asked what we can do to make agents much easier to build.

[16:42] So today we're going to launch something to help with that. The goal here is something for every builder that wants to go from idea to agent faster and easier.

[16:50] So we're excited to introduce a new thing called AgentKit. AgentKit is a complete set of building blocks available in the OpenAI platform designed to help you take agents from prototype to production. It is everything you need to build, deploy, and optimize agentic workflows with way less friction. Our hope is that everyone from individual developers to large enterprises will get a lot of value from this. And we'll talk about a few of the core capabilities now.

### Agent Builder

[17:17] So the first one is Agent Builder. This is a canvas to build agents. It's a fast visual way to design the logic steps, test the flows, and ship ideas. It's built on top of the Responses API that hundreds of thousands of developers already use. So most of you who have used our platform before should be familiar with the foundation.

### ChatKit

[17:36] The second thing is ChatKit. We've heard this one loud and clear, and we're making it easy to bring great chat experiences right into your own apps. You get a simple, embeddable chat interface that you can make your own. You can bring your own brand, your own workflows, whatever makes your own product unique. And you can see in the video here how chat can work across each agent node and call on tools to form the best response.

### Evals for Agents

[17:58] And then finally, evals for agents. We're shipping new features dedicated to measuring the performance of agents. You get trace grading to help you understand agent decisions step by step. You get data sets so you can assess individual agent nodes. You get automated prompt optimization. And you can even now run evals on external models directly from the OpenAI platform. This is all the stuff that we wished we had when we were trying to build our first agents.

### Data Access

[18:26] And of course, agentic access to data. So with OpenAI's Connector Registry, you can securely connect agents to your internal tools and third party systems through an admin control panel, while keeping everything safe and under your control.

### AgentKit Examples

[18:41] So let's look at a couple of examples. Albertsons runs over 2,000 grocery stores across the U.S. More than 37 million people shop there each week. And each store is like its own little economy. Managers have to make all these constant decisions, tweaking this promotion or that product mix, resetting the displays, working with a bunch of vendors. It's like a lot of stuff.

[19:02] So Albertson's built an agent using AgentKit. So now imagine a situation where sales are unexpectedly down for ice cream, down 32%. Before, this would have kicked off a long process of reporting. There'd be spreadsheets and meetings, a lot of panic, they sell a lot of ice cream, very important to them.

[19:18] Now an associate can just ask the agent what's going on. The agent will look at the full context of everything it can discover, seasonality, historical trends, external factors, and it will give a recommendation. Maybe it's time to adjust the display or to run a local ad.

[19:34] So let's take a look at another agent. HubSpot is a customer platform used by hundreds of thousands of organizations around the world. And they used AgentKit to improve the responses of Breeze, their AI tool, using the custom responses widget.

[19:50] So in this example, a HubSpot customer called Luma Plants gets a question about why a plant is not doing so well in Arizona. It then uses the Breeze assistant to search its own knowledge base, look up local treatments for the state's low humidity, pulls in policy details, and puts everything together. It then offers multiple ideas and a recommendation.

[20:09] So this is how we imagine intelligence working across many different sources, all operating together to deliver smart, useful answers to customers. And it's a great example of the thing that you can build with AgentKit.

[20:20] We have a bunch of great agent launch partners that have already scaled agents using AgentKit. And it's available to everyone starting today.

[20:29] So let's do a live demo, and I will pass it off to Christina.

---

## AgentKit Demo - Christina

[20:41] Thanks, Sam. Hi, everyone. I'm Christina, and I work on the team building AgentKit. Today, I want to show you how AgentKit helps developers create agents faster than ever before.

[20:50] So, you may have already seen our Dev Day website. It's the site here that all of you have access to and has everything about today's schedule. But right now, it's just a static page. What if it could actually help you navigate the day and point you to the sessions that are most relevant to you?

[21:07] We're OpenAI. We need to have AI in our Dev Day website. So that's what we're going to build together: an agent powered by AgentKit deployed right here inside this site.

[21:17] And to make this interesting, I'm going to give myself eight minutes to build and ship an agent right here in front of you. You just heard how hard it is to build an agent, so this is going to be a bit of a challenge. And I'm going to start the clock now to keep me honest. We have a clock going.

### Building the Workflow

[21:35] So I'm starting in the workflow builder in the OpenAI platform. And instead of starting with code, we can actually wire nodes up visually. Agent Builder helps you model really complex workflows in an easy and visual way using the common patterns that we've learned from building agents ourselves.

[21:51] So here on the left, we've already extracted the common building blocks. For example, tools like file search and MCP, guardrails, human in the loop, and other logical nodes.

[22:01] Today, I'm planning on building a workflow that uses two specialized agents. The first will be a sessions agent, which will return information about the schedule. And the second will be a more generic Dev Day information agent.

[22:12] So I'm starting off with a categorizing agent to just help route and categorize the type of message coming in, whether it's asking about a specific session or something more generic. And then I've added in an if-else node to route behavior based on that classifier.

### Creating the Session Agent

[22:28] Next, I'll create the session agent. Here, I'll drag and drop an agent node. I'll call this session agent. I'll give it the context about kind of grabbing information about a session. And then I can add in various tools here.

[22:43] Today I already have a doc with all the information about sessions, so I'll simply drop that in. Let's call this sessions and attach it. So this agent now has all of the information needed to answer my questions.

[22:56] But showing the schedule should also be fun and visually interesting, not just plain text. So I'll also create a widget for them. I'll head over to our widget builder. Here I could create a widget from scratch. I can browse the gallery to learn about other widgets and reuse them.

[23:12] But for today, I've actually already designed a widget for this use case. In this case, it's an onboarding session widget for Froge, one of our Dev Day friends that you'll see around the venue. Who's holding a 101 onboarding session in Golden Gate Park?

[23:26] So we can simply download this and then head back over to our agent and just attach it in as I don't think I clicked download. So let me go back and actually click the button. Download. There we go.

[23:49] Great. So head over and attach it as an output format for the sessions agent that we just created. Drop that in. We can preview it to make sure we added in the right widget, and everything looks ready to go. So this session agent is now done.

### Creating the DevDay Agent

[24:02] Next, I'll create the general DevDay agent. So once again, I'll drag in an agent node. Let's call this the dev day agent. We'll once again give it some context about what it's doing. And then we'll also make it speak in the style of Froge, just to make it really on brand with the day.

[24:20] We'll add in a file once again. So we have a file with all of the information about the day. Call this dev day. Attach it. This agent is ready to go as well, and we'll attach that here.

### Adding Guardrails

[24:35] Now, it looks like I have a couple more minutes, so let's add in some additional security with one of the pre-built guardrails. So one of the most important things when building agents is being able to trust them. And guardrails help you have that confidence, protecting against hallucinations, adding moderation, blocking PII.

[24:51] In this case, we already have a couple pre-built guardrails. I'll turn one on for PII, and then I'll just include name as well so I can easily verify its behavior.

[25:01] I'll attach this in to the beginning of the workflow to make sure Froge is really protected against PII, and then I'll add in an additional agent to handle cases when this information is passed in. So again, I'll make it speak in the style of Froge to stay consistent. And I'll remind it that it cannot help with questions that contain sensitive information and remove kind of the context.

[25:27] Great, so I think this workflow is ready to go. I can also configure the output to determine what shows up to the end user. In this case, I can also turn off file search sources if that is kind of more internal. And I think that's it.

### Testing the Agent

[25:41] Let's test it out. I can preview this directly from our agent builder. So here I can ask what session to attend to learn about building agents.

[25:53] And I can see this message moving its way through that workflow we just created, checking guardrail, categorizing intent, pulling information from the file of sessions that I just added in, finding the right session, using the widget that I added, and determining, you know, orchestrating agents at scale at 11:15 with James and Rohan is like the best session for me to go to to learn more about this.

[26:15] And then I see a couple ribbits because this is actually Froge talking to me and ribbitting at me. So, okay, I think this agent looks good. Need to watch the time.

### Publishing the Agent

[26:25] So we just built a few specialized agents using tools. We added in guardrails. We customized them using some widgets. And then we also tested out the workflow in preview.

[26:33] The one thing we haven't yet done is a full set of evals, and we can also do that directly from the agent builder to make sure that everything behaves exactly as expected before going live. But right now, I've got a giant clock chasing me, and Dev Day is waiting, so let's publish this.

[26:48] Hit publish here. Let's call this askFroge. Hit publish. And I now have a fully deployed published agent in production with a workflow ID that I can use to run directly.

[27:07] On the right, we also have code export in case I want to run this in my own environment, in my own servers. But you can see this is quite a bit of code to write. And so I'm just going to stick with using the workflow ID that we just created and then head over to my site.

### Integrating with the Website

[27:22] So here in my Dev Day site, I'm first going to create a chat kit session using the workflow that we just created. I'll simply drop in that workflow ID. I'll add in the chat kit React component using that client secret that we just created in our own server, and then adding in visual customization as well to again make this really Froge themed.

[27:43] In this case, it's going to be called Ask Froge. It's going to continue to rivet in the placeholder. And it'll have some Froge-specific colors and starter prompts.

[27:52] I'll add this Froge chat in a bottom sheet, so it'll come up from the bottom of the page. And then finally, I'll add in a link to Ask Froge at the top of the site so that it's really front and center on our website.

[28:03] So let's go back to our site. There it is. Ask Froge, top of the site. Let's try it out. So what session to attend to learn about building agents?

[28:17] And again, this is running through the exact same workflow we just created, checking for guardrails, categorizing the message, pulling from tools from file search, using the widget that we designed, and then again deciding orchestrating agents at scale is the right session for me to go to and continuing to rivet in the style of Froge.

[28:35] So, okay. Great, we've done it. The agent is ready. We can stop the clock. The agent is ready with 49 seconds to spare.

[28:50] And I can keep iterating on this agent directly in the visual builder and also deploy these changes directly to my site without making any code changes at all. This includes adding new tools, adding new widgets for other use cases, adding new guardrails, and I can even wire it up to client-side tools to take actions directly in my website.

[29:10] So in just a few minutes, we've designed an agent workflow visually. We added in some tools and widgets. We previewed it. We deployed it. We tested it and now you all can use it.

[29:22] This is actually live now in your Dev Day site. You can tap your badge and you should be able to see it and use it. Find the sessions that are best for you. So, we're looking forward to you using it and meeting Froge and also seeing all the new experiences that you'll now be able to build using AgentKit. Thanks, and back to Sam.

---

## Software Engineering with AI - Sam Altman

[29:48] Thank you, Christina. I think that's so cool. I can't wait to see what y'all all build with it.

[29:53] So we've looked at AI apps, agents, but now let's shift to one more thing that's just as important, how we write software. One of the most exciting things happening with AI is that we're entering a new era that changes how software gets written. Anyone with an idea can build apps for themselves, their families or their communities.

[30:14] And before we talk about Codex, we want to show you a few examples. In Japan, an 89-year-old retiree taught himself to code with the help of ChatGPT. He's now built 11 iPhone apps for elderly users. He's turning a lifetime of wisdom into tools that help others live more independently.

[30:33] In Spain, Pao Garcia and members of domestic data streamers are helping people reconnect with memories using ChatGPT, image generation, and Sora.

[30:44] At ASU, med students needed a better way to practice the kinds of difficult human conversations they'll have as doctors. So they built a virtual patient app with our models, where they can try, fail, and get better before they step into a real exam room.

[30:58] And at Versailles in France, visitors can now walk the palace and talk to it. They built an experience where you have a live discussion with art and sculptures with our real-time API. History becomes a conversation.

[31:12] It's awesome to see what people are building, and this is why we're so excited to give developers even more tools to build faster.

---

## Codex General Availability

[31:20] So earlier this year, we launched a research preview of Codex, OpenAI's software engineering agent, built to work alongside developers and speed up how software gets created. Since then, Codex has become very loved and grown into a much more capable collaborator.

[31:37] It works everywhere you code now: your IDE, the terminal, GitHub, and in the cloud. Your ChatGPT account connects everything, so you can move your work seamlessly between your tools.

[31:49] We've released a ton of new features for Codex, and it now runs on the new GPT-5 Codex model, a version of GPT-5 purposely trained for Codex and Agentic Coding. This model is better at tasks like code refactoring and code review, and it can dynamically adjust its thinking time for the complexity of the task.

[32:07] Developers love this new model. And the Codex usage has gone up really fast. One of our key metrics for looking at this is daily messages, the number of tasks and conversations that developers have with Codex each day. Since early August, daily messages are up 10x across Codex.

[32:22] And this rapid usage has also helped GPT-5 Codex become one of our fastest growing models ever. Since its release, we have served over forty trillion tokens from the model.

[32:33] Internally, at this point, Codex is everywhere we build. Almost all new code written at OpenAI today is written by Codex users. Our engineers that use Codex complete 70% more pull requests each week, and nearly every OpenAI PR goes through a Codex review. And from that, people get more depth than they'd expect, even from a very senior engineer.

[32:54] Starting today, Codex is officially out of Research Preview and into GA. And welcome. Thank you.

### New Codex Features for Teams

[33:06] And while Codex already has a lot of traction with individual developers, today we're introducing a new set of features to make Codex more helpful for engineering teams.

[33:16] First, we have a Slack integration. This has been very much requested, so that you can ask Codex to write code or answer questions directly from team conversations in Slack.

[33:25] Second, a new Codex SDK, so that you can extend and automate Codex in your team's own workflows.

[33:32] And third, new admin tools and reporting, including environment controls, monitoring, analytics dashboards and more, so that enterprises can better manage Codex.

[33:42] Expect to see a lot more Codex improvements coming soon.

[33:46] One of the things that's been really inspiring to us is to see the breadth of people using Codex, from developers building side projects on weekends to high growth startups to big global enterprises. Cisco rolled out Codex across its entire engineering org. They're now able to get through code reviews 50% faster and have reduced the average project timeline from weeks to days.

[34:09] So for our next demo, we want to show you something fun. We're going to show you how you can use the new Codex and our APIs to turn anything around you into workable software. And for that, please welcome Ramon to the stage.

---

## Codex Live Demo - Ramon

[34:26] Good morning, everyone. Last year, we built an iPhone app from scratch, and we've even programmed a Mini Drone live on stage using O1, our first reasoning model. It was kind of vibe coding before we even had a name for it, frankly. But the progress since has been incredible.

[34:42] Codex is now a teammate that understands your context, it works alongside you, and it can reliably take on work for your team. And we thought about how do we best show you all of the cool things that Codex can now do. We had a lot of ideas, but one that we kind of kept coming back to is what about building something that we could all experience and see together here in this room right now? So that's our challenge.

### Building Camera Control

[35:05] If you look up here, some of you might notice a camera that's mounted above the stage. And I thought maybe we could start there. And so earlier, I asked Codex CLI to create a very simple control panel interface with a simple interface. See a camera feed on the left. Some buttons on the right, and if we can bring my laptop on screen, you'll see what Codex came up with.

[35:29] Initially, it did it really well, but then I also added the Figma branding from the Dev Day event, so it could pull the exact colors and components to actually render it perfectly matching our design. Great, so that's our place to get started.

[35:44] Now, I haven't written a single line of code, but let's dive in and see what we can do on top of that. Now switching over here to we're going to skip this version. Skipping over here to my terminal, which I wanted to update, I'm sure you can see that we have Codex CLI. It's logged in with my ChatGPT account, and it's powered by GPT-5 Codex, our new model that Sam mentioned.

[36:09] Now let's start by asking this question that I'm sure many of you have not asked a coding agent before. How to control a Sony FR7 camera in Node? And honestly, I did not know how to get started. I saw there was a C++ SDK and I thought maybe Codex would want to use that and turn it into JavaScript. But then it had a much better idea than that. It realized that there's a Visca protocol to control these cameras.

[36:31] So as you can see, Codex can respond pretty fast for questions like this. And this all seemed promising to me. So basically, I went ahead and I typed this script over to Codex to completely scaffold an integration using the Visca protocol and wire it up to that control panel.

[36:48] Now, Codex is becoming harder and harder to demo, by the way, because it can really work tirelessly on your task. I've seen it work for up to seven hours on a very big refactoring, for instance, and get it right, which is pretty outstanding.

[37:01] Here, if we switch over and if we scroll back up, you know it updated its plan along the way, wrote a lot of code and everything, and this was the final result. As you can see on the screen, it worked for over 13 minutes on that one task, but it did everything I wanted it to do.

[37:16] So let's take a closer look. If I jump over to VS Code now, you can see on the right side of the screen, we also have our Codex integration in the IDE. And these are the files that the Codex CLI came up with for the camera control.

[37:30] So you can see it built a node server, it also figured out all of the UDP packets to send to this camera. Imagine the time it would have taken me to actually learn this protocol that's over thirty years old, by the way. Codex even figured out that there was like some very specific headers to send for this particular camera.

[37:48] All right, so with these UI components now wired up, the server is running, so we can take a quick look and try this. So here, if I turn on the camera there we go, we have the camera. That's all of you. Awesome. And let's try the controls. Boom! I can actually control the camera now from this interface. It's pretty cool. All right.

### Adding Xbox Controller

[38:13] But controlling with buttons is nice, but I think we can do something better. So I'm going to try to send another task, but live this time inside our IDE extension. So check this out. Wire up an Xbox wireless controller to control the camera. So I'm going to send this one right now.

[38:33] I was backstage earlier and I found this Xbox controller. I wasn't sure who's playing back there, but I thought this could be something we could try. So we're going to leave it here.

[38:42] And as you can see now, like Codex made a plan. Apparently, three tasks have to be completed. It's now exploring the file. It's figuring out how to wire up this gamepad.

[38:52] And what's interesting here is you can see in the IDE we also have this concept of auto-context. And what that means is that your prompts can be pretty short because Codex will kind of understand your intent, it will see like the recent files that you've used and really kind of adjust accordingly.

[39:08] So as you can see, we're now at task number two. This one will probably take another minute or so, so we'll leave it run in the background.

### Voice Control and Lighting System

[39:16] So in the meantime, what else could we do? Well, I thought one exciting interface is voice. So to save us a few minutes, I've already asked Codex to integrate with our real time API and our AgentKit SDK. And I wanted to wire up all of this into the app right here on this green little dot at the bottom right of the screen.

[39:36] But what's great about the real-time API is that it brings natural speech-to-speech into your app, but it also connects to any MCP server in the context of that conversation. And so that really got me thinking, what else could we show you in this room and turn into an MCP server?

[39:52] And then I thought, wait, we have a lighting system, so maybe we could wire up the lighting system of the venue over to an MCP server. So let me check out this task that I sent to Codex, but this time in Codex Cloud.

[40:06] So you can see here my prompt. I asked Codex to wire up this MCP server for this very specific model of lighting system. I gave it the reference docs that I found, and I gave it the exact interface that I want it to have for my UI to work.

[40:22] But what's fascinating to me is like if you look at the logs, for instance, like that's really the magic of the agentic behavior of Codex. I could have asked a teammate to do that, but because the task was very specific, now Codex is my teammate.

[40:37] And if you look at how it went through the process, it actually figured at some point that it needed to kind of find new information about Command 8 to move forward. So then it went ahead to fetch the GitHub docs again to kind of really operate and call tools along the way. And that's really the magic of GPT-5 Codex. You can really let it go off, do some complex tasks, and you'll see this agentic behavior emerge.

[41:00] And then after that, I did one more turn to actually ask Codex to like include the README information so I can understand how to run it. And sure enough, here is my MCP server.

[41:09] Now going back to VS Code, what's also very interesting sounds like the Xbox task just finished. We'll see that in a moment. Awesome.

[41:18] And now going back here, you can see that you have all of your local but also your cloud tasks right here inside the VS Code extension. So if I click on the build MCP server, for instance, this is the task I just showed you on Codex Cloud. And here, I can actually apply all of the changes locally if I want to test them. So I can just go ahead and click apply, and now all of the changes with this MCP server are now included locally.

[41:42] Now I didn't want to watch you I didn't want to let you watch me do npm install here on stage. So I just took that MCP server already and I started to install all of the dependencies to make it run.

### Testing Everything Together

[41:55] So let's now put all of that to the test. But first of all, if we go back to our app right here, let's see if we can actually control this camera now with this Xbox controller. There we go, it works. That's pretty awesome.

[42:10] What's funny is like I didn't even specify to Codex which button should do what, but it figured that the joystick was probably a good idea. So that's actually perfect.

[42:17] But let's do the real test now. Let's enter voice mode and see what happens. So sorry in advanced AV team, but we'll try to see if Codex figured this out to control the lights.

[42:29] Hi there.

[42:34] **Voice Agent:** Hello? Hi there, I can hear you loud and clear. Let me know what you need.

[42:41] Yeah, what do you see on the camera?

[42:45] **Voice Agent:** I see a large audience in front of you, with rows of attendees seated and ready. The room is well lit, and the crowd stretches far back, filling the space.

[43:01] **Voice Agent:** I've just lit up the audience with a nice bright wash. They should be perfectly highlighted now.

[43:09] Can you greet everyone here in the room now?

[43:14] **Voice Agent:** Absolutely. The audience lights are up. Let's welcome this fantastic crowd. Hello, amazing developers at Fort Mason. We are so excited to have you here for an incredible day.

[43:27] Awesome. Could you now do something fun with the lights and say hi to people tuning in on the live stream?

[43:38] **Voice Agent:** We've got the fun lights rolling now. Some dynamic, colorful effects in motion. And to everyone watching the live stream, thanks for joining us. This is going to be an amazing experience.

[43:49] Cool. All right, let's go back to normal now.

[43:54] Awesome. So I still have not written a single line of code, by the way, to make this happen.

### Codex SDK

[43:58] But there's one more thing I wanted to show you. Last but not least, Sam mentioned that we're launching the Codex SDK today. And so I wanted to finish up with something that gives you a little bit of a glimpse into what might be the future of software engineering. So let me go back into voice mode and try this.

[44:20] Hi, could you ask Codex to show a credits overlay like at the end of the movie, but this time the cast is all Dev Day attendees?

[44:31] **Voice Agent:** I'm running that with Codex now. I'll let you know when it's ready.

[44:37] Great. In the meantime, could you start a countdown and take a photo of all of us?

[44:52] Oh, and there we go.

[45:02] So to explain you what just happened here, when I sent a task to the voice agent, it also added Codex SDK as a tool. And what that means is that now on the fly I can reprogram this app in real time and instantly adapt it to user needs or any kind of feedback they have.

[45:18] So in this case, when I asked to create a credits overlay, it was able to go ahead and edit the code inside this React app, autoreload it, find what it needed to complete the task, and now the credits are rolling. It's pretty amazing.

[45:33] So with all that, we took voice, we took a sketch, we took some devices around us, and we turned all of this into workable software. And all of that without writing a single line of code by hand.

[45:44] So really give Codex your most ambitious ideas, give Codex your most complex coding problems and see what happens. I think you'll be as amazed as we are every day. The only limit now is your imagination. Thank you so much. Back to you, Sam.

---

## Model Updates - Sam Altman

[46:05] Thanks, Ramon. This is the biggest change to how software gets created that I have ever seen. And we can't wait to see what you all will do with it. I think the future is going to be very bright.

[46:14] We've covered a lot today, but obviously models matter a lot too. So I want to share a few model updates.

### GPT-5 and GPT-5 Pro

[46:20] Back in August, we launched GPT-5. We trained it to be really good at steering agents and end-to-end coding, and GPT-5 has delivered on that. Leading coding startups like Cursor, Windsurf, and Vercel are using GPT-5 to change how software gets written and ship in their apps.

[46:37] And then after that, we released GPT-5 Pro, the most intelligent model that we've ever shipped. Today, we're launching GPT-5 Pro in the API. It's available to all developers, and we hope you enjoy.

[46:56] GPT-5 Pro is great for assisting with really hard tasks. Domains like finance, legal, healthcare, much more, where you need high accuracy and depth of reasoning.

### GPT Real-Time Mini

[47:07] We're also releasing a smaller voice model in the API with GPT Real-Time Mini. It is a smaller, seventy percent cheaper version of the advanced voice model we shipped two months ago, with the same voice quality and expressiveness. Personally, I think that voice is going to become one of the primary ways that people interact with AI. And this is a big leap towards that reality.

---

## Sora 2 for Creators

[47:30] Now I want to shift gears and talk about what's new for creators. And this has been a hotly requested one, so we hope you'll like it. We've been seeing incredible work from filmmakers, designers, game developers, educators, and more using AI as part of their creative process.

[47:45] Today we're releasing a preview of Sora 2 in the API. You now have access to the same model that powers Sora 2's stunning video outputs right in your own app.

[48:00] One of the biggest jumps that we've made with this model is how controllable it is. You can give it detailed instructions, and it holds onto the state while delivering results that feel stylized, accurate, and composed.

[48:12] For example, you can take an iPhone view and prompt Sora to expand it into a sweeping cinematic wide shot. But one of the most exciting things that we've been working on is how well this new model can pair sound with visuals. Not just speech, but rich soundscapes, ambient audio, synchronized effects that are grounded in what you're seeing.

[48:31] So, here's an example in this kayak video.

[48:45] You can also bring pieces of the real world into Sora too. For example, you could take a picture of your dog and give your dog some new friends.

[48:53] **Video Audio:** Look who's coming, buddy! Here they all are. Good pups. Come on. That's it, everybody together. Happy dogs.

### Concept Development

[49:06] Sora 2 is also great for concept development. You can just describe a general vibe or a product, and Sora will give you a visual starting point. So here, we're going to use it to generate concepts for an e-commerce ad.

[49:18] **Video Audio:** When your new place feels like a blank canvas, find the pieces that make it yours. Browse, customize, and check out in minutes. Delivered fast to your door.

[49:29] People seem to love Sora too. It's been on the top of the App Store since we've launched it, and the creativity that people are demonstrating has been super fun for us to watch.

[49:37] We hope that now with Sora 2 Preview and the API, you will generate the same high quality videos directly inside your products, complete with the realistic and synchronized sound, and find all sorts of great new things to build.

[49:49] Just like our other modalities, it's built for flexibility. You get to control video length, aspect ratio, resolution, easily remix videos.

### Mattel Partnership

[49:58] Mattel has been a great partner working with us to test Sora 2 in the API and seeing what they can do to bring product ideas to life more quickly. So one of their designers can now start with a sketch and then turn these early concepts into something that you can see and share and react to. So let's take a look at how this works.

[50:47] That is a very cool new way to build toys. And it's incredible to watch with AI how fast ideas can turn into shareable, workable designs. So we're excited to see what else you'll come up with as you use Sora 2 in your own products.

---

## Closing Remarks - Sam Altman

[51:01] We hope that today gave you a few ideas of new things to build. We want OpenAI to be a great platform for this new era of building. We think things are going to get pretty incredible pretty soon.

[51:11] All of our announcements today are aimed to support you in this work. The Apps SDK for building native apps inside of ChatGPT. AgentKit, so you can deploy agents wherever you'd like, easily and with more confidence. A more powerful Codex, changing the way software gets written, helping your team ship faster. And new models in the API: GPT-5 Pro, Sora 2, and Real Time Mini that expand what's possible.

[51:37] We're watching something significant happen, I think. Software used to take months or years to build. You saw that it can take minutes now. To build with AI, you don't need a huge team. You need a good idea, and you can just sort of bring it to reality faster than ever before.

[51:54] So, thank you all for being here, and thank you for building. Our goal, one second, I'm almost done. Our goal is to make AI useful for everyone. And that goal won't happen without all of you. So, we're very grateful that you're here to build with us.

[52:07] And also a huge thanks to the team that made today possible. A huge amount of work went into this. And there's a lot more work, there's a lot more happening throughout the day. So enjoy the sessions, and we'll see you later. Thank you very much.
