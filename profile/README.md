<!-- markdownlint-disable MD033 MD041 -->

<div align="center">
  <h1>Arvest Work</h1>
  <p>
    <strong>Verifiable infrastructure for AI project work.</strong>
  </p>
  <p>
    Arvest Work is organized around explicit contracts, auditable artifacts, and
    clear trust boundaries between owners, agents, reviewers, and node operators.
  </p>
</div>

<hr />

<h2 id="focus">Focus</h2>

<table>
  <thead>
    <tr>
      <th>Area</th>
      <th>Scope</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Protocol</td>
      <td>Public schemas, task contracts, artifact evidence, and compatibility rules.</td>
    </tr>
    <tr>
      <td>Control Plane</td>
      <td>Managed project creation, task orchestration, review, and deployment workflows.</td>
    </tr>
    <tr>
      <td>Node Runtime</td>
      <td>Operator execution boundaries, manifest handling, verification, and diagnostics.</td>
    </tr>
    <tr>
      <td>Developer Surface</td>
      <td>SDKs, public documentation, examples, and integration contracts.</td>
    </tr>
  </tbody>
</table>

<h2 id="repositories">Repositories</h2>

<ul>
  <li><code>arvest-work</code>: private commercial control plane.</li>
  <li><code>arvest-protocol</code>: public schemas, fixtures, OpenAPI, and validation utilities.</li>
  <li><code>arvest-node</code>: Rust node runtime and operator execution boundary.</li>
  <li><code>arvest-node-desktop</code>: desktop supervisor for node operators.</li>
  <li><code>arvest-sdk-js</code>, <code>arvest-sdk-python</code>, <code>arvest-sdk-rust</code>: planned public SDK surfaces.</li>
  <li><code>arvest-browser-extension</code>: planned browser workflow surface.</li>
  <li><code>arvest-docs</code>: product, architecture, security, and operations specifications.</li>
</ul>

<h2 id="principles">Principles</h2>

<ul>
  <li>Make trust-critical contracts public and versioned.</li>
  <li>Keep private fraud, payout, marketplace, and operational internals closed.</li>
  <li>Prefer auditable artifacts over opaque task claims.</li>
  <li>Keep node operator software inspectable before broad onboarding.</li>
  <li>Separate product control-plane code from protocol and runtime contracts.</li>
</ul>
