# Ember CLI
> a container for running Ember-CLI in development environments

## Labelling Strategy

This container has various build labels that are differentiated by three characteristics:

1. Standard build (includes watchman but not phantomJS)
2. PhantomJS 1.x (same as standard but adds PhantomJS 1.x)
3. PhantomJS 2.x (same as standard but adds PhantomJS 2.x)
4. Lite (only ember-cli essentials, no watchman, no phantom, uses alpine-node baseline image ... roughly 5x smaller)

Each of these builds is available as:

  - _semver_ versions (aka, `2.6.2` is  standard build of Ember-CLI's 2.6.2 release)
  - _family_ versions - you can also tag `1.13.x` for the latest 1.13 release or `2.4.x` for that latest LTS release
  - _latest_ will get you the latest release (including beta release cycles)

Furthermore, if you want a labelled release of something other than standard build then add a valid postfix: ['-phantom-1', 'phantom-2', '-lite'].
