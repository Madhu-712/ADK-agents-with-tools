# Building AI Agents with ADK: Empowering with Tools

This project is a hands-on guide to building AI agents with the Gemini ADK (Agent Development Kit) and empowering them with various tools. It follows the steps outlined in the [Google Codelab](https://codelabs.developers.google.com/devsite/codelabs/build-agents-with-adk-empowering-with-tools#5).

## Getting Started

### Prerequisites

*   Python 3.10 or higher
*   An environment with the necessary dependencies installed. You can use `uv` to install them from `uv.lock`.

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/Madhu-712/ADK-agents-with-tools.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd ADK-agents-with-tools
    ```
3.  Install the dependencies:
    ```bash
    uv pip install -r requirements.txt
    ```

## Project Structure

The project is organized into several directories, each representing a different stage of agent development:

*   `personal_assistant/`: The initial base agent.
*   `personal_assistant1/`: The agent enhanced with a custom currency exchange tool and a Google Search tool.
*   `personal_assistant2/`: The final agent, which includes a specialized search agent and a Wikipedia tool.

## Execution Steps

This project demonstrates the step-by-step process of building a powerful AI agent:

1.  **Set up a base agent:**
    The `personal_assistant/` directory contains the code for a basic personal assistant agent. This is the starting point of our project.

2.  **Build a custom tool for currency exchange:**
    In `personal_assistant1/custom_functions.py`, you'll find a custom tool for currency exchange. This demonstrates how to create your own tools to extend the agent's capabilities.

3.  **Integrate a built-in Google Search tool directly:**
    The `personal_assistant1/agent.py` file shows how to integrate a built-in tool like Google Search directly into the agent.

4.  **Create a specialized search agent:**
    In `personal_assistant2/custom_agents.py`, a specialized search agent is created. This agent is designed to handle search-related queries more effectively.

5.  **Leverage LangChain's Wikipedia tool for cultural and historical information:**
    The `personal_assistant2/third_party_tools.py` file demonstrates how to use tools from third-party libraries like LangChain. In this case, the Wikipedia tool is used to provide the agent with access to a vast repository of knowledge.

## Conclusion

This project provides a comprehensive overview of how to build and enhance AI agents using the Gemini ADK. By following the steps outlined in this README and the accompanying code, you can learn how to create your own powerful and versatile AI agents.
