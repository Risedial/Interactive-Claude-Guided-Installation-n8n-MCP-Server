# 🚀 Interactive Claude-Guided Installation: n8n MCP Server

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Compatible](https://img.shields.io/badge/Claude-Compatible-purple)](https://claude.ai)
[![n8n](https://img.shields.io/badge/n8n-Automation-orange)](https://n8n.io)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> Transform your n8n MCP server installation from a static documentation nightmare into an **interactive, personalized experience** with Claude as your technical guide.

## 🎯 What Makes This Different?

Instead of following rigid, one-size-fits-all documentation, this repository provides **intelligent copy-paste prompts** that turn Claude into your personal installation assistant. Get real-time, adaptive guidance tailored to your specific system, technical level, and issues.

### Traditional Docs vs. Our Approach

| Traditional Documentation | Claude-Guided Installation |
|--------------------------|---------------------------|
| Static, generic instructions | Dynamic, personalized guidance |
| "Figure it out yourself" troubleshooting | Real-time problem solving |
| One-size-fits-all approach | Adapts to YOUR system |
| Outdated information | Always fetches latest info |
| Linear, rigid process | Flexible, conversational flow |

## ✨ Features

- 🤖 **AI-Powered Assistance**: Claude reads the latest installation info and guides you step-by-step
- 🔧 **Real-Time Troubleshooting**: Get instant help for your specific error messages
- 🎯 **Personalized Experience**: Adjusts to your technical level and operating system
- ✅ **Verification at Every Step**: Claude checks each step worked before proceeding
- 🚀 **Zero Guesswork**: Exact commands, exact file paths, exact configurations
- 💡 **Learning Opportunity**: Understand what's happening, not just copy-paste blindly

## 🖥️ Supported Platforms

- **Windows** (10, 11)
- **macOS** (Monterey, Ventura, Sonoma, Sequoia)

## 📋 Prerequisites

Before starting, ensure you have:
- ✅ Claude Desktop app installed (or access via web/mobile)
- ✅ ~30-45 minutes of time
- ✅ Administrator access to your computer
- ✅ Internet connection

## 🚀 Quick Start

### Option 1: Use the Web Guide
Visit our interactive web guide for the best experience:
> 🌐 **[Interactive Installation Guide](https://your-vercel-deployment.vercel.app)**

### Option 2: Direct Prompts

#### For Windows Users:
1. Open Claude (Desktop, Web, or Mobile)
2. Copy the Windows Setup Prompt from below
3. Paste it to Claude and follow the personalized guidance

<details>
<summary><b>📋 Click to expand Windows Setup Prompt</b></summary>

```xml
<task>
I need to install the n8n MCP (Model Context Protocol) server to work with Claude Desktop on Windows. I want you to be my personal technical guide through this entire process.

Please start by reading the latest installation information from this GitHub repository: https://github.com/leonardsellem/n8n-mcp-server

<requirements>
- Guide me step-by-step for Windows
- Check if each step worked before moving to the next
- Help me troubleshoot any issues
- Explain what each step does in plain English
- Ask me to confirm each step before proceeding
</requirements>

<my_system>
Operating System: Windows
Technical Level: [Tell me: Are you comfortable with command line? Scale 1-10]
Current n8n setup: [Tell me: Do you have n8n running? If yes, where? (localhost:5678, cloud, etc.)]
</my_system>
</task>

First, please:
1. Fetch the latest info from the GitHub repository
2. Tell me what we're going to install and why
3. Check what I need to have ready
4. Start with step 1: Node.js installation

Guide me through each step one at a time, and ask me to tell you the result before moving forward.
```
</details>

#### For Mac Users:
1. Open Claude (Desktop, Web, or Mobile)
2. Copy the Mac Setup Prompt from below
3. Paste it to Claude and follow the personalized guidance

<details>
<summary><b>📋 Click to expand Mac Setup Prompt</b></summary>

```xml
<task>
I need to install the n8n MCP (Model Context Protocol) server to work with Claude Desktop on Mac. I want you to be my personal technical guide through this entire process.

Please start by reading the latest installation information from this GitHub repository: https://github.com/leonardsellem/n8n-mcp-server

<requirements>
- Guide me step-by-step for macOS
- Check if each step worked before moving to the next
- Help me troubleshoot any issues
- Explain what each step does in plain English
- Ask me to confirm each step before proceeding
</requirements>

<my_system>
Operating System: macOS [Tell me: What version? Check Apple Menu > About This Mac]
Technical Level: [Tell me: Are you comfortable with Terminal? Scale 1-10]
Current n8n setup: [Tell me: Do you have n8n running? If yes, where? (localhost:5678, cloud, etc.)]
</my_system>
</task>

First, please:
1. Fetch the latest info from the GitHub repository
2. Tell me what we're going to install and why
3. Check what I need to have ready
4. Start with step 1: Node.js installation

Guide me through each step one at a time, and ask me to tell you the result before moving forward.
```
</details>

## 🆘 Troubleshooting Prompts

Running into issues? We've got specialized prompts for every situation:

### 🔧 General Troubleshooting
Use when something goes wrong during installation

<details>
<summary><b>View Troubleshooting Prompt</b></summary>

```xml
<troubleshooting>
I'm having an issue during the n8n MCP server installation.

<current_situation>
[Describe exactly what happened - what command you ran, what error you got, etc.]
</current_situation>

<system_info>
Operating System: [Your OS and version]
What I was trying to do: [Describe the specific step]
Error message: [Copy the exact error message if any]
</system_info>

Please help me:
1. Diagnose what went wrong
2. Provide the specific solution for my situation  
3. Give me the exact commands to run
4. Verify the fix worked before continuing
5. Continue with the installation from where we left off
</troubleshooting>
```
</details>

### 🎯 Advanced Recovery
For complex issues or multiple failures

<details>
<summary><b>View Advanced Recovery Prompt</b></summary>

```xml
<advanced_help>
I need comprehensive help with my n8n MCP server setup. Multiple things might be wrong.

<full_situation>
Operating System: [Windows/Mac + version]
Installation method used: [npm global install / from source / other]
Current issue: [Describe the main problem]

What's working:
- [List anything that IS working]

What's not working:  
- [List everything that's broken or not responding]

Error messages:
- [Include ALL error messages you're seeing]

What I've tried:
- [List any troubleshooting steps you've already attempted]
</full_situation>

I need you to:
1. Read the latest GitHub repository info to get current best practices
2. Diagnose ALL the issues systematically  
3. Give me a complete recovery plan
4. Walk through each fix step-by-step
5. Test each component individually
6. Get everything working together
</advanced_help>
```
</details>

## ✅ Post-Installation

After successful installation, use these prompts to verify and explore:

### 🧪 Testing & Verification
<details>
<summary><b>View Testing Prompt</b></summary>

```xml
<verification>
I want to thoroughly test my n8n MCP server installation with Claude Desktop.

<setup_details>
Operating System: [Your OS]
Installation complete: Yes
Configuration file: Created and saved
Claude Desktop: Restarted after config changes
</setup_details>

Please help me:
1. Test the basic connection between Claude and n8n
2. Verify I can list my n8n workflows  
3. Test creating a simple workflow through Claude
4. Check that API permissions are working correctly
5. Give me example commands to try
6. Show me what successful responses should look like
</verification>
```
</details>

### 🎓 Learning & Exploration
<details>
<summary><b>View Learning Prompt</b></summary>

```xml
<exploration>
My n8n MCP server is working! I want to learn what I can do with this powerful combination.

<my_interests>
I'm particularly interested in: [automation areas]
My technical level: [Beginner/Intermediate/Advanced]
My n8n experience: [New/Some/Advanced]
</my_interests>

Please help me:
1. Understand key capabilities
2. Show practical examples
3. Teach useful commands
4. Give automation project ideas
5. Explain best practices
6. Provide starter workflows
</exploration>
```
</details>

## 🎯 Use Cases

Once installed, you can use Claude + n8n to:
- 🤖 Build AI-powered automation workflows
- 📧 Automate email processing and responses
- 📊 Create data processing pipelines
- 🔔 Set up intelligent notification systems
- 🔄 Integrate multiple services seamlessly
- 📈 Build monitoring and reporting systems

## 📚 Why This Approach Works

### Built on Prompt Engineering Best Practices

- **🎭 Clear Role Definition**: Claude becomes your technical guide
- **📋 Structured Input**: XML tags organize information clearly
- **🧠 Chain of Thought**: Step-by-step problem solving
- **🔄 Context Preservation**: Each prompt builds on previous interactions
- **🎯 Specific Instructions**: Clear, actionable guidance
- **🛡️ Error Handling**: Built-in troubleshooting workflows

### Real User Benefits

> "Instead of spending hours debugging installation issues, Claude guided me through everything in 30 minutes. It even helped me understand what each step was doing!" - Developer feedback

> "The personalized troubleshooting saved my sanity. Claude diagnosed my Node.js permission issue instantly and provided the exact fix." - User testimonial

## 🛠️ Technical Details

This project leverages:
- **Claude's Capabilities**: Web browsing, code understanding, adaptive responses
- **n8n MCP Server**: [leonardsellem/n8n-mcp-server](https://github.com/leonardsellem/n8n-mcp-server)
- **Model Context Protocol**: Anthropic's MCP for tool integration
- **Prompt Engineering**: Advanced techniques for reliable AI assistance

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Created by**: [@alexbitar](https://instagram.com/alexbitar)
- **n8n MCP Server**: [Leonard Sellem](https://github.com/leonardsellem)
- **Powered by**: [Anthropic's Claude](https://claude.ai)
- **Automation by**: [n8n](https://n8n.io)

---

<div align="center">

**If this helped you, please ⭐ star the repository!**

Made with ❤️ by the community

[Report Bug](https://github.com/yourusername/repo/issues) · [Request Feature](https://github.com/yourusername/repo/issues) · [Join Discussion](https://github.com/yourusername/repo/discussions)

</div>