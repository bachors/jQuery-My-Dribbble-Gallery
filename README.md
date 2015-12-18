# jQuery-My-Dribbble-Gallery
Create a Simple Portfolio Using Dribbble API v1

<h2>Step 1</h2>
<h3>Register an Application</h3>

Dribbble now requires minimum authentication to access their API. Creating an app is easier than it sounds:

    1. Go to this page => https://dribbble.com/account/applications/new
    2. Enter all of the information
       (For “callback URL” you can just enter your domain name)

Take note of the <strong>Client Access Token</strong>, as you’ll be needing it in the next step.
<h2>Step 2</h2>
<h3>Edit Your Website</h3>

This guide assumes you have a good understanding of HTML and CSS. Open up your editor, and paste the following in the place you’d like the portfolio to appear:
<h4>CSS</h4>
<pre>&lt;!-- Custom style my dribbble gallery --&gt;
&lt;link type="text/css" rel="stylesheet" href="src/my-dribbble-gallery.css" /&gt;</pre>
<h4>HTML</h4>
<pre>&lt;!-- Your profiles --&gt;
&lt;div class="bcr_drb_profile"&gt;&lt;/div&gt;

&lt;!-- Your shot --&gt;
&lt;div class="dribbble bcr_drb_shots"&gt;&lt;/div&gt;

&lt;!-- Your buckets --&gt;
&lt;div class="dribbble bcr_drb_buckets" style="display:none"&gt;&lt;/div&gt;

&lt;!-- Your projects --&gt;
&lt;div class="dribbble bcr_drb_projects" style="display:none"&gt;&lt;/div&gt;

&lt;!-- Your teams --&gt;
&lt;div class="dribbble bcr_drb_teams" style="display:none"&gt;&lt;/div&gt;

&lt;!-- Your likes --&gt;
&lt;div class="dribbble bcr_drb_likes" style="display:none"&gt;&lt;/div&gt;

&lt;!-- Your followers --&gt;
&lt;div class="dribbble bcr_drb_followers" style="display:none"&gt;&lt;/div&gt;</pre>
<h4>JS</h4>
<pre>&lt;!-- Include jQuery --&gt;
&lt;script src="//code.jquery.com/jquery-2.1.1.min.js"&gt;&lt;/script&gt;

&lt;!-- jQuery my dribbble gallery --&gt;
&lt;script src="src/my-dribbble-gallery.js"&gt;&lt;/script&gt;

&lt;!-- Setting Example --&gt;
&lt;script&gt;
    bcr_mdg(
        drb_username = 'USERNAME',
        drb_token = 'TOKEN'
    );
&lt;/script&gt;</pre>
Edit the following:

    # Replace “USERNAME” with your dribbble username
    # Replace “TOKEN” with your app’s Client Access Token

Save the file and upload it to your site.
<p><h2><a href="http://ibacor.com/demo/jquery-my-dribbble-gallery" target="_BLANK">DEMO</a></h2></p>
