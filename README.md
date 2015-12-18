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
<pre>&lt;script&gt;
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
