# ITSM-Dashboard
A comprehensive IT service management dashboard to provide great visual analytics to your organization

## _*Note that this is a work in progress, we are currently converting proprietary code into open source. It might not be usable yet. We will remove this notice once the dashboard is usable.*_

### Background
This tool was written when we were working for L2 operations and productions support. After completing the ITIL Foundations certification and realizing the potential for graphical representation of ticket statistics, instead of drab, text based ones, we pumped this tool full of colorful graphs and pleasent interfaces, basing it on the most impactful design framework of that time - Google's Material Design.

### What is (rather, will be) included
We will provide the database schema and sample data for the working of the tool, the web frontend, and the Java backend. 
Eventual plans of providing a Python Flask backend is also in the works.

### Technology
A lot of this was written with HTML5, CSS3, and jQuery. Backend is a nicely modular Java Servlet returning JSON via web services, that is then collected by AJAX by the frontend, and then rendered on to the HTML page. Database is MySQL. The pages, the widgets, everything is responsive and ready to be deployed on any device of your choosing.

### Credits
We have used a LOT of Javascript frameworks, let me list out:
* [Bootstrap 3](http://getbootstrap.com/) - come on, isn't it obvious?
* [Materialize](http://materializecss.com/) - for cues
* [HighCharts](http://highcharts.com/) - for graphing the more complex parts
* [DataTables + plugins](https://www.datatables.net/) - to make tables on pages searchable, sortable, exportable, and what not
* [GSON](https://github.com/google/gson/) - to convert result sets to JSON and back
* [AnimateCSS](https://github.com/daneden/animate.css/)
* [FullCalendar](http://fullcalendar.io/)
* [SweetAlert2](https://github.com/limonte/sweetalert2)
* Various other small Bootstrap plugins like Growl, DateTimePicker, BootGrid, EasyPieChart,flotCharts,NiceScroll,Sparklines.
