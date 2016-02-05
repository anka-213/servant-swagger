1.0
---

* Major changes (see [#24](https://github.com/haskell-servant/servant-swagger/pull/24)):
    * Switch to `swagger2-2.*`;
    * Add automatic `ToJSON`/`ToSchema` validation tests;
    * Add great documentation;
    * Export some type-level functions for servant API.

* Minor changes:
    * Rework Todo API example;
    * Stop exporting `ToResponseHeader`, `AllAccept` and `AllToResponseHeader` (see [bd50db4](https://github.com/haskell-servant/servant-swagger/commit/bd50db48ca6a106e4366560ded70932d409de1e2));
    * Change maintainer, update authors/copyrights (see [1a62681](https://github.com/haskell-servant/servant-swagger/commit/1a6268101dc826a92c42e832e402e251c0d32147));
    * Include changelog and example files into `extra-source-files`.

0.1.2
---

* Fixes:
    * Fix default spec for `ReqBody` param to be required (see [#22](https://github.com/haskell-servant/servant-swagger/issues/22));
    * Set version bounds for `swagger2`.

0.1.1
---

* Fixes:
    * Fix `subOperations` to filter endpoints also by method (see [#18](https://github.com/haskell-servant/servant-swagger/issues/18));
    * Fix response schema in `ToSwagger` instance for `Header` (see [b59e557](https://github.com/haskell-servant/servant-swagger/commit/b59e557a05bc2669332c52b397879e7598747b82)).

0.1
---
* Major changes
    * Use `swagger2` for data model (see [#9](https://github.com/dmjio/servant-swagger/pull/9)); this changes almost everything.