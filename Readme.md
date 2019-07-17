# intrec-countdown

This website presents the visitor with a countdown.
Once the countdown runs out, the user will be redirected to the signup page.

All code is run client-side.
This is why the actual url that will be redirected to has not been pushed to the live server yet.
(See merge-request !1)

After the countdown has run out, most of the client logic is not needed anymore.
To reduce the resources that are loaded before the redirect is executed, there is a slim version of the site waiting in merge-request !2.


## Hosting

Url: intrec.netlify.com

The website is hosted on netlify and is automatically built from the master branch.
Therefor it is important to only push changes to master that are meant for release.


## Debugging

There is no backend. The `index.html` can be opened with any browser to be tested.


## Updating Countdown

To update the countdown, change the datetime on line 91 of `index.html`.
Do not forget to update the text in line 78 as well.
