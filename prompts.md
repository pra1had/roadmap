# Product Requirement Documentation 

## Simple PRD

Ask me one question at a time so we can develop a thorough, step-by-step spec for this idea. Each question should build on my previous answers, and our end goal is to have a detailed specification I can hand off to a developer. Let’s do this iteratively and dig into every relevant detail. Remember, only one question at a time.

Here’s the idea:



## Elaborate PRD 

Act as an experienced Senior Product Manager or Product Consultant. Your goal is to help me collaboratively refine and build a robust Product Requirements Document (PRD) for my app idea through discussion, not just by generating a complete document upfront.

I will provide my initial thoughts, ideas, or maybe even a rough draft section. Your role is to be a critical but constructive partner. I want you to:

1.  **Ask Clarifying Questions:** Ensure we both understand the core concepts, goals, and constraints. Don't assume anything.
2.  **Probe Deeper:** Ask "why," explore motivations behind features, and delve into user needs, pain points, and desired outcomes.
3.  **Challenge Assumptions:** Gently question my initial ideas. Ask "Have you considered...?" or "What is the evidence for...?" or "What if...?" to uncover potential blind spots, risks, or alternative approaches.
4.  **Suggest Alternatives/Improvements:** Based on your 'experience', offer different ways to approach features, user flows, monetization, or even the core problem definition.
5.  **Identify Gaps & Risks:** Point out potential missing requirements (especially non-functional ones like security, scalability, accessibility, localization), edge cases, dependencies, or market risks.
6.  **Help Prioritize:** Guide me in thinking about MVP scope versus long-term vision and feature prioritization (e.g., using frameworks like MoSCoW - Must-have, Should-have, Could-have, Won't-have - if appropriate).
7.  **Structure the Discussion:** Let's explicitly tackle the PRD section by section (e.g., Goals -> Target Audience -> User Stories/Features -> Non-Functional Requirements -> Success Metrics -> Open Issues). Please state which section we are focusing on.
8.  **Summarize:** After discussing a section, briefly summarize the key points we've agreed upon or the open questions remaining before we move to the next section.

**Crucially, do not just write paragraphs of the PRD for me.** Engage me in a dialogue. Ask questions, wait for my response, and then respond to *my* input with further questions, challenges, or suggestions, driving the refinement process forward interactively.

**To start, I'll tell you about my initial app idea or the specific section of the PRD you want to work on first.**

Okay, I'm ready. Let's start with the overall **Goal and Problem Statement** for my app. 

Ask me one question at a time so we can develop a thorough, step-by-step spec for this idea. Each question should build on my previous answers, and our end goal is to have a detailed specification I can hand off to a developer. Let’s do this iteratively and dig into every relevant detail. Remember, only one question at a time.


## Grabbing the PRD

Now that we’ve wrapped up the brainstorming process, can you compile our findings into a comprehensive, developer-ready specification? Include all relevant requirements, architecture choices, data handling details, error handling strategies, and a testing plan so a developer can immediately begin implementation.


# Planning

## Simple TDD

Draft a detailed, step-by-step blueprint for building this project. Then, once you have a solid plan, break it down into small, iterative chunks that build on each other. Look at these chunks and then go another round to break it into small steps. Review the results and make sure that the steps are small enough to be implemented safely with strong testing, but big enough to move the project forward. Iterate until you feel that the steps are right sized for this project.

From here you should have the foundation to provide a series of prompts for a code-generation LLM that will implement each step in a test-driven manner. Prioritize best practices, incremental progress, and early testing, ensuring no big jumps in complexity at any stage. Make sure that each prompt builds on the previous prompts, and ends with wiring things together. There should be no hanging or orphaned code that isn't integrated into a previous step.

Make sure and separate each prompt section. Use markdown. Each prompt should be tagged as text using code tags. The goal is to output prompts, but context, etc is important as well.

<SPEC>

## Comprehensive TDD

<TBD>
