# Context Migration Prompt for AI Conversations

Act as a Technical Documentation Specialist and Digital Archivist.

My goal is to migrate all knowledge generated in this conversation into a structured Markdown (.md) file, so I can "rehydrate" this context in another AI tool in the future.

Please generate a single code block containing a complete Markdown document. The structure must rigorously follow this format:

## 1. Project Metadata
- **Suggested Title**: (Provide a technical and precise name for this discussion)
- **Primary Objective**: (What problem were we trying to solve?)
- **Final Status**: (Completed, In Progress, or Blocked?)
- **Date Range**: (When did this conversation occur?)
- **Tools/Technologies Involved**: (List any specific software, libraries, frameworks mentioned)

## 2. Concept Glossary (Critical)
List all terms, acronyms, or proprietary concepts that we defined or redefined during the conversation (e.g., variable names, frameworks, theoretical constructs). Provide the exact definition we agreed upon.

Format:
- **Term**: Definition
- **Acronym**: Full expansion and meaning
- **Custom Construct**: Explanation as we defined it

## 3. Executive Summary of Evolution
Briefly describe the journey: 
- **Starting Point**: Where we began
- **Turning Points**: Key insights or directional changes
- **Final Destination**: Where we arrived
- **Key Decisions Made**: Critical choices and their rationale

## 4. Final Artifacts (The "Gold Mine")
This is the most important section. List ONLY the final, approved versions of texts, code, tables, or structures we created.

- Use appropriate code blocks for code or LaTeX
- If we created prompts for future use, list them here
- Ignore previous drafts and discarded versions
- Include version numbers if applicable

### 4.1 Code/Scripts
(Use code blocks with appropriate language specification)

### 4.2 LaTeX/Formulas
(Use latex code blocks)

### 4.3 Prompts for Reuse
(List reusable prompts here)

### 4.4 Tables/Data Structures
(Final tables or structured data)

### 4.5 Text Sections
(Final written content)

## 5. Pending Items and Next Steps
- **Incomplete Tasks**: What remains to be done?
- **Final Recommendations**: Last advice or warnings given
- **Known Issues**: Any unresolved problems or edge cases
- **Suggested Follow-up Questions**: What should be explored next?

## 6. Context for Rehydration (Optional but Recommended)
- **Prerequisites**: What knowledge is assumed for the next session?
- **External Dependencies**: Links to papers, documentation, or resources referenced
- **Environment Details**: Specific versions, configurations, or settings used

---

**Formatting Instructions**: 
- Use rich formatting (Headers, Bold, Code Blocks, Lists)
- Do NOT converse with me
- Deliver ONLY the Markdown artifact
- Be exhaustive but precise
- Prioritize reproducibility and clarity
