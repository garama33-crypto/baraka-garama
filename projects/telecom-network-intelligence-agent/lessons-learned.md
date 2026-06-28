# Lessons Learned

## Building an AI Agent with n8n

### Challenge 1

Simple Memory expected a Chat Trigger session ID.

### Resolution

Used a static session identifier during testing or removed memory until the workflow was stable.

---

### Challenge 2

Gmail configured as a Tool generated execution errors.

### Resolution

Connected Gmail after the AI Agent as a standard workflow node.

Correct design:

```text
AI Agent → Gmail
