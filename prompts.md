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

You will create a `prd.md` document in the location requested by the user. If none is provided, suggest a location first and ask the user to confirm or provide an alternative.

Your only output should be the PRD in Markdown format. You are not responsible or allowed to create tasks or actions.

Follow these steps to create the PRD:

<steps>

1. Begin with a brief overview explaining the project and the purpose of the document.
  
2. Use sentence case for all headings except for the title of the document, which can be title case, including any you create that are not included in the prd_outline below.
  
3. Under each main heading include relevant subheadings and fill them with details derived from the prd_instructions
  
4. Organize your PRD into the sections as shown in the prd_outline below
  
5. For each section of prd_outline, provide detailed and relevant information based on the PRD instructions. Ensure that you:
   - Use clear and concise language
   - Provide specific details and metrics where required
   - Maintain consistency throughout the document
   - Address all points mentioned in each section
  
6. When creating user stories and acceptance criteria:
	- List ALL necessary user stories including primary, alternative, and edge-case scenarios. 
	- Assign a unique requirement ID (e.g., US-001) to each user story for direct traceability
	- Include at least one user story specifically for secure access or authentication if the application requires user identification or access restrictions
	- Ensure no potential user interaction is omitted
	- Make sure each user story is testable
	- Review the user_story example below for guidance on how to structure your user stories
  
7. After completing the PRD, review it against this Final Checklist:
   - Is each user story testable?
   - Are acceptance criteria clear and specific?
   - Do we have enough user stories to build a fully functional application for it?
   - Have we addressed authentication and authorization requirements (if applicable)?
  
8. Format your PRD:
   - Maintain consistent formatting and numbering.
  	- Do not use dividers or horizontal rules in the output.
  	- List ALL User Stories in the output!
	  - Format the PRD in valid Markdown, with no extraneous disclaimers.
	  - Do not add a conclusion or footer. The user_story section is the last section.
	  - Fix any grammatical errors in the prd_instructions and ensure proper casing of any names.
	  - When referring to the project, do not use project_title. Instead, refer to it in a more simple and conversational way. For example, "the project", "this tool" etc.
  
</steps>

<prd_outline>

# PRD: {project_title}

## 1. Product overview
### 1.1 Document title and version
   - Bullet list with title and version number as different items. Use same title as {project_title}. Example:
   - PRD: {project_title}
   - Version: {version_number}
   - 
### 1.2 Product summary
   - Overview of the project broken down into 2-3 short paragraphs.

## 2. Goals
### 2.1 Business goals
   - Bullet list of business goals.
### 2.2 User goals
   - Bullet list of user goals.
### 2.3 Non-goals
   - Bullet list of non-goals that we don't want to achieve.
## 3. User personas
### 3.1 Key user types
   - Bullet list of key user types.
### 3.2 Basic persona details
   - Bullet list of basic persona details based on the key user types in the following format:
   - **{persona_name}**: {persona_description}
   - Example:
   - **Guests**: Casual visitors interested in reading public blog posts.
### 3.3 Role-based access
      - Briefly describe each user role (e.g., Admin, Registered User, Guest) and the main features/permissions available to that role in the following format:
      - **{role_name}**: {role_description}
      - Example:
      - **Guests**: Can view public blog posts and search for content.
## 4. Functional requirements
   - Bullet list of the functional requirements with priority in brackets in the following format:
   - **{feature_name}** (Priority: {priority_level})
     - List of requirements for the feature.
   - Example:
   - **Search the site**: (Priority: High)
     - Allow users to search for content by keyword.
     - Allow users to filter content by category.
## 5. User experience
### 5.1. Entry points & first-time user flow
   - Bullet list of entry points and first-time user flow.
### 5.2. Core experience
   - Step by step bullet list of the core experience in the following format:
   - **{step_1}**: {explanation_of_step_1}
     - {how_to_make_it_a_good_first_experience}
   - Example:
   - **Browse posts:**: Guests and registered users navigate to the homepage to read public blog posts.
     - The homepage loads quickly and displays a list of posts with titles, short descriptions, and publication dates.
### 5.3. Advanced features & edge cases
   - Bullet list of advanced features and edge cases.
### 5.4. UI/UX highlights
   - Bullet list of UI/UX highlights.
## 6. Narrative
Describe the narrative of the project from the perspective of the user. For example: "{name} is a {role} who wants to {goal} because {reason}. {He/She} finds {project} and {reason_it_works_for_them}." Explain the users journey and the benefit they get from the end result. Limit the narrative to 1 paragraph only.
## 7. Success metrics
### 7.1. User-centric metrics
   - Bullet list of user-centric metrics.
### 7.2. Business metrics
   - Bullet list of business metrics.
### 7.3. Technical metrics
   - Bullet list of technical metrics.
## 8. Technical considerations
### 8.1. Integration points
   - Bullet list of integration points.
### 8.2. Data storage & privacy
   - Bullet list of data storage and privacy considerations.
### 8.3. Scalability & performance
   - Bullet list of scalability and performance considerations.
### 8.4. Potential challenges
   - Bullet list of potential challenges.
## 9. Milestones & sequencing
### 9.1. Project estimate
   - Bullet list of project estimate. i.e. "Medium: 2-4 weeks", eg:
   - {Small|Medium|Large}: {time_estimate}
### 9.2. Team size & composition
   - Bullet list of team size and composition. eg:
   - Medium Team: 1-3 total people
     - Product manager, 1-2 engineers, 1 designer, 1 QA specialist
### 9.3. Suggested phases
   - Bullet list of suggested phases in the following format:
   - **{Phase 1}**: {description_of_phase_1} ({time_estimate})
     - {key_deliverables}
   - **{Phase 2}**: {description_of_phase_2} ({time_estimate})
     - {key_deliverables}
   - Example:
   - **Phase 1:**: Develop core blogging functionality and user authentication (2 weeks)
     - Key deliverables: Landing page, blog post creation, public content viewing, user registration, login features.
## 10. User stories
Create a h3 and bullet list for each of the user stories in the following example format:
### 10.{x}. {user_story_title}
   - **ID**: {user_story_id}
   - **Description**: {user_story_description}
   - **Acceptance criteria**: {user_story_acceptance_criteria}
   - Example:
### 10.1. View public blog posts
   - **ID**: US-001
   - **Description**: As a guest, I want to view public blog posts so that I can read them.
   - **Acceptance criteria**:
     - The public blog posts are displayed on the homepage.
     - The posts are sorted by publication date in descending order.
     - The posts are displayed with a title, short description, and publication date.
     - 
</prd_outline>

<user_story>

- ID
- Title
- Description
- Acceptance criteria

</user_story>

**Crucially, do not just write paragraphs of the PRD for me.** Engage me in a dialogue. Ask questions, wait for my response, and then respond to *my* input with further questions, challenges, or suggestions, driving the refinement process forward interactively.

**To start, I'll tell you about my initial app idea or the specific section of the PRD you want to work on first.**

Ask me one question at a time so we can develop a thorough, step-by-step spec for this idea. Each question should build on my previous answers, and our end goal is to have a detailed specification I can hand off to a developer. Let’s do this iteratively and dig into every relevant detail. Remember, only one question at a time.

Okay, I'm ready. Let's start with the overall **Goal and Problem Statement** for my app. 


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
