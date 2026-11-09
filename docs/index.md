# reactive.lua

A small, dependency-free reactivity system for Lua 5.4 — refs,
computed values, reactive tables, watchers, the works. If you've ever
used Vue 3 and thought "I wish I had this in Lua," well, here you go.

## Guide

Start at the top and work your way down, or jump straight to whatever
you need — every chapter stands on its own once you know what a `ref`
is.

1. [Introduction](guide/00-introduction.md) — what this is, why it exists
2. [Installation](guide/01-installation.md)
3. [`ref()` and `effect()`](guide/02-ref-and-effect.md) — the two building
   blocks everything else is made of
4. [`computed()`](guide/03-computed.md) — values derived from other values
5. [`reactive()`](guide/04-reactive-objects.md) — whole tables, made reactive
6. [`watch()` and `watchEffect()`](guide/05-watch.md) — reacting to change
   with more control

### Going deeper

7. [The `ref` family](guide/06-ref-variants.md) — `shallowRef`, `toRef`,
   `toRefs`, `proxyRefs`
8. [Reactive variants](guide/07-reactive-variants.md) — `shallowReactive`,
   `readonly`, `shallowReadonly`
9. [`effectScope()`](guide/08-effect-scope.md) — cleaning up in bulk
10. [Deep watching](guide/09-deep-watching.md) — the `deep` option, explained
    properly
11. [Lua stdlib interop](guide/10-lua-interop.md) — `table.sort()` and
    friends, plus one thing to never do
12. [Iteration details](guide/11-iteration-details.md) — `pairs()`,
    `ipairs()`, `#`, and what actually triggers what
13. [Tracking control](guide/12-tracking-control.md) — `pauseTracking()` and
    friends, for the rare case you need them
14. [Where we differ from Vue](guide/90-differences-from-vue.md) — for
    anyone coming from Vue with expectations

## Reference

Prefer looking things up over reading prose? The reference has every public
function with its exact signature and behavior, no fluff.
[See the reference index](reference/) for how it's organized.
