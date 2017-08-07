<script>
$(document).ready(function(){
$('#BT1').click(function(){
  $.getJSON("https://api.forismatic.com/api/1.0/?method=getQuote&lang=en&format=jsonp&jsonp=?", 
    function getQuote(res) {
     var quote = res.quoteText;
     var author = res.quoteAuthor;
    $(".quoteText").text(quote);
    $(".quoteAuthor").text(author);
     $('#tW2').attr('href', 'https://twitter.com/intent/tweet?hashtags=quotes&related=freecodecamp&text=' + encodeURIComponent('"' + quote + '" ' + author));
  })
  
  });
});

     
     

    
     


     //   $.ajax({
//     url: "http://api.forismatic.com/api/1.0/?method=getQuote&lang=en&format=json", success: function(getQuote){
//  $("#C2").html(getQuote);
//     }
        
//   });,

<script>
<script src="jquery-3.2.1.min.js"></script>