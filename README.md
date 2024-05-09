# WordPress plugin: Simple Tag Replacement via AJAX

Very simple plugin which adds an AJAX endpoint to WordPress allowing you to mass-replace tags for all posts given a certain post type.

## Usage
- Install & enable the plugin;
- As a logged in user, visit the following URL in your website: {yourwebsite.com}/admin-ajax.php?action=wp_ajax_replace_tag&find={BAD_TAG_ID}&replace={GOOD_TAG_ID}&post_type={POST_TYPE}
