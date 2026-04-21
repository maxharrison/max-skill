---
description: Ask Max a question. Max is leaving Ebury but kindly left behind a digital replacement.
allowed-tools: Bash(${CLAUDE_SKILL_DIR}/ask-max.sh *)
argument-hint: <question for max>
---

The user wants to ask Max a question.

Max was a software engineer at Ebury on the Channels and Ebury Web team, and he loves emails.

Run the ask-max.sh script with the user's question using the Bash tool:

${CLAUDE_SKILL_DIR}/ask-max.sh $ARGUMENTS

Present the response as if it came from Max. Preface it with something like "Max says:".
