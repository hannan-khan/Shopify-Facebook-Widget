# Shopify-Facebook-Widget
Facebook Page Widget For Shopify 

In shpoify backend go to online store  ->  theme, in theme go to edit  HTML/CSS 
go to snippents and click on add new snippent, then create a snippet , name it facebook-page-widget and paste my code from facebook-page-widget . then go to index or other file where you want to display facebook page and call the file like
{% include 'facebook-page-widget' %}

other configuration:<br>

{% assign sw_facebook_url = '' %}<br>
put your facebook url like<br>
{% assign sw_facebook_url = 'https://www.facebook.com/MYCINEPLEX' %}<br>


{% assign sw_facebook_height = '500' %}<br>
{% assign sw_facebook_width = '350' %}<br>
{% assign sw_facebook_face = 'true' %}<br>
{% assign sw_facebook_header = 'false' %}<br>
{% assign sw_facebook_header_hide = 'false' %}

For <a href="https://white-rose-2.myshopify.com/" target="_blank">Demo</a>

my name is hannan



