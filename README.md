Layerly Affiliate Badge

Easily add the Layerly affiliate badge to your website with a single iframe.

How to use
	1.	Copy and paste the code below into your website where you want the badge to appear:

<script>
  window.addEventListener('message', function(event) {
    if(event.data.iframeHeight){
      const iframe = document.getElementById('affiliateBadgeIframe');
      if(iframe) iframe.style.height = event.data.iframeHeight + 'px';
    }
  });
</script>
<iframe
  id="affiliateBadgeIframe"
  src="https://layerly.github.io/layerly-affiliate/affiliate-badge.html?affiliate_id=YOUR_ID&theme=light"
  width="100%"
  style="border:none; width:100%;"
></iframe>

Options
	•	affiliate_id – Replace YOUR_ID with your unique affiliate ID.
	•	theme – Choose between light (default) or dark.

Example (dark mode):

src="https://layerly.github.io/layerly-affiliate/affiliate-badge.html?affiliate_id=YOUR_ID&theme=dark"

That’s it! 🎉
