---
pageTitle: Ready to use styling
pageFeatureImage: /dist/images/demopost.jpg
pageFeatureImageRetina: /dist/images/demopost@2x.jpg
pageExcerpt: All default styling displayed here. Lorem ipsum dolor sit amet, consectetur adipiscing elit. In in euismod quam. Cras mollis ligula ut ex eleifend, a aliquet risus lobortis.
postTag: Styling
date: Last Modified
---

## This is a h2
### This is a h3

This is a paragraph. Lorem ipsum dolor sit amet, consectetur adipiscing elit. In in euismod quam. Cras mollis ligula ut ex eleifend, a aliquet risus lobortis. Fusce risus justo, faucibus vitae commodo quis, ultricies quis nunc. Nam ante erat, convallis id dapibus suscipit, lobortis nec dui. Maecenas fringilla varius tortor scelerisque facilisis. Nunc sed dui sem. Donec mauris libero, dapibus at venenatis ut, tincidunt vitae mi.

> This is a blockquote. Lorem ipsum dolor sit amet, consectetur adipiscing elit. In in euismod quam. Cras mollis ligula ut ex eleifend, a aliquet risus lobortis. Fusce risus justo, faucibus vitae commodo quis, ultricies quis nunc. Nam ante erat, convallis id dapibus suscipit, lobortis nec dui. Maecenas fringilla varius tortor scelerisque facilisis. Nunc sed dui sem. Donec mauris libero, dapibus at venenatis ut, tincidunt vitae mi.

This is a paragraph with some **strong** text and a <s>strikethrough</s>. Lorem ipsum dolor sit amet, consectetur adipiscing elit. In in euismod quam. Cras mollis ligula ut ex eleifend, a aliquet risus lobortis. Fusce risus justo, faucibus vitae commodo quis, ultricies quis nunc. Nam ante erat, convallis id dapibus suscipit, lobortis nec dui. Maecenas fringilla varius tortor scelerisque facilisis. Nunc sed dui sem. Donec mauris libero, dapibus at venenatis ut, tincidunt vitae mi.

```
This is a code block:

Lorem ipsum dolor sit amet.
Consectetur adipiscing elit.
In in euismod quam.
Cras mollis ligula ut ex eleifend, a aliquet risus lobortis.
Maecenas fringilla varius.
```

This is a paragraph with `some code in it` and a <mark>marked</mark> bit of copy. Lorem ipsum dolor sit amet, consectetur adipiscing elit. In in euismod quam. Cras mollis ligula ut ex eleifend, a aliquet risus lobortis. Fusce risus justo, faucibus vitae commodo quis, ultricies quis nunc. Nam ante erat, convallis id dapibus suscipit, lobortis nec dui. Maecenas fringilla varius tortor scelerisque facilisis. Nunc sed dui sem. Donec mauris libero, dapibus at venenatis ut, tincidunt vitae mi.

![This is an image](/dist/images/demopost.jpg)

This is a paragraph with a <a href="#">link in it</a>. Lorem ipsum dolor sit amet, consectetur adipiscing elit. In in euismod quam. Cras mollis ligula ut ex eleifend, a aliquet risus lobortis. Fusce risus justo, faucibus vitae commodo quis, ultricies quis nunc. Nam ante erat, convallis id dapibus suscipit, lobortis nec dui. Maecenas fringilla varius tortor scelerisque facilisis. Nunc sed dui sem. Donec mauris libero, dapibus at venenatis ut, tincidunt vitae mi.

This is a paragraph with a <abbr title="abbreviation">abbr</abbr>. Lorem ipsum dolor sit amet, consectetur adipiscing elit. In in euismod quam. Cras mollis ligula ut ex eleifend, a aliquet risus lobortis. Fusce risus justo, faucibus vitae commodo quis, ultricies quis nunc. Nam ante erat, convallis id dapibus suscipit, lobortis nec dui. Maecenas fringilla varius tortor scelerisque facilisis. Nunc sed dui sem. Donec mauris libero, dapibus at venenatis ut, tincidunt vitae mi.

----

## Form

<form id="FORM_ID" class="form" name="form_name" method="POST" data-parsley-validate>
    <div class="form-group">
        <label for="contact_form_name">Name<sup>*</sup></label>
        <input type="text" id="contact_form_name" name="contact_form_name" data-parsley-required="true" data-parsley-required-message="Required." required />
    </div>
    <div class="form-group">
        <label for="contact_form_tel">Telephone</label>
        <input type="tel" data-parsley-type="tel" id="contact_form_tel" name="contact_form_tel" data-parsley-type="digits" data-parsley-type-message="Invalid telephone number." />
    </div>
    <div class="form-group">
        <label for="contact_form_email">Email<sup>*</sup></label>
        <input type="email" data-parsley-type="email" id="contact_form_email" name="contact_form_email" data-parsley-type-message="Invalid email." data-parsley-required="true" data-parsley-required-message="Required." required />
    </div>
    <div class="form-group">
        <label for="contact_form_email_confirm">Confirm Email<sup>*</sup></label>
        <input type="email" data-parsley-type="email" id="contact_form_email_confirm" name="contact_form_email_confirm" data-parsley-type-message="Invalid email." data-parsley-required="true" data-parsley-required-message="Required." data-parsley-equalto="#contact_form_email" data-parsley-equalto-message="Email Mis-match." required />
    </div>
    <div class="form-group">
        <label for="contact_form_message">Message<sup>*</sup></label>
        <textarea id="contact_form_message" name="contact_form_message" data-parsley-required="true" data-parsley-required-message="Required." required></textarea>
    </div>
    <div class="form-group">
        <fieldset class="terms">
            <input type="checkbox" id="termsandconditions" name="termsandconditions" value="formterms" data-parsley-required="true" data-parsley-required-message="Please accept the terms and conditions.">
            <label for="termsandconditions" class="terms">I agree to your <a href="#">terms &amp; conditions</a> and <a href="#">privacy policy</a><sup>*</sup></label>
        </fieldset>
    </div>
    <div class="form-group">
        <button type="submit">Send Message</button>
    </div>
</form>

----

## Table of contents

<ul class="toc">
    <li><a href="#">Ross</a></li>
    <li><a href="#">Rachel</a></li>
    <li><a href="#">Chandler</a></li>
    <li><a href="#">Monica</a></li>
    <li><a href="#">Joey</a></li>
    <li><a href="#">Rachel</a></li>
</ul>

----

## Twitter Embed

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Daft Punk.<br><br>Game changers.<br>Legends.<br>🤖🤖<br><br>1993 - 2021 <a href="https://t.co/p6BUJQAa9n">pic.twitter.com/p6BUJQAa9n</a></p>&mdash; Defected Records (@DefectedRecords) <a href="https://twitter.com/DefectedRecords/status/1363871973508579331?ref_src=twsrc%5Etfw">February 22, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

----

## Gist Embed

<script src="https://gist.github.com/DanCanetti/8031abe17fb2895474b4c072ddb6aa85.js"></script>