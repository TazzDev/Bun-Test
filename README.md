# bun-test

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.0.0. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.

# Learnings

Bun cannot be used to run an entire project standalone. It needs something like Vite or Parcel to bundle the project.
However, it can be used to run a single file that does not depend on any DOM interaction.
