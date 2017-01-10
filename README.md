# slideToggle

`    $('.content').hide();
$('.title').click(function(e){
  var id = this.id;
  var opened = $(this).hasClass('clicked');
  e.preventDefault();
  $('.clicked').removeClass('clicked');
  $('.content').slideUp();
               
  if(!opened){
    //$(this).removeClass('clicked');
    $(this).addClass('clicked');
    $('.content.'+ id).slideDown();
    //console.log('fired');
`    }  
`    }) 