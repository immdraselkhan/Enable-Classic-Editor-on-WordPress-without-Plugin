You can disable the Gutenberg Editor with code. Simply add the following to your functions.php file.

add_filter('use_block_editor_for_post', '__return_false', 10);
