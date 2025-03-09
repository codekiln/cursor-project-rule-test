# Cursor Project Rules test

This repository contains tests for Cursor's project rules functionality.

For more tests and updates, see my logseq-encode-garden page, [CursorAI Project Rule Tests](https://codekiln.github.io/logseq-encode-garden/#/page/cursorai%2Fproject%20rule%2Ftest).

## Test Cases

### [Finding Rules Without Globs](results/0.46.11/agent/PASS/find-mdc-no-globs.md)
Tests if Cursor Agent can correctly identify and use project rules that don't have glob patterns attached. 
- ✅ PASS: Successfully identifies and responds with rule content

### [Finding Rules in Subfolders](results/0.46.11/agent/FAIL/find-mdc-files-in-subfolders.md)
Tests if Cursor Agent can locate and use project rules that are located in subdirectories.
- ❌ FAIL: Unable to find rules in subdirectories


