# Grevious

Grevious wants your help.  They need to update their three page website.

## Home Page, aka `home.html`

Their hosting service told them it needs to be renamed as `index.html`.  Rename the file, and then fix any errors it causes.

## About Page, aka `about.html`

You should have received the picture `grevious-work-environment.jpg`.  They want this inserted between the 2nd and 3rd paragraphs of text.  Make sure it's the same width as the team photo, and it should have a title of "It's great to work in our space!"

## Contact Page, aka `contact.html`

There's a bunch they want changed here:

- Remove the bullets from the unordered list
- Remove the padding from the unordered list (it's making the words appear too far to the right)
- The phone number and email address should be made into hyperlinks.  You can format the href so that it opens a phone app or opens an email client.  Look it up, and fix it!
- The map doesn't actually reflect the address.  They just pasted in some google code to make it work, but they're definitely not in Australia.  Find the correct latitude and longitude for their address and update the variable `latLong` inside the `<script>` tag with the correct information.

## Whole site

They're upset that the nav links are the same font as the whole site. They want the links to be in Roboto, with a very thin weight... maybe 100.  They'd also like the link text to brighten all the way to pure white (right now it's `#ddd`, pure white is `#fff`) when a user hovers over the navigation link.
