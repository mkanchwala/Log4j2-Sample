# Log4j2 - Apache Log4j Sample Application

Sample Project to show the capability on log4j and log4j2

	Run : com.mkanchwala.loggers.main.LogApp

and enter a number.

Also Remember to change the properties in the log4j2.xml

	   <Property name="log-path">C:/logs/</Property>
		<Property name="log-project-name">sample</Property>
		<Property name="log-pattern">%d{ISO8601} %-5p [Sample][%t|%c{1}] %L %M %m\n</Property>
		<Property name="rollover-strategy-max">7</Property>
		<Property name="rolling-size-based">1 MB</Property>

 you can configure it according to your needs.
 
 It'll create three Rolling files i.e. Info, Debug and Error at your specified log-path location prefixed by your project name.