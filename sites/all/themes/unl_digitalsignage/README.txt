Developed for Google Chrome on Mac OS X
Most recent version checked: 
  14.0.835.202 on 10.7.2


I haven't done a good enough job making the name references in the theme generic so you must use these:
Content type machine name: digital_sign
Fields: Label/Name/Field/Widget
  - Title
  - Videos/field_videosources/Text/Text field (Enter the address of the RSS feed for your mediahub channel(s), for example http://mediahub.unl.edu/channels/172?format=xml&limit=8)
  - News/field_newssources/Text/Text field (Enter RSS feeds of your news sources.  Could be a feed created by a View from your site, a feed of stories from newsroom.unl.edu that are properly tagged, etc.)
  - Twitter/field_twitter/Text/Text field (Enter a public twitter username <em>UNLNews</em> or a public list <em>UNLNews/unl</em>.  Do not enter the @ symbol or twitter.com.)
  - Photos/field_beautyshots/Image/Image Min 710x1080 (Use only high quality professional photos, no "snap shots".)

Blocks:
  - On admin/structure/block for UNL DIGITAL SIGNAGE turn off all blocks except for "Main page content"

Things to make dev easier
  - comment out overflow: hidden from html in style.css
  - change data_url in unl_digitalsignage_unlalert.js to a local copy for testing
  - add the controls attr and remove the autoplay attr from the video tag in unl_digitalsignage.js so the video doesn't autoplay and drive you crazy