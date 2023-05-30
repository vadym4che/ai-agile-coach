# AI-Agile-Coach
## Objective:
This is my implementation of a full-stack application that enables users to generate user stories and seek advice from an AI Coach based on Agile principles. The application must include prompts for AI Coach chat. Research and utilize information on Agile principles from various sources to complete the task.

## Technical Requirements:
## Front-end:
* Use React for UI components
* Employ Redux or Zustand for state management
* Implement Material UI for styling and UI components
* Utilize Socket.IO for real-time communication with the back-end
* Ensure a responsive layout for optimal viewing on different devices

## Back-end:
* Use Nest.js for server-side application framework
* Implement Socket.IO for real-time communication with the front-end
* Employ MySQL or PostgreSQL for database management
* Integrate with OpenAI API for AI Coach functionality
* Apply prompt engineering techniques

## Design:
Follow the provided [Figma design](https://www.figma.com/file/T3hfRXuZNCXEmNpru6UpQ1/Agile-Test-task?type=design&node-id=2902-6857&t=VAmxWRccQdZqRPqq-4)
 for the application layout and
components:

<!-- ![Preview image](/DOC/screen_1_start.png) -->
<img src="/DOC/screen_1_start.png" alt="preview1" style="max-width: 25vw; height: auto;">
<!-- ![Preview image](/DOC/screen_2_first.png) -->
<img src="/DOC/screen_2_first.png" alt="preview2" style="max-width: 25vw; height: auto;">
<!-- ![Preview image](/DOC/screen_3_last.png) -->
<img src="/DOC/screen_3_last.png" alt="preview3" style="max-width: 25vw; height: auto;">

## Front-end Implementation:
1. Implement a sidebar with navigation button for "AI Agile Coach"
2. Develop the page: AI Coach chat page for seeking Agile advice
3. Save generated user chat history in the application store
4. Use Socket.IO to make requests to the back-end

## Back-end Implementation:
* Develop Socket.IO events for handling requests to the OpenAI API
based on client context:
--*AI Agile Coach chat
* Think about the prompt for the system message and some additional
assistant messages for the chat to make it work properly.

## Helpful Resources:
Learn Prompting: [https://learnprompting.org/](https://learnprompting.org/)
OpenAI API Documentation:
[https://platform.openai.com/docs/api-reference/](https://platform.openai.com/docs/api-reference/)
