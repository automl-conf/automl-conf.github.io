jQuery(function($){
	$('body').on('click', '.loadmore', function() {
 
		var button = $(this);
		var data = {
			'action': 'virtual_conference_loadmore',
			'page' : virtual_conference_loadmore_params.current_page,
		};
 
		$.ajax({
			url : virtual_conference_loadmore_params.ajaxurl,
			data : data,
			type : 'POST',
			beforeSend : function ( xhr ) {
				button.text('Loading...');
			},
			success : function( data ) {
				if( data ) { 
					$( 'div.blog-list-block' ).append(data);
					button.text( 'More Posts' );
					virtual_conference_loadmore_params.current_page++;
 
					if ( virtual_conference_loadmore_params.current_page == virtual_conference_loadmore_params.max_page ) { 
						button.remove();
					}
				} else {
					button.remove();
				}
			}
		});
	});
});