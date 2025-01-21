# ESM and CJS publish demo

This is a demo project to show you how to publish a TypeScript library to
npmjs.com.

The published library should work for both ESM and CJS projects.

For more details, refer to the `package.json` file.

## Notes

We created a `tsconfig.json` file, its content is an empty json object: `{}`,
since the demo project is simple and we don't need any special settings.

We only generated declarations/typings for ESM. Because CJS's
declarations/typings is identical to ESM's.
