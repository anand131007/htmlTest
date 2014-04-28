/*Place holder   -  General.js */

// Utilizing the Modernizr object created to implement placeholder functionality
function hasPlaceholderSupport() {
   var input = document.createElement('input');
   return ('placeholder' in input);
}

$(document).ready(function(){
    if(!Modernizr.input.placeholder){ 
        $('[placeholder]').focus(function() {
            var input = $(this);
            if (input.val() == input.attr('placeholder')) {
                input.val('');
                input.removeClass('placeholder');
            }
        }).blur(function() {
            var input = $(this);
            if (input.val() == '' || input.val() == input.attr('placeholder')) {
                input.addClass('placeholder');
                input.val(input.attr('placeholder'));
            }
        }).blur();
        $('[placeholder]').parents('form').submit(function() {
            $(this).find('[placeholder]').each(function() {
                var input = $(this);
                if (input.val() == input.attr('placeholder')) {
                    input.val('');
                }
            })
        });
    }
	$( 'a[href="#"]' ).click( function(e) {		
	   	e.preventDefault();
	});
});
