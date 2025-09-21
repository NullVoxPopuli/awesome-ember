# Awesome Ember.js [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Ember.js packages, resources, and shiny things.

[Ember.js](https://emberjs.com) is a JavaScript framework that greatly reduces the time, effort and resources needed to build any web application. It is focused on making you, the developer, as productive as possible by doing all the common, repetitive, yet essential, tasks involved in most web development projects.

*You might also like [awesome-javascript](https://github.com/sorrycc/awesome-javascript).*

---

## Contents

- [Open Source Apps](#open-source-apps)
- [Libraries](#libraries)
- [Addons](#addons)
- [Learning Resources](#learning-resources)
- [Tools](#tools)
- [Testing](#testing)
- [Community](#community)
- [Contribution Guidelines](#contribution-guidelines)

---

## Open Source Apps

*Real-world applications built with Ember.js that you can explore and learn from.*

- [Ghost Admin](https://github.com/TryGhost/Ghost-Admin) - The admin interface for Ghost, the popular publishing platform
- [Travis CI](https://github.com/travis-ci/travis-web) - The Ember.js web client for Travis CI
- [Rancher](https://github.com/rancher/ui) - Enterprise management for Kubernetes
- [HospitalRun](https://github.com/HospitalRun/hospitalrun-frontend) - Open source hospital management system
- [Vault](https://github.com/hashicorp/vault/tree/master/ui/app) - HashiCorp's tool for managing secrets
- [API Docs](https://github.com/ember-learn/ember-api-docs) - Application for displaying Ember.js versioned API docs
- [Guides App](https://github.com/ember-learn/guides-app) - The official Ember.js Guides application
- [Super Rentals](https://github.com/ember-learn/super-rentals) - Tutorial application for learning Ember.js
- [Crates.io](https://github.com/rust-lang/crates.io) - The Rust Package Registry
- [emberclear](https://github.com/NullVoxPopuli/emberclear) - Encrypted chat with no history or logs
- [Percy](https://github.com/percy/percy-web) - Visual testing platform frontend
- [Fire Tracker](https://github.com/SCPR/fire-tracker) - Tool for tracking California wildfires
- [Limber](https://github.com/NullVoxPopuli/limber) - Online Ember.js playground and tutorial platform

## Libraries

### Core Libraries

- [Ember.js](https://github.com/emberjs/ember.js) - The main Ember.js framework
- [Ember Data](https://github.com/emberjs/data) - Data persistence library for Ember.js
- [Ember CLI](https://github.com/ember-cli/ember-cli) - Command line interface for ambitious web applications
- [Glimmer.js](https://github.com/glimmerjs/glimmer.js) - Fast and light-weight UI components

### State Management

- [ember-changeset](https://github.com/poteto/ember-changeset) - Changeset implementation for form validations

### Authentication

- [ember-simple-auth](https://github.com/simplabs/ember-simple-auth) - Lightweight authentication library

### Data Management

- [ember-apollo-client](https://github.com/bgentry/ember-apollo-client) - Apollo Client and GraphQL integration
- [ember-orbit](https://github.com/orbitjs/ember-orbit) - Data layer built with Orbit.js
- [ember-m3](https://github.com/hjdivad/ember-m3) - Alternative model implementation to DS.Model

## Addons

### UI Components

- [ember-bootstrap](http://www.ember-bootstrap.com/) - Bootstrap components for Ember.js
- [ember-power-select](https://github.com/cibernox/ember-power-select) - Extensible select component
- [ember-basic-dropdown](https://github.com/cibernox/ember-basic-dropdown) - Basic dropdown component
- [ember-flatpickr](https://github.com/shipshapecode/ember-flatpickr) - Flatpickr date picker integration

### Animation

- [ember-animated](https://github.com/ember-animation/ember-animated) - Web animations for Ember.js
- [liquid-fire](https://github.com/ember-animation/liquid-fire) - Animations and transitions

### Forms & Validation

- [ember-cp-validations](https://github.com/offirgolan/ember-cp-validations) - Computed property based validations
- [ember-changeset-validations](https://github.com/poteto/ember-changeset-validations/) - Validations for ember-changeset

### Styling

- [ember-css-modules](https://github.com/salsify/ember-css-modules) - CSS Modules for Ember applications
- [ember-cli-sass](https://github.com/aexmachina/ember-cli-sass) - Sass preprocessing support
- [ember-cli-tailwind](https://github.com/embermap/ember-cli-tailwind) - Tailwind CSS integration

### Testing

- [ember-cli-mirage](http://www.ember-cli-mirage.com/) - Client-side server for building, testing and demoing
- [ember-cli-page-object](https://github.com/san650/ember-cli-page-object) - Page object pattern for tests
- [ember-percy](https://github.com/percy/ember-percy) - Visual regression testing
- [ember-exam](https://github.com/trentmwillis/ember-exam) - Test randomization, splitting, and parallelization

### Development Tools

- [ember-cli-deploy](https://github.com/ember-cli-deploy/ember-cli-deploy) - Deployment pipeline
- [ember-cli-template-lint](https://github.com/ember-template-lint/ember-cli-template-lint) - Template linting
- [ember-auto-import](https://github.com/ef4/ember-auto-import) - Zero config imports from npm
- [ember-cli-update](https://github.com/ember-cli/ember-cli-update) - Update Ember CLI projects

### Accessibility

- [ember-a11y](https://github.com/ember-a11y/ember-a11y) - Collection of accessibility tools
- [ember-component-focus](https://github.com/ember-a11y/ember-component-focus) - Focus management utilities
- [ember-page-title](https://github.com/tim-evans/ember-page-title) - Page title management

### Internationalization

- [ember-intl](https://github.com/ember-intl/ember-intl) - Internationalization support with ICU message formatting

### TypeScript

- [ember-cli-typescript](https://github.com/typed-ember/ember-cli-typescript) - Use TypeScript in your Ember.js apps
- [glint](https://github.com/typed-ember/glint) - TypeScript powered tooling for Glimmer templates
- [ember-typings](https://github.com/typed-ember/ember-typings) - TypeScript type definitions for Ember.js

### Build Tools & Modern Compilation

- [embroider](https://github.com/embroider-build/embroider) - Compiling Ember apps into spec-compliant, modern JavaScript
- [ember-vite](https://github.com/mainmatter/ember-vite-codemod) - Vite integration for Ember applications

### Modern UI Primitives

- [ember-primitives](https://github.com/universal-ember/ember-primitives) - Primitives for building UI faster
- [reactiveweb](https://github.com/universal-ember/reactiveweb) - Reactive primitives for the web

### New Generation Tools

- [limber](https://github.com/NullVoxPopuli/limber) - Online Ember.js playground and tutorial system
- [ember-resources](https://github.com/NullVoxPopuli/ember-resources) - Resource utilities for Ember.js
- [kolay](https://github.com/universal-ember/kolay) - Docs system based on markdown files

### Performance

- [ember-concurrency](https://github.com/machty/ember-concurrency) - Improved concurrency primitives
- [ember-infinity](https://github.com/ember-infinity/ember-infinity) - Infinite scroll implementation
- [ember-service-worker](https://github.com/DockYard/ember-service-worker) - Service worker support
- [ember-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) - Server-side rendering

### HTTP & Data Fetching

- [ember-ajax](https://github.com/ember-cli/ember-ajax) - Service for making AJAX requests
- [ember-socket-guru](https://github.com/netguru/ember-socket-guru) - WebSocket integration
- [ember-fetch](https://github.com/ember-cli/ember-fetch) - Fetch API polyfill and wrapper

## Learning Resources

### Tutorials

- [Ember.js Guides](https://guides.emberjs.com/) - Official comprehensive guides
- [Super Rentals Tutorial](https://guides.emberjs.com/release/tutorial/part-1/) - Official step-by-step tutorial
- [Ember.js Tutorial for Beginners](https://www.youtube.com/playlist?list=PLk51HrKSBQ88wDXgPF-QLMfPFlLwcjTlo) - Video series by Shawn Chen
- [EmberMap](https://embermap.com) - Video tutorials and courses

### Books

- [The Shortest Ember.js Book](https://github.com/ember-learn/the-shortest-ember-book) - Concise introduction
- [Ember.js in Action](http://manning.com/skeie/) - Comprehensive book by Manning Publications
- [Rock and Roll with Ember.js](http://rockandrollwithemberjs.com/) - Book with practical examples

### Courses

- [EmberMap](https://embermap.com) - Professional video courses
- [Ember School](https://www.emberschool.com) - Structured learning path
- [Frontend Masters: Ember.js](https://frontendmasters.com/courses/ember-2/) - In-depth course by Mike North

### Documentation

- [Ember.js API Docs](https://emberjs.com/api/) - Complete API reference
- [Ember Data Guides](https://guides.emberjs.com/release/models/) - Data layer documentation
- [Ember CLI User Guide](https://cli.emberjs.com/) - Command line tool documentation

## Tools

### Development

- [Ember Inspector](https://github.com/emberjs/ember-inspector) - Browser extension for debugging
- [Ember CLI](https://ember-cli.com/) - Command line interface
- [ember-cli-update](https://github.com/ember-cli/ember-cli-update) - Update Ember CLI projects

### Code Quality

- [ember-template-lint](https://github.com/ember-template-lint/ember-template-lint) - Template linting
- [eslint-plugin-ember](https://github.com/ember-cli/eslint-plugin-ember) - ESLint rules for Ember.js

### IDE Support

- [VS Code Ember Syntax](https://marketplace.visualstudio.com/items?itemName=dhedgecock.ember-syntax) - Syntax highlighting
- [ember-language-server](https://github.com/emberwatch/ember-language-server) - Language server implementation

## Testing

### Test Runners

- [ember-qunit](https://github.com/emberjs/ember-qunit) - QUnit integration
- [ember-cli-mocha](https://github.com/ember-cli/ember-cli-mocha) - Mocha integration

### Test Utilities

- [ember-test-helpers](https://github.com/emberjs/ember-test-helpers) - Test helper functions
- [ember-cli-page-object](https://github.com/san650/ember-cli-page-object) - Page object implementation
- [ember-a11y-testing](https://github.com/ember-a11y/ember-a11y-testing) - Accessibility testing

### Mocking

- [ember-cli-mirage](http://www.ember-cli-mirage.com/) - API mocking library
- [ember-sinon](https://github.com/csantero/ember-sinon) - Sinon.js integration

## Community

### Official Channels

- [Ember.js Website](https://emberjs.com/) - Official website
- [Ember.js Blog](https://emberjs.com/blog/) - Official blog with announcements
- [Forum](https://discuss.emberjs.com/) - Official discussion forum
- [Discord](https://discordapp.com/invite/zT3asNS) - Real-time chat

### Recent Releases & Features

- [Ember.js 6.7.0](https://github.com/emberjs/ember.js/releases/tag/v6.7.0-ember-source) - Latest stable release with `trustHTML` API and internal improvements
- [Ember.js 6.8.0 Beta](https://github.com/emberjs/ember.js/releases/tag/v6.8.0-beta.3-ember-source) - Upcoming features including Tracked Collections and `renderComponent`
- [RFC #1068: Tracked Collections](https://rfcs.emberjs.com/id/1068-tracked-collections) - Built-in tracked data structures
- [RFC #1099: renderComponent](https://rfcs.emberjs.com/id/1099-renderComponent) - New API for rendering components

### Learning & News

- [The Ember Times](https://the-emberjs-times.ongoodbits.com/) - Weekly newsletter
- [Ember Weekly](http://www.emberweekly.com/) - Community newsletter
- [EmberMap Podcast](https://embermap.com/topics/the-embermap-podcast) - Technical discussions

### Blogs & Articles

- [Ember.js Blog](https://emberjs.com/blog/) - Official blog with announcements and guides
- [EmberMap Blog](https://blog.embermap.com) - Technical articles and tutorials
- [DockYard Blog](https://dockyard.com/blog/categories/ember) - Ember.js articles and best practices
- [Simplabs Blog](https://simplabs.com/blog/) - Advanced Ember.js topics
- [BalintErdi.com](https://balinterdi.com/blog/) - Ember.js insights and tutorials

### Videos & Screencasts

- [EmberConf](https://www.youtube.com/channel/UCukrIWlcLIkDLNmEh2lFpYA) - Annual conference videos
- [EmberMap](https://embermap.com) - Professional screencasts and tutorials
- [Ember Screencasts](https://www.emberscreencasts.com/) - Weekly screencasts
- [EmberFest](https://www.youtube.com/playlist?list=PLN4SpDLOSVkT0e094BZhGkUnf2WBF09xx) - European conference videos

### Social Media

- [Ember.js on Twitter](https://twitter.com/emberjs) - Official Twitter account
- [Reddit r/emberjs](https://www.reddit.com/r/emberjs/) - Community discussion

### Events

- [EmberConf](https://emberconf.com/) - Annual conference
- [EmberFest](https://emberfest.eu/) - European conference
- [Local Meetups](https://emberjs.com/community/meetups/) - Worldwide meetup groups

### Podcasts

- [The EmberMap Podcast](https://embermap.com/topics/the-embermap-podcast) - Technical deep dives
- [Ember Weekend](https://emberweekend.com/episodes) - Weekly Ember.js podcast

## Contribution Guidelines

Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.

### Adding to this list

1. Make sure your suggestion is useful and relevant to the Ember.js community
2. Check if your link is already included
3. Follow the existing format and alphabetical ordering
4. Provide a good description of what the resource offers
5. Make sure the link works and points to the correct resource

### Quality standards

- Only suggest resources you've used and can recommend
- Prefer official or well-maintained resources
- Include a brief description of what makes each resource awesome
- Keep descriptions concise but informative

---

**[⬆ back to top](#contents)**
