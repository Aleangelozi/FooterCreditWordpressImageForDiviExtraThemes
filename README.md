# footer_credit_image_to_Divi_and_Extra_themes
jQuery code to replace footer credit Wordpress with an image in Divi and Extra themes .

Add the code below to the head section of your website. Delete the target attribute to open the website in the same page.

<script>
jQuery(function($){
	$('#footer-info').html('<a href="URL" target="_blank"><img src="URL" alt="YourAltTextHere" title="YourTitleImageHere"/></a>');
});
</script>
