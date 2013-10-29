List of (mostly trivial) drupal issues that affect production environments but are blocked by drupal 8 development and drupal's backport policy.

<table>
<tr><th>Issue</th><th>Drupal</th><th>Backdrop</th></tr>
<tr><td>Watchdog logging of all searches is performance hit</td><td>https://drupal.org/node/733054</td><td>https://github.com/backdrop/backdrop-issues/issues/62</td></tr>
<tr><td>drupal_valid_path fails for dynamic paths (e.g. user/% cannot be added to menus)</td><td>https://drupal.org/node/876580</td><td></td></tr>
<tr><td>Maintenance mode should neither create nor retrieve cache</td><td>https://drupal.org/node/1032936</td><td>https://github.com/backdrop/backdrop-issues/issues/85</td></tr>
<tr><td>Charset definition missing in XML-RPC</td><td>https://drupal.org/node/1774618</td><td>https://github.com/backdrop/backdrop-issues/issues/60</td></tr>
<tr><td>Missing langcode in $context in hook_field_attach_view_alter()</td><td>https://drupal.org/node/1823306</td><td></td></tr>
<tr><td>EntityFieldQuery::$orderedResults is always empty</td><td>https://drupal.org/node/2033883</td><td>https://github.com/backdrop/backdrop-issues/issues/64</td></tr>
</table>

to be continued ...
