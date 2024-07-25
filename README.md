# teeps-tool-2

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

Usage:

Create a directory with the name of the document you want to use inside of `documents`. Add the `operations.json` file to the directory. You can do this with as many documents as you want.

Example:

```
documents/
  - example/
    - operations.json
  - another-example/
    - operations.json
... etc.
```

Run the tool with `bun run index.ts` and it will generate the updated file(s) in the `documents-updated` directory. The generated `.zip` files will have the same name as the original directory with the `operations.json` with "-updated" added at the end, so like `example-updated.zip`.
