# FullCalendar

A full-sized drag & drop event calendar (jQuery plugin).

- [Project website and demos](http://arshaw.com/fullcalendar/)
- [Documentation](http://arshaw.com/fullcalendar/docs/)
- [Support](http://arshaw.com/fullcalendar/support/)
- [Changelog](changelog.md)
- [License](license.txt)

For contributors:

- [Ways to contribute](http://arshaw.com/fullcalendar/wiki/Contributing/)
- [General coding guidelines](https://github.com/arshaw/fullcalendar/wiki/Contributing-Code)
- [Contributing features](https://github.com/arshaw/fullcalendar/wiki/Contributing-Features)
- [Contributing bugfixes](https://github.com/arshaw/fullcalendar/wiki/Contributing-Bugfixes)

Added ViewMore functionality by using lyconic fullcalendar.viewmore (https://github.com/lyconic/fullcalendar/tree/view-more).

Just call `limitEvents` with either of the following options :

        $('#calendar').limitEvents(2);
               or
        $('#calendar').limitEvents({
                maxEvents : 2
        });       
        
OR

        $('#calendar').limitEvents('height');
                        or
        $('#calendar').limitEvents({
                height  : true
        });
