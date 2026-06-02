# PaperIQ â€” Development Notes

This file tracks incremental development progress and changes.

<!-- [2026-05-02 10:48] fix: improve error handling in QnA chain -->

<!-- [2026-05-02 16:43] refactor: clean up vectorstore initialization -->

<!-- [2026-05-03 11:35] docs: update inline comments in data loader -->

<!-- [2026-05-03 15:05] feat: add retry logic for ArXiv API calls -->

<!-- [2026-05-04 09:09] style: reformat prompt builder for readability -->

<!-- [2026-05-04 17:26] fix: handle empty query edge case gracefully -->

<!-- [2026-05-05 11:06] chore: remove unused imports from llm.py -->

<!-- [2026-05-05 18:55] refactor: simplify LangChain chain construction -->

<!-- [2026-05-06 12:44] fix: correct distance threshold validation logic -->

<!-- [2026-05-06 18:15] feat: persist session state across reruns -->

<!-- [2026-05-07 09:28] docs: improve README setup instructions -->

<!-- [2026-05-07 17:33] fix: resolve semantic cache clearing bug -->

<!-- [2026-05-08 09:20] refactor: extract magic numbers to constants.py -->

<!-- [2026-05-08 13:24] feat: enhance sidebar UI with better labels -->

<!-- [2026-05-09 09:55] fix: handle PDF parsing errors gracefully -->

<!-- [2026-05-09 14:05] chore: update .gitignore with env file patterns -->

<!-- [2026-05-10 10:06] style: improve loading spinner message text -->

<!-- [2026-05-10 17:34] feat: add paper count input validation -->

<!-- [2026-05-11 10:52] fix: correct Redis connection retry logic -->

<!-- [2026-05-11 14:47] refactor: modularize embedding generation step -->

<!-- [2026-05-12 11:34] docs: add docstrings to all QnA module functions -->

<!-- [2026-05-12 17:57] fix: prevent duplicate context document entries -->

<!-- [2026-05-13 10:37] feat: log query metadata for debugging purposes -->

<!-- [2026-05-13 16:44] chore: pin dependency versions in requirements.txt -->

<!-- [2026-05-14 12:48] fix: handle ArXiv API timeout errors properly -->

<!-- [2026-05-14 14:34] refactor: improve vectorstore cleanup on reset -->

<!-- [2026-05-15 11:21] style: consistent formatting across app.py -->

<!-- [2026-05-15 17:53] feat: display paper titles in context expander -->

<!-- [2026-05-16 12:51] fix: fix session state initialization order bug -->

<!-- [2026-05-16 15:34] docs: document all required environment variables -->

<!-- [2026-05-17 11:25] refactor: move prompt templates to prompt.py -->

<!-- [2026-05-17 16:33] fix: improve semantic cache hit rate for queries -->

<!-- [2026-05-18 09:38] feat: add collapsible context expander section -->

<!-- [2026-05-18 15:54] chore: add dev-notes file for tracking progress -->

<!-- [2026-05-19 12:41] fix: sanitize user query input before processing -->

<!-- [2026-05-19 15:05] refactor: simplify chat message state handling -->

<!-- [2026-05-20 10:28] feat: show progress indicator while indexing papers -->

<!-- [2026-05-20 15:26] fix: resolve Docker entrypoint permission issue -->

<!-- [2026-05-21 11:34] docs: update architecture diagram description -->

<!-- [2026-05-21 14:49] chore: clean up leftover temp and cache files -->

<!-- [2026-05-22 12:21] fix: correct token limit calculation in LLM -->

<!-- [2026-05-22 16:08] feat: improve chat message markdown formatting -->

<!-- [2026-05-23 10:37] refactor: optimize document chunking strategy -->

<!-- [2026-05-23 17:23] fix: handle network interruption during indexing -->

<!-- [2026-05-24 11:29] style: update action button labels in sidebar -->

<!-- [2026-05-24 16:06] feat: add debug logging toggle via env variable -->

<!-- [2026-05-25 12:36] fix: resolve embedding dimension mismatch error -->

<!-- [2026-05-25 18:33] chore: bump GitHub Actions workflow versions -->

<!-- [2026-05-26 12:28] refactor: consolidate Redis client setup logic -->

<!-- [2026-05-26 16:03] docs: clarify RAG pipeline in README -->

<!-- [2026-05-27 12:47] fix: prevent null pointer when chain result empty -->

<!-- [2026-05-27 16:34] feat: track and display query response times -->

<!-- [2026-05-28 10:30] refactor: improve organization of constants.py -->

<!-- [2026-05-28 14:19] fix: correct assistant avatar image path -->

<!-- [2026-05-29 11:11] style: improve code readability in db.py module -->

<!-- [2026-05-29 16:39] feat: enforce maximum paper count limit of 50 -->

<!-- [2026-05-30 09:46] docs: add troubleshooting section to README -->

<!-- [2026-05-30 14:31] fix: handle expired Redis index on app restart -->

<!-- [2026-05-31 10:52] refactor: decouple LLM config from chain logic -->

<!-- [2026-05-31 13:16] chore: validate .env keys on application startup -->

<!-- [2026-06-01 09:25] fix: improve sidebar widget state persistence -->

<!-- [2026-06-01 17:13] feat: show source document metadata in response -->

<!-- [2026-06-02 12:51] refactor: clean up qna module file structure -->

<!-- [2026-06-02 15:25] fix: resolve Streamlit widget re-render issue -->
