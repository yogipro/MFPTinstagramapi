<h2 id = "welcome_text">welcome to my github page this is The tag finder project on behalf of hameed alimohamadi and farnaz alizade. enjoy!</h2> <br><br><br>
<label for = "tag-in">Your<span font-size = "20em">tag</span>:</label>
<input type = "text" name = "tag-in" id = "tag-in">
<input type = "submit" name = "submit" id = "submit">





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
   
   
FB.getLoginStatus(function(response) {
    statusChangeCallback(response);
});

</script>

<script>
var submit_button = document.getElementById('submit')
var welcome_text = document.getElementById("welcome_text")
submit_button.onclick = function(){
  window.fbAsyncInit()
  }
</script>
