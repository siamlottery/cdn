<?php
function replace_jquery() {
		wp_deregister_script('jquery');
		wp_register_script('jquery', 'https://cdnjs.cloudflare.com/ajax/libs/jquery/1.12.4/jquery.min.js', false, '1.12.4');
		wp_enqueue_script('jquery');
		wp_deregister_script( 'jquery-migrate' );
        wp_register_script( 'jquery-migrate', "https://cdnjs.cloudflare.com/ajax/libs/jquery-migrate/1.4.1/jquery-migrate.min.js", array(), '1.4.1' );
		wp_enqueue_script('jquery-migrate');
		wp_deregister_script( 'wp-embed' );
        wp_register_script( 'wp-embed', "https://raw.githubusercontent.com/WordPress/WordPress/master/wp-includes/js/wp-embed.min.js", array(), '4.9.8' );
		wp_enqueue_script('wp-embed');
}
add_action('wp_footer', 'replace_jquery');
