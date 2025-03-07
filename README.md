hwp-parser 1.0

A powerful and lightweight TypeScript library for parsing HWP (Hangul Word Processor) files. This library provides a simple and efficient way to extract text content from HWP files, making it easy to integrate with modern web applications, especially Vue 3 projects.

Features:
- Extract text content from HWP files
- Support for basic text formatting
- TypeScript support with full type definitions
- Zero dependencies
- Lightweight and fast
- Vue 3 composables support

Use cases:
- Document processing applications
- Text analysis tools
- Content management systems
- Document conversion tools
- Web-based document viewers

Installation:
```bash
npm install hwp-parser
# or
yarn add hwp-parser
```

Basic usage:
```typescript
import { HwpParser } from 'hwp-parser';

const parser = new HwpParser();
const text = await parser.parse(file);
```

Vue 3 usage:
```typescript
import { useHwpParser } from 'hwp-parser/vue';

const { parse, text } = useHwpParser();
```

License: MIT