# Tinyweb with Perl
<p><b><i>How to start Perl with TinyWeb</i></b></p>
<ol>
<li>Execute the <b><tt>run.bat</tt></b> batch file located in the root. This will start the webserver on port 8765 using local IP address 127.0.0.1, and will launch this web page. (If the URL of this page starts with <tt>http:</tt> you have already done that.)</li>

</ol>

<p><b><i>How to stop Perl with TinyWeb</i></b></p>
<ol>
<li>Simply quit the browser.</li>
<li>If you want to stop the TinyWeb webserver, run the Windows Task Manager and end the <tt>tinyweb.exe</tt> process.</li>
<li>Important!! You must shutdown TinyWeb with Task Manager if you want to start another instance. Else it is tell you "Forbidden"</li>
</ol>
<p><b><i>Notes and limitations:</i></b></p>
<ul>
<li>TinyWeb: TinyWeb is a small, simple and fast Win32 webserver daemon. It is Copyright (C) 2000 <a href="http://www.ritlabs.com/en/products/tinyweb/">RITLABS S.R.L.</a>. A modified version of TinyWeb is used so that TWiki can be run without any registry changes. The source code is included in the <tt>twiki/tinyweb/Src.zip</tt>; it requires the Delphi Pascal compiler. TinyWeb is distributed under a <a href="http://www.ritlabs.com/en/products/tinyweb/licence.txt">free license</a>.</li>
<li>Perl: The perl compiler of <a href="http://www.indigostar.com/indigoperl.htm">IndigoPerl</a> is distributed with this TWiki. The source can be obtained from their website. Perl is distributed under the <a href="http://perldoc.perl.org/perlartistic.html">Artistic License</a>.</li>
</ul>

<p><b><i>Directory tree:</i></b></p>
<pre>
    +                   -- root: Autorun.inf
      + www             -- package root: Readme.txt, run.bat
      + htdocs          -- hypertext document root
        + cgi-bin       -- cgi-bin directory
        + pub           -- TWiki attachments
      + logs            -- TinyWeb webserver logs
      + perl            -- Perl from IndigoPerl distribution
        + bin           -- Perl executables
        + lib           -- Perl libraries
      + tinyweb         -- TinyWeb webserver executable and source
</pre> 
<h1>Based on the work done for TWiki by Peter Theony<h1>
<p>-- <a href="http://twiki.org/cgi-bin/view/Main/PeterThoeny">Peter Thoeny</a> - <a href="http://twiki.org/">TWiki.org</a> - <a href="http://www.structuredwikis.com/">StructuredWikis.com</a> - 2006-12-27</p>
