# assignment2-karumuri
# karumuripavani
###### volleyball
I like volleyball because it is **sportive** game and it also gives me a lot of **physical exercise**. From childhood onwards I play this game very well and I hope so I will it in **future**.

---

## Lucknow Super Gaints

1. KL Rahul
2. Virat Kohli
3. ABD

## Other Team that I like

* Chennai Super Kings
* Punjab Super Kings
* Dehli Captials

[AboutMe_Link](AboutMe.md)

---
It aids in your understanding of the people's customs, traditions, and way of life in those countries. You are able to see everything from a larger range of perspectives.

### The places to visit as a tourist:

|  *Name of Country*  | *Why to visit* | *days to visit*|
| :------------ | :------------: | :------------: |
| 1. Japan    | To dine at local restaurants   | 45 |
| 2. India          | To visit Taj Mahal   | 60 |
| 3. UK        | To visit Tower of London   | 86 |
| 4. Russia         |  To look at the wonderful structure of Saint Petersburg | 45 |

---

### Funny Quotes

> *“People say nothing is impossible, but I do nothing every day.”* *~ A. A. Milne*

> *“People kept saying ‘Go Corona’ and it went to other countries to spread across the globe.”* *~ Invajy*

### Code Fencing

Stackoverflow link : <https://stackoverflow.com/questions/54157688/how-to-stop-jetpack-from-loading-css-files-from-wp-com>

```

// First, make sure Jetpack doesn't concatenate all its CSS
add_filter( 'jetpack_implode_frontend_css', '__return_false' );

// Then, remove each CSS file, one at a time
function jeherve_remove_all_jp_css() {
  wp_deregister_style( 'AtD_style' ); // After the Deadline
  wp_deregister_style( 'jetpack_likes' ); // Likes
  wp_deregister_style( 'jetpack_related-posts' ); //Related Posts
  wp_deregister_style( 'jetpack-carousel' ); // Carousel
  wp_deregister_style( 'grunion.css' ); // Grunion contact form
  wp_deregister_style( 'the-neverending-homepage' ); // Infinite Scroll
  wp_deregister_style( 'infinity-twentyten' ); // Infinite Scroll - Twentyten Theme
  wp_deregister_style( 'infinity-twentyeleven' ); // Infinite Scroll - Twentyeleven Theme
  wp_deregister_style( 'infinity-twentytwelve' ); // Infinite Scroll - Twentytwelve Theme
  wp_deregister_style( 'noticons' ); // Notes
  wp_deregister_style( 'post-by-email' ); // Post by Email
  wp_deregister_style( 'publicize' ); // Publicize
  wp_deregister_style( 'sharedaddy' ); // Sharedaddy
  wp_deregister_style( 'sharing' ); // Sharedaddy Sharing
  wp_deregister_style( 'stats_reports_css' ); // Stats
  wp_deregister_style( 'jetpack-widgets' ); // Widgets
  wp_deregister_style( 'jetpack-slideshow' ); // Slideshows
  wp_deregister_style( 'presentations' ); // Presentation shortcode
  wp_deregister_style( 'jetpack-subscriptions' ); // Subscriptions
  wp_deregister_style( 'tiled-gallery' ); // Tiled Galleries
  wp_deregister_style( 'widget-conditions' ); // Widget Visibility
  wp_deregister_style( 'jetpack_display_posts_widget' ); // Display Posts Widget
  wp_deregister_style( 'gravatar-profile-widget' ); // Gravatar Widget
  wp_deregister_style( 'widget-grid-and-list' ); // Top Posts widget
  wp_deregister_style( 'jetpack-widgets' ); // Widgets
}
add_action('wp_print_styles', 'jeherve_remove_all_jp_css' );

```

Snippet Source: <https://css-tricks.com/snippets/wordpress/get-featured-image-url/>
