# @tummycrypt/tinyland-physics (retired)

This repository is retired and archived (2026-10-10, estate uplift rulings
RU2, RU6, RU7, RU8).

No live application or package consumes it, so it was not carried forward
to the new stack (SvelteKit 3 / TypeScript 7). Its successor is
[xoxd-ai/tinyvectors](https://github.com/xoxd-ai/tinyvectors), which carries
its own blob physics, path generation, scroll handling and device motion
(`@tummycrypt/tinyvectors/core` and `@tummycrypt/tinyvectors/motion`,
registry module `tummycrypt_tinyvectors`). The APIs are not identical, so
callers port to the tinyvectors exports rather than swapping the import.

The registry module `tummycrypt_tinyland_physics` in
[xoxd-ai/bazel-registry](https://github.com/xoxd-ai/bazel-registry) is
marked deprecated. Its 0.2.2 entry stays resolvable and nothing is yanked,
so an existing pin keeps building. The package is no longer published to
npm or GitHub Packages; the publish workflow is removed. The source and
tags v0.1.0, v0.2.0 and v0.2.2 stay in place for reference.
