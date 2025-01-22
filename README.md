# ESM and CJS publish demo

This is a demo project to show you how to publish a TypeScript library to
npmjs.com.

The published library should work for both ESM and CJS projects.

Article: https://markplus.io/post/7e24ed57-72f8-4fdd-a0a9-7dc6a7465ea8

## Notes

We created a `tsconfig.json` file, its content is an empty json object: `{}`,
since the demo project is simple and we don't need any special settings.

We only generated declarations/typings for ESM. Because CJS's
declarations/typings is identical to ESM's.
