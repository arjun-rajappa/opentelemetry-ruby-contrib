# Release History: opentelemetry-propagator-vitess

# 0.2.1 (2025-09-24)

## Release Summary

This release includes the following pull requests:

* [#1344](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1344) - chore: bump rubocop from 1.69.1 to 1.70.0
  PR to replace the dependabot PRs

* [#1347](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1347) - ci: Add Ruby 3.4 build

* [#1348](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1348) - release: Release 49 gems
  This pull request prepares new gem releases for the following gems:
  
   *  **opentelemetry-helpers-mysql 0.2.0** (was 0.1.2)
   *  **opentelemetry-helpers-sql-obfuscation 0.3.0** (was 0.2.1)
   *  **opentelemetry-instrumentation-grape 0.3.0** (was 0.2.0)
   *  **opentelemetry-instrumentation-racecar 0.4.0** (was 0.3.4)
   *  **opentelemetry-instrumentation-rake 0.3.0** (was 0.2.2)
   *  **opentelemetry-instrumentation-rdkafka 0.5.0** (was 0.4.9)
   *  **opentelemetry-instrumentation-trilogy 0.61.0** (was 0.60.0)
   *  **opentelemetry-instrumentation-active_support 0.8.0** (was 0.7.0)
   *  **opentelemetry-instrumentation-action_mailer 0.4.0** (was 0.3.0)
   *  **opentelemetry-instrumentation-action_view 0.9.0** (was 0.8.0)
   *  **opentelemetry-instrumentation-action_pack 0.11.0** (was 0.10.0)
   *  **opentelemetry-instrumentation-active_job 0.8.0** (was 0.7.8)
   *  **opentelemetry-instrumentation-resque 0.6.0** (was 0.5.2)
   *  **opentelemetry-instrumentation-bunny 0.22.0** (was 0.21.4)
   *  **opentelemetry-instrumentation-base 0.23.0** (was 0.22.6)
   *  **opentelemetry-instrumentation-active_record 0.9.0** (was 0.8.1)
   *  **opentelemetry-instrumentation-aws_sdk 0.8.0** (was 0.7.0)
   *  **opentelemetry-instrumentation-aws_lambda 0.2.0** (was 0.1.1)
   *  **opentelemetry-instrumentation-lmdb 0.23.0** (was 0.22.3)
   *  **opentelemetry-instrumentation-http 0.24.0** (was 0.23.5)
   *  **opentelemetry-instrumentation-graphql 0.29.0** (was 0.28.4)
   *  **opentelemetry-instrumentation-http_client 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-httpx 0.2.0** (was 0.1.3)
   *  **opentelemetry-instrumentation-koala 0.21.0** (was 0.20.6)
   *  **opentelemetry-instrumentation-active_model_serializers 0.22.0** (was 0.21.1)
   *  **opentelemetry-instrumentation-concurrent_ruby 0.22.0** (was 0.21.4)
   *  **opentelemetry-instrumentation-dalli 0.26.0** (was 0.25.4)
   *  **opentelemetry-instrumentation-delayed_job 0.23.0** (was 0.22.4)
   *  **opentelemetry-instrumentation-ethon 0.22.0** (was 0.21.9)
   *  **opentelemetry-instrumentation-excon 0.23.0** (was 0.22.5)
   *  **opentelemetry-instrumentation-faraday 0.26.0** (was 0.25.0)
   *  **opentelemetry-instrumentation-grpc 0.2.0** (was 0.1.3)
   *  **opentelemetry-instrumentation-gruf 0.3.0** (was 0.2.1)
   *  **opentelemetry-instrumentation-mongo 0.23.0** (was 0.22.4)
   *  **opentelemetry-instrumentation-mysql2 0.29.0** (was 0.28.0)
   *  **opentelemetry-instrumentation-net_http 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-pg 0.30.0** (was 0.29.2)
   *  **opentelemetry-instrumentation-que 0.9.0** (was 0.8.4)
   *  **opentelemetry-instrumentation-rack 0.26.0** (was 0.25.0)
   *  **opentelemetry-instrumentation-rails 0.35.0** (was 0.34.1)
   *  **opentelemetry-instrumentation-redis 0.26.0** (was 0.25.7)
   *  **opentelemetry-instrumentation-restclient 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-rspec 0.4.0** (was 0.3.3)
   *  **opentelemetry-instrumentation-ruby_kafka 0.22.0** (was 0.21.3)
   *  **opentelemetry-instrumentation-sidekiq 0.26.0** (was 0.25.7)
   *  **opentelemetry-instrumentation-sinatra 0.25.0** (was 0.24.1)
   *  **opentelemetry-instrumentation-all 0.72.0** (was 0.71.1)
   *  **opentelemetry-processor-baggage 0.3.0** (was 0.2.1)
   *  **opentelemetry-propagator-ottrace 0.22.0** (was 0.21.4)
   *  **opentelemetry-propagator-vitess 0.2.0** (was 0.1.1)
   *  **opentelemetry-propagator-xray 0.23.0** (was 0.22.3)
   *  **opentelemetry-resource-detector-azure 0.2.0** (was 0.1.1)
   *  **opentelemetry-resource-detector-container 0.2.0** (was 0.1.2)
   *  **opentelemetry-resource-detector-google_cloud_patform 0.2.0** (was 0.1.1)
  
  For each gem, this pull request modifies the gem version and provides an initial changelog entry based on [conventional commit](https://conventionalcommits.org) messages. You can edit these changes before merging, to release a different version or to alter the changelog text.
  
   *  To confirm this release, merge this pull request, ensuring the     "release: pending" label is set. The release     script will trigger automatically on merge.
   *  To abort this release, close this pull request without merging.
  
  The generated changelog entries have been copied below:
  
  ----
  
  ## opentelemetry-helpers-mysql
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-helpers-sql-obfuscation
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-grape
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-racecar
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rake
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rdkafka
  
  ### v0.5.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-trilogy
  
  ### v0.61.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_support
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_mailer
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_view
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_pack
  
  ### v0.11.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_job
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-resque
  
  ### v0.6.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-bunny
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-base
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_record
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-aws_sdk
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-aws_lambda
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-lmdb
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-http
  
  ### v0.24.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-graphql
  
  ### v0.29.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-http_client
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-httpx
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-koala
  
  ### v0.21.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_model_serializers
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-concurrent_ruby
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-dalli
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  * FIXED: Format gat commands
  
  ----
  
  ## opentelemetry-instrumentation-delayed_job
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-ethon
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-excon
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-faraday
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-grpc
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-gruf
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-mongo
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-mysql2
  
  ### v0.29.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-net_http
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-pg
  
  ### v0.30.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-que
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rack
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rails
  
  ### v0.35.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-redis
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-restclient
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rspec
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-ruby_kafka
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-sidekiq
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-sinatra
  
  ### v0.25.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-all
  
  ### v0.72.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-processor-baggage
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-ottrace
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-vitess
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-xray
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-azure
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-container
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-google_cloud_patform
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1

* [#1365](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1365) - chore: bump rubocop from 1.70.0 to 1.71.0

* [#1366](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1366) - test: Fix simplecov configuration
  Most of the gemspecs here include simplecov, but the majority did not invoke it. Of the ones that _did_ invoke it, none of them did so at the correct place, so the only coverage tracked was generally for the test helper itself. This commit adds a project-wide simplecov configuration file, requires simplecov in the correct place, and ensures results from different appraisals are merged (rather than clobbered).

* [#1388](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1388) - refactor: Define a single ruby required version
  I _think_ this will make it easier to enforce the same min Ruby version, as opposed to using a _find and replace_ strategy or a script to bump all the versions.
  
  IDK, wdyt?

* [#1426](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1426) - chore: Enable Gemfile Dev Deps
  > Enforce that development dependencies for a gem are specified in Gemfile, rather than in the gemspec using add_development_dependency. Alternatively, using EnforcedStyle: gemspec, enforce that all dependencies are specified in gemspec, rather than in Gemfile.
  
  https://docs.rubocop.org/rubocop/cops_gemspec.html#gemspecdevelopmentdependencies

* [#1429](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1429) - chore: update rubocop to 1.72.2
  Two changes related to newfound offenses:
  ```output
  lib/opentelemetry/instrumentation/rack/middlewares/event_handler.rb:120:11: W: Lint/UselessConstantScoping: Useless private access modifier for constant scope.
            EMPTY_HASH = {}.freeze
            ^^^^^^^^^^^^^^^^^^^^^^
  
  lib/opentelemetry/instrumentation/graphql/tracers/graphql_tracer.rb:129:15: W: Lint/CopDirectiveSyntax: Malformed directive comment detected. Cop names must be separated by commas. Comment in the directive must start with --.
                # rubocop:disable Style/SafeNavigation - using safe navigation creates more objects, we want to avoid this
                ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  ```
  
  🤖 Dependabot excerpt on this release: 
  
  > Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  > <details>
  > <summary>Release notes</summary>
  > <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  > <blockquote>
  > <h2>RuboCop 1.72.2</h2>
  > <h3>Bug fixes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13853">#13853</a>: Fix exclusion of relative paths in plugin's <code>AllCops: Exclude</code> as expected. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13844">#13844</a>: Fix an error for <code>Style/RedundantFormat</code> when a template argument is used without keyword arguments. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13857">#13857</a>: Fix an error for <code>Style/RedundantFormat</code> when numeric placeholders is used in the template argument. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13861">#13861</a>: Fix <code>ArgumentError</code> related to two deprecated <code>AllowedPattern</code> APIs. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13849">#13849</a>: Fix an error for <code>Lint/UselessConstantScoping</code> when multiple assigning to constants after <code>private</code> access modifier. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13856">#13856</a>: Fix false positives for <code>Lint/UselessConstantScoping</code> when a constant is used after <code>private</code> access modifier with arguments. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > </ul>
  > <h3>Changes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13846">#13846</a>: Mark <code>Style/RedundantFormat</code> as unsafe autocorrect. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > </ul>
  > </blockquote>
  > </details>
  > <details>
  > <summary>Changelog</summary>
  > <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  > <blockquote>
  > <h2>1.72.2 (2025-02-17)</h2>
  > <h3>Bug fixes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13853">#13853</a>: Fix exclusion of relative paths in plugin's <code>AllCops: Exclude</code> as expected. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13844">#13844</a>: Fix an error for <code>Style/RedundantFormat</code> when a template argument is used without keyword arguments. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13857">#13857</a>: Fix an error for <code>Style/RedundantFormat</code> when numeric placeholders is used in the template argument. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13861">#13861</a>: Fix <code>ArgumentError</code> related to two deprecated <code>AllowedPattern</code> APIs. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13849">#13849</a>: Fix an error for <code>Lint/UselessConstantScoping</code> when multiple assigning to constants after <code>private</code> access modifier. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13856">#13856</a>: Fix false positives for <code>Lint/UselessConstantScoping</code> when a constant is used after <code>private</code> access modifier with arguments. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > </ul>
  > <h3>Changes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13846">#13846</a>: Mark <code>Style/RedundantFormat</code> as unsafe autocorrect. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > </ul>
  > <h2>1.72.1 (2025-02-15)</h2>
  > <h3>Bug fixes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13836">#13836</a>: Fix an error for <code>Style/RedundantParentheses</code> when a different expression appears before a range literal. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13839">#13839</a>: Fix false positives for <code>Lint/RedundantTypeConversion</code> when passing block arguments when generating a Hash or a Set. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > </ul>
  > <h3>Changes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13839">#13839</a>: Extension plugin is loaded automatically with `require 'rubocop/rspec/support'. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > </ul>
  > <h2>1.72.0 (2025-02-14)</h2>
  > <h3>New features</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13740">#13740</a>: Add new <code>Lint/CopDirectiveSyntax</code> cop. ([<a href="https://github.com/kyanagi"><code>@​kyanagi</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13800">#13800</a>: Add new <code>Lint/SuppressedExceptionInNumberConversion</code> cop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13702">#13702</a>: Add new <code>Lint/RedundantTypeConversion</code> cop. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13831">#13831</a>: Add new <code>Lint/UselessConstantScoping</code> cop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13793">#13793</a>: Add new <code>Style/RedundantFormat</code> cop to check for uses of <code>format</code> or <code>sprintf</code> with only a single string argument. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13581">#13581</a>: Add new <code>InternalAffairs/LocationExists</code> cop to check for code that can be replaced with <code>Node#loc?</code> or <code>Node#loc_is?</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13661">#13661</a>: Make server mode detect local paths in .rubocop.yml under <code>inherit_from</code> and <code>require</code> for automatically restart. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13721">#13721</a>: <code>Naming/PredicateName</code>: Optionally use Sorbet to detect predicate methods. ([<a href="https://github.com/issyl0"><code>@​issyl0</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/6012">#6012</a>: Support RuboCop extension plugin. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > </ul>
  > <h3>Bug fixes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13807">#13807</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when chaining <code>[]</code> method calls. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13788">#13788</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when <code>[]</code> method is called with variable or constant receivers. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13811">#13811</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when handling range literals with redundant parentheses. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13796">#13796</a>: Fix crash in <code>Layout/EmptyLinesAroundMethodBody</code> for endless methods. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13817">#13817</a>: Fix false positive for format specifier with non-numeric precision. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12672">#12672</a>: Fix false positives for <code>Lint/FormatParameterMismatch</code> when the width value is interpolated. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12795">#12795</a>: Fix <code>Layout/BlockAlignment</code> for blocks that are the body of an endless method. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13822">#13822</a>: Fix undefined method Logger when processing watched file notifications. ([<a href="https://github.com/vinistock"><code>@​vinistock</code></a>][])</li>
  > </ul>
  > <!-- raw HTML omitted -->
  > </blockquote>
  > <p>... (truncated)</p>
  > </details>
  > <details>
  > <summary>Commits</summary>
  > <ul>
  > <li><a href="https://github.com/rubocop/rubocop/commit/869b5d4e9353e8a167fd92a416767af80e113fe5"><code>869b5d4</code></a> Cut 1.72.2</li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/7c361777d3d8814798a2dbb21bf7ab8c8fee1214"><code>7c36177</code></a> Update Changelog</li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/d4525d6d5bd824c78afd3c05d052ed0054975f22"><code>d4525d6</code></a> Correct Style/RedundantParentheses documentation</li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/7fc05f8b8521dd4d3a7a9b1d089a120d8f1415a5"><code>7fc05f8</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/13861">#13861</a>] Fix <code>ArgumentError</code> related to two deprecated <code>AllowedPattern</code> APIs</li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/aa8c0a97854a5e2249036ffd1514970f98096ba0"><code>aa8c0a9</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/13849">#13849</a>] Fix an error for <code>Lint/UselessConstantScoping</code></li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/241fe6be27a57bb314d9a99b90062ee06fd249af"><code>241fe6b</code></a> Fix an error for <code>Style/RedundantFormat</code></li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/b573711918799d59cc2342336ed7659cbfdc2471"><code>b573711</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/13856">#13856</a>] Fix false positives for <code>Lint/UselessConstantScoping</code></li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/e8119f745fe73f4e8f867b42c07dee3ed060f2ca"><code>e8119f7</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/13844">#13844</a>] Fix an error for <code>Style/RedundantFormat</code></li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/a807f7c38e8de4fa5f378931c50e98e47f89e568"><code>a807f7c</code></a> Fix exclusion of relative paths in plugin's <code>AllCops: Exclude</code> as expected</li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/28c2fe875ff08eb5468d78faffd86db1bf4a71a6"><code>28c2fe8</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/13850">#13850</a>] Fix false negatives for <code>InternalAffairs/ExampleDescription</code></li>
  > <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.71.0...v1.72.2">compare view</a></li>
  > </ul>
  > </details>
  > <br />
  > 
  >

* [#1445](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1445) - chore: bump rubocop and rubocop-performance gem versions 
  Replaces the dependabot PRs (#1440, #1441) for these versions to cover all Gemfiles.
  
  rubocop-performance from 1.23.0 to 1.24.0 
  rubocop from 1.72.0 to. 1.73.2

* [#1461](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1461) - chore: update rubocop requirement from ~> 1.73.2 to ~> 1.75.1
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.75.1</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.75.1 (2025-03-26)</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  </ul>
  <h2>1.75.0 (2025-03-26)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12049">#12049</a>: Add new <code>Style/HashFetchChain</code> cop to detect chained <code>fetch</code> calls that can be replaced with a single call to <code>dig</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13597">#13597</a>: Add new <code>Style/ItBlockParameter</code> cop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13899">#13899</a>: Enable reusable Prism parse result for Ruby LSP add-on. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14015">#14015</a>: Support <code>it</code> block parameter in <code>Layout</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14017">#14017</a>: Support <code>it</code> block parameter in <code>Lint</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14018">#14018</a>: Support <code>it</code> block parameter in <code>Metrics</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14013">#14013</a>: Support <code>it</code> block parameter in <code>Style</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14025">#14025</a>: Support <code>TargetRubyVersion: 3.5</code> (experimental). ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14022">#14022</a>: Fix an error for <code>Style/HashFetchChain</code> when no arguments are given to <code>fetch</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14028">#14028</a>: Fix false negative for <code>Layout/MultilineMethodParameterLineBreaks</code> when class method definitions are used. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14027">#14027</a>: Fix false negative for <code>Layout/LineLength</code> when autocorrecting class method definitions. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/8099">#8099</a>: Fix infinite loop between <code>Layout/SpaceAroundOperators</code> and <code>Layout/HashAlignment</code> with <code>EnforcedHashRocketStyle</code> being an array containing <code>table</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14021">#14021</a>: Fix handling of long heredoc lines with SplitStrings enabled. ([<a href="https://github.com/mauro-oto"><code>@​mauro-oto</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13968">#13968</a>: Fix <code>InternalAffairs/RedundantDescribedClassAsSubject</code> cop error on missing <code>describe</code>. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14036">#14036</a>: Fix false negative for <code>Lint/ShadowingOuterLocalVariable</code> when block local variable is used inside a condition. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13990">#13990</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when a variable is reassigned in a different branch. ([<a href="https://github.com/eugeneius"><code>@​eugeneius</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14012">#14012</a>: Fix incorrect autocorrections for <code>Style/SoleNestedConditional</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14020">#14020</a>: Fix comment autocorrection for <code>Style/IfInsideElse</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12358">#12358</a>: Add <code>does</code> as a forbidden prefix to <code>Naming/PredicateName</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13621">#13621</a>: Add <code>ForbiddenIdentifiers</code> and <code>ForbiddenPatterns</code> config options to <code>Naming/MethodName</code> cop. ([<a href="https://github.com/tejasbubane"><code>@​tejasbubane</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13986">#13986</a>: Add support for <code>Array#intersection</code> to <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14006">#14006</a>: Allow cop renames to trigger warnings instead of fatal errors. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13617">#13617</a>: Use the <code>prism</code> translation layer to analyze Ruby 3.4+ by default. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14024">#14024</a>: Change <code>Style/RedundantParentheses</code> to offend parentheses for chained <code>&amp;&amp;</code> expressions. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14029">#14029</a>: Add <code>AllowConsecutiveConditionals</code> setting to <code>Style/Next</code> to allow consecutive conditional statements. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14016">#14016</a>: Update <code>Style/RedundantFormat</code> to register offenses when the only argument to <code>format</code> or <code>sprintf</code> is a constant. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h2>1.74.0 (2025-03-13)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13936">#13936</a>: Adds new cop <code>Style/ComparableBetween</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13943">#13943</a>: Allow writing steep annotation to method definition for <code>Style/CommentedKeyword</code>. ([<a href="https://github.com/dak2"><code>@​dak2</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/3872dced1fa9de4a93a31c981e33aadbebf41a7c"><code>3872dce</code></a> Cut 1.75.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/b0999f3767ad9c3eedd770442254261f5bb414d7"><code>b0999f3</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/3ed6febf8adcd9a58e9e1f3084529adc65c94853"><code>3ed6feb</code></a> Rename <code>allow_named_parameter</code> to <code>only_numbered_parameters</code> in `Style/ItBloc...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/784abb29c89953349faafefb6df79ce8bf3f0164"><code>784abb2</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14039">#14039</a> from lovro-bikic/adjust-raise-args-docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/246dee9af40f217c2a400b159ac8c1698040e8cc"><code>246dee9</code></a> Update Style/RaiseArgs docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/cf5e38211cf90ca48afbf375b12c148bd6b008cb"><code>cf5e382</code></a> Reset the docs version</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9c2bc8eb11e269f1cf47113041a1be3ff615f68b"><code>9c2bc8e</code></a> Cut 1.75</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/95ed9879fda27a77a26e72505ce52b7d9ca2fb8f"><code>95ed987</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/f969e0d7369bb04900cb07c97820203f2db8ea29"><code>f969e0d</code></a> Fix handling of long heredoc lines with SplitStrings enabled</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/91fafeb3c06b3a0ea60548662a2cae777e080d3d"><code>91fafeb</code></a> Fix comment autocorrection for Style/IfInsideElse</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.73.2...v1.75.1">compare view</a></li>
  </ul>
  </details>
  <br />

* [#1558](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1558) - chore: update rubocop requirement from ~> 1.75.1 to ~> 1.76.2
  _when I was able to run the update dependencies script, a newer version of rubocop had already been released_
  
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.76.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. (<a href="https://github.com/ka8725"><code>@​ka8725</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.76.1 (2025-06-09)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. ([<a href="https://github.com/ka8725"><code>@​ka8725</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h2>1.76.0 (2025-06-04)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12360">#12360</a>: Add new <code>Naming/PredicateMethod</code> cop to check that predicate methods end with <code>?</code> and non-predicate methods do not. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13121">#13121</a>: Add new <code>Style/EmptyStringInsideInterpolation</code> cop. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14091">#14091</a>: Add new cop <code>Style/RedundantArrayFlatten</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14184">#14184</a>: Add new cop <code>Lint/UselessOr</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14221">#14221</a>: Enhance <code>Gemspec</code> department cops to detect offenses if specification variable is <code>it</code> or a numbered parameter. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14166">#14166</a>: Add new cop <code>Lint/UselessDefaultValueArgument</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14228">#14228</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when using a one-line <code>rescue</code> expression as a method argument. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14224">#14224</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when using one-line pattern matching. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14205">#14205</a>: False negatives in <code>Style/SafeNavigation</code> when a ternary expression is used in a method argument. ([<a href="https://github.com/steiley"><code>@​steiley</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14226">#14226</a>: Fix <code>Lint/LiteralAsCondition</code> autocorrect when branches of a condition have comments. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14066">#14066</a>: Add <code>EnforcedStyle: allow_single_line</code> as the default to <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13788">#13788</a>: Disable <code>Lint/ShadowingOuterLocalVariable</code> by default. ([<a href="https://github.com/nekketsuuu"><code>@​nekketsuuu</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14215">#14215</a>: Recognize inequation (<code>!=</code>) in <code>Lint/IdentityComparison</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.75.8 (2025-05-28)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14191">#14191</a>: Fix <code>Lint/FloatComparison</code> cop to detect floating-point number comparisons in <code>case</code> statements. ([<a href="https://github.com/daisuke"><code>@​daisuke</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14209">#14209</a>: Fix an error for <code>Style/RedundantFormat</code> with invalid format arguments. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14200">#14200</a>: Fix false positives for <code>Style/DefWithParentheses</code> when using endless method definition with empty parentheses and a space before <code>=</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14197">#14197</a>: Fix infinite loop error for <code>EnforcedStyle: with_fixed_indentation</code> of <code>Layout/ArgumentAlignment</code> and <code>EnforcedStyle: consistent</code> of <code>Layout/FirstArgumentIndentation</code> and <code>Layout/HashAlignment</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14204">#14204</a>: Fix <code>Layout/EmptyLinesAroundAccessModifier</code> cop error on trailing access modifier. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14198">#14198</a>: Fix <code>Lint/DuplicateMethods</code> cop error on <code>to</code> option is dynamically generated and <code>prefix</code> is enabled. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14199">#14199</a>: Fix wrong autocorrection for <code>Style/MapToHash</code> with destructuring argument. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14050">#14050</a>: Modify condition for <code>rubocop:todo</code> EOL comment. ([<a href="https://github.com/jonas054"><code>@​jonas054</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/c74a5b3e838a01e535e3c59b03960a2e273a9b65"><code>c74a5b3</code></a> Cut 1.76.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/c78ad7af9ba2755b5a2471796196bcb64520430e"><code>c78ad7a</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0bd38fff7c79b66356ee1b018be102f71a8d3dd6"><code>0bd38ff</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>] Fix false positives for <code>Style/RedundantArrayFlatten</code></li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bf526269c929a7cf8d26b9d19a5ba8d8a019a2c2"><code>bf52626</code></a> Improve <code>expect_offense</code> interpolation documentation</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/d0dfd683abd1f00ffeebbe61fbb86c446825de16"><code>d0dfd68</code></a> Add new rake task to verify config references availability</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/44f5eb772990ea73dd790fdc3b5f528388b21816"><code>44f5eb7</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14259">#14259</a> from koic/fix_build_error_on_windows_matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/ed880df1855d36e7346a73ad7d8ba3e1c0e85512"><code>ed880df</code></a> Fix build errors on Winsows matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9316b04a691df3244bc148a8cfe6d8d8f21c337c"><code>9316b04</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14244">#14244</a> from koic/fix_false_positives_for_style_redundant_p...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bb32f69c0cc5259db5fc235ba8a48d6257c51d73"><code>bb32f69</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14252">#14252</a> from koic/workaround_ruby_lsp_0_24</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/067da9d3d23c799cae6d8e02111f020cac64ae49"><code>067da9d</code></a> Workaround to avoid build error in Ruby LSP add-on test with Ruby LSP 0.24</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.75.1...v1.76.1">compare view</a></li>
  </ul>
  </details>
  <br />
  
  
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.
  
  [//]: # (dependabot-automerge-start)
  [//]: # (dependabot-automerge-end)
  
  ---
  
  <details>
  <summary>Dependabot commands and options</summary>
  <br />
  
  You can trigger Dependabot actions by commenting on this PR:
  - `@dependabot rebase` will rebase this PR
  - `@dependabot recreate` will recreate this PR, overwriting any edits that have been made to it
  - `@dependabot merge` will merge this PR after your CI passes on it
  - `@dependabot squash and merge` will squash and merge this PR after your CI passes on it
  - `@dependabot cancel merge` will cancel a previously requested merge and block automerging
  - `@dependabot reopen` will reopen this PR if it is closed
  - `@dependabot close` will close this PR and stop Dependabot recreating it. You can achieve the same result by closing it manually
  - `@dependabot show <dependency name> ignore conditions` will show all of the ignore conditions of the specified dependency
  - `@dependabot ignore this major version` will close this PR and stop Dependabot creating any more for this major version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this minor version` will close this PR and stop Dependabot creating any more for this minor version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this dependency` will close this PR and stop Dependabot creating any more for this dependency (unless you reopen the PR or upgrade to it yourself)
  
  
  </details>

* [#1595](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1595) - chore: update rubocop requirement from ~> 1.76.2 to ~> 1.78.0
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.

* [#1614](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1614) - chore: update rubocop requirement from ~> 1.78.0 to ~> 1.79.1
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.79.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. (<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>)</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. (<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.79.1 (2025-07-31)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. ([<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h2>1.79.0 (2025-07-24)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14348">#14348</a>: Add new cop <code>Layout/EmptyLinesAfterModuleInclusion</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14374">#14374</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>Data</code> members. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14373">#14373</a>: Fix an error for <code>Style/ParallelAssignment</code> when a lambda with parallel assignment is used on the RHS. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14370">#14370</a>: Fix comment duplication bug in <code>Style/AccessorGrouping</code> separated autocorrect. ([<a href="https://github.com/r7kamura"><code>@​r7kamura</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14377">#14377</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when the assignment is inside a loop body. ([<a href="https://github.com/5hun-s"><code>@​5hun-s</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14355">#14355</a>: Fix a false negative for <code>Style/RedundantParentheses</code> when using parentheses around a <code>rescue</code> expression on a one-line. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14354">#14354</a>: Fix incorrect autocorrect for <code>Style/AccessModifierDeclarations</code> when using a grouped access modifier declaration. ([<a href="https://github.com/girasquid"><code>@​girasquid</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14367">#14367</a>: Fix an incorrect autocorrect for <code>Style/SingleLineMethods</code> when defining a single-line singleton method. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14344">#14344</a>: Fix incorrect autocorrect for <code>Style/SingleLineMethods</code> when a single-line method definition contains a modifier. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14350">#14350</a>: Fix <code>Naming/MethodName</code> cop false positives with <code>define_method</code> and operator names. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14333">#14333</a>: Fix <code>Naming/PredicateMethod</code> ignoring the implicit <code>nil</code> from missing <code>else</code> branches. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14356">#14356</a>: Fix <code>Style/ItBlockParameter</code> cop error on <code>always</code> style and missing block body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14362">#14362</a>: Update <code>Lint/RequireRangeParentheses</code> to not register false positives when range elements span multiple lines. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14309">#14309</a>: Update <code>Style/SoleNestedConditional</code> to properly correct assignments within <code>and</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14358">#14358</a>: Add <code>tsort</code> gem to runtime dependency for Ruby 3.5-dev. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14322">#14322</a>: Expand the scope of <code>Style/ItAssignment</code> to consider all local variable and method parameter names. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14378">#14378</a>: Change <code>Layout/SpaceAroundKeyword</code> to offend for missing whitespace between <code>return</code> and opening parenthesis. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14360">#14360</a>: Make <code>Layout/SpaceAroundOperators</code> aware of alternative and as pattern matchings. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14375">#14375</a>: Make <code>Lint/RedundantSafeNavigation</code> aware of builtin convert methods <code>to_s</code>, <code>to_i</code>, <code>to_f</code>, <code>to_a</code>, and <code>to_h</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13835">#13835</a>: Add <code>InferNonNilReceiver</code> config to <code>Lint/RedundantSafeNavigation</code> to check previous code paths if the receiver is non-nil. ([<a href="https://github.com/fatkodima"><code>@​fatkodima</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14381">#14381</a>: Offend <code>array1.any? { |elem| array2.member?(elem) }</code> and <code>array1.none? { |elem| array2.member?(elem) }</code> in <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.78.0 (2025-07-08)</h2>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/5ecd375e149e1aa4054711ef1d637f2acbfd92ac"><code>5ecd375</code></a> Cut 1.79.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0b19d9215392a34991ecbd11de0bde6e27d13cf8"><code>0b19d92</code></a> Tweak a couple of changelog entries</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/300bc8674d348afbed8fb10c4ea0895ada1453fa"><code>300bc86</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/8e6be288701175d4c4f63f452fe4268e8bc9bc36"><code>8e6be28</code></a> Add support for or nodes to Lint/LiteralAsCondition</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/6adbb279fba7782fac4ada65611930b07eed127b"><code>6adbb27</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14405">#14405</a> from viralpraxis/fix-naming-method-name-cop-spec-de...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/968229405da46c16136f14cc8aa011c09f113a6f"><code>9682294</code></a> Fix <code>Naming/MethodName</code> cop spec descriptions</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/fc0e660eaa2c12513ad2cd8e77dd4f7f5ad52a9e"><code>fc0e660</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14403">#14403</a> from viralpraxis/enhance-naming-method-name-to-hand...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/19f9c0b4e597a7ae28483874d4cd9380bb2934f2"><code>19f9c0b</code></a> Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and `alias_...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9d262b14e3f5f6e2c1922670f36909e4d0002704"><code>9d262b1</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14400">#14400</a> from koic/fix_false_positive_for_layout_empty_lines...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/13c50509aafe9c0a0be9253a4756c6bfb2189575"><code>13c5050</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>] Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code></li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.78.0...v1.79.1">compare view</a></li>
  </ul>
  </details>
  <br />

### General Changes

* chore: update rubocop requirement from ~> 1.78.0 to ~> 1.79.1 ([#1614](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1614) [975e5ee](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/975e5ee7eece401424e07613c728c2a791580a90))
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.79.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. (<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>)</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. (<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.79.1 (2025-07-31)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. ([<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h2>1.79.0 (2025-07-24)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14348">#14348</a>: Add new cop <code>Layout/EmptyLinesAfterModuleInclusion</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14374">#14374</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>Data</code> members. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14373">#14373</a>: Fix an error for <code>Style/ParallelAssignment</code> when a lambda with parallel assignment is used on the RHS. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14370">#14370</a>: Fix comment duplication bug in <code>Style/AccessorGrouping</code> separated autocorrect. ([<a href="https://github.com/r7kamura"><code>@​r7kamura</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14377">#14377</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when the assignment is inside a loop body. ([<a href="https://github.com/5hun-s"><code>@​5hun-s</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14355">#14355</a>: Fix a false negative for <code>Style/RedundantParentheses</code> when using parentheses around a <code>rescue</code> expression on a one-line. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14354">#14354</a>: Fix incorrect autocorrect for <code>Style/AccessModifierDeclarations</code> when using a grouped access modifier declaration. ([<a href="https://github.com/girasquid"><code>@​girasquid</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14367">#14367</a>: Fix an incorrect autocorrect for <code>Style/SingleLineMethods</code> when defining a single-line singleton method. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14344">#14344</a>: Fix incorrect autocorrect for <code>Style/SingleLineMethods</code> when a single-line method definition contains a modifier. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14350">#14350</a>: Fix <code>Naming/MethodName</code> cop false positives with <code>define_method</code> and operator names. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14333">#14333</a>: Fix <code>Naming/PredicateMethod</code> ignoring the implicit <code>nil</code> from missing <code>else</code> branches. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14356">#14356</a>: Fix <code>Style/ItBlockParameter</code> cop error on <code>always</code> style and missing block body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14362">#14362</a>: Update <code>Lint/RequireRangeParentheses</code> to not register false positives when range elements span multiple lines. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14309">#14309</a>: Update <code>Style/SoleNestedConditional</code> to properly correct assignments within <code>and</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14358">#14358</a>: Add <code>tsort</code> gem to runtime dependency for Ruby 3.5-dev. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14322">#14322</a>: Expand the scope of <code>Style/ItAssignment</code> to consider all local variable and method parameter names. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14378">#14378</a>: Change <code>Layout/SpaceAroundKeyword</code> to offend for missing whitespace between <code>return</code> and opening parenthesis. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14360">#14360</a>: Make <code>Layout/SpaceAroundOperators</code> aware of alternative and as pattern matchings. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14375">#14375</a>: Make <code>Lint/RedundantSafeNavigation</code> aware of builtin convert methods <code>to_s</code>, <code>to_i</code>, <code>to_f</code>, <code>to_a</code>, and <code>to_h</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13835">#13835</a>: Add <code>InferNonNilReceiver</code> config to <code>Lint/RedundantSafeNavigation</code> to check previous code paths if the receiver is non-nil. ([<a href="https://github.com/fatkodima"><code>@​fatkodima</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14381">#14381</a>: Offend <code>array1.any? { |elem| array2.member?(elem) }</code> and <code>array1.none? { |elem| array2.member?(elem) }</code> in <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.78.0 (2025-07-08)</h2>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/5ecd375e149e1aa4054711ef1d637f2acbfd92ac"><code>5ecd375</code></a> Cut 1.79.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0b19d9215392a34991ecbd11de0bde6e27d13cf8"><code>0b19d92</code></a> Tweak a couple of changelog entries</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/300bc8674d348afbed8fb10c4ea0895ada1453fa"><code>300bc86</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/8e6be288701175d4c4f63f452fe4268e8bc9bc36"><code>8e6be28</code></a> Add support for or nodes to Lint/LiteralAsCondition</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/6adbb279fba7782fac4ada65611930b07eed127b"><code>6adbb27</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14405">#14405</a> from viralpraxis/fix-naming-method-name-cop-spec-de...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/968229405da46c16136f14cc8aa011c09f113a6f"><code>9682294</code></a> Fix <code>Naming/MethodName</code> cop spec descriptions</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/fc0e660eaa2c12513ad2cd8e77dd4f7f5ad52a9e"><code>fc0e660</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14403">#14403</a> from viralpraxis/enhance-naming-method-name-to-hand...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/19f9c0b4e597a7ae28483874d4cd9380bb2934f2"><code>19f9c0b</code></a> Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and `alias_...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9d262b14e3f5f6e2c1922670f36909e4d0002704"><code>9d262b1</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14400">#14400</a> from koic/fix_false_positive_for_layout_empty_lines...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/13c50509aafe9c0a0be9253a4756c6bfb2189575"><code>13c5050</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>] Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code></li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.78.0...v1.79.1">compare view</a></li>
  </ul>
  </details>
  <br />

* chore: update rubocop requirement from ~> 1.78.0 to ~> 1.79.1 ([#1614](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1614) [975e5ee](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/975e5ee7eece401424e07613c728c2a791580a90))
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.79.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. (<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>)</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. (<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.79.1 (2025-07-31)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. ([<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h2>1.79.0 (2025-07-24)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14348">#14348</a>: Add new cop <code>Layout/EmptyLinesAfterModuleInclusion</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14374">#14374</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>Data</code> members. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14373">#14373</a>: Fix an error for <code>Style/ParallelAssignment</code> when a lambda with parallel assignment is used on the RHS. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14370">#14370</a>: Fix comment duplication bug in <code>Style/AccessorGrouping</code> separated autocorrect. ([<a href="https://github.com/r7kamura"><code>@​r7kamura</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14377">#14377</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when the assignment is inside a loop body. ([<a href="https://github.com/5hun-s"><code>@​5hun-s</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14355">#14355</a>: Fix a false negative for <code>Style/RedundantParentheses</code> when using parentheses around a <code>rescue</code> expression on a one-line. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14354">#14354</a>: Fix incorrect autocorrect for <code>Style/AccessModifierDeclarations</code> when using a grouped access modifier declaration. ([<a href="https://github.com/girasquid"><code>@​girasquid</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14367">#14367</a>: Fix an incorrect autocorrect for <code>Style/SingleLineMethods</code> when defining a single-line singleton method. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14344">#14344</a>: Fix incorrect autocorrect for <code>Style/SingleLineMethods</code> when a single-line method definition contains a modifier. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14350">#14350</a>: Fix <code>Naming/MethodName</code> cop false positives with <code>define_method</code> and operator names. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14333">#14333</a>: Fix <code>Naming/PredicateMethod</code> ignoring the implicit <code>nil</code> from missing <code>else</code> branches. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14356">#14356</a>: Fix <code>Style/ItBlockParameter</code> cop error on <code>always</code> style and missing block body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14362">#14362</a>: Update <code>Lint/RequireRangeParentheses</code> to not register false positives when range elements span multiple lines. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14309">#14309</a>: Update <code>Style/SoleNestedConditional</code> to properly correct assignments within <code>and</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14358">#14358</a>: Add <code>tsort</code> gem to runtime dependency for Ruby 3.5-dev. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14322">#14322</a>: Expand the scope of <code>Style/ItAssignment</code> to consider all local variable and method parameter names. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14378">#14378</a>: Change <code>Layout/SpaceAroundKeyword</code> to offend for missing whitespace between <code>return</code> and opening parenthesis. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14360">#14360</a>: Make <code>Layout/SpaceAroundOperators</code> aware of alternative and as pattern matchings. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14375">#14375</a>: Make <code>Lint/RedundantSafeNavigation</code> aware of builtin convert methods <code>to_s</code>, <code>to_i</code>, <code>to_f</code>, <code>to_a</code>, and <code>to_h</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13835">#13835</a>: Add <code>InferNonNilReceiver</code> config to <code>Lint/RedundantSafeNavigation</code> to check previous code paths if the receiver is non-nil. ([<a href="https://github.com/fatkodima"><code>@​fatkodima</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14381">#14381</a>: Offend <code>array1.any? { |elem| array2.member?(elem) }</code> and <code>array1.none? { |elem| array2.member?(elem) }</code> in <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.78.0 (2025-07-08)</h2>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/5ecd375e149e1aa4054711ef1d637f2acbfd92ac"><code>5ecd375</code></a> Cut 1.79.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0b19d9215392a34991ecbd11de0bde6e27d13cf8"><code>0b19d92</code></a> Tweak a couple of changelog entries</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/300bc8674d348afbed8fb10c4ea0895ada1453fa"><code>300bc86</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/8e6be288701175d4c4f63f452fe4268e8bc9bc36"><code>8e6be28</code></a> Add support for or nodes to Lint/LiteralAsCondition</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/6adbb279fba7782fac4ada65611930b07eed127b"><code>6adbb27</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14405">#14405</a> from viralpraxis/fix-naming-method-name-cop-spec-de...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/968229405da46c16136f14cc8aa011c09f113a6f"><code>9682294</code></a> Fix <code>Naming/MethodName</code> cop spec descriptions</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/fc0e660eaa2c12513ad2cd8e77dd4f7f5ad52a9e"><code>fc0e660</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14403">#14403</a> from viralpraxis/enhance-naming-method-name-to-hand...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/19f9c0b4e597a7ae28483874d4cd9380bb2934f2"><code>19f9c0b</code></a> Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and `alias_...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9d262b14e3f5f6e2c1922670f36909e4d0002704"><code>9d262b1</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14400">#14400</a> from koic/fix_false_positive_for_layout_empty_lines...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/13c50509aafe9c0a0be9253a4756c6bfb2189575"><code>13c5050</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>] Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code></li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.78.0...v1.79.1">compare view</a></li>
  </ul>
  </details>
  <br />

* chore: update rubocop requirement from ~> 1.78.0 to ~> 1.79.1 ([#1614](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1614) [975e5ee](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/975e5ee7eece401424e07613c728c2a791580a90))
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.79.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. (<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>)</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. (<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.79.1 (2025-07-31)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. ([<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h2>1.79.0 (2025-07-24)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14348">#14348</a>: Add new cop <code>Layout/EmptyLinesAfterModuleInclusion</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14374">#14374</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>Data</code> members. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14373">#14373</a>: Fix an error for <code>Style/ParallelAssignment</code> when a lambda with parallel assignment is used on the RHS. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14370">#14370</a>: Fix comment duplication bug in <code>Style/AccessorGrouping</code> separated autocorrect. ([<a href="https://github.com/r7kamura"><code>@​r7kamura</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14377">#14377</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when the assignment is inside a loop body. ([<a href="https://github.com/5hun-s"><code>@​5hun-s</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14355">#14355</a>: Fix a false negative for <code>Style/RedundantParentheses</code> when using parentheses around a <code>rescue</code> expression on a one-line. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14354">#14354</a>: Fix incorrect autocorrect for <code>Style/AccessModifierDeclarations</code> when using a grouped access modifier declaration. ([<a href="https://github.com/girasquid"><code>@​girasquid</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14367">#14367</a>: Fix an incorrect autocorrect for <code>Style/SingleLineMethods</code> when defining a single-line singleton method. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14344">#14344</a>: Fix incorrect autocorrect for <code>Style/SingleLineMethods</code> when a single-line method definition contains a modifier. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14350">#14350</a>: Fix <code>Naming/MethodName</code> cop false positives with <code>define_method</code> and operator names. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14333">#14333</a>: Fix <code>Naming/PredicateMethod</code> ignoring the implicit <code>nil</code> from missing <code>else</code> branches. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14356">#14356</a>: Fix <code>Style/ItBlockParameter</code> cop error on <code>always</code> style and missing block body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14362">#14362</a>: Update <code>Lint/RequireRangeParentheses</code> to not register false positives when range elements span multiple lines. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14309">#14309</a>: Update <code>Style/SoleNestedConditional</code> to properly correct assignments within <code>and</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14358">#14358</a>: Add <code>tsort</code> gem to runtime dependency for Ruby 3.5-dev. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14322">#14322</a>: Expand the scope of <code>Style/ItAssignment</code> to consider all local variable and method parameter names. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14378">#14378</a>: Change <code>Layout/SpaceAroundKeyword</code> to offend for missing whitespace between <code>return</code> and opening parenthesis. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14360">#14360</a>: Make <code>Layout/SpaceAroundOperators</code> aware of alternative and as pattern matchings. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14375">#14375</a>: Make <code>Lint/RedundantSafeNavigation</code> aware of builtin convert methods <code>to_s</code>, <code>to_i</code>, <code>to_f</code>, <code>to_a</code>, and <code>to_h</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13835">#13835</a>: Add <code>InferNonNilReceiver</code> config to <code>Lint/RedundantSafeNavigation</code> to check previous code paths if the receiver is non-nil. ([<a href="https://github.com/fatkodima"><code>@​fatkodima</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14381">#14381</a>: Offend <code>array1.any? { |elem| array2.member?(elem) }</code> and <code>array1.none? { |elem| array2.member?(elem) }</code> in <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.78.0 (2025-07-08)</h2>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/5ecd375e149e1aa4054711ef1d637f2acbfd92ac"><code>5ecd375</code></a> Cut 1.79.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0b19d9215392a34991ecbd11de0bde6e27d13cf8"><code>0b19d92</code></a> Tweak a couple of changelog entries</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/300bc8674d348afbed8fb10c4ea0895ada1453fa"><code>300bc86</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/8e6be288701175d4c4f63f452fe4268e8bc9bc36"><code>8e6be28</code></a> Add support for or nodes to Lint/LiteralAsCondition</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/6adbb279fba7782fac4ada65611930b07eed127b"><code>6adbb27</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14405">#14405</a> from viralpraxis/fix-naming-method-name-cop-spec-de...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/968229405da46c16136f14cc8aa011c09f113a6f"><code>9682294</code></a> Fix <code>Naming/MethodName</code> cop spec descriptions</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/fc0e660eaa2c12513ad2cd8e77dd4f7f5ad52a9e"><code>fc0e660</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14403">#14403</a> from viralpraxis/enhance-naming-method-name-to-hand...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/19f9c0b4e597a7ae28483874d4cd9380bb2934f2"><code>19f9c0b</code></a> Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and `alias_...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9d262b14e3f5f6e2c1922670f36909e4d0002704"><code>9d262b1</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14400">#14400</a> from koic/fix_false_positive_for_layout_empty_lines...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/13c50509aafe9c0a0be9253a4756c6bfb2189575"><code>13c5050</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>] Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code></li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.78.0...v1.79.1">compare view</a></li>
  </ul>
  </details>
  <br />

* chore: update rubocop requirement from ~> 1.78.0 to ~> 1.79.1 ([#1614](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1614) [975e5ee](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/975e5ee7eece401424e07613c728c2a791580a90))
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.79.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. (<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>)</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. (<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.79.1 (2025-07-31)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. ([<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h2>1.79.0 (2025-07-24)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14348">#14348</a>: Add new cop <code>Layout/EmptyLinesAfterModuleInclusion</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14374">#14374</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>Data</code> members. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14373">#14373</a>: Fix an error for <code>Style/ParallelAssignment</code> when a lambda with parallel assignment is used on the RHS. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14370">#14370</a>: Fix comment duplication bug in <code>Style/AccessorGrouping</code> separated autocorrect. ([<a href="https://github.com/r7kamura"><code>@​r7kamura</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14377">#14377</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when the assignment is inside a loop body. ([<a href="https://github.com/5hun-s"><code>@​5hun-s</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14355">#14355</a>: Fix a false negative for <code>Style/RedundantParentheses</code> when using parentheses around a <code>rescue</code> expression on a one-line. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14354">#14354</a>: Fix incorrect autocorrect for <code>Style/AccessModifierDeclarations</code> when using a grouped access modifier declaration. ([<a href="https://github.com/girasquid"><code>@​girasquid</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14367">#14367</a>: Fix an incorrect autocorrect for <code>Style/SingleLineMethods</code> when defining a single-line singleton method. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14344">#14344</a>: Fix incorrect autocorrect for <code>Style/SingleLineMethods</code> when a single-line method definition contains a modifier. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14350">#14350</a>: Fix <code>Naming/MethodName</code> cop false positives with <code>define_method</code> and operator names. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14333">#14333</a>: Fix <code>Naming/PredicateMethod</code> ignoring the implicit <code>nil</code> from missing <code>else</code> branches. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14356">#14356</a>: Fix <code>Style/ItBlockParameter</code> cop error on <code>always</code> style and missing block body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14362">#14362</a>: Update <code>Lint/RequireRangeParentheses</code> to not register false positives when range elements span multiple lines. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14309">#14309</a>: Update <code>Style/SoleNestedConditional</code> to properly correct assignments within <code>and</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14358">#14358</a>: Add <code>tsort</code> gem to runtime dependency for Ruby 3.5-dev. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14322">#14322</a>: Expand the scope of <code>Style/ItAssignment</code> to consider all local variable and method parameter names. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14378">#14378</a>: Change <code>Layout/SpaceAroundKeyword</code> to offend for missing whitespace between <code>return</code> and opening parenthesis. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14360">#14360</a>: Make <code>Layout/SpaceAroundOperators</code> aware of alternative and as pattern matchings. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14375">#14375</a>: Make <code>Lint/RedundantSafeNavigation</code> aware of builtin convert methods <code>to_s</code>, <code>to_i</code>, <code>to_f</code>, <code>to_a</code>, and <code>to_h</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13835">#13835</a>: Add <code>InferNonNilReceiver</code> config to <code>Lint/RedundantSafeNavigation</code> to check previous code paths if the receiver is non-nil. ([<a href="https://github.com/fatkodima"><code>@​fatkodima</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14381">#14381</a>: Offend <code>array1.any? { |elem| array2.member?(elem) }</code> and <code>array1.none? { |elem| array2.member?(elem) }</code> in <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.78.0 (2025-07-08)</h2>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/5ecd375e149e1aa4054711ef1d637f2acbfd92ac"><code>5ecd375</code></a> Cut 1.79.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0b19d9215392a34991ecbd11de0bde6e27d13cf8"><code>0b19d92</code></a> Tweak a couple of changelog entries</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/300bc8674d348afbed8fb10c4ea0895ada1453fa"><code>300bc86</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/8e6be288701175d4c4f63f452fe4268e8bc9bc36"><code>8e6be28</code></a> Add support for or nodes to Lint/LiteralAsCondition</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/6adbb279fba7782fac4ada65611930b07eed127b"><code>6adbb27</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14405">#14405</a> from viralpraxis/fix-naming-method-name-cop-spec-de...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/968229405da46c16136f14cc8aa011c09f113a6f"><code>9682294</code></a> Fix <code>Naming/MethodName</code> cop spec descriptions</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/fc0e660eaa2c12513ad2cd8e77dd4f7f5ad52a9e"><code>fc0e660</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14403">#14403</a> from viralpraxis/enhance-naming-method-name-to-hand...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/19f9c0b4e597a7ae28483874d4cd9380bb2934f2"><code>19f9c0b</code></a> Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and `alias_...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9d262b14e3f5f6e2c1922670f36909e4d0002704"><code>9d262b1</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14400">#14400</a> from koic/fix_false_positive_for_layout_empty_lines...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/13c50509aafe9c0a0be9253a4756c6bfb2189575"><code>13c5050</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>] Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code></li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.78.0...v1.79.1">compare view</a></li>
  </ul>
  </details>
  <br />

* chore: update rubocop requirement from ~> 1.78.0 to ~> 1.79.1 ([#1614](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1614) [975e5ee](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/975e5ee7eece401424e07613c728c2a791580a90))
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.79.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. (<a href="https://github.com/earlopain"><code>@​earlopain</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. (<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>)</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. (<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.79.1 (2025-07-31)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14390">#14390</a>: Fix wrong autocorrect for <code>Style/ArgumentsForwarding</code> when the method arguments contain <code>*</code>, <code>**</code> or <code>&amp;</code>, and the method call contains <code>self</code> as the first argument. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>: Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code> when <code>prepend</code> is used with block methods. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14396">#14396</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside a ternary operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14383">#14383</a>: Fix false positives for <code>Lint/UselessAssignment</code> when duplicate assignments in <code>if</code> branch inside a loop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14394">#14394</a>: Fix false positive for <code>Lint/UselessAssignment</code> with <code>retry</code> in <code>rescue</code> branch. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14386">#14386</a>: Fix false positives for <code>Style/RedundantParentheses</code> when parentheses are used around a one-line <code>rescue</code> expression inside array or hash literals. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14395">#14395</a>: Fix LSP handling of URI-encoded paths with spaces. ([<a href="https://github.com/hakanensari"><code>@​hakanensari</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14403">#14403</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and <code>alias_method</code> calls. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14389">#14389</a>: Add support for <code>||</code> to <code>Lint/LiteralAsCondition</code>. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h2>1.79.0 (2025-07-24)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14348">#14348</a>: Add new cop <code>Layout/EmptyLinesAfterModuleInclusion</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14374">#14374</a>: Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>Data</code> members. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14373">#14373</a>: Fix an error for <code>Style/ParallelAssignment</code> when a lambda with parallel assignment is used on the RHS. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14370">#14370</a>: Fix comment duplication bug in <code>Style/AccessorGrouping</code> separated autocorrect. ([<a href="https://github.com/r7kamura"><code>@​r7kamura</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14377">#14377</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when the assignment is inside a loop body. ([<a href="https://github.com/5hun-s"><code>@​5hun-s</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14355">#14355</a>: Fix a false negative for <code>Style/RedundantParentheses</code> when using parentheses around a <code>rescue</code> expression on a one-line. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14354">#14354</a>: Fix incorrect autocorrect for <code>Style/AccessModifierDeclarations</code> when using a grouped access modifier declaration. ([<a href="https://github.com/girasquid"><code>@​girasquid</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14367">#14367</a>: Fix an incorrect autocorrect for <code>Style/SingleLineMethods</code> when defining a single-line singleton method. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14344">#14344</a>: Fix incorrect autocorrect for <code>Style/SingleLineMethods</code> when a single-line method definition contains a modifier. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14350">#14350</a>: Fix <code>Naming/MethodName</code> cop false positives with <code>define_method</code> and operator names. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14333">#14333</a>: Fix <code>Naming/PredicateMethod</code> ignoring the implicit <code>nil</code> from missing <code>else</code> branches. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14356">#14356</a>: Fix <code>Style/ItBlockParameter</code> cop error on <code>always</code> style and missing block body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14362">#14362</a>: Update <code>Lint/RequireRangeParentheses</code> to not register false positives when range elements span multiple lines. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14309">#14309</a>: Update <code>Style/SoleNestedConditional</code> to properly correct assignments within <code>and</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14358">#14358</a>: Add <code>tsort</code> gem to runtime dependency for Ruby 3.5-dev. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14322">#14322</a>: Expand the scope of <code>Style/ItAssignment</code> to consider all local variable and method parameter names. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14378">#14378</a>: Change <code>Layout/SpaceAroundKeyword</code> to offend for missing whitespace between <code>return</code> and opening parenthesis. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14360">#14360</a>: Make <code>Layout/SpaceAroundOperators</code> aware of alternative and as pattern matchings. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14375">#14375</a>: Make <code>Lint/RedundantSafeNavigation</code> aware of builtin convert methods <code>to_s</code>, <code>to_i</code>, <code>to_f</code>, <code>to_a</code>, and <code>to_h</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13835">#13835</a>: Add <code>InferNonNilReceiver</code> config to <code>Lint/RedundantSafeNavigation</code> to check previous code paths if the receiver is non-nil. ([<a href="https://github.com/fatkodima"><code>@​fatkodima</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14381">#14381</a>: Offend <code>array1.any? { |elem| array2.member?(elem) }</code> and <code>array1.none? { |elem| array2.member?(elem) }</code> in <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.78.0 (2025-07-08)</h2>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/5ecd375e149e1aa4054711ef1d637f2acbfd92ac"><code>5ecd375</code></a> Cut 1.79.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0b19d9215392a34991ecbd11de0bde6e27d13cf8"><code>0b19d92</code></a> Tweak a couple of changelog entries</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/300bc8674d348afbed8fb10c4ea0895ada1453fa"><code>300bc86</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/8e6be288701175d4c4f63f452fe4268e8bc9bc36"><code>8e6be28</code></a> Add support for or nodes to Lint/LiteralAsCondition</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/6adbb279fba7782fac4ada65611930b07eed127b"><code>6adbb27</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14405">#14405</a> from viralpraxis/fix-naming-method-name-cop-spec-de...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/968229405da46c16136f14cc8aa011c09f113a6f"><code>9682294</code></a> Fix <code>Naming/MethodName</code> cop spec descriptions</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/fc0e660eaa2c12513ad2cd8e77dd4f7f5ad52a9e"><code>fc0e660</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14403">#14403</a> from viralpraxis/enhance-naming-method-name-to-hand...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/19f9c0b4e597a7ae28483874d4cd9380bb2934f2"><code>19f9c0b</code></a> Enhance <code>Naming/MethodName</code> cop to detect offenses within <code>alias</code> and `alias_...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9d262b14e3f5f6e2c1922670f36909e4d0002704"><code>9d262b1</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14400">#14400</a> from koic/fix_false_positive_for_layout_empty_lines...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/13c50509aafe9c0a0be9253a4756c6bfb2189575"><code>13c5050</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14399">#14399</a>] Fix false positives for <code>Layout/EmptyLinesAfterModuleInclusion</code></li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.78.0...v1.79.1">compare view</a></li>
  </ul>
  </details>
  <br />

* chore: update rubocop requirement from ~> 1.76.2 to ~> 1.78.0 ([#1595](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1595) [3c31306](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/3c3130616b55e21207802a0180440ffd4a56b497))
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.

* chore: update rubocop requirement from ~> 1.76.2 to ~> 1.78.0 ([#1595](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1595) [3c31306](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/3c3130616b55e21207802a0180440ffd4a56b497))
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.

* chore: update rubocop requirement from ~> 1.76.2 to ~> 1.78.0 ([#1595](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1595) [3c31306](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/3c3130616b55e21207802a0180440ffd4a56b497))
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.

* chore: update rubocop requirement from ~> 1.76.2 to ~> 1.78.0 ([#1595](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1595) [3c31306](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/3c3130616b55e21207802a0180440ffd4a56b497))
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.

* chore: update rubocop requirement from ~> 1.76.2 to ~> 1.78.0 ([#1595](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1595) [3c31306](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/3c3130616b55e21207802a0180440ffd4a56b497))
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.

* chore: update rubocop requirement from ~> 1.75.1 to ~> 1.76.2 ([#1558](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1558) [3981a52](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/3981a52125abffa558d3943456a1af4cffe4607c))
  _when I was able to run the update dependencies script, a newer version of rubocop had already been released_
  
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.76.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. (<a href="https://github.com/ka8725"><code>@​ka8725</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.76.1 (2025-06-09)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. ([<a href="https://github.com/ka8725"><code>@​ka8725</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h2>1.76.0 (2025-06-04)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12360">#12360</a>: Add new <code>Naming/PredicateMethod</code> cop to check that predicate methods end with <code>?</code> and non-predicate methods do not. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13121">#13121</a>: Add new <code>Style/EmptyStringInsideInterpolation</code> cop. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14091">#14091</a>: Add new cop <code>Style/RedundantArrayFlatten</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14184">#14184</a>: Add new cop <code>Lint/UselessOr</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14221">#14221</a>: Enhance <code>Gemspec</code> department cops to detect offenses if specification variable is <code>it</code> or a numbered parameter. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14166">#14166</a>: Add new cop <code>Lint/UselessDefaultValueArgument</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14228">#14228</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when using a one-line <code>rescue</code> expression as a method argument. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14224">#14224</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when using one-line pattern matching. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14205">#14205</a>: False negatives in <code>Style/SafeNavigation</code> when a ternary expression is used in a method argument. ([<a href="https://github.com/steiley"><code>@​steiley</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14226">#14226</a>: Fix <code>Lint/LiteralAsCondition</code> autocorrect when branches of a condition have comments. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14066">#14066</a>: Add <code>EnforcedStyle: allow_single_line</code> as the default to <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13788">#13788</a>: Disable <code>Lint/ShadowingOuterLocalVariable</code> by default. ([<a href="https://github.com/nekketsuuu"><code>@​nekketsuuu</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14215">#14215</a>: Recognize inequation (<code>!=</code>) in <code>Lint/IdentityComparison</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.75.8 (2025-05-28)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14191">#14191</a>: Fix <code>Lint/FloatComparison</code> cop to detect floating-point number comparisons in <code>case</code> statements. ([<a href="https://github.com/daisuke"><code>@​daisuke</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14209">#14209</a>: Fix an error for <code>Style/RedundantFormat</code> with invalid format arguments. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14200">#14200</a>: Fix false positives for <code>Style/DefWithParentheses</code> when using endless method definition with empty parentheses and a space before <code>=</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14197">#14197</a>: Fix infinite loop error for <code>EnforcedStyle: with_fixed_indentation</code> of <code>Layout/ArgumentAlignment</code> and <code>EnforcedStyle: consistent</code> of <code>Layout/FirstArgumentIndentation</code> and <code>Layout/HashAlignment</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14204">#14204</a>: Fix <code>Layout/EmptyLinesAroundAccessModifier</code> cop error on trailing access modifier. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14198">#14198</a>: Fix <code>Lint/DuplicateMethods</code> cop error on <code>to</code> option is dynamically generated and <code>prefix</code> is enabled. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14199">#14199</a>: Fix wrong autocorrection for <code>Style/MapToHash</code> with destructuring argument. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14050">#14050</a>: Modify condition for <code>rubocop:todo</code> EOL comment. ([<a href="https://github.com/jonas054"><code>@​jonas054</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/c74a5b3e838a01e535e3c59b03960a2e273a9b65"><code>c74a5b3</code></a> Cut 1.76.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/c78ad7af9ba2755b5a2471796196bcb64520430e"><code>c78ad7a</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0bd38fff7c79b66356ee1b018be102f71a8d3dd6"><code>0bd38ff</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>] Fix false positives for <code>Style/RedundantArrayFlatten</code></li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bf526269c929a7cf8d26b9d19a5ba8d8a019a2c2"><code>bf52626</code></a> Improve <code>expect_offense</code> interpolation documentation</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/d0dfd683abd1f00ffeebbe61fbb86c446825de16"><code>d0dfd68</code></a> Add new rake task to verify config references availability</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/44f5eb772990ea73dd790fdc3b5f528388b21816"><code>44f5eb7</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14259">#14259</a> from koic/fix_build_error_on_windows_matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/ed880df1855d36e7346a73ad7d8ba3e1c0e85512"><code>ed880df</code></a> Fix build errors on Winsows matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9316b04a691df3244bc148a8cfe6d8d8f21c337c"><code>9316b04</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14244">#14244</a> from koic/fix_false_positives_for_style_redundant_p...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bb32f69c0cc5259db5fc235ba8a48d6257c51d73"><code>bb32f69</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14252">#14252</a> from koic/workaround_ruby_lsp_0_24</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/067da9d3d23c799cae6d8e02111f020cac64ae49"><code>067da9d</code></a> Workaround to avoid build error in Ruby LSP add-on test with Ruby LSP 0.24</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.75.1...v1.76.1">compare view</a></li>
  </ul>
  </details>
  <br />
  
  
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.
  
  [//]: # (dependabot-automerge-start)
  [//]: # (dependabot-automerge-end)
  
  ---
  
  <details>
  <summary>Dependabot commands and options</summary>
  <br />
  
  You can trigger Dependabot actions by commenting on this PR:
  - `@dependabot rebase` will rebase this PR
  - `@dependabot recreate` will recreate this PR, overwriting any edits that have been made to it
  - `@dependabot merge` will merge this PR after your CI passes on it
  - `@dependabot squash and merge` will squash and merge this PR after your CI passes on it
  - `@dependabot cancel merge` will cancel a previously requested merge and block automerging
  - `@dependabot reopen` will reopen this PR if it is closed
  - `@dependabot close` will close this PR and stop Dependabot recreating it. You can achieve the same result by closing it manually
  - `@dependabot show <dependency name> ignore conditions` will show all of the ignore conditions of the specified dependency
  - `@dependabot ignore this major version` will close this PR and stop Dependabot creating any more for this major version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this minor version` will close this PR and stop Dependabot creating any more for this minor version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this dependency` will close this PR and stop Dependabot creating any more for this dependency (unless you reopen the PR or upgrade to it yourself)
  
  
  </details>

* chore: update rubocop requirement from ~> 1.75.1 to ~> 1.76.2 ([#1558](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1558) [3981a52](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/3981a52125abffa558d3943456a1af4cffe4607c))
  _when I was able to run the update dependencies script, a newer version of rubocop had already been released_
  
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.76.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. (<a href="https://github.com/ka8725"><code>@​ka8725</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.76.1 (2025-06-09)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. ([<a href="https://github.com/ka8725"><code>@​ka8725</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h2>1.76.0 (2025-06-04)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12360">#12360</a>: Add new <code>Naming/PredicateMethod</code> cop to check that predicate methods end with <code>?</code> and non-predicate methods do not. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13121">#13121</a>: Add new <code>Style/EmptyStringInsideInterpolation</code> cop. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14091">#14091</a>: Add new cop <code>Style/RedundantArrayFlatten</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14184">#14184</a>: Add new cop <code>Lint/UselessOr</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14221">#14221</a>: Enhance <code>Gemspec</code> department cops to detect offenses if specification variable is <code>it</code> or a numbered parameter. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14166">#14166</a>: Add new cop <code>Lint/UselessDefaultValueArgument</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14228">#14228</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when using a one-line <code>rescue</code> expression as a method argument. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14224">#14224</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when using one-line pattern matching. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14205">#14205</a>: False negatives in <code>Style/SafeNavigation</code> when a ternary expression is used in a method argument. ([<a href="https://github.com/steiley"><code>@​steiley</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14226">#14226</a>: Fix <code>Lint/LiteralAsCondition</code> autocorrect when branches of a condition have comments. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14066">#14066</a>: Add <code>EnforcedStyle: allow_single_line</code> as the default to <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13788">#13788</a>: Disable <code>Lint/ShadowingOuterLocalVariable</code> by default. ([<a href="https://github.com/nekketsuuu"><code>@​nekketsuuu</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14215">#14215</a>: Recognize inequation (<code>!=</code>) in <code>Lint/IdentityComparison</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.75.8 (2025-05-28)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14191">#14191</a>: Fix <code>Lint/FloatComparison</code> cop to detect floating-point number comparisons in <code>case</code> statements. ([<a href="https://github.com/daisuke"><code>@​daisuke</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14209">#14209</a>: Fix an error for <code>Style/RedundantFormat</code> with invalid format arguments. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14200">#14200</a>: Fix false positives for <code>Style/DefWithParentheses</code> when using endless method definition with empty parentheses and a space before <code>=</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14197">#14197</a>: Fix infinite loop error for <code>EnforcedStyle: with_fixed_indentation</code> of <code>Layout/ArgumentAlignment</code> and <code>EnforcedStyle: consistent</code> of <code>Layout/FirstArgumentIndentation</code> and <code>Layout/HashAlignment</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14204">#14204</a>: Fix <code>Layout/EmptyLinesAroundAccessModifier</code> cop error on trailing access modifier. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14198">#14198</a>: Fix <code>Lint/DuplicateMethods</code> cop error on <code>to</code> option is dynamically generated and <code>prefix</code> is enabled. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14199">#14199</a>: Fix wrong autocorrection for <code>Style/MapToHash</code> with destructuring argument. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14050">#14050</a>: Modify condition for <code>rubocop:todo</code> EOL comment. ([<a href="https://github.com/jonas054"><code>@​jonas054</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/c74a5b3e838a01e535e3c59b03960a2e273a9b65"><code>c74a5b3</code></a> Cut 1.76.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/c78ad7af9ba2755b5a2471796196bcb64520430e"><code>c78ad7a</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0bd38fff7c79b66356ee1b018be102f71a8d3dd6"><code>0bd38ff</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>] Fix false positives for <code>Style/RedundantArrayFlatten</code></li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bf526269c929a7cf8d26b9d19a5ba8d8a019a2c2"><code>bf52626</code></a> Improve <code>expect_offense</code> interpolation documentation</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/d0dfd683abd1f00ffeebbe61fbb86c446825de16"><code>d0dfd68</code></a> Add new rake task to verify config references availability</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/44f5eb772990ea73dd790fdc3b5f528388b21816"><code>44f5eb7</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14259">#14259</a> from koic/fix_build_error_on_windows_matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/ed880df1855d36e7346a73ad7d8ba3e1c0e85512"><code>ed880df</code></a> Fix build errors on Winsows matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9316b04a691df3244bc148a8cfe6d8d8f21c337c"><code>9316b04</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14244">#14244</a> from koic/fix_false_positives_for_style_redundant_p...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bb32f69c0cc5259db5fc235ba8a48d6257c51d73"><code>bb32f69</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14252">#14252</a> from koic/workaround_ruby_lsp_0_24</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/067da9d3d23c799cae6d8e02111f020cac64ae49"><code>067da9d</code></a> Workaround to avoid build error in Ruby LSP add-on test with Ruby LSP 0.24</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.75.1...v1.76.1">compare view</a></li>
  </ul>
  </details>
  <br />
  
  
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.
  
  [//]: # (dependabot-automerge-start)
  [//]: # (dependabot-automerge-end)
  
  ---
  
  <details>
  <summary>Dependabot commands and options</summary>
  <br />
  
  You can trigger Dependabot actions by commenting on this PR:
  - `@dependabot rebase` will rebase this PR
  - `@dependabot recreate` will recreate this PR, overwriting any edits that have been made to it
  - `@dependabot merge` will merge this PR after your CI passes on it
  - `@dependabot squash and merge` will squash and merge this PR after your CI passes on it
  - `@dependabot cancel merge` will cancel a previously requested merge and block automerging
  - `@dependabot reopen` will reopen this PR if it is closed
  - `@dependabot close` will close this PR and stop Dependabot recreating it. You can achieve the same result by closing it manually
  - `@dependabot show <dependency name> ignore conditions` will show all of the ignore conditions of the specified dependency
  - `@dependabot ignore this major version` will close this PR and stop Dependabot creating any more for this major version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this minor version` will close this PR and stop Dependabot creating any more for this minor version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this dependency` will close this PR and stop Dependabot creating any more for this dependency (unless you reopen the PR or upgrade to it yourself)
  
  
  </details>

* chore: update rubocop requirement from ~> 1.75.1 to ~> 1.76.2 ([#1558](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1558) [3981a52](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/3981a52125abffa558d3943456a1af4cffe4607c))
  _when I was able to run the update dependencies script, a newer version of rubocop had already been released_
  
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.76.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. (<a href="https://github.com/ka8725"><code>@​ka8725</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.76.1 (2025-06-09)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. ([<a href="https://github.com/ka8725"><code>@​ka8725</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h2>1.76.0 (2025-06-04)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12360">#12360</a>: Add new <code>Naming/PredicateMethod</code> cop to check that predicate methods end with <code>?</code> and non-predicate methods do not. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13121">#13121</a>: Add new <code>Style/EmptyStringInsideInterpolation</code> cop. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14091">#14091</a>: Add new cop <code>Style/RedundantArrayFlatten</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14184">#14184</a>: Add new cop <code>Lint/UselessOr</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14221">#14221</a>: Enhance <code>Gemspec</code> department cops to detect offenses if specification variable is <code>it</code> or a numbered parameter. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14166">#14166</a>: Add new cop <code>Lint/UselessDefaultValueArgument</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14228">#14228</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when using a one-line <code>rescue</code> expression as a method argument. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14224">#14224</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when using one-line pattern matching. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14205">#14205</a>: False negatives in <code>Style/SafeNavigation</code> when a ternary expression is used in a method argument. ([<a href="https://github.com/steiley"><code>@​steiley</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14226">#14226</a>: Fix <code>Lint/LiteralAsCondition</code> autocorrect when branches of a condition have comments. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14066">#14066</a>: Add <code>EnforcedStyle: allow_single_line</code> as the default to <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13788">#13788</a>: Disable <code>Lint/ShadowingOuterLocalVariable</code> by default. ([<a href="https://github.com/nekketsuuu"><code>@​nekketsuuu</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14215">#14215</a>: Recognize inequation (<code>!=</code>) in <code>Lint/IdentityComparison</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.75.8 (2025-05-28)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14191">#14191</a>: Fix <code>Lint/FloatComparison</code> cop to detect floating-point number comparisons in <code>case</code> statements. ([<a href="https://github.com/daisuke"><code>@​daisuke</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14209">#14209</a>: Fix an error for <code>Style/RedundantFormat</code> with invalid format arguments. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14200">#14200</a>: Fix false positives for <code>Style/DefWithParentheses</code> when using endless method definition with empty parentheses and a space before <code>=</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14197">#14197</a>: Fix infinite loop error for <code>EnforcedStyle: with_fixed_indentation</code> of <code>Layout/ArgumentAlignment</code> and <code>EnforcedStyle: consistent</code> of <code>Layout/FirstArgumentIndentation</code> and <code>Layout/HashAlignment</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14204">#14204</a>: Fix <code>Layout/EmptyLinesAroundAccessModifier</code> cop error on trailing access modifier. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14198">#14198</a>: Fix <code>Lint/DuplicateMethods</code> cop error on <code>to</code> option is dynamically generated and <code>prefix</code> is enabled. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14199">#14199</a>: Fix wrong autocorrection for <code>Style/MapToHash</code> with destructuring argument. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14050">#14050</a>: Modify condition for <code>rubocop:todo</code> EOL comment. ([<a href="https://github.com/jonas054"><code>@​jonas054</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/c74a5b3e838a01e535e3c59b03960a2e273a9b65"><code>c74a5b3</code></a> Cut 1.76.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/c78ad7af9ba2755b5a2471796196bcb64520430e"><code>c78ad7a</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0bd38fff7c79b66356ee1b018be102f71a8d3dd6"><code>0bd38ff</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>] Fix false positives for <code>Style/RedundantArrayFlatten</code></li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bf526269c929a7cf8d26b9d19a5ba8d8a019a2c2"><code>bf52626</code></a> Improve <code>expect_offense</code> interpolation documentation</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/d0dfd683abd1f00ffeebbe61fbb86c446825de16"><code>d0dfd68</code></a> Add new rake task to verify config references availability</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/44f5eb772990ea73dd790fdc3b5f528388b21816"><code>44f5eb7</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14259">#14259</a> from koic/fix_build_error_on_windows_matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/ed880df1855d36e7346a73ad7d8ba3e1c0e85512"><code>ed880df</code></a> Fix build errors on Winsows matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9316b04a691df3244bc148a8cfe6d8d8f21c337c"><code>9316b04</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14244">#14244</a> from koic/fix_false_positives_for_style_redundant_p...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bb32f69c0cc5259db5fc235ba8a48d6257c51d73"><code>bb32f69</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14252">#14252</a> from koic/workaround_ruby_lsp_0_24</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/067da9d3d23c799cae6d8e02111f020cac64ae49"><code>067da9d</code></a> Workaround to avoid build error in Ruby LSP add-on test with Ruby LSP 0.24</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.75.1...v1.76.1">compare view</a></li>
  </ul>
  </details>
  <br />
  
  
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.
  
  [//]: # (dependabot-automerge-start)
  [//]: # (dependabot-automerge-end)
  
  ---
  
  <details>
  <summary>Dependabot commands and options</summary>
  <br />
  
  You can trigger Dependabot actions by commenting on this PR:
  - `@dependabot rebase` will rebase this PR
  - `@dependabot recreate` will recreate this PR, overwriting any edits that have been made to it
  - `@dependabot merge` will merge this PR after your CI passes on it
  - `@dependabot squash and merge` will squash and merge this PR after your CI passes on it
  - `@dependabot cancel merge` will cancel a previously requested merge and block automerging
  - `@dependabot reopen` will reopen this PR if it is closed
  - `@dependabot close` will close this PR and stop Dependabot recreating it. You can achieve the same result by closing it manually
  - `@dependabot show <dependency name> ignore conditions` will show all of the ignore conditions of the specified dependency
  - `@dependabot ignore this major version` will close this PR and stop Dependabot creating any more for this major version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this minor version` will close this PR and stop Dependabot creating any more for this minor version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this dependency` will close this PR and stop Dependabot creating any more for this dependency (unless you reopen the PR or upgrade to it yourself)
  
  
  </details>

* chore: update rubocop requirement from ~> 1.75.1 to ~> 1.76.2 ([#1558](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1558) [3981a52](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/3981a52125abffa558d3943456a1af4cffe4607c))
  _when I was able to run the update dependencies script, a newer version of rubocop had already been released_
  
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.76.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. (<a href="https://github.com/ka8725"><code>@​ka8725</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.76.1 (2025-06-09)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. ([<a href="https://github.com/ka8725"><code>@​ka8725</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h2>1.76.0 (2025-06-04)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12360">#12360</a>: Add new <code>Naming/PredicateMethod</code> cop to check that predicate methods end with <code>?</code> and non-predicate methods do not. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13121">#13121</a>: Add new <code>Style/EmptyStringInsideInterpolation</code> cop. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14091">#14091</a>: Add new cop <code>Style/RedundantArrayFlatten</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14184">#14184</a>: Add new cop <code>Lint/UselessOr</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14221">#14221</a>: Enhance <code>Gemspec</code> department cops to detect offenses if specification variable is <code>it</code> or a numbered parameter. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14166">#14166</a>: Add new cop <code>Lint/UselessDefaultValueArgument</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14228">#14228</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when using a one-line <code>rescue</code> expression as a method argument. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14224">#14224</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when using one-line pattern matching. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14205">#14205</a>: False negatives in <code>Style/SafeNavigation</code> when a ternary expression is used in a method argument. ([<a href="https://github.com/steiley"><code>@​steiley</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14226">#14226</a>: Fix <code>Lint/LiteralAsCondition</code> autocorrect when branches of a condition have comments. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14066">#14066</a>: Add <code>EnforcedStyle: allow_single_line</code> as the default to <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13788">#13788</a>: Disable <code>Lint/ShadowingOuterLocalVariable</code> by default. ([<a href="https://github.com/nekketsuuu"><code>@​nekketsuuu</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14215">#14215</a>: Recognize inequation (<code>!=</code>) in <code>Lint/IdentityComparison</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.75.8 (2025-05-28)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14191">#14191</a>: Fix <code>Lint/FloatComparison</code> cop to detect floating-point number comparisons in <code>case</code> statements. ([<a href="https://github.com/daisuke"><code>@​daisuke</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14209">#14209</a>: Fix an error for <code>Style/RedundantFormat</code> with invalid format arguments. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14200">#14200</a>: Fix false positives for <code>Style/DefWithParentheses</code> when using endless method definition with empty parentheses and a space before <code>=</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14197">#14197</a>: Fix infinite loop error for <code>EnforcedStyle: with_fixed_indentation</code> of <code>Layout/ArgumentAlignment</code> and <code>EnforcedStyle: consistent</code> of <code>Layout/FirstArgumentIndentation</code> and <code>Layout/HashAlignment</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14204">#14204</a>: Fix <code>Layout/EmptyLinesAroundAccessModifier</code> cop error on trailing access modifier. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14198">#14198</a>: Fix <code>Lint/DuplicateMethods</code> cop error on <code>to</code> option is dynamically generated and <code>prefix</code> is enabled. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14199">#14199</a>: Fix wrong autocorrection for <code>Style/MapToHash</code> with destructuring argument. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14050">#14050</a>: Modify condition for <code>rubocop:todo</code> EOL comment. ([<a href="https://github.com/jonas054"><code>@​jonas054</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/c74a5b3e838a01e535e3c59b03960a2e273a9b65"><code>c74a5b3</code></a> Cut 1.76.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/c78ad7af9ba2755b5a2471796196bcb64520430e"><code>c78ad7a</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0bd38fff7c79b66356ee1b018be102f71a8d3dd6"><code>0bd38ff</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>] Fix false positives for <code>Style/RedundantArrayFlatten</code></li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bf526269c929a7cf8d26b9d19a5ba8d8a019a2c2"><code>bf52626</code></a> Improve <code>expect_offense</code> interpolation documentation</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/d0dfd683abd1f00ffeebbe61fbb86c446825de16"><code>d0dfd68</code></a> Add new rake task to verify config references availability</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/44f5eb772990ea73dd790fdc3b5f528388b21816"><code>44f5eb7</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14259">#14259</a> from koic/fix_build_error_on_windows_matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/ed880df1855d36e7346a73ad7d8ba3e1c0e85512"><code>ed880df</code></a> Fix build errors on Winsows matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9316b04a691df3244bc148a8cfe6d8d8f21c337c"><code>9316b04</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14244">#14244</a> from koic/fix_false_positives_for_style_redundant_p...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bb32f69c0cc5259db5fc235ba8a48d6257c51d73"><code>bb32f69</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14252">#14252</a> from koic/workaround_ruby_lsp_0_24</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/067da9d3d23c799cae6d8e02111f020cac64ae49"><code>067da9d</code></a> Workaround to avoid build error in Ruby LSP add-on test with Ruby LSP 0.24</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.75.1...v1.76.1">compare view</a></li>
  </ul>
  </details>
  <br />
  
  
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.
  
  [//]: # (dependabot-automerge-start)
  [//]: # (dependabot-automerge-end)
  
  ---
  
  <details>
  <summary>Dependabot commands and options</summary>
  <br />
  
  You can trigger Dependabot actions by commenting on this PR:
  - `@dependabot rebase` will rebase this PR
  - `@dependabot recreate` will recreate this PR, overwriting any edits that have been made to it
  - `@dependabot merge` will merge this PR after your CI passes on it
  - `@dependabot squash and merge` will squash and merge this PR after your CI passes on it
  - `@dependabot cancel merge` will cancel a previously requested merge and block automerging
  - `@dependabot reopen` will reopen this PR if it is closed
  - `@dependabot close` will close this PR and stop Dependabot recreating it. You can achieve the same result by closing it manually
  - `@dependabot show <dependency name> ignore conditions` will show all of the ignore conditions of the specified dependency
  - `@dependabot ignore this major version` will close this PR and stop Dependabot creating any more for this major version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this minor version` will close this PR and stop Dependabot creating any more for this minor version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this dependency` will close this PR and stop Dependabot creating any more for this dependency (unless you reopen the PR or upgrade to it yourself)
  
  
  </details>

* chore: update rubocop requirement from ~> 1.75.1 to ~> 1.76.2 ([#1558](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1558) [3981a52](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/3981a52125abffa558d3943456a1af4cffe4607c))
  _when I was able to run the update dependencies script, a newer version of rubocop had already been released_
  
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.76.1</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. (<a href="https://github.com/ka8725"><code>@​ka8725</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. (<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.76.1 (2025-06-09)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14245">#14245</a>: Fix an error for <code>Lint/EmptyInterpolation</code> when using primitives in interpolation. ([<a href="https://github.com/ka8725"><code>@​ka8725</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14233">#14233</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with index access call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14236">#14236</a>: Fix an error for <code>Style/SafeNavigation</code> when using ternary expression with operator method call. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>: Fix false positives for <code>Style/RedundantArrayFlatten</code> when <code>Array#join</code> is used with an argument other than the default <code>nil</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14239">#14239</a>: Fix false positives for <code>Style/RedundantParentheses</code> when using one-line <code>in</code> pattern matching in operator. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14240">#14240</a>: Fix <code>Naming/PredicateMethod</code> cop error on empty parentheses method body. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14235">#14235</a>: Fix <code>Style/SafeNavigation</code> cop error on indexed assignment in ternary expression. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14247">#14247</a>: Fix <code>Style/SafeNavigation</code> invalid autocorrection on double colon method call. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  </ul>
  <h2>1.76.0 (2025-06-04)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12360">#12360</a>: Add new <code>Naming/PredicateMethod</code> cop to check that predicate methods end with <code>?</code> and non-predicate methods do not. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13121">#13121</a>: Add new <code>Style/EmptyStringInsideInterpolation</code> cop. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14091">#14091</a>: Add new cop <code>Style/RedundantArrayFlatten</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14184">#14184</a>: Add new cop <code>Lint/UselessOr</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14221">#14221</a>: Enhance <code>Gemspec</code> department cops to detect offenses if specification variable is <code>it</code> or a numbered parameter. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14166">#14166</a>: Add new cop <code>Lint/UselessDefaultValueArgument</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14228">#14228</a>: Fix a false positive for <code>Style/RedundantParentheses</code> when using a one-line <code>rescue</code> expression as a method argument. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14224">#14224</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when using one-line pattern matching. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14205">#14205</a>: False negatives in <code>Style/SafeNavigation</code> when a ternary expression is used in a method argument. ([<a href="https://github.com/steiley"><code>@​steiley</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14226">#14226</a>: Fix <code>Lint/LiteralAsCondition</code> autocorrect when branches of a condition have comments. ([<a href="https://github.com/zopolis4"><code>@​zopolis4</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14066">#14066</a>: Add <code>EnforcedStyle: allow_single_line</code> as the default to <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13788">#13788</a>: Disable <code>Lint/ShadowingOuterLocalVariable</code> by default. ([<a href="https://github.com/nekketsuuu"><code>@​nekketsuuu</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14215">#14215</a>: Recognize inequation (<code>!=</code>) in <code>Lint/IdentityComparison</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h2>1.75.8 (2025-05-28)</h2>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14191">#14191</a>: Fix <code>Lint/FloatComparison</code> cop to detect floating-point number comparisons in <code>case</code> statements. ([<a href="https://github.com/daisuke"><code>@​daisuke</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14209">#14209</a>: Fix an error for <code>Style/RedundantFormat</code> with invalid format arguments. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14200">#14200</a>: Fix false positives for <code>Style/DefWithParentheses</code> when using endless method definition with empty parentheses and a space before <code>=</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14197">#14197</a>: Fix infinite loop error for <code>EnforcedStyle: with_fixed_indentation</code> of <code>Layout/ArgumentAlignment</code> and <code>EnforcedStyle: consistent</code> of <code>Layout/FirstArgumentIndentation</code> and <code>Layout/HashAlignment</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14204">#14204</a>: Fix <code>Layout/EmptyLinesAroundAccessModifier</code> cop error on trailing access modifier. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14198">#14198</a>: Fix <code>Lint/DuplicateMethods</code> cop error on <code>to</code> option is dynamically generated and <code>prefix</code> is enabled. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14199">#14199</a>: Fix wrong autocorrection for <code>Style/MapToHash</code> with destructuring argument. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/14050">#14050</a>: Modify condition for <code>rubocop:todo</code> EOL comment. ([<a href="https://github.com/jonas054"><code>@​jonas054</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/c74a5b3e838a01e535e3c59b03960a2e273a9b65"><code>c74a5b3</code></a> Cut 1.76.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/c78ad7af9ba2755b5a2471796196bcb64520430e"><code>c78ad7a</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/0bd38fff7c79b66356ee1b018be102f71a8d3dd6"><code>0bd38ff</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/14249">#14249</a>] Fix false positives for <code>Style/RedundantArrayFlatten</code></li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bf526269c929a7cf8d26b9d19a5ba8d8a019a2c2"><code>bf52626</code></a> Improve <code>expect_offense</code> interpolation documentation</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/d0dfd683abd1f00ffeebbe61fbb86c446825de16"><code>d0dfd68</code></a> Add new rake task to verify config references availability</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/44f5eb772990ea73dd790fdc3b5f528388b21816"><code>44f5eb7</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14259">#14259</a> from koic/fix_build_error_on_windows_matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/ed880df1855d36e7346a73ad7d8ba3e1c0e85512"><code>ed880df</code></a> Fix build errors on Winsows matrix</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9316b04a691df3244bc148a8cfe6d8d8f21c337c"><code>9316b04</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14244">#14244</a> from koic/fix_false_positives_for_style_redundant_p...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/bb32f69c0cc5259db5fc235ba8a48d6257c51d73"><code>bb32f69</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14252">#14252</a> from koic/workaround_ruby_lsp_0_24</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/067da9d3d23c799cae6d8e02111f020cac64ae49"><code>067da9d</code></a> Workaround to avoid build error in Ruby LSP add-on test with Ruby LSP 0.24</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.75.1...v1.76.1">compare view</a></li>
  </ul>
  </details>
  <br />
  
  
  Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.
  
  [//]: # (dependabot-automerge-start)
  [//]: # (dependabot-automerge-end)
  
  ---
  
  <details>
  <summary>Dependabot commands and options</summary>
  <br />
  
  You can trigger Dependabot actions by commenting on this PR:
  - `@dependabot rebase` will rebase this PR
  - `@dependabot recreate` will recreate this PR, overwriting any edits that have been made to it
  - `@dependabot merge` will merge this PR after your CI passes on it
  - `@dependabot squash and merge` will squash and merge this PR after your CI passes on it
  - `@dependabot cancel merge` will cancel a previously requested merge and block automerging
  - `@dependabot reopen` will reopen this PR if it is closed
  - `@dependabot close` will close this PR and stop Dependabot recreating it. You can achieve the same result by closing it manually
  - `@dependabot show <dependency name> ignore conditions` will show all of the ignore conditions of the specified dependency
  - `@dependabot ignore this major version` will close this PR and stop Dependabot creating any more for this major version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this minor version` will close this PR and stop Dependabot creating any more for this minor version (unless you reopen the PR or upgrade to it yourself)
  - `@dependabot ignore this dependency` will close this PR and stop Dependabot creating any more for this dependency (unless you reopen the PR or upgrade to it yourself)
  
  
  </details>

* chore: update rubocop requirement from ~> 1.73.2 to ~> 1.75.1 ([#1461](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1461) [dc076e7](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/dc076e739712f07b70885e0f3ee5cbfc520dcf98))
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.75.1</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.75.1 (2025-03-26)</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  </ul>
  <h2>1.75.0 (2025-03-26)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12049">#12049</a>: Add new <code>Style/HashFetchChain</code> cop to detect chained <code>fetch</code> calls that can be replaced with a single call to <code>dig</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13597">#13597</a>: Add new <code>Style/ItBlockParameter</code> cop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13899">#13899</a>: Enable reusable Prism parse result for Ruby LSP add-on. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14015">#14015</a>: Support <code>it</code> block parameter in <code>Layout</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14017">#14017</a>: Support <code>it</code> block parameter in <code>Lint</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14018">#14018</a>: Support <code>it</code> block parameter in <code>Metrics</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14013">#14013</a>: Support <code>it</code> block parameter in <code>Style</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14025">#14025</a>: Support <code>TargetRubyVersion: 3.5</code> (experimental). ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14022">#14022</a>: Fix an error for <code>Style/HashFetchChain</code> when no arguments are given to <code>fetch</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14028">#14028</a>: Fix false negative for <code>Layout/MultilineMethodParameterLineBreaks</code> when class method definitions are used. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14027">#14027</a>: Fix false negative for <code>Layout/LineLength</code> when autocorrecting class method definitions. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/8099">#8099</a>: Fix infinite loop between <code>Layout/SpaceAroundOperators</code> and <code>Layout/HashAlignment</code> with <code>EnforcedHashRocketStyle</code> being an array containing <code>table</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14021">#14021</a>: Fix handling of long heredoc lines with SplitStrings enabled. ([<a href="https://github.com/mauro-oto"><code>@​mauro-oto</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13968">#13968</a>: Fix <code>InternalAffairs/RedundantDescribedClassAsSubject</code> cop error on missing <code>describe</code>. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14036">#14036</a>: Fix false negative for <code>Lint/ShadowingOuterLocalVariable</code> when block local variable is used inside a condition. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13990">#13990</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when a variable is reassigned in a different branch. ([<a href="https://github.com/eugeneius"><code>@​eugeneius</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14012">#14012</a>: Fix incorrect autocorrections for <code>Style/SoleNestedConditional</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14020">#14020</a>: Fix comment autocorrection for <code>Style/IfInsideElse</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12358">#12358</a>: Add <code>does</code> as a forbidden prefix to <code>Naming/PredicateName</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13621">#13621</a>: Add <code>ForbiddenIdentifiers</code> and <code>ForbiddenPatterns</code> config options to <code>Naming/MethodName</code> cop. ([<a href="https://github.com/tejasbubane"><code>@​tejasbubane</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13986">#13986</a>: Add support for <code>Array#intersection</code> to <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14006">#14006</a>: Allow cop renames to trigger warnings instead of fatal errors. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13617">#13617</a>: Use the <code>prism</code> translation layer to analyze Ruby 3.4+ by default. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14024">#14024</a>: Change <code>Style/RedundantParentheses</code> to offend parentheses for chained <code>&amp;&amp;</code> expressions. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14029">#14029</a>: Add <code>AllowConsecutiveConditionals</code> setting to <code>Style/Next</code> to allow consecutive conditional statements. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14016">#14016</a>: Update <code>Style/RedundantFormat</code> to register offenses when the only argument to <code>format</code> or <code>sprintf</code> is a constant. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h2>1.74.0 (2025-03-13)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13936">#13936</a>: Adds new cop <code>Style/ComparableBetween</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13943">#13943</a>: Allow writing steep annotation to method definition for <code>Style/CommentedKeyword</code>. ([<a href="https://github.com/dak2"><code>@​dak2</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/3872dced1fa9de4a93a31c981e33aadbebf41a7c"><code>3872dce</code></a> Cut 1.75.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/b0999f3767ad9c3eedd770442254261f5bb414d7"><code>b0999f3</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/3ed6febf8adcd9a58e9e1f3084529adc65c94853"><code>3ed6feb</code></a> Rename <code>allow_named_parameter</code> to <code>only_numbered_parameters</code> in `Style/ItBloc...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/784abb29c89953349faafefb6df79ce8bf3f0164"><code>784abb2</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14039">#14039</a> from lovro-bikic/adjust-raise-args-docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/246dee9af40f217c2a400b159ac8c1698040e8cc"><code>246dee9</code></a> Update Style/RaiseArgs docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/cf5e38211cf90ca48afbf375b12c148bd6b008cb"><code>cf5e382</code></a> Reset the docs version</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9c2bc8eb11e269f1cf47113041a1be3ff615f68b"><code>9c2bc8e</code></a> Cut 1.75</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/95ed9879fda27a77a26e72505ce52b7d9ca2fb8f"><code>95ed987</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/f969e0d7369bb04900cb07c97820203f2db8ea29"><code>f969e0d</code></a> Fix handling of long heredoc lines with SplitStrings enabled</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/91fafeb3c06b3a0ea60548662a2cae777e080d3d"><code>91fafeb</code></a> Fix comment autocorrection for Style/IfInsideElse</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.73.2...v1.75.1">compare view</a></li>
  </ul>
  </details>
  <br />

* chore: update rubocop requirement from ~> 1.73.2 to ~> 1.75.1 ([#1461](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1461) [dc076e7](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/dc076e739712f07b70885e0f3ee5cbfc520dcf98))
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.75.1</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.75.1 (2025-03-26)</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  </ul>
  <h2>1.75.0 (2025-03-26)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12049">#12049</a>: Add new <code>Style/HashFetchChain</code> cop to detect chained <code>fetch</code> calls that can be replaced with a single call to <code>dig</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13597">#13597</a>: Add new <code>Style/ItBlockParameter</code> cop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13899">#13899</a>: Enable reusable Prism parse result for Ruby LSP add-on. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14015">#14015</a>: Support <code>it</code> block parameter in <code>Layout</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14017">#14017</a>: Support <code>it</code> block parameter in <code>Lint</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14018">#14018</a>: Support <code>it</code> block parameter in <code>Metrics</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14013">#14013</a>: Support <code>it</code> block parameter in <code>Style</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14025">#14025</a>: Support <code>TargetRubyVersion: 3.5</code> (experimental). ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14022">#14022</a>: Fix an error for <code>Style/HashFetchChain</code> when no arguments are given to <code>fetch</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14028">#14028</a>: Fix false negative for <code>Layout/MultilineMethodParameterLineBreaks</code> when class method definitions are used. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14027">#14027</a>: Fix false negative for <code>Layout/LineLength</code> when autocorrecting class method definitions. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/8099">#8099</a>: Fix infinite loop between <code>Layout/SpaceAroundOperators</code> and <code>Layout/HashAlignment</code> with <code>EnforcedHashRocketStyle</code> being an array containing <code>table</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14021">#14021</a>: Fix handling of long heredoc lines with SplitStrings enabled. ([<a href="https://github.com/mauro-oto"><code>@​mauro-oto</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13968">#13968</a>: Fix <code>InternalAffairs/RedundantDescribedClassAsSubject</code> cop error on missing <code>describe</code>. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14036">#14036</a>: Fix false negative for <code>Lint/ShadowingOuterLocalVariable</code> when block local variable is used inside a condition. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13990">#13990</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when a variable is reassigned in a different branch. ([<a href="https://github.com/eugeneius"><code>@​eugeneius</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14012">#14012</a>: Fix incorrect autocorrections for <code>Style/SoleNestedConditional</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14020">#14020</a>: Fix comment autocorrection for <code>Style/IfInsideElse</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12358">#12358</a>: Add <code>does</code> as a forbidden prefix to <code>Naming/PredicateName</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13621">#13621</a>: Add <code>ForbiddenIdentifiers</code> and <code>ForbiddenPatterns</code> config options to <code>Naming/MethodName</code> cop. ([<a href="https://github.com/tejasbubane"><code>@​tejasbubane</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13986">#13986</a>: Add support for <code>Array#intersection</code> to <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14006">#14006</a>: Allow cop renames to trigger warnings instead of fatal errors. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13617">#13617</a>: Use the <code>prism</code> translation layer to analyze Ruby 3.4+ by default. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14024">#14024</a>: Change <code>Style/RedundantParentheses</code> to offend parentheses for chained <code>&amp;&amp;</code> expressions. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14029">#14029</a>: Add <code>AllowConsecutiveConditionals</code> setting to <code>Style/Next</code> to allow consecutive conditional statements. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14016">#14016</a>: Update <code>Style/RedundantFormat</code> to register offenses when the only argument to <code>format</code> or <code>sprintf</code> is a constant. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h2>1.74.0 (2025-03-13)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13936">#13936</a>: Adds new cop <code>Style/ComparableBetween</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13943">#13943</a>: Allow writing steep annotation to method definition for <code>Style/CommentedKeyword</code>. ([<a href="https://github.com/dak2"><code>@​dak2</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/3872dced1fa9de4a93a31c981e33aadbebf41a7c"><code>3872dce</code></a> Cut 1.75.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/b0999f3767ad9c3eedd770442254261f5bb414d7"><code>b0999f3</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/3ed6febf8adcd9a58e9e1f3084529adc65c94853"><code>3ed6feb</code></a> Rename <code>allow_named_parameter</code> to <code>only_numbered_parameters</code> in `Style/ItBloc...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/784abb29c89953349faafefb6df79ce8bf3f0164"><code>784abb2</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14039">#14039</a> from lovro-bikic/adjust-raise-args-docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/246dee9af40f217c2a400b159ac8c1698040e8cc"><code>246dee9</code></a> Update Style/RaiseArgs docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/cf5e38211cf90ca48afbf375b12c148bd6b008cb"><code>cf5e382</code></a> Reset the docs version</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9c2bc8eb11e269f1cf47113041a1be3ff615f68b"><code>9c2bc8e</code></a> Cut 1.75</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/95ed9879fda27a77a26e72505ce52b7d9ca2fb8f"><code>95ed987</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/f969e0d7369bb04900cb07c97820203f2db8ea29"><code>f969e0d</code></a> Fix handling of long heredoc lines with SplitStrings enabled</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/91fafeb3c06b3a0ea60548662a2cae777e080d3d"><code>91fafeb</code></a> Fix comment autocorrection for Style/IfInsideElse</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.73.2...v1.75.1">compare view</a></li>
  </ul>
  </details>
  <br />

* chore: update rubocop requirement from ~> 1.73.2 to ~> 1.75.1 ([#1461](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1461) [dc076e7](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/dc076e739712f07b70885e0f3ee5cbfc520dcf98))
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.75.1</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.75.1 (2025-03-26)</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  </ul>
  <h2>1.75.0 (2025-03-26)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12049">#12049</a>: Add new <code>Style/HashFetchChain</code> cop to detect chained <code>fetch</code> calls that can be replaced with a single call to <code>dig</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13597">#13597</a>: Add new <code>Style/ItBlockParameter</code> cop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13899">#13899</a>: Enable reusable Prism parse result for Ruby LSP add-on. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14015">#14015</a>: Support <code>it</code> block parameter in <code>Layout</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14017">#14017</a>: Support <code>it</code> block parameter in <code>Lint</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14018">#14018</a>: Support <code>it</code> block parameter in <code>Metrics</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14013">#14013</a>: Support <code>it</code> block parameter in <code>Style</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14025">#14025</a>: Support <code>TargetRubyVersion: 3.5</code> (experimental). ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14022">#14022</a>: Fix an error for <code>Style/HashFetchChain</code> when no arguments are given to <code>fetch</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14028">#14028</a>: Fix false negative for <code>Layout/MultilineMethodParameterLineBreaks</code> when class method definitions are used. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14027">#14027</a>: Fix false negative for <code>Layout/LineLength</code> when autocorrecting class method definitions. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/8099">#8099</a>: Fix infinite loop between <code>Layout/SpaceAroundOperators</code> and <code>Layout/HashAlignment</code> with <code>EnforcedHashRocketStyle</code> being an array containing <code>table</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14021">#14021</a>: Fix handling of long heredoc lines with SplitStrings enabled. ([<a href="https://github.com/mauro-oto"><code>@​mauro-oto</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13968">#13968</a>: Fix <code>InternalAffairs/RedundantDescribedClassAsSubject</code> cop error on missing <code>describe</code>. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14036">#14036</a>: Fix false negative for <code>Lint/ShadowingOuterLocalVariable</code> when block local variable is used inside a condition. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13990">#13990</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when a variable is reassigned in a different branch. ([<a href="https://github.com/eugeneius"><code>@​eugeneius</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14012">#14012</a>: Fix incorrect autocorrections for <code>Style/SoleNestedConditional</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14020">#14020</a>: Fix comment autocorrection for <code>Style/IfInsideElse</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12358">#12358</a>: Add <code>does</code> as a forbidden prefix to <code>Naming/PredicateName</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13621">#13621</a>: Add <code>ForbiddenIdentifiers</code> and <code>ForbiddenPatterns</code> config options to <code>Naming/MethodName</code> cop. ([<a href="https://github.com/tejasbubane"><code>@​tejasbubane</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13986">#13986</a>: Add support for <code>Array#intersection</code> to <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14006">#14006</a>: Allow cop renames to trigger warnings instead of fatal errors. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13617">#13617</a>: Use the <code>prism</code> translation layer to analyze Ruby 3.4+ by default. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14024">#14024</a>: Change <code>Style/RedundantParentheses</code> to offend parentheses for chained <code>&amp;&amp;</code> expressions. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14029">#14029</a>: Add <code>AllowConsecutiveConditionals</code> setting to <code>Style/Next</code> to allow consecutive conditional statements. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14016">#14016</a>: Update <code>Style/RedundantFormat</code> to register offenses when the only argument to <code>format</code> or <code>sprintf</code> is a constant. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h2>1.74.0 (2025-03-13)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13936">#13936</a>: Adds new cop <code>Style/ComparableBetween</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13943">#13943</a>: Allow writing steep annotation to method definition for <code>Style/CommentedKeyword</code>. ([<a href="https://github.com/dak2"><code>@​dak2</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/3872dced1fa9de4a93a31c981e33aadbebf41a7c"><code>3872dce</code></a> Cut 1.75.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/b0999f3767ad9c3eedd770442254261f5bb414d7"><code>b0999f3</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/3ed6febf8adcd9a58e9e1f3084529adc65c94853"><code>3ed6feb</code></a> Rename <code>allow_named_parameter</code> to <code>only_numbered_parameters</code> in `Style/ItBloc...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/784abb29c89953349faafefb6df79ce8bf3f0164"><code>784abb2</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14039">#14039</a> from lovro-bikic/adjust-raise-args-docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/246dee9af40f217c2a400b159ac8c1698040e8cc"><code>246dee9</code></a> Update Style/RaiseArgs docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/cf5e38211cf90ca48afbf375b12c148bd6b008cb"><code>cf5e382</code></a> Reset the docs version</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9c2bc8eb11e269f1cf47113041a1be3ff615f68b"><code>9c2bc8e</code></a> Cut 1.75</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/95ed9879fda27a77a26e72505ce52b7d9ca2fb8f"><code>95ed987</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/f969e0d7369bb04900cb07c97820203f2db8ea29"><code>f969e0d</code></a> Fix handling of long heredoc lines with SplitStrings enabled</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/91fafeb3c06b3a0ea60548662a2cae777e080d3d"><code>91fafeb</code></a> Fix comment autocorrection for Style/IfInsideElse</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.73.2...v1.75.1">compare view</a></li>
  </ul>
  </details>
  <br />

* chore: update rubocop requirement from ~> 1.73.2 to ~> 1.75.1 ([#1461](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1461) [dc076e7](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/dc076e739712f07b70885e0f3ee5cbfc520dcf98))
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.75.1</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.75.1 (2025-03-26)</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  </ul>
  <h2>1.75.0 (2025-03-26)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12049">#12049</a>: Add new <code>Style/HashFetchChain</code> cop to detect chained <code>fetch</code> calls that can be replaced with a single call to <code>dig</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13597">#13597</a>: Add new <code>Style/ItBlockParameter</code> cop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13899">#13899</a>: Enable reusable Prism parse result for Ruby LSP add-on. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14015">#14015</a>: Support <code>it</code> block parameter in <code>Layout</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14017">#14017</a>: Support <code>it</code> block parameter in <code>Lint</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14018">#14018</a>: Support <code>it</code> block parameter in <code>Metrics</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14013">#14013</a>: Support <code>it</code> block parameter in <code>Style</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14025">#14025</a>: Support <code>TargetRubyVersion: 3.5</code> (experimental). ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14022">#14022</a>: Fix an error for <code>Style/HashFetchChain</code> when no arguments are given to <code>fetch</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14028">#14028</a>: Fix false negative for <code>Layout/MultilineMethodParameterLineBreaks</code> when class method definitions are used. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14027">#14027</a>: Fix false negative for <code>Layout/LineLength</code> when autocorrecting class method definitions. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/8099">#8099</a>: Fix infinite loop between <code>Layout/SpaceAroundOperators</code> and <code>Layout/HashAlignment</code> with <code>EnforcedHashRocketStyle</code> being an array containing <code>table</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14021">#14021</a>: Fix handling of long heredoc lines with SplitStrings enabled. ([<a href="https://github.com/mauro-oto"><code>@​mauro-oto</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13968">#13968</a>: Fix <code>InternalAffairs/RedundantDescribedClassAsSubject</code> cop error on missing <code>describe</code>. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14036">#14036</a>: Fix false negative for <code>Lint/ShadowingOuterLocalVariable</code> when block local variable is used inside a condition. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13990">#13990</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when a variable is reassigned in a different branch. ([<a href="https://github.com/eugeneius"><code>@​eugeneius</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14012">#14012</a>: Fix incorrect autocorrections for <code>Style/SoleNestedConditional</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14020">#14020</a>: Fix comment autocorrection for <code>Style/IfInsideElse</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12358">#12358</a>: Add <code>does</code> as a forbidden prefix to <code>Naming/PredicateName</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13621">#13621</a>: Add <code>ForbiddenIdentifiers</code> and <code>ForbiddenPatterns</code> config options to <code>Naming/MethodName</code> cop. ([<a href="https://github.com/tejasbubane"><code>@​tejasbubane</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13986">#13986</a>: Add support for <code>Array#intersection</code> to <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14006">#14006</a>: Allow cop renames to trigger warnings instead of fatal errors. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13617">#13617</a>: Use the <code>prism</code> translation layer to analyze Ruby 3.4+ by default. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14024">#14024</a>: Change <code>Style/RedundantParentheses</code> to offend parentheses for chained <code>&amp;&amp;</code> expressions. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14029">#14029</a>: Add <code>AllowConsecutiveConditionals</code> setting to <code>Style/Next</code> to allow consecutive conditional statements. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14016">#14016</a>: Update <code>Style/RedundantFormat</code> to register offenses when the only argument to <code>format</code> or <code>sprintf</code> is a constant. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h2>1.74.0 (2025-03-13)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13936">#13936</a>: Adds new cop <code>Style/ComparableBetween</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13943">#13943</a>: Allow writing steep annotation to method definition for <code>Style/CommentedKeyword</code>. ([<a href="https://github.com/dak2"><code>@​dak2</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/3872dced1fa9de4a93a31c981e33aadbebf41a7c"><code>3872dce</code></a> Cut 1.75.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/b0999f3767ad9c3eedd770442254261f5bb414d7"><code>b0999f3</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/3ed6febf8adcd9a58e9e1f3084529adc65c94853"><code>3ed6feb</code></a> Rename <code>allow_named_parameter</code> to <code>only_numbered_parameters</code> in `Style/ItBloc...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/784abb29c89953349faafefb6df79ce8bf3f0164"><code>784abb2</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14039">#14039</a> from lovro-bikic/adjust-raise-args-docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/246dee9af40f217c2a400b159ac8c1698040e8cc"><code>246dee9</code></a> Update Style/RaiseArgs docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/cf5e38211cf90ca48afbf375b12c148bd6b008cb"><code>cf5e382</code></a> Reset the docs version</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9c2bc8eb11e269f1cf47113041a1be3ff615f68b"><code>9c2bc8e</code></a> Cut 1.75</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/95ed9879fda27a77a26e72505ce52b7d9ca2fb8f"><code>95ed987</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/f969e0d7369bb04900cb07c97820203f2db8ea29"><code>f969e0d</code></a> Fix handling of long heredoc lines with SplitStrings enabled</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/91fafeb3c06b3a0ea60548662a2cae777e080d3d"><code>91fafeb</code></a> Fix comment autocorrection for Style/IfInsideElse</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.73.2...v1.75.1">compare view</a></li>
  </ul>
  </details>
  <br />

* chore: update rubocop requirement from ~> 1.73.2 to ~> 1.75.1 ([#1461](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1461) [dc076e7](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/dc076e739712f07b70885e0f3ee5cbfc520dcf98))
  Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  <details>
  <summary>Release notes</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  <blockquote>
  <h2>RuboCop v1.75.1</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  </ul>
  </blockquote>
  </details>
  <details>
  <summary>Changelog</summary>
  <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  <blockquote>
  <h2>1.75.1 (2025-03-26)</h2>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14038">#14038</a>: Rename <code>EnforcedStyle: allow_named_parameter</code> to <code>EnforcedStyle: only_numbered_parameters</code> in <code>Style/ItBlockParameter</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  </ul>
  <h2>1.75.0 (2025-03-26)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12049">#12049</a>: Add new <code>Style/HashFetchChain</code> cop to detect chained <code>fetch</code> calls that can be replaced with a single call to <code>dig</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13597">#13597</a>: Add new <code>Style/ItBlockParameter</code> cop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13899">#13899</a>: Enable reusable Prism parse result for Ruby LSP add-on. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14015">#14015</a>: Support <code>it</code> block parameter in <code>Layout</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14017">#14017</a>: Support <code>it</code> block parameter in <code>Lint</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14018">#14018</a>: Support <code>it</code> block parameter in <code>Metrics</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14013">#14013</a>: Support <code>it</code> block parameter in <code>Style</code> cops. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14025">#14025</a>: Support <code>TargetRubyVersion: 3.5</code> (experimental). ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  </ul>
  <h3>Bug fixes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14022">#14022</a>: Fix an error for <code>Style/HashFetchChain</code> when no arguments are given to <code>fetch</code>. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14028">#14028</a>: Fix false negative for <code>Layout/MultilineMethodParameterLineBreaks</code> when class method definitions are used. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14027">#14027</a>: Fix false negative for <code>Layout/LineLength</code> when autocorrecting class method definitions. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/8099">#8099</a>: Fix infinite loop between <code>Layout/SpaceAroundOperators</code> and <code>Layout/HashAlignment</code> with <code>EnforcedHashRocketStyle</code> being an array containing <code>table</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14021">#14021</a>: Fix handling of long heredoc lines with SplitStrings enabled. ([<a href="https://github.com/mauro-oto"><code>@​mauro-oto</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13968">#13968</a>: Fix <code>InternalAffairs/RedundantDescribedClassAsSubject</code> cop error on missing <code>describe</code>. ([<a href="https://github.com/viralpraxis"><code>@​viralpraxis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14036">#14036</a>: Fix false negative for <code>Lint/ShadowingOuterLocalVariable</code> when block local variable is used inside a condition. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13990">#13990</a>: Fix a false positive for <code>Lint/UselessAssignment</code> when a variable is reassigned in a different branch. ([<a href="https://github.com/eugeneius"><code>@​eugeneius</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14012">#14012</a>: Fix incorrect autocorrections for <code>Style/SoleNestedConditional</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14020">#14020</a>: Fix comment autocorrection for <code>Style/IfInsideElse</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  </ul>
  <h3>Changes</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12358">#12358</a>: Add <code>does</code> as a forbidden prefix to <code>Naming/PredicateName</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13621">#13621</a>: Add <code>ForbiddenIdentifiers</code> and <code>ForbiddenPatterns</code> config options to <code>Naming/MethodName</code> cop. ([<a href="https://github.com/tejasbubane"><code>@​tejasbubane</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13986">#13986</a>: Add support for <code>Array#intersection</code> to <code>Style/ArrayIntersect</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14006">#14006</a>: Allow cop renames to trigger warnings instead of fatal errors. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13617">#13617</a>: Use the <code>prism</code> translation layer to analyze Ruby 3.4+ by default. ([<a href="https://github.com/earlopain"><code>@​earlopain</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14024">#14024</a>: Change <code>Style/RedundantParentheses</code> to offend parentheses for chained <code>&amp;&amp;</code> expressions. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14029">#14029</a>: Add <code>AllowConsecutiveConditionals</code> setting to <code>Style/Next</code> to allow consecutive conditional statements. ([<a href="https://github.com/vlad-pisanov"><code>@​vlad-pisanov</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/14016">#14016</a>: Update <code>Style/RedundantFormat</code> to register offenses when the only argument to <code>format</code> or <code>sprintf</code> is a constant. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  </ul>
  <h2>1.74.0 (2025-03-13)</h2>
  <h3>New features</h3>
  <ul>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13936">#13936</a>: Adds new cop <code>Style/ComparableBetween</code>. ([<a href="https://github.com/lovro-bikic"><code>@​lovro-bikic</code></a>][])</li>
  <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13943">#13943</a>: Allow writing steep annotation to method definition for <code>Style/CommentedKeyword</code>. ([<a href="https://github.com/dak2"><code>@​dak2</code></a>][])</li>
  </ul>
  <!-- raw HTML omitted -->
  </blockquote>
  <p>... (truncated)</p>
  </details>
  <details>
  <summary>Commits</summary>
  <ul>
  <li><a href="https://github.com/rubocop/rubocop/commit/3872dced1fa9de4a93a31c981e33aadbebf41a7c"><code>3872dce</code></a> Cut 1.75.1</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/b0999f3767ad9c3eedd770442254261f5bb414d7"><code>b0999f3</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/3ed6febf8adcd9a58e9e1f3084529adc65c94853"><code>3ed6feb</code></a> Rename <code>allow_named_parameter</code> to <code>only_numbered_parameters</code> in `Style/ItBloc...</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/784abb29c89953349faafefb6df79ce8bf3f0164"><code>784abb2</code></a> Merge pull request <a href="https://redirect.github.com/rubocop/rubocop/issues/14039">#14039</a> from lovro-bikic/adjust-raise-args-docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/246dee9af40f217c2a400b159ac8c1698040e8cc"><code>246dee9</code></a> Update Style/RaiseArgs docs</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/cf5e38211cf90ca48afbf375b12c148bd6b008cb"><code>cf5e382</code></a> Reset the docs version</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/9c2bc8eb11e269f1cf47113041a1be3ff615f68b"><code>9c2bc8e</code></a> Cut 1.75</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/95ed9879fda27a77a26e72505ce52b7d9ca2fb8f"><code>95ed987</code></a> Update Changelog</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/f969e0d7369bb04900cb07c97820203f2db8ea29"><code>f969e0d</code></a> Fix handling of long heredoc lines with SplitStrings enabled</li>
  <li><a href="https://github.com/rubocop/rubocop/commit/91fafeb3c06b3a0ea60548662a2cae777e080d3d"><code>91fafeb</code></a> Fix comment autocorrection for Style/IfInsideElse</li>
  <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.73.2...v1.75.1">compare view</a></li>
  </ul>
  </details>
  <br />

* chore: bump rubocop and rubocop-performance gem versions  ([#1445](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1445) [06a295b](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/06a295b1cdc9f705b334e9f3bec67ba2afee300e))
  Replaces the dependabot PRs (#1440, #1441) for these versions to cover all Gemfiles.
  
  rubocop-performance from 1.23.0 to 1.24.0 
  rubocop from 1.72.0 to. 1.73.2

* chore: Enable Gemfile Dev Deps ([#1426](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1426) [5cf6114](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/5cf61145d492e5dfd15d58f1bfd10fb14bbf3f9b))
  > Enforce that development dependencies for a gem are specified in Gemfile, rather than in the gemspec using add_development_dependency. Alternatively, using EnforcedStyle: gemspec, enforce that all dependencies are specified in gemspec, rather than in Gemfile.
  
  https://docs.rubocop.org/rubocop/cops_gemspec.html#gemspecdevelopmentdependencies

* chore: update rubocop to 1.72.2 ([#1429](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1429) [a9592d7](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/a9592d7a4f0cb88e4298e5d41592f75d3eaf9869))
  Two changes related to newfound offenses:
  ```output
  lib/opentelemetry/instrumentation/rack/middlewares/event_handler.rb:120:11: W: Lint/UselessConstantScoping: Useless private access modifier for constant scope.
            EMPTY_HASH = {}.freeze
            ^^^^^^^^^^^^^^^^^^^^^^
  
  lib/opentelemetry/instrumentation/graphql/tracers/graphql_tracer.rb:129:15: W: Lint/CopDirectiveSyntax: Malformed directive comment detected. Cop names must be separated by commas. Comment in the directive must start with --.
                # rubocop:disable Style/SafeNavigation - using safe navigation creates more objects, we want to avoid this
                ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  ```
  
  🤖 Dependabot excerpt on this release: 
  
  > Updates the requirements on [rubocop](https://github.com/rubocop/rubocop) to permit the latest version.
  > <details>
  > <summary>Release notes</summary>
  > <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/releases">rubocop's releases</a>.</em></p>
  > <blockquote>
  > <h2>RuboCop 1.72.2</h2>
  > <h3>Bug fixes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13853">#13853</a>: Fix exclusion of relative paths in plugin's <code>AllCops: Exclude</code> as expected. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13844">#13844</a>: Fix an error for <code>Style/RedundantFormat</code> when a template argument is used without keyword arguments. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13857">#13857</a>: Fix an error for <code>Style/RedundantFormat</code> when numeric placeholders is used in the template argument. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13861">#13861</a>: Fix <code>ArgumentError</code> related to two deprecated <code>AllowedPattern</code> APIs. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13849">#13849</a>: Fix an error for <code>Lint/UselessConstantScoping</code> when multiple assigning to constants after <code>private</code> access modifier. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13856">#13856</a>: Fix false positives for <code>Lint/UselessConstantScoping</code> when a constant is used after <code>private</code> access modifier with arguments. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > </ul>
  > <h3>Changes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13846">#13846</a>: Mark <code>Style/RedundantFormat</code> as unsafe autocorrect. (<a href="https://github.com/koic"><code>@​koic</code></a>)</li>
  > </ul>
  > </blockquote>
  > </details>
  > <details>
  > <summary>Changelog</summary>
  > <p><em>Sourced from <a href="https://github.com/rubocop/rubocop/blob/master/CHANGELOG.md">rubocop's changelog</a>.</em></p>
  > <blockquote>
  > <h2>1.72.2 (2025-02-17)</h2>
  > <h3>Bug fixes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13853">#13853</a>: Fix exclusion of relative paths in plugin's <code>AllCops: Exclude</code> as expected. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13844">#13844</a>: Fix an error for <code>Style/RedundantFormat</code> when a template argument is used without keyword arguments. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13857">#13857</a>: Fix an error for <code>Style/RedundantFormat</code> when numeric placeholders is used in the template argument. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13861">#13861</a>: Fix <code>ArgumentError</code> related to two deprecated <code>AllowedPattern</code> APIs. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13849">#13849</a>: Fix an error for <code>Lint/UselessConstantScoping</code> when multiple assigning to constants after <code>private</code> access modifier. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13856">#13856</a>: Fix false positives for <code>Lint/UselessConstantScoping</code> when a constant is used after <code>private</code> access modifier with arguments. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > </ul>
  > <h3>Changes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13846">#13846</a>: Mark <code>Style/RedundantFormat</code> as unsafe autocorrect. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > </ul>
  > <h2>1.72.1 (2025-02-15)</h2>
  > <h3>Bug fixes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13836">#13836</a>: Fix an error for <code>Style/RedundantParentheses</code> when a different expression appears before a range literal. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13839">#13839</a>: Fix false positives for <code>Lint/RedundantTypeConversion</code> when passing block arguments when generating a Hash or a Set. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > </ul>
  > <h3>Changes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13839">#13839</a>: Extension plugin is loaded automatically with `require 'rubocop/rspec/support'. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > </ul>
  > <h2>1.72.0 (2025-02-14)</h2>
  > <h3>New features</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13740">#13740</a>: Add new <code>Lint/CopDirectiveSyntax</code> cop. ([<a href="https://github.com/kyanagi"><code>@​kyanagi</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13800">#13800</a>: Add new <code>Lint/SuppressedExceptionInNumberConversion</code> cop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13702">#13702</a>: Add new <code>Lint/RedundantTypeConversion</code> cop. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13831">#13831</a>: Add new <code>Lint/UselessConstantScoping</code> cop. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13793">#13793</a>: Add new <code>Style/RedundantFormat</code> cop to check for uses of <code>format</code> or <code>sprintf</code> with only a single string argument. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13581">#13581</a>: Add new <code>InternalAffairs/LocationExists</code> cop to check for code that can be replaced with <code>Node#loc?</code> or <code>Node#loc_is?</code>. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13661">#13661</a>: Make server mode detect local paths in .rubocop.yml under <code>inherit_from</code> and <code>require</code> for automatically restart. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13721">#13721</a>: <code>Naming/PredicateName</code>: Optionally use Sorbet to detect predicate methods. ([<a href="https://github.com/issyl0"><code>@​issyl0</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/6012">#6012</a>: Support RuboCop extension plugin. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > </ul>
  > <h3>Bug fixes</h3>
  > <ul>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13807">#13807</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when chaining <code>[]</code> method calls. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13788">#13788</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when <code>[]</code> method is called with variable or constant receivers. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/13811">#13811</a>: Fix false negatives for <code>Style/RedundantParentheses</code> when handling range literals with redundant parentheses. ([<a href="https://github.com/koic"><code>@​koic</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13796">#13796</a>: Fix crash in <code>Layout/EmptyLinesAroundMethodBody</code> for endless methods. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13817">#13817</a>: Fix false positive for format specifier with non-numeric precision. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12672">#12672</a>: Fix false positives for <code>Lint/FormatParameterMismatch</code> when the width value is interpolated. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/issues/12795">#12795</a>: Fix <code>Layout/BlockAlignment</code> for blocks that are the body of an endless method. ([<a href="https://github.com/dvandersluis"><code>@​dvandersluis</code></a>][])</li>
  > <li><a href="https://redirect.github.com/rubocop/rubocop/pull/13822">#13822</a>: Fix undefined method Logger when processing watched file notifications. ([<a href="https://github.com/vinistock"><code>@​vinistock</code></a>][])</li>
  > </ul>
  > <!-- raw HTML omitted -->
  > </blockquote>
  > <p>... (truncated)</p>
  > </details>
  > <details>
  > <summary>Commits</summary>
  > <ul>
  > <li><a href="https://github.com/rubocop/rubocop/commit/869b5d4e9353e8a167fd92a416767af80e113fe5"><code>869b5d4</code></a> Cut 1.72.2</li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/7c361777d3d8814798a2dbb21bf7ab8c8fee1214"><code>7c36177</code></a> Update Changelog</li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/d4525d6d5bd824c78afd3c05d052ed0054975f22"><code>d4525d6</code></a> Correct Style/RedundantParentheses documentation</li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/7fc05f8b8521dd4d3a7a9b1d089a120d8f1415a5"><code>7fc05f8</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/13861">#13861</a>] Fix <code>ArgumentError</code> related to two deprecated <code>AllowedPattern</code> APIs</li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/aa8c0a97854a5e2249036ffd1514970f98096ba0"><code>aa8c0a9</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/13849">#13849</a>] Fix an error for <code>Lint/UselessConstantScoping</code></li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/241fe6be27a57bb314d9a99b90062ee06fd249af"><code>241fe6b</code></a> Fix an error for <code>Style/RedundantFormat</code></li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/b573711918799d59cc2342336ed7659cbfdc2471"><code>b573711</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/13856">#13856</a>] Fix false positives for <code>Lint/UselessConstantScoping</code></li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/e8119f745fe73f4e8f867b42c07dee3ed060f2ca"><code>e8119f7</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/13844">#13844</a>] Fix an error for <code>Style/RedundantFormat</code></li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/a807f7c38e8de4fa5f378931c50e98e47f89e568"><code>a807f7c</code></a> Fix exclusion of relative paths in plugin's <code>AllCops: Exclude</code> as expected</li>
  > <li><a href="https://github.com/rubocop/rubocop/commit/28c2fe875ff08eb5468d78faffd86db1bf4a71a6"><code>28c2fe8</code></a> [Fix <a href="https://redirect.github.com/rubocop/rubocop/issues/13850">#13850</a>] Fix false negatives for <code>InternalAffairs/ExampleDescription</code></li>
  > <li>Additional commits viewable in <a href="https://github.com/rubocop/rubocop/compare/v1.71.0...v1.72.2">compare view</a></li>
  > </ul>
  > </details>
  > <br />
  > 
  >

* refactor: Define a single ruby required version ([#1388](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1388) [7c04e40](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/7c04e40423fcc01365ca717aa93507d7c4100228))
  I _think_ this will make it easier to enforce the same min Ruby version, as opposed to using a _find and replace_ strategy or a script to bump all the versions.
  
  IDK, wdyt?

* **REFACTOR:** refactor: Define a single ruby required version ([#1388](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1388) [7c04e40](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/7c04e40423fcc01365ca717aa93507d7c4100228))
  I _think_ this will make it easier to enforce the same min Ruby version, as opposed to using a _find and replace_ strategy or a script to bump all the versions.
  
  IDK, wdyt?

* ci: Add Ruby 3.4 build ([#1347](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1347) [1fc6949](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/1fc69498640c8a7d1fc0eb7deba507ba77dc5a5c))

* **TEST:** test: Fix simplecov configuration ([#1366](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1366) [d6568c1](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/d6568c1376735d0c4ee12998f424c9508911eb08))
  Most of the gemspecs here include simplecov, but the majority did not invoke it. Of the ones that _did_ invoke it, none of them did so at the correct place, so the only coverage tracked was generally for the test helper itself. This commit adds a project-wide simplecov configuration file, requires simplecov in the correct place, and ensures results from different appraisals are merged (rather than clobbered).

* test: Fix simplecov configuration ([#1366](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1366) [d6568c1](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/d6568c1376735d0c4ee12998f424c9508911eb08))
  Most of the gemspecs here include simplecov, but the majority did not invoke it. Of the ones that _did_ invoke it, none of them did so at the correct place, so the only coverage tracked was generally for the test helper itself. This commit adds a project-wide simplecov configuration file, requires simplecov in the correct place, and ensures results from different appraisals are merged (rather than clobbered).

* **TEST:** test: Fix simplecov configuration ([#1366](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1366) [d6568c1](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/d6568c1376735d0c4ee12998f424c9508911eb08))
  Most of the gemspecs here include simplecov, but the majority did not invoke it. Of the ones that _did_ invoke it, none of them did so at the correct place, so the only coverage tracked was generally for the test helper itself. This commit adds a project-wide simplecov configuration file, requires simplecov in the correct place, and ensures results from different appraisals are merged (rather than clobbered).

* chore: bump rubocop from 1.70.0 to 1.71.0 ([#1365](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1365) [93895a1](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/93895a1ebf56e751fc6a1b4ec6e9f0aaec96fc12))

* chore: bump rubocop from 1.69.1 to 1.70.0 ([#1344](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1344) [a6ce7a8](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/a6ce7a8c42aa506d7633a52f32d76a6684212284))
  PR to replace the dependabot PRs

* Co-authored-by: release: Release 49 gems ([#1348](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1348) [e6e603e](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/e6e603ef9ad3a210eee331d9f29cc46ab33ec093))
  This pull request prepares new gem releases for the following gems:
  
   *  **opentelemetry-helpers-mysql 0.2.0** (was 0.1.2)
   *  **opentelemetry-helpers-sql-obfuscation 0.3.0** (was 0.2.1)
   *  **opentelemetry-instrumentation-grape 0.3.0** (was 0.2.0)
   *  **opentelemetry-instrumentation-racecar 0.4.0** (was 0.3.4)
   *  **opentelemetry-instrumentation-rake 0.3.0** (was 0.2.2)
   *  **opentelemetry-instrumentation-rdkafka 0.5.0** (was 0.4.9)
   *  **opentelemetry-instrumentation-trilogy 0.61.0** (was 0.60.0)
   *  **opentelemetry-instrumentation-active_support 0.8.0** (was 0.7.0)
   *  **opentelemetry-instrumentation-action_mailer 0.4.0** (was 0.3.0)
   *  **opentelemetry-instrumentation-action_view 0.9.0** (was 0.8.0)
   *  **opentelemetry-instrumentation-action_pack 0.11.0** (was 0.10.0)
   *  **opentelemetry-instrumentation-active_job 0.8.0** (was 0.7.8)
   *  **opentelemetry-instrumentation-resque 0.6.0** (was 0.5.2)
   *  **opentelemetry-instrumentation-bunny 0.22.0** (was 0.21.4)
   *  **opentelemetry-instrumentation-base 0.23.0** (was 0.22.6)
   *  **opentelemetry-instrumentation-active_record 0.9.0** (was 0.8.1)
   *  **opentelemetry-instrumentation-aws_sdk 0.8.0** (was 0.7.0)
   *  **opentelemetry-instrumentation-aws_lambda 0.2.0** (was 0.1.1)
   *  **opentelemetry-instrumentation-lmdb 0.23.0** (was 0.22.3)
   *  **opentelemetry-instrumentation-http 0.24.0** (was 0.23.5)
   *  **opentelemetry-instrumentation-graphql 0.29.0** (was 0.28.4)
   *  **opentelemetry-instrumentation-http_client 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-httpx 0.2.0** (was 0.1.3)
   *  **opentelemetry-instrumentation-koala 0.21.0** (was 0.20.6)
   *  **opentelemetry-instrumentation-active_model_serializers 0.22.0** (was 0.21.1)
   *  **opentelemetry-instrumentation-concurrent_ruby 0.22.0** (was 0.21.4)
   *  **opentelemetry-instrumentation-dalli 0.26.0** (was 0.25.4)
   *  **opentelemetry-instrumentation-delayed_job 0.23.0** (was 0.22.4)
   *  **opentelemetry-instrumentation-ethon 0.22.0** (was 0.21.9)
   *  **opentelemetry-instrumentation-excon 0.23.0** (was 0.22.5)
   *  **opentelemetry-instrumentation-faraday 0.26.0** (was 0.25.0)
   *  **opentelemetry-instrumentation-grpc 0.2.0** (was 0.1.3)
   *  **opentelemetry-instrumentation-gruf 0.3.0** (was 0.2.1)
   *  **opentelemetry-instrumentation-mongo 0.23.0** (was 0.22.4)
   *  **opentelemetry-instrumentation-mysql2 0.29.0** (was 0.28.0)
   *  **opentelemetry-instrumentation-net_http 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-pg 0.30.0** (was 0.29.2)
   *  **opentelemetry-instrumentation-que 0.9.0** (was 0.8.4)
   *  **opentelemetry-instrumentation-rack 0.26.0** (was 0.25.0)
   *  **opentelemetry-instrumentation-rails 0.35.0** (was 0.34.1)
   *  **opentelemetry-instrumentation-redis 0.26.0** (was 0.25.7)
   *  **opentelemetry-instrumentation-restclient 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-rspec 0.4.0** (was 0.3.3)
   *  **opentelemetry-instrumentation-ruby_kafka 0.22.0** (was 0.21.3)
   *  **opentelemetry-instrumentation-sidekiq 0.26.0** (was 0.25.7)
   *  **opentelemetry-instrumentation-sinatra 0.25.0** (was 0.24.1)
   *  **opentelemetry-instrumentation-all 0.72.0** (was 0.71.1)
   *  **opentelemetry-processor-baggage 0.3.0** (was 0.2.1)
   *  **opentelemetry-propagator-ottrace 0.22.0** (was 0.21.4)
   *  **opentelemetry-propagator-vitess 0.2.0** (was 0.1.1)
   *  **opentelemetry-propagator-xray 0.23.0** (was 0.22.3)
   *  **opentelemetry-resource-detector-azure 0.2.0** (was 0.1.1)
   *  **opentelemetry-resource-detector-container 0.2.0** (was 0.1.2)
   *  **opentelemetry-resource-detector-google_cloud_patform 0.2.0** (was 0.1.1)
  
  For each gem, this pull request modifies the gem version and provides an initial changelog entry based on [conventional commit](https://conventionalcommits.org) messages. You can edit these changes before merging, to release a different version or to alter the changelog text.
  
   *  To confirm this release, merge this pull request, ensuring the     "release: pending" label is set. The release     script will trigger automatically on merge.
   *  To abort this release, close this pull request without merging.
  
  The generated changelog entries have been copied below:
  
  ----
  
  ## opentelemetry-helpers-mysql
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-helpers-sql-obfuscation
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-grape
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-racecar
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rake
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rdkafka
  
  ### v0.5.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-trilogy
  
  ### v0.61.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_support
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_mailer
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_view
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_pack
  
  ### v0.11.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_job
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-resque
  
  ### v0.6.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-bunny
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-base
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_record
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-aws_sdk
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-aws_lambda
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-lmdb
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-http
  
  ### v0.24.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-graphql
  
  ### v0.29.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-http_client
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-httpx
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-koala
  
  ### v0.21.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_model_serializers
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-concurrent_ruby
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-dalli
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  * FIXED: Format gat commands
  
  ----
  
  ## opentelemetry-instrumentation-delayed_job
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-ethon
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-excon
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-faraday
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-grpc
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-gruf
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-mongo
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-mysql2
  
  ### v0.29.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-net_http
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-pg
  
  ### v0.30.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-que
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rack
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rails
  
  ### v0.35.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-redis
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-restclient
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rspec
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-ruby_kafka
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-sidekiq
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-sinatra
  
  ### v0.25.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-all
  
  ### v0.72.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-processor-baggage
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-ottrace
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-vitess
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-xray
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-azure
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-container
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-google_cloud_patform
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1

* Co-authored-by: release: Release 49 gems ([#1348](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1348) [e6e603e](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/e6e603ef9ad3a210eee331d9f29cc46ab33ec093))
  This pull request prepares new gem releases for the following gems:
  
   *  **opentelemetry-helpers-mysql 0.2.0** (was 0.1.2)
   *  **opentelemetry-helpers-sql-obfuscation 0.3.0** (was 0.2.1)
   *  **opentelemetry-instrumentation-grape 0.3.0** (was 0.2.0)
   *  **opentelemetry-instrumentation-racecar 0.4.0** (was 0.3.4)
   *  **opentelemetry-instrumentation-rake 0.3.0** (was 0.2.2)
   *  **opentelemetry-instrumentation-rdkafka 0.5.0** (was 0.4.9)
   *  **opentelemetry-instrumentation-trilogy 0.61.0** (was 0.60.0)
   *  **opentelemetry-instrumentation-active_support 0.8.0** (was 0.7.0)
   *  **opentelemetry-instrumentation-action_mailer 0.4.0** (was 0.3.0)
   *  **opentelemetry-instrumentation-action_view 0.9.0** (was 0.8.0)
   *  **opentelemetry-instrumentation-action_pack 0.11.0** (was 0.10.0)
   *  **opentelemetry-instrumentation-active_job 0.8.0** (was 0.7.8)
   *  **opentelemetry-instrumentation-resque 0.6.0** (was 0.5.2)
   *  **opentelemetry-instrumentation-bunny 0.22.0** (was 0.21.4)
   *  **opentelemetry-instrumentation-base 0.23.0** (was 0.22.6)
   *  **opentelemetry-instrumentation-active_record 0.9.0** (was 0.8.1)
   *  **opentelemetry-instrumentation-aws_sdk 0.8.0** (was 0.7.0)
   *  **opentelemetry-instrumentation-aws_lambda 0.2.0** (was 0.1.1)
   *  **opentelemetry-instrumentation-lmdb 0.23.0** (was 0.22.3)
   *  **opentelemetry-instrumentation-http 0.24.0** (was 0.23.5)
   *  **opentelemetry-instrumentation-graphql 0.29.0** (was 0.28.4)
   *  **opentelemetry-instrumentation-http_client 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-httpx 0.2.0** (was 0.1.3)
   *  **opentelemetry-instrumentation-koala 0.21.0** (was 0.20.6)
   *  **opentelemetry-instrumentation-active_model_serializers 0.22.0** (was 0.21.1)
   *  **opentelemetry-instrumentation-concurrent_ruby 0.22.0** (was 0.21.4)
   *  **opentelemetry-instrumentation-dalli 0.26.0** (was 0.25.4)
   *  **opentelemetry-instrumentation-delayed_job 0.23.0** (was 0.22.4)
   *  **opentelemetry-instrumentation-ethon 0.22.0** (was 0.21.9)
   *  **opentelemetry-instrumentation-excon 0.23.0** (was 0.22.5)
   *  **opentelemetry-instrumentation-faraday 0.26.0** (was 0.25.0)
   *  **opentelemetry-instrumentation-grpc 0.2.0** (was 0.1.3)
   *  **opentelemetry-instrumentation-gruf 0.3.0** (was 0.2.1)
   *  **opentelemetry-instrumentation-mongo 0.23.0** (was 0.22.4)
   *  **opentelemetry-instrumentation-mysql2 0.29.0** (was 0.28.0)
   *  **opentelemetry-instrumentation-net_http 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-pg 0.30.0** (was 0.29.2)
   *  **opentelemetry-instrumentation-que 0.9.0** (was 0.8.4)
   *  **opentelemetry-instrumentation-rack 0.26.0** (was 0.25.0)
   *  **opentelemetry-instrumentation-rails 0.35.0** (was 0.34.1)
   *  **opentelemetry-instrumentation-redis 0.26.0** (was 0.25.7)
   *  **opentelemetry-instrumentation-restclient 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-rspec 0.4.0** (was 0.3.3)
   *  **opentelemetry-instrumentation-ruby_kafka 0.22.0** (was 0.21.3)
   *  **opentelemetry-instrumentation-sidekiq 0.26.0** (was 0.25.7)
   *  **opentelemetry-instrumentation-sinatra 0.25.0** (was 0.24.1)
   *  **opentelemetry-instrumentation-all 0.72.0** (was 0.71.1)
   *  **opentelemetry-processor-baggage 0.3.0** (was 0.2.1)
   *  **opentelemetry-propagator-ottrace 0.22.0** (was 0.21.4)
   *  **opentelemetry-propagator-vitess 0.2.0** (was 0.1.1)
   *  **opentelemetry-propagator-xray 0.23.0** (was 0.22.3)
   *  **opentelemetry-resource-detector-azure 0.2.0** (was 0.1.1)
   *  **opentelemetry-resource-detector-container 0.2.0** (was 0.1.2)
   *  **opentelemetry-resource-detector-google_cloud_patform 0.2.0** (was 0.1.1)
  
  For each gem, this pull request modifies the gem version and provides an initial changelog entry based on [conventional commit](https://conventionalcommits.org) messages. You can edit these changes before merging, to release a different version or to alter the changelog text.
  
   *  To confirm this release, merge this pull request, ensuring the     "release: pending" label is set. The release     script will trigger automatically on merge.
   *  To abort this release, close this pull request without merging.
  
  The generated changelog entries have been copied below:
  
  ----
  
  ## opentelemetry-helpers-mysql
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-helpers-sql-obfuscation
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-grape
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-racecar
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rake
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rdkafka
  
  ### v0.5.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-trilogy
  
  ### v0.61.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_support
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_mailer
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_view
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_pack
  
  ### v0.11.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_job
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-resque
  
  ### v0.6.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-bunny
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-base
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_record
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-aws_sdk
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-aws_lambda
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-lmdb
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-http
  
  ### v0.24.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-graphql
  
  ### v0.29.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-http_client
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-httpx
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-koala
  
  ### v0.21.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_model_serializers
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-concurrent_ruby
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-dalli
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  * FIXED: Format gat commands
  
  ----
  
  ## opentelemetry-instrumentation-delayed_job
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-ethon
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-excon
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-faraday
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-grpc
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-gruf
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-mongo
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-mysql2
  
  ### v0.29.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-net_http
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-pg
  
  ### v0.30.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-que
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rack
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rails
  
  ### v0.35.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-redis
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-restclient
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rspec
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-ruby_kafka
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-sidekiq
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-sinatra
  
  ### v0.25.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-all
  
  ### v0.72.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-processor-baggage
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-ottrace
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-vitess
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-xray
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-azure
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-container
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-google_cloud_patform
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1

* release: release: Release 49 gems ([#1348](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1348) [e6e603e](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/e6e603ef9ad3a210eee331d9f29cc46ab33ec093))
  This pull request prepares new gem releases for the following gems:
  
   *  **opentelemetry-helpers-mysql 0.2.0** (was 0.1.2)
   *  **opentelemetry-helpers-sql-obfuscation 0.3.0** (was 0.2.1)
   *  **opentelemetry-instrumentation-grape 0.3.0** (was 0.2.0)
   *  **opentelemetry-instrumentation-racecar 0.4.0** (was 0.3.4)
   *  **opentelemetry-instrumentation-rake 0.3.0** (was 0.2.2)
   *  **opentelemetry-instrumentation-rdkafka 0.5.0** (was 0.4.9)
   *  **opentelemetry-instrumentation-trilogy 0.61.0** (was 0.60.0)
   *  **opentelemetry-instrumentation-active_support 0.8.0** (was 0.7.0)
   *  **opentelemetry-instrumentation-action_mailer 0.4.0** (was 0.3.0)
   *  **opentelemetry-instrumentation-action_view 0.9.0** (was 0.8.0)
   *  **opentelemetry-instrumentation-action_pack 0.11.0** (was 0.10.0)
   *  **opentelemetry-instrumentation-active_job 0.8.0** (was 0.7.8)
   *  **opentelemetry-instrumentation-resque 0.6.0** (was 0.5.2)
   *  **opentelemetry-instrumentation-bunny 0.22.0** (was 0.21.4)
   *  **opentelemetry-instrumentation-base 0.23.0** (was 0.22.6)
   *  **opentelemetry-instrumentation-active_record 0.9.0** (was 0.8.1)
   *  **opentelemetry-instrumentation-aws_sdk 0.8.0** (was 0.7.0)
   *  **opentelemetry-instrumentation-aws_lambda 0.2.0** (was 0.1.1)
   *  **opentelemetry-instrumentation-lmdb 0.23.0** (was 0.22.3)
   *  **opentelemetry-instrumentation-http 0.24.0** (was 0.23.5)
   *  **opentelemetry-instrumentation-graphql 0.29.0** (was 0.28.4)
   *  **opentelemetry-instrumentation-http_client 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-httpx 0.2.0** (was 0.1.3)
   *  **opentelemetry-instrumentation-koala 0.21.0** (was 0.20.6)
   *  **opentelemetry-instrumentation-active_model_serializers 0.22.0** (was 0.21.1)
   *  **opentelemetry-instrumentation-concurrent_ruby 0.22.0** (was 0.21.4)
   *  **opentelemetry-instrumentation-dalli 0.26.0** (was 0.25.4)
   *  **opentelemetry-instrumentation-delayed_job 0.23.0** (was 0.22.4)
   *  **opentelemetry-instrumentation-ethon 0.22.0** (was 0.21.9)
   *  **opentelemetry-instrumentation-excon 0.23.0** (was 0.22.5)
   *  **opentelemetry-instrumentation-faraday 0.26.0** (was 0.25.0)
   *  **opentelemetry-instrumentation-grpc 0.2.0** (was 0.1.3)
   *  **opentelemetry-instrumentation-gruf 0.3.0** (was 0.2.1)
   *  **opentelemetry-instrumentation-mongo 0.23.0** (was 0.22.4)
   *  **opentelemetry-instrumentation-mysql2 0.29.0** (was 0.28.0)
   *  **opentelemetry-instrumentation-net_http 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-pg 0.30.0** (was 0.29.2)
   *  **opentelemetry-instrumentation-que 0.9.0** (was 0.8.4)
   *  **opentelemetry-instrumentation-rack 0.26.0** (was 0.25.0)
   *  **opentelemetry-instrumentation-rails 0.35.0** (was 0.34.1)
   *  **opentelemetry-instrumentation-redis 0.26.0** (was 0.25.7)
   *  **opentelemetry-instrumentation-restclient 0.23.0** (was 0.22.8)
   *  **opentelemetry-instrumentation-rspec 0.4.0** (was 0.3.3)
   *  **opentelemetry-instrumentation-ruby_kafka 0.22.0** (was 0.21.3)
   *  **opentelemetry-instrumentation-sidekiq 0.26.0** (was 0.25.7)
   *  **opentelemetry-instrumentation-sinatra 0.25.0** (was 0.24.1)
   *  **opentelemetry-instrumentation-all 0.72.0** (was 0.71.1)
   *  **opentelemetry-processor-baggage 0.3.0** (was 0.2.1)
   *  **opentelemetry-propagator-ottrace 0.22.0** (was 0.21.4)
   *  **opentelemetry-propagator-vitess 0.2.0** (was 0.1.1)
   *  **opentelemetry-propagator-xray 0.23.0** (was 0.22.3)
   *  **opentelemetry-resource-detector-azure 0.2.0** (was 0.1.1)
   *  **opentelemetry-resource-detector-container 0.2.0** (was 0.1.2)
   *  **opentelemetry-resource-detector-google_cloud_patform 0.2.0** (was 0.1.1)
  
  For each gem, this pull request modifies the gem version and provides an initial changelog entry based on [conventional commit](https://conventionalcommits.org) messages. You can edit these changes before merging, to release a different version or to alter the changelog text.
  
   *  To confirm this release, merge this pull request, ensuring the     "release: pending" label is set. The release     script will trigger automatically on merge.
   *  To abort this release, close this pull request without merging.
  
  The generated changelog entries have been copied below:
  
  ----
  
  ## opentelemetry-helpers-mysql
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-helpers-sql-obfuscation
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-grape
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-racecar
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rake
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rdkafka
  
  ### v0.5.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-trilogy
  
  ### v0.61.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_support
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_mailer
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_view
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-action_pack
  
  ### v0.11.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_job
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-resque
  
  ### v0.6.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-bunny
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-base
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_record
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-aws_sdk
  
  ### v0.8.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-aws_lambda
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-lmdb
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-http
  
  ### v0.24.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-graphql
  
  ### v0.29.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-http_client
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-httpx
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-koala
  
  ### v0.21.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-active_model_serializers
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-concurrent_ruby
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-dalli
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  * FIXED: Format gat commands
  
  ----
  
  ## opentelemetry-instrumentation-delayed_job
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-ethon
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-excon
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-faraday
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-grpc
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-gruf
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-mongo
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-mysql2
  
  ### v0.29.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-net_http
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-pg
  
  ### v0.30.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-que
  
  ### v0.9.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rack
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rails
  
  ### v0.35.0 / 2025-01-16
  
  * BREAKING CHANGE: Drop Support for EoL Rails 6.1
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Drop Support for EoL Rails 6.1
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-redis
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-restclient
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-rspec
  
  ### v0.4.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-ruby_kafka
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-sidekiq
  
  ### v0.26.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-sinatra
  
  ### v0.25.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-instrumentation-all
  
  ### v0.72.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-processor-baggage
  
  ### v0.3.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-ottrace
  
  ### v0.22.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-vitess
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-propagator-xray
  
  ### v0.23.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-azure
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-container
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1
  
  ----
  
  ## opentelemetry-resource-detector-google_cloud_patform
  
  ### v0.2.0 / 2025-01-16
  
  * BREAKING CHANGE: Set minimum supported version to Ruby 3.1
  
  * ADDED: Set minimum supported version to Ruby 3.1


### v0.2.0 / 2025-01-16

* BREAKING CHANGE: Set minimum supported version to Ruby 3.1

* ADDED: Set minimum supported version to Ruby 3.1

### v0.1.1 / 2024-11-26

* (No significant changes)

### v0.1.0 / 2024-02-08

Initial release.
