# gmail-contacts-api
An Initiative using google api to find your gmail contacts list . 


First create an app in https://console.developers.google.com/project and obtain below information 

    $client_id = 'Your Client Id';
    $client_secret = 'Your Client Secret Id';
    $redirect_uri = 'http://Your Redirect URL';
    
    
After obtaining the info then Make the link for Google Login

  <a  style="font-size:25px;font-weight:bold;" href="https://accounts.google.com/o/oauth2/auth?client_id=client_id&redirect_uri=your_redirect_url&scope=https://www.google.com/m8/feeds/&response_type=code">Click here to Import Gmail Contacts</a>
    