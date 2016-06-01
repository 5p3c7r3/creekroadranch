---
layout: default
title: Photos
group: navigation
---
<style>
.modal-dialog {width:600px;}
.thumbnail {margin-bottom:6px;}
</style>

<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g1.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g2.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g3.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g4.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g5.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g6.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g7.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g8.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g9.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g10.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g11.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g12.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g13.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g14.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g15.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g16.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g17.jpg"></a></div>
<div class="col-lg-3 col-md-4 col-sm-4 col-xs-6"><a title="&nbsp;" href="#"><img class="thumbnail img-responsive" src="/img/gallery/g18.jpg"></a></div>

<div tabindex="-1" class="modal fade" id="myModal" role="dialog">
  <div class="modal-dialog">
  <div class="modal-content">
    <div class="modal-header">
		<button class="close" type="button" data-dismiss="modal">×</button>
		<h3 class="modal-title">Heading</h3>
	</div>
	<div class="modal-body">

	</div>
	<div class="modal-footer">
		<button class="btn btn-default" data-dismiss="modal">Close</button>
	</div>
   </div>
  </div>
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script>
$(document).ready(function() {
$('.thumbnail').click(function(){
      $('.modal-body').empty();
  	var title = $(this).parent('a').attr("title");
  	$('.modal-title').html(title);
  	$($(this).parents('div').html()).appendTo('.modal-body');
  	$('#myModal').modal({show:true});
});
});
</script>

<br/>
<br/>

<div style="clear:both;">
<!-- &nbsp; -->
</div>
<br/>
