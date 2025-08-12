# multi-tenant-backend Monorepo

This is a monorepo managed with **Yarn Workspaces**.

## Structure

- `/packages` – All your packages (apps, libs, services) go here.

## Getting Started

1. **Install dependencies**

   ```bash
   yarn install
   ```

2. **Add a new package**

   ```bash
   mkdir -p packages/my-new-package
   cd packages/my-new-package
   yarn init -y
   ```

3. **Develop locally**

   - Each package manages its own code and dependencies.
   - Use `yarn workspaces` commands to manage all packages together.

## Resources

- [Yarn Workspaces Documentation](https://classic.yarnpkg.com/en/docs/workspaces/)