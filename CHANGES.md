# Depot changes

## v1.5.1

 * Merge [#13](https://github.com/Olical/depot/pull/13) - Fix a couple of issues with `--update`.

## v1.5.0

 * Merge [#9](https://github.com/Olical/depot/pull/9) - Ignore "RELEASE" and "LATEST", bring back Clojure 1.8 compatibility (as mentioned in [#7](https://github.com/Olical/depot/issues/7)).
 * Merge [#10](https://github.com/Olical/depot/pull/10) - Let --update also check :override-deps.

Even more improvements from [@plexus](https://github.com/plexus)! I also sorted out some formatting and deleted some unused forms, but that's all.

## v1.4.0

 * Merge [#6](https://github.com/Olical/depot/pull/6) - Updating `deps.edn` automatically with `--update`.

Thank you very much, [@plexus](https://github.com/plexus)!

## v1.3.0

 * Merge [#5](https://github.com/Olical/depot/pull/5) - Support `:override-deps`.
 * Bump `org.clojure/tools.cli` to `0.4.1`.
 * Bump `org.clojure/tools.deps.alpha` to `0.5.460`.

## v1.2.0

 * Merge [#4](https://github.com/Olical/depot/pull/4) - Add support for git dependencies.

Thank you, [@kennyjwilli](https://github.com/kennyjwilli), great contribution.

## v1.1.0

 * Merge [#3](https://github.com/Olical/depot/pull/3)
   * Only consider changes when selected and latest are non-blank strings.
   * Gather changes and print a nice table rather than printing as differences are found.
   * Print a message if no changes can be found.

Thank you very much, [@robert-stuttaford](https://github.com/robert-stuttaford)!

## v1.0.1

 * Only try to check dependencies that use the `:mvn/version` key, attempting to parse git shas was causing an error. [#1](https://github.com/Olical/depot/issues/1)

## v1.0.0

 * Initial release with `depot.outdated.main` that checks for outdated dependencies in your `deps.edn` file.
