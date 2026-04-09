# Awesome Ember [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Ember packages, resources, and shiny things.

[Ember](https://emberjs.com) is a JavaScript framework that greatly reduces the time, effort and resources needed to build any web application. It is focused on making you, the developer, as productive as possible by doing all the common, repetitive, yet essential, tasks involved in most web development projects.

*You might also like [awesome-javascript](https://github.com/sorrycc/awesome-javascript).*

---

## Contents

- [Apps](#apps)
- [Open Source Apps](#open-source-apps)
- [Design Systems](#design-systems)
- [Libraries](#libraries)
- [Learning Resources](#learning-resources)
- [Tools](#tools)
- [Testing](#testing)
- [Community](#community)
- [Contribution Guidelines](#contribution-guidelines)

---

## Apps

- [pikimov](https://pikimov.com/) - free Motion design and video editor
- [percy](https://percy.io/) - visual regression testing and review platform
- [PomoTimer](https://pomotimer.io/) - a Pomodoro timer
- [typelog](https://typelog.dev/) - a community of "build in public" and collaboration
- [Feldico](https://feldico.com/) - Feldico is Argentina’s #1 platform connecting farmers and rural contractors.
- [Lineup Ninja](https://lineup.ninja/) - Advanced speaker management software for ambitious conference producers, marketers and operations teams.

## Open Source Apps

*Real-world applications built with Ember that you can explore and learn from.*

- [Discourse](https://www.discourse.org/) - [Source](https://github.com/discourse/discourse) - A platform for community discussion
- [Limber](https://limber.glimdown.com/) - [Source](https://github.com/NullVoxPopuli/limber) - Multi-framework REPL and playground
- [Crates.io](https://crates.io/) - [Source](https://github.com/rust-lang/crates.io) - The Rust Package Registry
- [Vault](https://developer.hashicorp.com/vault) - [Source](https://github.com/hashicorp/vault/tree/master/ui/app) - HashiCorp's tool for managing secrets
- [UniDancing.art](https://unidancing.art) - [Source](https://github.com/gossi/unidancing) - Training resources for unicycling

## Design Systems

- [Elastic EUI](https://github.com/prysmex/ember-eui/tree/master) - by @prysmex
- [Hokulea](https://github.com/hokulea/hokulea) - by @gossi
- [Frontile](https://github.com/josemarluedke/frontile) - by @josemarluedke
- [NRG UI](https://github.com/knoxville-utilities-board/nrg-ui) - by Knoxville Utilities Board
- [Carbon](https://github.com/IBM/carbon-components-ember) - by IBM
- [Helios](https://github.com/hashicorp/design-system) - by Hashicorp
- [shadcn-ember](https://shadcn-ember.com/) - [Source](https://github.com/IgnaceMaes/shadcn-ember) - shadcn/ui port for Ember — accessible and customizable components you can copy and paste into your apps - by @IgnaceMaes

## Libraries

### Core Libraries

- [Ember](https://github.com/emberjs/ember.js) - The main Ember framework
- [WarpDrive](https://github.com/warp-drive-data/warp-drive) - Universal data management for use with any framework

### Authentication

- [ember-simple-auth](https://github.com/simplabs/ember-simple-auth) - Lightweight (multi-)authentication library
- [ember-better-auth](https://github.com/ember-integrations/ember-better-auth) - Ember adapter for [better-auth](https://better-auth.com/)

### Data Management

- [WarpDrive](https://github.com/warp-drive-data/warp-drive) - Universal data management for use with any framework
- [glimmer-apollo](https://github.com/josemarluedke/glimmer-apollo) - Integration with Apollo Client

### UI Components

- [ember-bootstrap](https://www.ember-bootstrap.com/) - Bootstrap components for Ember - Since 2015 - [npm](https://www.npmjs.com/package/ember-bootstrap) - ![NPM Downloads](https://img.shields.io/npm/dm/ember-bootstrap)
- [ember-power-select](https://github.com/cibernox/ember-power-select) - Extensible select component - Since 2015 - [npm](https://www.npmjs.com/package/ember-power-select) - ![NPM Downloads](https://img.shields.io/npm/dm/ember-power-select)
- [ember-basic-dropdown](https://github.com/cibernox/ember-basic-dropdown) - Basic dropdown component - Since 2015 - [npm](https://www.npmjs.com/package/ember-basic-dropdown) - ![NPM Downloads](https://img.shields.io/npm/dm/ember-basic-dropdown)
- [ember-power-calendar](https://github.com/cibernox/ember-power-calendar) - Customizable calendar component - Since 2016 - [npm](https://www.npmjs.com/package/ember-power-calendar) - ![NPM Downloads](https://img.shields.io/npm/dm/ember-power-calendar)
- [ember-flatpickr](https://github.com/shipshapecode/ember-flatpickr) - Flatpickr date picker integration - Since 2016 - [npm](https://www.npmjs.com/package/ember-flatpickr) - ![NPM Downloads](https://img.shields.io/npm/dm/ember-flatpickr)
- [ember-sortable](https://github.com/adopted-ember-addons/ember-sortable) - Sortable UI primitives - Since 2015 - [npm](https://www.npmjs.com/package/ember-sortable) - ![NPM Downloads](https://img.shields.io/npm/dm/ember-sortable)
- [ember-file-upload](https://github.com/adopted-ember-addons/ember-file-upload) - File upload component - Since 2014 - [npm](https://www.npmjs.com/package/ember-file-upload) - ![NPM Downloads](https://img.shields.io/npm/dm/ember-file-upload)
- [ember-maplibre-gl](https://github.com/johanrd/ember-maplibre-gl) - [Docs](https://johanrd.github.io/ember-maplibre-gl) - Declarative MapLibre GL JS map components for Ember
- [ember-safe-button](https://ember-safe-button.netlify.app/) - [Source](https://gitlab.com/michal-bryxi-oss/ember-safe-button) - Button component with confirmation for potentially dangerous actions

### Forms & Validation

- [ember-headless-form](https://github.com/CrowdStrike/ember-headless-form) - Headless forms with a11y and validation support built in
- [pahu](https://github.com/hokulea/pahu) - framework agnostic headless form library

### Styling

- [ember-scoped-css](https://github.com/auditboard/ember-scoped-css/) - enables automatic sccoping of embedded `<style scoped>` in the `<template>...</template>` of components as well as optional usage of co-located CSS stylesheets with automated scoping of the styles. 
- [glimmer-scoped-css](https://github.com/cardstack/glimmer-scoped-css) - enables automatic scoping of embedded `<style scoped>` in the `<template>...</template>` of components.



### Internationalization

- [ember-intl](https://github.com/ember-intl/ember-intl) - Internationalization support with ICU message formatting

### TypeScript

- [glint](https://github.com/typed-ember/glint) - TypeScript-plugin for enabling type-aware Ember 

### Alternative Rendering

- [ember-native](https://github.com/ember-native/ember-native) - Use the Ember framework with NativeScript
- [ember-tui](https://github.com/patricklx/ember-tui) - Terminal UI library — build and test CLI tools using Ember.js with Flexbox layouts powered by Yoga

### Build Tools & Modern Compilation

- [embroider](https://github.com/embroider-build/embroider) - Compiling Ember apps into spec-compliant, modern JavaScript
- [ember-vite-codemod](https://github.com/mainmatter/ember-vite-codemod) - Migrates non-vite Ember Apps to Vite 
- [vite-ember-ssr](https://github.com/evoactivity/vite-ember-ssr) - Vite plugin and SSR/SSG runtime for compatless Ember apps using HappyDOM — no FastBoot required
- [vite-plugin-ember](https://github.com/aklkv/vite-plugin-ember) - Vite plugin for rendering live, interactive Ember components inside VitePress documentation pages

### Utilities 

- [@responsive-image/ember](https://emberobserver.com/addons/@responsive-image/ember) - automatically create responsive optimized images for faster page loads
- [ember-primitives](https://github.com/universal-ember/ember-primitives) - Primitives for building UI faster
- [reactiveweb](https://github.com/universal-ember/reactiveweb) - Reactive primitives for the web
- [ember-page-title](https://github.com/tim-evans/ember-page-title) - Page title management
- [ember-resources](https://github.com/NullVoxPopuli/ember-resources) - Resource utilities for Ember
- [ember-concurrency](https://github.com/machty/ember-concurrency) - Improved concurrency primitives
- [ember-keyboard](https://emberobserver.com/addons/ember-keyboard) - easy key-combos
- [ember-aria-voyager](https://github.com/hokulea/aria-voyager) - aria keyboard support for composite controls

## Learning Resources

### Tutorials

- [Ember Guides](https://guides.emberjs.com/) - Official comprehensive guides
- [Super Rentals Tutorial](https://guides.emberjs.com/release/tutorial/part-1/) - Official step-by-step tutorial
- [Interactive cheatsheet-based tutorial](https://tutorial.glimdown.com/)
- [Component Architecture](https://ember-handbook.netlify.app/component-architecture/)

### Books

- [The Shortest Ember Book](https://github.com/ember-learn/the-shortest-ember-book) - Concise introduction
- [Rock and Roll with Ember](http://rockandrollwithemberjs.com/) - Book with practical examples


### Documentation

- [Ember Guides](https://guides.emberjs.com/) - Official comprehensive guides
- [Ember API Docs](https://emberjs.com/api/) - Complete API reference
- [Ember Data Guides](https://guides.emberjs.com/release/models/) - Data layer documentation
- [Ember CLI User Guide](https://cli.emberjs.com/) - Command line tool documentation
- [ember-fireplace](https://github.com/NullVoxPopuli/ember-fireplace) - Community research project aggregating Ember resources in one place

## Tools

### Development

- [Ember Inspector](https://github.com/emberjs/ember-inspector) - Browser extension for debugging
- [Ember CLI](https://ember-cli.com/) - Command line interface
- [ember-cli-update](https://github.com/ember-cli/ember-cli-update) - Update Ember CLI projects
- [gember](https://github.com/bertdeblock/gember) - Modern generators for Ember apps and addons (components, routes, services, and more)
- [ember.nvp](https://github.com/NullVoxPopuli/ember.nvp) - Ember project generator with idempotent, layered features — a reenvisioning of blueprints
- [refined-ember](https://github.com/bertdeblock/refined-ember) - CSS refinements for Ember documentation websites (API docs, Guides, CLI docs)

### Code Quality

- [ember-template-lint](https://github.com/ember-template-lint/ember-template-lint) - Template linting
- [eslint-plugin-ember](https://github.com/ember-cli/eslint-plugin-ember) - ESLint rules for Ember

### Codemods

- [ember-estree](https://github.com/NullVoxPopuli/ember-estree) - ESTree-compatible AST parser for `.gjs` and `.gts` files — enables linters and codemods to work with both JS/TS and template portions
- [zmod-ember](https://github.com/NullVoxPopuli/zmod-ember) - Adapter for the [zmod](https://github.com/NaamuKim/zmod) codemod toolkit to support Ember's `.gjs` and `.gts` files via ember-estree

### AI

- [agent-skills](https://github.com/ember-tooling/agent-skills) - Collection of skills for AI coding agents following the [Agent Skills](https://agentskills.io/) format — includes Ember best practices across 7 categories
- [ember-mcp](https://github.com/ember-tooling/ember-mcp) - MCP server providing access to Ember documentation, API references, guides, and best practices

### IDE Support

- [Official docs for Editors](https://guides.emberjs.com/release/code-editors/)

#### VSCode

- [vscode-ember](https://github.com/ember-tooling/vscode-ember) - Ember extension for VSCode
- [ember-language-server](https://github.com/ember-tooling/ember-language-server) - Language server providing code intelligence for Ember templates and components
- [ember-source-lens](https://github.com/ember-tooling/ember-source-lens) - Source lens for navigating Ember source files
- [snippets](https://github.com/ember-tooling/snippets) - Code snippets for Ember (also supports Neovim)

#### Neovim

- [ember.nvim](https://github.com/nullvoxpopuli/ember.nvim) - Neovim plugin for Ember development
- [snippets](https://github.com/ember-tooling/snippets) - Code snippets for Ember (also supports VSCode)

#### Vim

- [vim-ember-hbs](https://github.com/joukevandermaas/vim-ember-hbs/pull/16) - Handlebars/Glimmer template syntax support for Vim

#### Emacs

- [glnt-ts-mode](https://github.com/overcast-software/glnt-ts-mode) - Glimmer TypeScript tree-sitter mode for Emacs

#### Syntax

- [tree-sitter-glimmer](https://github.com/ember-tooling/tree-sitter-glimmer) - Tree-sitter grammar for Glimmer templates
- [tree-sitter-glimmer-javascript](https://github.com/ember-tooling/tree-sitter-glimmer-javascript) - Tree-sitter grammar for Glimmer with JavaScript
- [tree-sitter-glimmer-typescript](https://github.com/ember-tooling/tree-sitter-glimmer-typescript) - Tree-sitter grammar for Glimmer with TypeScript

## Testing

### Runners

- [ember-qunit](https://github.com/emberjs/ember-qunit) - QUnit integration
- [ember-vitest](https://github.com/NullVoxPopuli/ember-vitest) - Vitest integration

### Utilities

- [ember-test-helpers](https://github.com/emberjs/ember-test-helpers) - Test helper functions
- [ember-a11y-testing](https://github.com/ember-a11y/ember-a11y-testing) - Accessibility testing
- [ember-percy](https://github.com/percy/ember-percy) - Visual regression testing
- [ember-exam](https://github.com/trentmwillis/ember-exam) - Test randomization, splitting, and parallelization
- [@universal-ember/test-support](https://github.com/universal-ember/test-support) - Collection of additional, community maintained, test-utilities
- [testem-code-coverage](https://github.com/NullVoxPopuli/testem-code-coverage) - Browser test coverage using Chrome's native `startPreciseCoverage` — no Babel plugins needed


## Community

### Official Channels

- [Ember Website](https://emberjs.com/) - Official website
- [Ember Blog](https://emberjs.com/blog/) - Official blog with announcements
- [Forum](https://discuss.emberjs.com/) - Official discussion forum
- [Discord](https://discord.gg/emberjs) - Real-time chat

### Learning & News

- [The Ember Times](https://the-emberjs-times.ongoodbits.com/) - Weekly newsletter
- [Ember Weekly](http://www.emberweekly.com/) - Community newsletter
- [EmberMap Podcast](https://embermap.com/topics/the-embermap-podcast) - Technical discussions

### Blogs & Articles

- [Official Ember Blog](https://emberjs.com/blog/) 
- [Dev.to tag: Ember](https://dev.to/t/ember/latest)
- [Mainmatter Blog](https://mainmatter.com/blog/) 
- [BalintErdi.com](https://balinterdi.com/blog/)
- [Melanie.codes](https://melanie.codes/)
- [NullVoxPopuli.com](https://nullvoxpopuli.com)
- [runspired.com](https://runspired.com/)
- [yehudakatz.com](https://yehudakatz.com/)

### Social Media

- [Ember on BlueSky](https://bsky.app/profile/emberjs.com) - Official BlueSky account
- [Ember on Mastodon](https://hachyderm.io/@emberjs) - Official Mastodon account

- [Reddit r/emberjs](https://www.reddit.com/r/emberjs/) - Community discussion

## Contributors

<!-- readme: contributors -start -->
<table>
	<tbody>
		<tr>
            <td align="center">
                <a href="https://github.com/NullVoxPopuli">
                    <img src="https://avatars.githubusercontent.com/u/199018?v=4" width="100;" alt="NullVoxPopuli"/>
                    <br />
                    <sub><b>NullVoxPopuli</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/mkszepp">
                    <img src="https://avatars.githubusercontent.com/u/19845290?v=4" width="100;" alt="mkszepp"/>
                    <br />
                    <sub><b>Markus Sanin</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/gossi">
                    <img src="https://avatars.githubusercontent.com/u/283700?v=4" width="100;" alt="gossi"/>
                    <br />
                    <sub><b>Thomas Gossmann</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/elgordino">
                    <img src="https://avatars.githubusercontent.com/u/19666042?v=4" width="100;" alt="elgordino"/>
                    <br />
                    <sub><b>Gordon Johnston</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/marcemira">
                    <img src="https://avatars.githubusercontent.com/u/1788212?v=4" width="100;" alt="marcemira"/>
                    <br />
                    <sub><b>Marcelo Mira</b></sub>
                </a>
            </td>
		</tr>
	<tbody>
</table>
<!-- readme: contributors -end -->

## Contribution Guidelines

Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.

### Adding to this list

1. Make sure your suggestion is useful and relevant to the Ember community
2. Check if your link is already included
4. Provide a good description of what the resource offers
5. Make sure the link works and points to the correct resource

### Quality standards

- Only suggest resources you've used and can recommend
- Include a brief description of what makes each resource awesome
- Keep descriptions concise but informative

---

**[⬆ back to top](#contents)**
