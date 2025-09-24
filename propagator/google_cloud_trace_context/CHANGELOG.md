# Release History: opentelemetry-propagator-google_cloud_trace_context

# 1.0.0 (2025-09-24)

## Release Summary

This release includes the following pull requests:

* [#1408](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1408) - feat: added google_cloud_trace_context propagator
  The `X-Cloud-Trace-Context` header that is used by Google Cloud predates the W3C specification. For backwards compatibility, some Google Cloud services continue to accept, generate, and propagate the `X-Cloud-Trace-Context` header. However, it is likely that these systems also support the traceparent header.
  
  The `X-Cloud-Trace-Context` header has the following format:
  
  ```
  X-Cloud-Trace-Context: TRACE_ID/SPAN_ID;o=OPTIONS
  ```
  
  The fields of header are defined as follows:
  
  - `TRACE_ID` is a 32-character hexadecimal value representing a 128-bit number.
  - `SPAN_ID` is a 64-bit decimal representation of the unsigned span ID.
  - `OPTIONS` supports 0 (parent not sampled) and 1 (parent was sampled).

* [#1517](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1517) - release: Release opentelemetry-propagator-google_cloud_trace_context 0.1.0 (initial release)
  *  **opentelemetry-propagator-google_cloud_trace_context 0.1.0** (initial release)

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

* feat: added google_cloud_trace_context propagator ([#1408](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1408) [266a8ba](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/266a8baa00dd05b7915a4840b95480cc4c22feaa))
  The `X-Cloud-Trace-Context` header that is used by Google Cloud predates the W3C specification. For backwards compatibility, some Google Cloud services continue to accept, generate, and propagate the `X-Cloud-Trace-Context` header. However, it is likely that these systems also support the traceparent header.
  
  The `X-Cloud-Trace-Context` header has the following format:
  
  ```
  X-Cloud-Trace-Context: TRACE_ID/SPAN_ID;o=OPTIONS
  ```
  
  The fields of header are defined as follows:
  
  - `TRACE_ID` is a 32-character hexadecimal value representing a 128-bit number.
  - `SPAN_ID` is a 64-bit decimal representation of the unsigned span ID.
  - `OPTIONS` supports 0 (parent not sampled) and 1 (parent was sampled).

* feat: added google_cloud_trace_context propagator ([#1408](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1408) [266a8ba](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/266a8baa00dd05b7915a4840b95480cc4c22feaa))
  The `X-Cloud-Trace-Context` header that is used by Google Cloud predates the W3C specification. For backwards compatibility, some Google Cloud services continue to accept, generate, and propagate the `X-Cloud-Trace-Context` header. However, it is likely that these systems also support the traceparent header.
  
  The `X-Cloud-Trace-Context` header has the following format:
  
  ```
  X-Cloud-Trace-Context: TRACE_ID/SPAN_ID;o=OPTIONS
  ```
  
  The fields of header are defined as follows:
  
  - `TRACE_ID` is a 32-character hexadecimal value representing a 128-bit number.
  - `SPAN_ID` is a 64-bit decimal representation of the unsigned span ID.
  - `OPTIONS` supports 0 (parent not sampled) and 1 (parent was sampled).

* **NEW:** feat: added google_cloud_trace_context propagator ([#1408](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1408) [266a8ba](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/266a8baa00dd05b7915a4840b95480cc4c22feaa))
  The `X-Cloud-Trace-Context` header that is used by Google Cloud predates the W3C specification. For backwards compatibility, some Google Cloud services continue to accept, generate, and propagate the `X-Cloud-Trace-Context` header. However, it is likely that these systems also support the traceparent header.
  
  The `X-Cloud-Trace-Context` header has the following format:
  
  ```
  X-Cloud-Trace-Context: TRACE_ID/SPAN_ID;o=OPTIONS
  ```
  
  The fields of header are defined as follows:
  
  - `TRACE_ID` is a 32-character hexadecimal value representing a 128-bit number.
  - `SPAN_ID` is a 64-bit decimal representation of the unsigned span ID.
  - `OPTIONS` supports 0 (parent not sampled) and 1 (parent was sampled).

### Propagator: GOOGLE_CLOUD_TRACE_CONTEXT

* Co-authored-by: release: Release opentelemetry-propagator-google_cloud_trace_context 0.1.0 (initial release) ([#1517](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1517) [fb84ce0](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/fb84ce03c000e1901366dd45014b362a1f95db8e))
  *  **opentelemetry-propagator-google_cloud_trace_context 0.1.0** (initial release)

* Co-authored-by: release: Release opentelemetry-propagator-google_cloud_trace_context 0.1.0 (initial release) ([#1517](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1517) [fb84ce0](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/fb84ce03c000e1901366dd45014b362a1f95db8e))
  *  **opentelemetry-propagator-google_cloud_trace_context 0.1.0** (initial release)

* release: release: Release opentelemetry-propagator-google_cloud_trace_context 0.1.0 (initial release) ([#1517](https://github.com/open-telemetry/opentelemetry-ruby-contrib/pull/1517) [fb84ce0](https://github.com/open-telemetry/opentelemetry-ruby-contrib/commit/fb84ce03c000e1901366dd45014b362a1f95db8e))
  *  **opentelemetry-propagator-google_cloud_trace_context 0.1.0** (initial release)


### v0.1.0 / 2025-05-01

Initial release.
