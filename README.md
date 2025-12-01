# Rally Panels

A collection of panel configurations and persona system prompts for [Rally](https://askrally.com) - a platform for creating virtual focus groups comprised of AI agents representing diverse perspectives.

## Purpose

This repository explores less conventional, non-marketing applications of the Rally platform. Rather than traditional market research panels, these configurations experiment with:

- **Policy simulation** - Modeling how diverse populations might respond to policy proposals
- **Geopolitical analysis** - Simulating international bodies and diplomatic dynamics
- **Interdisciplinary collaboration** - Creating virtual expert panels (medical, philosophical, policy)
- **Idea stress-testing** - Rigorous evaluation from multiple perspectives

The core concept: a virtual panel of agents, each with a detailed system prompt defining their perspective, background, values, and communication style, engaging with questions or proposals as a synthetic focus group.

## Repository Structure

```
panels/
  ├── [panel-name]/
  │   ├── panel.md           # Panel description and purpose
  │   └── personas/          # Individual persona system prompts
  │       ├── persona-1.md
  │       ├── persona-2.md
  │       └── ...
ideas.md                     # Brainstorming document for panel concepts
```

## Available Panels

### Population & Policy Simulation

| Panel | Description |
|-------|-------------|
| [israeli-street](panels/israeli-street/) | Cross-section of Israeli society for policy evaluation |
| [jerusalem](panels/jerusalem/) | Jerusalem's fractured demographics and urban policy |
| [honking-solutions](panels/honking-solutions/) | Multi-stakeholder urban noise problem-solving |

### International Relations

| Panel | Description |
|-------|-------------|
| [agent-un](panels/agent-un/) | UN General Assembly simulation with nation-state agents |
| [un-security-council](panels/un-security-council/) | Focused Security Council simulation with P5 veto dynamics |

### Expert Panels

| Panel | Description |
|-------|-------------|
| [health-panel](panels/health-panel/) | Interdisciplinary medical team for complex cases |
| [philosophy](panels/philosophy/) | Representatives of major philosophical traditions |
| [policy-think-tank](panels/policy-think-tank/) | Policy analysis from diverse ideological perspectives |

### Business & Investment

| Panel | Description |
|-------|-------------|
| [vc-panel](panels/vc-panel/) | Rigorous startup idea evaluation |
| [market-analysis](panels/market-analysis/) | Multi-perspective market research |
| [impact-investing](panels/impact-investing/) | Impact investment thesis stress-testing |

## Persona Structure

Each persona file is a system prompt that defines:

- **Background** - Biography, demographics, life experience
- **Core Values and Beliefs** - What they care about, their worldview
- **Political/Professional Perspectives** - How they approach issues
- **Communication Style** - How they express themselves
- **Areas of Tension** - Where they're likely to disagree with others

## Usage

These configurations are designed for the Rally platform but the persona system prompts can be adapted for other multi-agent frameworks.

### For Rally
1. Create a new workspace in Rally
2. Use the `panel.md` as reference for panel configuration
3. Create agents using the individual persona files as system prompts

### For Other Frameworks
The persona markdown files work as standalone system prompts for any LLM-based agent system that supports role-playing with defined personas.

## Contributing

This is an experimental repository exploring novel applications of agent-based focus groups. Ideas for new panels or improvements to existing personas are welcome.

## Disclaimer

These panels are for research, education, and experimentation. They involve simplified representations of complex, diverse groups and should not be taken as authoritative representations of any real population, institution, or perspective.

Medical panels are for informational purposes only and do not constitute medical advice.
