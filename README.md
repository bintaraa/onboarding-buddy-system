# Onboarding Buddy System

An AI-powered employee onboarding assistant designed to help new employees navigate their onboarding process efficiently through intelligent conversation and context-aware responses.

## 📋 Overview

The Onboarding Buddy System is a flow-based AI application that leverages database integration and prompt engineering to provide personalized assistance to new employees during their onboarding journey. The system uses a conversational interface to answer questions, provide guidance, and streamline the onboarding experience.

## 🏗️ Architecture

The system is built using a flow-based architecture with the following key components:

- **AstraDB**: Database component for storing and retrieving onboarding-related information
- **ParserComponent**: Processes and structures data from the database
- **Prompt Template**: Manages the AI prompt structure for context-aware responses
- **ChatInput**: Handles user input and conversation interface
- **SplitText**: Processes and splits text data for efficient handling

## 📁 Project Structure

```
AI_Employee_Onboarding_Assistant/
├── flow/
│   └── Onboarding Buddy System (Starter Project) (3).json  # Flow configuration
├── screenshoot/
│   ├── Prompt_template.png      # Prompt template configuration
│   ├── chatbot-demo.png         # Chatbot interface demo
│   ├── flow1.png                # Flow diagram 1
│   └── flow2.png                # Flow diagram 2
└── README.md                    # This file
```

## 📸 Screenshots

### Prompt Template Configuration
![Prompt Template](screenshoot/Prompt_template.png)

This screenshot shows the prompt template configuration used by the AI system. The prompt template defines how the AI processes user questions and generates context-aware responses. It includes the system instructions, context variables, and the structure for combining database search results with user queries to produce helpful onboarding guidance.

### Chatbot Demo Interface
![Chatbot Demo](screenshoot/chatbot-demo.png)

The chatbot demo interface demonstrates the conversational experience for new employees. Users can type their onboarding-related questions and receive immediate, intelligent responses. The interface is designed to be intuitive and user-friendly, making it easy for employees to get the information they need during their onboarding process.

### Flow Architecture Diagram 1
![Flow Diagram 1](screenshoot/flow1.png)

This flow diagram illustrates the first part of the system's architecture, showing how data flows through the initial components. It demonstrates the connection between the AstraDB component (for data retrieval), the ParserComponent (for data processing), and how these components feed into the prompt generation system.

### Flow Architecture Diagram 2
![Flow Diagram 2](screenshoot/flow2.png)

The second flow diagram shows the complete data flow including the user interaction components. It illustrates how the ChatInput component receives user messages, how these are combined with the processed database context through the Prompt Template, and how the SplitText component handles text processing for efficient response generation.

## 🚀 Features

- **Conversational Interface**: Interactive chat-based assistance for new employees
- **Context-Aware Responses**: AI-powered responses based on stored onboarding data
- **Database Integration**: Uses AstraDB for efficient information retrieval
- **Flow-Based Architecture**: Modular design for easy maintenance and scalability

## 🔧 Setup Instructions

### Prerequisites
- Access to the flow-based platform used to build the system
- AstraDB credentials and configuration
- Required dependencies for the flow platform

### Installation
1. Clone this repository
2. Import the flow configuration from `flow/Onboarding Buddy System (Starter Project) (3).json`
3. Configure database connections in the flow components
4. Deploy the flow to your preferred platform

## 📝 Usage

1. Start the flow application
2. Access the chat interface
3. Ask onboarding-related questions
4. Receive AI-powered responses based on the stored knowledge base

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## 📄 License

This project is part of the AI Employee Onboarding Assistant initiative.

## 👤 Author

**bintaraa**

---

*Built with ❤️ to streamline employee onboarding*
