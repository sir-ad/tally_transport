# Instructions for Code Generation Workflow

1. **User prompt → agent.md persona**  
   The agent reads task + context and infers the goal (e.g., "transport module").
2. **Agent generates full `.tdl` code** using internal templates.
3. **Code validator** checks syntax consistency (no undefined references).
4. **Docs generator** creates a mini README describing:
   - Purpose
   - Usage
   - Installation steps
   - Example screenshots (optional)
