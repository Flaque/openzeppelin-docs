---
id: version-2.0.0-rc.2-utils_ReentrancyGuard
title: ReentrancyGuard
original_id: utils_ReentrancyGuard
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> ReentrancyGuard</h2><p class="description">If you mark a function `nonReentrant`, you should also mark it `external`.</p><div class="source">Source: <a href="https://github.com/OpenZeppelin/zeppelin-solidity/blob/v2.0.0-rc.2/contracts/utils/ReentrancyGuard.sol" target="_blank">utils/ReentrancyGuard.sol</a></div><div class="author">Author: Remco Bloemen &lt;remco@2π.com&gt;, Eenae &lt;alexey@mixbytes.io&gt;</div></div><div class="index"><h2>Index</h2><ul><li><a href="utils_ReentrancyGuard.html#nonReentrant">nonReentrant</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="modifiers"><h3>Modifiers</h3><ul><li><div class="item modifier"><span id="nonReentrant" class="anchor-marker"></span><h4 class="name">nonReentrant</h4><div class="body"><code class="signature">modifier <strong>nonReentrant</strong><span>() </span></code><hr/><div class="description"><p>Prevents a contract from calling itself, directly or indirectly. If you mark a function `nonReentrant`, you should also mark it `external`. Calling one `nonReentrant` function from another is not supported. Instead, you can implement a `private` function doing the actual work, and an `external` wrapper marked as `nonReentrant`.</p></div></div></div></li></ul></div></div></div>