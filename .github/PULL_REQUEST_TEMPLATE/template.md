JIRA Link:

  ## Migration Summary

  **Component(s) being migrated:**
  <!-- e.g., header, footer, cookie-banner -->

  **Migration type:**
  - [ ] Full component migration
  - [ ] Shared utility/helper migration
  - [ ] Types/interfaces migration

  ## What has changed, and why?

  <!-- Describe what was migrated and any adaptations made for
  the banana codebase -->

  ## Changes from original global-components implementation

  <!-- Highlight any differences from the original code -->
  <!-- * Bullet points: API changes, renamed exports, removed
  features, etc. -->

  ## Breaking changes for consumers

  - [ ] No breaking changes
  - [ ] Breaking changes (detail below)

  <!-- If breaking, describe the migration path for consumers
  -->

  ## Checklist

  ### Pre-review
  - [ ] Component behaviour matches the original
  global-components implementation
  - [ ] Existing unit tests have been migrated and pass
  - [ ] Code adheres to the banana [Style Guide](../blob/main/d
  ocs/01-introduction/top-10-style-guide-checklist.md)
  - [ ] Public API is documented and any TSDoc comments are
  preserved
  - [ ] Peer dependencies are accounted for in banana's setup
  - [ ] No leftover references to
  `@skyscanner-internal/global-components` or
  `@web-platform/global-components-*` paths

  ### Testing
  - [ ] Unit/integration tests migrated and passing
  - [ ] Manually tested in major browsers (Chrome, Firefox,
  Safari)
  - [ ] Manually tested
  [RTL](../blob/main/docs/06-reference/right-to-left.md)
  support (with screenshot)
  - [ ] Manually tested [accessibility](https://skyscanner.atla
  ssian.net/l/cp/FhXF71dH)
  - [ ] Percy visual regression tests added/verified
  - [ ] Check Percy tests against [Common flaky
  snapshots](https://skyscanner.atlassian.net/l/cp/pzXA121b)

  ### Post-migration
  - [ ] Corresponding deprecation PR raised in
  global-components (if applicable)
  - [ ] Consumer migration guide documented in `/docs` (if API
  changed)
  - [ ] Events still emitted for external consumers (e.g. BAR
  and Data Platform)

  ## Screenshots

  <!-- Before/after comparison if there are any visual changes
  -->

  ## Danger toggles

  - [ ] Skip PR size check
  - [ ] Skip bundle size increase check
  - [ ] Skip checking config fixture generation

  ## Reviews

  GitHub's CODEOWNERS is used. It has [public GitHub
  docs](https://docs.github.com/en/repositories/managing-your-r
  epositorys-settings-and-features/customizing-your-repository/
  about-code-owners).

  To aid with working out the minimum review set run `pnpm run
  who-to-ask-for-review` for a suggestion of the reviewer
  groups needed for your change.