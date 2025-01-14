---

layout: col-sidebar
title: OWASP Newcastle (UK)
tags: newcastle
level: 4
region: Europe
altfooter: true
meetup-group: OWASP-Newcastle-Chapter
country: United Kingdom
postal-code: 

---

Welcome to the official chapter page of the OWASP Newcastle-Upon-Tyne (UK) Chapter. We meet at least four times a year, check back on this page for future meeting dates or check our Meetup group directly. Some of our previous talks are on our [Playeur](https://playeur.com/c/OWASPNewcastle/) channel.

We're always looking for speakers, we welcome anyone who is interested in presenting a talk. Whether you are new to the chapter or an existing member, we encourage you to reach out to one of our chapter leaders for more information on how to get involved. To help you along the way, we can also provide support with the preparation and delivery of your talk.

As we encourage knowledge sharing and raising awareness of our events and the topics covered, we also make the presentations available on our [previous events](#previousevents) page after each event where possible.

---

### Check our Upcoming Meetup Events:

---
Please follow OWASP Newcastle on [X](https://x.com/owasp_newcastle)/[Meetup](https://www.meetup.com/owasp-newcastle-chapter/)/[LinkedIn](https://www.linkedin.com/company/owasp-newcastle/) to be notified as soon as the next event date & location is announced

---
OWASP Newcastle Chapter upcoming events can be found on Meetup:

[https://www.meetup.com/owasp-newcastle-chapter/](https://www.meetup.com/owasp-newcastle-chapter/)

---
{% include chapter_events.html group=page.meetup-group %}


<script type='text/javascript'>
  $(function(){
    $(".timeclass").hover(function() {
      utc_str = $(this).text();
      ndx = utc_str.indexOf(':');
      st_hour_str = utc_str.substring(0, ndx);
      st_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(st_hour_str), parseInt(st_min_str), 0);
      start_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);

      ndx = utc_str.lastIndexOf(':');
      end_hour_str = utc_str.substring(ndx - 2, ndx - 1);
      end_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(end_hour_str), parseInt(end_min_str), 0);
      end_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);
      popstr = start_dt.toLocaleString(luxon.DateTime.TIME_WITH_SECONDS) + ' to ' + end_dt.toLocaleString(luxon.DateTime.TIME_WITH_SHORT_OFFSET);
      $(this).prop('title', popstr);
    });
  });  
</script>
