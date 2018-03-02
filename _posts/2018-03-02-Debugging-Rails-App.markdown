- <h4>Three ways to do:</h4>
	<% debug @article %><br>
	<% simple_format @article.to_yaml %><br>
	<% [].inspect %> //useful will arrays<br>

<b>Logger levels:</b> :debug, :info, :warn, :error, :fatal, :unknown<br>
<b>Class: ActiveSupport::Logger</b><br>
<b>Rails displays log if the log level is higher or equal to the configured log level.</b><br>
Use <b>"Rails.logger.level"</b> to know the current log level.<br>
Use <b>"Rails.logger.level = 1" </b>to set the log level.<br>
"logger.debug 'debug message' ", "@variable.inspect" --> in Controller, Model, View, Mailer<br>

- <h4>gem byebug (gem install byebug)</h4>
	<b>next:</b> next line <br>
	<b>step:</b> like next but go inside methods<br>
	<b>help var </b>--> display hepl<br>
	<b>help set</b> --> settings<br>
	<b>instance_variable:</b> see all available instance variable<br>
	<b>var local:</b> see local variables<br>
	<b>var instance [Oject].new:</b> inspect for an oject method<br>
	<b>display [@variable]:</b> <br>
	<b>break [n]:</b> <br>
	<b>info breakpoints:</b> list all breakpoints<br>
	<b>delete[n]:</b> delete breakpoint n<br>
	<b>continue:</b> resume execution bypass all the breakpoints<br>
