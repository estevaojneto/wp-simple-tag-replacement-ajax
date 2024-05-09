# WordPress plugin: Simple Tag Replacement via AJAX

Very simple plugin which adds an AJAX endpoint to WordPress allowing you to mass-replace tags for all posts given a certain post type.

## Usage
- Install & enable the plugin;
- As a logged in user, visit the following URL in your website:
```
{yourwebsite}/admin-ajax.php?action=wp_ajax_replace_tag&find={BAD_TAG_ID}&replace={GOOD_TAG_ID}&post_type={POST_TYPE}
```
...doing the proper replacements, of course.
- As usual, do a test run in a safe environment (Staging or local environment) before using it in Production. I take no responsibility for any unwanted results you may encounter from using this plugin.
