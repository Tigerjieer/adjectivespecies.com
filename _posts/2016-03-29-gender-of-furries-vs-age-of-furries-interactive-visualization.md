---
layout: post
title: 'Gender of furries vs Age of furries: interactive visualization'
date: 2016-03-29 12:00:22.000000000 -07:00
type: post
parent_id: '0'
published: true
password: ''
status: publish
categories:
- Articles
tags:
- data visualization
meta:
  _edit_last: '14'
  _at_widget: '1'
  _social_notify: '1'
  _social_broadcast_content: 'a:1:{s:7:"twitter";a:1:{i:403645425;s:90:"New interactive
    visualization: Furry gender vs Age http://www.adjectivespecies.com/?p=2768";}}'
  _social_broadcast_meta: a:1:{s:7:"twitter";a:1:{i:403645425;a:0:{}}}
  _social_aggregation_next_run: '1459275342'
  _social_broadcasted_ids: 'a:1:{s:7:"twitter";a:1:{i:403645425;a:1:{i:714874941439512580;a:3:{s:7:"message";s:3264:"eyJjcmVhdGVkX2F0IjoiVHVlIE1hciAyOSAxODowMDo0MiArMDAwMCAyMDE2IiwiaWQiOiI3MTQ4NzQ5NDE0Mzk1MTI1ODAiLCJpZF9zdHIiOiI3MTQ4NzQ5NDE0Mzk1MTI1ODAiLCJ0ZXh0IjoiTmV3IGludGVyYWN0aXZlIHZpc3VhbGl6YXRpb246IEZ1cnJ5IGdlbmRlciB2cyBBZ2UgaHR0cHM6XC9cL3QuY29cL0E0RkFEcmNSNlEiLCJlbnRpdGllcyI6eyJoYXNodGFncyI6W10sInN5bWJvbHMiOltdLCJ1c2VyX21lbnRpb25zIjpbXSwidXJscyI6W3sidXJsIjoiaHR0cHM6XC9cL3QuY29cL0E0RkFEcmNSNlEiLCJleHBhbmRlZF91cmwiOiJodHRwOlwvXC93d3cuYWRqZWN0aXZlc3BlY2llcy5jb21cLz9wPTI3NjgiLCJkaXNwbGF5X3VybCI6ImFkamVjdGl2ZXNwZWNpZXMuY29tXC8/cD0yNzY4IiwiaW5kaWNlcyI6WzUxLDc0XX1dfSwidHJ1bmNhdGVkIjpmYWxzZSwic291cmNlIjoiPGEgaHJlZj1cImh0dHBzOlwvXC9zb3ByZXN0by5tYWlsY2hpbXAuY29tXCIgcmVsPVwibm9mb2xsb3dcIj5Tb2NpYWwgUHJveHkgYnkgTWFpbGNoaW1wPFwvYT4iLCJpbl9yZXBseV90b19zdGF0dXNfaWQiOm51bGwsImluX3JlcGx5X3RvX3N0YXR1c19pZF9zdHIiOm51bGwsImluX3JlcGx5X3RvX3VzZXJfaWQiOm51bGwsImluX3JlcGx5X3RvX3VzZXJfaWRfc3RyIjpudWxsLCJpbl9yZXBseV90b19zY3JlZW5fbmFtZSI6bnVsbCwidXNlciI6eyJpZCI6IjQwMzY0NTQyNSIsImlkX3N0ciI6IjQwMzY0NTQyNSIsIm5hbWUiOiJbYWRqZWN0aXZlXVtzcGVjaWVzXSIsInNjcmVlbl9uYW1lIjoiYWRqc3BlY2llcyIsImxvY2F0aW9uIjoiIiwiZGVzY3JpcHRpb24iOiJFeHBsb3JpbmcgdGhlIGZ1cnJ5IHdvcmxkIGZyb20gdGhlIGluc2lkZSBvdXQuIiwidXJsIjoiaHR0cDpcL1wvdC5jb1wvWlloOVdtTFUwbiIsImVudGl0aWVzIjp7InVybCI6eyJ1cmxzIjpbeyJ1cmwiOiJodHRwOlwvXC90LmNvXC9aWWg5V21MVTBuIiwiZXhwYW5kZWRfdXJsIjoiaHR0cDpcL1wvYWRqZWN0aXZlc3BlY2llcy5jb20iLCJkaXNwbGF5X3VybCI6ImFkamVjdGl2ZXNwZWNpZXMuY29tIiwiaW5kaWNlcyI6WzAsMjJdfV19LCJkZXNjcmlwdGlvbiI6eyJ1cmxzIjpbXX19LCJwcm90ZWN0ZWQiOmZhbHNlLCJmb2xsb3dlcnNfY291bnQiOjE2MzAsImZyaWVuZHNfY291bnQiOjM4NSwibGlzdGVkX2NvdW50IjozMCwiY3JlYXRlZF9hdCI6IldlZCBOb3YgMDIgMTk6NTc6MzggKzAwMDAgMjAxMSIsImZhdm91cml0ZXNfY291bnQiOjQ5NiwidXRjX29mZnNldCI6LTI1MjAwLCJ0aW1lX3pvbmUiOiJQYWNpZmljIFRpbWUgKFVTICYgQ2FuYWRhKSIsImdlb19lbmFibGVkIjpmYWxzZSwidmVyaWZpZWQiOmZhbHNlLCJzdGF0dXNlc19jb3VudCI6MzEwMywibGFuZyI6ImVuIiwiY29udHJpYnV0b3JzX2VuYWJsZWQiOmZhbHNlLCJpc190cmFuc2xhdG9yIjpmYWxzZSwiaXNfdHJhbnNsYXRpb25fZW5hYmxlZCI6ZmFsc2UsInByb2ZpbGVfYmFja2dyb3VuZF9jb2xvciI6IkMwREVFRCIsInByb2ZpbGVfYmFja2dyb3VuZF9pbWFnZV91cmwiOiJodHRwOlwvXC9hYnMudHdpbWcuY29tXC9pbWFnZXNcL3RoZW1lc1wvdGhlbWUxXC9iZy5wbmciLCJwcm9maWxlX2JhY2tncm91bmRfaW1hZ2VfdXJsX2h0dHBzIjoiaHR0cHM6XC9cL2Ficy50d2ltZy5jb21cL2ltYWdlc1wvdGhlbWVzXC90aGVtZTFcL2JnLnBuZyIsInByb2ZpbGVfYmFja2dyb3VuZF90aWxlIjpmYWxzZSwicHJvZmlsZV9pbWFnZV91cmwiOiJodHRwOlwvXC9wYnMudHdpbWcuY29tXC9wcm9maWxlX2ltYWdlc1wvNDE2MzMxNDA2MjEwMzgzODcyXC9HMlhYRzljel9ub3JtYWwucG5nIiwicHJvZmlsZV9pbWFnZV91cmxfaHR0cHMiOiJodHRwczpcL1wvcGJzLnR3aW1nLmNvbVwvcHJvZmlsZV9pbWFnZXNcLzQxNjMzMTQwNjIxMDM4Mzg3MlwvRzJYWEc5Y3pfbm9ybWFsLnBuZyIsInByb2ZpbGVfbGlua19jb2xvciI6IjAwODRCNCIsInByb2ZpbGVfc2lkZWJhcl9ib3JkZXJfY29sb3IiOiJDMERFRUQiLCJwcm9maWxlX3NpZGViYXJfZmlsbF9jb2xvciI6IkRERUVGNiIsInByb2ZpbGVfdGV4dF9jb2xvciI6IjMzMzMzMyIsInByb2ZpbGVfdXNlX2JhY2tncm91bmRfaW1hZ2UiOnRydWUsImhhc19leHRlbmRlZF9wcm9maWxlIjpmYWxzZSwiZGVmYXVsdF9wcm9maWxlIjp0cnVlLCJkZWZhdWx0X3Byb2ZpbGVfaW1hZ2UiOmZhbHNlLCJmb2xsb3dpbmciOmZhbHNlLCJmb2xsb3dfcmVxdWVzdF9zZW50IjpmYWxzZSwibm90aWZpY2F0aW9ucyI6ZmFsc2V9LCJnZW8iOm51bGwsImNvb3JkaW5hdGVzIjpudWxsLCJwbGFjZSI6bnVsbCwiY29udHJpYnV0b3JzIjpudWxsLCJpc19xdW90ZV9zdGF0dXMiOmZhbHNlLCJyZXR3ZWV0X2NvdW50IjowLCJmYXZvcml0ZV9jb3VudCI6MCwiZmF2b3JpdGVkIjpmYWxzZSwicmV0d2VldGVkIjpmYWxzZSwicG9zc2libHlfc2Vuc2l0aXZlIjpmYWxzZSwibGFuZyI6ImVuIn0=";s:4:"urls";a:2:{i:0;s:105:"http://www.adjectivespecies.com/2016/03/29/gender-of-furries-vs-age-of-furries-interactive-visualization/";i:1;s:39:"http://www.adjectivespecies.com/?p=2768";}s:7:"account";O:8:"stdClass":1:{s:4:"user";O:8:"stdClass":38:{s:2:"id";s:9:"403645425";s:6:"id_str";s:9:"403645425";s:4:"name";s:20:"[adjective][species]";s:11:"screen_name";s:10:"adjspecies";s:8:"location";s:0:"";s:3:"url";s:27:"http://adjectivespecies.com";s:11:"description";s:46:"Exploring
    the furry world from the inside out.";s:9:"protected";s:1:"0";s:15:"followers_count";s:3:"561";s:13:"friends_count";s:3:"350";s:12:"listed_count";s:1:"6";s:10:"created_at";s:30:"Wed
    Nov 02 19:57:38 +0000 2011";s:16:"favourites_count";s:2:"11";s:10:"utc_offset";s:6:"-28800";s:9:"time_zone";s:30:"Pacific
    Time (US &amp; Canada)";s:11:"geo_enabled";s:1:"0";s:8:"verified";s:1:"0";s:14:"statuses_count";s:4:"1944";s:4:"lang";s:2:"en";s:6:"status";a:10:{s:10:"created_at";s:30:"Sun
    Feb 17 15:21:53 +0000 2013";s:2:"id";s:18:"303162359898312705";s:6:"id_str";s:18:"303162359898312705";s:4:"text";s:49:"New
    Post: Birds of a Feather http://t.co/Y61Z4Ht6";s:6:"source";s:9:"TweetDeck";s:9:"truncated";s:1:"0";s:13:"retweet_count";s:1:"2";s:9:"favorited";s:1:"0";s:9:"retweeted";s:1:"0";s:18:"possibly_sensitive";s:1:"0";}s:20:"contributors_enabled";s:1:"0";s:13:"is_translator";s:1:"0";s:24:"profile_background_color";s:6:"C0DEED";s:28:"profile_background_image_url";s:47:"http://a0.twimg.com/images/themes/theme1/bg.png";s:34:"profile_background_image_url_https";s:49:"https://si0.twimg.com/images/themes/theme1/bg.png";s:23:"profile_background_tile";s:1:"0";s:17:"profile_image_url";s:71:"http://a0.twimg.com/profile_images/1647343758/adjspecies-ico_normal.png";s:23:"profile_image_url_https";s:73:"https://si0.twimg.com/profile_images/1647343758/adjspecies-ico_normal.png";s:18:"profile_link_color";s:6:"0084B4";s:28:"profile_sidebar_border_color";s:6:"C0DEED";s:26:"profile_sidebar_fill_color";s:6:"DDEEF6";s:18:"profile_text_color";s:6:"333333";s:28:"profile_use_background_image";s:1:"1";s:15:"default_profile";s:1:"1";s:21:"default_profile_image";s:1:"0";s:9:"following";s:1:"0";s:19:"follow_request_sent";s:1:"0";s:13:"notifications";s:1:"0";}}}}}}'
author:
  login: GuestPost
  email: submit@adjectivespecies.com
  display_name: GuestPost
  first_name: Guest
  last_name: Poster
---
<p><a href="http://vis.adjectivespecies.com/gender-age/">Click here for our interactive visualization showing the relationship between furry gender and age</a>.</p>
<p><em>Visualization by Ruxley. Species and age data taken from the 2015 Furry Survey. click through for the interactive version.</em></p>
<p><img class="aligncenter size-full wp-image-2769" src="{{ site.baseurl }}/assets/Screen-Shot-2016-03-25-at-18.06.53.png" alt="Screen Shot 2016-03-25 at 18.06.53" width="840" height="504" /></p>



