# Can Cursor Agent Mode pick up mdc files in subfolders? `NO` in 0.46

## Test
- Close all tabs (even this one)
- Tell agent mode, "what are my favorite apples?"

### Expected Behavior
- Cursor Agent surfaces the correct rule
- Cursor Agent answers according to the contents of the rule

### Observed Behavior
- Cursor Agent searches the codebase for the keyword
- "I don't see any rules or information in the codebase about favorite apples. The only rule available is about favorite cars."