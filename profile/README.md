<div align="center">

# Quantum PHP

### Build with clarity.

A modular PHP framework for building websites, APIs, and applications with a clear structure, practical tooling, and an application skeleton ready to extend.

[Website](https://quantumphp.io) · [Documentation](https://quantumphp.io/v3.0/getting-started/introduction) · [Quickstart](https://quantumphp.io/v3.0/getting-started/quickstart) · [Report an issue](https://github.com/quantum-php/framework/issues)

</div>

<br>

<div align="center">
  <img src="../assets/space-oddity.jpg" alt="Quantum PHP — space exploration" width="100%" />
</div>

<br>

## Start building

Create a new Quantum application and run the local development server:

```bash
composer create-project quantum/project my-app
cd my-app
php qt serve
```

**Requirements:** PHP 8.0+ and Composer.

## What Quantum gives you

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚛️ Modular by design</h3>
      <p>Organize applications into focused modules, with their own routes, controllers, views, and business logic.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🧭 Clear request flow</h3>
      <p>Routes, middleware, caching, controllers, and responses work together in a predictable lifecycle.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🗄️ Practical data layer</h3>
      <p>Work with models, collections, pagination, soft deletes, transactions, and flexible database adapters.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🛠️ Built for daily development</h3>
      <p>Use the <code>qt</code> CLI, scaffolding, routing, views, cache, authentication, and developer tools from one cohesive framework.</p>
    </td>
  </tr>
</table>

## How a request moves through Quantum

```text
Request → Bootstrap → Route → Middleware → Cache or Controller → Response
```

Start with the [Getting Started guide](https://quantumphp.io/v3.0/getting-started/introduction), then explore [routing](https://quantumphp.io/v3.0/core-concepts/routing), [packages](https://quantumphp.io/v3.0/packages/app/overview), and the full [request lifecycle](https://quantumphp.io/v3.0/advanced-features/request-lifecycle).

## Explore the project

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>⚛️ <a href="https://github.com/quantum-php/framework">Framework</a></h3>
      <p>The core Quantum PHP package: application architecture, routing, modules, database integration, CLI tooling, and more.</p>
    </td>
    <td width="33%" valign="top">
      <h3>🚀 <a href="https://github.com/quantum-php/project">Project</a></h3>
      <p>The starter application and project skeleton for beginning a new Quantum project.</p>
    </td>
    <td width="33%" valign="top">
      <h3>📚 <a href="https://github.com/quantum-php/docs">Documentation</a></h3>
      <p>The documentation source for the Quantum PHP website and framework guides.</p>
    </td>
  </tr>
</table>

## Learn more

- [Quantum PHP website](https://quantumphp.io)
- [Documentation](https://quantumphp.io)
- [GitBook documentation](https://quantumphp.gitbook.io/docs)
- [Read the Docs mirror](https://quantum-php-framework.readthedocs.io/)
- [Framework issues](https://github.com/quantum-php/framework/issues)
- [Project issues](https://github.com/quantum-php/project/issues)
- [GitHub Discussions](https://github.com/quantum-php/framework/discussions)
- [Sponsor Quantum](https://github.com/sponsors/quantum-php)

## Contributing

Issues, discussions, and pull requests are welcome. If you find a bug, have an idea, or want to improve the framework or docs, start with the relevant repository above.
