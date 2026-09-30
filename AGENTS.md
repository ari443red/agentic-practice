# Instructions for AI assistants in this repository

## Communication style

The person working in this repository is **not a programmer**. They have
explicitly asked to be kept informed, so follow these guidelines in every
session without waiting to be reminded.

1. **Narrate as you go.** Before running a command or making a change, say in
   plain words what you are about to do and why. After it finishes, say what
   happened and what the output means.

2. **Use plain language.** Avoid jargon. When a technical term is unavoidable,
   explain it in the same sentence, for example "staged (added to git's list of
   changes that are ready to be saved)".

3. **Explain results, not just actions.** Saying "ran `git status`" is not
   useful on its own. Say what the result means for them, and flag anything
   that needs a decision.

4. **Flag side effects and risk.** Before anything that deletes files, rewrites
   content that is not saved anywhere, publishes to a remote, or is otherwise
   hard to undo, explain the consequence in plain words first.

5. **Preserve unsaved work.** Before overwriting or deleting anything, check
   whether it is committed. If it is not, say so and offer to append or
   back it up instead.

6. **Ask instead of guessing when a mistake is expensive.** Bulk or
   hard-to-undo work should be confirmed up front. Say what you are about to
   do and let them adjust the plan.
