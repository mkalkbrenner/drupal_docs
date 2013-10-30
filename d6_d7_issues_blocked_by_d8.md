List of (mostly trivial) drupal issues that affect production environments but existing patches are blocked by drupal 8 development and drupal's backport policy.

<table>
<tr><th>Issue</th><th>Drupal</th><th>Backdrop</th></tr>
<tr><td>Watchdog logging of all searches is performance hit</td><td>https://drupal.org/node/733054</td><td>https://github.com/backdrop/backdrop-issues/issues/62</td></tr>
<tr><td>drupal_valid_path fails for dynamic paths (e.g. user/% cannot be added to menus)</td><td>https://drupal.org/node/876580</td><td></td></tr>
<tr><td>Maintenance mode should neither create nor retrieve cache</td><td>https://drupal.org/node/1032936</td><td>https://github.com/backdrop/backdrop-issues/issues/85</td></tr>
<tr><td>Charset definition missing in XML-RPC</td><td>https://drupal.org/node/1774618</td><td>https://github.com/backdrop/backdrop-issues/issues/60</td></tr>
<tr><td>Missing langcode in $context in hook_field_attach_view_alter()</td><td>https://drupal.org/node/1823306</td><td></td></tr>
<tr><td>EntityFieldQuery::$orderedResults is always empty</td><td>https://drupal.org/node/2033883</td><td>https://github.com/backdrop/backdrop-issues/issues/64</td></tr>
<tr><td>Add select event to autocomplete feature</td><td>https://drupal.org/node/365241</td><td></td></tr>
<tr><td>Bootstrap issue with theme initialization.</td><td>https://drupal.org/node/2086335</td><td></td></tr>
<tr><td>theme inheritance seems to crash if theme is selected by hook_custom_theme and "engine" is missing in theme.info file</td><td>https://drupal.org/node/1916188</td><td></td></tr>
<tr><td>Ensure that entries are written to watchdog table</td><td>https://drupal.org/node/298768</td><td>https://github.com/backdrop/backdrop-issues/issues/63</td></tr>
<tr><td>dblog fails to log MAX_ALLOWED_PACKET errors because they're longer than MAX_ALLOWED_PACKET</td><td>https://drupal.org/node/972528</td><td></td></tr>
<tr><td>form_set_error() flags ALL form elements with the same name on a page</td><td>https://drupal.org/node/119208</td><td></td></tr>
<tr><td>drupal_http_request() fails</td><td>https://drupal.org/node/617126</td><td></td></tr>
<tr><td>node_view() incompatible to php5</td><td>https://drupal.org/node/229411</td><td></td></tr>
</table>

to be continued ...
