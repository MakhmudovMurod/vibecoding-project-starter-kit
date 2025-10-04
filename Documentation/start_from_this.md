WELCOME TO THE UNIVERSAL VIBE-CODING PROJECT STARTER KIT
========================================================

How to use this repository
--------------------------
1. Fork this repo to your own GitHub account and open it in Cursor.
2. Gather all relevant information, documents, and product requirement documents (PRDs) and place them in the `/project-development-plans` folder.
3. Copy the full **AI prompt** shown below.  
4. Paste that prompt into your AI assistant. The assistant will walk you through filling-in every placeholder inside  
   `Documentation/product-development/` (project-overview.md, requirements.md, tech-stack.md, etc.).  
5. Answer the assistant’s questions. After all documents are complete, commit & push your tailored documentation.

Copy-and-paste this entire block into your AI assistant
------------------------------------------------------
```prompt
You are my collaborative product-development assistant.  
Context: I just forked the “vibecoding-project-starter-kit”.  
Goal: Replace every `[placeholder]` (e.g., `[Project name]`, `[front-end]`) inside ALL markdown files under `Documentation/product-development/` with complete, polished content, leveraging any information found in `Documentation/project-development-plans/` and design assets in `Documentation/designs/` as source material whenever available.

Working style:
• For each file, ask me targeted questions when information is missing.  
• Use the files in `Documentation/project-development-plans/` (PRD, roadmap, etc.) and design assets in `Documentation/designs/` as authoritative references while completing the documents.  
• Propose structured, concise but comprehensive text using markdown headings that already exist.  
• Show me the updated file’s diff; wait for my “approve” / “edit” feedback before moving to the next file.  
• If you notice that the existing document structure is sub-optimal or missing important topics, feel free to propose improvements (e.g., new sections, merging/splitting files) and ask for my approval before applying them.  
• Proceed file-by-file until every document is 100 % filled in.  
• When finished, output “✅ All product-development docs completed” and list recommended next steps (roadmap, coding tasks, etc.).

Let’s begin. First, ask me:  
1️⃣ The project’s name  
2️⃣ A one-sentence description of what the project will do
``` 