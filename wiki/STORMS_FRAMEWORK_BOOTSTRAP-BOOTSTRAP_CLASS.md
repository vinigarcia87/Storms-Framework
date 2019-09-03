- Bootstrap/Bootstrap Class
	- If load_sf_bootstrap is true, register and enqueue Bootstrap scripts
	- If load_select2-bootstrap is true, enqueue Bootstrap customization for Select2 dropdown
	- If load_sf_bootstrap is true, register and enqueue Bootstrap styles
	- Add bootstrap's img-responsive class to images on the_content, post_thumbnail_html, image_send_to_editor, woocommerce_single_product_image_thumbnail_html, wp_get_attachment_image_attributes
	- Bootstrap layout for post's password form
	- Change the default gallery for an bootstrap custom gallery - It depends on Bootstrap scripts [CHECK THIS! We already have a custom gallery, we don't need a new one... to be honest, this can be resolved with a 3rd-party plugin]
	- Customize the calendar widget with Boostrap style
	- Customize comment_reply_link as an Bootstrap button
	- Customize avatar image with Boostrap style
	- Cleaner Gallery Customization [REMOVE THIS! This is not applicable]
	- Customize comments form with Bootstrap style
	- Customize badges, like the count in categories widget, with Bootstrap style
	- Customize search form with Boostrap style, using a custom template in /template-parts/searchform.php
	- Function 'comments_loop' [REMOVE THIS! We use Bootstrap/CommentWalker instead. Find where this is used and remove it]
	- Bootstrap/CommentWalker: Customize the comment loop
	- Bootstrap/Breadcrumb: Customize the breadcrumbs, extending the Breadcrumb_Trail
	- Bootstrap/NavWalker: Customize the menu
	- Bootstrap/Pagination: Customize the paginator

	- Storms options defined on this class:
		- load_sf_bootstrap: false
		- load_select2-bootstrap: false
		- add_extra_calsses_to_img: true
		- add_classes_to_images: array('img-responsive')