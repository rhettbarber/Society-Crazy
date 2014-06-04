Society-Crazy - A jQuery social plugin for sharing to multiple social networks
================

Tired of social sharing plugins that make you share to each social network separately? Then you'll love this easy-to-use jQuery social media plug-in.
Society-Crazy is a plug-in that lets everyone share your content to multiple social networks from one place.
Use Share to post updates, content or screenshots to Facebook, Twitter, Pinterest, Digg, Google+, LinkedIn, Tumblr or email.

Features
================

    - Share updates from multiple social networks from a single form
    - Supports Facebook, Twitter, LinkedIn, Tumblr
    - Attractive buttons and multiple themes
    - Easy to implement with just a few lines of code
    
    
Example initialization
================
    $('#share_product').share({
        networks: ['twitter','facebook','tumblr','pinterest','googleplus','email'],
        title : 'Check this out!',
        pictureUrl :  'http://placekitten.com/200/300',
        pageDesc: 'description_to_share' ,
        orientation: 'vertical',
        urlToShare:  'http://example.com',
        redirectUri:  'http://example.com/close_window',
        appId: 'YOUR_APP_ID' ,
        affix: 'right center'
    })
