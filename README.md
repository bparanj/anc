Site wide announcement using jQuery in Rails 5. This sample Rails 5 app displays site wide announcement and auto hides the announcement after specified number of seconds. You can change the default 5 seconds used in auto hiding in application layout file by replacing 5000 with let's say 10000 for 10 seconds delay:

$('#announcement').delay(5000).fadeOut('slow');


