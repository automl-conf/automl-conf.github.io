const loadWidth = window.innerWidth;


function getAccordion(screen) {

    const breakpoint = screen;

    jQuery(window).resize(function ($) { 
        if((loadWidth < breakpoint && window.innerWidth >= breakpoint) || (loadWidth >= breakpoint && window.innerWidth < breakpoint))
        location.reload(); 
    });

    if (jQuery(window).width() < screen)  {
        var navTab = jQuery("#pills-tab"),
        tabContent = jQuery(".tab-content");
        // hiding the navtabs
        navTab.hide();
    // appending each link to respective tab-pane
    navTab.find("li").each(function(){
        var destination = jQuery(jQuery(this).find(".nav-link").attr("href"));
        var anchor = jQuery(this).find(".nav-link");
            // removing unused attributes and adding tabContent-toggler class
            anchor.removeAttr("data-toggle role aria-controls aria-selected").addClass("tabContent-toggler").insertBefore(destination);
        });
    var tabToggler = jQuery('.tabContent-toggler'),
    tabPane = tabContent.find(".tab-pane"),
    // get all classes in tab pane for further usage and replace tab-pane with empty data
    nonActiveTabPane = tabContent.find(".tab-pane:not(.active)").attr("class");
    tabPaneClass = tabPane.attr('class');
    tabPaneClass = tabPaneClass.replace(nonActiveTabPane,"");
    tabToggler.click(function(e){
        // get the destination of clicked element
        var destination = jQuery(jQuery(this).attr("href"));
        // if not this element then remove active class
        jQuery(this).parent().find(tabToggler).not(jQuery(this)).removeClass("active");
        //if not clicked destination then remove all other class except tab-pane
        jQuery(this).parent().find('.tab-pane').removeClass(tabPaneClass);
        // now toggle active class
        jQuery(this).toggleClass("active");
        // also toggle all other class in tab-pane
        destination.toggleClass(tabPaneClass);
        // if this element dont have active class then remove all other class from tab-pane
        if(!jQuery(this).hasClass("active")){
            destination.removeClass(tabPaneClass);
        }
        // first element of nested tab-pane should be active
        if(destination.has(tabToggler)){
            var tabTogglerFirstChild = destination.find(".tabContent-toggler:first-child"),
            tabTogglerFirstDestination = jQuery(tabTogglerFirstChild.attr("href"));
            tabTogglerFirstChild.addClass("active");
            tabTogglerFirstDestination.addClass(tabPaneClass);
        }
        // preventing default behaviour of element
        e.preventDefault();
    });
} 
}
// check if device is mobile and if so only run the function
jQuery(document).ready(function(){
    getAccordion(768);
});

jQuery(document).ready(function(){

    jQuery('.tabContent-toggler').on( 'click', function(){
        var id = jQuery(this).attr('href');
        jQuery('.tab-content-1 .tab-pane:first-of-type', jQuery(id)).tab('show');
    });
});
