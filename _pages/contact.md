---
layout: single
title: Contact
permalink: /contact/
---

<div class="page__comments-form">
<h4 class="page__comments-title">Leave a Message</h4>
<p class="small">Your email address will kept confidential. Required fields are marked <span class="required">*</span></p>
<form id="new_comment" class="page__comments-form js-form form" method="post" action="https://formspree.io/ourlittleyellowkitchen@gmail.com">
<div class="form__spinner">
<i class="fas fa-spinner fa-spin fa-3x fa-fw"></i>
<span class="sr-only">Loading...</span>
</div>
<div class="form-group">
<label for="comment-form-message">Message <small class="required">*</small></label>
<textarea type="text" rows="3" id="comment-form-message" name="fields[message]" tabindex="1"></textarea>
<div class="small help-block"><a href="https://daringfireball.net/projects/markdown/">Markdown is supported.</a></div>
</div>
<div class="form-group">
<label for="comment-form-name">Name <small class="required">*</small></label>
<input type="text" id="comment-form-name" name="fields[name]" tabindex="2" />
</div>
<div class="form-group">
<label for="comment-form-email">Email address <small class="required">*</small></label>
<input type="email" id="comment-form-email" name="fields[email]" tabindex="3" />
</div>
<div class="form-group">
<label for="comment-form-phone">Phone Number (optional)</label>
<input type="phone" id="comment-form-phone" name="fields[phonem]" tabindex="4" />
</div>
<div class="form-group hidden" style="display: none;">
<input type="hidden" name="options[slug]" value="" />
<label for="comment-form-location">Not used. Leave blank if you are a human.</label>
<input type="text" id="comment-form-location" name="fields[hidden]" autocomplete="off" />
</div>

<p class="hidden js-notice">
<strong class="js-notice-text"></strong>
</p>

<div class="form-group">
<button type="submit" id="comment-form-submit" tabindex="5" class="btn btn--primary btn--large">Submit comment</button>
</div>
</form>
</div>

