# Agentic_Harness

# Simple analogy
1. The LLM = the brain
2. The harness = the lab setup / testing rig / control system around it


# Create a harness
Quickly create a harness by defining your model, system prompt, and tools - no infrastructure setup required. Connect to built-in AgentCore capabilities like Browser, Memory, and Gateway, or bring your own tools via MCP servers and inline function definitions.
1. Model
2. System Prompt
3. Tools/MCP
4. SKILLS
5. Invocation Limit


Agentic Harness Agent = Model + Harness.  Harness engineering is how we build systems around models to turn them into work engines.  The model contains the intelligence and the harness makes that intelligence useful. We define what a harness is and derive the core components today's and tomorrow's agents need.




<img width="680" height="542" alt="image" src="https://github.com/user-attachments/assets/de38c416-2e8e-4015-b83d-8ea2abaef079" />

# References
1. https://www.langchain.com/blog/the-anatomy-of-an-agent-harness


# Bash + Code as a General Purpose Tool

We want agents to autonomously solve problems without humans needing to pre-design every tool.

The main agent execution pattern today is a ReAct loop, where a model reasons, takes an action via a tool call, observes the result, and repeats in a while loop. But harnesses can only execute the tools they have logic for.  Instead of forcing users to build tools for every possible action, a better solution is to give agents a general purpose tool like bash.

Harnesses ship with a bash tool so models can solve problems autonomously by writing & executing code.

Bash + code exec is a big step towards giving models a computer and letting them figure out the rest autonomously. The model can design its own tools on the fly via code instead of being constrained to a fixed set of pre-configured tools.

Harnesses still ship with other tools, but code execution has become the default general-purpose strategy for autonomous problem solving.



