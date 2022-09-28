# Colors 

```
	source("one.R");
	github.install("humanVerse");
	method1 = colors.getList("R-657");
	method2 = data.get("humanVerse/kdlsj.pipe.txt");
```

{{< rawhtml >}}
<DIV>
<TABLE>
	<THEAD>
	<TR>
		<TH valign="top" align="center">Wikipedia Link</TH>			
		<TH valign="top" align="center">Description</TH>
		<TH valign="top" align="center">Color Library</TH>	
	</TR>
	</THEAD>
	<TBODY>
	<TR>
		<TH colspan=3>
		I developed a <a href="http://colors.mshaffer.com">COLOR PICKER TOOL</a> to make it easier for me to select harmonious colors based on the mathematics of the color wheel.  Most of the conversion tools I have written in the *humanVerse* library were ported from the javascript code I used on this website.  I have developed several color-helper functions in the *humanVerse* anchored to BASE-R with my knowledge of color uses.  One important feature is the ability for you to create your own named lists of colors to use.
		</TH>
	</TR>
	<TR>
		<TH valign="top" align="center"><a href="https://en.wikipedia.org/wiki/R_(programming_language)">R</a></TH>
		<TD valign="top" align="left">
			R uses the <a href="https://en.wikipedia.org/wiki/RGBA_color_model">RGBa</a> color model to drive colors within the system (mainly used for plotting).  They use the formulas derived from <a href="http://www.brucelindbloom.com/index.html?Eqn_RGB_to_XYZ.html">Bruce</a> to do the conversions.  For print and other purposes, these other colors may have applications (e.g., CMYK for printing).  By default, HEXCOLORS and RGB with (alpha) are sufficient as conversion tools are readily available. 
		</TD>	
		<TH valign="top" align="center"><a href="https://raw.githubusercontent.com/MonteShaffer/humanVerse.data/main/-colors-/COLORS_R-657.txt">R-657</a></TH>
	</TR>
	
	<TR>
		<TH valign="top" align="center"><a href="https://en.wikipedia.org/wiki/ANSI_escape_code#8-bit">ANSI terminal</a></TH>
		<TD valign="top" align="left">
			ANSI sequences were introduced in the 1970s and became widespread  by the early 1980s. ESC codes bring color to the terminal environment.  The original specification only had 8 colors.
		</TD>	
		<TH valign="top" align="center"><a href="https://raw.githubusercontent.com/MonteShaffer/humanVerse.data/main/-colors-/COLORS_ANSI-256.txt">ANSI-256</a></TH>
	</TR>
	<TR>
		<TH valign="top" align="center"><a href="https://en.wikipedia.org/wiki/Web_colors#Web-safe_colors">Web safe</a></TH>
		<TD valign="top" align="left">
			In the mid-1990s, many displays were only capable of displaying 256 colors.There were various attempts to make a "standard" color palette. A palette of 216 was chosen (6 * 6 * 6 = 216):  six equally spaced shades of red, green, and blue (mod 151?), each from 00 to FF.
		</TD>	
		<TH valign="top" align="center"><a href="https://raw.githubusercontent.com/MonteShaffer/humanVerse.data/main/-colors-/COLORS_WEB-216.txt">WEB-216</a></TH>
	</TR>
	<TR>
		<TH valign="top" align="center"><a href="https://en.wikipedia.org/wiki/X11_color_names#Color_name_chart">X11 color</a></TH>
		<TD valign="top" align="left">
			The first versions of Mosaic and Netscape Navigator used the X11 colors as the basis for the web colors list, as both were originally X applications. The W3C specifications SVG and CSS level 3 module Color eventually adopted the X11 list with some changes. The present W3C list is a superset of the 16 "VGA colors" defined in HTML 3.2 and CSS level 1.
		</TD>	
		<TH valign="top" align="center"><a href="https://raw.githubusercontent.com/MonteShaffer/humanVerse.data/main/-colors-/COLORS_X11-141.txt">X11-141</a></TH>
	</TR>
	<TR>
		<TH valign="top" align="center"><a href="https://en.wikipedia.org/wiki/Web_colors#Basic_colors">HTML 16</a></TH>
		<TD valign="top" align="left">
			The basic colors are 16 colors defined in the HTML 4.01 specification, ratified in 1999.
		</TD>	
		<TH valign="top" align="center"><a href="https://raw.githubusercontent.com/MonteShaffer/humanVerse.data/main/-colors-/COLORS_HTML-16.txt">HTML-16</a></TH>
	</TR>
	<TR>
		<TH valign="top" align="center"><a href="https://en.wikipedia.org/wiki/List_of_software_palettes">HTML 8</a></TH>
		<TD valign="top" align="left">
			The webcolors used on the web before HTML 4 in 1999. 
		</TD>	
		<TH valign="top" align="center"><a href="https://raw.githubusercontent.com/MonteShaffer/humanVerse.data/main/-colors-/COLORS_HTML-8.txt">HTML-8</a></TH>
	</TR>
	<TR>
		<TD align="left" valign="top" colspan=3>
		<B><U>DATA SOURCES:</U></B>
		<ul>
			<li>http://colors.mshaffer.com</li>
			<li>http://c.mshaffer.com/js/colorpicker/colorpicker.colors.js</li>
			<li>http://www.calmar.ws/vim/256-xterm-24bit-rgb-color-chart.html</li>
		</ul>
		<B><U>SOURCES TO GET HTML TO RENDER ON GITHUB:</U></B>
		<ul>
			<li>http://cerebrumcontorquet.debun.nl/brainwaves/tablecheck/index.php</li>
			<li>https://metacpan.org/dist/perl/view/pod/perlpod.pod</li>
		</ul>
		</TD>
	</TR>
	</TBODY>
</TABLE>
</DIV>
{{< /rawhtml >}}

