---
title: "Programming with Wt - A C++ library for developing stateful and highly interactive web applications"
date: 2015-06-24T16:04:07-04:00
menu:
  sidebar:
    name: Programming with Wt
    identifier: wt
    parent: videos
    weight: 10
hero: images/p1010038.jpg
draft: false
---
#### I presented this webinar on June 24th, 2015 as a part of a series of regular biweekly General Interest Webinars ran by [SHARCNET](https://sharcnet.ca).
---
{{< youtube qDc_s8hy3cY >}}

---
If you need to expose a new HPC service or a brand new scientific methodology to outside community by developing a highly interactive web application but without gaining familiarity with ever-changing technologies such as HTML/XHTML, JavaScript, CSS, AJAX, CGI, DHTML, SVG/VML/Canvas, PHP, etc., this webinar is for you. Wt (pronounced 'witty') is a freely available (http://www.webtoolkit.eu/) widget-centric C++ library and application server for developing web applications that brings the desktop programming model to web application development. From a programmer's perspective, the Wt API is similar to those offered by libraries such as Qt, GTK, wxWindows, and the like. However, instead of rendering widgets to Windows/X11 windows, Wt incrementally renders the widgets in web browsers. A web application developed with Wt is written in only one compiled language (C++), from which the library generates the necessary HTML/XHTML, JavaScript, CGI, or AJAX code. If available, Wt will maximally use JavaScript and AJAX, but applications developed using Wt will also function correctly when AJAX is not available, or when JavaScript is disabled, reverting to a plain HTML/CGI mechanism for communication between browser and server. Browser-side events such as button clicks, mouse movements, and drag-and-drop events are transparently converted into server-side events using Wt's signal/slot mechanism. Being a native C++ library, web applications developed with Wt typically enjoy greater efficiency and a smaller footprint than Java or Ruby solutions. As such, Wt lends itself to devices where efficiency and footprint matters, like in embedded applications.

In this webinar, I will introduce Wt, demonstrate some interesting samples and go over the basics of making an interactive web application. The audience are expected to have some basic programming skills preferably in C++, but no experience in HTML, CSS or JavaScript is necessary.
