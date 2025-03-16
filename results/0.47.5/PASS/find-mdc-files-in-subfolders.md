# Can Cursor Agent Mode pick up mdc files in subfolders? - YES in `0.47`
- see updates in [Changelog - Mar 11, 2025 | Cursor - The AI Code Editor | Cursor - The AI Code Editor](https://www.cursor.com/changelog/reliability-keyboard-shortcuts-early-access-opt-in) 

## Test
- Close all tabs (even this one)
- Tell agent mode, "what are my favorite apples?"

### Expected Behavior
- Cursor Agent surfaces the correct rule
- Cursor Agent answers according to the contents of the rule

### Observed Behavior
- Cursor surfaces `Rule: subfolder/favorite-apples`
- "I see that this rule is actually about Apple computers and the Macintosh naming rather than edible apples. ..."