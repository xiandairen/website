$(document).ready(function(){
     var pageH = $(document).height()
     var pageW = $(document).height();
     $(".wrap").css({height:pageH})

    $(".carousel-txt-list li").click(function(){
        var i = $(this).index();
        $(".carousel-img li").each(function(){
            $(this).hide();
            if($(this).index() == i){
                $(this).show()
            }
        })
    })

    $(".search-msg-login").each(function(){
        var i = $(this).index();
        $(this).click(function(){
            if(i == 1){
            $(".search-box").animate({
                opacity: 'show'
               },500)
            }
        })
    })


    function move(itag,afterEle){
        $(itag).hover(function(){
            var that = $(this);
            var nextEle = that.prev();


        },function(){

        })
    }



})