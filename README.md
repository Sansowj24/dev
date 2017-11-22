<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta name="author" content="Parallelus" />
	<meta name="description" content="A brief description of this website or your business." />
	<meta name="keywords" content="keywords, or phrases, associated, with each page, are best" />
	<title>Unite - Together is Better (created by Parallelus)</title>
	
	<!-- Favorites icon -->
	<link rel="shortcut icon" href="http://para.llel.us/favicon.ico" />
	
	<!-- Style sheets -->
	<link rel="stylesheet" type="text/css" href="css/reset.min.css" />
	<link rel="stylesheet" type="text/css" href="css/menu.min.css" />
	<link rel="stylesheet" type="text/css" href="css/fancybox.css" />
	<link rel="stylesheet" type="text/css" href="css/tooltip.min.css" />
	<link rel="stylesheet" type="text/css" href="css/default.css" />
	
	<!-- jQuery framework and utilities -->
	<script type="text/javascript" src="js/jquery-1.4.min.js"></script>
	<script type="text/javascript" src="js/jquery-ui-1.7.2.min.js"></script>
	<script type="text/javascript" src="js/jquery.easing.1.3.min.js"></script>
	<script type="text/javascript" src="js/hoverIntent.min.js"></script>
	<script type="text/javascript" src="js/jquery.bgiframe.min.js"></script>
	<!-- Drop down menus -->
	<script type="text/javascript" src="js/superfish.min.js"></script>
	<script type="text/javascript" src="js/supersubs.min.js"></script>
	<!-- Tooltips -->
	<script type="text/javascript" src="js/jquery.cluetip.min.js"></script>
	<!-- Input labels -->
	<script type="text/javascript" src="js/jquery.overlabel.min.js"></script>
	<!-- Anchor tag scrolling effects -->
	<script type="text/javascript" src="js/jquery.scrollTo-min.js"></script>
	<script type="text/javascript" src="js/jquery.localscroll-min.js"></script>
	<!-- Inline popups/modal windows -->
	<script type="text/javascript" src="js/jquery.fancybox-1.2.6.pack.js"></script>		
	<!-- Font replacement (cufón) -->
	<script src="js/cufon-yui.js" type="text/javascript"></script>
	<script src="js/LiberationSans.font.js" type="text/javascript"></script>

	<!-- IE only includes (PNG Fix and other things for sucky browsers -->
	
	<!--[if lt IE 7]>
		<link rel="stylesheet" type="text/css" href="css/ie-only.css">
		<script type="text/javascript" src="js/pngFix.min.js"></script>
		<script type="text/javascript"> 
			$(document).ready(function(){ 
				$(document.body).supersleight();
			}); 
		</script> 
	<![endif]-->
	<!--[if IE]><link rel="stylesheet" type="text/css" href="css/ie-only-all-versions.css"><![endif]-->
	
	
	<!-- BEGIN: For Demo Only -->
		<!--			
		These entries are only needed for demo features, such as the real-time skin changer.
		They can be deleted for production installs without effecting the theme's design or 
		any of the funcionality.
		-->
		<script type="text/javascript" src="js/demo.js"></script>	
		<link rel="stylesheet" type="text/css" href="css/demo.css" />
	<!-- END: For Demo Only -->
	

	<!-- Functions to initialize after page load -->
	<script type="text/javascript" src="js/onLoad.min.js"></script>
	
	<!-- form validation scripts (for contact page) -->
	<script src="js/jquery.validate.min.js" type="text/javascript"></script>
	<script type="text/javascript">
		// initialize form validation
		$(document).ready(function() {
			$("#CommentForm").validate();
		});
	</script>
	
	
</head>
<body>

<!-- Top reveal (slides open, add class "topReveal" to links for open/close toggle ) -->
<div id="ContentPanel">

	<!-- close button -->
	<a href="#" class="topReveal closeBtn">Close</a>
	
	<div class="contentArea">

		<!-- New member registration -->
		<div class="right" style="margin:10px 0 0;">
			<h1>
				Not a member yet?
				<span>Register now and get started.</span>
			</h1>
			<button type="button">Register for an account</button>
		</div>
		
		<!-- Alternate Login -->				
		<div>
			<form class="loginForm" method="post" action="" style="height:auto;">
				<div id="loginBg"><img src="images/icons/lock-and-key-110.png" width="110" height="110" alt="lock and key" /></div>
				<h2 style="margin-top: 20px;">Sign in to your account.</h2>
				<fieldset>
					<legend>Account Login</legend>
					<p class="left" style="margin: 0 8px 0 0;">
						<label for="RevealUsername" class="overlabel">Username</label>
						<input id="RevealUsername" name="RevealUsername" type="text" class="loginInput textInput rounded" />
					</p>
					<p class="left" style="margin: 0 5px 0 0;">
						<label for="RevealPassword" class="overlabel">Password</label>
						<input id="RevealPassword" name="RevealPassword" type="password" class="loginInput textInput rounded" />
					</p>
					<p class="left" style="margin: -7px 0 0;">
						<button type="submit" class="btn" style="margin:0;"><span>Sign in</span></button>
					</p>
				</fieldset>
				<p class="left noMargin">
					<a href="#">Forgot your password?</a>
				</p>
			</form>		
		</div>
		
		<!-- End of Content -->
		<div class="clear"></div>
	
	</div>
</div>

<!-- Site Container -->
<div id="Wrapper">
	<div id="PageWrapper">
		<div class="pageTop"></div>
		<div id="Header">
		
			<!-- Main Menu -->
			<div id="MenuWrapper">
				<div id="MainMenu">
					<div id="MmLeft"></div>
					<div id="MmBody">
						
						<!-- Main Menu Links -->
						<ul class="sf-menu">
							<li class="current"><a href="index.html">Home</a></li>
							<li>
								<a href="#">Features</a>
								<ul>
									<li><a href="#">Home page</a>
										<ul>
											<li><a href="index.html">Home 1 (default)</a></li>
											<li><a href="index-2.html">Home 2 (CU3ER)</a></li>
											<li><a href="index-3.html">Home 3 (GalleryView)</a></li>
										</ul>
									</li>
									<li><a href="sample-portfolio.html">Portfolio</a></li>
									<li><a href="sample-blog.html">Blog</a></li>
									<li>
										<a href="sample-login.html" class="login">Login</a>
										<ul>
											<li><a href="sample-login.html" class="login">Style 1 (popup)</a></li>
											<li><a href="#ContentPanel" class="topReveal">Style 2 (slide)</a></li>
										</ul>
									</li>
									<li><a href="sample-text.html">Text Styles</a></li>
									<li><a href="theme-information.html">About the Theme</a></li>
								</ul>
							</li>
							<li>
								<a href="#">Skins</a>
								<ul>

									<li>
										<a href="#" onclick="switchSkin('1');">Skin 1</a>
										<ul>
											<li style="text-align:center;"><a href="#" onclick="switchSkin('1');"><img class="skin" src="images/content/skin-changer/skin-1.jpg" height="250" alt="Skin 1" /></a></li>
										</ul>
									</li>
									<li>
										<a href="#" onclick="switchSkin('2');">Skin 2</a>
										<ul>
											<li style="text-align:center;"><a href="#" onclick="switchSkin('2');"><img class="skin" src="images/content/skin-changer/skin-2.jpg" height="250" alt="Skin 2" /></a></li>
										</ul>
									</li>
									<li>
										<a href="#" onclick="switchSkin('3');">Skin 3</a>
										<ul>
											<li style="text-align:center;"><a href="#" onclick="switchSkin('3');"><img class="skin" src="images/content/skin-changer/skin-3.jpg" height="250" alt="Skin 3" /></a></li>
										</ul>
									</li>
									<li>
										<a href="#" onclick="switchSkin('4');">Skin 4</a>
										<ul>
											<li style="text-align:center;"><a href="#" onclick="switchSkin('4');"><img class="skin" src="images/content/skin-changer/skin-4.jpg" height="250" alt="Skin 4" /></a></li>
										</ul>
									</li>
									<li>
										<a href="#" onclick="switchSkin('5');">Skin 5</a>
										<ul>
											<li style="text-align:center;"><a href="#" onclick="switchSkin('5');"><img class="skin" src="images/content/skin-changer/skin-5.jpg" height="250" alt="Skin 5" /></a></li>
										</ul>
									</li>
								</ul>
							</li>
							<li>
								<a href="sample-layout.html">Layout</a>
								<ul>
									<li><a href="sample-layout.html">Default Page</a></li>
									<li><a href="sample-layout.html#full_page">Full Page</a></li>
									<li><a href="sample-layout.html#blog_page">Blog</a></li>
									<li><a href="sample-layout.html#multi_column_page">2 &amp; 3 Column</a></li>
								</ul>
							</li>	
							<li><a href="sample-contact.html">Contact</a></li>	
						</ul>
						
						<div class="mmDivider"></div>				
						
						<!-- Extra Menu Links -->
						<ul id="MmOtherLinks" class="sf-menu">
							<li>
								<a href="#"><span class="mmFeeds">Feeds</span></a>
								<ul>
									<li><a href="#"><span class="mmRSS">RSS</span></a></li>
									<li><a href="#"><span class="mmFacebook">Facebook</span></a></li>
									<li><a href="#"><span class="mmTwitter">Twitter</span></a></li>
								</ul>
							</li>
							<li><a href="sample-login.html" class="login"><span class="mmLogin">Login</span></a></li>
						</ul>
						
					</div>
					<div id="MmRight"></div>
				</div>
			</div>
			
			<!-- Search -->
			<div id="Search">
				<form action="#" id="SearchForm" method="post">
					<p style="margin:0;"><input type="text" name="SearchInput" id="SearchInput" value="" /></p>
					<p style="margin:0;"><input type="submit" name="SearchSubmit" id="SearchSubmit" class="noStyle" value="" /></p>
				</form>
			</div>
			
			<!-- Logo -->
			<div id="Logo">
				<a href="index.html"></a>
			</div>
			
			<!-- End of Content -->
			<div class="clear"></div>
		
		</div>
		
		<div class="pageMain">
			
			<div class="contentArea">
				<!-- Title / Page Headline -->
				<div class="full-page">
					<h1 class="headline"><strong>Text</strong> &nbsp;//&nbsp; Samples of text formatting options</h1>
				</div>
				
				<div class="hr"></div>

				<!-- Breadcrumbs -->
				<div class="full-page">
					<p class="breadcrumbs">
						<a href="index.html">Home</a> <span>&raquo;</span> <a href="#">Some Page</a> <span>&raquo;</span> <a href="#">Some Page</a> <span>&raquo;</span> This Page
					</p>
				</div>
				
				<!-- End of Content -->
				<div class="clear"></div>
			</div>
			
			<div class="contentArea">
				<div class="full-page">
				
					<!-- Text samples -->

					<h2 class="headline">Headings</h2>
					<div class="hr"></div>

					<p>
						Samples of the heading text for this theme: <code>&lt;h1&gt;</code>, <code>&lt;h2&gt;</code>, <code>&lt;h3&gt;</code>, <code>&lt;h4&gt;</code>, <code>&lt;h5&gt;</code>, <code>&lt;h6&gt;</code>
					</p>
					<div style="padding: 15px 35px;">
						<h1>This is a Heading 1 Element</h1>
						<h2>This is a Heading 2 Element</h2>
						<h3>This is a Heading 3 Element</h3>
						<h4>This is a Heading 4 Element</h4>
						<h5>This is a Heading 5 Element</h5>
						<h6>This is a Heading 6 Element</h6>
					</div>
					
					<br />
					<h2 class="headline">Headlines / Page Titles</h2>
					<div class="hr"></div>
					<p>
						Headlines are a different color than standard headings and can be assigned to any H1-H6 tag using <code>class="headline"</code>.
						To create a highlight, place <code>&lt;strong&gt;</code> tags around the words to be highlighted.
					</p>
					
					<div style="padding: 15px 35px;">
						<h1 class="headline">This headline has a <strong>highlight</strong> in it.</h1>
						<code>&lt;h1 class="headline"&gt;This headline has a &lt;strong&gt;highlight&lt;/strong&gt; in it.&lt;/h1&gt;</code>
					</div>
						
					<br />
					<h2 class="headline">Sub-Headings</h2>
					<div class="hr"></div>
					<p>
						Add a sub-heading to any H1-H6 tag using <code>&lt;span&gt;</code> tag.
					</p>
					
					<div style="padding: 15px 35px;">
						<h1>
							Heading Text
							<span>This is a sub-heading</span>
						</h1>
												
						<code>&lt;h1&gt;Heading Text&lt;span&gt;This is a sub-heading&lt;/span&gt;&lt;/h1&gt;</code>
					</div>

					<!-- End of Content -->
					<div class="clear"></div>
					
				</div>
				
				<!-- End of Content -->
				<div class="clear"></div>
					
				<!-- Title / Page Headline -->
				<div class="full-page">
					<br />
					<h2 class="headline">List Styles</h2>
					<div class="hr"></div>
				</div>
				
				<!-- End of Content -->
				<div class="clear"></div>
									
				<div class="half-page">
					
					<h4>Bulleted Lists</h4>
					<p>The following styles for bulleted lists are available. Add the class name associated with a bullet to the UL tag for your list to use the desired style.</p>
					<ul class="bullet-check">
						<li>Check mark</li> 
						<li><code>&lt;ul class="<strong>bullet-check</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-black">
						<li>Black</li> 
						<li><code>&lt;ul class="<strong>bullet-black</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-gray">
						<li>Gray (defalut if no class entered)</li> 
						<li><code>&lt;ul class="<strong>bullet-gray</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-silver">
						<li>Silver</li> 
						<li><code>&lt;ul class="<strong>bullet-silver</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-blue">
						<li>Blue</li> 
						<li><code>&lt;ul class="<strong>bullet-blue</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-green">
						<li>Green</li> 
						<li><code>&lt;ul class="<strong>bullet-green</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-orange">
						<li>Orange</li> 
						<li><code>&lt;ul class="<strong>bullet-orange</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-red">
						<li>Red</li> 
						<li><code>&lt;ul class="<strong>bullet-red</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-disc-black">
						<li>Disc Black</li> 
						<li><code>&lt;ul class="<strong>bullet-disc-black</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-disc-gray">
						<li>Disc Gray</li> 
						<li><code>&lt;ul class="<strong>bullet-disc-gray</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-disc-silver">
						<li>Disc Silver</li> 
						<li><code>&lt;ul class="<strong>bullet-disc-silver</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-disc-blue">
						<li>Disc Blue</li> 
						<li><code>&lt;ul class="<strong>bullet-disc-blue</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-disc-green">
						<li>Disc Green</li> 
						<li><code>&lt;ul class="<strong>bullet-disc-green</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-disc-orange">
						<li>Disc Orange</li> 
						<li><code>&lt;ul class="<strong>bullet-disc-orange</strong>"&gt;</code></li>
					</ul>
					<ul class="bullet-disc-red">
						<li>Disc Red</li> 
						<li><code>&lt;ul class="<strong>bullet-disc-red</strong>"&gt;</code></li>
					</ul>
					
					<!-- End of Content -->
					<div class="clear"></div>					
				
				</div>
							
				<div class="half-page">
					<h4>Numbered Lists</h4>
					<p>Choose from the following numbered list styles.</p>
					<ol class="number-pad">
						<li>Numbered item <code>&lt;ol class="<strong>number-pad</strong>"&gt;</code></li>
						<li>Numbered item</li>
						<li>Numbered item</li>
						<li>Numbered item</li>
						<li>Numbered item</li>
					</ol>
					<ol>
						<li>Numbered item (defalut, no class)</li>
						<li>Numbered item</li>
						<li>Numbered item</li>
						<li>Numbered item</li>
						<li>Numbered item</li>
					</ol>

					<h4>Custom Lists</h4>
					<p>
						A custom list style for displaying previews of news or blog posts. <br />
						<code>&lt;ul class="<strong>post-list</strong>"&gt;</code>.
					</p>
					<ul class="post-list" style="width: 300px;">
						<li>
							<img src="images/content/placeholder_48x48.png" width="48" height="48" alt="Recent News" />
							<a href="#">News/Blog Posts List</a>
							<p>This can include information such as a title, date, image and short description.</p>
						</li>
						<li>
							<img src="images/content/placeholder_48x48.png" width="48" height="48" alt="Recent News" />
							<a href="#">News/Blog Posts List</a>
							<p>This can include information such as a title, date, image and short description.</p>
						</li>
						<li>
							<img src="images/content/placeholder_48x48.png" width="48" height="48" alt="Recent News" />
							<a href="#">News/Blog Posts List</a>
							<p>This can include information such as a title, date, image and short description.</p>
						</li>
					</ul>
					<p>The "post-list" style can include the following HTML elements: <code>IMG</code>, <code>A</code>, <code>P</code>. Below is a sample implementation of the style.</p>
<pre>
&lt;ul class="post-list"&gt;
&lt;li&gt;
	&lt;img src="image.jpg" /&gt;
	&lt;a href="#"&gt;Title&lt;/a&gt;
	&lt;p&gt;Description text for this entry.&lt;/p&gt;
&lt;/li&gt;
&lt;li&gt;
	&lt;img src="image.jpg" /&gt;
	&lt;a href="#"&gt;Title&lt;/a&gt;
	&lt;p&gt;Description text for this entry.&lt;/p&gt;
&lt;/li&gt;
&lt;li&gt;
	&lt;img src="image.jpg" /&gt;
	&lt;a href="#"&gt;Title&lt;/a&gt;
	&lt;p&gt;Description text for this entry.&lt;/p&gt;
&lt;/li&gt;
&lt;/ul&gt;
</pre>
					<!-- End of Content -->
					<div class="clear"></div>
					
				</div>

				<!-- End of Content -->
				<div class="clear"></div>

			</div>
			<div class="contentArea">
				<div class="full-page">
					
					<br />
					<h2 class="headline">Blockquote</h2>
					<div class="hr"></div>

					<blockquote>
						<div>This is the default blockquote style applied to this theme's <code>&lt;blockquote&gt;</code> tags. Each skin has a custom color for the blockquote style. You can also create your own custom styles to match any skin using the following code in your stylesheet:</div>
						
<pre style="margin-top:8px;">
blockquote {
	border-color: [your color];
}
</pre>
					</blockquote>

					<br />
					<h2 class="headline">Other Text</h2>
					<div class="hr"></div>

					<h4>Paragraph text sample:</h4>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In pretium, leo ac hendrerit vulputate, libero libero congue ipsum, nec consectetur nunc arcu in tortor. Phasellus eu cursus nunc. Duis eros nulla, mollis eu molestie id, commodo gravida massa. Nullam mollis, nisl nec sodales hendrerit, diam nunc auctor arcu, eget suscipit lectus metus nec lacus.</p>
<p>Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Suspendisse nibh tortor, aliquet vel pellentesque ac, interdum non mauris. Donec est eros, fringilla vitae commodo non, pretium vel tortor. Quisque sed elit mi. Sed tortor nunc, egestas eu suscipit sed, faucibus a nisl. Praesent eros orci, viverra vitae vestibulum quis, luctus feugiat ipsum.</p>
<p>Nullam tristique nunc quis ante dapibus vel tincidunt turpis ornare. Nullam ante arcu, viverra ac rhoncus id, pretium eget magna. Aliquam quis massa urna, accumsan pellentesque sapien. </p>
					<br />

					<h4>Abbreviation, acronym, cite, delete, insert...</h4>
					
					<table cellpadding="0" cellspacing="0">
						<tr>
							<td style="padding: 3px 8px 3px 0;"><abbr>abbr</abbr></td>
							<td style="padding: 3px 8px 3px 0;"><code>&lt;abbr&gt;</code></td>
						</tr>
						<tr>
							<td style="padding: 3px 8px 3px 0;"><acronym>a.c.r.o.n.y.m</acronym></td>
							<td style="padding: 3px 8px 3px 0;"><code>&lt;acronym&gt;</code></td>
						</tr>
						<tr>
							<td style="padding: 3px 8px 3px 0;"><cite>This is cited.</cite></td>
							<td style="padding: 3px 8px 3px 0;"><code>&lt;cite&gt;</code></td>
						</tr>
						<tr>
							<td style="padding: 3px 8px 3px 0;"><del>Deleted text</del></td>
							<td style="padding: 3px 8px 3px 0;"><code>&lt;del&gt;</code></td>
						</tr>
						<tr>
							<td style="padding: 3px 8px 3px 0;"><ins>Inserted text</ins></td>
							<td style="padding: 3px 8px 3px 0;"><code>&lt;ins&gt;</code></td>
						</tr>
						<tr>
							<td style="padding: 3px 8px 3px 0;"><dfn>This is a definition.</dfn></td>
							<td style="padding: 3px 8px 3px 0;"><code>&lt;dfn&gt;</code></td>
						</tr>
						<tr>
							<td style="padding: 3px 8px 3px 0;"><em>With emphysis</em></td>
							<td style="padding: 3px 8px 3px 0;"><code>&lt;em&gt;</code></td>
						</tr>
						<tr>
							<td style="padding: 3px 8px 3px 0;"><strong>Strong (bold)</strong></td>
							<td style="padding: 3px 8px 3px 0;"><code>&lt;strong&gt;</code></td>
						</tr>
						<tr>
							<td style="padding: 3px 8px 3px 0;"><code>Code text sample</code></td>
							<td style="padding: 3px 8px 3px 0;"><code>&lt;code&gt;</code></td>
						</tr>
					</table>
					<p><br /></p>

					<h4>Predefined text:</h4>
<pre style="width: 400px;">
This is predefined text with custom spacing and tabs.

body {
	margin: 0;
	padding: 0;
	background: none;
	font-style: normal;
	color: #000;
}
</pre> 


					<p><br /></p>
					<h4>Table layout:</h4>
					<table cellspacing="0" cellpadding="0" id="FeatureMatrix">
						<tbody>
							<tr>
								<th id="MatrixItems">&nbsp;</th>
								<th class="matrixColumn">
									<h6>Column Title</h6>
									<p><a href="#">Column Link</a></p>
								</th>
								<th class="matrixColumn">
									<h6>Column Title</h6>
									<p><a href="#">Column Link</a></p>
								</th>
								<th class="matrixColumn">
									<h6>Column Title</h6>
									<p><a href="#">Column Link</a></p>
								</th>
								<th class="matrixColumn">
									<h6>Column Title</h6>
									<p><a href="#">Column Link</a></p>
								</th>
							</tr>
							<tr>
								<td class="matrixItem">Item</td>
								<td class="matrixOdd">value / option</td>
								<td class="matrixEven">value / option</td>
								<td class="matrixOdd">value / option</td>
								<td class="matrixEven">value / option</td>
							</tr>
							<tr>
								<td class="matrixItem">Item</td>
								<td class="matrixOdd">value / option</td>
								<td class="matrixEven">value / option</td>
								<td class="matrixOdd">value / option</td>
								<td class="matrixEven">value / option</td>
							</tr>
							<tr>
								<td class="matrixItem">Item</td>
								<td class="matrixOdd">value / option</td>
								<td class="matrixEven">value / option</td>
								<td class="matrixOdd">value / option</td>
								<td class="matrixEven">value / option</td>
							</tr>
							<tr>
								<td class="matrixItem">Item</td>
								<td class="matrixOdd">value / option</td>
								<td class="matrixEven">value / option</td>
								<td class="matrixOdd">value / option</td>
								<td class="matrixEven">value / option</td>
							</tr>
							<tr>
								<td class="matrixItem last">Item</td>
								<td class="matrixOdd checkMark last">&nbsp;</td>
								<td class="matrixEven checkMark last">&nbsp;</td>
								<td class="matrixOdd checkMark last">&nbsp;</td>
								<td class="matrixEven checkMark last">&nbsp;</td>
							</tr>
						</tbody>
					</table>

					<br />
					
					<!-- End of Content -->
					<div class="clear"></div>					
				
				</div>
				
			</div>
			
		</div>
		
		<!-- Footer -->
		<div id="Footer">
			<div id="FooterTop"></div>
			<div id="FooterContent">
			
				<div class="contentArea">
				
					<!-- Column 1 -->
					<div class="one-third">
						<h3>Design Details</h3>
						<p>Ceated by <a href="http://para.llel.us">Parallelus</a> and available for purchase on <a href="http://themeforest.net/user/Parallelus/portfolio">ThemeForest</a>.</p>
					</div>

					<!-- Column 2 -->
					<div class="one-third">
						<h3>Stay Connected</h3>
						<ul class="horizList">
							<li><a href="#"><img src="images/icons/social/delicious.png" width="40" height="40" alt="Delicious" /></a></li>
							<li><a href="#"><img src="images/icons/social/flickr.png" width="40" height="40" alt="Flickr" /></a></li>
							<li><a href="#"><img src="images/icons/social/linkedin.png" width="40" height="40" alt="LinkedIn" /></a></li>
							<li><a href="#"><img src="images/icons/social/skype.png" width="40" height="40" alt="Skype" /></a></li>
							<li><a href="#"><img src="images/icons/social/twitter.png" width="40" height="40" alt="Twitter" /></a></li>
							<li><a href="#"><img src="images/icons/social/yahoo.png" width="40" height="40" alt="Yahoo!" /></a></li>
						</ul>
						<p>Keep track of Unite on all your favorite social networks.</p>
					</div>

					<!-- Column 3 -->
					<div class="one-third last">
						<h3>Contact Information</h3>
						<div class="logoMark"></div>
						<p>
							(555) 443.3221<br />
							contact@unite-inc.com<br />
							<a href="#">www.unite-inc.com</a><br />
						</p>
					</div>
					
					<!-- End of Content -->
					<div class="clear"></div>
	
				</div>
					
			</div>
			<div id="FooterBottom"></div>
			
		</div>
		
		<!-- Copyright/legal text -->
		<div id="Copyright">
			<p>
				Copyright &copy; 2010 - <a href="http://para.llel.us" onclick="window.open(this.href); return false;">Parallelus</a> - All rights reserved. 
				Conforms to W3C Standard 
				<a href="http://validator.w3.org/check?uri=referer" onclick="window.open(this.href); return false;">XHTML</a> &amp; 
				<a href="http://jigsaw.w3.org/css-validator/check/referer?profile=css3" onclick="window.open(this.href); return false;">CSS</a>
			</p>
		</div>
		
	</div>
</div>

<!-- Activate Font Replacement (cufón) -->
<script type="text/javascript"> Cufon.now(); </script>
</body>
</html>
