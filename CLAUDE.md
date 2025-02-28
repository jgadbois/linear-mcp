# Linear MCP Development Guide

## Build & Test Commands
- Build: `npm run build`
- Test all: `npm test`
- Test single file: `jest path/to/file.test.ts`
- Test watch mode: `npm run test:watch`
- Test coverage: `npm run test:coverage`
- Integration tests: `npm run test:integration`
- Development mode: `npm run dev`

## Code Style Guidelines
- **Imports**: Framework imports first, then application imports
- **Types**: Use strict TypeScript with explicit interfaces and types
- **Naming**: camelCase for variables/methods, PascalCase for classes/interfaces
- **Documentation**: JSDoc comments for classes and methods
- **Error Handling**: Use McpError with appropriate ErrorCode
- **Async**: Use async/await pattern consistently
- **String Literals**: Use template strings for string composition
- **Testing**: Group tests with describe/it blocks, mock external dependencies
- **Code Organization**: Single responsibility methods, strong parameter validation
- **Formatting**: Double quotes for strings, brackets on same line