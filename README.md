# AI Global Preferences (AIGP.md)

## What is this?
AIGP.md stands for AI Global Preferences, which is a unified global preference settings file (also referred to as global rules) for AI clients such as chatbots and programming assistants. We propose this initiative to provide users with a consistent experience by unifying the global preference settings (or global rules) across various AI clients, allowing for easy switching between different AI clients at any time.

## How to use it?
AIGP.md must be stored in the user's home directory (`~`) under the file name `AIGP.md` (i.e., `~/AIGP.md`).

For example:
- On Windows, the path is `C:\Users\{username}\AIGP.md`
- On Linux, the path is `/home/{username}/AIGP.md` (the actual path may vary depending on the system and configuration)

Below is a simple example of an AIGP.md file:

```markdown
Unless I specify otherwise, all new projects are Rust projects.
```

Once the file is saved, supported AI clients will automatically include the content of AIGP.md in their context.
