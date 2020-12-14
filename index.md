welcome to my github page this is The tag finder project on behalf of hameed alimohamadi and farnaz alizade. enjoy! <br><br><br>
<label for = "tag-in">Your<span font-size = "20em">tag</span>:</label>
<input type = "text" name = "tag-in" id = "tag-in">
<input type = "submit" name = "submit">




<script>
  window.fbAsyncInit = function() {
    FB.init({
      appId      : '4037672036267212',
      cookie     : true,
      xfbml      : true,
      version    : 'v9.0'
    });
      
    FB.AppEvents.logPageView();   
      
  };

  (function(d, s, id){
     var js, fjs = d.getElementsByTagName(s)[0];
     if (d.getElementById(id)) {return;}
     js = d.createElement(s); js.id = id;
     js.src = "https://connect.facebook.net/en_US/sdk.js";
     fjs.parentNode.insertBefore(js, fjs);
   }(document, 'script', 'facebook-jssdk'));
</script>

<script type = 'javascript'>
var submit_button = document.getElementById('submit')
submit_button.onclcick = function(){
  window.fbAsyncInit()
  }
</script>
