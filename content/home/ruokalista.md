---
# An instance of the Blank widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

title: Ruokalista 
subtitle:
design:
  spacing:
    padding: ["20px", "0", "20px", "0"]
---
<center>

[https://ruokalistat.azurewebsites.net/](https://ruokalistat.azurewebsites.net/#/8cfdbfde-ea98-e511-9417-00215a9c1ca7)

<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.0/jquery.min.js"></script>
<script type="text/javascript">
$(function(){
    $('#button').click(function(){ 
        if(!$('#iframe').length) {
                $('#iframeHolder').html('<iframe src="https://ruokalistat.azurewebsites.net/#/8cfdbfde-ea98-e511-9417-00215a9c1ca7" width="65%" height="350" loading="lazy" frameborder="0" marginheight="0" marginwidth="0">');
        }
    });   
});
</script>
<button id="button" type="button" class="btn btn-primary btn-lg">Paina tästä</button>

  <div id="iframeHolder"></div>


</center>