---
layout: post_layout
---

0xBU is a cybersecurity club and <a href="https://ctftime.org/ctf-wtf/">CTF</a> competition team at <a href="https://www.bu.edu">Boston University</a>. 

If you're interested in exploring, and learning about the world of cyber security, then please drop by! No security background is necessary to participate, however a willingness to learn is.

We meet regularly every **Saturday from 1PM to 3PM in 111 Cummington Mall, Room B26, Boston, MA 02215** (<a href="http://builds.cc">BUILDS</a> room).

Our <a href="https://github.com/0xbu/workshops">meetings</a> generally focus around practical workshops involving **binary exploitation** (pwning), **reverse engineering** (cracking), **malware analysis**, **network security**, **web security**, **cryptography**, **digital forensics**, **applied programming**, and previous **CTF challenges**.

If you have any questions, contact Chet Powers at <a href="mailto:ccpowers@bu.edu">ccpowers@bu.edu</a>, please include 0xBU in the subject.

<!-- Begin Mailing List -->
### Sign up for the BUILDS mailing list to stay updated

<form action="//builds.us14.list-manage.com/subscribe/post?u=48eeff7657509db01b37d0c9b&amp;id=c7c2160530" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" target="_blank" novalidate="">
    <div id="mc_embed_signup_scroll">
        <input type="email" value="" name="EMAIL" id="mce-EMAIL" placeholder="Sign up with your email." required="">
        <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
        <div style="display: none;" aria-hidden="true"><input type="text" name="b_48eeff7657509db01b37d0c9b_c7c2160530" tabindex="-1" value=""></div>
        <input class="button-primary" type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe">
    </div>
</form>

<a href="https://0xbu.slack.com" class="button-primary"><input class="button-primary" type="button" value="#Slack Chat"></a>

<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>

<script>
$("#emailform").submit(function(event) {
  // Stop form from submitting normally
  event.preventDefault();
 
  // Get some values from elements on the page:
  var $form = $(this),
    term = $form.find("input[name='email']").val(),
    url = $form.attr("action");
 
  // Send the data using post
  var posting = $.post(url, {'email':term}, function(data) {
  }).error(function() {
    $(".xalert-error-invis").show();
  }).success(function() {
    $(".xalert-success-invis").show();
  });
  return false;
});

</script>

<!-- Begin Calendar -->
### Calendar
<iframe src="https://calendar.google.com/calendar/embed?src=bu.edu_7n7ld2696rv78u7ha8998ngr64%40group.calendar.google.com&ctz=America/New_York" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>	

