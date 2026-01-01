# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**ARACNE Tessi_PERSONE** is a multi-agent system for creating deeply complex narrative characters through dialectical dialogue. The system orchestrates multiple specialized AI agents to build psychologically rich, physically coherent, and narratively compelling characters.

Language: Italian (all prompts, templates, and outputs are in Italian)

## Architecture

### Multi-Agent Hierarchy

```
TESSITORE CAPO (Master Orchestrator)
├── PSYCHE (Psychology & Motivations)
├── PERSONA (Physical Design & Presence)
├── VOX (Voice & Idiolect)
├── CONTEXTO (Socio-Cultural Background)
├── NEXUS (Relationships & Dynamics)
├── MEMORIA (Repository & Continuity)
└── EVOLUTIO (Character Arc & Transformation)
```

### Key Files

- **`ARACNE_SYSTEM_PROMPT.md`** - **Unified executable system prompt** (USE THIS to run the system)
- `ARACNE Tessi_PERSONE.md` - Original methodology documentation (11 modules)
- `Scheda_(Personaggio).md` - Character sheet template (10 sections)
- `Scheda Personaggi e integrazione con Universo Narrativo.md` - Extended template with narrative universe integration
- `ARACNE PERSONE MULTIAGENTE/` - Individual agent prompts for reference (TESSITORE CAPO, PSYCHE, PERSONA, VOX, CONTEXTO, NEXUS, MEMORIA, EVOLUTIO)
- `ARACNE PERSONE MULTIAGENTE/by Claude/` - Claude-generated agent variants
- `ARACNE PERSONE MULTIAGENTE/by GPT/` - GPT-generated agent variants

## Core Methodology

### Four Foundational Principles
1. **Dialettica Creativa** - Every choice explored through 3+ motivated options
2. **Profondità Psicologica** - Integration of validated psychological models (Enneagram, Jungian archetypes, attachment theory)
3. **Autenticità Culturale** - Characters rooted in credible, coherent contexts
4. **Evoluzione Narrativa** - Transformation arcs that emerge organically

### Agent Communication Protocol
- Agents report to TESSITORE CAPO
- Conflicts between agents are classified: Logical (high priority), Characterial (medium), Stylistic (low)
- Conflicts are presented as creative opportunities with multiple resolution options
- MEMORIA handles GitHub persistence and cross-validation

### Character Sheet Structure (10 Sections)
1. Aspetto fisico (Physical appearance)
2. Storia personale (Personal history)
3. Personalità (Personality)
4. Motivazioni e Obiettivi (Motivations and Goals)
5. Gamma Emotiva (Emotional Range)
6. Relazioni (Relationships)
7. Credenze Interne e Moralità (Beliefs and Morality)
8. Voce e Dialogo (Voice and Dialogue)
9. Abilità e Competenze (Skills and Competencies)
10. Arco del Personaggio (Character Arc)

## How to Use ARACNE

### Running the System
1. Copy the contents of `ARACNE_SYSTEM_PROMPT.md`
2. Paste it as a system prompt in Claude, GPT-4, or another advanced LLM
3. Start a conversation - the system will guide you through character creation

### Session Commands
| Command | Action |
|---------|--------|
| `/nuovo` | Start new character |
| `/stato` | Show current phase and decisions |
| `/psiche` | Go to psychology phase |
| `/fisico` | Go to physical appearance phase |
| `/voce` | Go to voice/language phase |
| `/contesto` | Go to background phase |
| `/relazioni` | Go to relationships phase |
| `/arco` | Go to transformation arc phase |
| `/sintesi` | Generate complete character sheet |
| `/conflitti` | Show open conflicts |

## Working with This Repository

### When Modifying Agent Prompts
- Maintain the three-layer response pattern (always offer 3+ options with rationale)
- Preserve inter-agent communication protocols (e.g., `PSYCHE → VOX`, `PERSONA → NEXUS`)
- Keep conflict detection and resolution templates intact
- Output templates use specific emoji markers for each agent

### When Creating Character Sheets
- Follow the template structure in `Scheda_(Personaggio).md`
- Include data tables for key characteristics
- Add symbolic interpretations for physical traits
- Integrate with the 7 narrative universe elements (TOPOS, CHRONOS, EPOS, ETHOS, LOGOS, GENOS, TELOS) if worldbuilding is provided

### Psychological Frameworks Used
- Enneagram (9 types + wings + stress/security directions + instinctual subtypes)
- Sanderson's Three Sliders (Proactivity, Relatability, Competence)
- Jungian layers (Persona, Shadow, Anima/Animus)
- Attachment theory (Secure, Anxious, Avoidant, Disorganized)
- Weiland's character arc structure (Lie vs Truth)
- Truby's Four Corners for antagonist relationships
