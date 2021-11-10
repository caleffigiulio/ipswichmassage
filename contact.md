---
title: Contact Us and find our location
permalink: "/contact-and-map/"
position: 4
layout: default
---

{% include contact-us-section.html %}

Opening Hours
Sunday 7:30 - 3:00pm
Monday 8:00 - 7:00pm
Tuesday 8:00 - 7:00pm
Wednesday 8:00 - 7:00pm
Thursday 8:00 - 7:00pm
Friday 8:00 - 7:00 pm
Saturday 7:30 - 5:00pm

<!-- Messenger Chat plugin Code -->
    <div id="fb-root"></div>

    <!-- Your Chat plugin code -->
    <div id="fb-customer-chat" class="fb-customerchat">
    </div>

    <script>
      var chatbox = document.getElementById('fb-customer-chat');
      chatbox.setAttribute("page_id", "271078168387");
      chatbox.setAttribute("attribution", "biz_inbox");

      window.fbAsyncInit = function() {
        FB.init({
          xfbml            : true,
          version          : 'v12.0'
        });
      };

      (function(d, s, id) {
        var js, fjs = d.getElementsByTagName(s)[0];
        if (d.getElementById(id)) return;
        js = d.createElement(s); js.id = id;
        js.src = 'https://connect.facebook.net/en_US/sdk/xfbml.customerchat.js';
        fjs.parentNode.insertBefore(js, fjs);
      }(document, 'script', 'facebook-jssdk'));
    </script>

