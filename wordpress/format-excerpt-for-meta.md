The following snippet grabs the excerpt from the current post in the loop, and removes all tags. It does not include the "read more" link, or apply any filters. It's appropriate for using in `meta` tags, such as for SEO or Twitter Cards.

`<?php echo wp_strip_all_tags( get_the_excerpt(), true ); ?>`
