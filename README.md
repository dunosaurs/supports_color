# supports_color

> A deno port of chalk's excellent supports-color library

## Usage

```typescript
import supportsColor, {
  createSupportsColor,
} from "https://deno.land/x/supports_color/mod.ts";

// Automatically check stdout
console.log(supportsColor.stdout);
console.log(supportsColor.stderr);

// Check supports color at arbitrary part of runtime
console.log(createSupportsColor(Deno.stdout));
```
