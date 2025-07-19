# CLAUDE.md - Repository Learning Context

## 🎯 Repository Overview

This is **gmogmz's personal fork** of the official **LangChain Academy "Agents From Scratch"** course repository. This fork serves as a personalized learning environment for mastering ambient agent development, specifically email assistant agents using LangGraph.

### Repository Details:
- **Location**: `/Users/gmogmz/Code/LangGraph/langgraph-agent-development`
- **Original Course**: [LangChain Academy - Ambient Agents](https://academy.langchain.com/courses/take/ambient-agents/texts/66147177-module-1-resources)
- **Fork Source**: `https://github.com/langchain-ai/agents-from-scratch`
- **Your Fork**: `git@github.com:gmogmzGithub/langgraph-agent-development.git`

### Fork Purpose:
1. **Personal Learning Journey**: Track progress through the course modules
2. **Learning Continuity**: Resume learning after breaks without losing context
3. **Portfolio Development**: Showcase agent development skills
4. **Safe Experimentation**: Modify and extend course materials without affecting originals

## 📁 Current Repository Structure

```
langgraph-agent-development/
├── 📚 OFFICIAL COURSE CONTENT (preserve as-is)
│   ├── README.md                           # Original course documentation
│   ├── notebooks/                          # Course notebooks (5 modules)
│   │   ├── langgraph_101.ipynb            # LangGraph fundamentals
│   │   ├── agent.ipynb                    # Basic agent construction
│   │   ├── evaluation.ipynb               # Agent evaluation methods
│   │   ├── hitl.ipynb                     # Human-in-the-loop patterns
│   │   ├── memory.ipynb                   # Memory systems
│   │   ├── img/                           # Course images and diagrams
│   │   └── test_tools.py                  # Testing utilities
│   ├── src/email_assistant/               # Core implementation code
│   │   ├── email_assistant.py             # Basic email agent
│   │   ├── email_assistant_hitl.py        # + Human-in-the-loop
│   │   ├── email_assistant_hitl_memory.py # + Memory capabilities
│   │   ├── email_assistant_hitl_memory_gmail.py # + Gmail integration
│   │   ├── langgraph_101.py              # LangGraph basics
│   │   ├── configuration.py              # Config management
│   │   ├── prompts.py                    # Agent prompts
│   │   ├── schemas.py                    # Data schemas
│   │   ├── utils.py                      # Utilities
│   │   ├── cron.py                       # Scheduling
│   │   ├── tools/                        # Tools directory
│   │   └── eval/                         # Evaluation code
│   ├── tests/                            # Automated testing suite
│   │   ├── conftest.py                   # Test configuration
│   │   ├── test_response.py              # Response testing
│   │   ├── test_notebooks.py             # Notebook testing
│   │   └── run_all_tests.py              # Test runner
│   ├── pyproject.toml                    # Package configuration
│   ├── uv.lock                          # Dependency lockfile
│   ├── langgraph.json                   # LangGraph config
│   ├── .env.example                     # Environment template
│   └── .gitignore                       # Git ignore rules
│
├── 🎓 PERSONAL LEARNING FILES (safe to add/modify)
│   ├── CLAUDE.md                        # This context file
│   ├── AGENTS.md                        # Agent implementations guide
│   └── 📁 PLANNED ADDITIONS:
│       ├── learning-progress.md         # Personal progress tracker
│       ├── learning-resources/          # Personal learning aids
│       │   ├── notes.md                # Module-by-module notes
│       │   ├── troubleshooting.md      # Personal solutions
│       │   └── setup-check.py          # Environment verification
│       ├── my-experiments/             # Personal modifications
│       │   ├── custom-agents/          # Your agent variations
│       │   ├── additional-tools/       # Tools you develop
│       │   └── practice-notebooks/     # Your practice work
│       └── portfolio-showcase/         # Recruiter-ready demos
```

## 🚀 Current Setup Status

### ✅ Environment Setup Complete
- Repository forked and cloned
- Python environment configured with `uv`
- Dependencies installed via `uv sync --extra dev`
- PyCharm IDE opened and configured

### ✅ Package Installation
- Installed as `interrupt_workshop` with import name `email_assistant`
- Allows imports: `from email_assistant import ...`

### 🔄 Git Configuration
- **Origin**: `git@github.com:gmogmzGithub/langgraph-agent-development.git`
- **Missing**: Upstream remote to original course repository
- **Status**: Clean working tree on main branch

## 📚 Course Module Overview

### **Preface: LangGraph 101** 
- **Notebook**: `notebooks/langgraph_101.ipynb`
- **Code**: `src/email_assistant/langgraph_101.py`
- **Focus**: Chat models, tool calling, nodes/edges, memory, Studio

### **Module 1: Building an Agent**
- **Notebook**: `notebooks/agent.ipynb` 
- **Code**: `src/email_assistant/email_assistant.py`
- **Focus**: Email triage, response generation, tool integration

### **Module 2: Evaluation**
- **Notebook**: `notebooks/evaluation.ipynb`
- **Focus**: LLM-as-judge, testing frameworks, evaluation metrics

### **Module 3: Human-in-the-Loop**
- **Notebook**: `notebooks/hitl.ipynb`
- **Code**: `src/email_assistant/email_assistant_hitl.py` 
- **Focus**: Agent Inbox, interrupts, human approval workflows

### **Module 4: Memory**
- **Notebook**: `notebooks/memory.ipynb`
- **Code**: `src/email_assistant/email_assistant_hitl_memory.py`
- **Focus**: LangGraph Store, persistent learning, user preferences

### **Module 5: Production Deployment**
- **Code**: `src/email_assistant/email_assistant_hitl_memory_gmail.py`
- **Focus**: Gmail API integration, LangGraph Platform deployment


## 🧠 Claude AI Assistant Instructions

When helping gmogmz with this repository:

### **Context Awareness**
- This is a PERSONAL FORK for learning purposes
- Preserve original course content integrity
- Focus on learning enhancement and personal development

### **File Management Guidelines**
- **This forked version is aimed to modify**: `notebooks/`, `src/`, `tests/`, `README.md`, original course files

### **Learning Support Approach**
- Help track progress in personal learning files
- Suggest experiments in `my-experiments/` directory
- Guide documentation in `learning-resources/`
- Encourage regular syncing with upstream

### **Getting Back Up to Speed Protocol**
When gmogmz returns after a break:
1. **Check** `learning-progress.md` for current status
2. **Verify** environment: `python -c "from email_assistant import *"`
3. **Review** recent personal notes and experiments
4. **Sync** with upstream: `git fetch upstream`
5. **Suggest** next steps based on progress

### **Troubleshooting Hierarchy**
1. Check if issue is with original course content
2. Verify environment setup and API keys
3. Look at personal troubleshooting guide
4. Reference official course documentation
5. Create personal solutions in learning-resources/

## 🎯 Learning Workflow Recommendations

### **Phase 1: Foundation (Current Focus)**
- Complete environment setup verification
- Work through `notebooks/langgraph_101.ipynb`
- Create personal progress tracking system

### **Phase 2: Core Learning**
- Progress through modules 1-4 sequentially
- Document insights in personal notes
- Create experiments in `my-experiments/`

### **Phase 3: Advanced Integration**
- Gmail API integration (Module 5)
- Deploy to LangGraph Platform
- Build portfolio showcases

### **Phase 4: Personal Innovation**
- Create custom agent variations
- Develop additional tools
- Build portfolio demonstrations

## 🔄 Maintenance & Syncing

### **Regular Syncing with Upstream**
```bash
# Weekly or before starting new modules
git fetch upstream
git checkout main
git merge upstream/main
git push origin main
```

### **Progress Documentation**
- Update personal learning files after each session
- Commit personal additions regularly
- Use descriptive commit messages for learning journey

---

*This context file helps Claude AI assist with your personal learning journey through the LangChain Agents From Scratch course. Update it as your learning progresses and new patterns emerge.*