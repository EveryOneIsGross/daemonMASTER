# daemonMASTER

daemonMASTER is an innovative conversational tool platform that enables control over various bot instances. The name is a playful nod to both the concept of system daemons in the realm of computer science and the role of the Dungeon Master in tabletop role-playing games. Our platform gives life to rich "characters" - sophisticated chatbot instances that can be utilized in a variety of applications, beyond the realm of role-playing games. 

![daemonMASTERScreenshot01](https://github.com/EveryOneIsGross/daemonMASTER/assets/23621140/0289cd19-13b8-4cc2-91e1-9c063e3c582c)

> "With the building blocks you are using to build your Waifu, I'll begin to assemble the pieces of my Guru." - ChatGPT

## Project Description

daemonMASTER leverages AI technologies to provide a seamless interface for controlling and managing bot instances. It allows for the creation, customization, and control of these instances, providing a versatile toolset for any scenario requiring advanced conversational agents. 

One of our key features is the integration of animated avatars with gradio, enabling a visually immersive experience that further enriches the interactions with our bot characters.

![mermaid-diagram-2023-07-02-024054](https://github.com/EveryOneIsGross/daemonMASTER/assets/23621140/3c4607fc-d9ee-4f99-8266-76829e8888a2)

## Features

- Control and manage multiple bot instances
- Rich customization options for bot characters
- Integration of animated avatars with gradio
- (More features to be added)

## To Do

- [x] Develop core platform for controlling bot instances
- [x] Implement customization options for bot characters
- [x] Integrate animated avatars with gradio
- [x] Add individual memory creation and retention
- [x] Add simple openai embeddings for search
- [ ] Develop advanced NLP capabilities for bots
- [ ] Implement multi-platform support
- [ ] Expand avatar library in gradio integration

## User Experience

"daemonMASTER" is designed to perform a variety of tasks, including chatting, executing commands, summarizing text, extracting keywords, and searching through chat history. The user interface, powered by the Gradio library, is intuitive and easy to navigate, allowing users to interact with the chatbot seamlessly.

Customizing the Bot
Users can personalize the bot's name and behavior according to their preferences. The Gradio interface provides text boxes where users can input the desired bot name and define the bot's behavior.

Mode Selection
The chatbot operates in several modes that users can select from a dropdown menu. The available modes include 'chat', 'instruct', 'sentiment', 'summarise', 'keywords', 'last_responses', and 'search'. Each mode offers a unique functionality, providing a diverse range of interactions with the bot.

Input and Output
Users can input text into a provided text box, which the bot uses to perform the selected operation. The bot's response is then displayed in an output text box. Additionally, an image corresponding to the selected mode is displayed, adding a visual element to the interaction. IO is a create place to lead on to talking about M E M O R Y \m/

## Memory

Scalability and Future Dynamic Node-Based Interactions

The daemonMASTER chatbot's memory management system, which uses a verbose full language state stored in JSON format, is designed with scalability and future enhancements in mind. This system not only allows for efficient storage and retrieval of conversation history but also sets the foundation for more complex, dynamic node-based interactions in the future.

Scalability

The use of JSON for memory state management provides several advantages in terms of scalability. JSON is a lightweight data-interchange format that is easy to understand and write. It is also easy for machines to parse and generate, making it an excellent choice for large-scale applications.

The conversation history stored in JSON format can be easily expanded to accommodate more data as the conversation progresses. The bot can handle a growing amount of data without a significant impact on performance, thanks to the efficient nature of JSON.

Dynamic Node-Based Interactions

Looking towards the future, the JSON-based memory state management system lays the groundwork for dynamic node-based interactions. In a node-based system, each interaction or conversation turn can be considered a node. These nodes can be linked together in various ways to create a network of interactions.

This approach allows for more complex and dynamic conversations. For example, the bot could reference previous nodes (i.e., past interactions) to provide more contextually relevant responses. It could also use this network to navigate the conversation, choosing the next node based on the current context and the user's inputs.

Moreover, the bot could leverage this node-based system to manage interactions between different recorded memory states. This would allow the bot to switch between different conversation contexts or "personalities" dynamically, providing a more diverse and engaging user experience.

In conclusion, the daemonMASTER chatbot's memory management system is designed to scale and adapt to future enhancements. The use of JSON for memory state management and the potential for dynamic node-based interactions make it a versatile and future-proof tool for creating interactive chatbots.
