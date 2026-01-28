# Claude Code Video Review – PSB System (Plan → Setup → Build)

## 1. Comprehensive Overview

This video introduces a structured system for starting and building coding projects using Claude Code (an AI-powered coding tool from Anthropic). It's aimed at beginners to experienced users who want to avoid common pitfalls like disorganized development, inefficient workflows, and wasted time. The tutorial emphasizes that proper planning and setup make AI-assisted coding 10x more effective, turning chaotic freestyle prompting into a reliable process.

The content is broken into three main phases (the "PSB system"): **Plan**, **Setup**, and **Build**. These phases teach how to align AI with your goals, configure tools for efficiency, and execute development productively.

- **Main Skills Taught**:
  - Project planning and specification writing.
  - Configuring AI coding environments (e.g., GitHub integration, plugins, custom commands).
  - AI-assisted development workflows, including parallel processing and issue management.
  - Debugging, iteration, and optimization techniques.

- **Key Concepts**:
  - AI as a collaborative tool: Treat Claude like a smart assistant that needs clear instructions, context, and constraints to perform well.
  - Iterative development: Break projects into milestones (e.g., MVP first), use feedback loops to refine.
  - Automation and extensibility: Leverage plugins, servers, and hooks to automate repetitive tasks.
  - Regression prevention: Continuously update AI's "memory" to avoid repeating errors.

- **Phases**:
  - **Plan Phase**: Brainstorm goals, milestones, and create a spec doc combining product (what/why) and engineering (how) requirements. Use AI for clarification.
  - **Setup Phase**: Prepare the environment with a GitHub repo, env files, claude.md (project memory), automated docs, plugins, MCP servers, and custom commands/subagents.
  - **Build Phase**: Develop the MVP, then use workflows (general, issue-based, multi-agent) to add features. Apply tips for productivity like model selection and discarding bad work.

Overall, it's like building a house: Plan the blueprint, set up tools/materials, then construct efficiently. The video assumes basic familiarity with coding but shows how AI democratizes advanced development.

## 2. Skill Tree Extraction

The video outlines skills for mastering AI-assisted coding with Claude Code. Organized hierarchically from foundational to advanced.

| Level              | Skill Category              | Specific Skills |
|--------------------|-----------------------------|-------------------------------------------------------------|
| **Foundational**   | Project Goal Setting        | - Asking key questions: "What am I trying to do?" and "What are the milestones?"<br>- Brainstorming with pen/paper or AI voice mode.<br>- Using AI to generate clarifying questions. |
|                    | Basic Spec Creation         | - Outlining product requirements (user problems, features, UX specifics).<br>- Defining engineering requirements (tech stack choices, architecture basics). |
|                    | Environment Setup Basics    | - Creating a GitHub repo and basic .env file.<br>- Writing a simple claude.md file with project goals and constraints. |
| **Intermediate**   | Advanced Planning           | - Creating detailed project spec docs with milestones (e.g., MVP focus).<br>- Researching tech stacks via AI reports.<br>- Provisioning infrastructure (e.g., databases, APIs). |
|                    | Claude Code Configuration   | - Setting up automated documentation (architecture.md, changelog.md, status.md).<br>- Installing plugins (e.g., front-end, feature dev) and MCP servers (e.g., for databases, deployment).<br>- Creating basic slash commands and subagents (e.g., for testing or updates). |
|                    | Single-Feature Development  | - Using the general workflow: Research → Plan → Implement → Test.<br>- Building MVPs with plan mode and parallel subagents.<br>- Managing branches and commits. |
| **Advanced**       | Multi-Feature Workflows     | - Issue-based development: Turning specs into GitHub issues; parallel bug fixing.<br>- Multi-agent development: Using git work trees for simultaneous feature branches; merging changes. |
|                    | Automation & Optimization   | - Pre-configuring permissions and hooks (e.g., auto-tests, notifications).<br>- Tuning claude.md iteratively with regression prevention (# instructions).<br>- Model selection (Opus for complex tasks) and discarding/restarting work. |
|                    | Continuous Improvement      | - Reflecting with retro agents/subagents.<br>- Scaling to team/work scenarios (e.g., company policies in specs).<br>- Customizing for specific domains (e.g., web apps with Vercel integration). |

Mastery involves iterating on real projects, starting small and scaling to complex ones.

## 3. Actionable Learning Plan

4–6 week plan assuming basic coding experience. 5–10 hours/week, hands-on focus.

**Week 1: Foundations & Planning**  
- Watch video (overview + notes). Install Claude Code.  
- Brainstorm simple project → spec doc.  
- Use voice mode for ideation.

**Week 2: Setup Phase Mastery**  
- GitHub repo + .env + claude.md  
- Automated docs + 2–3 plugins + 1 MCP + custom commands  
- Test configuration

**Week 3: Build Phase Basics**  
- Build MVP using general workflow  
- Apply tips: model selection, # regression rules  
- Deploy MVP

**Week 4: Advanced Workflows**  
- Issue-based development  
- Multi-agent with git work trees  
- Retro subagent to improve claude.md

**Week 5–6: Real-World Application & Review**  
- Build new project from scratch  
- Time yourself, get community feedback  
- Self-assess competence

## 4. Core Concepts & Mental Models

- **PSB System**: Plan blueprint → Setup tools → Build efficiently  
- **AI as Guided Assistant**: Needs clear context + constraints  
- **Milestone Thinking**: MVP first, iterate fast  
- **Context Window Management**: Keep claude.md concise, link external docs  
- **Regression Prevention**: Use # to lock in lessons  
- **Parallelism in Development**: Subagents / multi-instances like a team  
- **Code is Cheap**: Discard & restart freely

## 5. Practical Application Focus

- New repo per project  
- Commit spec.md first  
- Write 3–5 rules in claude.md  
- Install front-end plugin + Vercel MCP  
- Prompt: "Build MVP from spec.md using plan mode + parallel subagents"  
- New feature → GitHub issue → new branch  
- Multi-agent: git worktree + 2 terminals → merge  
- After feature: /commit + update changelog  
- Bug → # prevention rule immediately  
- Deploy → Vercel preview branches

## 6. Knowledge Checks & Evaluation

**Quiz Questions**  
1. Why does planning save time? Example?  
2. Slash command vs subagent — when to use each?  
3. How do git work trees enable multi-agent?  
4. Opus vs Haiku — when & why?  
5. claude.md vs automated docs — purpose & linking?

**Hands-On Exercises**  
1. Plan weather app → spec + Claude questions  
2. Configure repo + plugin + MCP → build tiny feature  
3. Compare general vs issue-based workflow speed  
4. Run multi-agent merge → note conflict prevention  
5. Retro subagent → apply improvements to next task

## 7. Workflow & Process Mapping

**Overall PSB**  
1. Plan → spec  
2. Setup → repo + claude.md + plugins/MCPs  
3. Build → MVP → features (loop)

**General Workflow**  
1. Research  
2. Plan mode  
3. Implement + subagents  
4. Test  
5. Update docs + #

**Issue-Based**  
1. Generate issues from spec  
2. Assign → branch  
3. General workflow per issue  
4. PR + review  
5. Parallel execution

**Multi-Agent**  
1. git worktree add branches  
2. Multiple Claude terminals  
3. Assign features  
4. Merge + conflict resolution  
5. Test previews

## 8. Common Mistakes & Pitfalls

- Freestyle prompting → always plan first  
- Bloated claude.md → keep concise + link docs  
- Skipping plan mode → always enable it  
- No GitHub repo → limits parallelism & history  
- Cheap models for hard tasks → use Opus/Sonnet  
- Not preventing regressions → use # immediately  
- Building everything at once → MVP milestones only  
- Fear of discarding → restart freely  
- Manual updates → automate with hooks/commands