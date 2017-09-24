<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' expr:class='&quot;v2 sevidahtml &quot; + data:blog.mobileClass + &quot; &quot; + data:blog.languageDirection' expr:dir='data:blog.languageDirection' id='sevidahtml' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr' xmlns:og='http://ogp.me/ns#'>
<head>
<meta content='width=device-width,initial-scale=1' name='viewport'/>
<b:include data='blog' name='all-head-content'/>
<title>
  <b:if cond='data:blog.pageType == &quot;index&quot;'>
    <data:blog.pageTitle/>
  <b:elseif cond='data:blog.pageType != &quot;error_page&quot;'/> 
    <data:blog.pageName/> | <data:blog.title/>
  <b:else/>
	404 | <data:blog.title/> 
  </b:if>
</title>
<b:if cond='data:blog.metaDescription != &quot;&quot;'>
<meta expr:content='data:blog.metaDescription' property='og:description'/>
<meta expr:content='data:blog.metaDescription' name='twitter:description'/>
<meta expr:content='data:blog.metaDescription' itemprop='description'/>
</b:if>
<b:if cond='data:blog.postImageUrl or data:blog.postImageThumbnailUrl'>
<meta expr:content='(data:blog.postImageUrl ? data:blog.postImageUrl : data:blog.postImageThumbnailUrl)' property='og:image'/>
<meta expr:content='(data:blog.postImageUrl ? data:blog.postImageUrl : data:blog.postImageThumbnailUrl)' name='twitter:image'/>
<meta expr:content='(data:blog.postImageUrl ? data:blog.postImageUrl : data:blog.postImageThumbnailUrl)' itemprop='image'/>
</b:if>
<meta content='Kuna Patra, Kuna, Patra, Dj, VFX, GFX, Joke, Sms, Sad, Hindi, One line, Status, DJ Kuna' name='keywords'/>
<!-- Metadata Facebook -->
<meta expr:content='data:blog.title' property='og:site_name'/>
<meta expr:content='data:blog.pageTitle' property='og:title'/>
<meta content='article' property='og:type'/>
<meta expr:content='data:blog.url' property='og:url'/>
<meta content='100002549773049' property='fb:admins'/>
<!-- Metadata Twitter -->
<meta name='twitter:card' value='summary'/>
<meta expr:content='data:blog.pageTitle' name='twitter:title'/>
<meta content='@publisher_handle' name='twitter:site'/>
<meta content='@author_handle' name='twitter:creator'/>
<!-- Schema.org markup for Google+ -->
<meta expr:content='data:blog.pageTitle' itemprop='name'/>
 <!--[if lt IE 9]>
<script src="http://css3-mediaqueries-js.googlecode.com/svn/trunk/css3-mediaqueries.js"></script>
<![endif]-->
<b:template-skin>
<b:variable default='960px' name='content.width' type='length' value='960px'/>
<b:variable default='0px' name='main.column.left.width' type='length' value='0px'/>
<b:variable default='342px' name='main.column.right.width' type='length' value='342px'/>
<b:variable default='left' name='startSide' type='automatic'/>
<b:variable default='right' name='endSide' type='automatic'/>
<![CDATA[
.container{min-width:$(content.width)}
.main-wrapper{padding-$(endSide):$(main.column.right.width);padding-$(startSide):$(main.column.left.width)}
.rtl .main-wrapper{padding-$(startSide):$(main.column.right.width);padding-$(endSide):$(main.column.left.width)}
.sidebar-right,.sidebar-right > .innerwrap{width:$(main.column.right.width)}
.sidebar-left,.sidebar-left > .innerwrap{width:$(main.column.left.width);overflow:hidden}
.left-post .main-wrapper{padding-right:$(main.column.right.width);padding-left:$(main.column.left.width)}
.right-post .main-wrapper{padding-left:$(main.column.right.width);padding-right:$(main.column.left.width)}
.left-side .main-wrapper{padding-right:0;padding-left:$(main.column.right.width)}
.right-side .main-wrapper{padding-left:0;padding-right:$(main.column.right.width)}
#layout{height:auto}
#layout .homepost .HTML{visibility:visible}
#layout .admin.row{margin:10px 15px 0;padding:15px 0}
#layout .admin.row div.widget{width:31.333333%;margin:0 1% 3px}
#layout .container .section,#layout #gadsmain-file1{background-color:transparent;border:0;padding:0;margin-bottom:8px}
#layout .middle-header .topads,#layout .top-header .section,#layout .links-submenu .section,#layout .admin.row div.widget,#layout .bottom-section-area > div,#layout .middle-header .header,#layout .footer{float:$(startSide)}
#layout .middle-header .topads,#layout .top-header .section,#layout .middle-header .header,#layout .main-bottom-area1 > div > .section{width:49%;margin:0;margin-right:2%}
#layout #top-social-sec,#layout #topads,#layout #links-sub4,#layout #footer4,#layout .main-bottom-area1 > div > .section.main-column-right{margin-right:0}
#layout .top-header,#layout .bottom-header{height:auto}
#layout .links-submenu .section,#layout .wrap .footer{width:23.5%;margin:0;margin-right:2%;margin-bottom:10px}
#layout .topnav,body#layout .topads{height:auto}
#layout .head-wrap{padding:0;display:block}
#layout .header-wrap{padding:5px 0;background-color:#258A60;margin:0 15px}
#layout .header,#layout .topads,#layout .author-profile-area,#layout .links-submenu,#layout .bottom-section-area,#layout .gads-mainfile,#layout .blogpost-setting{display:block}
#layout .homepost .HTML{visibility:visible}
#layout .FollowByEmail .widget-content:before{content:""}
#layout .admin.row{background-color:#035B92}
#layout .admin.row > div:before,#layout .footer-area:before,#layout #main-top:before,#layout .main-bottom-area1:before,#layout #sidebar-wrapper .innerwrap:before,#layout #sidebartabs:before,#layout .topfeatured-area .wrap:before,#layout .middle-big:before,#layout .author-profile-area:before,#layout .author-profile-area:before,#layout .links-submenu:before,#layout .manual-image-area:before{color:#FFF;font-size:30px;margin-bottom:15px;display:block}
#layout .admin.row > div:before{content:"Theme Options"}
#layout .header .widget{max-width:none}
#layout .outer-nav{position:static;background-color:#2B6D09;margin:0 15px 15px;padding:15px 0 10px}
#layout .srcnavbutton,#layout .posts-title,#layout .copyright-area,#layout .hidden-contact,#layout .unwanted,#layout .contact-sec,#layout .top-date,#layout .section > h4{display:none!important}
#layout a.editlink{background-color:#1446ac;padding:0 10px;color:#fff!important;right:0;bottom:0}
#layout #sidebar-wrapper{overflow:visible;position:static;width:40%;margin:0;float:$(endSide)}
#layout #sidebar-wrapper .innerwrap,#layout #sidebartabs,#layout #main-top,#layout .main-bottom-area1,#layout .middle-big,#layout #gadsmain-file1{padding:15px 10px 10px;margin-bottom:15px}
#layout #sidebar-wrapper .innerwrap{background-color:#A4550D}
#layout #main-top,#layout .main-bottom-area1{background-color:#228E4A!important;width:auto}
#layout #sidebartabs{background-color:#DAC526}
#layout #sidebar-wrapper .innerwrap:before{content:"Sidebar Area"}
#layout #sidebartabs:before{content:"Sidebar Tab Area"}
#layout .topfeatured-area .wrap:before{content:"Top Featured Area"}
#layout .author-profile-area:before{content:"Author Profile Area"}
#layout .manual-image-area:before{content:"Manual Slide Image Area"}
#layout .links-submenu:before{content:"Mega Menu links Content"}
#layout #main-top:before,#layout .main-bottom-area1:before,#layout .middle-big:before{content:"Magazine Widget Area"}
#layout .footer-area{background-color:#850F70;margin:0 15px}
#layout .footer-area:before{content:"Footer Area"}
#layout #sidebar-wrapper .innerwrap,#layout .topfeatured-area .wrap{width:auto}
#layout .m-big .FollowByEmail .widget-content{max-width:none}
#layout .topfeatured-area .wrap{background-color:#09A511;padding:10px;margin:0 15px}
#layout .author-profile-area{background-color:#2AC7DC}
#layout .middle-big{margin-left:15px;margin-right:15px}
#layout .links-submenu{background-color:#940D7A;padding:10px 10px 0;margin-bottom:15px}
#layout .manual-image-area{background-color:#053B6D}
#layout .bottom-section-area{padding:0 15px;overflow:hidden}
#layout .middle-header{margin:0}
#layout .main-bottom-area1{overflow:visible}
#layout .blogpost-setting > .HTML{width:32.3333%;float:$(startSide);margin:8px 0.5% 5px}
#layout .blogpost-setting{overflow:hidden!important}
#layout .image-manual-slide .widget{margin:8px .5% 5px;float:$(startSide)}
#layout .bottom-setting-sec > .HTML,#layout .image-manual-slide .widget{width:49%;margin-bottom:5px}
#layout div.layout-widget-description{display:none!important}
#layout .bottom-section-area > div{width:50%}
#layout #header,#layout #midnav,#layout .main-wrapper > div > .section,#layout #main-top,#layout .main-bottom-area1 > .section,#layout .main-bottom-area1{margin:0}
#layout .container .blogpost-setting{background-color:#9C9C9C;padding:10px}
#layout #main{padding:15px;background-color:#009BCA}
#layout .main-wrapper,#layout .sidebar-area > div{padding-top:0}
body#layout .add_widget{background-color:rgba(255,255,255,0.3);padding:16px 8px}
#layout .main-wrapper{padding-bottom:0}
#layout .container #author-section1,#layout .container #image-section1{padding:0 10px 10px}
]]>
</b:template-skin>

<b:skin><![CDATA[/*
-----------------------------------------------
Blogger Template Style
Name: Sevida Blogger Theme
Version: 2.5
Added:
- Recommended Post
- Complex Widget by Labels Style
- Spot.IM Comment
- Complex Widget
- Mega Menu Carousel Style

Design by: MKRdezign
ThemeForest URL: http://themeforest.net/user/MKRdezign
----------------------------------------------- */

/* Variable definitions
   ====================

<Variable name="startSide" description="text starts" type="automatic" default="left"/>
<Variable name="endSide" description="text ends" type="automatic" default="right"/>

<Group description="Main Color" selector="body">	
<Variable name="body.background.color" description="Body Color" type="color" default="#F5F5F5" value="#F5F5F5"/>
<Variable name="header.background.color" description="Header Area" type="color" default="transparent" value="transparent"/>
<Variable name="outer.background.color" description="Container Area" type="color" default="#FFFFFF" value="#FFFFFF"/>
<Variable name="footer.background.color" description="Footer Area" type="color" default="#2E2E2E" value="#2E2E2E"/>	
</Group>

<Group description="Backgrounds" selector="body">
<Variable name="keycolor" description="Primary Color" type="color" default="#007ABE" value="#007ABE"/>
<Variable name="body.background" description="Background" type="background" color="$(body.background.color)" default="$(color) url(http://2.bp.blogspot.com/-Cbz-Y1ezxB0/USDif0nOx4I/AAAAAAAAIcw/xpk2AZufA_U/s1600/bg.png) repeat fixed top center" value="$(color) url(http://2.bp.blogspot.com/-Cbz-Y1ezxB0/USDif0nOx4I/AAAAAAAAIcw/xpk2AZufA_U/s1600/bg.png) repeat fixed top center"/>
</Group>

<Group description="Links" selector="body">	
<Variable name="link.visited.color" description="Visited Color" type="color" default="#999999" value="#999999"/>
<Variable name="link.hover.color" description="Hover Color" type="color" default="#222222" value="#222222"/>
</Group>

<Group description="Page Text" selector="body">	
<Variable name="main.body.font" description="Body Font" type="font" default="normal normal 15px 'Roboto', 'Helvetica Neue', Helvetica, Arial, sans-serif" value="normal normal 15px &#39;Roboto&#39;, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif"/>
<Variable name="main.heading.font" description="Heading Font" type="font" default="normal normal 100% 'Open Sans', serif, Sans-serif" value="normal normal 100% &#39;Open Sans&#39;, serif, Sans-serif"/>
<Variable name="main.text.color" description="Text Color" type="color" default="#616161" value="#616161"/>
</Group>
   
<Group description="Header Area" selector=".header-wrap">	
<Variable name="header.top.color" description="Header Top Color" type="color" default="#1A1A1A" value="#1A1A1A"/>
<Variable name="header.bottom.color" description="Header Bottom Color" type="color" default="#2E2E2E" value="#2E2E2E"/>
<Variable name="header.bottom1.color" description="Header Border Color" type="color" default="#1A1A1A" value="#1A1A1A"/>
<Variable name="header.text.color" description="Text Color" type="color" default="#E2E2E2" value="#E2E2E2"/>
</Group>

<Group description="Content Area" selector=".content-wrapper">	
<Variable name="cont.background.color" description="Background Color" type="color" default="#FDFDFD" value="#FDFDFD"/>
<Variable name="cont.border.color" description="Border Color" type="color" default="#D3D3D3" value="#D3D3D3"/>
<Variable name="button.color" description="Button Color" type="color" default="#2E2E2E" value="#2E2E2E"/>
<Variable name="butext.color" description="Button Text Color" type="color" default="#FFFFFF" value="#FFFFFF"/>
</Group>

<Group description="Content Area 2" selector=".content-wrapper">	
<Variable name="cont.title.font" description="Post Title" type="font" default="normal normal 26px 'Open Sans', serif, sans-serif" value="normal normal 26px &#39;Open Sans&#39;, serif, sans-serif"/>
<Variable name="cont.botback.color" description="Background Bottom Color" type="color" default="#F6F6F6" value="#F6F6F6"/>
<Variable name="cont.botback2.color" description="Bottom Active Color" type="color" default="#F5F5F5" value="#F5F5F5"/>
<Variable name="cont.border2.color" description="Border Bottom Color" type="color" default="#EEEEEE" value="#EEEEEE"/>
</Group>

<Group description="Title Color" selector=".content-wrapper">
<Variable name="cont.widtitle.color" description="Widget Title" type="color" default="#222222" value="#222222"/>
<Variable name="cont.postitle.color" description="Post Title Color" type="color" default="#0E0E0E" value="#0E0E0E"/>
<Variable name="cont.footitle.color" description="Footer Title" type="color" default="#DBDBDB" value="#DBDBDB"/>
</Group>

<Group description="Featured Content" selector=".content-wrapper">
<Variable name="cont.featback.color" description="Featured Content" type="color" default="#2E2E2E" value="#2E2E2E"/>
<Variable name="cont.feattext.color" description="Text Color" type="color" default="#FFFFFF" value="#FFFFFF"/>
</Group>

<Group description="Footer Area" selector=".footer .widget">	
<Variable name="foot.text.color" description="Text Color" type="color" default="#CACACA" value="#CACACA"/>
<Variable name="foot.border.color" description="Border Color" type="color" default="#181818" value="#181818"/>
<Variable name="foot.heading.color" description="Heading Color" type="color" default="#ECECEC" value="#ECECEC"/>
<Variable name="foot.img.color" description="Image Color" type="color" default="#1F1F1F" value="#1F1F1F"/>
</Group>

<Group description="Social Counter" selector="body">	
<Variable name="socbt.counter.color" description="Social Counter Color" type="color" default="#E9E9E9" value="#E9E9E9"/>
<Variable name="soc.counter.color" description="Text Color" type="color" default="#FFFFFF" value="#FFFFFF"/>
</Group>

*/

/* 
 CONTENTS
 =======================
  = A. CSS Reset 
  = B. Container
  = C. Header Section and Top Navigation
  = D. Social Icons Widget
  = E. Magazine Section
  = F. Posts Section
  = G. Blogger Comments
  = H. Sidebar Section
  = I. Blogger Widgets
  = J. Footer Section
  = K. Error page 
  = L. Shortcodes 
  = M. Responsive Menu
  = N. Other Effect
  = O. Responsive
*/

/*=====================================
= A. CSS Reset
=====================================*/
html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}
body{margin:0}
article,aside,details,figcaption,figure,footer,header,hgroup,main,menu,nav,section,summary{display:block}
audio,canvas,progress,video{display:inline-block;vertical-align:baseline}
audio:not([controls]){display:none;height:0}
[hidden],template,.blogpost-setting{display:none}
a{background-color:transparent}
a:active,a:hover{outline:0}
b,strong{font-weight:bold}
dfn{font-style:italic}
h1{font-size:2em;margin:0.67em 0}
mark{background:#ff0;color:#000}
small{font-size:80%}
sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}
sup{top:-0.5em}
sub{bottom:-0.25em}
img{border:0}
svg:not(:root){overflow:hidden}
figure{margin:1em 40px}
hr{-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box;height:0}
pre{overflow:auto}
code,kbd,pre,samp{font-family:monospace,monospace;font-size:1em}
button,input,optgroup,select,textarea{color:inherit;font:inherit;margin:0}
button{overflow:visible}
button,select{text-transform:none}
button,html input[type="button"],input[type="reset"],input[type="submit"]{-webkit-appearance:button;cursor:pointer}
button[disabled],html input[disabled]{cursor:default}
button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}
input{line-height:normal}
input[type="checkbox"],input[type="radio"]{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;padding:0}
input[type="number"]::-webkit-inner-spin-button,input[type="number"]::-webkit-outer-spin-button{height:auto}
input[type="search"]{-webkit-appearance:textfield;-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box}
input[type="search"]::-webkit-search-cancel-button,input[type="search"]::-webkit-search-decoration{-webkit-appearance:none}
fieldset{border:1px solid #c0c0c0;margin:0 2px;padding:0.35em 0.625em 0.75em}
legend{border:0;padding:0}
textarea{overflow:auto}
optgroup{font-weight:bold}
table{border-collapse:collapse;border-spacing:0}
td,th{padding:0}
@media print{
  *,*:before,*:after{background:transparent!important;color:#000!important;-webkit-box-shadow:none!important;box-shadow:none!important;text-shadow:none!important}
  a,a:visited{text-decoration:underline}
  a[href]:after{content:" (" attr(href) ")"}
  abbr[title]:after{content:" (" attr(title) ")"}
  a[href^="#"]:after,a[href^="javascript:"]:after{content:""}
  pre{border:1px solid #999;page-break-inside:avoid}
  thead{display:table-header-group}
  tr,img{page-break-inside:avoid}
  img{max-width:100%!important}
  p,h2,h3{orphans:3;widows:3}
  h2,h3{page-break-after:avoid}
  select{background:#fff!important}
  .navbar{display:none}
  .btn > .caret,.dropup > .btn > .caret{border-top-color:#000!important}
  .label{border:1px solid #000}
  .table{border-collapse:collapse!important}
  .table td,.table th{background-color:#fff!important}
  .table-bordered th,.table-bordered td{border:1px solid #ddd!important}
}
*{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;position:relative}
*:before,*:after{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}
html{font-size:10px;-webkit-tap-highlight-color:rgba(0,0,0,0)}
html body{font:$(main.body.font);line-height:1.42857143;color:$(main.text.color);background:$(body.background);font-weight:300;padding:0}
input,button,select,textarea{font-family:inherit;font-size:inherit;line-height:inherit}
input:focus{outline-color:$(keycolor)}
a{color:$(keycolor);text-decoration:none}
a:hover,a:focus{color:$(link.hover.color);text-decoration:underline}
a:visited{color:$(link.visited.color)}
figure{margin:0}
img{vertical-align:middle}
p{margin:0 0 10.5px}
.section,.widget,.widget ul,.widget li{margin:0;padding:0}
.widget{line-height:inherit}
.content-wrapper .widget{overflow:hidden}
h1,h2,h3,h4,h5,h6,.h1,.h2,.h3,.h4,.h5,.h6{font:$(main.heading.font);line-height:1.2em;color:inherit;font-weight:600}
h1,.h1,h2,.h2,h3,.h3{margin-top:21px;margin-bottom:10.5px}
h4,.h4,h5,.h5,h6,.h6{margin-top:10.5px;margin-bottom:10.5px}
h1,.h1{font-size:30px}
h2,.h2{font-size:24px}
h3,.h3{font-size:22px}
h4,.h4{font-size:19px}
h5,.h5{font-size:17px}
h6,.h6{font-size:16px}
.clear{clear:both}
.clearfix:before,.clearfix:after,.row:before,.row:after,.container:before,.container:after,.wrap:before,.wrap:after{content:" ";display:table}
.clearfix:after,.container:after,.row:after,.wrap:after{clear:both}
.blog-feeds,.widget-item-control{display:none!important}
svg{position:absolute;top:0;left:0;width:100%;height:100%}
circle{fill:rgba(255,255,255,0.1)}
.btn{cursor:pointer}
a,.main-menu > li,.label-size,.social-wrap .fa,.youtubeplay .fa,.youtubeplay:after,.flickr_badge_image img,.scrolled .header-wrap,.thumb-area a:before,.post-type,.content-area,.first-area,.contact-sec,.postdate,.owl-nav div,.timeline .thumb-outer,.post-type,.featured .content-area,a.rcomment-img img,.dsq-widget-item img,.contact-button,.item-share span,.reco-place{-webkit-transition:all 0.3s ease;-moz-transition:all 0.3s ease;-ms-transition:all 0.3s ease;-o-transition:all 0.3s ease;transition:all 0.3s ease}
.circle{border-radius:2000px}
.Label li:before,.owl-custom-nav div:before,.owl-nav div:before,.list .items:before,.icon.blog-author:before,.breadcrumbs .homex:before,.comments .comment .comment-actions .item-control a:before,a.tag-name:before,.pager-isi span:before,.pager-isi a:before,blockquote:before,.sidebar .LinkList li:before,.newsticker h3 a:before,.posts-title .title-wrap:before,.blog-pager-item a:before,.blog-pager-item .linkgrey:before,.icon.blog-author:before,.widget .post-body ul li:before,.links-content li:before,.plabelsbtn:before,.ticker-controls li:before,.social-desc:before,.item-share span:after,.blog-pager-item .pager-isi > a:before,.linkgrey:before,span.resbutton:before,.post-body ul li:before,.breakline-place h3:before,.sbreakline .content-area h3:before{display:inline-block;font-family:FontAwesome;font-size:inherit;text-rendering:auto;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}
.widget-content{padding:10px}
blockquote{padding-$startSide:40px;opacity:0.9;font-size:100%;font-style:italic}
blockquote:before{content:"\f10d";position:absolute;$startSide:0;font-size:30px;top:-10px;opacity:0.7;width:33px;font-style:normal}
.rtl blockquote:before{content:"\f10d"}
::selection{background:$(keycolor);color:#FFF;text-shadow:none}
::-moz-selection{background:$(keycolor);color:#FFF;text-shadow:none}
/*=====================================
= B. Container
=====================================*/
.container,.scrolled .bottom-header .head-wrap{width:100%;margin:0 auto;padding:0;max-width:1150px}
.wrap,.scrolled .main-nav{margin:0 15px;width:auto}
.full-style .container{width:100%;margin:0 auto;padding: 0;max-width: none}
.full-style .wrap{margin:0 auto;max-width:1150px;width: 98%}
.full-style .scrolled .main-nav {margin:0}
.header-wrap{background-color:$(header.background.color)}
.container{box-shadow:0 0 5px rgba(0,0,0,0.25);background-color:$(outer.background.color);overflow:hidden}
.main-wrapper,.sidebar-wrapper{min-height:100%;padding-top:15px;padding-bottom:15px}
.stickside-work .main-wrapper{padding-bottom:0}
.stickside-work .item .main-wrapper,.stickside-work .static_page .main-wrapper{padding-bottom:15px}
.content-wrapper{background-color:$(outer.background.color)}
.homeq .content-wrapper{box-shadow:0 -2px 5px rgba(0,0,0,0.10)}
.container-outer,.contact-sec > div,.pager-summary,a.jdshrt-tooltip > span{-webkit-transition:all 0.5s ease;-moz-transition:all 0.5s ease;-ms-transition:all 0.5s ease;-o-transition:all 0.5s ease;transition:all 0.5s ease;z-index:2}
.topfeatured-area{background-color:$(outer.background.color)}
.widget ul,.widget li{margin:0;padding:0;list-style:none}
.sidebar-area{position:static}
.sidebar-right,.sidebar-left{position:absolute;top:0;height:100%;padding-top:15px}
.sidebar-left{$startSide:0}
.sidebar-right{$endSide:0}
.widget > h2,.posts-title h2,.comments-tabs-header h3,.related_posts h4{font-size:17px;text-transform:uppercase;color:$(cont.widtitle.color);margin:0 0 8px}
.title-wrap{background-color:$(outer.background.color);z-index:1;padding-$endSide:7px}
.posts-title h2,.title-wrap{display:inline}
.posts-title .title-wrap{display:inline-block}
.view{background-color:$(outer.background.color);position:absolute;$endSide:0;top:0;z-index:1;padding-$startSide:8px}
.view span{float:$endSide;display:block;padding:0 5px;cursor:pointer}
/*=====================================
= C. Header Section and Top Navigation
=====================================*/
.header-wrap .widget-content{padding:0}
.resbutton,.menu,.menu ul,.labelhide,.content-area .psummary,.first-area .psummary,.first-item .postdate,.contact-sec,.list .rpstmetainfo,.timeline .widcomments,.timeline .wid-author,.timeline .rpstmetainfo .fa,.list .thumb-outer,.post-type .fa,.carousel1 .rpstmetainfo,.carousel2 .postdate,.hot a.bottom-morepost,.gallery .content-area,.gallery .first-area,.gallery .first-item:first-child .postdate,.newsticker .thumb-outer,.newsticker .rcptags,.newsticker a.bottom-morepost,.newsticker h2,.newsticker .rpstmetainfo .fa,.newsticker .wid-author,.newsticker .widcomments,.newsmoreinfo,.featured h2,.featured .post-type,.featured2 .items .psummary,a.menu-morepost.random,.bottom-section-area,.post-feeds,#comment-post-message,.comments,.shrt-gallery > br,.acrd-content,.emoWrap,.rel-carousel .rpstmetainfo,.links-submenu,.links-content .fbig-widget-area,.links-content .first-item:first-child .first-area .psummary,.links-content a.bottom-morepost,.links-content .rpstmetainfo,span.resbutton,.cst-share-btn,.slider .post-type,.error_page .sidebar-area,.show-popup .cst-share-btn,.imageheader,.item .home-area .homepost,.dhref-done span:after,.sharesinfo .icons-whatsapp, .item-share .icons-whatsapp,.item .dhref-done span:before,.slide-pfeatured .owl-next:last-child{display:none}
.menu.show,.newsmoreinfo.active,.featured2 .items:hover .psummary,.tab-blogger.comments{display:block}
.titlewrapper .h1{margin:10px 0;font:normal normal 35px 'Open Sans',serif,sans-serif}
.Header .descriptionwrapper p{margin:0 0 10px}
.middle-header .head-wrap{display:table}
.middle-header .header,.middle-header .topads{display:table-cell;vertical-align:middle}
.middle-header{margin:15px 0}
.middle-header .topads{max-width:728px}
.middle-header .header{width:450px}
.middle-header .header a:hover,.middle-header .header a:active,.middle-header .header a:visited {text-decoration: none;color: inherit}
a.home-icon{position:absolute;height:56px;line-height:60px;width:60px;top:-5px;background-color:$(keycolor);text-align:center;font-size:32px;color:$(butext.color);text-decoration:none}
.top-date,.top-menu-sec,.menu > li{float:$startSide}
.top-social-sec,.menu-search{float:$endSide}
.top-date span{margin-$endSide:10px;float:$startSide}
.top-header{height:32px;background-color:$(header.top.color);color:$(header.text.color);line-height:32px;font-size:14px;z-index:5}
.top-date{font-size:12px;color:$(header.text.color)}
.bottom-header{height:55px;color:$(header.text.color);border-bottom:4px solid $(keycolor);z-index:3}
.bottom-header,a.nohover{background-color:$(header.bottom.color)}
a.nohover:hover{background-color:$(keycolor)}
.menu li > a{color:inherit;line-height:inherit;display:block}
.menu ul{position:absolute}
.menu a:hover,.menu a:focus{text-decoration:none}
.main-menu{padding-$startSide:60px!important}
.menu > li > a{height:32px;line-height:32px;padding:0 0.7em}
.main-menu > li > a{height:55px;line-height:17px;padding:0 0.8em;padding-top:17px;font-weight:400;text-transform:uppercase;font-size:14px}
.main-menu > .have-desc > a{padding-top: 10px}
.menu .submenu > a{padding-$endSide:1.8em}
.sub-menu{top:100%;$startSide:0}
.sub-sub-menu{top:-1px;$startSide:100%;padding-$startSide:1px!important}
.sub-button{position:absolute;$endSide:10px;bottom:10px;font-size:12px}
.main-menu .sub-button{bottom:23px}
.main-menu .have-desc > .sub-icon .sub-button{bottom:31px}
.subsubmenu .sub-button{bottom:7px;$endSide:7px}
.rtl .menu .sub-button .fa-caret-right:before{content:"\f0d9"}
.menu ul li > a{white-space:nowrap;line-height:28px;padding:0 0.8em;background-color:$(keycolor);margin:1px 0;border-radius:2px;font-size:90%;min-width:140px}
.sub-menu li:hover > a{padding-$startSide:15px}
.menu-desc{font-size:11px;opacity:0.8;display:block;line-height:16px;text-transform:capitalize}
.top-menu ul li > a{background-color:$(header.top.color)}
.top-menu li:hover > a,.sc-move{background-color:$(keycolor)}
.sc-move{height:60px;position:absolute;top:-5px}
.mega-menu{position:static}
.mega-menu > .sub-menu{top:55px;background-color:$(header.bottom.color);padding:15px;left:0;right:0}
.scrolled .middle-header{padding-bottom:55px}
.scrolled .bottom-header{position:fixed;left:0;right:0;top:-55px}
.scrolled .scroll-up .bottom-header{top:0;box-shadow:0 2px 8px rgba(0,0,0,0.4)}
.search-form{margin-top:10px}
.search-form input{border:0;border-radius:2px;background-color:#4C4C4C;background-color:rgba(255,255,255,0.15);font-size:12px;height:33px;padding:5px 10px;line-height:33px;width:220px;margin-$endSide:36px}
.search-form button{background-color:transparent;border:0;font-size:22px;height:33px;line-height:33px;position:absolute;$endSide:0;top:0}
.search-form input:focus,.search-form button:focus{border:0;outline:0}
.src-result{position:absolute;$endSide:0;top:45px;border:1px solid $(cont.border.color);background-color:$(outer.background.color);color:$(main.text.color);-webkit-box-shadow:0 3px 11px -4px rgba(0,0,0,.6);-moz-box-shadow:0 3px 11px -4px rgba(0,0,0,.6);box-shadow:0 3px 11px -4px rgba(0,0,0,.6);padding:8px;margin:0;width:300px;display:none}
.src-area{height:350px;font-size:12px}
.src-area .mCSB_container{margin-$endSide:10px}
.src-result .close{position:absolute;$endSide:8px;top:8px;text-decoration:none;font-size:18px;font-weight:400;color:$(butext.color);background-color:$(keycolor);width:20px;height:20px;line-height:20px;text-align:center}
.src-header{font-weight:400;margin:2px 0 10px;display:block}
.src-img{display:block;width:50px;height:50px}
.src-img-outer{margin-$endSide:5px;float:$startSide;padding:3px;border:1px solid $(cont.border.color);border-radius:2px}
.src-mark{color:$(butext.color);background-color:$(keycolor)}
.src-title{font-weight:400;font-size:110%;color:$(cont.postitle.color);display:block;margin-bottom:5px;line-height:1.2em}
.src-morepost a{display:block;text-align:center;text-decoration:none;color:$(butext.color);background-color:$(keycolor);padding:4px 0;font-size:14px;margin-top:10px;border-radius:3px}
.src-morepost a:hover{background-color:$(header.bottom.color)}
.src-morepost a:active{top:1px}
.links-content{width:23.5%;float:$startSide;margin-$endSide:2%}
.links-content:last-child{margin-$endSide:0}
.links-content ul{display:block;position:static}
.links-content > h2{margin:0 0 15px;font-size:16px;color:$(header.text.color)}
.links-content > h2 a{color:inherit}
.links-content > h2 a:hover{text-decoration:none}
.links-content .title-wrap{background-color:$(header.bottom.color)}
.links-content a.morepost{background-color:$(keycolor);color:$(butext.color)}
.links-content ul > li{background-color:rgba(0,0,0,0.2);margin-bottom:2px}
.links-content ul li > a{background-color:transparent;margin:0;line-height:32px;padding-left:18px;font-size:100%}
.links-content ul li > span{position:absolute;$endSide:8px;height:18px;line-height:18px;top:50%;margin-top:-9px}
.links-content ul > li:before{content:"";position:absolute;width:3px;top:9px;bottom:9px;$startSide:5px;background-color:$(keycolor)}
.links-content ul > li:hover:before{width:6px}
.links-content .first-item:first-child a.rcthumb{height:160px}
.links-content .first-item:first-child .first-area{position:absolute;bottom:10px;color:$(header.text.color);right:10px;left:10px}
.links-content .first-item:first-child .items-inner{border-bottom:0;padding-bottom:0;margin-bottom:0}
.links-content .first-item:first-child .first-area h3{color:$(header.text.color);font-size:16px}
.menu a .fa,.res-menu a .fa{margin-$endSide: 7px}
.mcarousel a.rcthumb{height:140px}
.mcarousel .rcptags,.mcarousel .psummary{display:none !important}
.mcarousel .owl-nav div{margin-top:0;top:55px}
.mcarousel .owl-dots{position:static;margin-top:10px}
.mcarousel .items-inner{padding:0 5px}
.mcarousel .owl-carousel .content-area{padding-$startSide:0;padding-top:8px}
.gridpost .owl-item a.rcthumb{height:160px}
.gridpost .owl-item .content-area{position:absolute;bottom:10px}
.gridpost .owl-item .content-area h3 a{color:#FFFFFF;text-shadow:0 1px 4px rgba(0,0,0,0.75)}
.gridpost .owl-dots{bottom:auto;top:10px;$endSide:10px;$startSide:auto}
/*=====================================
= D. Social Icons Widget
=====================================*/
.widget .social-icon{padding-bottom:0;padding-top:0;margin:0;overflow:hidden}
.social-icon a{color:$(header.text.color);text-decoration:none;display:inline-block;width:28px;height:32px;line-height:32px;text-align:center;font-size:15px}
.icon-twitter:before{content:"\f099"}
.icon-facebook:before{content:"\f09a"}
.icon-google:before{content:"\f0d5"}
.icon-rss:before{content:"\f09e"}
.icon-linkedin:before{content:"\f0e1"}
.icon-dribbble:before{content:"\f17d"}
.icon-pinterest:before{content:"\f0d2"}
.icon-youtube:before{content:"\f167"}
.icon-vimeo:before{content:"\f194"}
.icon-skype:before{content:"\f17e"}
.icon-deviantart:before{content:"\f1bd"}
.icon-flickr:before{content:"\f16e"}
.icon-stumbleupon:before{content:"\f1a4"}
.icon-tumblr:before{content:"\f173"}
.icon-delicious:before{content:"\f1a5"}
.icon-digg:before{content:"\f1a6"}
.icon-lastfm:before{content:"\f202"}
.icon-wordpress:before{content:"\f19a"}
.icon-instagram:before{content:"\f16d"}
.icon-apple:before{content:"\f179"}
.icon-dropbox:before{content:"\f16b"}
.icon-behance:before{content:"\f1b4"}
.icon-reddit:before{content:"\f1a1"}
.social-icon li{display:inline}
.social-wrap{overflow:hidden;padding:10px 0 0;border:0!important;background-color: transparent !important;}
.social-wrap li{width:25%;float:$startSide;height:110px;text-align:center;padding-$startSide:0!important;margin-bottom:0!important;line-height:1em}
.social-wrap li:before{display:none!important}
.social-wrap .icon-counter,.social-wrap .social-desc{display:block}
.social-desc{background-color:$(keycolor);width:70px;margin:0 auto;padding:5px 0}
.social-desc:before{content:"\f0de";color:$(keycolor);position:absolute;width:14px;left:50%;margin-left:-7px;top:-5px;font-size:21px}
.social-desc span{display:block;color:$(butext.color)}
.item-count{font-weight:400;font-size:17px;margin-top:2px}
.item-text{font-size:11px}
.social-wrap li:hover .social-desc{background-color:$(button.color)}
.social-wrap li:hover .social-desc:before{color:$(button.color)}
.social-wrap .fa{width:70px;text-shadow:0 1px 2px rgba(0,0,0,0.10);height:60px;line-height:60px;text-align:center;font-size:32px;background-color:$(socbt.counter.color)}
.social-wrap .icon-twitter,.social-wrap a:hover .icon-twitter:after{color:#2DAAE1}
.social-wrap .icon-facebook,.social-wrap a:hover .icon-facebook:after{color:#3C5B9B}
.social-wrap .icon-google,.social-wrap a:hover .icon-google:after{color:#F63E28}
.social-wrap .icon-rss,.social-wrap a:hover .icon-rss:after{color:#FA8C27}
.social-wrap .icon-linkedin,.social-wrap a:hover .icon-linkedin:after{color:#0173B2}
.social-wrap .icon-dribbble,.social-wrap a:hover .icon-dribbble:after{color:#F9538F}
.social-wrap .icon-pinterest,.social-wrap a:hover .icon-pinterest:after{color:#CB2027}
.social-wrap .icon-youtube,.social-wrap a:hover .icon-youtube:after{color:#CD332D}
.social-wrap .icon-vimeo,.social-wrap a:hover .icon-vimeo:after{color:#44BBFF}
.social-wrap .icon-skype,.social-wrap a:hover .icon-skype:after{color:#00AFF0}
.social-wrap .icon-deviantart,.social-wrap a:hover .icon-deviantart:after{color:#4B5D50}
.social-wrap .icon-flickr,.social-wrap a:hover .icon-flickr:after{color:#0063DB}
.social-wrap .icon-stumbleupon,.social-wrap a:hover .icon-stumbleupon:after{color:#EB4924}
.social-wrap .icon-tumblr,.social-wrap a:hover .icon-tumblr:after{color:#2C4762}
.social-wrap .icon-delicious,.social-wrap a:hover .icon-delicious:after{color:#3274D1}
.social-wrap .icon-digg,.social-wrap a:hover .icon-digg:after{color:#14589E}
.social-wrap .icon-lastfm,.social-wrap a:hover .icon-lastfm:after{color:#D51007}
.social-wrap .icon-wordpress,.social-wrap a:hover .icon-wordpress:after{color:#21759B}
.social-wrap .icon-instagram,.social-wrap a:hover .icon-instagram:after{color:#3F729B}
.social-wrap .icon-apple,.social-wrap a:hover:after{color:#B9BFC1}
.social-wrap .icon-dropbox,.social-wrap a:hover .icon-dropbox:after{color:#2281CF}
.social-wrap .icon-behance,.social-wrap a:hover .icon-behance:after{color:#1769ff}
.social-wrap .icon-reddit,.social-wrap a:hover .icon-reddit:after{color:#FF4500}
.social-wrap a:hover,.social-wrap a:focus{text-decoration:none}
.social-wrap a:hover .fa{color:$(soc.counter.color)}
.social-icon .icon-twitter:hover,a:hover .icon-twitter,.icons-twitter .fa,.authorSocial .icon-twitter,.cst-twitter{background-color:#2DAAE1}
.social-icon .icon-facebook:hover,a:hover .icon-facebook,.icons-facebook .fa,.authorSocial .icon-facebook,.cst-facebook{background-color:#3C5B9B}
.social-icon .icon-google:hover,a:hover .icon-google,.icons-gplus .fa,.authorSocial .icon-google,.cst-google-plus{background-color:#F63E28}
.social-icon .icon-rss:hover,a:hover .icon-rss{background-color:#FA8C27}
.social-icon .icon-linkedin:hover,a:hover .icon-linkedin,.icons-linkedin .fa,.authorSocial .icon-linkedin,.cst-linkedin{background-color:#0173B2}
.social-icon .icon-dribbble:hover,a:hover .icon-dribbble,.authorSocial .icon-dribbble{background-color:#F9538F}
.social-icon .icon-pinterest:hover,a:hover .icon-pinterest,.icons-pinterest .fa,.authorSocial .icon-pinterest,.cst-pinterest{background-color:#CB2027}
.social-icon .icon-youtube:hover,a:hover .icon-youtube,.authorSocial .icon-youtube{background-color:#CD332D}
.social-icon .icon-vimeo:hover,a:hover .icon-vimeo,.authorSocial .icon-vimeo{background-color:#44BBFF}
.social-icon .icon-skype:hover,a:hover .icon-skype,.authorSocial .icon-skype{background-color:#00AFF0}
.social-icon .icon-deviantart:hover,a:hover .icon-deviantart,.authorSocial .icon-deviantart{background-color:#4B5D50}
.social-icon .icon-flickr:hover,a:hover .icon-flickr,.authorSocial .icon-flickr{background-color:#0063DB}
.social-icon .icon-stumbleupon:hover,a:hover .icon-stumbleupon,.authorSocial .icon-stumbleupon,.icons-stumbleupon .fa,.cst-stumbleupon{background-color:#EB4924}
.social-icon .icon-tumblr:hover,a:hover .icon-tumblr,.authorSocial .icon-tumblr,.cst-tumblr{background-color:#2C4762}
.social-icon .icon-delicious:hover,a:hover .icon-delicious,.cst-delicious{background-color:#3274D1}
.social-icon .icon-digg:hover,a:hover .icon-digg,.cst-digg{background-color:#14589E}
.social-icon .icon-lastfm:hover,a:hover .icon-lastfm{background-color:#D51007}
.social-icon .icon-wordpress:hover,a:hover .icon-wordpress{background-color:#21759B}
.social-icon .icon-instagram:hover,a:hover .icon-instagram{background-color:#3F729B}
.social-icon .icon-apple:hover,a:hover .icon-apple{background-color:#B9BFC1}
.social-icon .icon-dropbox:hover,a:hover .icon-dropbox{background-color:#2281CF}
.social-icon .icon-behance:hover,a:hover .icon-behance{background-color:#1769ff}
.social-icon .icon-reddit:hover,a:hover .icon-reddit,.cst-reddit{background-color:#FF4500}
.icons-whatsapp .fa,.cst-whatsapp{background-color: #5cbe4a}
.cst-envelope{background-color:#511295}
.cst-hacker-news{background-color:#f08641}
.cst-share-item:nth-child(7) .cst-envelope{background-color:#dd4b39}
.cst-vk{background-color:#4c75a3}
.cst-print{background-color:#75aa33}
.sharesinfo{position:absolute;width:auto;$endSide:4px;$startSide:4px;bottom:4px;top:4px;background-color:rgba(0,0,0,0.8);padding:0;z-index:2;display:none;text-align:center}
.sharesinfo .fa{width:32px;height:32px;line-height:32px;color:$(butext.color);font-size:14px}
.sharesinfo a:hover,.sharesinfo a:focus{text-decoration:none}
.sharesinfo a{display:inline-block;height:32px;width:32px;margin-top:65px}
.grip .sharesinfo a{margin-top:58px}
.sharesinfo span{color:$(butext.color);font-size:12px;height:18px;line-height:18px;position:absolute;top:-30px;left:-7px;right:-7px;background-color:$(keycolor);display:none}
.sharesinfo a:hover span{display:block}
.sharesinfo span:before{content:"";position:absolute;top:100%;left:50%;margin-left:-5px;width:0;height:0;border:5px solid transparent;border-top-color:$(keycolor)}
/*=====================================
= E. Magazine Section
=====================================*/
.loadinghtml .HTML,.loadinghtml .LinkList,.sevida-widget{visibility:hidden}
.widget-area,.fbig-widget-area,.main-bottom-area1{overflow:hidden}
.thumb-outer,.content-area,.first-area{display:table-cell;vertical-align:middle}
.content-area h3,.first-area h3{margin:0;font-size:15px;color:$(cont.postitle.color);overflow:hidden;max-height:37px}
a.morepost{background-color:$(outer.background.color);color:$(cont.postitle.color);font-size:12px;float:$endSide;padding:0 10px;height:20px;line-height:20px}
.content-area h3 a,.first-area h3 a,.sevida-widget h2 a,.rpstmetainfo a{color:inherit}
.content-area,.first-area{padding-$startSide:10px}
.items-inner{overflow:hidden;margin-bottom:10px;padding-bottom:10px;border-bottom:1px solid $(cont.border2.color)}
.rpstmetainfo{font-size:11px;margin-top:8px;overflow:hidden;line-height:15px}
.rpstmetainfo > span{display:inline-block}
.fbig1 .first-item:first-child,.fbig1 .fbig-widget-area,.fbig2 .first-item:first-child .thumb-outer,.fbig2 .fbig-widget-area .items,.hot .first-item:first-child,.hot .fbig-widget-area,.gallery2 .fbig-widget-area .items,.main-bottom-column > div{width:50%;float:$startSide}
.fbig1 .first-item:first-child,.fbig2 .first-item:first-child .thumb-outer,.fbig2 .fbig-widget-area .items:nth-child(odd) .items-inner,.main-column-left{padding-$endSide:10px}
.fbig1 .fbig-widget-area,.fbig2 .first-item:first-child .first-area,.fbig2 .fbig-widget-area .items:nth-child(even) .items-inner,.main-column-right{padding-$startSide:10px}
.fbig2 .fbig-widget-area .items:nth-child(even) .items-inner{border-bottom:1px solid $(cont.border2.color);padding-bottom:10px}
.items:last-child .items-inner,.gallery .items-inner{margin-bottom:0;padding-bottom:0;border-bottom:0}
.rpstmetainfo > span,.rpstmetainfo .fa{float:$startSide;margin-$endSide:7px}
.rpstmetainfo .fa{margin-$endSide:4px;line-height:16px}
.sevida-widget h2 a:hover,.sevida-widget h2 a:focus{text-decoration:none}
a.bottom-morepost,.carousel2 .content-area,.slider2 .content-area{text-align:center}
.animated-item .items{margin-bottom:10px}
.first-item{z-index:0}
.first-item:first-child .thumb-outer,.first-item:first-child .first-area .psummary,.first-item:first-child .postdate,.slider .widget-content .psummary,.owl-item .thumb-outer,.owl-item  .content-area,.owl-item  .first-area,.hot .fbig-widget-area .thumb-outer,.hot .content-area,.gallery .thumb-outer,.video .thumb-outer,.video .content-area,.newsmoreinfo .thumb-outer,.newsmoreinfo .content-area,.newsmoreinfo .psummary,.featured .psummary,.feat-wrapitem .thumb-outer,.feat-wrapitem .content-area,.grip .content-area,.mtab .content-area,.grip .thumb-outer,.mtab .thumb-outer,.emoWrap.active{display:block}
.column1 .load-added .widget-area{max-height:460px}
.column2 .load-added .fbig-widget-area,.fbig1 .load-added .fbig-widget-area{max-height:355px}
.fbig2 .fbig-widget-area{max-height:178px}
.first-item:first-child a.rcthumb{width:auto;height:180px}
.first-item:first-child .thumb-area,.video .thumb-area,.carousel .thumb-area,.hot .thumb-area,.related_posts .thumb-area{padding:4px}
.first-item:first-child .first-area h3{font-size:20px;margin:10px 0 8px;max-height:none}
.first-item:first-child .first-area{padding-$startSide:0}
.fbig1 .first-item:first-child .items-inner{border-bottom:0}
.first-area .psummary{margin:10px 0}
.first-area a.readmorebut{float:$startSide;padding:5px 10px;font-size:12px;border-radius:3px;margin-top:10px}
.fbig2 .first-item:first-child .first-area h3{margin-top:0}
.mbig .items,.video .items,.gallery1 .fbig-widget-area .items,.featured .items,.grip .items,.mtab .items{float:$startSide}
.fbig2 .fbig-widget-area .items:nth-child(even),.featured3 .items:nth-child(2){float:$endSide}
.owl-item .thumb-area > a{width:auto}
.slider .thumb-area a{height:350px}
.slider .widget-content,.manualslide .widget-content{padding:5px}
.slider1 .content-area,.mslide-info{position:absolute;bottom:35px;right:20px;left:20px;background-color:$(cont.featback.color);padding:15px;color:$(cont.feattext.color)}
.mslide-info{padding:0}
.mcaption{padding:15px;margin-top:5px}
.mslide-info h3{margin:0}
.slider .content-area h3,.mslide-info h3{color:$(cont.feattext.color);font-size:20px;text-shadow:0 1px 2px rgba(0,0,0,0.6)}
.slider1 .content-area h3,.mslide-info h3{position:absolute;bottom:90%;background-color:$(keycolor);$startSide:0;padding:5px 10px;max-height:none;max-width:95%}
.slider1 .content-area a,.mslide-info h3 a{color:inherit}
.slider1 .widget-content .psummary{font-size:14px}
.slider .widget-content .psummary{margin-top:10px}
.slider2 .content-area h3{font-size:25px;max-height:none}
.slider2 .content-area{position:absolute;bottom:80px;color:$(cont.feattext.color);left:20px;right:20px;text-shadow:0 1px 2px rgba(0,0,0,0.6)}
.content-wrapper .slider,.content-wrapper .manualslide{overflow:visible;margin-bottom:25px!important;z-index:0}
.featured .thumb-area a:before,.slider2 .thumb-area a:before,.gallery .thumb-area a:before,.carousel1 .thumb-area a:before,.video .thumb-area a:before,.simple .thumb-area a:before,.related_posts .thumb-area a:before,.shrt-carousel-item  a.shrt-owl-img:before{content:"";background:-webkit-linear-gradient(top,rgba(0,0,0,0.2) 50%,rgba(0,0,0,0.5) 70%,rgba(0,0,0,1) 100%);background:-moz-linear-gradient(top,rgba(0,0,0,0.2) 50%,rgba(0,0,0,0.5) 70%,rgba(0,0,0,1) 100%);background:-ms-linear-gradient(top,rgba(0,0,0,0.2) 50%,rgba(0,0,0,0.5) 70%,rgba(0,0,0,1) 100%);background:-o-linear-gradient(top,rgba(0,0,0,0.2) 50%,rgba(0,0,0,0.5) 70%,rgba(0,0,0,1) 100%);background:linear-gradient(top,rgba(0,0,0,0.2) 50%,rgba(0,0,0,0.5) 70%,rgba(0,0,0,1) 100%);position:absolute;height:100%;width:100%;opacity:0.5}
.featured .items:hover .thumb-area a:before,.slider2 .items:hover .thumb-area a:before,.gallery .items:hover .thumb-area a:before,.carousel1 .items:hover .thumb-area a:before,.video .thumb-area:hover a:before,.simple .thumb-area:hover a:before,.related_posts .thumb-area:hover a:before,.slider .thumb-area:hover > a,.shrt-carousel-item:hover  a.shrt-owl-img:before{opacity:1}
.slider2 .rpstmetainfo > span,.slider2 .rpstmetainfo .fa,.carousel2 .rpstmetainfo > span,.carousel2 .rpstmetainfo .fa{float:none}
.list .content-area{padding-$startSide:0}
.timeline .content-area,.timeline .items-inner,.newsmoreinfo .content-area{position:static}
.timeline .content-area{min-height:75px;display:block;}
.timeline .content-area h3:before,.timeline .content-area h3:after{content:"";background-color:$(cont.border.color);border-radius:2000px;width:11px;height:11px;position:absolute;$startSide:-16px;top:4px}
.timeline .content-area h3:after{width:7px;height:7px;$startSide:-14px;top:6px;background-color:$(outer.background.color)}
.timeline .items:hover .content-area h3:before{background-color:$(keycolor)}
.timeline .items-inner{margin-bottom:0;border-bottom:0;margin-$startSide:75px;border-$startSide:1px solid $(cont.border.color);padding-bottom:15px}
.list .content-area h3,.timeline .content-area h3,.carousel .content-area h3,.related_posts .content-area h3{max-height:none}
.timeline .rpstmetainfo{position:absolute;$startSide:0;margin-top:0;top:0;width:67px}
.timeline .rpstmetainfo .wid-date{background-color:$(button.color);color:$(butext.color);padding:2px 5px;margin-$endSide:1px;float:$endSide}
.timeline .items:hover .rpstmetainfo .wid-date{background-color:$(keycolor)}
.timeline .content-area h3,.timeline .content-area,.timeline .items-inner{overflow:visible}
.owl-dots{position:absolute;bottom:5px;text-align:center;left:0;right:0}
.owl-dot{display:inline-block;width:14px;height:14px;margin:0 3px;border-radius:2000px;background-color:$(keycolor)}
.owl-dot.active span,.owl-dot:hover span{display:inline-block;width:10px;height:10px;background-color:$(outer.background.color);border-radius:2000px;position:absolute;left:2px;top:2px}
.simple .thumb-area > a{width:60px;height:60px}
.simple .content-area h3{font-size:14px;max-height:32px}
.simple .rpstmetainfo{font-size:10px}
.simple .rpstmetainfo .fa{line-height:12px}
.timeline .psummary{display:block;font-size:12px;margin-top:10px}
.timeline .thumb-outer{position:absolute;$startSide:0;top:24px;opacity:0.3}
.timeline .thumb-area > a{width:57px;height:57px}
.timeline .items:last-child .items-inner{padding-bottom:5px}
.timeline .load-added .widget-area{max-height:532px}
.list .items{padding-$startSide:20px}
.list .items:before{content:"\f090";position:absolute;$startSide:0;top:0}
.carousel1 .thumb-outer,.rel-carousel .thumb-outer{margin:0 5px}
.carousel .thumb-area > a,.rel-carousel .thumb-area > a{height:135px}
.carousel .content-area,.rel-carousel .content-area{padding:0 5px;margin-top:10px}
.carousel .owl-controls .owl-nav div,.rel-carousel .owl-nav div{z-index:2;margin-top:-10px}
.carousel .owl-dots,.rel-carousel .owl-dots{position:relative;bottom:0;margin-top:5px}
.carousel .content-area h3,.rel-carousel .content-area h3{font-size:14px}
.carousel2 .thumb-area,.sidebar .video .widget-content,.slider .thumb-area{border:0}
.hot .widget-content,.carousel2 .thumb-area,.slider .thumb-area,.video .content-area{padding:0}
.hot .widget-area{background-color:$(keycolor)}
.hot .first-item:first-child .first-area h3{color:$(cont.feattext.color)}
.hot .first-item:first-child{padding:15px;color:$(cont.feattext.color)}
.hot .fbig-widget-area a.rcthumb{width:auto;height:180px}
.hot .fbig-widget-area{padding:15px;background-color:#F3F3F3}
.hot .fbig-widget-area .items:first-child{margin-bottom:15px}
.hot .fbig-widget-area .content-area{position:absolute;bottom:15px;right:15px;left:15px;color:$(cont.feattext.color);background-color:rgba(0,0,0,0.7);padding:8px}
.hot .fbig-widget-area h3{color:$(cont.feattext.color)}
.hot .items-inner,.video .items-inner,.newsmoreinfo .items-inner,.featured .items-inner,.grip .items-inner,.mtab .items-inner,.mbig .first-item .items-inner,.mbig .fbig-widget-area .items:nth-child(5) .items-inner,.mbig .fbig-widget-area .items:nth-child(6) .items-inner{margin-bottom:0;border-bottom:0}
.hot .content-area,.newsmoreinfo .content-area{padding-$startSide:0;margin-top:5px}
.video .items{width:32%;margin-$endSide:2%;z-index:0}
.video .widget-content{padding:10px 0}
.gallery1 .fbig-widget-area .items{width:33.33333%}
.gallery1 .first-item:first-child{padding-$endSide:330px}
.gallery1 .fbig-widget-area,.gallery2 .fbig-widget-area{width:330px;position:absolute;$endSide:0;top:0}
.video .items:nth-child(3),.video .items:nth-child(6),.video .items:nth-child(9){margin-$endSide:0}
.video .rcthumb{height:150px;width:auto}
.video .content-area h3{margin-top:10px}
.video .items-inner{height:240px;border-bottom:0}
.video .thumb-area:hover .youtubeplay .fa{opacity:0;-webkit-transform:scale(0);-moz-transform:scale(0);transform:scale(0)}
.gallery1 .rcthumb{height:76px;width:auto}
.gallery1 .first-item:first-child a.rcthumb{height:252px}
.gallery1 .first-item:first-child .items-inner{padding-$endSide:10px;padding-bottom:10px}
.gallery1 .widget-content,.gallery2 .widget-content,.featured .items-inner,.newsmoreinfo .items-inner,.grip .items-inner,.mtab .items-inner,.hot .items-inner{padding-bottom:0}
.gallery1 .fbig-widget-area .items-inner{margin:0 0 5px 5px}
.gallery2 .rcthumb{height:95px;width:auto}
.gallery2 .first-item:first-child{padding-$startSide:350px}
.gallery2 .fbig-widget-area{width:350px;$endSide:auto;$startSide:0}
.gallery2 .first-item:first-child a.rcthumb{height:201px}
.gallery2 .first-item:first-child .items-inner{padding-$startSide:10px;padding-bottom:10px}
.gallery2 .fbig-widget-area .items-inner{margin:0 5px 5px 0}
.gallery3 .items{width:33%;float:$startSide;margin-$endSide:0.5%}
.gallery3 .items:nth-child(3),.gallery3 .items:nth-child(6),.gallery3 .items:nth-child(9){margin-$endSide:0}
.gallery3 .rcthumb,.newsmoreinfo a.rcthumb{width:auto;height:140px}
.gallery3 .items .items-inner{margin-bottom:5px}
.gallery1 .wid-pagenumber,.gallery2 .wid-pagenumber{margin-bottom:10px;margin-top:10px}
.sidebar .newsticker .widget-content{padding:0;margin:15px 0 0;border:0;background-color:transparent;border:0}
.home-area .sidebar .newsticker .widget-content{margin-bottom:15px}
.newsticker .rpstmetainfo{position:absolute;$startSide:7px;top:7px;margin-top:0;opacity:1;border-$endSide:2px solid;height:15px;line-height:15px}
.newsticker .content-area h3{margin-$startSide:70px;margin-top:6px;font-size:14px}
.newsticker .content-area h3 a{text-decoration:none}
.newsmoreinfo{position:absolute;z-index:2;width:320px;padding:15px;background-color:$(cont.featback.color);color:$(cont.feattext.color);margin-top:10px}
.newsmoreinfo.botwid{margin-top:0}
.newsmoreinfo h3,.featured .content-area h3{color:$(cont.feattext.color);font-size:17px;max-height:none}
.newsmoreinfo .rpstmetainfo{margin:8px 0}
.newsmoreinfo .psummary{font-size:14px;opacity:0.8}
.newsmoreinfo.hovergallery{margin-top:80px}
.rcptags{position:absolute}
.newsmoreinfo .rcptags{top:15px;$endSide:15px}
.featured .rcptags{$endSide:0;top:-15px}
.featured .thumb-area{padding:2px;border:0}
.sidebar .featured .widget-content{padding:5px;margin-top:15px}
.featured{padding-bottom:15px;z-index:0}
.featured1 .items{height:190px}
.featured2 .items,.featured3 .items{height:200px}
.featured2 .items{width:33.3333%}
.featured1 .items,.featured2 .items:nth-child(1),.featured2 .items:nth-child(2),.mbig .fbig-widget-area .items{width:50%}
.featured1 .items:nth-child(1){height:380px}
.featured1 .items:nth-child(3),.featured1 .items:nth-child(4){width:25%}
.featured .thumb-outer,.featured .items-inner,.featured .thumb-area,.featured .thumb-area a{height:100%}
.featured .content-area{position:absolute;bottom:0;padding:14px}
.featured .psummary{font-size:90%;margin-top:8px}
.featured .content-area{left:15px;bottom:15px;right:15px;background-color:rgba(0,0,0,0.5);color:$(cont.feattext.color);z-index:2}
.featured .items .content-area:hover,.rcptags a:hover{background-color:$(cont.featback.color)}
.featured1 .items:nth-child(3) .psummary,.featured1 .items:nth-child(4) .psummary,.featured1 .owl-dots,.hovergallery .psummary,.hovergallery .postdate,.featured2 .owl-dots,.featured3 .owl-dots,.featured2 .items:nth-child(3) .psummary,.featured2 .items:nth-child(4) .psummary,.featured2 .items:nth-child(5) .psummary,.featured3 .items:nth-child(3) .psummary,.featured3 .items:nth-child(4) .psummary,.featured3 .items:nth-child(5) .psummary,.feat-wrapitem:last-child .psummary,.feat-wrapitem:last-child .rcptags,.mbig .postdate{display:none!important}
.featured3 .items:nth-child(1){width:60%}
.featured3 .items:nth-child(2){height:400px;width:40%}
.featured3 .items:nth-child(3),.featured3 .items:nth-child(4),.featured3 .items:nth-child(5){width:20%}
.rcptags a{display:inline-block;color:$(butext.color);background-color:$(keycolor);padding:0 5px;text-decoration:none}
.featured4 .content-area h3{font-size:23px}
.featured4 .owl-item,.featured4 .owl-item .thumb-outer{height:400px}
.featured4 .thumb-area{padding:0}
.featured4 .owl-item .content-area{position:absolute;bottom:40px;z-index:1;text-align:center;left:15px;right:15px;opacity:0}
.featured4 .owl-dots{left:50%;margin-left:-57px;width:114px}
.featured4 .owl-nav > div{top:0;height:400px;line-height:400px;font-size:40px;background-color:transparent!important;opacity:1!important;margin-top:0}
.featured4 .owl-nav > div:hover{background-color:transparent}
.featured4 .psummary{display:block;font-size:15px}
.featured4 .rpstmetainfo > span,.featured4 .rpstmetainfo .fa{float:none}
.featured4 .owl-item .items:before{content:"";position:absolute;display:block;height:100%;width:100%;background-color:rgba(0,0,0,0.3);z-index:1}
.featured4 .center .content-area,.item-share a:hover span{opacity:1}
.featured4 .center .items:before{display:none}
.feat-wrapitem,.feat-wrapitem:first-child .items{height:380px}
.feat-wrapitem:first-child .items{width:100%}
.feat-wrapitem a.rcthumb{width:auto}
.feat-wrapitem:first-child{margin-$startSide:450px;width:auto}
.feat-wrapitem:last-child{position:absolute;top:0;$startSide:0;width:450px}
.feat-wrapitem:last-child .items{height:120px;margin-bottom:10px;float:none}
.feat-wrapitem:last-child .items-inner{margin-$endSide:15px}
.feat-wrapitem:first-child .content-area{bottom:35px}
.feat-wrapitem:last-child .content-area{background-color:transparent!important;padding:0}
.grip .items,.mtab .items{width:23.5%;margin-$endSide:2%}
.grip .items:last-child,.mtab .items:last-child{margin-$endSide:0}
.grip a.rcthumb,.mtab a.rcthumb{width:auto;height:120px}
.mega-menu .content-area h3{color:$(header.text.color)}
.grip h3,.mtab h3{margin-top:10px}
.grip .content-area{position:static}
.grip .rcptags{top:10px;$startSide:10px}
.grip .content-area,.mtab .content-area{padding-$startSide:0}
.mtab .tab-content{margin-$startSide:200px}
.mega-menu > .sub-menu > li{z-index:0}
.mtab .tab-wrapper{display:block;width:200px;$startSide:0;top:20px}
.mtab .simpleTab .tab-wrapper li{float:none;width:auto;display:block}
.mtab .tab-wrapper li a{height:30px;line-height:30px;text-align:left;display:block;border-radius:0;background-color:transparent}
.mega-menu .mtab{margin:-15px}
.mtab .tab-wrapper li a.activeTab,.mtab .tab-content{background-color:$(header.bottom1.color)}
.mtab .simpleTab{margin:0}
.mbig .first-item{width:380px;padding-$endSide:15px;position:absolute;float:none;z-index:2}
.mbig .fbig-widget-area{padding-$startSide:380px;padding-bottom:5px}
.mbig .fbig-widget-area .items-inner{border-bottom:1px solid $(header.bottom1.color);margin-right:10px;margin-left:10px}
.mbig .first-item:first-child a.rcthumb{height:140px}
.mbig .first-item:first-child .first-area h3{color:$(header.text.color);font-size:18px;max-height:63px}
.mbig .first-item .psummary{font-size:14px}
.mega-menu a.menu-morepost{position:absolute;$endSide:-15px;bottom:-15px;min-width:0;padding:0;background-color:transparent;width:40px;color:$(butext.color);height:40px;margin:0}
.mega-menu .mtab a.menu-morepost{$endSide:0;bottom:0}
.mega-menu a.menu-morepost .fa{z-index:2;position:absolute;$endSide:7px;bottom:5px;margin-$endSide:0}
.mega-menu a.menu-morepost:after{content:"";position:absolute;$endSide:0;margin-top:-2px;height:0;width:0;border:20px solid transparent;border-bottom-color:$(keycolor);border-$endSide-color:$(keycolor);bottom:0}
.submenu .loading:before{content:"";width:100%;height:150px;display:block;background:url(http://2.bp.blogspot.com/-F1ZoS1Ns3h4/VWXkqjEuUoI/AAAAAAAAAbs/Q415Cu_-75I/s1600/anim_loading_sm_082208.gif) 50% 50% no-repeat}
.loadinghtml #top-featured .widget-content {height:390px}
.pagenumber a.bottom-morepost{display:none}
.blogpost .widget-content,.halfpost .widget-content,.bigpost .widget-content{border:0!important;padding:0}
.bigpost .items-inner > div,.halfpost .items-inner > div,.mkblock .psummary{display:block;padding:0}
.wid-pagenumber{overflow:hidden;margin-top:15px}
.blogpost a.rcthumb{width:240px;height:150px}
.blogpost h3,.bigpost h3{font-size:22px;max-height:52px}
.mkblock .rcreadMore,.handle{overflow:hidden}
.mkblock .items-inner{border-bottom:0}
.mkblock a.readmorebut{float:$startSide;font-size:12px;padding:5px 10px;border-radius:2px;margin-top:5px}
.mkblock .thumb-outer{z-index:0}
.blogpost .items:last-child .items-inner{padding-bottom:10px}
.handle:before{background-color:#FFF;position:absolute;top:0;left:0;right:0;bottom:0;content:"";z-index:10;opacity:0.6}
.halfpost .items{width:48.5%;float:$startSide;margin-$endSide:3%}
.halfpost .items:nth-child(even){margin-$endSide:0}
.halfpost a.rcthumb{width:auto;height:180px}
.halfpost .thumb-outer{margin-bottom:15px}
.halfpost .content-area h3{font-size:20px;max-height:48px}
.mkblock .psummary{margin-top:8px}
.bigpost a.rcthumb{width:auto;height:320px}
.bigpost .thumb-outer{margin-bottom:15px}
.simplepost a.rcthumb{width:60px;height:60px}
.simplepost .items-inner{margin-bottom:7px;padding-bottom:7px}
.simplepost .review-place{width:25px;height:25px;line-height:25px;font-size:14px}
.simplepost .review-place .slice{width:17px}
.simplepost .post-type{font-size:22px}
.simplepost .wid-pagenumber .actual,.simplepost .wid-pagenumber a{font-size:12px;line-height:26px;width:26px;height:26px}
.have-pfeatured .bread-title,.post-featured,.hide,.ads-widget-sec .adsbygoogle,.sbreakline h4,.sbreakline .rpstmetainfo{display:none}
.post-featured{padding:3px;border:1px solid $(cont.border.color);margin-bottom:8px;border-radius:2px}
.post-featured.show,.post-featured a{display:block}
.post-featured img{width:100%}
a.itemcommentnum span{margin-$endSide:5px}
.locked-content{text-align:center;border:1px solid $(cont.border.color)}
.locked-content .fa{font-size:50px}
.locked-content .inner{margin:10px;background-color:rgba(0,0,0,0.07);padding:20px}
.locked-content-action{display:inline-block;vertical-align:top;margin:0 15px}
.locked-content h2{margin:10px 0}
.locked-content h3{margin:10px 0 20px}
.pcaption{position:absolute;z-index:2;bottom:40px;padding:8px 10px;background-color:rgba(0,0,0,0.8);color:#FFF;font-size:18px;$startSide:0}
.post-featured .owl-item img{height:100%}
.post-featured .owl-item,.post-featured .owl-item > *{height:350px}
.adstitle{margin-bottom:10px}
.adsbottom{margin-top:10px}
.adsbygoogle{display:inline-block}
.adspltop > .adsbygoogle,.adsplbottom > .adsbygoogle,.adsinside-it .adsbygoogle{min-width:300px;max-width:970px;width:100%;height:90px}
.adsinside-it{margin:15px auto}
.post-body .adsbygoogle iframe{margin-bottom:0}
.hvbreakline .adsbygoogle{width:300px;height:250px}
.hvbreakline{text-align:$startSide}
.hvbreakline .adspltop,.hvbreakline .adsplbottom{z-index:2}
.hvbreakline .topbreakline{padding-$startSide:15px}
.hvbreakline > div{display:table-cell;vertical-align:middle}
.hvbreakline .bottombreakline{padding-$endSide:15px;width:600px}
.dexcerpt{padding:10px;background-color:rgba(0,0,0,0.06);margin-bottom:10px}
.dexcerpt p{margin:0}
.sbreakline .content-area h3{font-size:14px;max-height:32px;color:$(keycolor);margin-bottom:10px;padding-$startSide:16px}
.sbreakline .items:last-child .content-area h3{margin-bottom:0}
.sbreakline .content-area h3:before{content:"\f005";$startSide:0;font-size:10px;top:0;position:absolute}
.sbreakline .content-area h3:hover{opacity:0.7}
.sbreakline .items-inner{margin-bottom:0;padding-bottom:0;border-bottom:0}
.sbreakline .content-area{padding-$startSide:0}
.loadinghtml .post-outer{opacity:0}
.complex .tab-wrapper{position:absolute;top:-29px;$endSide:0;background-color:$(outer.background.color)}
.complex .tab-content{padding:0;background-color:transparent;}
.complex .simpleTab{margin:0;position:static}
.complex .tab-wrapper li{width:auto}
.complex .tab-wrapper a{height:19px;line-height:19px;font-size:70%;padding:0 5px;margin-$startSide:3px;border-radius:2px;text-transform:uppercase;background-color:rgba(0,0,0,0.11)}
.FeaturedPost .post-summary{background-color:$(keycolor);color:#FFF;padding:8px;border-radius:2px}
.FeaturedPost .post-summary > h3{font-size:19px;margin:0 0 10px}
.FeaturedPost .post-summary a{color:#FFF}
.FeaturedPost .post-summary img{min-height:180px}
.hot .wid-pagenumber{padding:0;margin:0;position:absolute;bottom:10px;$startSide:10px}
.hot .wid-pagenumber a{background-color:$(cont.background.color);color:$(main.text.color)}
.hot .wid-pagenumber .actual,.hot .wid-pagenumber a,.column .wid-pagenumber .actual,.column .wid-pagenumber a,.timeline .wid-pagenumber .actual,.timeline .wid-pagenumber a,.list .wid-pagenumber .actual,.list .wid-pagenumber a{font-size:80%;width:26px;height:26px;line-height:26px}
/*====================================
= F. Posts Section
=====================================*/
.widget.Blog{margin-bottom:25px}
.index .blog-posts.hfeed,.archive .blog-posts.hfeed{overflow:hidden;padding-top:10px;margin:0 -7px}
.index .post-outer,.archive .post-outer{width:33.333%;float:$startSide}
.index .post-outer.list,.archive .post-outer.list{width:100%;float:none}
.index .post,.archive .post{padding:0 7px;min-height:210px}
.index .list .post,.archive .list .post{min-height:190px}
.summary-content,.bottommeta,.topmetainfo,.msg-wrap{display:none}
.summary-content{margin:5px 0 10px}
.list .summary-content,.list .bottommeta,.list .topmetainfo{display:block}
.post-title{color:$(cont.postitle.color)}
.post-title a{color:inherit;-webkit-transition:none;-moz-transition:none;-ms-transition:none;-o-transition:none;transition:none}
.post-title a:hover,.post-title a:focus{text-decoration:none}
.post-title:hover,.thumb-area:hover > a,.topmetainfo,.view span,.PopularPosts .item-thumbnail:hover a,.rpstmetainfo,.sevida-widget h2 a:hover,.widget-area h3 a:hover,a.rcomment-img:hover img,.dsq-widget-item a:hover img,.linkgrey{opacity:0.75;filter:"alpha(opacity=75)";-ms-filter:"alpha(opacity=75)"}
.view .active,.timeline .items:hover .thumb-outer,.carousel:hover .owl-nav div,.rel-carousel:hover .owl-nav div,a.jdshrt-tooltip:hover > span{opacity:1;filter:"alpha(opacity=100)";-ms-filter:"alpha(opacity=100)"}
.thumb-area{border:1px solid $(cont.border.color);background-color:$(cont.background.color);-moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;padding:3px}
.latest-img{margin-bottom:10px;padding:4px}
.latest-img:before,.latest-img:after,.first-item:first-child .thumb-area:before,.first-item:first-child .thumb-area:after,.slider .widget-content:before,.slider .widget-content:after,.carousel1 .thumb-area:before,.carousel1 .thumb-area:after,.video .thumb-area:before,.video .thumb-area:after,.newsmoreinfo .thumb-area:before,.newsmoreinfo .thumb-area:after,.featured .widget-content:before,.featured .widget-content:after,.mtab .thumb-area:before,.mtab .thumb-area:after,.grip .thumb-area:before,.grip .thumb-area:after,.manualslide .widget-content:before,.manualslide .widget-content:after,.related_posts .thumb-area:before,.related_posts .thumb-area:after,.mkblock .thumb-area:before,.mkblock .thumb-area:after{content:"";position:absolute;z-index:-2;bottom:15px;left:5px;width:50%;height:20%;max-width:300px;-webkit-box-shadow:0 15px 10px rgba(0,0,0,0.6);-moz-box-shadow:0 15px 10px rgba(0,0,0,0.6);box-shadow:0 15px 10px rgba(0,0,0,0.6);-webkit-transform:rotate(-3deg);-moz-transform:rotate(-3deg);-ms-transform:rotate(-3deg);-o-transform:rotate(-3deg);transform:rotate(-3deg)}
.latest-img:after,.first-item:first-child .thumb-area:after,.slider .widget-content:after,.carousel1 .thumb-area:after,.video .thumb-area:after,.newsmoreinfo .thumb-area:after,.featured .widget-content:after,.mtab .thumb-area:after,.grip .thumb-area:after,.manualslide .widget-content:after,.related_posts .thumb-area:after,.mkblock .thumb-area:after{right:5px;left:auto;-webkit-transform:rotate(3deg);-moz-transform:rotate(3deg);-ms-transform:rotate(3deg);-o-transform:rotate(3deg);transform:rotate(3deg)}
.thumb-area > a{display:block;height:65px;width:90px}
.latest-img > a{width:100%;height:140px}
.list .latest-img{float:$startSide;margin-$endSide:10px;width:250px}
.list .latest-img > a{height:160px}
.post-type{position:absolute}
.post-outer{z-index:0}
h3.post-title{margin:0;font-size:14px}
.grid h3.post-title{overflow:hidden;max-height:40px;line-height:1.4em}
.list h3.post-title{font-size:22px;margin-bottom:10px}
.item-control{position:absolute;top:124px;$startSide:15px}
.list .item-control{top:144px}
.topmetainfo,.bottommeta,.post-content{overflow:hidden}
.topmetainfo,.bottommeta{font-size:12px}
.topmetainfo a{color:inherit}
.topmetainfo .labelqi{color:$(keycolor)}
.topmetainfo > span,.bottommeta > *,.topmetainfo .infometa,.topmetainfo .fa{float:$startSide}
.topmetainfo > span{margin-$endSide:10px}
.topmetainfo .fa,.topmetainfo .infometa{display:block;line-height:17px}
.topmetainfo .fa{margin-$endSide:5px}
.bottommeta{padding:5px 0}
.bottommeta > *{padding:5px 10px;border-radius:3px}
a.readmorebut{display:block;background-color:$(keycolor);color:$(butext.color);text-decoration:none}
a.readmorebut:hover{background-color:$(button.color)}
.sharesbottom{margin-$startSide:10px;background-color:$(cont.botback.color);box-shadow:0 0 2px rgba(0,0,0,0.2);cursor:pointer}
.active .sharesbottom{box-shadow:inset 0 0 3px rgba(0,0,0,0.2);background-color:$(cont.botback2.color)}
.postdate{position:absolute;z-index:1;background-color:$(keycolor);color:$(butext.color);padding:3px 0;top:0;$startSide:20px;display:block;font-family:Verdana,Geneva,sans-serif;text-align:center}
.shclick .postdate{display:none}
.post:hover .postdate,.items:hover .postdate{background-color:$(button.color)}
.postdate > *{display:block;padding:0 2px}
.postdate strong{font-size:21px;line-height:23px}
.postdate span,.postdate small{font-size:9px;height:12px;line-height:12px}
.youtubeplay{position:static}
.youtubeplay .fa{position:absolute;top:50%;left:50%;text-align:center;width:32px;height:32px;margin-left:-16px;margin-top:-16px;line-height:32px;font-size:32px;color:#FFF}
a:hover .youtubeplay .fa,.post-type{opacity:0}
a.loadpost,a.bottom-morepost{color:$(butext.color);background-color:$(keycolor);font-size:14px;display:block;max-width:80%;margin:0 auto;padding:5px 0;text-decoration:none;border-radius:2px}
a.bottom-morepost{margin-top:10px}
a.loadpost:active,a.bottom-morepost:active{top:1px}
.sharesbottom span:after,.sharesinfo span:after{content:"Share"}
.sharesinfo .icons-twitter span:after{content:"Tweet"}
.sharesbottom span:after{margin-$startSide:5px}
.wasupport .icons-whatsapp {display:inline-block}
.plabels{position:absolute;background-color:$(outer.background.color);box-shadow:0 1px 5px rgba(0,0,0,0.4);min-width:220px;border-radius:2px;padding:10px;font-size:14px;top:33px;display:none;max-height:330px}
.plabels .label-name{text-decoration:none;display:block;padding:1px 4px}
.plabels:before,.plabels:after{border-width:10px 10px;border-style:solid;border-color:transparent transparent $(outer.background.color) transparent;content:"";$startSide:40px;width:0;height:0;position:absolute;z-index:4;bottom:100%}
.plabels:after{border-width:11px 11px;border-color:transparent transparent $(cont.border.color) transparent;z-index:3;$startSide:39px}
.plabelsbtn{cursor:pointer;padding-$endSide:15px}
.plabelsbtn:before{content:"\f0dc";position:absolute;$endSide:2px;font-size:11px;top:3px}
.plabels .label-count{color:$(butext.color);background-color:$(keycolor);text-align:center;width:17px;display:inline-block;font-size:11px;line-height:15px;border-radius:2px}
.post-type .video:before{content:"\f144"}
.post-type .music:before{content:"\f001"}
.post-type .gallery:before{content:"\f03e"}
.post-type .text:before{content:"\f0f6"}
.post-type .quote:before{content:"\f10e"}
.post-type .fa:first-child{display:inline-block}
.post-type{width:32px;height:32px;line-height:32px;top:50%;left:50%;margin-top:-16px;margin-left:-16px;font-size:26px;text-align:center;color:#FFFFFF;z-index:2;text-shadow:0 1px 4px rgba(0,0,0,0.5)}
.blog-pager >span,.wid-pagenumber > *{float:$startSide;margin-$endSide:5px}
.showpageNum a,.showpagePoint,.showpage a,.wid-pagenumber .actual,.wid-pagenumber a{display:inline-block;width:32px;height:32px;line-height:32px;text-align:center;color:$(butext.color);background-color:$(keycolor);border-radius:2px;text-decoration:none}
.showpageNum a:hover,.showpagePoint,.showpage:hover,.wid-pagenumber .actual{background-color:$(button.color)}
.wid-pagenumber a:hover{background-color:$(button.color)!important}
.separator > a{margin:0 auto 1.2em!important;max-width:100%;display:block}
.separator > a[style*="float:right"],.separator > a[style*="float: right"]{margin-left:1em!important}
.separator > a[style*="float:left"],.separator > a[style*="float: left"]{margin-right:1em!important}
table.tr-caption-container{padding:0;margin-bottom:1em}
.post .tr-caption-container tr:nth-child(2) .tr-caption{padding-top:8px;font-size:90%;opacity:0.9}
.post-body img{max-width:100%;height:auto}
.post-body iframe{margin-bottom:15px;max-width:100%}
.glpost{overflow:hidden;margin-bottom:15px}
.post-body .glpost > *{width:33.333333%;display:block;float:$startSide;height:150px;padding:2px;overflow:hidden;border:0}
.glpost a img{height:100%;width:100%}
.breadcrumbs{border-radius:2px;border:1px solid $(cont.border.color);height:28px;line-height:26px;overflow:hidden;font-size:14px;padding:0 10px;margin-bottom:8px}
.breadcrumbs span,.breadcrumbs .fa{float:$startSide;line-height:inherit}
.breadcrumbs .fa{margin:0 5px}
.rtl .breadcrumbs .fa-angle-right:before{content:"\f104"}
.item .post,.static_page .post{border:1px solid $(cont.border.color);border-radius:2px;padding:10px}
.item .postdate{$startSide:10px}
.post-title.h1{margin:0;font:$(cont.title.font);border-bottom:1px solid $(cont.border.color);padding-bottom:10px;padding-$startSide:40px;font-weight:600;line-height:1.2em}
.static_page .post-title.h1{padding-$startSide:0}
.post-body img{padding:4px;border:1px solid $(cont.border.color)}
.post-body ul li:before{content:"\f05d";font-size:14px;position:absolute;$startSide:-20px;top:1px}
.item .item-control,.static_page .item-control{$endSide:5px;$startSide:auto;top:5px}
.item-topmeta{margin-top:5px;overflow:hidden;margin-bottom:15px}
.item-topmeta > span{margin-$endSide:10px}
.item-topmeta > span,.item-topmeta > span *{float:$startSide;line-height:inherit}
.item-topmeta > span .fa{margin-$endSide:5px}
.more-options{float:$endSide;padding-$endSide:32px}
.item-topmeta{font-size:14px;line-height:25px}
.item-topmeta a{color:inherit}
.more-options a{color:$(butext.color);background-color:$(keycolor);padding:0 8px;display:inline-block;height:25px;border-radius:2px;font-size:14px;text-decoration:none;float:$startSide;margin-$startSide:5px}
.text-finder-area{position:absolute;$endSide:0}
.btntextFind{color:$(butext.color);position:absolute;$endSide:0;top:0;width:25px;height:25px;background-color:$(keycolor);text-align:center;border-radius:2px;cursor:pointer}
.more-options a:hover,.btntextFind:hover{background-color:$(button.color)}
.text-finder{margin-$endSide:32px;height:25px;background-color:$(butext.color);display:none}
.active .text-finder{display:block}
.text-finder input{height:25px;line-height:21px;outline:0;border:1px solid $(cont.border.color);border-radius:2px;float:$startSide}
.text-finder input[type="text"]{width:182px;margin-$endSide:5px}
.text-finder input[type="reset"]{background-color:transparent;border:0;font-weight:600;font-size:22px;width:20px;padding:0}
span.highlight{background-color:$(keycolor);color:#FFF}
.tab-facebook,.fb_iframe_widget_fluid span,.fb_iframe_widget iframe{width:100%!important}
.bottom-infoitem{padding:10px;margin:10px -10px -10px;border-top:1px solid $(cont.border.color);background-color:$(cont.botback.color)}
.item-share{height:28px;margin:10px 0 0}
.item-share a{float:$startSide}
.item-share a{display:block;margin-$endSide:2%;height:28px;line-height:28px;color:$(butext.color);text-decoration:none;text-align:center;width:15%;z-index:0}
.item-share a:last-child{margin-$endSide:0}
.item-share .fa{display:block;height:28px;line-height:28px;border-radius:2px;width:32px;position:absolute}
.item-share span{padding:0 5px;font-size:14px;color:$(button.color);height:28px;display:block;position:absolute;padding-$startSide:40px;background-color:$(butext.color);z-index:-1;box-shadow:0 1px 3px rgba(0,0,0,0.4);border-radius:2px}
.item-share b{float:$endSide;padding:0 7px;margin-$startSide:5px;background-color:rgba(0,0,0,0.08);font-weight:300;font-size:12px}
.item-share .dhref-done span{padding-$endSide:0}
.item-share span:before{content:"Share"}
.item-share .icons-twitter span:before{content:"Tweet"}
.wasupport .item-share a {width:12.5714%}
.authorProfile{overflow:hidden;margin:10px -10px -10px;background-color:$(cont.botback.color);border-top:1px solid $(cont.border.color)}
.authorProfile p{margin:0}
.authorInner{padding:20px;overflow:hidden}
.authorProfile h3{margin:0;font-size:20px}
.autorMeta{float:$startSide;text-align:center;margin-$endSide:15px}
.autorMeta span{display:block;overflow:hidden;border:1px solid $(cont.border.color);border-radius:2px;padding:4px}
.autorMeta img{width:80px;height:80px}
.authorTitle{overflow:hidden;margin-bottom:10px}
.authorTitle > *{display:inline-block}
.authorSocial{position:absolute;z-index:2;$endSide:0;top:0}
.authorSocial a{display:inline-block;color:$(butext.color);width:20px;height:20px;line-height:20px;margin-$startSide:10px;text-decoration:none;text-align:center}
.blog-pager-item{margin:15px 0;overflow:hidden}
.blog-pager-item a{text-decoration:none}
.blog-pager-item .pager-isi > a:before,.item .linkgrey:before{position:absolute;font-size:24px;height:24px;line-height:24px;top:50%;margin-top:-12px}
.blog-pager-item .pager-isi > a:hover:before{color:$(keycolor)}
a.blog-pager-newer-link-item,a.blog-pager-older-link-item,.linkgrey{width:50%;display:block;color:inherit;float:$startSide}
a.blog-pager-older-link-item,.linkgrey.right{text-align:$endSide}
a.blog-pager-newer-link-item,.linkgrey.left{padding-$startSide:30px}
a.blog-pager-older-link-item,.linkgrey.right{padding-$endSide:30px}
a.blog-pager-older-link-item > span,a.blog-pager-newer-link-item > span,.linkgrey span{font-weight:600;font-size:18px}
.linkgrey.left span:after{content:"Next"}
.linkgrey.right span:after{content:"Previous"}
.pager-summary{position:absolute;bottom:100%;opacity:0;background-color:$(outer.background.color);font-size:12px;text-align:$endSide;padding:5px;border:1px solid $(cont.border.color);box-shadow:0 1px 3px rgba(0,0,0,0.1)}
.pager-summary h4{margin:0 0 8px;font-size:16px}
.blog-pager-item a:hover .pager-summary{opacity:1}
a.blog-pager-older-link-item:before,.linkgrey.right:before,.rtl a.blog-pager-newer-link-item:before,.rtl .linkgrey.left:before{content:"\f054"}
a.blog-pager-newer-link-item:before,.linkgrey.left:before,.rtl a.blog-pager-older-link-item:before,.rtl .linkgrey.right:before{content:"\f053"}
a.blog-pager-older-link-item:before,.linkgrey.right:before{$endSide:2px}
a.blog-pager-newer-link-item:before,.linkgrey.left:before{$startSide:2px}
.pager-summary img{height:100px;width:100px;display:block;border:1px solid $(cont.border.color);padding:2px}
.pager-summary p{margin:0}
a.blog-pager-newer-link-item img{float:$endSide;margin-$endSide:5px}
a.blog-pager-older-link-item img{float:$startSide;margin-$startSide:5px}
.oldernewerleft .pager-summary{$startSide:30px}
.oldernewerright .pager-summary{$endSide:30px}
.oldernewerright .pager-summary{text-align:$startSide}
.related_posts .widget-area{padding:10px;}
.rel-carousel .widget-area{opacity:0}
.rel-carousel .widget-area.owl-loaded{opacity:1}
.item .related_posts .postdate{$startSide:20px}
.cst-social-share{position:fixed;top:10%;z-index:22;left:10%;right:10%;bottom:10%;display:none}
.cst-social-share.cst-show{display:block}
.cst-share-inner{margin:0;position:absolute;left:20%;right:20%;top:10%}
.cst-share-item{width:33.3333%;float:$startSide}
a.cst-share{display:block;width:70px;height:70px;margin:0 auto 10px;text-align:center;line-height:70px;font-size:24px;text-decoration:none;border-radius:3px;color:$(butext.color);box-shadow:0 0 5px rgba(0,0,0,0.4)}
a.cst-share span{display:none}
.landscape .cst-share-inner{left:10px;right:10px;top:10px}
.landscape .cst-share-item{width:25%}
.cst-close{position:absolute;color:$(butext.color);width:48px;height:48px;line-height:48px;background-color:rgba(0,0,0,0.6);z-index:99;$endSide:-11%;top:-11%;text-align:center;font-size:20px}
.post-summary{padding-top:0}
/*=====================================
= G. Blogger Comments
=====================================*/
.comments-tabs.simpleTab{margin:0}
.comments-tabs-header .tab-wrapper{position:absolute;top:0;$endSide:0;background-color:$(outer.background.color);padding:0 5px!important}
.comments-tabs-header .tab-wrapper li{width:auto;text-transform:uppercase}
.comments-tabs-header .tab-wrapper a{height:20px;line-height:20px;padding:0 10px;border-radius:2px;font-size:12px;background-color:$(button.color);margin-$startSide:5px;color:$(butext.color)}
.comments-tabs .tab-content,.comments .comments-content .inline-thread,.related_posts .widget-area{border:1px solid $(cont.border.color);-moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px}
.comments-tabs .tab-content{background-color:transparent}
.comments .comments-content .comment-thread ol{margin:0}
.comments .comments-content .comment:first-child{padding-top:0}
.comments .comments-content .inline-thread{border-$startSide:2px solid $(keycolor)}
.comments .continue a,.comments .comments-content .comment-thread ol .comment-replybox-thread{-moz-box-shadow:inset 0 1px 5px rgba(0,0,0,0.22);-webkit-box-shadow:inset 0 1px 5px rgba(0,0,0,0.22);box-shadow:inset 0 1px 5px rgba(0,0,0,0.22);background-color:$(cont.botback.color)}
.comments .comments-content .inline-thread .comment:first-child{padding-top:12px}
.comments .comments-content .comment-header > *{display:inline-block}
.icon.blog-author:before{content:"\f007"}
.item .comments .item-control,.static_page .comments .item-control{position:static}
.emo-button{background-color:$(keycolor);color:$(butext.color);padding:3px 5px;display:inline-block;margin-bottom:10px;border-radius:3px}
.emo-button .fa{margin-$endSide:5px}
/*=====================================
= H. Sidebar Section
=====================================*/
.sidebar-right > .innerwrap{padding-$startSide:20px}
.sidebar-left > .innerwrap{padding-$endSide:20px}
.sidebar-right > .innerwrap,.sidebar-left > .innerwrap{margin-bottom:15px}
.hline{background-image:-webkit-linear-gradient(45deg,rgba(0,0,0,0.10) 25%,transparent 25%,transparent 50%,rgba(0,0,0,0.1) 50%,rgba(0,0,0,0.10) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(0,0,0,0.10) 25%,transparent 25%,transparent 50%,rgba(0,0,0,0.1) 50%,rgba(0,0,0,0.10) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(0,0,0,0.10) 25%,transparent 25%,transparent 50%,rgba(0,0,0,0.1) 50%,rgba(0,0,0,0.10) 75%,transparent 75%,transparent);-webkit-background-size:6px 6px;background-size:6px 6px;display:block;height:11px;background-color:$(outer.background.color);position:absolute;width:100%;top:4px}
.sidebar .widget{margin-bottom:15px}
.sidebar .widget-content{border:1px solid $(cont.border.color);background-color:$(cont.background.color);border-radius:2px}
.sidebartabs .widget > h2{display:none}
.sidebartabs .tab-content{padding:0;border:1px solid $(cont.border.color);border-top:0}
.sidebartabs .widget-content{border:0}
.sidebartabs .simpleTab .tab-wrapper{padding:0 10px!important;border-bottom:5px solid $(keycolor)}
.sidebartabs .tab-wrapper a{font-size:14px;line-height:32px;height:32px;color:$(butext.color)}
.sidebartabs .tab-wrapper a,a.loadpost:hover,.selected .label-count{background-color:$(button.color)}
a.bottom-morepost:hover{background-color:$(button.color)!important}
.sidebartabs .tab-wrapper a:hover{background-color:$(keycolor)}
.side-fixed{position:fixed!important}
#sidebar-top .widget:last-child{margin-bottom:15px}
.left-post .sidebar-right,.right-post .sidebar-left,.right-side .sidebar-right{right:0;left:auto}
.left-post .sidebar-left,.right-post .sidebar-right,.left-side .sidebar-right{left:0;right:auto}
.left-post .sidebar-right > .innerwrap,.right-post .sidebar-left > .innerwrap,.right-side .sidebar-right > .innerwrap{padding-left:20px;padding-right:0}
.left-post .sidebar-left > .innerwrap,.right-post .sidebar-right > .innerwrap,.left-side .sidebar-right > .innerwrap{padding-right:20px;padding-left:0}
.left-side .sidebar-left,.right-side .sidebar-left,.full-post .sidebar-right,.full-post .sidebar-left{display:none}
.full-post .main-wrapper{padding-left:0;padding-right:0}
/*=====================================
= I. Blogger Widgets
=====================================*/
.PopularPosts .item-thumbnail{float:$startSide;margin:0;margin-$endSide:5px;padding:3px;border:1px solid $(cont.border.color);z-index:2}
.PopularPosts .item-title{padding-bottom:.2em;color:$(cont.postitle.color);font-weight:400;font-size:15px}
.PopularPosts .item-title a{color:inherit}
.PopularPosts .item-snippet{margin-top:5px;line-height:1.4em}
.PopularPosts .item-snippet,.Label{font-size:14px}
.PopularPosts .item-thumbnail img,a.populars-img{padding:0;width:65px;height:65px}
a.populars-img {display:block}
.list-label-widget-content li{padding:3px;margin:1px 0}
.list-label-widget-content li:hover,.plabels a:hover{border-$startSide:3px solid $(keycolor)}
.list-label-widget-content li:nth-child(even),.plabels a:nth-child(even){background-color:$(cont.botback.color);background-color:rgba(0,0,0,0.06)}
.Label a:hover{text-decoration:none}
.cloud-label-widget-content{text-align:$startSide;overflow:hidden}
.label-size{font-size:100%;margin-$endSide:4px;margin-bottom:4px;display:block;background-color:$(keycolor);color:$(butext.color);padding:4px 6px;float:$startSide;border-radius:2px}
.label-size:hover{background-color:$(button.color)}
.label-size a{color:inherit;text-decoration:none}
.sevida-by-email-address{border:0;outline:0;display:block;padding:10px 8px;width:100%;background-color:$(cont.botback.color);background-color:rgba(0,0,0,0.1);margin:10px 0 20px}
.sevida-by-email-address:focus{background-color:$(outer.background.color);box-shadow:0 0 2px $(keycolor)}
.sevida-by-email-submit{display:block;border:0;text-align:center;width:100%;color:$(butext.color);padding:10px 8px;background-color:$(keycolor);text-transform:uppercase;border-radius:2px;outline:0}
.sevida-by-email-submit:hover{background-color:$(button.color)}
.sevida-by-email-submit:active{top:1px}
.sevida-flickr{overflow:hidden;margin-bottom:-8px}
.flickr_badge_image{width:25%;float:$startSide;text-align:center;margin-bottom:10px}
.flickr_badge_image a{display:block;padding:3px;border:1px solid $(cont.border.color);width:70px;height:70px;margin:0 auto}
.flickr_badge_image img{width:100%;height:100%}
.rcomment-item,.widget .dsq-widget-item{margin-bottom:15px;font-size:14px}
a.rcomment-img,.dsq-widget-item > a{display:block;float:$startSide;width:58px;height:58px;padding:3px;border:1px solid $(cont.border.color);border-radius:3px;margin-$endSide:8px;z-index:1}
.rcadmin a.rcomment-img{border-color:$(keycolor)}
a.rcomment-img img,.dsq-widget-avatar{width:100%;height:100%}
a.rcomment-title{text-transform:capitalize}
.rcomment-meta{font-size:11px;margin:5px 0}
.rcomment-info > a:first-child,a.dsq-widget-user{font-weight:700}
.rcomment-info a,.dsq-widget-item a{color:$(keycolor)}
.rcomment-summary{margin:10px 0 0}
.rcomment-summary .emo{max-height:24px}
p.dsq-widget-meta{font-size:12px}
.FBboxSevida{min-height:250px}
.FBboxSevida .widget-content{padding:5px;min-height:226px;}
.reco-inner > h4,.reco-inner .items:nth-child(1){display:none}
.reco-place{position:fixed;bottom:50px;$endSide:-350px;z-index:50;width:350px;background-color:$(outer.background.color);box-shadow:0 0 5px rgba(0,0,0,0.35)}
.reco-place.showIt{$endSide:0}
.reco-place > h4{font-size:16px;margin:10px 0 5px;padding:0 10px}
.reco-inner{padding:5px 10px 10px}
.reco-inner .thumb-area > a.rcthumb{width:70px;height:60px}
.reco-close{position:absolute;top:0;$endSide:0;height:39px;line-height:39px;background-color:$(outer.background.color);width:35px;text-align:center}
/*=====================================
= J. Footer Section
=====================================*/
.footer-area{overflow:hidden;padding:20px 0 0;border-top:5px solid $(keycolor);background-color:$(footer.background.color);color:$(foot.text.color)}
.footer{width:23.5%;float:$startSide;margin-$endSide:2%}
.footer:last-child{margin-$endSide:0}
.footer .thumb-area,.newsmoreinfo .thumb-area,.mega-menu .thumb-area{background-color:$(foot.img.color);border:1px solid $(foot.border.color)}
.footer .title-wrap{background-color:$(footer.background.color)}
.footer .widget > h2{color:$(foot.heading.color)}
.footer .hline,.links-content .hline{background-image:-webkit-linear-gradient(45deg,rgba(0,0,0,0.4) 25%,transparent 25%,transparent 50%,rgba(0,0,0,0.4) 50%,rgba(0,0,0,0.4) 75%,transparent 75%,transparent);background-image:-o-linear-gradient(45deg,rgba(0,0,0,0.4) 25%,transparent 25%,transparent 50%,rgba(0,0,0,0.4) 50%,rgba(0,0,0,0.4) 75%,transparent 75%,transparent);background-image:linear-gradient(45deg,rgba(0,0,0,0.4) 25%,transparent 25%,transparent 50%,rgba(0,0,0,0.4) 50%,rgba(0,0,0,0.4) 75%,transparent 75%,transparent);background-color:#5E5E5E}
.footer .items-inner,.links-content .items-inner{border-bottom:1px solid $(foot.border.color)}
.footer .widget-content{padding:0}
.footer .content-area h3,.footer .first-area h3{color:$(cont.footitle.color)}
.footer .widget{margin-bottom:15px}
.copyright-area{border-top:1px solid $(foot.border.color);padding:8px 0;font-size:14px;margin-top:15px}
.contact-sec{position:fixed;top:50%;left:50%;width:600px;height:386px;margin-left:-300px;margin-top:-193px;z-index:99;background-color:$(outer.background.color);padding:15px;border-radius:2px;box-shadow:0 0 8px rgba(0,0,0,0.6)}
.contact-sec.contact-show{display:block}
.contact-sec .contact-form-widget{max-width:none}
.contact-sec input,.contact-sec textarea{width:100%;max-width:none;border:1px solid rgba(0,0,0,0.14);padding:7px 10px;height:auto;border-radius:2px}
.contact-sec textarea{height:106px}
.contact-sec .contact-form-button{background:$(keycolor);text-transform:uppercase;font-size:16px}
a.contact-close{position:absolute;top:-15px;$endSide:-15px;background-color:$(outer.background.color);width:45px;height:48px;text-align:center;line-height:48px;color:$(keycolor)}
/*=====================================
= K. Error page
=====================================*/
.error-custom{margin-top:15px;border:1px solid $(cont.border.color);padding:15px;border-radius:3px;text-align:center;background-color:$(outer.background.color);background-image:url(http://1.bp.blogspot.com/-XKqVUlnOOBc/UXVCp_hfbEI/AAAAAAAAI_k/KdS4rjvZgkc/s500/Abstract+Floral+Vector+Illustration.png);background-repeat:no-repeat;background-position:right bottom;padding-bottom:220px}
.error-custom span{font-size:30px;margin-bottom:10px;display:block}
.errorsrc input{width:300px;padding:8px 10px;border:1px solid $(cont.border.color);text-align: center}
/*=====================================
= L. Shortcodes
=====================================*/
.first-character{float:$startSide;color:$(keycolor);font-size:75px;line-height:60px;padding-top:3px;padding-$endSide:8px;padding-$startSide:3px;font-family:Georgia}
.post-body .button{display:inline-block;color:$(butext.color)}
.button{border-radius:2px;background:$(keycolor);padding:10px 20px;margin:5px;color:#fff;text-align:center;border:0;cursor:pointer;display:inline-block;text-decoration:none;font-weight:400;color:#fff;-webkit-box-shadow:0 4px 4px -2px rgba(0,0,0,0.1);;box-shadow:0 4px 4px -2px rgba(0,0,0,0.1)}
.button.small{font-size:12px;padding:6px 16px}
.button.medium{font-size:14px;padding:8px 18px}
.button.large{font-size:16px;padding:10px 20px}
.button:hover{-webkit-box-shadow:none;box-shadow:none;color:#fff;text-decoration:none}
.button:active{top:1px}
.red{background:#e74c3c}
.orange{background:#F39C12}
.green{background:#2ecc71}
.blue{background:#3498db}
.purple{background:#9b59b6}
.yellow{background:#FFD600}
.pink{background:#F889EB}
.grey{background:#bdc3c7}
.turquoise{background:#1abc9c}
.midnight{background:#2c3e50}
.asbestos{background:#6d7b7c}
.dark{background:#454545}
.small-button{width:100%;overflow:hidden;clear:both}
.medium-button{width:100%;overflow:hidden;clear:both}
.large-button{width:100%;overflow:hidden;clear:both}
.widget .post-body ul,.widget .post-body ol{line-height:1.5;padding:0;margin:1.5em 0;margin-$startSide:1.8em}
.widget .post-body li{margin:5px 0;padding:0;line-height:1.5}
.widget .post-body ol li{list-style:inherit}
pre{background-color:#F1F1F1;color:#333;position:relative;padding:0 7px;margin:15px 0 10px;overflow:hidden;word-wrap:normal;white-space:pre;position:relative;box-shadow:inset 0 2px 4px 1px rgba(0,0,0,0.05)}
pre[data-codetype]{padding:37px 1em 5px}
pre[data-codetype]:before{content:attr(data-codetype);display:block;position:absolute;top:0;right:0;left:0;background-color:$(keycolor);padding:0 7px;color:#FFFFFF;height:32px;line-height:32px}
pre[data-codetype="HTML"]{color:#5CB85C}
pre[data-codetype="CSS"]{color:#CC0616}
pre[data-codetype="JavaScript"]{color:#F3791F}
pre[data-codetype="JQuery"]{color:#49AADB}
pre[data-codetype="HTML"]:before{background-color:#5CB85C}
pre[data-codetype="CSS"]:before{background-color:#CC0616}
pre[data-codetype="JavaScript"]:before{background-color:#F3791F}
pre[data-codetype="JQuery"]:before{background-color:#49AADB}
pre code,pre .line-number{display:block;color:#069}
pre .line-number{color:#7D7D7D;min-width:2.5em;float:$startSide;text-align:$endSide;margin-$startSide:-1em;margin-$endSide:1em;border-$endSide:2px solid $(cont.border.color)}
pre[data-codetype="HTML"] .line-number{border-$endSide:2px solid #5CB85C}
pre[data-codetype="CSS"] .line-number{border-$endSide:2px solid #CC0616}
pre[data-codetype="JavaScript"] .line-number{border-$endSide:2px solid #F3791F}
pre[data-codetype="JQuery"] .line-number{border-$endSide:2px solid #49AADB}
pre .line-number span{display:block;padding:0 5px}
pre .line-number span:nth-child(even){background-color:#D5D5D5}
pre .cl{display:block;clear:both}
a.jdshrt-tooltip > span{position:absolute;width:300px;right:-15px;bottom:100%;margin-bottom:10px;padding:8px;background-color:$(outer.background.color);border:1px solid $(cont.border.color);border-bottom:3px solid $(keycolor);border-radius:2px;color:$(main.text.color);box-shadow:0 1px 3px rgba(0,0,0,0.15);font-size:85%}
.shrt-message{color:#FFF;margin-bottom:15px;box-shadow:0 1px 2px rgba(0,0,0,0.20);border-radius:2px;padding:10px}
.shrt-success{background-color:#5cb85c}
.shrt-alert{background-color:#5bc0de}
.shrt-warning{background-color:#f0ad4e}
.shrt-update{background-color:#017CB9}
.shrt-info{background-color:#525252}
.shrt-error{background-color:#d9534f}
.headline{font-size:16px;background-color:rgba(0,0,0,0.30);padding:8px 10px;margin:-10px;margin-bottom:10px}
.headline > .fa{margin-$endSide:5px}
.shrt-contact{background-color:$(outer.background.color);margin:30px 0!important}
.shrt-contact .contact-form-widget{max-width:100%!important}
.shrt-contact .contact-form-name,.shrt-contact .contact-form-email,.shrt-contact .contact-form-email-message{display:block;color:#A0A0A0;background-color:#F4F4F4;border:0;border-radius:2px;padding:0;margin-bottom:10px!important;max-width:100%!important;box-sizing:content-box;box-shadow:inset 0 1px 2px rgba(0,0,0,.2)}
.shrt-contact .contact-form-name{width:45%;height:40px;float:$startSide}
.shrt-contact .contact-form-email{width:46%;height:40px;float:$endSide;}
.shrt-contact .contact-form-name,.shrt-contact .contact-form-email{padding:0 2%}
.shrt-contact .contact-form-email-message{height:150px;padding:10px 2%;width:96%}
.shrt-contact .contact-form-button-submit{line-height:24px;max-width:100%;width:100%;z-index:0;margin:4px 0 0;padding:10px 20px!important;text-align:center;cursor:pointer;background:$(keycolor);border:0;height:auto;-webkit-border-radius:2px;-moz-border-radius:2px;-ms-border-radius:2px;-o-border-radius:2px;border-radius:2px;text-transform:uppercase;-webkit-transition:all .2s ease-out;-moz-transition:all .2s ease-out;-o-transition:all .2s ease-out;-ms-transition:all .2s ease-out;transition:all .2s ease-out;color:$(butext.color)}
.shrt-contact .contact-form-button-submit:hover{background:$(keycolor)}
.shrt-2column,.shrt-3column,.shrt-4column{overflow:hidden}
.shrt-2column > div,.shrt-3column > div,.shrt-4column > div{padding:0;float:$startSide;margin-$endSide:2%}
.shrt-2column > div{width:49%}
.shrt-3column > div{width:32%}
.shrt-4column > div{width:23%}
.shrt-2column > div:last-child,.shrt-3column > div:last-child,.shrt-4column > div:last-child{margin-$endSide:0}
.fa-check-circle:before{content:"\f058"}
.fa-info-circle:before{content:"\f05a"}
.fa-exclamation-triangle:before{content:"\f071"}
.fa-exclamation-circle:before{content:"\f06a"}
.tab-wrapper li{width:33.3%;float:$startSide;list-style:none}
.tab-wrapper a{display:block;line-height:34px;height:34px;text-decoration:none}
.tab-wrapper a:hover,.tab-wrapper a.activeTab{}
.simpleTab .tab-wrapper li{display:inline-block;margin:0;padding:0}
.simpleTab .tab-wrapper li:before{display:none!important}
.tab-wrapper li a{padding:0;display:block}
.tab-wrapper li:before{content:'';display:none}
.simpleTab{margin:10px 0}
.tab-content{padding:15px;background-color:$(outer.background.color)}
.tab-wrapper li a.activeTab{background-color:$(keycolor);color:#fff}
.simpleTab *{transition:all 0s ease;-webkit-transition:all 0s ease;-moz-transition:all 0s ease;-o-transition:all 0s ease}
.simpleTab.side .tab-wrapper{float:$startSide;width:30%;margin:0!important;padding:0!important}
.simpleTab .tab-wrapper{padding:0!important;margin:0!important;overflow:hidden;text-align:center}
.simpleTab.side .tab-content{float:$startSide;width:70%;padding:15px}
.simpleTab.side .tab-wrapper li{width:100%;display:block;text-align:center}
.simpleTab.side{overflow:hidden}
.post-body .simpleTab.side .tab-wrapper,.post .tab-wrapper a{background-color:$(button.color)}
.shrt-tab .tab-wrapper a,.shrt-vtab .tab-wrapper a{background-color:$(button.color);color:$(butext.color)}
.post .tab-wrapper li{width:auto}
.post .tab-wrapper a{padding:0 15px}
.post .tab-content{border:1px solid $(cont.border.color);border-top:3px solid $(keycolor)}
.adinside-it{display:inline-block;line-height:0}
.post-body .ads-post{margin:15px auto;line-height:0}
.shrt-gallery{overflow:hidden;margin-bottom:10px}
.shrtImg{margin:0 auto;display:block}
.shrt-gallery > *{width:33%;float:$startSide;height:140px!important;margin-$endSide:0.5%;margin-bottom:5px;padding:4px;border:1px solid $(cont.border.color)}
.shrt-gallery .shrtImg:nth-child(3),.shrt-gallery .shrtImg:nth-child(6),.shrt-gallery .shrtImg:nth-child(9),.shrt-gallery .shrtImg:nth-child(12),.shrt-gallery .shrtImg:nth-child(15),.shrt-gallery .shrtImg:nth-child(18),.shrt-gallery .shrtImg:nth-child(21){margin-$endSide:0}
.shrt-bgallery{overflow:hidden}
.shrt-bgallery > *{float:left;width:25%;height:120px!important;display:block}
.shrt-bgallery > *:first-child{float:none;width:100%;height:350px!important}
.shrt-gallery a img,.shrt-bgallery a img{width:100%;height:100%;display:block}
.acrd-toggle{font-size:16px;overflow:hidden;background-color:$(keycolor);margin:0 0 5px;color:$(butext.color);padding:8px 10px}
.acrd-toggle > .fa{margin-$endSide:5px}
.acrd-toggle .anchor{float:$endSide}
.acrd-toggle.current{background-color:$(button.color)}
.acrd-toggle.current .fa-plus:before{content:"\f068"}
.acrd-content{padding:15px;margin-bottom:15px;margin-top:-5px;background-color:#F2F2F2;box-shadow:inset 0 -1px 7px rgba(0,0,0,0.2)}
a.shrt-owl-img{display:block;height:350px}
.shrt-carousel-item a.shrt-owl-img{height:150px}
.shrt-carousel-item{padding:5px;border:1px solid $(cont.border.color)}
.shrt-slide{padding:5px;border:1px solid $(cont.border.color)}
.shrt-slide .shrt-summary{position:absolute;bottom:20px;color:$(cont.feattext.color);background-color:$(cont.featback.color);left:20px;right:20px}
.shrt-summary a{color:inherit}
.shrt-summary h3,.shrt-summary p{margin:10px}
.shrt-slide h3{font-size:20px}
.shrt-carousel h3{font-size:15px;margin:0;position:absolute;bottom:10px;left:10px;right:10px;color:$(cont.feattext.color)}
.shrt-slide .owl-dots,.shrt-carousel p,.shrt-carousel .owl-dots{display:none!important}
.inlinestyle{display:inline}
.post-body .inlinestyle iframe{margin-bottom:0}
.shrt-vtab ul.tab-wrapper{width:30%;position:absolute;$startSide:0}
.post .shrt-vtab .tab-content{border-top:1px solid $(cont.border.color);margin-$startSide:30%;border-$startSide:3px solid $(keycolor)}
.shrt-vtab ul.tab-wrapper li{display:block;float:none;text-align:$startSide}
/*=====================================
= M. Responsive Menu
=====================================*/
span.resbutton{position:absolute;z-index:22;width:60px;height:60px;line-height:58px;text-align:center;background-color:$(keycolor);top:-5px;font-size:28px}
span.resbutton:before{content:"\f0c9"}
.responsive-menu{position:fixed;left:-300px;width:310px;top:0;bottom:0;z-index:30}
.show-res-menu{overflow:hidden}
.res-menu-area{background-color:$(header.bottom.color);color:$(butext.color);margin-right:10px;direction:ltr}
.res-menu,.res-menu li,.res-menu ul{margin:0;list-style:none;padding:0}
.res-menu a:hover{text-decoration:none}
.res-menu ul{display:none}
.res-menu-area,.resmenu-innner,.res-menu-inner,ul.res-menu{height:100%}
.show-popup-res .container-outer:before,.show-popup .container-outer:before{content:"";background-color:rgba(0,0,0,0.6);position:absolute;top:0;bottom:0;width:100%;z-index:6}
.res-menu .thumb-outer,.res-menu .rpstmetainfo,.res-menu .psummary,.res-menu a.menu-morepost,.res-menu .rcptags,.res-menu .hline,.res-menu .links-content ul > li:before,.res-menu .links-content .thumb-outer,.res-menu .first-item:first-child .postdate{display:none!important}
.res-menu .mtab .tab-wrapper{width:100%;overflow:hidden}
.res-menu .mtab .tab-wrapper li{float:$startSide}
.res-menu .mtab .tab-wrapper li a{padding:0 10px}
.res-menu .mtab .tab-content{margin-$startSide:0;background-color:transparent}
.res-menu .mega-menu > .sub-menu,.res-menu .links-content .first-item:first-child .first-area,.res-menu .sub-icon,.res-menu .sub-sub-menu{position:static;padding:0}
.res-menu .grip .items,.res-menu .mtab .items,.res-menu .links-content,.res-menu .mbig .fbig-widget-area .items{width:100%;margin-$endSide:0;float:none}
.res-menu .mega-menu .mtab,.res-menu .mbig .fbig-widget-area .items-inner{margin:0}
.res-menu .mtab .tab-wrapper{width:100%;overflow:hidden;top:0}
.res-menu .widget-area .items h3{font-size:14px!important;font-weight:300;max-height:none;margin:0}
.res-menu{overflow-y:scroll;padding:20px 10px}
.res-menu > li > a{color:$(butext.color);display:block;height:40px;line-height:40px;padding:0 10px;background-color:$(keycolor);margin-bottom:2px}
.res-menu .mega-menu{position:relative}
.res-menu .menu-desc{display:inline-block;background-color:rgba(0,0,0,0.5);padding:0 5px}
.res-menu .widget-content,.res-menu .mtab .tab-content{padding:0}
.res-menu .links-content h2{margin:0;line-height:32px;font-size:15px;font-weight:300;margin-bottom:1px;padding-$startSide:12px}
.res-menu .links-content ul li > a{line-height:30px;padding-$startSide:12px;display:block}
.res-menu .links-content ul > li{margin-bottom:1px}
.res-menu .sub-button{top:0;bottom:auto;background-color:rgba(0,0,0,0.5);$endSide:0;width:40px;height:40px;text-align:center;line-height:40px;font-size:20px}
.res-menu .links-content a.morepost{margin-top:7px}
.res-menu .links-content .fbig-widget-area,.res-menu .content-area,.res-menu .first-area,.res-menu .widget-area .items h3 a,.res-menu .links-content ul{display:block}
.res-menu .content-area{padding-$startSide:0}
.res-menu .items-inner,.res-menu .links-content .items-inner,.res-menu .mbig .fbig-widget-area .items-inner{border-bottom:0;margin-bottom:0;padding-bottom:0}
.res-menu .widget-area .items h3 a{display:block;margin-bottom:2px;padding:5px 12px;background-color:rgba(0,0,0,0.4)}
.res-menu .links-content .widget-area .items h3 a{background-color:rgba(0,0,0,0.2)}
.res-menu ul.sub-menu > li > a{background-color:rgba(0,0,0,0.2);display:block;padding:0 12px;height:30px;line-height:30px;margin-bottom:1px}
.res-menu .subsubmenu .sub-button{height:30px;width:40px;line-height:32px}
.res-menu .fa-caret-right:before{content:"\f0d7"}
.res-menu .active .fa-caret-right:before,.res-menu .active .fa-caret-down:before{content:"\f0d8"}
.res-menu .sub-sub-menu a{display:block;height:30px;line-height:30px;padding:0 15px;background-color:rgba(0,0,0,0.5);margin-bottom:1px}
.res-menu .mbig .first-item{position:static;width:100%}
.res-menu .mbig .fbig-widget-area,.res-menu .mbig .first-item{padding:0}
.show-res-menu .resmenu-innner{box-shadow:2px 0 8px rgba(0,0,0,0.5)}
.rtl .res-menu ul,.rtl .res-menu li{direction:rtl;text-align:right}
.res-menu .mcarousel .content-area,.res-menu .mcarousel .items-inner{padding-top:0}
/*=====================================
= N. Other Effect
=====================================*/
.owl-carousel{display:none;width:100%;-webkit-tap-highlight-color:transparent;position:relative;z-index:1}
.owl-carousel .owl-stage{position:relative;-ms-touch-action:pan-Y}
.owl-carousel .owl-stage:after{content:".";display:block;clear:both;visibility:hidden;line-height:0;height:0}
.owl-carousel .owl-stage-outer{position:relative;overflow:hidden;-webkit-transform:translate3d(0px,0px,0px)}
.owl-controls .owl-nav div,.related_posts .owl-nav div,a.jdshrt-tooltip > span{opacity:0}
.owl-nav div,.owl-dot,a.gotop,.contact-button,span.resbutton,.acrd-toggle,.cst-share-btn,.cst-close,.emo-button,.sharesinfo a,.item-share a{cursor:pointer;cursor:hand;-webkit-user-select:none;-khtml-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}
.owl-carousel.owl-loaded{display:block}
.owl-carousel.owl-loading{opacity:0;display:block}
.owl-carousel.owl-hidden{opacity:0}
.owl-carousel .owl-refresh .owl-item{display:none}
.owl-carousel .owl-item{position:relative;min-height:1px;float:left;-webkit-backface-visibility:hidden;-webkit-tap-highlight-color:transparent;-webkit-touch-callout:none;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}
.owl-carousel .owl-item img{display:block;width:100%;-webkit-transform-style:preserve-3d}
.owl-carousel.owl-text-select-on .owl-item{-webkit-user-select:auto;-moz-user-select:auto;-ms-user-select:auto;user-select:auto}
.owl-carousel .owl-grab{cursor:move;cursor:-webkit-grab;cursor:-o-grab;cursor:-ms-grab;cursor:grab}
.owl-carousel.owl-rtl{direction:rtl}
.owl-carousel.owl-rtl .owl-item{float:right}
.no-js .owl-carousel{display:block}
.owl-nav,.owl-controls{position:static}
.owl-nav div{position:absolute;background-color:$(keycolor);height:48px;width:32px;top:50%;margin-top:-24px;font-size:20px;line-height:50px;text-align:center;color:$(butext.color);z-index:2}
.owl-prev{left:0}
.owl-next{right:0}
.owl-prev:before{content:"\f053"}
.owl-next:before{content:"\f054"}
.owl-carousel:hover .owl-controls .owl-nav div,.thumb-area:hover .post-type,.touch .owl-controls .owl-nav div{opacity:1}
.owl-carousel .animated{-webkit-animation-duration:1000ms;animation-duration:1000ms;-webkit-animation-fill-mode:both;animation-fill-mode:both}
.owl-carousel .owl-animated-in{z-index:0}
.owl-carousel .owl-animated-out{z-index:1}
.owl-carousel .fadeOut{-webkit-animation-name:fadeOut;animation-name:fadeOut}
@-webkit-keyframes fadeOut{
  0%{opacity:1}
  100%{opacity:0}
}
@keyframes fadeOut{
  0%{opacity:1}
  100%{opacity:0}
}
@-webkit-keyframes slideOutDown{
  0%{-webkit-transform:translateY(0);transform:translateY(0)}
  100%{opacity:0;-webkit-transform:translateY(2000px);transform:translateY(2000px)}
}
@keyframes slideOutDown{
  0%{-webkit-transform:translateY(0);-ms-transform:translateY(0);transform:translateY(0)}
  100%{opacity:0;-webkit-transform:translateY(2000px);-ms-transform:translateY(2000px);transform:translateY(2000px)}
}
.slideOutDown{-webkit-animation-name:slideOutDown;animation-name:slideOutDown}
@-webkit-keyframes flipInX{
  0%{-webkit-transform:perspective(400px) rotateX(90deg);transform:perspective(400px) rotateX(90deg);opacity:0}
  40%{-webkit-transform:perspective(400px) rotateX(-10deg);transform:perspective(400px) rotateX(-10deg)}
  70%{-webkit-transform:perspective(400px) rotateX(10deg);transform:perspective(400px) rotateX(10deg)}
  100%{-webkit-transform:perspective(400px) rotateX(0deg);transform:perspective(400px) rotateX(0deg);opacity:1}
}
@keyframes flipInX{
  0%{-webkit-transform:perspective(400px) rotateX(90deg);-ms-transform:perspective(400px) rotateX(90deg);transform:perspective(400px) rotateX(90deg);opacity:0}
  40%{-webkit-transform:perspective(400px) rotateX(-10deg);-ms-transform:perspective(400px) rotateX(-10deg);transform:perspective(400px) rotateX(-10deg)}
  70%{-webkit-transform:perspective(400px) rotateX(10deg);-ms-transform:perspective(400px) rotateX(10deg);transform:perspective(400px) rotateX(10deg)}
  100%{-webkit-transform:perspective(400px) rotateX(0deg);-ms-transform:perspective(400px) rotateX(0deg);transform:perspective(400px) rotateX(0deg);opacity:1}
}
.flipInX{-webkit-backface-visibility:visible!important;-ms-backface-visibility:visible!important;backface-visibility:visible!important;-webkit-animation-name:flipInX;animation-name:flipInX}
.mCustomScrollbar{-ms-touch-action:none;touch-action:none}
.mCustomScrollbar.mCS_no_scrollbar{-ms-touch-action:auto;touch-action:auto}
.mCustomScrollBox{position:relative;overflow:hidden;height:100%;max-width:100%;outline:none;direction:ltr}
.mCSB_container{overflow:hidden;width:auto;height:auto;margin-$endSide:10px}
.mCSB_container.mCS_no_scrollbar_y.mCS_y_hidden{margin-right:0}
.mCS-dir-rtl > .mCSB_inside > .mCSB_container{margin-right:0;margin-left:30px}
.mCS-dir-rtl > .mCSB_inside > .mCSB_container.mCS_no_scrollbar_y.mCS_y_hidden{margin-left:0}
.mCSB_outside + .mCSB_scrollTools{$endSide:-10px}
.mCS-dir-rtl > .mCSB_inside > .mCSB_scrollTools,.mCS-dir-rtl > .mCSB_outside + .mCSB_scrollTools{right:auto;left:0}
.mCS-dir-rtl > .mCSB_outside + .mCSB_scrollTools{left:-10px}
.mCSB_scrollTools .mCSB_draggerContainer{position:absolute;top:0;left:0;bottom:0;right:0;height:auto}
.mCSB_scrollTools a + .mCSB_draggerContainer{margin:20px 0}
.mCSB_scrollTools .mCSB_draggerRail{width:2px;height:100%;margin:0 auto;-webkit-border-radius:16px;-moz-border-radius:16px;border-radius:16px;background-color:rgba(0,0,0,0.15)}
.mCSB_scrollTools .mCSB_dragger{cursor:pointer;width:100%;height:30px;z-index:1}
.mCSB_scrollTools .mCSB_dragger .mCSB_dragger_bar{position:relative;width:4px;height:100%;margin:0 auto;-webkit-border-radius:16px;-moz-border-radius:16px;border-radius:16px;text-align:center}
.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_dragger.mCSB_dragger_onDrag_expanded .mCSB_dragger_bar,.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_draggerContainer:hover .mCSB_dragger .mCSB_dragger_bar{width:12px}
.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_dragger.mCSB_dragger_onDrag_expanded + .mCSB_draggerRail,.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_draggerContainer:hover .mCSB_draggerRail{width:8px}
.mCSB_scrollTools .mCSB_buttonUp,.mCSB_scrollTools .mCSB_buttonDown{display:block;position:absolute;height:20px;width:100%;overflow:hidden;margin:0 auto;cursor:pointer}
.mCSB_scrollTools .mCSB_buttonDown{bottom:0}
.mCSB_scrollTools,.mCSB_scrollTools .mCSB_dragger .mCSB_dragger_bar,.mCSB_scrollTools .mCSB_buttonUp,.mCSB_scrollTools .mCSB_buttonDown,.mCSB_scrollTools .mCSB_buttonLeft,.mCSB_scrollTools .mCSB_buttonRight{-webkit-transition:opacity .2s ease-in-out,background-color .2s ease-in-out;-moz-transition:opacity .2s ease-in-out,background-color .2s ease-in-out;-o-transition:opacity .2s ease-in-out,background-color .2s ease-in-out;transition:opacity .2s ease-in-out,background-color .2s ease-in-out}
.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_dragger_bar,.mCSB_scrollTools_vertical.mCSB_scrollTools_onDrag_expand .mCSB_draggerRail,.mCSB_scrollTools_horizontal.mCSB_scrollTools_onDrag_expand .mCSB_dragger_bar,.mCSB_scrollTools_horizontal.mCSB_scrollTools_onDrag_expand .mCSB_draggerRail{-webkit-transition:width .2s ease-out .2s,height .2s ease-out .2s,margin-left .2s ease-out .2s,margin-right .2s ease-out .2s,margin-top .2s ease-out .2s,margin-bottom .2s ease-out .2s,opacity .2s ease-in-out,background-color .2s ease-in-out;-moz-transition:width .2s ease-out .2s,height .2s ease-out .2s,margin-left .2s ease-out .2s,margin-right .2s ease-out .2s,margin-top .2s ease-out .2s,margin-bottom .2s ease-out .2s,opacity .2s ease-in-out,background-color .2s ease-in-out;-o-transition:width .2s ease-out .2s,height .2s ease-out .2s,margin-left .2s ease-out .2s,margin-right .2s ease-out .2s,margin-top .2s ease-out .2s,margin-bottom .2s ease-out .2s,opacity .2s ease-in-out,background-color .2s ease-in-out;transition:width .2s ease-out .2s,height .2s ease-out .2s,margin-left .2s ease-out .2s,margin-right .2s ease-out .2s,margin-top .2s ease-out .2s,margin-bottom .2s ease-out .2s,opacity .2s ease-in-out,background-color .2s ease-in-out}
.mCSB_scrollTools{position:absolute;width:16px;height:auto;$startSide:auto;top:0;$endSide:0;bottom:0}
.mCSB_scrollTools .mCSB_dragger .mCSB_dragger_bar{background-color:$(keycolor);filter:"alpha(opacity=20)";-ms-filter:"alpha(opacity=20)"}
.mCustomScrollbar .mCSB_scrollTools{opacity:0;filter:"alpha(opacity=0)";-ms-filter:"alpha(opacity=0)"}
.mCustomScrollbar:hover > .mCustomScrollBox ~ .mCSB_scrollTools,.mCustomScrollbar:hover > .mCustomScrollBox > .mCSB_scrollTools,.mCustomScrollbar > .mCustomScrollBox ~ .mCSB_scrollTools.mCSB_scrollTools_onDrag,.mCustomScrollbar > .mCustomScrollBox > .mCSB_scrollTools.mCSB_scrollTools_onDrag{opacity:1;filter:"alpha(opacity=100)";-ms-filter:"alpha(opacity=100)"}
.ticker-wrapper.has-js{margin:0;padding:0;width:100%;height:32px;display:block;-webkit-border-radius:3px;-moz-border-radius:3px;border-radius:3px;background-color:$(outer.background.color);border:1px solid $(cont.border.color)}
.ticker{width:100%;height:32px;padding-$endSide:90px;display:block;position:relative;overflow:hidden}
.ticker-title{color:$(butext.color);font-weight:400;background-color:$(keycolor);text-transform:uppercase;line-height:30px;padding:0 10px;letter-spacing:-1px;font-size:12px}
.ticker-content{margin:0;position:absolute;font-weight:bold;overflow:hidden;white-space:nowrap;line-height:32px}
.ticker-content:focus{outline:none}
.ticker-content a{text-decoration:none;color:#1F527B}
.ticker-content a:hover{text-decoration:underline;color:#0D3059}
.ticker-swipe{position:absolute;top:0;background-color:$(outer.background.color);display:block;width:100%;height:24px}
.ticker-swipe span{margin-left:1px;background-color:$(outer.background.color);border-bottom:1px solid #000;height:24px;width:8px;display:block}
.ticker-controls{padding:8px 0 0 0;list-style-type:none;float:left}
.ticker-controls li{padding:0;margin-$startSide:5px;float:$startSide;cursor:pointer;height:16px;width:19px;display:block;background-color:#E8E8E8;border-radius:2px;font-size:9px;line-height:16px;text-align:center}
.ticker-controls li.jnt-play-pause:before{content:"\f04c"}
.ticker-controls li.jnt-play-pause.paused:before{content:"\f04b"}
.ticker-controls li.jnt-prev:before,.rtl .ticker-controls li.jnt-next:before{content:"\f04a"}
.ticker-controls li.jnt-next:before,.rtl .ticker-controls li.jnt-prev:before{content:"\f04e"}
.ticker-controls li.over{opacity:0.75}
.ticker-controls li.down{top:1px}
.js-hidden{display:none}
.no-js-news{padding:10px 0 0 45px;color:#F8F0DB}
.newsticker .ticker-controls{position:absolute;$endSide:0;top:0;background-color:$(outer.background.color);padding:7px}
.ticker-content,.ticker-title,.ticker{float:$startSide}
.gcse-resultplace > div,.gcse-resultplace > div *{-webkit-box-sizing:content-box;-moz-box-sizing:content-box;box-sizing:content-box}
.gsc-table-result,.gs-promotion-table{border-collapse:initial}
.gcse-resultplace{height:0;width:0;overflow:hidden}
.gcse-resultplace .gsc-results-wrapper-overlay{width:auto;left:12%;right:12%;top:55px;bottom:50px}
a.gotop,.contact-button,.cst-share-btn{width:42px;height:42px;line-height:42px;text-align:center;color:$(butext.color);border-radius:3px 3px 0 0;box-shadow:0 2px 5px rgba(0,0,0,0.5)}
a.gotop,.cst-share-btn{position:fixed;bottom:-42px;$endSide:20px;background-color:$(keycolor)}
.contact-btn-area{position:fixed;$endSide:70px;z-index:30}
.show-popup .contact-btn-area,.show-popup .cst-share-btn{z-index:5}
.contact-button{background-color:#FF4D00;bottom:-42px;display:block}
a.gotop.showup,.showup .contact-button,.contact-btn-area,.cst-share-btn.showup{bottom:0}
.fb-page,.fb-page span,.fb-page span iframe[style]{width:100%!important}
.mobile .middle-header .head-wrap,.mobile .middle-header .header,.post-content-mobile,.mobile .comments,.mobile #comment-post-message{display:block}
.mobile .middle-header .header{width:100%}
.mobile .middle-header .header img{width:auto;margin:0 auto}
.mobile h3.post-title{font-size:24px;margin-bottom:10px}
.info-mobile a{color:inherit}
.post-outer-mobile .latest-img{width:250px;float:$startSide;margin-$endSide:10px}
.post-outer-mobile .latest-img > a{z-index:1}
.mobile .view{display:none}
.mobile .index .post,.mobile .archive .post{min-height:0}
.post-mobile{z-index:0}
.info-mobile{font-size:12px}
.sevida-mobile-button a,.mobile-url-button a,.mobile-desktop-url a{background-color:$(keycolor);color:$(butext.color);padding:0 10px;font-size:30px;height:38px;line-height:33px!important;width:38px;border-radius:2px;text-align:center;display:block}
.mobile-url-button a,.mobile-desktop-url a{font-size:15px;width:auto;height:33px}
.item #blog-pager-mobile,.mobile-url-button a,.mobile-desktop-url a{margin-top:15px}
.mobile-newer{float:$startSide}
.mobile-older{float:$endSide}
.item-info-mobile{margin:10px 0 15px;font-size:14px}
.adstitle-breakline{overflow:hidden;margin-bottom:15px;margin-top:15px}
.adstitle-place{float:$startSide}
.excerpt-breakline{margin-$startSide:320px}
.excerpt p{background-color:#2E2E2E;padding:15px;margin-bottom:10px;color:#FFF}
.breakline-place .rpstmetainfo{display:none}
.breakline-place h3{max-height:none;font-weight:300;font-size:14px}
.breakline-place h3 a{color:$(keycolor)}
.breakline-place h3:before{content:"\f005";margin-$endSide:5px;opacity:0.7;font-size:80%}
.breakline-place .content-area{padding-$startSide:0}
#HTML869{display:none}
a.item-tag span{display:inline-block;margin-$startSide:5px;font-size:80%}
.post-subtitle{font-size:80%;opacity:0.8}
.page-place{overflow:hidden}
.page-place a{display:inline-block;padding:0 8px;font-size:14px;margin-top:15px;background-color:#2E2E2E;box-shadow:0 1px 2px rgba(0,0,0,0.3);margin-bottom:5px;margin-$endSide:5px;margin-$startSide:3px;height:28px;line-height:28px;border-radius:2px;color:#FFF;text-decoration:none;cursor:pointer}
.page-place a.active_page,.page-place a:hover{background-color:$(keycolor)}
.page-place .fa{line-height:inherit}
.shrt-review{background-color:rgba(0,0,0,0.07)}
.rev-item{padding:10px 10px}
.rev-value-outer{background-color:#E9E9E9}
.rev-value{height:14px;background-color:$(keycolor);border-radius:2px}
.rev-desc span{float:$endSide;font-weight:600}
.rev-desc-place span{display:block;padding-$endSide:15px}
.rev-desc-place h4{background-color:#007ABE;display:inline-block;color:#FFF;padding:4px 10px;font-size:16px;text-transform:uppercase}
.rev-summary{padding:10px;overflow:hidden}
.rev-item:nth-child(even){background-color:rgba(0,0,0,0.08)}
.rev-summary > div{display:table-cell}
.rev-desc-place{vertical-align:top}
.rev-overall{width:150px;text-align:center;vertical-align:middle}
.rev-cir{position:relative;width:120px;height:120px;margin:0 auto}
.rev-score{position:absolute;font-size:60px;font-weight:400;width:100px;text-align:center;line-height:100px;height:100px;top:50%;margin-top:-50px;margin-left:-50px;left:50%;color:$(keycolor)}
.rev-cir .slice{position:absolute;width:100px;left:50%;margin-left:-50px;bottom:10px;background-color:rgba(0,0,0,0.5)}
.rev-cir .meter{height:5px;background-color:$(keycolor)}
.overall-inner{background-color:rgba(0,0,0,0.1);padding-bottom:10px}
.rev-overall span{font-weight:600}
.review-place{position:absolute;$endSide:5px;top:5px;background-color:$(keycolor);color:#FFF;width:40px;height:40px;text-align:center;line-height:40px;font-size:20px;font-weight:600;border-radius:2px}
.review-place .slice{background-color:#000;width:32px;position:absolute;bottom:3px;$startSide:4px}
.review-place .bar{height:2px;background-color:#FFF}
.fbig-widget-area .review-place,.column1 .review-place{width:24px;height:24px;font-size:12px;line-height:20px}
.fbig-widget-area .review-place .slice,.column1 .slice{width:20px;$startSide:2px}
.rel-simple .thumb-area{padding:3px}
.rel-simple .items,.rel-fbig .items:first-child .thumb-outer,.rel-fbig .items:first-child .content-area,.rel-fbig .items{width:50%;float:$startSide}
.rel-fbig .items:first-child{width:100%;float:none}
.rel-fbig .items:first-child .thumb-outer,.rel-fbig .items:first-child .content-area,.rel-fbig .items:first-child .psummary{display:block}
.rel-fbig .items:first-child .thumb-outer{padding-$endSide:10px}
.rel-fbig .items:first-child a.rcthumb{width:auto;height:180px}
.rel-fbig .items:first-child .psummary{margin:10px 0}
.rel-fbig .items:first-child h3{font-size:20px;margin:10px 0 8px;max-height:none}
.video .review-place,.gallery .review-place{display:none}
.sevida-table{border:2px solid $(keycolor);width:100%;margin:0 0 15px;padding:0}
.sevida-table thead{color:$(butext.color);background-color:$(keycolor)}
.sevida-table tr{border:1px solid $(cont.border.color);padding:5px}
.sevida-table th,.snews-table td{padding:10px;text-align:center}
.sevida-table th{text-transform:uppercase;letter-spacing:1px}
.sevida-table td{padding:8px 10px;font-size:14px}
.sevida-table td:nth-child(even),.snews-table th:nth-child(even){background-color:rgba(0,0,0,0.05)}
.blog-pager-item img{width:73px;height:73px;padding:3px;border:1px solid $(cont.border.color);border-radius:2px;display:none}
/*=====================================
= O. Responsive
=====================================*/
@media screen and (max-width:1149px){
  .search-form input{width:200px}
  .full-style .scrolled .main-nav{margin:0 auto;max-width: 1150px;width:98%}
}
@media screen and (max-width:1100px){
  .feat-wrapitem:first-child{margin-$startSide:350px}
  .feat-wrapitem:last-child{width:350px}
  .search-form input{width:150px}
  .sidebar-left{display:none}
  .main-wrapper{padding-$startSide:0}
  .right-post .main-wrapper{padding-right:0}
  .left-post .main-wrapper{padding-left:0}
}
@media screen and (max-width:1000px){
  .full-style .wrap,.full-style .scrolled .main-nav{width: auto;margin:0 10px}
  .middle-header .header,.middle-header .topads{display:inline-block;width:auto}
  .Header img{margin:0 auto}
  .middle-header .header{min-width:300px}
  .middle-header{text-align:center}
  #midnav,.sc-move,.top-menu-sec,.bottom-menu,.show-res-menu a.gotop,.show-res-menu .contact-btn-area,.show-res-menu .cst-share-btn,.middle-header .topads,.touch .newsmoreinfo.active,.reco-place{display:none}
  span.resbutton,.cst-share-btn,.middle-header .head-wrap{display:block}
  .container{min-width:0}
  .wrap,.scrolled .main-nav{width:auto;margin:0 10px}
  .search-form input{width:220px}
  .cst-share-btn{$startSide:20px;$endSide:auto;z-index:30}
}
@media screen and (max-width:960px){
  .sidebar-left{display:block}
  .main-wrapper,.main-bottom-left,.rtl .main-wrapper,.right-post .main-wrapper,.left-post .main-wrapper,.right-side .main-wrapper,.left-side .main-wrapper{padding-$endSide:0}
  .right-post .main-wrapper,.left-post .main-wrapper,.right-side .main-wrapper,.left-side .main-wrapper{padding-$startSide:0}
  .sidebar-left > .innerwrap,.sidebar-right > .innerwrap{width:auto}
  .sidebar-left,.feat-wrapitem:last-child .items{float:$startSide}
  .sidebar-left,.sidebar-right,.footer{width:50%}
  .list .latest-img{width:280px}
  .sidebar-right{float:$endSide}
  .sidebar-left > .innerwrap,.sidebar-right > .innerwrap,.sidebar-left,.sidebar-right{position:static!important;height:auto!important}
  .feat-wrapitem:last-child{position:static;width:100%;height:auto;overflow:hidden}
  .feat-wrapitem:first-child{margin-$startSide:0;margin-bottom:5px}
  .feat-wrapitem:last-child .items{margin-bottom:0;width:32.666666667%;margin-$endSide:1%}
  .feat-wrapitem:last-child .items-inner,.feat-wrapitem:last-child .items:last-child,.footer{margin-$endSide:0}
  .sidebar-left > .innerwrap,.footer:nth-child(odd){padding-$endSide:10px!important;padding-$startSide:0!important}
  .sidebar-right > .innerwrap,.footer:nth-child(even){padding-$startSide:10px!important;padding-$endSide:0!important}
  .featured1 .items:nth-child(1),.featured3 .items:nth-child(1){float:none}
  .featured3 .content-area{left:10px;right:10px;bottom:10px;padding:10px}
  .featured3 .items h3{font-size:16px}
  .full-post .sidebar-left,.full-post .sidebar-right,.left-side .sidebar-left,.right-side .sidebar-left{display:block}
}
@media screen and (max-width:860px){
  .list .latest-img{width:250px}
  .featured1 .items:nth-child(2),.featured3 .items:nth-child(1),.featured1 .items:nth-child(1){width:100%}
  .featured1 .items:nth-child(3),.featured1 .items:nth-child(4){width:50%}
  .featured3 .items:nth-child(2),.featured3 .items:nth-child(3),.featured3 .items:nth-child(4),.featured3 .items:nth-child(5){width:25%;height:200px}
  .featured3 .items:nth-child(1),.featured4 .owl-item,.featured4 .owl-item .thumb-outer{height:300px}
  .featured3 .items:nth-child(2) .psummary,.featured4 .owl-nav{display:none}
}
@media screen and (max-width:730px){
  .sidebar-left,.sidebar-right,.feat-wrapitem:last-child .items,.footer,.featured2 .items:nth-child(1),.feat-wrapitem:last-child .items,.hot .first-item:first-child,.hot .fbig-widget-area,.fbig1 .first-item:first-child,.fbig1 .fbig-widget-area,.fbig2 .first-item:first-child .thumb-outer,.fbig2 .fbig-widget-area .items,.fbig2 .fbig-widget-area .items:nth-child(even){width:100%;float:none}
  .feat-wrapitem:last-child .items,.video .items{margin-$endSide:0}
  .cst-social-share{left:15px;top:5px;bottom:20px;right:15px}
  .feat-wrapitem:last-child .items{margin-bottom:5px}
  .feat-wrapitem:last-child .items:last-child{margin-bottom:0}
  .hot .first-item:first-child a.rcthumb,.hot .fbig-widget-area a.rcthumb{height:200px}
  .fbig2 .first-item:first-child .first-area h3{margin-top:10px}
  .featured1 .items,.featured3 .items:nth-child(2),.featured3 .items:nth-child(3),.featured3 .items:nth-child(4),.featured3 .items:nth-child(5){height:150px}
  .feat-wrapitem,.feat-wrapitem:first-child .items,.featured1 .items:nth-child(1),.slider .thumb-area a{height:300px}
  .index .post-outer,.archive .post-outer,.video .items,.featured2 .items,.featured3 .items:nth-child(2),.featured3 .items:nth-child(3),.featured3 .items:nth-child(4),.featured3 .items:nth-child(5){width:50%}
  .bottommeta{margin-bottom:15px}
  .video .items:nth-child(odd) .items-inner{padding-$endSide:6px}
  .video .items:nth-child(even) .items-inner{padding-$startSide:6px}
  .sidebar-right > .innerwrap,.sidebar-left > .innerwrap,.gallery1 .first-item:first-child,.gallery1 .first-item:first-child .items-inner,.gallery2 .first-item:first-child,.gallery2 .first-item:first-child .items-inner,.fbig1 .fbig-widget-area,.fbig1 .first-item:first-child,.fbig2 .first-item:first-child .thumb-outer,.fbig2 .first-item:first-child .first-area,.fbig2 .fbig-widget-area .items .items-inner,.footer:nth-child(odd),.footer:nth-child(even){padding-$endSide:0!important;padding-$startSide:0!important}
  .gallery1 .fbig-widget-area,.gallery2 .fbig-widget-area{position:static;width:auto}
  .gallery1 .rcthumb{height:100px}
  .gallery2 .fbig-widget-area .items{width:25%}
  .flickr_badge_image{width:12.5%}
  .timeline .content-area{display:block}
  .fbig2 .fbig-widget-area{max-height:none}
  .featured1 .items:nth-child(2) .psummary,.featured2 .items:hover .psummary,.item-share span{display:none}
  .gallery1 .fbig-widget-area .items-inner,.gallery2 .fbig-widget-area .items-inner{margin-left:3px;margin-right:3px}
  .gallery1 .fbig-widget-area,.gallery2 .fbig-widget-area{margin-left:-3px;margin-right:-3px}
  .shrt-4column > div{width:49%;margin-bottom:15px}
  .shrt-4column > div:nth-child(2){margin-$endSide:0}
  .inlinestyle iframe{max-height:350px}
  .cst-close{top:0;$endSide:0}
  .post-outer-mobile .latest-img{width:200px}
  .item-share .fa{width:auto;position:static}
  .excerpt-breakline{margin-$startSide:0}
  .adstitle-place{float:none;margin-bottom:15px;text-align:center}
  .adstitle-place > *{display:inline-block!important}
  .bigpost a.rcthumb{height:280px}
}
@media screen and (max-width:620px){
  .contact-sec{margin-left:0;margin-top:0;left:10px;right:10px;top:15px;bottom:15px;width:auto}
  .inlinestyle iframe{max-height:300px}
  .list .latest-img{float:none;width:100%;margin-bottom:15px}
  .list .latest-img,.gallery3 .items{margin-$endSide:0}
  .list .latest-img > a{height:200px}
  .list .item-control{top:184px}
  .featured1 .items{height:140px}
  .feat-wrapitem,.feat-wrapitem:first-child .items,a.mslide-img,a.mslide-img img,.featured1 .items:nth-child(1),.featured3 .items:nth-child(1),.featured4 .owl-item,.featured4 .owl-item .thumb-outer{height:280px}
  .fbig2 .items,.fbig2 .first-item:first-child,.first-item:first-child .first-area,.first-item:first-child .first-image,.fbig1 .items,.fbig2 .animated-area,.featured1 .items:nth-child(3),.featured1 .items:nth-child(4),.main-bottom-column > div{width:100%}
  .fbig2 .items,.fbig2 .first-item:first-child,.fbig2 .animated-area,.fbig1 .first-item:first-child .first-image,.first-item:first-child .first-area,.fbig1 .items,.featured1 .items,.more-options,.copyright-area .row > div,.main-bottom-column > div{float:none}
  .main-column-left,.main-column-right{padding:0}
  .mcaption,.slider1 .widget-content .psummary{display:none}
  .mslide-info h3{font-size:18px;background-color:rgba(0,0,0,0.6);max-width:none;width:auto;left:0;right:0;bottom:0}
  .touch .owl-nav div{top:10px;margin-top:0}
  .touch .owl-next{right:10px}
  .touch .owl-prev{left:auto;right:50px}
  .touch .carousel .owl-controls .owl-nav div,.touch .related_posts .owl-nav div{top:50%}
  .touch .carousel .owl-next,.touch .related_posts .owl-next{right:0}
  .touch .carousel .owl-prev,.touch .related_posts .owl-prev{left:0;right:auto}
  a.mslide-img{display:block}
  .gallery2 .fbig-widget-area .items,.gallery3 .items{width:50%}
  .gallery3 .items{padding:0 2px}
  .flickr_badge_image{width:25%}
  .gallery1 .rcthumb{height:75px}
  .video .rcthumb{height:130px}
  .video .items-inner{height:220px}
  .bottommeta{margin-bottom:0}
  .copyright-area{text-align:center}
  .more-options{margin-top:30px}
  .more-options a{margin-$endSide:5px;margin-$startSide:0}
  .post-title.h1{font-size:24px}
  .post-body .glpost > *{height:120px}
  .shrt-gallery > *{height:120px!important}
  .post-outer-mobile .latest-img{width:180px}
  .rel-simple .items,.rel-fbig .items,.rel-fbig .items:first-child .thumb-outer,.rel-fbig .items:first-child .content-area{width:100%;float:none}
  .rel-fbig .items:first-child .thumb-outer{padding-$endSide:0}
  .rel-fbig .items:first-child .content-area{padding-$startSide:0}
  .sevida-table{border:0}
  .sevida-table thead{display:none}
  .sevida-table tr{margin-bottom:10px;display:block;padding:0}
  .sevida-table tr:after{content:"";display:table;clear:both}
  .sevida-table td{box-sizing:border-box;display:block;float:$startSide;clear:$startSide;width:100%;text-align:$endSide;border-bottom:1px solid $(cont.border.color)}
  .sevida-table td:last-child{border-bottom:0}
  .sevida-table td:before{content:attr(data-label);float:$startSide;text-transform:uppercase;font-weight:bold}
  .blogpost .thumb-outer,.blogpost .content-area{display:block}
  .blogpost .content-area{padding-$startSide:0}
  .blogpost a.rcthumb,.bigpost a.rcthumb{width:auto;height:200px}
  .blogpost .thumb-outer{margin-bottom:15px}
  .halfpost a.rcthumb{height:140px}
  .slide-pfeatured,.slide-pfeatured img,.slide-pfeatured iframe,.post-featured iframe{height:280px}
  .hvbreakline > div{display:block}
  .hvbreakline .adspltop,.hvbreakline .adsplbottom{text-align:center}
  .hvbreakline .bottombreakline{padding-$endSide:0;width:auto;margin-bottom:15px}
  .hvbreakline .topbreakline{padding-$startSide:0;margin-top:15px}
}
@media screen and (max-width:460px){
  .gcse-resultplace .gsc-results-wrapper-overlay,.cst-share-inner{left:10px;right:10px}
  .inlinestyle iframe{max-height:280px}
  .list .latest-img > a,.hot .first-item:first-child a.rcthumb,.hot .fbig-widget-area a.rcthumb,.featured2 .items{height:160px}
  .list .item-control{top:144px}
  .index .post-outer,.archive .post-outer,.featured2 .items,.video .items,.featured2 .items:nth-child(2),.featured3 .items:nth-child(2),.featured3 .items:nth-child(3),.featured3 .items:nth-child(4),.featured3 .items:nth-child(5),.shrt-2column > div,.shrt-3column > div,.shrt-4column > div{width:100%;float:none}
  .grid h3.post-title{max-height:none}
  .index .post,.archive .post{min-height:0;margin-bottom:15px}
  .featured1 .items{height:135px}
  .feat-wrapitem,.feat-wrapitem:first-child .items,a.mslide-img,a.mslide-img img,.featured1 .items:nth-child(1),.slider .thumb-area a,.featured4 .owl-item,.featured4 .owl-item .thumb-outer,.shrt-bgallery > *:first-child,a.shrt-owl-img{height:270px}
  .featured .psummary,.slider .widget-content .psummary,.top-date,.newsticker .rpstmetainfo,.ticker-title,.shrt-summary p{display:none!important}
  .slider1 .content-area{padding:10px 5px}
  .top-social-sec,.slider1 .content-area{text-align:center}
  .slider1 .content-area h3{max-width:100%;background-color:transparent;position:static}
  .slider1 .rpstmetainfo > span,.slider1 .rpstmetainfo .fa,.top-social-sec{float:none}
  .newsticker .content-area h3{margin-$startSide:0}
  .ticker-content{$startSide:0!important}
  .video .rcthumb{height:150px}
  .video .items-inner{height:auto}
  .video .items:nth-child(odd) .items-inner{padding-$endSide:0}
  .video .items:nth-child(even) .items-inner{padding-$startSide:0}
  .slider2 .content-area h3,.featured4 .items h3,.post-title.h1{font-size:20px}
  .post .tr-caption-container,.separator > a[style*="float:right"],.separator > a[style*="float:right"],.separator > a[style*="float:left"],.separator > a[style*="float:left"]{float:none!important}
  .post .tr-caption-container{width:100%;margin:0 0 1.2em!important}
  .separator > a[style*="float:right"],.separator > a[style*="float:right"]{margin-left:auto!important}
  .separator > a[style*="float:left"],.separator > a[style*="float:left"]{margin-right:auto!important}
  blockquote{padding-$startSide:30px;margin:1em}
  blockquote:before{font-size:25px}
  .item-share span{left:-5px;right:-5px}
  .authorInner{text-align:center}
  .autorMeta{float:none;margin-$endSide:0;margin-bottom:10px}
  .autorMeta span{width:80px;height:80px;overflow:hidden;margin:0 auto}
  .autorMeta img{width:100%;height:100%}
  .authorTitle > *{display:block}
  .authorSocial{position:static;margin-top:15px}
  .authorSocial a{margin:0 5px}
  .post-body .glpost > *,.shrt-bgallery > *{width:50%}
  .shrt-2column > div,.shrt-3column > div,.shrt-4column > div{margin-$endSide:0}
  .post-outer-mobile .latest-img{width:100px;height:80px;margin-$endSide:8px}
  .post-outer-mobile .latest-img > a{height:100%}
  .post-mobile .postdate{display:none}
  .mobile h3.post-title{font-size:18px;margin-bottom:5px}
  .blogpost a.rcthumb,.bigpost a.rcthumb{height:140px}
  .halfpost .items{float:none;width:auto}
  .slide-pfeatured,.slide-pfeatured img,.slide-pfeatured iframe,.post-featured iframe{height:250px}
  .adspltop > .adsbygoogle,.adsplbottom > .adsbygoogle{width:300px;height:250px}
}
@media screen and (max-width:350px){
  .featured1 .items:nth-child(1) .psummary{display:none}
  a.shrt-owl-img{height:200px}
  .more-options{margin-top:60px}
  .post-body .glpost > *,.shrt-gallery > *,.shrt-bgallery > *{height:80px!important}
  .shrt-bgallery > *:first-child{height:200px!important}
  .featured1 .items{height:125px}
  .feat-wrapitem,.feat-wrapitem:first-child .items,a.mslide-img,a.mslide-img img,.featured1 .items:nth-child(1),.slider .thumb-area a,.featured3 .items:nth-child(1),.featured4 .owl-item,.featured4 .owl-item .thumb-outer{height:250px}
  .search-form input{width:150px}
  .inlinestyle iframe{max-height:250px}
  .first-item:first-child a.rcthumb,.featured2 .items,.halfpost a.rcthumb{height:150px}
  .slide-pfeatured,.slide-pfeatured img,.slide-pfeatured iframe,.post-featured iframe{height:220px}
}
@media print{
  .top-header,.bottom-header,.middle-header .topads,.topfeatured-area,a.gotop,.contact-button,.cst-share-btn,.breadcrumbs,.item-topmeta,.itemtags,.item-share,.item-control,.authorProfile,.blog-pager,.related_posts,#HTML859,.sidebar-area,.footer-area,.Header a:after,.post-title a:after,.tr-caption-container a:after,.separator a:after,.postdate,.bottom-infoitem,.comments-tabs-header .tab-wrapper,#form-wrapper{display:none!important}
  .acrd-content,.middle-header .header{display:block!important}
  .middle-header .header{text-align:center;width:auto}
  .main-wrapper,.post-title.h1{padding:0!important}
  .Header a{color:#303030}
  .post,.post-title.h1,.comments-tabs .tab-content,.comments .comments-content .inline-thread{border:0!important}
}
]]></b:skin>


</head>
<body expr:class='data:blog.pageType' id='webpage' itemscope='' itemtype='http://schema.org/WebPage'>
<div class='body-area' id='body-area'>
<div class='container-outer'>
<div expr:class='(data:blog.url == data:blog.homepageUrl ? &quot;home-area&quot; : data:blog.pageType )+ &quot; container&quot;' id='outer-wrapper'>
<div id='fb-root'/>
<script>
//<![CDATA[
var d = document.getElementById("webpage");d.className = d.className + " loadinghtml";
cookieChoices = {};
//]]>
</script>

<div class='admin row' style='display:none'>
<b:section class='option' id='option' maxwidgets='1' showaddelement='yes'>
  <b:widget id='LinkList850' locked='true' title='Translator' type='LinkList' version='1'>
    <b:includable id='main'>
     <b:loop values='data:links' var='link'>
       <span class='trans' expr:data-trans='data:link.target' expr:title='data:link.name'/>
     </b:loop>
    </b:includable>
  </b:widget>
  <b:widget id='HTML850' locked='true' mobile='yes' title='Full Style' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'/>
    </b:widget-settings>
    <b:includable id='main'>
      <b:if cond='data:content == &quot;y&quot;'>
	    <script type='text/javascript'> 
        //<![CDATA[
		    var afc = document.getElementById("sevidahtml");afc.className = afc.className + " full-style";		 
        //]]>
      </script>
      </b:if>
    </b:includable>
  </b:widget>
  <b:widget id='LinkList851' locked='true' mobile='yes' title='Change Default Setting' type='LinkList' version='1'>
    <b:includable id='main'>
			<b:loop values='data:links' var='link'>
				<span expr:class='&quot;var&quot; + data:link.name' expr:title='data:link.target'/>
			</b:loop>     
    </b:includable>
  </b:widget>
</b:section>
</div>

<div class='header-wrap' id='header-wrapper'>
<div class='top-header'>
<div class='wrap head-wrap'>
<div class='top-date'><span id='dplace'/><span id='tplace'/></div>
<b:section class='top-menu-sec navi' id='top-menu-sec' maxwidgets='1'>
  <b:widget id='LinkList852' locked='true' mobile='yes' title='Top Menu' type='LinkList' version='1'>
    <b:widget-settings>
      <b:widget-setting name='link-5'>http://www.kunapatra.info/p/about.html</b:widget-setting>
      <b:widget-setting name='link-6'>http://kunapatra.byethost5.com/index.php?r=user%2Fauth%2Flogin</b:widget-setting>
      <b:widget-setting name='link-3'>http://</b:widget-setting>
      <b:widget-setting name='link-4'>http://www.kunapatra.info/p/terms-of-service.html</b:widget-setting>
      <b:widget-setting name='text-1'>Sitemap</b:widget-setting>
      <b:widget-setting name='text-0'>Home</b:widget-setting>
      <b:widget-setting name='text-3'>More</b:widget-setting>
      <b:widget-setting name='text-2'>_Sitemap</b:widget-setting>
      <b:widget-setting name='text-5'>_About</b:widget-setting>
      <b:widget-setting name='text-4'>_Terms and Conditions</b:widget-setting>
      <b:widget-setting name='text-6'>Login | Register</b:widget-setting>
      <b:widget-setting name='sorting'>NONE</b:widget-setting>
      <b:widget-setting name='link-1'>http://www.kunapatra.info/sitemap.xml</b:widget-setting>
      <b:widget-setting name='link-2'>http://www.kunapatra.info/p/site-map.html</b:widget-setting>
      <b:widget-setting name='link-0'>http://kunapatra.info</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
			<div class='widget-content'>
        <ul class='menu top-menu' id='topnavi'>
					<b:loop values='data:links' var='link'>
						<li><a expr:href='data:link.target' expr:title='data:link.name'><data:link.name/></a></li>
					</b:loop>
				</ul>
      </div>		
    </b:includable>
  </b:widget>
</b:section>
<b:section class='top-social-sec' id='top-social-sec' maxwidgets='1'>
  <b:widget id='LinkList853' locked='true' mobile='yes' title='Social Link' type='LinkList' version='1'>
    <b:widget-settings>
      <b:widget-setting name='sorting'>NONE</b:widget-setting>
      <b:widget-setting name='text-1'>Twitter</b:widget-setting>
      <b:widget-setting name='link-1'>http://www.twitter.com/kpatra321kuna</b:widget-setting>
      <b:widget-setting name='text-0'>Facebook</b:widget-setting>
      <b:widget-setting name='link-0'>http://www.facebook.com/kpatra321</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
			<div class='widget-content'>
				<ul class='social-icon'>
					<b:loop values='data:links' var='link'>
						<li><a expr:class='&quot;fa icon-&quot; + data:link.name' expr:href='data:link.target' expr:title='data:link.name' rel='nofollow' target='_blank'/></li>
					</b:loop>
				</ul>
			</div>
		</b:includable>
  </b:widget>
</b:section>
<div class='clear'/>
</div>
</div>
<div class='middle-header'>
<div class='wrap head-wrap'>
<header class='header' id='header-area' itemprop='mainEntity' itemscope='' itemtype='http://schema.org/WPHeader'>
	<b:section id='header' maxwidgets='1' showaddelement='no'>
<b:widget id='Header1' locked='true' title='KunaPatra (Header)' type='Header' version='1'>
  <b:widget-settings>
    <b:widget-setting name='displayUrl'/>
    <b:widget-setting name='displayHeight'>0</b:widget-setting>
    <b:widget-setting name='sectionWidth'>150</b:widget-setting>
    <b:widget-setting name='useImage'>false</b:widget-setting>
    <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
    <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
    <b:widget-setting name='displayWidth'>0</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
				<meta expr:content='data:title' itemprop='name'/>
				<meta expr:content='data:blog.homepageUrl' itemprop='url'/>
				<b:if cond='data:useImage'>
					<b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
						<b:if cond='data:mobile'>
							<div id='header-inner'>
								<div class='titlewrapper' style='background: transparent'>
									<b:include name='headtitle'/>
								</div>
								<b:include name='description'/>
							</div>
						<b:else/>
							<div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot; + &quot;background-position: &quot; + data:backgroundPositionStyleStr + &quot;; &quot; + data:widthStyleStr + &quot;min-height: &quot; + data:height + &quot;_height: &quot; + data:height + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
								<div class='titlewrapper' style='background: transparent'>
									<b:include name='headtitle'/>
								</div>
								<b:include name='description'/>
							</div>
						</b:if>
					<b:else/>
						<!--Show the image only-->
						<div id='header-inner'>
							<a expr:href='data:blog.homepageUrl' style='display: block'>
								<img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:title='data:title' expr:width='data:width' style='display: block'/>
							</a>
							<!--Show the description-->
							<b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
								<b:include name='description'/>
							</b:if>
						</div>
						<b:include name='headtitle'/>
					</b:if>
				<b:else/>
					<!--No header image -->
					<div id='header-inner'>
						<div class='titlewrapper'>
							<b:include name='headtitle'/>							
						</div>
						<b:include name='description'/>
					</div>
				</b:if>
			</b:includable>
  <b:includable id='description'>
				<div class='descriptionwrapper'>
					<p class='description'><span itemprop='description'><data:description/></span></p>
				</div>
			</b:includable>
  <b:includable id='headtitle'>
				<b:if cond='data:blog.pageType in {&quot;item&quot;, &quot;static_page&quot;}'>					
					<p expr:class='&quot;title h1 &quot;+(data:useImage and data:imagePlacement != &quot;BEHIND&quot; ? &quot;imageheader&quot; : &quot;&quot;)' itemprop='headline'>
						<b:include name='title'/>
					</p>
				<b:else/>
					<h1 expr:class='&quot;title h1 &quot;+(data:useImage and data:imagePlacement != &quot;BEHIND&quot; ? &quot;imageheader&quot; : &quot;&quot;)' itemprop='headline'>
						<b:include name='title'/>
					</h1>
				</b:if>
			</b:includable>
  <b:includable id='title'>
				<b:if cond='data:blog.url == data:blog.homepageUrl'>					
					<data:title/>
				<b:else/>
					<a expr:href='data:blog.homepageUrl'><data:title/></a>
				</b:if>
			</b:includable>
</b:widget>
</b:section>
</header> 
<b:section class='topads' id='topads' maxwidgets='1' showaddelement='no'>
   <b:widget id='HTML865' locked='true' title='Top Ads' type='HTML' version='1'>
     <b:widget-settings>
       <b:widget-setting name='content'/>
     </b:widget-settings>
     <b:includable id='main'>
			<b:if cond='data:content == &quot;&quot;'>
				<style>.middle-header .head-wrap,.middle-header .header {display: block;width:auto}.middle-header {text-align:center}.header .widget {max-width:none}.header img {margin:0 auto;display:inline-block}.topads {display:none}</style>
      <b:else/>
				<div class='widget-content'><data:content/></div>
			</b:if>
		</b:includable>
   </b:widget>
 </b:section> 
<div class='clear'/>
</div>
</div>
<div class='bottom-header'>
<div class='wrap head-wrap'>
<div class='main-nav'>
	<div class='sc-move'/>
	<span class='resbutton btn'/>
	<nav class='mainnav-area' id='mainnav-area' itemprop='mainEntity' itemscope='' itemtype='http://schema.org/SiteNavigationElement'>
		<b:section class='navi' id='midnav' maxwidgets='1'>
<b:widget id='LinkList854' locked='true' mobile='yes' title='Main Menu' type='LinkList' version='1'>
  <b:widget-settings>
    <b:widget-setting name='text-10'>Other Zone [Hack |Complain | Request | Comment ]</b:widget-setting>
    <b:widget-setting name='sorting'>NONE</b:widget-setting>
    <b:widget-setting name='link-1'>http://www.kunapatra.info/p/blog-page.html</b:widget-setting>
    <b:widget-setting name='link-13'>http://www.kunapatra.info/p/chat.html</b:widget-setting>
    <b:widget-setting name='link-2'>http://www.kunapatra.info/p/blog-page_29.html</b:widget-setting>
    <b:widget-setting name='link-12'>http://kunapatra.byethost5.com</b:widget-setting>
    <b:widget-setting name='link-15'>https://drive.google.com/file/d/0ByMDsaAGidlcLVRRN3ZDR1VBaEU/view?usp=sharing</b:widget-setting>
    <b:widget-setting name='link-0'/>
    <b:widget-setting name='link-14'>http://www.kunapatra.info/p/my-android-app.html</b:widget-setting>
    <b:widget-setting name='link-11'>http://www.kunapatra.info/search/label/Hack</b:widget-setting>
    <b:widget-setting name='link-10'>http://</b:widget-setting>
    <b:widget-setting name='text-9'>_Attitude [Best Attitude collection</b:widget-setting>
    <b:widget-setting name='link-9'>http://www.kunapatra.info/search/label/Attitude</b:widget-setting>
    <b:widget-setting name='text-8'>_Joke [Best Joke Collection]</b:widget-setting>
    <b:widget-setting name='link-7'>http://www.kunapatra.info/search/label/Heart%20Touching</b:widget-setting>
    <b:widget-setting name='link-8'>http://www.kunapatra.info/search/label/Joke</b:widget-setting>
    <b:widget-setting name='link-5'>http://www.kunapatra.info/search/label/SMS</b:widget-setting>
    <b:widget-setting name='link-6'>http://www.kunapatra.info/search/label/Love</b:widget-setting>
    <b:widget-setting name='link-3'>http://www.kunapatra.info/p/gfx-vfx.html</b:widget-setting>
    <b:widget-setting name='link-4'>http://www.kunapatra.info/p/videos.html</b:widget-setting>
    <b:widget-setting name='text-1'>_DJ [DJ Kuna Production]</b:widget-setting>
    <b:widget-setting name='text-0'>Kuna Zone [DJ | VFX | GFX | Photography]</b:widget-setting>
    <b:widget-setting name='text-3'>_GFX [VFX Generation Studio]</b:widget-setting>
    <b:widget-setting name='text-2'>_Photography [VFX Generation Studio]</b:widget-setting>
    <b:widget-setting name='text-5'>SMS [Love, Joke, Sad, Heart touching]</b:widget-setting>
    <b:widget-setting name='text-4'>_VFX [VFX Gen Studio]</b:widget-setting>
    <b:widget-setting name='text-7'>_Heart Touching [Best Heart Touching]</b:widget-setting>
    <b:widget-setting name='text-6'><![CDATA[_Love [Best Love Status & SMS]]]></b:widget-setting>
    <b:widget-setting name='text-15'>_Download Now [Direct Download Link]</b:widget-setting>
    <b:widget-setting name='text-11'>_Hack [Serial Key | Crack | Software]</b:widget-setting>
    <b:widget-setting name='text-12'>_ShoutBox [User Comment | Request Zone ]</b:widget-setting>
    <b:widget-setting name='text-13'>_Complain Box [Complain | Suggest]</b:widget-setting>
    <b:widget-setting name='text-14'>Android App [Download Now my Official App]</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
					<a class='home-icon btn' expr:href='data:blog.homepageUrl' expr:title='data:blog.title'><i class='fa fa-home'/></a>
					<div class='widget-content'>
            <ul class='menu main-menu' id='mainnavi'>
              <b:loop values='data:links' var='link'>
                <li><a expr:href='data:link.target' expr:title='data:link.name' itemprop='url'><span itemprop='name'><data:link.name/></span></a></li>				
              </b:loop>
						</ul>
          </div>
        </b:includable>
</b:widget>
</b:section>
	</nav>
  <div class='menu-search'>
    <form action='/search' class='search-form' id='ajax-search-form'>
	  <input name='q' onblur='if (this.value == &quot;&quot;) {this.value = &quot;Type and hit enter to search...&quot;;}' onfocus='if (this.value == &quot;Type and hit enter to search...&quot;) {this.value = &quot;&quot;;}' type='text' value='Type and hit enter to search...'/>
      <button title='Search' type='submit'><i class='fa fa-search'/></button>
	</form>
  </div>
  <div class='clear'/>
</div>
</div>
<div class='clear'/>
<div class='links-submenu wrap'>
  <b:section class='sidebar links-sub' id='links-sub1' maxwidgets='1' preferred='yes'>
    <b:widget id='HTML7' locked='false' title='Disqus for kunapatra' type='HTML'>
      <b:widget-settings>
        <b:widget-setting name='content'><![CDATA[<!-- Disqus Widget -->]]></b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
<script type='text/javascript'>
var disqus_shortname = &#39;kunapatra&#39;;
var disqus_blogger_current_url = &quot;<data:blog.canonicalUrl/>&quot;;
if (!disqus_blogger_current_url.length) {
disqus_blogger_current_url = &quot;<data:blog.url/>&quot;;
}
var disqus_blogger_homepage_url = &quot;<data:blog.homepageUrl/>&quot;;
var disqus_blogger_canonical_homepage_url = &quot;<data:blog.canonicalHomepageUrl/>&quot;;
</script>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<style type='text/css'>
#comments {display:none;}
</style>
<script type='text/javascript'>
(function() {
    var bloggerjs = document.createElement(&#39;script&#39;);
    bloggerjs.type = &#39;text/javascript&#39;;
    bloggerjs.async = true;
    bloggerjs.src = &#39;//&#39; + disqus_shortname + &#39;.disqus.com/blogger_item.js&#39;;
    (document.getElementsByTagName(&#39;head&#39;)[0] || document.getElementsByTagName(&#39;body&#39;)[0]).appendChild(bloggerjs);
})();
</script>
</b:if>
<style type='text/css'>
.post-comment-link { visibility: hidden; }
</style>
<script type='text/javascript'>
(function() {
var bloggerjs = document.createElement(&#39;script&#39;);
bloggerjs.type = &#39;text/javascript&#39;;
bloggerjs.async = true;
bloggerjs.src = &#39;//&#39; + disqus_shortname + &#39;.disqus.com/blogger_index.js&#39;;
(document.getElementsByTagName(&#39;head&#39;)[0] || document.getElementsByTagName(&#39;body&#39;)[0]).appendChild(bloggerjs);
})();
</script>
</b:includable>
    </b:widget>
    <b:widget id='Label850' locked='false' title='Labels' type='Label' version='1'>
      <b:widget-settings>
        <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
        <b:widget-setting name='display'>LIST</b:widget-setting>
        <b:widget-setting name='selectedLabelsList'/>
        <b:widget-setting name='showType'>ALL</b:widget-setting>
        <b:widget-setting name='showFreqNumbers'>true</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
				<b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
				<div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
					<b:if cond='data:display == &quot;list&quot;'>
						<ul>
							<b:loop values='data:labels' var='label'>
								<li>
									<b:if cond='data:blog.url == data:label.url'>
										<span expr:dir='data:blog.languageDirection'><data:label.name/></span>
									<b:else/>
										<a expr:dir='data:blog.languageDirection' expr:href='data:label.url' expr:title='data:label.name'><data:label.name/></a>
									</b:if>
									<b:if cond='data:showFreqNumbers'>
										<span dir='ltr'>(<data:label.count/>)</span>
									</b:if>
								</li>
							</b:loop>
						</ul>
					<b:else/>
						<b:loop values='data:labels' var='label'>
							<span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
								<b:if cond='data:blog.url == data:label.url'>
									<span expr:dir='data:blog.languageDirection'><data:label.name/></span>
								<b:else/>
									<a expr:dir='data:blog.languageDirection' expr:href='data:label.url' expr:title='data:label.name'><data:label.name/></a>
								</b:if>
								<b:if cond='data:showFreqNumbers'>
									<span class='label-count' dir='ltr'>(<data:label.count/>)</span>
								</b:if>
							</span>
						</b:loop>
					</b:if>
				</div>
			</b:includable>
    </b:widget>
    <b:widget id='Label17' locked='false' title='Labels' type='Label' version='1'>
      <b:widget-settings>
        <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
        <b:widget-setting name='display'>LIST</b:widget-setting>
        <b:widget-setting name='selectedLabelsList'/>
        <b:widget-setting name='showType'>ALL</b:widget-setting>
        <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
                  <b:if cond='data:title'>
                    <h2>
                      <data:title/>
                    </h2>
                  </b:if>
                  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
                    <b:if cond='data:display == &quot;list&quot;'>
                      <ul>
                        <b:loop values='data:labels' var='label'>
                          <li>
                            <b:if cond='data:blog.url == data:label.url'>
                              <span expr:dir='data:blog.languageDirection'>
                                <data:label.name/>
                              </span>
                              <b:else/>
                              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'>
                                <data:label.name/>
                              </a>
                            </b:if>
                            <b:if cond='data:showFreqNumbers'>
                              <span dir='ltr'>
                                (
                                <data:label.count/>
                                )
                              </span>
                            </b:if>
                          </li>
                        </b:loop>
                      </ul>
                      <b:else/>
                      <b:loop values='data:labels' var='label'>
                        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
                          <b:if cond='data:blog.url == data:label.url'>
                            <span expr:dir='data:blog.languageDirection'>
                              <data:label.name/>
                            </span>
                            <b:else/>
                            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'>
                              <data:label.name/>
                            </a>
                          </b:if>
                          <b:if cond='data:showFreqNumbers'>
                            <span class='label-count' dir='ltr'>
                              (
                              <data:label.count/>
                              )
                            </span>
                          </b:if>
                        </span>
                      </b:loop>
                    </b:if>
                    <b:include name='quickedit'/>
                  </div>
                </b:includable>
    </b:widget>
    <b:widget id='BlogArchive1' locked='false' title='Archive' type='BlogArchive' version='1'>
      <b:widget-settings>
        <b:widget-setting name='showStyle'>HIERARCHY</b:widget-setting>
        <b:widget-setting name='yearPattern'>yyyy</b:widget-setting>
        <b:widget-setting name='showWeekEnd'>true</b:widget-setting>
        <b:widget-setting name='monthPattern'>MMMM</b:widget-setting>
        <b:widget-setting name='dayPattern'>MMM dd</b:widget-setting>
        <b:widget-setting name='weekPattern'>MM/dd</b:widget-setting>
        <b:widget-setting name='chronological'>false</b:widget-setting>
        <b:widget-setting name='showPosts'>true</b:widget-setting>
        <b:widget-setting name='frequency'>MONTHLY</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <b:if cond='data:title'>
    <h2><data:title/></h2>
  </b:if>
  <div class='widget-content'>
  <div id='ArchiveList'>
  <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
    <b:if cond='data:style == &quot;HIERARCHY&quot;'>
     <b:include data='data' name='interval'/>
    </b:if>
    <b:if cond='data:style == &quot;FLAT&quot;'>
      <b:include data='data' name='flat'/>
    </b:if>
    <b:if cond='data:style == &quot;MENU&quot;'>
      <b:include data='data' name='menu'/>
    </b:if>
  </div>
  </div>
  <b:include name='quickedit'/>
  </div>
</b:includable>
      <b:includable id='flat' var='data'>
  <ul class='flat'>
    <b:loop values='data:data' var='i'>
      <li class='archivedate'>
        <a expr:href='data:i.url'><data:i.name/></a> (<data:i.post-count/>)
      </li>
    </b:loop>
  </ul>
</b:includable>
      <b:includable id='interval' var='intervalData'>
  <b:loop values='data:intervalData' var='i'>
      <ul class='hierarchy'>
        <li expr:class='&quot;archivedate &quot; + data:i.expclass'>
          <b:include data='i' name='toggle'/>
          <a class='post-count-link' expr:href='data:i.url'><data:i.name/></a>
            <span class='post-count' dir='ltr'>(<data:i.post-count/>)</span>
          <b:if cond='data:i.data'>
            <b:include data='i.data' name='interval'/>
          </b:if>
          <b:if cond='data:i.posts'>
            <b:include data='i.posts' name='posts'/>
          </b:if>
        </li>
      </ul>
  </b:loop>
</b:includable>
      <b:includable id='menu' var='data'>
  <select expr:id='data:widget.instanceId + &quot;_ArchiveMenu&quot;'>
    <option value=''><data:title/></option>
    <b:loop values='data:data' var='i'>
      <option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option>
    </b:loop>
  </select>
</b:includable>
      <b:includable id='posts' var='posts'>
  <ul class='posts'>
    <b:loop values='data:posts' var='i'>
      <li><a expr:href='data:i.url'><data:i.title/></a></li>
    </b:loop>
  </ul>
</b:includable>
      <b:includable id='toggle' var='interval'>
  <b:if cond='data:interval.toggleId'>
  <b:if cond='data:interval.expclass == &quot;expanded&quot;'>
    <a class='toggle' href='javascript:void(0)'>
      <span class='zippy toggle-open'>&#9660;&#160;</span>
    </a>
  <b:else/>
    <a class='toggle' href='javascript:void(0)'>
      <span class='zippy'>
        <b:if cond='data:blog.languageDirection == &quot;rtl&quot;'>
          &#9668;&#160;
        <b:else/>
          &#9658;&#160;
        </b:if>
      </span>
    </a>
  </b:if>
 </b:if>
</b:includable>
    </b:widget>
    <b:widget id='HTML14' locked='false' title='Flickr' type='HTML'>
      <b:widget-settings>
        <b:widget-setting name='content'/>
      </b:widget-settings>
      <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
    </b:widget>
    <b:widget id='HTML15' locked='false' title='Headline' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'/>
      </b:widget-settings>
      <b:includable id='main'>
<b:if cond='data:blog.pageType == &quot;index&quot;'>

<h2><data:title/></h2>
<div class='widget-content'>
<script type='text/javaScript'>
  document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?max-results=&quot;+Label1_numposts+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=featuredposts\&quot;&gt;&lt;\/script&gt;&quot;);
</script>	  
    </div>

      </b:if>

</b:includable>
    </b:widget>
    <b:widget id='HTML18' locked='false' title='Sponsor' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'/>
      </b:widget-settings>
      <b:includable id='main'>
                  <!-- only display title if it's non-empty -->
                  <b:if cond='data:title != &quot;&quot;'>
                    <h2 class='title'>
                      <data:title/>
                    </h2>
                  </b:if>
                  <div class='widget-content'>
                    <data:content/>
                  </div>
                  <b:include name='quickedit'/>
                </b:includable>
    </b:widget>
    <b:widget id='Feed1' locked='false' title='Blogger Templates' type='Feed'>
      <b:includable id='main'>
    <h2><data:title/></h2>
    <div class='widget-content' expr:id='data:widget.instanceId + &quot;_feedItemListDisplay&quot;'>
      <span style='filter: alpha(25); opacity: 0.25;'>
        <a expr:href='data:feedUrl'><data:loadingMsg/></a>
      </span>
    </div>
    <b:include name='quickedit'/>
  </b:includable>
    </b:widget>
    <b:widget id='HTML44' locked='false' title='Business' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'/>
      </b:widget-settings>
      <b:includable id='main'>
  <!-- only display title if it's non-empty -->

  <div class='widget-content'>
  <div class='lof-main-wapper' id='slider'>
<div class='slider-main-outer'>
<ul class='slider-main-wapper'>
<script>                   
document.write(&quot;&lt;script src=\&quot;/feeds/posts/default?max-results=&quot;+numposts11+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=recentposts\&quot;&gt;&lt;\/script&gt;&quot;);
</script>
</ul>
</div>
<div class='slider-navigator-outer'>
<ul class='slider-navigator'>
<script>                   
document.write(&quot;&lt;script src=\&quot;/feeds/posts/default?max-results=&quot;+numposts11+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=recentposts0\&quot;&gt;&lt;\/script&gt;&quot;);
</script>
</ul>
</div>
</div>
  </div>

  <b:include name='quickedit'/>
</b:includable>
    </b:widget>
    <b:widget id='Navbar1' locked='false' title='Navbar' type='Navbar' version='1'>
      <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/plusone.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
      gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
        if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
          gapi.iframes.getContext().openChild({
              url: &#39;https://www.blogger.com/navbar.g?targetBlogID\x3d4309328727641908333\x26blogName\x3dKunaPatra\x26publishMode\x3dPUBLISH_MODE_HOSTED\x26navbarType\x3dDISABLED\x26layoutType\x3dLAYOUTS\x26searchRoot\x3dhttp://www.kunapatra.info/search\x26blogLocale\x3den_GB\x26v\x3d2\x26homepageUrl\x3dhttp://www.kunapatra.info/\x26vt\x3d7987674320113877342&#39;,
              where: document.getElementById(&quot;navbar-iframe-container&quot;),
              id: &quot;navbar-iframe&quot;
          });
        }
      });
    &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
    </b:widget>
    <b:widget id='Label1' locked='false' title='Tags' type='Label' version='1'>
      <b:widget-settings>
        <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
        <b:widget-setting name='display'>LIST</b:widget-setting>
        <b:widget-setting name='selectedLabelsList'/>
        <b:widget-setting name='showType'>ALL</b:widget-setting>
        <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <b:if cond='data:title'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
      <b:loop values='data:labels' var='label'>
        <li>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </li>
      </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
    </b:widget>
    <b:widget id='HTML33' locked='false' title='Breaking News' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'/>
      </b:widget-settings>
      <b:includable id='main'>
                    <!-- only display title if it's non-empty -->
                    <b:if cond='data:title != &quot;&quot;'>
                      <script>
                        document.write(&#39;&lt;div class=&quot;recent-post-title&quot;&gt;&lt;h2&gt;&lt;a href=&quot;/search/label/<data:content/>?max-results=10&quot;&gt;<data:title/>&lt;/a&gt;&lt;/h2&gt;&lt;/div&gt;&#39;); 
                      </script>
                    </b:if>
                    <div class='clear'/>
                    <div class='widget-content'>
                      <div id='previous_button'>
                        <i class='fa fa-angle-left'/>
                      </div>
                      <div id='next_button'>
                        <i class='fa fa-angle-right'/>
                      </div>
                      <div class='content'>
                        <ul>
                          <script>
                            document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?max-results=&quot;+numposts5+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=recentarticles1\&quot;&gt;&lt;\/script&gt;&quot;);
                          </script>
                        </ul>
                        <div class='clear'/>
                      </div>
                      <div class='clear'/>
                    </div>
                    <script type='text/javascript'>
                      (function($) { $(document).ready(function(){
                        $(&quot;#carousel .content&quot;).jCarouselLite({
                          auto:0,
                          scroll: 1,
                          speed: 400,	
                          visible: 3,
                          start: 0,
                          circular: true,
                          btnPrev: &quot;#previous_button&quot;,
                          btnNext: &quot;#next_button&quot;
                          });
                      })})(jQuery)	
                    </script>
                    <b:include name='quickedit'/>
                  </b:includable>
    </b:widget>
    <b:widget id='Label2' locked='false' title='Labels' type='Label' version='1'>
      <b:widget-settings>
        <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
        <b:widget-setting name='display'>LIST</b:widget-setting>
        <b:widget-setting name='selectedLabelsList'/>
        <b:widget-setting name='showType'>ALL</b:widget-setting>
        <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
              <b:if cond='data:title'>
                <h2>
                  <data:title/>
                </h2>
              </b:if>
              <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
                <b:if cond='data:display == &quot;list&quot;'>
                  <ul>
                    <b:loop values='data:labels' var='label'>
                      <li>
                        <b:if cond='data:blog.url == data:label.url'>
                          <span expr:dir='data:blog.languageDirection'>
                            <data:label.name/>
                          </span>
                          <b:else/>
                          <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'>
                            <data:label.name/>
                          </a>
                        </b:if>
                        <b:if cond='data:showFreqNumbers'>
                          <span dir='ltr'>
                            (
                            <data:label.count/>
                            )
                          </span>
                        </b:if>
                      </li>
                    </b:loop>
                  </ul>
                  <b:else/>
                  <b:loop values='data:labels' var='label'>
                    <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
                      <b:if cond='data:blog.url == data:label.url'>
                        <span expr:dir='data:blog.languageDirection'>
                          <data:label.name/>
                        </span>
                        <b:else/>
                        <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'>
                          <data:label.name/>
                        </a>
                      </b:if>
                      <b:if cond='data:showFreqNumbers'>
                        <span class='label-count' dir='ltr'>
                          (
                          <data:label.count/>
                          )
                        </span>
                      </b:if>
                    </span>
                  </b:loop>
                </b:if>
                <b:include name='quickedit'/>
              </div>
            </b:includable>
    </b:widget>
    <b:widget id='PopularPosts1' locked='false' title='Popular Posts' type='PopularPosts' version='1'>
      <b:widget-settings>
        <b:widget-setting name='numItemsToShow'>10</b:widget-setting>
        <b:widget-setting name='showThumbnails'>true</b:widget-setting>
        <b:widget-setting name='showSnippets'>true</b:widget-setting>
        <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <b:if cond='data:title'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='data:showThumbnails == &quot;false&quot;'>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (3) Show only thumbnails -->
            <div class='item-thumbnail-only'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            </div>
            <div style='clear: both;'/>
          <b:else/>
            <!-- (4) Show snippets and thumbnails -->
            <div class='item-content'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
              <div class='item-snippet'><data:post.snippet/></div>
            </div>
            <div style='clear: both;'/>
          </b:if>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
    </b:widget>
    <b:widget id='PopularPosts2' locked='false' title='Popular Posts' type='PopularPosts' version='1'>
      <b:widget-settings>
        <b:widget-setting name='numItemsToShow'>10</b:widget-setting>
        <b:widget-setting name='showThumbnails'>true</b:widget-setting>
        <b:widget-setting name='showSnippets'>true</b:widget-setting>
        <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <b:if cond='data:title'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='data:showThumbnails == &quot;false&quot;'>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (3) Show only thumbnails -->
            <div class='item-thumbnail-only'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            </div>
            <div style='clear: both;'/>
          <b:else/>
            <!-- (4) Show snippets and thumbnails -->
            <div class='item-content'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
              <div class='item-snippet'><data:post.snippet/></div>
            </div>
            <div style='clear: both;'/>
          </b:if>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
    </b:widget>
    <b:widget id='PopularPosts3' locked='false' title='Popular Posts' type='PopularPosts' version='1'>
      <b:widget-settings>
        <b:widget-setting name='numItemsToShow'>10</b:widget-setting>
        <b:widget-setting name='showThumbnails'>true</b:widget-setting>
        <b:widget-setting name='showSnippets'>true</b:widget-setting>
        <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <b:if cond='data:title'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='data:showThumbnails == &quot;false&quot;'>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (3) Show only thumbnails -->
            <div class='item-thumbnail-only'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            </div>
            <div style='clear: both;'/>
          <b:else/>
            <!-- (4) Show snippets and thumbnails -->
            <div class='item-content'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
              <div class='item-snippet'><data:post.snippet/></div>
            </div>
            <div style='clear: both;'/>
          </b:if>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
    </b:widget>
  </b:section>
  <b:section class='sidebar links-sub' id='links-sub2' maxwidgets='1' preferred='yes'>
    <b:widget id='LinkList855' locked='false' title='Layout' type='LinkList' version='1'>
      <b:widget-settings>
        <b:widget-setting name='sorting'>NONE</b:widget-setting>
        <b:widget-setting name='text-0'>-links</b:widget-setting>
        <b:widget-setting name='link-0'>http://</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
				<b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
				<div class='widget-content'>
					<ul>
						<b:loop values='data:links' var='link'>
							<li><a expr:href='data:link.target' expr:title='data:link.name'><data:link.name/></a></li>
						</b:loop>
					</ul>
				</div>
			</b:includable>
    </b:widget>
  </b:section>
  <b:section class='sidebar links-sub' id='links-sub3' maxwidgets='1' preferred='yes'>
    <b:widget id='LinkList856' locked='false' title='Post Style' type='LinkList' version='1'>
      <b:widget-settings>
        <b:widget-setting name='sorting'>NONE</b:widget-setting>
        <b:widget-setting name='text-0'>-mbig/random</b:widget-setting>
        <b:widget-setting name='link-0'>http://</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
				<b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
				<div class='widget-content'>
					<ul>
						<b:loop values='data:links' var='link'>
							<li><a expr:href='data:link.target' expr:title='data:link.name'><data:link.name/></a></li>
						</b:loop>
					</ul>
				</div>
			</b:includable>
    </b:widget>
  </b:section>
  <b:section class='sidebar links-sub' id='links-sub4' maxwidgets='1' preferred='yes'>
    <b:widget id='HTML866' locked='false' title='Technology' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'>Love</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
				<b:if cond='data:title != &quot;&quot;'><h2 class='title'><data:title/></h2></b:if>
				<div class='widget-content'>
					<data:content/>
				</div>
			</b:includable>
    </b:widget>
  </b:section>  
<div class='clear'/>
</div>
</div>
</div>

<div class='topfeatured-area'>
<div class='wrap'>
<div class='ticker-area'>
<b:section class='sidebar' id='newsticker' maxwidgets='1' preferred='yes'>
  <b:widget id='HTML867' locked='true' title='Breaking News' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>[recent][newsticker]</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
			<b:if cond='data:content == &quot;n&quot; or data:content == &quot;&quot;'><b:else/>
				<b:if cond='data:title != &quot;&quot;'><h2 class='title'><data:title/></h2></b:if>
				<div class='widget-content'>
					<data:content/>
				</div>
			</b:if>
		</b:includable>
  </b:widget>
</b:section>
</div>
<b:if cond='data:blog.url == data:blog.homepageUrl'>
<b:section class='sidebar homepost' id='top-featured' maxwidgets='1' preferred='yes'>
  <b:widget id='HTML868' locked='true' title='Top Featured' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>[SMS][featured1]</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>	  
			<b:if cond='data:content == &quot;n&quot; or data:content == &quot;&quot;'><b:else/>
				<b:if cond='data:title != &quot;&quot;'><h2 class='title'><data:title/></h2></b:if>
					<div class='widget-content'>
						<data:content/>
					</div>
			</b:if>	  
		</b:includable>
  </b:widget>
</b:section>
</b:if>
</div>
</div>
    
<div class='content-wrapper content-wrapper-top' id='content-wrapper'>
<div class='wrap'>
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
  <div class='error-custom'>    
    <span>404 Page Not Found</span>
    <p class='error-body'>We&#39;re sorry but we could not find the page you are looking for.<br/>
	  This may happen if you have entered site url incorrectly or this page doesn&#39;t exist anymore.</p>
	  <p>You can try searching page again or go back to <a class='error_button' expr:href='data:blog.homepageUrl'><i class='fa fa-home'/> home</a></p>
    <div class='errorsrc'>
      <form action='/search' id='searchform' method='get'>
				<input id='s' name='q' onblur='if (this.value == &quot;&quot;) {this.value = &quot;Type and hit enter to search...&quot;;}' onfocus='if (this.value == &quot;Type and hit enter to search...&quot;) {this.value = &quot;&quot;;}' type='text' value='Type and hit enter to search...'/>
      </form>
    </div>      
  </div>
</b:if>
<div class='main-wrapper' id='main-wrapper'>
<div class='innerwrap'>
	<b:if cond='data:blog.url == data:blog.homepageUrl'>
		<b:section class='sidebar homepost main-homepost' id='main-top' preferred='yes'/>
	</b:if>
	<b:if cond='data:blog.pageType in {&quot;archive&quot;, &quot;index&quot;}'>
		<div class='posts-title'>
			<div class='title-wrap'>
				<h2 class='plabelsbtn'>
					<b:if cond='data:blog.url == data:blog.homepageUrl or data:blog.title == data:blog.pageTitle'>Latest Post
					<b:elseif cond='data:blog.pageType == &quot;archive&quot;'/><data:blog.pageName/>
					<b:elseif cond='data:blog.searchQuery'/>Search Result For &quot;<data:blog.searchQuery/>&quot;
					<b:elseif cond='data:blog.searchLabel'/>Articles by &quot;<data:blog.searchLabel/>&quot;</b:if>
				</h2>	
				<div class='plabels' id='plabels'/>
			</div>
		<nav class='view' id='view'>
      <span class='list' title='list mode'><i class='fa fa-th-list'/></span>
      <span class='grid' title='grid mode'><i class='fa fa-th'/></span>
		</nav>
		<span class='hline'/>
	</div>
	</b:if>

	<b:section class='ads-widget-sec blogpost-setting' id='ads-widget-sec1' showaddelement='no'>
<b:widget id='HTML875' locked='true' title='Ads Below Title' type='HTML' version='1'>
  <b:widget-settings>
    <b:widget-setting name='content'/>
  </b:widget-settings>
  <b:includable id='main'>
        <b:if cond='data:blog.pageType in {&quot;static_page&quot;, &quot;item&quot;}'>
					<b:if cond='data:content == &quot;n&quot; or data:content == &quot;&quot;'><b:else/>
						<div class='adsbelow'>
							<data:content/>
						</div>
					</b:if>
				</b:if>
      </b:includable>
</b:widget>
<b:widget id='HTML869' locked='true' title='Ads Inside Post' type='HTML' version='1'>
  <b:widget-settings>
    <b:widget-setting name='content'/>
  </b:widget-settings>
  <b:includable id='main'>
        <b:if cond='data:blog.pageType in {&quot;static_page&quot;, &quot;item&quot;}'>
					<b:if cond='data:content == &quot;n&quot; or data:content == &quot;&quot;'><b:else/>
						<div class='adsinside'>
							<data:content/>
						</div>
					</b:if>
				</b:if>
      </b:includable>
</b:widget>
<b:widget id='HTML876' locked='true' title='Ads End Post' type='HTML' version='1'>
  <b:widget-settings>
    <b:widget-setting name='content'/>
  </b:widget-settings>
  <b:includable id='main'>
        <b:if cond='data:blog.pageType in {&quot;static_page&quot;, &quot;item&quot;}'>
					<b:if cond='data:content == &quot;n&quot; or data:content == &quot;&quot;'><b:else/>
						<div class='adsendpost'>
							<data:content/>
						</div>
					</b:if>
				</b:if>
      </b:includable>
</b:widget>
</b:section>

  <b:section class='main-area' id='main' showaddelement='no'>
    <b:widget id='Label851' locked='true' title='Post Labels' type='Label' version='1'>
      <b:widget-settings>
        <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
        <b:widget-setting name='display'>LIST</b:widget-setting>
        <b:widget-setting name='selectedLabelsList'/>
        <b:widget-setting name='showType'>ALL</b:widget-setting>
        <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
				<div expr:class='&quot;widget-content labelhide &quot; + data:display + &quot;-label-widget-content&quot;'>
					<div class='labels-wrap'>
						<b:loop values='data:labels' var='label'>
							<b:if cond='data:blog.url == data:label.url'>
								<span class='label-name selected'>
									<b:if cond='data:showFreqNumbers'>
										<span class='label-count'><data:label.count/></span>
									</b:if>
									<data:label.name/>
								</span>
							<b:else/>
								<a class='label-name' expr:href='data:label.url' expr:title='data:label.name'>
									<b:if cond='data:showFreqNumbers'>
										<span class='label-count'><data:label.count/></span>
									</b:if>
									<data:label.name/>
								</a>
							</b:if>
						</b:loop>
					</div>      
				</div>
			</b:includable>
    </b:widget>
    <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='1'>
      <b:widget-settings>
        <b:widget-setting name='showDateHeader'>true</b:widget-setting>
        <b:widget-setting name='style.textcolor'>#4e2800</b:widget-setting>
        <b:widget-setting name='showShareButtons'>true</b:widget-setting>
        <b:widget-setting name='showCommentLink'>true</b:widget-setting>
        <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
        <b:widget-setting name='showAuthor'>true</b:widget-setting>
        <b:widget-setting name='style.linkcolor'>#f48d1d</b:widget-setting>
        <b:widget-setting name='style.unittype'>TextOnly</b:widget-setting>
        <b:widget-setting name='style.bgcolor'>#f7873d</b:widget-setting>
        <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
        <b:widget-setting name='style.layout'>300x250</b:widget-setting>
        <b:widget-setting name='showLabels'>true</b:widget-setting>
        <b:widget-setting name='showLocation'>false</b:widget-setting>
        <b:widget-setting name='showTimestamp'>true</b:widget-setting>
        <b:widget-setting name='postsPerAd'>1</b:widget-setting>
        <b:widget-setting name='showBacklinks'>false</b:widget-setting>
        <b:widget-setting name='style.bordercolor'>#f7873d</b:widget-setting>
        <b:widget-setting name='showInlineAds'>false</b:widget-setting>
        <b:widget-setting name='showReactions'>false</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main' var='top'>
				<b:if cond='data:mobile == &quot;false&quot;'>
					<!-- posts -->
					<div class='blog-posts hfeed'>
						<b:if cond='data:blog.pageType in {&quot;archive&quot;, &quot;index&quot;}'>
							<div itemscope='itemscope' itemtype='http://schema.org/Blog' style='display: none;'>
								<meta expr:content='data:blog.title' itemprop='name'/>
								<b:if cond='data:blog.metaDescription'>
									<meta expr:content='data:blog.metaDescription' itemprop='description'/>
								</b:if>
							</div>
						</b:if>	 
						<b:include cond='data:blog.pageType != &quot;error_page&quot;' data='top' name='status-message'/>     
						<data:defaultAdStart/>
						<b:loop values='data:posts' var='post'>
							<div class='post-outer'>
								<b:include data='post' name='post'/>      
								<b:include cond='data:blog.pageType in {&quot;static_page&quot;, &quot;item&quot;}' data='post' name='fn_comment_picker'/>             
							</div>        
						</b:loop>      
						<data:adEnd/>
					</div>
					<div class='clear'/>
					<!-- navigation -->
					<b:include cond='data:blog.pageType in {&quot;archive&quot;, &quot;index&quot;}' name='nextprev'/>
					<!-- feed links -->
					<b:include name='feedLinks'/>
					<b:if cond='data:top.showStars'>
						<script src='//www.google.com/jsapi' type='text/javascript'/>
						<script type='text/javascript'>
							google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
							function initialize() {
								google.annotations.setApplicationId(<data:top.blogspotReviews/>);
								google.annotations.createAll();
								google.annotations.fetch();
							}
							google.setOnLoadCallback(initialize);
						</script>
					</b:if>
				<b:else/>
					<b:include name='mobile-main'/>
				</b:if>
				<b:if cond='data:top.showDummy'>
					<data:top.dummyBootstrap/>
				</b:if>
			</b:includable>
      <b:includable id='CustomshareButtons' var='post'>
				<a class='icons-twitter dhref' expr:data-text='data:post.title' expr:data-url='data:post.url' expr:href='&quot;http://twitter.com/share?text=&quot; + data:post.title + &quot;&amp;url=&quot; + data:post.url + &quot;&amp;via=&quot;' rel='nofollow' target='_blank' title='Twitter Tweet'><i class='fa fa-twitter'/><span/></a>
        <a class='icons-facebook dhref' expr:data-text='data:post.title' expr:data-url='data:post.url' expr:href='&quot;http://www.facebook.com/share.php?v=4&amp;u=&quot; + data:post.url + &quot;&amp;t=&quot; + data:post.title' rel='nofollow' target='_blank' title='Facebook Share'><i class='fa fa-facebook'/><span/></a>
        <a class='icons-gplus dhref' expr:data-text='data:post.title' expr:data-url='data:post.url' expr:href='&quot;https://plus.google.com/share?url=&quot; + data:post.url' rel='nofollow' target='_blank' title='Google Plus Share'><i class='fa fa-google-plus'/><span/></a>
        <a class='icons-pinterest dhref' expr:data-img='data:post.thumbnailUrl' expr:data-text='data:post.title' expr:data-url='data:post.url' expr:href='&quot;http://pinterest.com/pin/create/button/?url=&quot; + data:post.url + &quot;&amp;media=&quot; + data:post.thumbnailUrl + &quot;&amp;description=&quot; + data:post.title' rel='nofollow' target='_blank' title='Share to pinterest'><i class='fa fa-pinterest'/><span/></a>
				<a class='icons-whatsapp' expr:href='&quot;whatsapp://send?text=&quot;+ data:post.title + &quot; &quot; + data:post.url' onclick='window.parent.null' rel='nofollow' target='_top' title='Share to whatsapp'><i class='fa fa-whatsapp'/><span/></a>
        <a class='icons-linkedin dhref' expr:data-text='data:post.title' expr:data-url='data:post.url' expr:href='&quot;http://www.linkedin.com/shareArticle?mini=true&amp;url=&quot; + data:post.url + &quot;&amp;title=&quot; + data:post.title + &quot;&amp;summary=&quot; + data:post.snippet' rel='nofollow' target='_blank' title='Share to linkedin'><i class='fa fa-linkedin'/><span/></a>
				<a class='icons-stumbleupon dhref' expr:data-text='data:post.title' expr:data-url='data:post.url' expr:href='&quot;http://www.stumbleupon.com/badge?url=&quot; + data:post.url + &quot;&amp;title=&quot; + data:post.title' rel='nofollow' target='_blank' title='Share to stumbleupon'><i class='fa fa-stumbleupon'/><span/></a>
      </b:includable>
      <b:includable id='backlinkDeleteIcon' var='backlink'>
        <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
          <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
            <img src='//www.blogger.com/img/icon_delete13.gif'/>
          </a>
        </span>
      </b:includable>
      <b:includable id='backlinks' var='post'>
        <a name='links'/><h4><data:post.backlinksLabel/></h4>
        <b:if cond='data:post.numBacklinks != 0'>
        <dl class='comments-block' id='comments-block'>
        <b:loop values='data:post.backlinks' var='backlink'>
        <div class='collapsed-backlink backlink-control'>
          <dt class='comment-title'>
            <span class='backlink-toggle-zippy'>&#160;</span>
            <a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
            <b:include data='backlink' name='backlinkDeleteIcon'/>
          </dt>
          <dd class='comment-body collapseable'>
            <data:backlink.snippet/>
          </dd>
          <dd class='comment-footer collapseable'>
            <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
            <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
          </dd>
        </div>
        </b:loop>
        </dl>
        </b:if>
        <p class='comment-footer'>
          <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'><data:post.createLinkLabel/></a>
        </p>
      </b:includable>
      <b:includable id='breadcrumb'>
        <div class='breadcrumbs' itemscope='' itemtype='http://schema.org/BreadcrumbList'>
          <span><a class='homex' expr:href='data:blog.homepageUrl'><span><data:homeMsg/></span></a></span><i class='fa fa-angle-right'/>
          <b:loop values='data:posts' var='post'>
						<span class='ultagnya'>
							<b:if cond='data:post.labels'>
								<b:loop values='data:post.labels' var='label'>
									<span class='labeltag' itemprop='itemListElement' itemscope='' itemtype='http://schema.org/ListItem'>
										<a expr:href='data:label.url' itemprop='item' typeof='WebPage'><span itemprop='name'><data:label.name/></span></a>
									</span>
									<b:if cond='data:label.isLast != &quot;true&quot;'><i class='fa fa-angle-right'/></b:if>
								</b:loop>
							<b:else/>
								<span class='labeltag'>Unlabelled</span>
							</b:if>
							<i class='fa bread-title fa-angle-right'/><span class='bread-title'><data:post.title/></span>			  
						</span>
          </b:loop>
        </div>
      </b:includable>
      <b:includable id='comment-form' var='post'>
				<div class='comment-form'>
          <a name='comment-form'/>
          <b:if cond='data:mobile'>
            <h4 id='comment-post-message'>
              <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a>
						</h4>
					</b:if>
          <p><data:blogCommentMessage/></p>
          <data:blogTeamBlogMessage/>
          <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
          <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:style='(data:mobile ? &quot;display:none&quot; : &quot;&quot;)' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
          <data:post.friendConnectJs/>
					<data:post.cmtfpIframe/>
					<script type='text/javascript'>
						BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
					</script>
				</div>
			</b:includable>
      <b:includable id='comment-title-picker' var='post'>
				<h4 id='comment-post-message'>		
					<data:postCommentMsg/>	
				</h4>
      </b:includable>
      <b:includable id='commentDeleteIcon' var='comment'>
        <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
          <b:if cond='data:showCmtPopup'>
            <div class='goog-toggle-button'>
              <div class='goog-inline-block comment-action-icon'/>
            </div>
          <b:else/>
            <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
              <img src='//www.blogger.com/img/icon_delete13.gif'/>
            </a>
          </b:if>
        </span>
      </b:includable>
      <b:includable id='comment_count_picker' var='post'>
        <b:if cond='data:post.forceIframeComments or data:post.commentSource == 1'>
          <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-url='data:post.canonicalUrl'/>
        <b:else/>
          <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
            <data:post.commentLabelFull/>:
          </a>       
        </b:if>
      </b:includable>
      <b:includable id='comment_picker' var='post'>
				<div class='default-comment comment-box' id='blogger_cm'>
					<b:if cond='data:post.forceIframeComments'>
						<b:include data='post' name='iframe_comments'/>
						<b:if cond='data:post.showThreadedComments'>
							<b:include data='post' name='threaded_comments'/>
						<b:else/>
							<b:include data='post' name='comments'/>
						</b:if>
					<b:else/>
						<b:if cond='data:post.commentSource == 1'>
							<b:include data='post' name='iframe_comments'/>
						<b:else/>
							<b:if cond='data:post.showThreadedComments'>
								<b:include data='post' name='threaded_comments'/>
							<b:else/>
								<b:include data='post' name='comments'/>
							</b:if>
						</b:if>
					</b:if>
				</div>
      </b:includable>
      <b:includable id='comments' var='post'> 
				<b:if cond='data:post.allowComments'>      
					<b:if cond='data:post.commentPagingRequired'>
						<span class='paging-control-container'>
							<a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
							&#160;
							<a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
							&#160;
							<data:post.commentRangeText/>
							&#160;
							<a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
							&#160;
							<a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
						</span>
					</b:if>
					<div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
						<b:if cond='data:post.numComments != 0'>
							&lt;div  class=&#39;boxcommentnya&#39;&gt;
						</b:if>        
						<dl expr:class='data:post.avatarIndentClass' id='comments-block'>
							<b:loop values='data:post.comments' var='comment'>
								<div class='commentarea'>
									<dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
										<b:if cond='data:comment.author == data:post.author'><span class='author-comment' title='Author'/></b:if>
										<b:if cond='data:comment.favicon'>
											<img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
										</b:if>
										<a expr:name='data:comment.anchorName'/>
										<b:if cond='data:blog.enabledCommentProfileImages'>
											<data:comment.authorAvatarImage/>
										</b:if>
										<b:if cond='data:comment.authorUrl'>
											<a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
										<b:else/>
											<data:comment.author/>
										</b:if>
										<data:commentPostedByMsg/>
										<a class='datecm' expr:href='data:comment.url' title='comment permalink'>
											<data:comment.timestamp/>
										</a>
									</dt>
									<dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
										<b:if cond='data:comment.isDeleted'>
											<span class='deleted-comment'><data:comment.body/></span>
										<b:else/>
											<p>
												<data:comment.body/>
											</p>
										</b:if>
									</dd>
									<dd class='comment-footer'>                              
										<b:include data='comment' name='commentDeleteIcon'/>             
									</dd>
								</div>
							</b:loop>
						</dl>  
						<b:if cond='data:post.numComments != 0'>
							&lt;/div&gt;
						</b:if>
					</div>

					<b:if cond='data:post.commentPagingRequired'>
						<span class='paging-control-container'>
							<a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
								<data:post.oldestLinkText/>
							</a>
							<a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
								<data:post.olderLinkText/>
							</a>
							&#160;
							<data:post.commentRangeText/>
							&#160;
							<a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
								<data:post.newerLinkText/>
							</a>
							<a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
								<data:post.newestLinkText/>
							</a>
						</span>
					</b:if>

					<p class='addnew-comment comment-footer'>
						<b:if cond='data:post.embedCommentForm'>
							<b:if cond='data:post.allowNewComments'>
								<b:include data='post' name='comment-form'/>
							<b:else/>
								<data:post.noNewCommentsText/>
							</b:if>
						<b:else/>
							<b:if cond='data:post.allowComments'>
								<a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
							</b:if>
						</b:if>
					</p>
	  
				</b:if>
				<b:if cond='data:showCmtPopup'>
					<div id='comment-popup'>
						<iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'/>
					</div>
				</b:if>

				<div id='backlinks-container'>
					<div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
						<b:if cond='data:post.showBacklinks'>
							<b:include data='post' name='backlinks'/>
						</b:if>
					</div>
				</div>  
      </b:includable>
      <b:includable id='enclosureindex' var='post'>
				<div class='post-type'>
					<b:loop values='data:post.enclosures' var='enclosure'>
						<b:if cond='data:enclosure.mimeType == &quot;music&quot;'>
							<i class='fa music'/>
						</b:if>
						<b:if cond='data:enclosure.mimeType == &quot;video&quot;'>
							<i class='fa video'/>
						</b:if>
						<b:if cond='data:enclosure.mimeType == &quot;gallery&quot;'>
							<i class='fa gallery'/>
						</b:if>
						<b:if cond='data:enclosure.mimeType == &quot;text&quot;'>
							<i class='fa text'/>
						</b:if>
						<b:if cond='data:enclosure.mimeType == &quot;quote&quot;'>
							<i class='fa quote'/>
						</b:if>
					</b:loop>
					<i class='fa text'/>
				</div>
			</b:includable>
      <b:includable id='feedLinks'>
        <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
					<b:if cond='data:feedLinks'>
						<div class='blog-feeds'>
							<b:include data='feedLinks' name='feedLinksBody'/>
						</div>
					</b:if>
        <b:else/> <!--Post feed links -->
          <div class='post-feeds'>
						<b:loop values='data:posts' var='post'>
							<b:if cond='data:post.allowComments and data:post.feedLinks'>								
								<b:include data='post.feedLinks' name='feedLinksBody'/>								
							</b:if>
						</b:loop>
          </div>
        </b:if>
      </b:includable>
      <b:includable id='feedLinksBody' var='links'>
        <div class='feed-links'>
          <data:feedLinksMsg/>
          <b:loop values='data:links' var='f'>
            <a class='feed-link' expr:href='data:f.url' expr:title='data:feedLinksMsg' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
          </b:loop>
        </div>
      </b:includable>
      <b:includable id='fn_comment_picker' var='post'>
        <div class='comments'>
					<b:if cond='data:post.allowComments'>
						<b:include data='post' name='comment-title-picker'/>
						<b:include data='post' name='comment_picker'/>
					<b:else/>
						<data:post.noNewCommentsText/>
					</b:if>
        </div>
      </b:includable>
      <b:includable id='iframe_comments' var='post'>
        <b:if cond='data:post.allowIframeComments'>
					<div id='gPlusComment'>
            <div class='cmt_iframe_holder' expr:data-href='data:post.canonicalUrl' expr:data-viewtype='data:post.viewType' id='gpluscomments'/>
          </div>
				</b:if>
			</b:includable>
      <b:includable id='itempostitle' var='post'>				
				<h1 class='post-title entry-title h1' itemprop='name headline'>
					<data:post.title/>
					<meta class='itemurl hidefix' expr:content='(data:post.link ? data:post.link : data:post.url ? data:post.url : data:blog.canonicalUrl)' itemprop='url'/>
					<div class='post-subtitle'/>
				</h1>				
			</b:includable>
      <b:includable id='mobile-index-post' var='post'>
        <div class='mobile-date-outer date-outer'>        
					<div class='mobile-post-outer'>
						<a expr:href='data:post.url'>
							<h3 class='mobile-index-title entry-title' itemprop='name'>
								<data:post.title/>
							</h3>
							<div class='mobile-index-arrow'>&amp;rsaquo;</div>
							<div class='mobile-index-contents'>
								<b:if cond='data:post.thumbnailUrl'>
									<div class='mobile-index-thumbnail'>
										<div class='Image'>
											<img expr:src='data:post.thumbnailUrl'/>
										</div>
									</div>
								</b:if>
								<div class='post-body'>
									<b:if cond='data:post.snippet'><data:post.snippet/></b:if>
								</div>
							</div>
							<div class='clear'/>
						</a>
						<div class='mobile-index-comment'>
							<b:include cond='data:blog.pageType != &quot;static_page&quot; and data:post.allowComments and data:post.numComments != 0' data='post' name='comment_count_picker'/>
						</div>
					</div>
        </div>
      </b:includable>
      <b:includable id='mobile-main' var='top'>
				<!-- posts -->
				<div class='blog-posts hfeed'>
					<b:if cond='data:blog.pageType in {&quot;archive&quot;, &quot;index&quot;}'>
						<div itemscope='itemscope' itemtype='http://schema.org/Blog' style='display: none;'>
							<meta expr:content='data:blog.title' itemprop='name'/>
							<b:if cond='data:blog.metaDescription'>
								<meta expr:content='data:blog.metaDescription' itemprop='description'/>
							</b:if>
						</div>	
					</b:if>
          <b:include data='top' name='status-message'/>
          <data:defaultAdStart/>
          <b:loop values='data:posts' var='post'>            
            <div class='post-outer-mobile'>
              <b:include data='post' name='mobile-post'/>           
              <b:include cond='data:blog.pageType in {&quot;static_page&quot;, &quot;item&quot;}' data='post' name='fn_comment_picker'/>                         
            </div>        
          </b:loop>          
          <data:adEnd/>
        </div>
        <div class='clear'/>		
				<b:include cond='data:blog.pageType in {&quot;index&quot;, &quot;archive&quot;}' name='mobile-nextprev'/>	
			</b:includable>
      <b:includable id='mobile-nextprev'>
        <div class='blog-pager blog-pager-mobile' id='blog-pager-mobile'>
					<b:if cond='data:newerPageUrl'>          
						<a class='newer-link-btn nextprev-button' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><i class='fa fa-chevron-left'/></a>          
					</b:if>
					<b:if cond='data:olderPageUrl'>		 
						<a class='older-link-btn nextprev-button' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><i class='fa fa-chevron-right'/></a>	  
					</b:if>		
					<div class='mobile-url-button'>
						<a class='home-url' expr:href='data:blog.homepageUrl'><i class='fa fa-home'/><data:homeMsg/></a>		
						<a class='desktop-url' expr:href='data:desktopLinkUrl'><i class='fa fa-desktop'/><data:desktopLinkMsg/></a>
					</div>
					<div class='clear'/>
				</div>
				<div class='clear'/>
      </b:includable>
      <b:includable id='mobile-post' var='post'>
				<article class='post post-mobile hentry' expr:id='data:post.id' itemscope='' itemtype='http://schema.org/BlogPosting'>		 
					<b:include cond='data:blog.pageType in {&quot;static_page&quot;, &quot;item&quot;}' data='post' name='itempostitle'/>	
					<b:if cond='data:blog.pageType == &quot;item&quot;'>
						<div class='info-mobile item-info-mobile'>
							<b:if cond='data:top.showAuthor'>
								<span class='isiinfo-mobile authorinfo' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
									<i class='fa fa-user'/>
									<b:if cond='data:post.authorProfileUrl'>
										<span class='fn'>
											<meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
											<a expr:href='data:post.authorProfileUrl' expr:title='data:post.author' rel='author'>
												<span itemprop='name'><data:post.author/></span>
											</a>
										</span>
									<b:else/>
										<span class='fn' itemprop='name'><data:post.author/></span>
									</b:if>
								</span>
							</b:if>
							<b:if cond='data:top.showTimestamp'>
								<meta expr:content='data:post.timestampISO8601' itemprop='datePublished dateModified'/>
								<span class='isiinfo-mobile dateinfo'>
									<i class='fa fa-calendar'/>
									<b:if cond='data:post.url'>
										<a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published updated' expr:datetime='data:post.timestamp' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr></a>
									</b:if>
								</span>
							</b:if>
							<b:if cond='data:top.showLocation and data:post.location'>							
								<span class='isiinfo-mobile locationinfo'>
									<i class='fa fa-map-marker'/>
									<a expr:href='data:post.location.mapsUrl' target='_blank'>
										<data:post.location.name/>
									</a>
								</span>			 
							</b:if>
						</div>
					</b:if>
					<b:if cond='data:blog.pageType in {&quot;static_page&quot;, &quot;item&quot;}'>		
						<div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' expr:itemprop='(data:blog.metaDescription ? &quot;&quot; : &quot;description &quot;) + &quot;articleBody&quot;'>
							<data:post.body/>
						</div>
					</b:if>
					<b:if cond='data:blog.pageType in {&quot;index&quot;, &quot;archive&quot;}'>		  
						<div class='post-summary-mobile' expr:id='&quot;summaryContainer-&quot; + data:post.id'>
							<!-- for non/inactive JavaScript browsers -->
              <div class='thumb-area latest-img'>
                <a expr:class='&quot;thumb-img&quot; + (data:post.thumbnailUrl or data:post.firstImageUrl ? &quot;&quot; : &quot; noimage&quot;)' expr:data-img='(data:post.thumbnailUrl ? data:post.thumbnailUrl : data:post.firstImageUrl ?  data:post.firstImageUrl : &quot;rgba(0, 0, 0, 0.15)&quot;)' expr:href='(data:post.link ? data:post.link : data:post.url)' expr:title='data:post.title' style='background:rgba(0, 0, 0, 0.15) no-repeat center center;background-size:cover&quot;'/>
                <b:include data='post' name='enclosureindex'/>
              </div>
              <b:if cond='data:post.thumbnailUrl or data:post.firstImageUrl'>
								<div class='hideit' itemprop='image' itemscope='' itemtype='https://schema.org/ImageObject'>
									<meta expr:content='data:post.firstImageUrl' itemprop='url'/>
									<meta content='800' itemprop='width'/>
									<meta content='300' itemprop='height'/>
								</div> 
							</b:if>
							<b:include data='post' name='postitle'/>
							<div class='info-mobile'>
								<b:if cond='data:top.showAuthor'>
									<span class='isiinfo-mobile authorinfo' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
										<i class='fa fa-user'/>
										<b:if cond='data:post.authorProfileUrl'>
											<span class='fn'>
												<meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
												<a expr:href='data:post.authorProfileUrl' expr:title='data:post.author' rel='author'><span itemprop='name'><data:post.author/></span></a>
											</span>
										<b:else/>
											<span class='fn' itemprop='name'><data:post.author/></span>
										</b:if>
									</span>
								</b:if>
								<b:if cond='data:top.showTimestamp'>
									<meta expr:content='data:post.timestampISO8601' itemprop='datePublished dateModified'/>
									<span class='isiinfo-mobile dateinfo'>
										<i class='fa fa-calendar'/>
										<b:if cond='data:post.url'>
											<a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published updated' expr:datetime='data:post.timestamp' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr></a>
										</b:if>
									</span>
								</b:if>				
							</div>
							<b:if cond='data:post.snippet'>
								<div class='entry-content summary-content post-content-mobile' itemprop='description'>
									<data:post.snippet/>
								</div>
							</b:if>			
							<!-- end for non/inactive JavaScript browsers -->
            </div>		  
					</b:if>
					<div class='clear'/>
					<!-- clear for photos floats -->
		  
					<b:if cond='data:blog.pageType == &quot;item&quot;'>
						<div class='itemtags'>
							<b:if cond='data:post.labels'>
								<data:postLabelsLabel/>
								<b:loop values='data:post.labels' var='label'>
									<a class='item-tag' expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'><span>,</span></b:if>				
								</b:loop>
							</b:if>
						</div>
						<div class='clear'/>
					</b:if>
				</article>
				<b:if cond='data:blog.pageType == &quot;item&quot;'>
					<b:include name='mobile-nextprev'/>
				</b:if>
				<b:if cond='data:blog.pageType in {&quot;static_page&quot;, &quot;item&quot;} and data:post.includeAd'>		
          <b:if cond='data:post.isFirstPost'>
            <data:defaultAdEnd/>
          <b:else/>
            <data:adEnd/>
          </b:if>
          <div class='inline-ad'>
            <data:adCode/>
          </div>
          <data:adStart/>        
				</b:if>
			</b:includable>
      <b:includable id='nextprev'>
				<div class='blog-pager' id='blog-pagerindex'>
					<b:if cond='data:newerPageUrl'>
						<span class='pager-newer-link'>
							<a class='blog-pager-newer-link btn' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
						</span>
						<link expr:href='data:newerPageUrl' rel='next'/>
					</b:if>
					<b:if cond='data:olderPageUrl'>
						<span class='pager-older-link'>
							<a class='blog-pager-older-link btn' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
						</span>
						<link expr:href='data:olderPageUrl' rel='prev'/>
					</b:if>
					<b:if cond='data:mobileLinkUrl'>
						<div class='mobile-link'>
							<a class='btn' expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
						</div>
					</b:if>
				</div>
				<div class='clear'/>
			</b:includable>
      <b:includable id='post' var='post'>
				<b:if cond='data:blog.pageType in {&quot;static_page&quot;, &quot;item&quot;}'>
					<div class='post-featured'/>
				</b:if>
				<b:include cond='data:blog.pageType == &quot;item&quot;' name='breadcrumb'/>
				<div class='clear'/>
				<article class='post hentry' expr:id='data:post.id' itemscope='' itemtype='http://schema.org/BlogPosting'>
					<b:include cond='data:blog.pageType in {&quot;static_page&quot;, &quot;item&quot;}' data='post' name='itempostitle'/>
					<b:include cond='data:blog.pageType == &quot;item&quot;' data='post' name='topmetaitem'/>
					<link expr:href='data:post.url' itemprop='mainEntityOfPage'/>
					<b:if cond='data:blog.pageType in {&quot;static_page&quot;, &quot;item&quot;}'>
						<div class='hide' itemprop='image' itemscope='' itemtype='https://schema.org/ImageObject'>
							<meta expr:content='data:post.firstImageUrl' itemprop='url'/>
							<meta content='800' itemprop='width'/>
							<meta content='300' itemprop='height'/>
						</div>
						<div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' expr:itemprop='(data:blog.metaDescription ? &quot;&quot; : &quot;description &quot;) + &quot;articleBody&quot;'>
							<data:post.body/>
						</div>
						<b:if cond='data:blog.metaDescription != &quot;&quot;'>
							<div class='excerpt hide'><p itemprop='description'><data:blog.metaDescription/></p></div>
						</b:if>
					</b:if>
					<b:if cond='data:blog.pageType in {&quot;index&quot;, &quot;archive&quot;}'>
						<div class='post-summary' expr:id='&quot;summaryContainer-&quot; + data:post.id'>
							<!-- for non/inactive JavaScript browsers -->
							<div class='thumb-area latest-img'>
								<a expr:class='&quot;thumb-img&quot; + (data:post.thumbnailUrl or data:post.firstImageUrl ? &quot;&quot; : &quot; noimage&quot;)' expr:data-img='(data:post.thumbnailUrl ? data:post.thumbnailUrl : data:post.firstImageUrl ?  data:post.firstImageUrl : &quot;rgba(0, 0, 0, 0.15)&quot;)' expr:href='(data:post.link ? data:post.link : data:post.url)' expr:title='data:post.title' style='background:rgba(0, 0, 0, 0.15) no-repeat center center;background-size:cover&quot;'/>
								<b:include data='post' name='enclosureindex'/>
								<div class='sharesinfo pupopsinfo'><b:include data='post' name='CustomshareButtons'/></div>
							</div>
							<b:if cond='data:post.thumbnailUrl or data:post.firstImageUrl'>
								<div class='hideit' itemprop='image' itemscope='' itemtype='https://schema.org/ImageObject'>
									<meta expr:content='data:post.firstImageUrl' itemprop='url'/>
									<meta content='800' itemprop='width'/>
									<meta content='300' itemprop='height'/>
								</div>
							</b:if>
							<div class='post-content'>
								<b:include data='post' name='postitle'/>
								<b:include data='post' name='topmetaindex'/>
								<b:if cond='data:post.snippet'>
									<meta expr:content='data:post.snippet' itemprop='description'/>
								</b:if>
								<div class='entry-content summary-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'><data:post.body/></div>			  
								<div class='bottommeta'>
									<a class='readmorebut botbutton' expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.jumpText + &quot; &quot; + data:post.title'>
										<span><data:post.jumpText/></span>
									</a>
									<div class='isiinfo sharesbottom'>
										<span class='sharesbut btn botbutton' title='Share this'><i class='fa fa-share-alt'/></span>			    
									</div>
								</div>
							</div>
							<!-- end for non/inactive JavaScript browsers -->
						</div>
					</b:if>
					<div class='clear'/><!-- clear for photos floats -->
		  
					<b:if cond='data:blog.pageType == &quot;item&quot;'>
						<div class='page-place'/>
						<div class='bottom-infoitem'>
							<div class='itemtags'>
								<b:if cond='data:post.labels'>
									<data:postLabelsLabel/>
									<b:loop values='data:post.labels' var='label'>
										<a class='item-tag' expr:href='data:label.url' expr:title='data:label.name' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'><span>,</span></b:if>
									</b:loop>
								</b:if>
							</div>
							<div class='item-share'><b:include data='post' name='CustomshareButtons'/></div>		
						</div>
						<b:if cond='data:post.authorAboutMe'>
							<div class='authorProfile' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
								<div class='authorInner'>
									<div class='autorMeta'><span><img expr:src='data:post.authorPhoto.url' itemprop='image'/></span></div>
									<div class='authorTitle'>
										<h3><a class='g-profile' expr:href='data:post.authorProfileUrl' itemprop='url' rel='author' target='_blank' title='author profile'><span itemprop='name'><data:post.author/></span></a></h3>
										<div class='authorSocial'/>
									</div>
									<p itemprop='description'><data:post.authorAboutMe/></p>
								</div>
							</div>
						</b:if>		  
					</b:if>
					<b:include data='post' name='postQuickEdit'/>
				</article>
				<b:if cond='data:blog.pageType == &quot;item&quot;'>			
					<b:include name='postnextprev'/>
					<div class='related_posts' id='related_posts'/>
				</b:if>
			</b:includable>
      <b:includable id='postQuickEdit' var='post'>
				<b:if cond='data:post.editUrl'>
					<span expr:class='&quot;item-control &quot; + data:post.adminClass'>
						<a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg' rel='nofollow'><i class='fa fa-pencil-square'/></a>
					</span>
				</b:if>
			</b:includable>
      <b:includable id='postitle' var='post'>
				<h3 class='post-title entry-title h2' itemprop='name headline'>
					<b:if cond='data:post.link'>
						<a expr:href='data:post.link' expr:title='data:post.title' itemprop='url'><data:post.title/></a>
					<b:elseif cond='data:post.url'/>			
						<a expr:href='data:post.url' expr:title='data:post.title' itemprop='url'><data:post.title/></a>
					<b:else/>
						<data:post.title/>			
          </b:if>
				</h3>		
			</b:includable>
      <b:includable id='postnextprev'>
				<div class='blog-pager blog-pager-item' id='blog-pager-item'>
					<div class='pager-isi'>
						<b:if cond='data:newerPageUrl'>
							<a class='blog-pager-newer-link-item' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><span/><div><data:newerPageTitle/></div></a>
							<link expr:href='data:newerPageUrl' rel='next'/>
						<b:else/>
							<span class='linkgrey left'><span/><div>This is the most recent post.</div></span>
						</b:if>
						<b:if cond='data:olderPageUrl'>
							<a class='blog-pager-older-link-item' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><span/><div><data:olderPageTitle/></div></a>
							<link expr:href='data:olderPageUrl' rel='prev'/>
						<b:else/>
              <span class='linkgrey right'><span/><div>This is the last post.</div></span>
						</b:if>
					</div>
				</div>
			</b:includable>
      <b:includable id='shareButtons' var='post'>
				<b:if cond='data:top.showEmailButton'>
					<a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a>
				</b:if>
				<b:if cond='data:top.showBlogThisButton'>
					<a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a>
				</b:if>
				<b:if cond='data:top.showTwitterButton'>
					<a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a>
				</b:if>
				<b:if cond='data:top.showFacebookButton'>
					<a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a>
				</b:if>
				<b:if cond='data:top.showPinterestButton'>
					<a class='goog-inline-block share-button sb-pinterest' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToPinterestMsg/></span></a>
				</b:if>
				<b:if cond='data:top.showDummy'>
					<div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
				</b:if>
			</b:includable>
      <b:includable id='status-message'>
				<b:if cond='data:navMessage'>
					<div class='msg-wrap'>
						<div class='msg-body'>
							<data:navMessage/>
						</div>
					</div>
					<div class='clear'/>
				</b:if>
			</b:includable>
      <b:includable id='threaded-comment-form' var='post'>
	    <div class='comment-form'>
				<a name='comment-form'/>					
				<div id='form-wrapper'>
					<p><data:blogCommentMessage/></p>
					<data:blogTeamBlogMessage/>
					<a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
					<iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:style='(data:mobile ? &quot;display: none&quot; : &quot;&quot;)' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
				</div>					
				<data:post.friendConnectJs/>
				<data:post.cmtfpIframe/>
				<script type='text/javascript'>
					BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
				</script>
				</div>
			</b:includable>
      <b:includable id='threaded_comment_js' var='post'>
				<script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
				<script type='text/javascript'>
		  (function() {
		    var items = <data:post.commentJso/>;
			var msgs = <data:post.commentMsgs/>;
			var config = <data:post.commentConfig/>;
			// <![CDATA[
			  var cursor=null;items&&0<items.length&&(cursor=parseInt(items[items.length-1].timestamp)+1);var bodyFromEntry=function(e){if(e.gd$extendedProperty)for(var t in e.gd$extendedProperty)if("blogger.contentRemoved"==e.gd$extendedProperty[t].name)return'<span class="deleted-comment">'+e.content.$t+"</span>";return e.content.$t},parse=function(e){cursor=null;var t=[];if(e&&e.feed&&e.feed.entry)for(var r,o=0;r=e.feed.entry[o];o++){var n={},a=/blog-(\d+).post-(\d+)/.exec(r.id.$t);if(n.id=a?a[2]:null,n.body=bodyFromEntry(r),n.timestamp=Date.parse(r.published.$t)+"",r.author&&r.author.constructor===Array&&(a=r.author[0])&&(n.author={name:a.name?a.name.$t:void 0,profileUrl:a.uri?a.uri.$t:void 0,avatarUrl:a.gd$image?a.gd$image.src:void 0}),r.link&&(r.link[2]&&(n.link=n.permalink=r.link[2].href),r.link[3]&&(a=/.*comments\/default\/(\d+)\?.*/.exec(r.link[3].href))&&a[1]&&(n.parentId=a[1])),n.deleteclass="item-control blog-admin",r.gd$extendedProperty)for(var d in r.gd$extendedProperty)"blogger.itemClass"==r.gd$extendedProperty[d].name?n.deleteclass+=" "+r.gd$extendedProperty[d].value:"blogger.displayTime"==r.gd$extendedProperty[d].name&&(n.displayTime=r.gd$extendedProperty[d].value);t.push(n)}return t},paginator=function(e){if(hasMore()){var t=config.feed+"?alt=json&v=2&orderby=published&reverse=false&max-results=50";cursor&&(t+="&published-min="+new Date(cursor).toISOString()),window.bloggercomments=function(t){t=parse(t),cursor=50>t.length?null:parseInt(t[t.length-1].timestamp)+1,e(t),window.bloggercomments=null};var t=t+"&callback=bloggercomments",r=document.createElement("script");r.type="text/javascript",r.src=t,document.getElementsByTagName("head")[0].appendChild(r)}},hasMore=function(){return!!cursor},getMeta=function(e,t){return"iswriter"==e?t.author&&t.author.name==config.authorName&&t.author.profileUrl==config.authorUrl?"true":"":"deletelink"==e?config.baseUri+"/delete-comment.g?blogID="+config.blogId+"&postID="+t.id:"deleteclass"==e?t.deleteclass:""},replybox=null,replyUrlParts=null,replyParent=void 0,onReply=function(e,t){null==replybox&&(replybox=document.getElementById("comment-editor"),null!=replybox&&(replybox.height="250px",replybox.style.display="block",replyUrlParts=replybox.src.split("#"))),replybox&&e!==replyParent&&(document.getElementById(t).insertBefore(document.getElementById("form-wrapper"),null),replybox.src=replyUrlParts[0]+(e?"&parentID="+e:"")+"#"+replyUrlParts[1],replyParent=e)},hash=(window.location.hash||"#").substring(1),startThread,targetComment;/^comment-form_/.test(hash)?startThread=hash.substring(13):/^c[0-9]+$/.test(hash)&&(targetComment=hash.substring(1));var configJso={maxDepth:config.maxThreadDepth},provider={id:config.postId,data:items,loadNext:paginator,hasMore:hasMore,getMeta:getMeta,onReply:onReply,rendered:!0,initComment:targetComment,initReplyThread:startThread,config:configJso,messages:msgs},render=function(){if(window.goog&&window.goog.comments){var e=document.getElementById("comment-holder");window.goog.comments.render(e,provider)}};window.goog&&window.goog.comments?render():(window.goog=window.goog||{},window.goog.comments=window.goog.comments||{},window.goog.comments.loadQueue=window.goog.comments.loadQueue||[],window.goog.comments.loadQueue.push(render));
			})();
		  // ]]>
			</script>
			</b:includable>
      <b:includable id='threaded_comments' var='post'>
				<div class='comments-content'>
					<b:if cond='data:post.embedCommentForm'>
						<b:include data='post' name='threaded_comment_js'/>
					</b:if>
					<div id='comment-holder'>
						<data:post.commentHtml/>
					</div>
				</div>
				<p class='comment-footer'>
					<b:if cond='data:post.allowNewComments'>
						<b:include data='post' name='threaded-comment-form'/>
					<b:else/>
						<data:post.noNewCommentsText/>
					</b:if>
				</p>
				<b:if cond='data:showCmtPopup'>
					<div id='comment-popup'>
						<iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'/>
					</div>
				</b:if>
				<div id='backlinks-container'>
					<div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
						<b:if cond='data:post.showBacklinks'>
							<b:include data='post' name='backlinks'/>
						</b:if>
					</div>
				</div>
			</b:includable>
      <b:includable id='topmetaindex' var='post'>
				<div class='topmetainfo'>
					<b:if cond='data:top.showAuthor'>
						<span class='isiinfo authorinfo vcard author' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
							<i class='fa fa-user'/>
							<span class='infometa'>
								<b:if cond='data:post.authorProfileUrl'>
									<span class='fn'>
										<meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
										<a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
											<span itemprop='name'><data:post.author/></span>
										</a>
									</span>
								<b:else/>
									<span class='fn' itemprop='name'><data:post.author/></span>
								</b:if>
							</span>
						</span>
						<div class='hide' itemprop='publisher' itemscope='itemscope' itemtype='https://schema.org/Organization'>
							<div itemprop='logo' itemscope='itemscope' itemtype='https://schema.org/ImageObject'>
								<meta expr:content='&quot;http:&quot; + data:post.authorPhoto.url' itemprop='url'/>
								<meta content='600' itemprop='width'/>
								<meta content='60' itemprop='height'/>
							</div>
							<meta expr:content='data:blog.title' itemprop='name'/>
						</div>
					</b:if>
					<b:if cond='data:top.showTimestamp'>
						<meta expr:content='data:post.timestampISO8601' itemprop='datePublished dateModified'/>
						<span class='isiinfo dateinfo'>
							<i class='fa fa-calendar'/>
							<span class='infometa'>
								<b:if cond='data:post.url'>
									<a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published updated' expr:datetime='data:post.timestamp' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr></a>
								</b:if>
							</span>
						</span>
					</b:if>
					<b:if cond='data:post.allowComments and data:post.numComments != 0'>
						<span class='isiinfo itemcomment'><i class='fa fa-comments'/> <a class='commentnum' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick' expr:title='data:post.numComments' itemprop='discussionUrl'><span itemprop='interactionCount'><data:post.numComments/></span></a></span>
					</b:if>
					<b:if cond='data:post.labels'>
						<span class='isiinfo labelsbottom'>
							<i class='fa fa-tags'/>
							<b:loop values='data:post.labels' var='label'>
								<a expr:class='(data:blog.searchLabel == data:label.name ? &quot;labelqi &quot; : &quot;&quot; ) + &quot;labtn&quot;' expr:href='data:label.url' expr:title='data:label.name' rel='tag'><data:label.name/></a>
								<b:if cond='data:label.isLast != &quot;true&quot;'><span>,</span></b:if>
							</b:loop>
						</span>
					</b:if>
				</div>
			</b:includable>
      <b:includable id='topmetaitem' var='post'>
				<div class='item-topmeta'>
					<b:if cond='data:top.showAuthor'>
						<span class='item-info authorinfo vcard author' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
							<i class='fa fa-user'/>
							<b:if cond='data:post.authorProfileUrl'>
								<span class='fn'>
									<meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
									<a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
										<span itemprop='name'><data:post.author/></span>
									</a>
								</span>
							<b:else/>
								<span class='fn' itemprop='name'><data:post.author/></span>
							</b:if>
						</span>
						<div class='hide' itemprop='publisher' itemscope='itemscope' itemtype='https://schema.org/Organization'>
							<div itemprop='logo' itemscope='itemscope' itemtype='https://schema.org/ImageObject'>
								<meta expr:content='&quot;http:&quot; + data:post.authorPhoto.url' itemprop='url'/>
								<meta content='600' itemprop='width'/>
								<meta content='60' itemprop='height'/>
							</div>
							<meta expr:content='data:blog.title' itemprop='name'/>
						</div>
					</b:if>
					<b:if cond='data:top.showTimestamp'>
						<meta expr:content='data:post.timestampISO8601' itemprop='datePublished dateModified'/>
						<span class='item-info dateinfo'>
							<i class='fa fa-calendar'/>
							<b:if cond='data:post.url'>
								<a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published updated' expr:datetime='data:post.timestamp' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr></a>
							</b:if>
						</span>
					</b:if>
					<b:if cond='data:post.allowComments and data:post.numComments != 0'>
						<span class='comment-item'>
							<i class='fa fa-comments'/> 
							<a class='itemcommentnum' expr:href='data:post.url + &quot;#comments-area&quot;' expr:onclick='data:post.addCommentOnclick' itemprop='discussionUrl'><b:if cond='data:post.numComments == 1'><span itemprop='interactionCount'><data:post.numComments/></span> <data:top.commentLabel/><b:else/><span itemprop='interactionCount'><data:post.numComments/></span> <data:top.commentLabelPlural/></b:if></a>
						</span>
					</b:if>
					<div class='more-options'>
						<span class='zoomingtext'>
							<a class='zoom-text zoom-in-text' href='#A+' title='zoom-in-text'>A<span>+</span></a>
							<a class='zoom-text zoom-out-text' href='#A-' title='zoom-out-text'>A<span>-</span></a>
						</span>
						<span class='more-button'>
							<a class='button_print' onClick='window.print()'><i class='fa fa-print'/> Print</a>
							<a class='button_email' expr:href='&quot;http://www.blogger.com/share-post.g?blogID=&quot; + data:blog.blogId + &quot;&amp;postID=&quot; +data:post.id+ &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><i class='fa fa-envelope'/> Email</a>
						</span>
						<div class='text-finder-area'>
							<form action='javascript:;' class='text-finder' id='text-finder'>
								<input placeholder='Find...' type='text'/>
								<input type='reset' value='&amp;times;'/>
							</form>
							<span class='btntextFind'><i class='fa fa-search'/></span>
             </div>
					</div>
				</div>
			</b:includable>
    </b:widget>
  </b:section>
  <b:section class='bottom-setting-sec blogpost-setting' id='bottom-setting-sec1' showaddelement='no'>
    <b:widget id='HTML870' locked='true' title='Comments system' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'>[blogger][disqus][facebook][spotim]</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
				<b:if cond='data:blog.pageType in {&quot;item&quot;, &quot;static_page&quot;}'>
					<div class='comments-tabs'>
						<b:if cond='data:content == &quot;&quot;'>
							[blogger]
						<b:else/>
							<data:content/>
						</b:if>
					</div>
				</b:if>
      </b:includable>
    </b:widget>
    <b:widget id='HTML871' locked='true' title='Disqus Shortname' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'>kunapatra</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
				<b:if cond='data:content != &quot;&quot; or data:content != &quot;n&quot;'>
					<span class='vardisqusshortname' expr:title='data:content'/>
					<div id='drcmt' style='display:none'/>
				</b:if>
      </b:includable>
    </b:widget>
    <b:widget id='HTML878' locked='true' title='Spot.IM ID' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'/>
      </b:widget-settings>
      <b:includable id='main'>
				<b:if cond='data:content != &quot;&quot; or data:content != &quot;n&quot;'>
					<span class='varspotimid' expr:title='data:content'/>
				</b:if>
			</b:includable>
    </b:widget>
    <b:widget id='HTML872' locked='true' title='Flickr User ID' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'/>
      </b:widget-settings>
      <b:includable id='main'>
				<b:if cond='data:content != &quot;&quot; or data:content != &quot;n&quot;'>
					<span class='varflickrid' expr:title='data:content'/>	
					<div id='flickrid' style='display:none'/>
				</b:if>
			</b:includable>
    </b:widget>
  </b:section>
	
	<b:if cond='data:blog.url == data:blog.homepageUrl'>
		<div class='main-bottom-area1'>
			<b:section class='sidebar homepost main-homepost' id='main-bottom' preferred='yes'>
<b:widget id='HTML9' locked='false' title='Sponsor Ad' type='HTML'>
  <b:widget-settings>
    <b:widget-setting name='content'><![CDATA[<a href="https://www.znetlive.com/bundled-offers/?afl=OTU2Mzg="><img src="https://manage.znetlive.com/attachments/31032015135445_730-155.gif" width="730x155" height="" alt="Complete Online Bundle2" /></a>]]></b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
<b:widget id='HTML1' locked='false' title='Sad' type='HTML'>
  <b:widget-settings>
    <b:widget-setting name='content'>[Sad][fbig1]</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>
			<div class='main-bottom-column clearfix'>
				<b:section class='sidebar homepost main-homepost main-column-left' id='main-bottom2' preferred='yes'>
<b:widget id='HTML2' locked='false' title='Joke' type='HTML'>
  <b:widget-settings>
    <b:widget-setting name='content'>[Joke][column1]</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>
				<b:section class='sidebar homepost main-homepost main-column-right' id='main-bottom3' preferred='yes'>
<b:widget id='HTML3' locked='false' title='Heart Touching' type='HTML'>
  <b:widget-settings>
    <b:widget-setting name='content'>[Heart Touching][column1]</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>
				<div class='clear'/>
			</div>
			<b:section class='sidebar homepost main-homepost' id='main-bottom4' preferred='yes'>
<b:widget id='HTML10' locked='false' title='Free Product from Amazone.in' type='HTML'>
  <b:widget-settings>
    <b:widget-setting name='content'>&lt;script type=&quot;text/javascript&quot; language=&quot;javascript&quot;&gt;
      var aax_size=&#39;728x90&#39;;
      var aax_pubname = &#39;offersmarket-21&#39;;
      var aax_src=&#39;302&#39;;
    &lt;/script&gt;
    &lt;script type=&quot;text/javascript&quot; language=&quot;javascript&quot; src=&quot;http://c.amazon-adsystem.com/aax2/assoc.js&quot;&gt;&lt;/script&gt;</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
<b:widget id='HTML4' locked='false' title='Love' type='HTML'>
  <b:widget-settings>
    <b:widget-setting name='content'>[Love][gallery1]</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>
			<div class='main-bottom-column clearfix'>
				<b:section class='sidebar homepost main-homepost main-column-left' id='main-bottom5' preferred='yes'/>
				<b:section class='sidebar homepost main-homepost main-column-right' id='main-bottom6' preferred='yes'/>
				<div class='clear'/>
			</div>
			<b:section class='sidebar homepost main-homepost' id='main-bottom7' preferred='yes'>
<b:widget id='HTML5' locked='false' title='Just For You' type='HTML'>
  <b:widget-settings>
    <b:widget-setting name='content'>complex{fbig2}/Love, Sad, Heart Touching</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>
		</div>
	</b:if>
</div>
</div>
<aside class='sidebar-area' id='sidebar-wrapper' itemprop='mainEntity' itemscope='' itemtype='http://schema.org/WPSideBar'>
<div class='sidebar-right'>
<div class='innerwrap'>
  <div id='sidebar-top'>
		<b:section class='sidebar' id='sidebar-atas1' preferred='yes'>
<b:widget id='HTML8' locked='false' title='Facebook Fan Page' type='HTML'>
  <b:widget-settings>
    <b:widget-setting name='content'>FBbox/https://www.facebook.com/kunapatraofficial</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
<b:widget id='LinkList857' locked='true' title='Social Counter' type='LinkList' version='1'>
  <b:includable id='main'>
          <b:if cond='data:title != &quot;&quot;'><h2 class='title'><data:title/></h2></b:if>
					<div class='widget-content social-wrap'>
						<ul>
							<b:loop values='data:links' var='link'>
								<li><a expr:href='data:link.target' expr:title='data:link.name' rel='nofollow' target='_blank'><span class='icon-counter'><i expr:class='&quot;fa icon-&quot; + data:link.name'/></span><div class='social-desc'><div class='hide-count'><data:link.name/></div><span class='item-text'>Followers</span></div></a></li>
							</b:loop>
						</ul>
					</div>
				</b:includable>
</b:widget>
<b:widget id='FollowByEmail800' locked='false' title='Follow by Email' type='FollowByEmail' version='1'>
  <b:includable id='main'>
					<b:if cond='data:title != &quot;&quot;'><h2 class='title'><data:title/></h2></b:if>
					<div class='widget-content'>
						<div class='sevida-emailtext'>Enter your email address to subscribe to this blog and receive notifications of new posts by email.</div>
						<div class='sevida-by-email-inner'>
							<form action='https://feedburner.google.com/fb/a/mailverify' expr:onsubmit='&quot;window.open(\&quot;https://feedburner.google.com/fb/a/mailverify?uri=&quot; + data:feedPath + &quot;\&quot;, \&quot;popupwindow\&quot;, \&quot;scrollbars=yes,width=550,height=520\&quot;); return true&quot;' method='post' target='popupwindow'>
								<div class='sevida-email-area'><input class='sevida-by-email-address' name='email' placeholder='Email address...' type='text'/></div>
								<div class='sevida-email-input'><input class='sevida-by-email-submit' type='submit' value='Subscribe Me'/></div>
								<input expr:value='data:feedPath' name='uri' type='hidden'/>
								<input name='loc' type='hidden' value='en_US'/>
							</form>
						</div>
					</div>
				</b:includable>
</b:widget>
</b:section>
  </div>
  <div class='sidebartabs' id='sidebartabs'>
    <b:section class='sidebar' id='sidebar-tabs1' preferred='yes'>
      <b:widget id='HTML6' locked='false' title='Recent Post' type='HTML'>
        <b:widget-settings>
          <b:widget-setting name='content'>recentpost</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
      </b:widget>
      <b:widget id='PopularPosts800' locked='false' title='Populars' type='PopularPosts' version='1'>
        <b:widget-settings>
          <b:widget-setting name='numItemsToShow'>10</b:widget-setting>
          <b:widget-setting name='showThumbnails'>true</b:widget-setting>
          <b:widget-setting name='showSnippets'>true</b:widget-setting>
          <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
					<b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
						<div class='widget-content popular-posts'>
							<ul>
								<b:loop values='data:posts' var='post'>
									<li>
									<b:if cond='!data:showThumbnails'>
										<b:if cond='!data:showSnippets'>
											<!-- (1) No snippet/thumbnail -->
											<a expr:href='data:post.href' expr:title='data:post.title'><data:post.title/></a>
										<b:else/>
											<!-- (2) Show only snippets -->
											<div class='item-title'><a expr:href='data:post.href' expr:title='data:post.title'><data:post.title/></a></div>
											<div class='item-snippet'><data:post.snippet/></div>
										</b:if>
									<b:else/>
										<!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
										<div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
											<b:if cond='data:post.thumbnail'>
												<div class='item-thumbnail'>
													<a class='populars-img' expr:data-img='data:post.thumbnail' expr:href='data:post.href' expr:title='data:post.title' style='background:rgba(0, 0, 0, 0.15) no-repeat center center;background-size:cover'/>
												</div>
											</b:if>
											<div class='item-title'><a expr:href='data:post.href' expr:title='data:post.title'><data:post.title/></a></div>
											<b:if cond='data:showSnippets'>
												<div class='item-snippet'><data:post.snippet/></div>
											</b:if>
										</div>
										<div style='clear: both;'/>
									</b:if>
								</li>
							</b:loop>
						</ul>    
					</div>
				</b:includable>
      </b:widget>
    </b:section>  
  </div>
  <div id='sidebar-bottom'>
    <b:section class='sidebar' id='sidebar-bottom1' preferred='yes'/>
  </div>
  <div class='clear'/>
</div>
</div>
<div class='sidebar-left'>
<div class='innerwrap'>
  <b:section class='sidebar' id='sidebar-left' preferred='yes'/>  
</div>
</div>
</aside><!-- end sidebar-wrapper -->
<!-- spacer for skins that want sidebar and main to be the same height-->
<div class='clear'/>

</div>
</div> <!-- end content-wrapper -->


<footer class='footer-area' id='footer-wrapper' itemprop='mainEntity' itemscope='' itemtype='http://schema.org/WPFooter'>

<div class='wrap'>
 <b:section class='footer' id='footer1' showaddelement='yes'/>  
 <b:section class='footer' id='footer2' showaddelement='yes'/>   
 <b:section class='footer' id='footer3' showaddelement='yes'/>
 <b:section class='footer' id='footer4' showaddelement='yes'>
   <b:widget id='HTML12' locked='false' title='Random Posts' type='HTML'>
     <b:widget-settings>
       <b:widget-setting name='content'>&lt;!-- Histats.com  START (html only)--&gt;
&lt;a href=&quot;/viewstats/?SID=3828952&amp;f=2&quot; alt=&quot;website free tracking&quot; target=&quot;_blank&quot; &gt;&lt;div id=&quot;histatsC&quot;&gt;&lt;img border=&quot;0&quot; src=&quot;http://s4is.histats.com/stats/i/3828952.gif?3828952&amp;amp;103&quot; /&gt;&lt;/div&gt;&lt;/a&gt;
&lt;!-- Histats.com  END  --&gt;</b:widget-setting>
     </b:widget-settings>
     <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
   </b:widget>
 </b:section>
</div>
<div class='clear'/>
<div class='copyright-area'>
<div class='wrap wrap-bottom'>
<div class='wrap-inner'>  
  <div class='row'>
	<div class='pull-left'><a expr:href='data:blog.homepageUrl'><data:blog.title/></a> &#169; 2016. All Rights Reserved.</div>
    <div class='pull-right'>Developed by <a href='http://www.facebook.com/kpatra321/' rel='nofollow' target='_blank'>Kuna Patra</a></div>
  </div>
</div>
</div>
</div>
</footer><!-- end footer-wrapper -->

<div class='contact-btn-area'><span class='contact-button' title='Contact Us'><i class='fa fa-envelope-o'/></span></div>
<a class='gotop' href='#webpage' id='gotop' title='Scroll to Top'><i class='fa fa-arrow-up'/></a>
<div class='bottom-section-area'>
<div class='author-profile-area'>
  <b:section class='profile-sec' id='author-section1' showaddelement='yes'>
    <b:widget id='HTML873' locked='false' title='Author Name' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'>{picture#https://2.bp.blogspot.com/-k0W2G3yZPpg/WDWYZwoaevI/AAAAAAAAEGM/9ff30Cyony8Bq4kfyTrGCEMDlgZnfnZ_ACPcB/s1600/kp%2Bdppppppp.jpg}

Hi Im Kuna Patra (Narsing Patra) a Blogger, Web Developer, DJ, VFX and GFX Artist &amp; Photographer from Kodinga, Nabarangpur, Orissa, India

{facebook#http://www.facebook.com/kpatra321}
{twitter#http://www.twitter.com/kpatra321kuna}
{google#https://plus.google.com/u/0/+KunaPatraofficial}
{youtube#https://www.youtube.com/channel/UCWTVVZlyrnFxXNP7MkvMk8w}
{instagram#http://www.instagram.com/djkunaofficial}</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
				<b:if cond='data:title != &quot;&quot;'> <h2 class='title'><data:title/></h2></b:if>
				<div class='widget-content'>
					<data:content/>
				</div>
			</b:includable>
    </b:widget>
  </b:section>
</div>
<div class='manual-image-area'>
  <b:section class='image-manual-slide' id='image-section1' showaddelement='yes'>
    <b:widget id='Image850' locked='false' title='Image 1 Title' type='Image' version='1'>
      <b:includable id='main'>
				<span class='manual-img-raw' expr:data-caption='data:caption' expr:data-img='data:sourceUrl' expr:data-link='data:link' expr:data-title='(data:title != &quot;&quot; ? data:title : &quot;&quot; )'/>
			</b:includable>
    </b:widget>
    <b:widget id='Image851' locked='false' title='Image 2 Title' type='Image' version='1'>
      <b:includable id='main'>
				<span class='manual-img-raw' expr:data-caption='data:caption' expr:data-img='data:sourceUrl' expr:data-link='data:link' expr:data-title='(data:title != &quot;&quot; ? data:title : &quot;&quot; )'/>
			</b:includable>
    </b:widget>
    <b:widget id='Image852' locked='false' title='Image 3 Title' type='Image' version='1'>
      <b:includable id='main'>
				<span class='manual-img-raw' expr:data-caption='data:caption' expr:data-img='data:sourceUrl' expr:data-link='data:link' expr:data-title='(data:title != &quot;&quot; ? data:title : &quot;&quot; )'/>
			</b:includable>
    </b:widget>
    <b:widget id='Image853' locked='false' title='Image 4 Title' type='Image' version='1'>
      <b:includable id='main'>
				<span class='manual-img-raw' expr:data-caption='data:caption' expr:data-img='data:sourceUrl' expr:data-link='data:link' expr:data-title='(data:title != &quot;&quot; ? data:title : &quot;&quot; )'/>
			</b:includable>
    </b:widget>
    <b:widget id='Image854' locked='false' title='Image 5 Title' type='Image' version='1'>
      <b:includable id='main'>
				<span class='manual-img-raw' expr:data-caption='data:caption' expr:data-img='data:sourceUrl' expr:data-link='data:link' expr:data-title='(data:title != &quot;&quot; ? data:title : &quot;&quot; )'/>
			</b:includable>
    </b:widget>
    <b:widget id='Image855' locked='false' title='Image 6 Title' type='Image' version='1'>
      <b:includable id='main'>
				<span class='manual-img-raw' expr:data-caption='data:caption' expr:data-img='data:sourceUrl' expr:data-link='data:link' expr:data-title='(data:title != &quot;&quot; ? data:title : &quot;&quot; )'/>
			</b:includable>
    </b:widget>
    <b:widget id='Image856' locked='false' title='Image 7 Title' type='Image' version='1'>
      <b:includable id='main'>
				<span class='manual-img-raw' expr:data-caption='data:caption' expr:data-img='data:sourceUrl' expr:data-link='data:link' expr:data-title='(data:title != &quot;&quot; ? data:title : &quot;&quot; )'/>
			</b:includable>
    </b:widget>
    <b:widget id='Image857' locked='false' title='Image 8 Title' type='Image' version='1'>
      <b:includable id='main'>
				<span class='manual-img-raw' expr:data-caption='data:caption' expr:data-img='data:sourceUrl' expr:data-link='data:link' expr:data-title='(data:title != &quot;&quot; ? data:title : &quot;&quot; )'/>
			</b:includable>
    </b:widget>
    <b:widget id='Image858' locked='false' title='Image 9 Title' type='Image' version='1'>
      <b:includable id='main'>
				<span class='manual-img-raw' expr:data-caption='data:caption' expr:data-img='data:sourceUrl' expr:data-link='data:link' expr:data-title='(data:title != &quot;&quot; ? data:title : &quot;&quot; )'/>
			</b:includable>
    </b:widget>
    <b:widget id='Image859' locked='false' title='Image 10 Title' type='Image' version='1'>
      <b:includable id='main'>
				<span class='manual-img-raw' expr:data-caption='data:caption' expr:data-img='data:sourceUrl' expr:data-link='data:link' expr:data-title='(data:title != &quot;&quot; ? data:title : &quot;&quot; )'/>
			</b:includable>
    </b:widget>
  </b:section>
</div>
   
  </div>
<b:section class='contact-sec' id='contact-sec' maxwidgets='1' showaddelement='yes'>
  <b:widget id='ContactForm1' locked='false' title='Contact Form' type='ContactForm' version='1'>
    <b:includable id='main'>
			<b:if cond='data:title != &quot;&quot;'><h2 class='title'><data:title/></h2></b:if>
			<div class='contact-form-widget'>
				<div class='form'>
				<form name='contact-form'>
					<p/>
					<data:contactFormNameMsg/>
					<br/>
					<input class='contact-form-name' expr:id='data:widget.instanceId + &quot;_contact-form-name&quot;' name='name' size='30' type='text' value=''/>
					<p/>
					<data:contactFormEmailMsg/> <span style='font-weight: bolder;'>*</span>
					<br/>
					<input class='contact-form-email' expr:id='data:widget.instanceId + &quot;_contact-form-email&quot;' name='email' size='30' type='text' value=''/>
					<p/>
					<data:contactFormMessageMsg/> <span style='font-weight: bolder;'>*</span>
					<br/>
					<textarea class='contact-form-email-message' cols='25' expr:id='data:widget.instanceId + &quot;_contact-form-email-message&quot;' name='email-message' rows='5'/>
					<p/>
					<input class='contact-form-button contact-form-button-submit' expr:id='data:widget.instanceId + &quot;_contact-form-submit&quot;' expr:value='data:contactFormSendMsg' type='button'/>
					<p/>
					<div style='text-align: center; max-width: 222px; width: 100%'>
						<p class='contact-form-error-message' expr:id='data:widget.instanceId + &quot;_contact-form-error-message&quot;'/>
						<p class='contact-form-success-message' expr:id='data:widget.instanceId + &quot;_contact-form-success-message&quot;'/>
					</div>
				</form>
				</div>
			</div>
			<a class='contact-close' href='#'><i class='fa fa-times'/></a>
	  </b:includable>
  </b:widget>
</b:section>
<!-- Contact Us form -->
<div class='hidden-contact' style='display:none'>
<b:section class='contact' id='contact' maxwidgets='1' showaddelement='no'>
  <b:widget id='ContactForm10' locked='true' title='Contact us' type='ContactForm' version='1'>
    <b:includable id='main'>
			<div class='contact-form-widget'>
				<div class='form'>
					<form name='contact-form'>
						<input class='contact-form-name' expr:id='data:widget.instanceId + &quot;_contact-form-name&quot;' expr:placeholder='data:contactFormNameMsg' name='name' size='30' type='text' value=''/>
						<input class='contact-form-email' expr:id='data:widget.instanceId + &quot;_contact-form-email&quot;' expr:placeholder='data:contactFormEmailMsg' name='email' size='30' type='text' value=''/>
						<div class='clear'/>
						<textarea class='contact-form-email-message' cols='25' expr:id='data:widget.instanceId + &quot;_contact-form-email-message&quot;' expr:placeholder='data:contactFormMessageMsg' name='email-message' rows='5'/>
						<input class='contact-form-button contact-form-button-submit' expr:id='data:widget.instanceId + &quot;_contact-form-submit&quot;' expr:value='data:contactFormSendMsg' type='button'/>
							<div style='text-align: center; max-width: 222px; width: 100%'>
								<p class='contact-form-error-message' expr:id='data:widget.instanceId + &quot;_contact-form-error-message&quot;'/>
								<p class='contact-form-success-message' expr:id='data:widget.instanceId + &quot;_contact-form-success-message&quot;'/>
							</div>
					</form>
				</div>
			</div>
		</b:includable>
  </b:widget>
</b:section>
</div>

<!-- unwanted widgets -->
  <div style='display: none'>
    <b:section class='unwanted' id='unwanted' showaddelement='no' style='display: none'>
      <b:widget id='Attribution1' locked='true' title='' type='Attribution'>
        <b:widget-settings>
          <b:widget-setting name='copyright'/>
        </b:widget-settings>
        <b:includable id='main'>
    <div class='widget-content' style='text-align: center;'>
      <b:if cond='data:attribution != &quot;&quot;'>
       <data:attribution/>
      </b:if>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
      </b:widget>
    </b:section>
  </div>
</div> <!-- end outer-wrapper -->
</div>
</div>
<div expr:class='data:blog.languageDirection' id='dectdirect' style='display:none'/>
<b:if cond='data:blog.searchQuery'><span class='searchQuered'/></b:if>
<b:include data='blog' name='google-analytics'/>
<span class='canUrl' expr:title='data:blog.canonicalUrl'/>
<span class='bposId' expr:title='data:blog.postId'/>
<span class='pstUrl' expr:title='data:blog.url'/>
<script type='text/javascript'>
//<![CDATA[
var emoIMG = {
  emo1 : "https://lh3.googleusercontent.com/-duNoMAb1RS4/T2WEWrOfR8I/AAAAAAAACZ0/ObgHf-PmTuE/s36/03.gif",
  emo2 : "https://lh6.googleusercontent.com/-LIr-ZdDp2xI/T2WEYDacVnI/AAAAAAAACaY/W7MF5qKO2sE/s47/06.gif",
  emo3 : "https://lh6.googleusercontent.com/-Q5lMkgcmVR4/T2WEWkNi3MI/AAAAAAAACZ4/7VBYeVbx7kA/s36/01.gif",
  emo4 : "https://lh3.googleusercontent.com/-mCsZPeixHvA/T2WEWivv9FI/AAAAAAAACZw/64ZGRgdlDeg/s36/02.gif",
  emo5 : "https://lh5.googleusercontent.com/-u__sc3DgZ2c/T2d0_lDLueI/AAAAAAAACkw/YbeuRNde61Q/s36/03a.gif",
  emo6 : "https://lh5.googleusercontent.com/-EwonQGBTYwo/T2WEXeVq3oI/AAAAAAAACZ8/4ixt2ZVlqrI/s36/04.gif",
  emo7 : "https://lh3.googleusercontent.com/-fMtAZDakmBI/T2WEXswr5BI/AAAAAAAACaA/83R1X_PumTk/s36/05.gif",
  emo8 : "https://lh3.googleusercontent.com/-Em3lvBgvYlI/T2WElbV0BaI/AAAAAAAACdI/ApynphQdka8/s36/7.gif",
  emo9 : "https://lh4.googleusercontent.com/-0R7-2DC1klM/T2WEmMQajfI/AAAAAAAACdM/-4JFCeC6QD8/s36/8.gif",
  emo10 : "https://lh5.googleusercontent.com/-PE2GWBseiGk/T2acYH_uNRI/AAAAAAAAChg/HloTeaRIdyQ/s36/09.gif",
  emo11 : "https://lh5.googleusercontent.com/-nkyzLkHUPg8/T2WEYdFqFxI/AAAAAAAACaQ/Mu1yPq91yuc/s36/10.gif",
  emo12 : "https://lh6.googleusercontent.com/-0-zgLVgK2Cg/T2WEY10FXuI/AAAAAAAACag/dyKQ5pPUIGQ/s36/11.gif",
  emo13 : "https://lh3.googleusercontent.com/-xbWqvOWJNE0/T2WEZM-VLTI/AAAAAAAACak/8dLATIlXRDk/s36/12.gif",
  emo14 : "https://lh4.googleusercontent.com/-cguZVxYzR3o/T2WEZSgFvUI/AAAAAAAACas/nDJgr6YcuaI/s36/13.gif",
  emo15 : "https://lh5.googleusercontent.com/-VKGWq-wPGUw/T2WEaEQLA9I/AAAAAAAACa4/ZDnLP29mlgk/s36/14.gif",
  emo16 : "https://lh6.googleusercontent.com/-hIVRIc7IAJw/T2WEaO5ASUI/AAAAAAAACaw/FLmCvzeMSbc/s36/15.gif",
  emo17 : "https://lh4.googleusercontent.com/-hk3q3tP-0Pg/T2WEcRONc5I/AAAAAAAACbY/bJ00rge5Mq8/s36/16.gif",
  emo18 : "https://lh5.googleusercontent.com/-cysJNcXxT-Q/T2WEcxVM5dI/AAAAAAAACbU/Mvuc437f1ZI/s36/17.gif",
  emo19 : "https://lh6.googleusercontent.com/-H20tIsy7Hvw/T2WEbDW0R7I/AAAAAAAACbE/DymXsZOmO3s/s36/18.gif",
  emo20 : "https://lh4.googleusercontent.com/-IvNFZtzJJYI/T2WEcDj-0NI/AAAAAAAACbM/kiqtHbdkarQ/s36/19.gif",
  emo21 : "https://lh5.googleusercontent.com/-XCXdaCYaOGE/T2WEcmd15EI/AAAAAAAACbQ/Z5UyZCuX4Xo/s36/20.gif",
  emo22 : "https://lh4.googleusercontent.com/-g6V0tBD1vwk/T2WEdRGJfWI/AAAAAAAACbo/P8P_SGEdhzI/s36/21.gif",
  emo23 : "https://lh6.googleusercontent.com/-ErUGB8ea0H4/T2WEdm5-ZSI/AAAAAAAACbs/245Hxnaa82g/s35/22.gif",
  emo24 : "https://lh6.googleusercontent.com/-p-5AT-amLik/T2WEi_MJDqI/AAAAAAAACco/5J-MqivSQw4/s36/23.gif",
  emo25 : "https://lh3.googleusercontent.com/-H8izCFTaHFE/T2b39mmu2NI/AAAAAAAACkM/k4bDdFe301U/s36/24.gif",
  emo26 : "https://lh5.googleusercontent.com/-LZn6dX8GslQ/T2W30lpp_kI/AAAAAAAAChA/Rym2Ql5H-jU/s36/25.gif",
  emo27 : "https://lh5.googleusercontent.com/-k6r8YBUhxVk/T2WEgBtjFtI/AAAAAAAACcE/U5U5uPCpxq8/s36/26.gif", 
  emo28 : "https://lh5.googleusercontent.com/-pj6fMvZXTyc/T2WEga9-gjI/AAAAAAAACcM/kVpUCa7uqpw/s36/27.gif",
  emo29 : "https://lh3.googleusercontent.com/-zI2UJmwerDM/T2WEhSRkuTI/AAAAAAAACcc/Gr3xFDrZF3Y/s36/28.gif",
  emo30 : "https://lh3.googleusercontent.com/-ilBYLLWFQJQ/T2WEiJXJ7LI/AAAAAAAACcY/bXpkIPuVUto/s36/29.gif",
  emo31 : "https://lh5.googleusercontent.com/-_NHYkuf5bZg/T2WEjOhTIxI/AAAAAAAACcg/76qRE27R_ig/s36/30.gif",
  emo32 : "https://lh6.googleusercontent.com/-O6m44_Z-8AA/T2WEjLRImnI/AAAAAAAACck/c_jh643HU6o/s36/31.gif",
  emo33 : "https://lh5.googleusercontent.com/-9TYEg93ImUM/T2WEjvuhxTI/AAAAAAAACc0/KQRBXuuV_Yg/s36/32.gif"
}

WebFontConfig={custom:{families:["FontAwesome"],urls:["https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"]},google:{families:["Roboto:400,700,300:latin","Open+Sans:400,600,700:latin"]}},function(){var t=document.createElement("script");t.src=("https:"==document.location.protocol?"https":"http")+"://ajax.googleapis.com/ajax/libs/webfont/1.6.16/webfont.js",t.type="text/javascript",t.async="true";var e=document.getElementsByTagName("script")[0];e.parentNode.insertBefore(t,e)}();

/*! jQuery v1.11.3 | (c) 2005, 2015 jQuery Foundation, Inc. | jquery.org/license */
!function(a,b){"object"==typeof module&&"object"==typeof module.exports?module.exports=a.document?b(a,!0):function(a){if(!a.document)throw new Error("jQuery requires a window with a document");return b(a)}:b(a)}("undefined"!=typeof window?window:this,function(a,b){var c=[],d=c.slice,e=c.concat,f=c.push,g=c.indexOf,h={},i=h.toString,j=h.hasOwnProperty,k={},l="1.11.3",m=function(a,b){return new m.fn.init(a,b)},n=/^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g,o=/^-ms-/,p=/-([\da-z])/gi,q=function(a,b){return b.toUpperCase()};m.fn=m.prototype={jquery:l,constructor:m,selector:"",length:0,toArray:function(){return d.call(this)},get:function(a){return null!=a?0>a?this[a+this.length]:this[a]:d.call(this)},pushStack:function(a){var b=m.merge(this.constructor(),a);return b.prevObject=this,b.context=this.context,b},each:function(a,b){return m.each(this,a,b)},map:function(a){return this.pushStack(m.map(this,function(b,c){return a.call(b,c,b)}))},slice:function(){return this.pushStack(d.apply(this,arguments))},first:function(){return this.eq(0)},last:function(){return this.eq(-1)},eq:function(a){var b=this.length,c=+a+(0>a?b:0);return this.pushStack(c>=0&&b>c?[this[c]]:[])},end:function(){return this.prevObject||this.constructor(null)},push:f,sort:c.sort,splice:c.splice},m.extend=m.fn.extend=function(){var a,b,c,d,e,f,g=arguments[0]||{},h=1,i=arguments.length,j=!1;for("boolean"==typeof g&&(j=g,g=arguments[h]||{},h++),"object"==typeof g||m.isFunction(g)||(g={}),h===i&&(g=this,h--);i>h;h++)if(null!=(e=arguments[h]))for(d in e)a=g[d],c=e[d],g!==c&&(j&&c&&(m.isPlainObject(c)||(b=m.isArray(c)))?(b?(b=!1,f=a&&m.isArray(a)?a:[]):f=a&&m.isPlainObject(a)?a:{},g[d]=m.extend(j,f,c)):void 0!==c&&(g[d]=c));return g},m.extend({expando:"jQuery"+(l+Math.random()).replace(/\D/g,""),isReady:!0,error:function(a){throw new Error(a)},noop:function(){},isFunction:function(a){return"function"===m.type(a)},isArray:Array.isArray||function(a){return"array"===m.type(a)},isWindow:function(a){return null!=a&&a==a.window},isNumeric:function(a){return!m.isArray(a)&&a-parseFloat(a)+1>=0},isEmptyObject:function(a){var b;for(b in a)return!1;return!0},isPlainObject:function(a){var b;if(!a||"object"!==m.type(a)||a.nodeType||m.isWindow(a))return!1;try{if(a.constructor&&!j.call(a,"constructor")&&!j.call(a.constructor.prototype,"isPrototypeOf"))return!1}catch(c){return!1}if(k.ownLast)for(b in a)return j.call(a,b);for(b in a);return void 0===b||j.call(a,b)},type:function(a){return null==a?a+"":"object"==typeof a||"function"==typeof a?h[i.call(a)]||"object":typeof a},globalEval:function(b){b&&m.trim(b)&&(a.execScript||function(b){a.eval.call(a,b)})(b)},camelCase:function(a){return a.replace(o,"ms-").replace(p,q)},nodeName:function(a,b){return a.nodeName&&a.nodeName.toLowerCase()===b.toLowerCase()},each:function(a,b,c){var d,e=0,f=a.length,g=r(a);if(c){if(g){for(;f>e;e++)if(d=b.apply(a[e],c),d===!1)break}else for(e in a)if(d=b.apply(a[e],c),d===!1)break}else if(g){for(;f>e;e++)if(d=b.call(a[e],e,a[e]),d===!1)break}else for(e in a)if(d=b.call(a[e],e,a[e]),d===!1)break;return a},trim:function(a){return null==a?"":(a+"").replace(n,"")},makeArray:function(a,b){var c=b||[];return null!=a&&(r(Object(a))?m.merge(c,"string"==typeof a?[a]:a):f.call(c,a)),c},inArray:function(a,b,c){var d;if(b){if(g)return g.call(b,a,c);for(d=b.length,c=c?0>c?Math.max(0,d+c):c:0;d>c;c++)if(c in b&&b[c]===a)return c}return-1},merge:function(a,b){var c=+b.length,d=0,e=a.length;while(c>d)a[e++]=b[d++];if(c!==c)while(void 0!==b[d])a[e++]=b[d++];return a.length=e,a},grep:function(a,b,c){for(var d,e=[],f=0,g=a.length,h=!c;g>f;f++)d=!b(a[f],f),d!==h&&e.push(a[f]);return e},map:function(a,b,c){var d,f=0,g=a.length,h=r(a),i=[];if(h)for(;g>f;f++)d=b(a[f],f,c),null!=d&&i.push(d);else for(f in a)d=b(a[f],f,c),null!=d&&i.push(d);return e.apply([],i)},guid:1,proxy:function(a,b){var c,e,f;return"string"==typeof b&&(f=a[b],b=a,a=f),m.isFunction(a)?(c=d.call(arguments,2),e=function(){return a.apply(b||this,c.concat(d.call(arguments)))},e.guid=a.guid=a.guid||m.guid++,e):void 0},now:function(){return+new Date},support:k}),m.each("Boolean Number String Function Array Date RegExp Object Error".split(" "),function(a,b){h["[object "+b+"]"]=b.toLowerCase()});function r(a){var b="length"in a&&a.length,c=m.type(a);return"function"===c||m.isWindow(a)?!1:1===a.nodeType&&b?!0:"array"===c||0===b||"number"==typeof b&&b>0&&b-1 in a}var s=function(a){var b,c,d,e,f,g,h,i,j,k,l,m,n,o,p,q,r,s,t,u="sizzle"+1*new Date,v=a.document,w=0,x=0,y=ha(),z=ha(),A=ha(),B=function(a,b){return a===b&&(l=!0),0},C=1<<31,D={}.hasOwnProperty,E=[],F=E.pop,G=E.push,H=E.push,I=E.slice,J=function(a,b){for(var c=0,d=a.length;d>c;c++)if(a[c]===b)return c;return-1},K="checked|selected|async|autofocus|autoplay|controls|defer|disabled|hidden|ismap|loop|multiple|open|readonly|required|scoped",L="[\\x20\\t\\r\\n\\f]",M="(?:\\\\.|[\\w-]|[^\\x00-\\xa0])+",N=M.replace("w","w#"),O="\\["+L+"*("+M+")(?:"+L+"*([*^$|!~]?=)"+L+"*(?:'((?:\\\\.|[^\\\\'])*)'|\"((?:\\\\.|[^\\\\\"])*)\"|("+N+"))|)"+L+"*\\]",P=":("+M+")(?:\\((('((?:\\\\.|[^\\\\'])*)'|\"((?:\\\\.|[^\\\\\"])*)\")|((?:\\\\.|[^\\\\()[\\]]|"+O+")*)|.*)\\)|)",Q=new RegExp(L+"+","g"),R=new RegExp("^"+L+"+|((?:^|[^\\\\])(?:\\\\.)*)"+L+"+$","g"),S=new RegExp("^"+L+"*,"+L+"*"),T=new RegExp("^"+L+"*([>+~]|"+L+")"+L+"*"),U=new RegExp("="+L+"*([^\\]'\"]*?)"+L+"*\\]","g"),V=new RegExp(P),W=new RegExp("^"+N+"$"),X={ID:new RegExp("^#("+M+")"),CLASS:new RegExp("^\\.("+M+")"),TAG:new RegExp("^("+M.replace("w","w*")+")"),ATTR:new RegExp("^"+O),PSEUDO:new RegExp("^"+P),CHILD:new RegExp("^:(only|first|last|nth|nth-last)-(child|of-type)(?:\\("+L+"*(even|odd|(([+-]|)(\\d*)n|)"+L+"*(?:([+-]|)"+L+"*(\\d+)|))"+L+"*\\)|)","i"),bool:new RegExp("^(?:"+K+")$","i"),needsContext:new RegExp("^"+L+"*[>+~]|:(even|odd|eq|gt|lt|nth|first|last)(?:\\("+L+"*((?:-\\d)?\\d*)"+L+"*\\)|)(?=[^-]|$)","i")},Y=/^(?:input|select|textarea|button)$/i,Z=/^h\d$/i,$=/^[^{]+\{\s*\[native \w/,_=/^(?:#([\w-]+)|(\w+)|\.([\w-]+))$/,aa=/[+~]/,ba=/'|\\/g,ca=new RegExp("\\\\([\\da-f]{1,6}"+L+"?|("+L+")|.)","ig"),da=function(a,b,c){var d="0x"+b-65536;return d!==d||c?b:0>d?String.fromCharCode(d+65536):String.fromCharCode(d>>10|55296,1023&d|56320)},ea=function(){m()};try{H.apply(E=I.call(v.childNodes),v.childNodes),E[v.childNodes.length].nodeType}catch(fa){H={apply:E.length?function(a,b){G.apply(a,I.call(b))}:function(a,b){var c=a.length,d=0;while(a[c++]=b[d++]);a.length=c-1}}}function ga(a,b,d,e){var f,h,j,k,l,o,r,s,w,x;if((b?b.ownerDocument||b:v)!==n&&m(b),b=b||n,d=d||[],k=b.nodeType,"string"!=typeof a||!a||1!==k&&9!==k&&11!==k)return d;if(!e&&p){if(11!==k&&(f=_.exec(a)))if(j=f[1]){if(9===k){if(h=b.getElementById(j),!h||!h.parentNode)return d;if(h.id===j)return d.push(h),d}else if(b.ownerDocument&&(h=b.ownerDocument.getElementById(j))&&t(b,h)&&h.id===j)return d.push(h),d}else{if(f[2])return H.apply(d,b.getElementsByTagName(a)),d;if((j=f[3])&&c.getElementsByClassName)return H.apply(d,b.getElementsByClassName(j)),d}if(c.qsa&&(!q||!q.test(a))){if(s=r=u,w=b,x=1!==k&&a,1===k&&"object"!==b.nodeName.toLowerCase()){o=g(a),(r=b.getAttribute("id"))?s=r.replace(ba,"\\$&"):b.setAttribute("id",s),s="[id='"+s+"'] ",l=o.length;while(l--)o[l]=s+ra(o[l]);w=aa.test(a)&&pa(b.parentNode)||b,x=o.join(",")}if(x)try{return H.apply(d,w.querySelectorAll(x)),d}catch(y){}finally{r||b.removeAttribute("id")}}}return i(a.replace(R,"$1"),b,d,e)}function ha(){var a=[];function b(c,e){return a.push(c+" ")>d.cacheLength&&delete b[a.shift()],b[c+" "]=e}return b}function ia(a){return a[u]=!0,a}function ja(a){var b=n.createElement("div");try{return!!a(b)}catch(c){return!1}finally{b.parentNode&&b.parentNode.removeChild(b),b=null}}function ka(a,b){var c=a.split("|"),e=a.length;while(e--)d.attrHandle[c[e]]=b}function la(a,b){var c=b&&a,d=c&&1===a.nodeType&&1===b.nodeType&&(~b.sourceIndex||C)-(~a.sourceIndex||C);if(d)return d;if(c)while(c=c.nextSibling)if(c===b)return-1;return a?1:-1}function ma(a){return function(b){var c=b.nodeName.toLowerCase();return"input"===c&&b.type===a}}function na(a){return function(b){var c=b.nodeName.toLowerCase();return("input"===c||"button"===c)&&b.type===a}}function oa(a){return ia(function(b){return b=+b,ia(function(c,d){var e,f=a([],c.length,b),g=f.length;while(g--)c[e=f[g]]&&(c[e]=!(d[e]=c[e]))})})}function pa(a){return a&&"undefined"!=typeof a.getElementsByTagName&&a}c=ga.support={},f=ga.isXML=function(a){var b=a&&(a.ownerDocument||a).documentElement;return b?"HTML"!==b.nodeName:!1},m=ga.setDocument=function(a){var b,e,g=a?a.ownerDocument||a:v;return g!==n&&9===g.nodeType&&g.documentElement?(n=g,o=g.documentElement,e=g.defaultView,e&&e!==e.top&&(e.addEventListener?e.addEventListener("unload",ea,!1):e.attachEvent&&e.attachEvent("onunload",ea)),p=!f(g),c.attributes=ja(function(a){return a.className="i",!a.getAttribute("className")}),c.getElementsByTagName=ja(function(a){return a.appendChild(g.createComment("")),!a.getElementsByTagName("*").length}),c.getElementsByClassName=$.test(g.getElementsByClassName),c.getById=ja(function(a){return o.appendChild(a).id=u,!g.getElementsByName||!g.getElementsByName(u).length}),c.getById?(d.find.ID=function(a,b){if("undefined"!=typeof b.getElementById&&p){var c=b.getElementById(a);return c&&c.parentNode?[c]:[]}},d.filter.ID=function(a){var b=a.replace(ca,da);return function(a){return a.getAttribute("id")===b}}):(delete d.find.ID,d.filter.ID=function(a){var b=a.replace(ca,da);return function(a){var c="undefined"!=typeof a.getAttributeNode&&a.getAttributeNode("id");return c&&c.value===b}}),d.find.TAG=c.getElementsByTagName?function(a,b){return"undefined"!=typeof b.getElementsByTagName?b.getElementsByTagName(a):c.qsa?b.querySelectorAll(a):void 0}:function(a,b){var c,d=[],e=0,f=b.getElementsByTagName(a);if("*"===a){while(c=f[e++])1===c.nodeType&&d.push(c);return d}return f},d.find.CLASS=c.getElementsByClassName&&function(a,b){return p?b.getElementsByClassName(a):void 0},r=[],q=[],(c.qsa=$.test(g.querySelectorAll))&&(ja(function(a){o.appendChild(a).innerHTML="<a id='"+u+"'></a><select id='"+u+"-\f]' msallowcapture=''><option selected=''></option></select>",a.querySelectorAll("[msallowcapture^='']").length&&q.push("[*^$]="+L+"*(?:''|\"\")"),a.querySelectorAll("[selected]").length||q.push("\\["+L+"*(?:value|"+K+")"),a.querySelectorAll("[id~="+u+"-]").length||q.push("~="),a.querySelectorAll(":checked").length||q.push(":checked"),a.querySelectorAll("a#"+u+"+*").length||q.push(".#.+[+~]")}),ja(function(a){var b=g.createElement("input");b.setAttribute("type","hidden"),a.appendChild(b).setAttribute("name","D"),a.querySelectorAll("[name=d]").length&&q.push("name"+L+"*[*^$|!~]?="),a.querySelectorAll(":enabled").length||q.push(":enabled",":disabled"),a.querySelectorAll("*,:x"),q.push(",.*:")})),(c.matchesSelector=$.test(s=o.matches||o.webkitMatchesSelector||o.mozMatchesSelector||o.oMatchesSelector||o.msMatchesSelector))&&ja(function(a){c.disconnectedMatch=s.call(a,"div"),s.call(a,"[s!='']:x"),r.push("!=",P)}),q=q.length&&new RegExp(q.join("|")),r=r.length&&new RegExp(r.join("|")),b=$.test(o.compareDocumentPosition),t=b||$.test(o.contains)?function(a,b){var c=9===a.nodeType?a.documentElement:a,d=b&&b.parentNode;return a===d||!(!d||1!==d.nodeType||!(c.contains?c.contains(d):a.compareDocumentPosition&&16&a.compareDocumentPosition(d)))}:function(a,b){if(b)while(b=b.parentNode)if(b===a)return!0;return!1},B=b?function(a,b){if(a===b)return l=!0,0;var d=!a.compareDocumentPosition-!b.compareDocumentPosition;return d?d:(d=(a.ownerDocument||a)===(b.ownerDocument||b)?a.compareDocumentPosition(b):1,1&d||!c.sortDetached&&b.compareDocumentPosition(a)===d?a===g||a.ownerDocument===v&&t(v,a)?-1:b===g||b.ownerDocument===v&&t(v,b)?1:k?J(k,a)-J(k,b):0:4&d?-1:1)}:function(a,b){if(a===b)return l=!0,0;var c,d=0,e=a.parentNode,f=b.parentNode,h=[a],i=[b];if(!e||!f)return a===g?-1:b===g?1:e?-1:f?1:k?J(k,a)-J(k,b):0;if(e===f)return la(a,b);c=a;while(c=c.parentNode)h.unshift(c);c=b;while(c=c.parentNode)i.unshift(c);while(h[d]===i[d])d++;return d?la(h[d],i[d]):h[d]===v?-1:i[d]===v?1:0},g):n},ga.matches=function(a,b){return ga(a,null,null,b)},ga.matchesSelector=function(a,b){if((a.ownerDocument||a)!==n&&m(a),b=b.replace(U,"='$1']"),!(!c.matchesSelector||!p||r&&r.test(b)||q&&q.test(b)))try{var d=s.call(a,b);if(d||c.disconnectedMatch||a.document&&11!==a.document.nodeType)return d}catch(e){}return ga(b,n,null,[a]).length>0},ga.contains=function(a,b){return(a.ownerDocument||a)!==n&&m(a),t(a,b)},ga.attr=function(a,b){(a.ownerDocument||a)!==n&&m(a);var e=d.attrHandle[b.toLowerCase()],f=e&&D.call(d.attrHandle,b.toLowerCase())?e(a,b,!p):void 0;return void 0!==f?f:c.attributes||!p?a.getAttribute(b):(f=a.getAttributeNode(b))&&f.specified?f.value:null},ga.error=function(a){throw new Error("Syntax error, unrecognized expression: "+a)},ga.uniqueSort=function(a){var b,d=[],e=0,f=0;if(l=!c.detectDuplicates,k=!c.sortStable&&a.slice(0),a.sort(B),l){while(b=a[f++])b===a[f]&&(e=d.push(f));while(e--)a.splice(d[e],1)}return k=null,a},e=ga.getText=function(a){var b,c="",d=0,f=a.nodeType;if(f){if(1===f||9===f||11===f){if("string"==typeof a.textContent)return a.textContent;for(a=a.firstChild;a;a=a.nextSibling)c+=e(a)}else if(3===f||4===f)return a.nodeValue}else while(b=a[d++])c+=e(b);return c},d=ga.selectors={cacheLength:50,createPseudo:ia,match:X,attrHandle:{},find:{},relative:{">":{dir:"parentNode",first:!0}," ":{dir:"parentNode"},"+":{dir:"previousSibling",first:!0},"~":{dir:"previousSibling"}},preFilter:{ATTR:function(a){return a[1]=a[1].replace(ca,da),a[3]=(a[3]||a[4]||a[5]||"").replace(ca,da),"~="===a[2]&&(a[3]=" "+a[3]+" "),a.slice(0,4)},CHILD:function(a){return a[1]=a[1].toLowerCase(),"nth"===a[1].slice(0,3)?(a[3]||ga.error(a[0]),a[4]=+(a[4]?a[5]+(a[6]||1):2*("even"===a[3]||"odd"===a[3])),a[5]=+(a[7]+a[8]||"odd"===a[3])):a[3]&&ga.error(a[0]),a},PSEUDO:function(a){var b,c=!a[6]&&a[2];return X.CHILD.test(a[0])?null:(a[3]?a[2]=a[4]||a[5]||"":c&&V.test(c)&&(b=g(c,!0))&&(b=c.indexOf(")",c.length-b)-c.length)&&(a[0]=a[0].slice(0,b),a[2]=c.slice(0,b)),a.slice(0,3))}},filter:{TAG:function(a){var b=a.replace(ca,da).toLowerCase();return"*"===a?function(){return!0}:function(a){return a.nodeName&&a.nodeName.toLowerCase()===b}},CLASS:function(a){var b=y[a+" "];return b||(b=new RegExp("(^|"+L+")"+a+"("+L+"|$)"))&&y(a,function(a){return b.test("string"==typeof a.className&&a.className||"undefined"!=typeof a.getAttribute&&a.getAttribute("class")||"")})},ATTR:function(a,b,c){return function(d){var e=ga.attr(d,a);return null==e?"!="===b:b?(e+="","="===b?e===c:"!="===b?e!==c:"^="===b?c&&0===e.indexOf(c):"*="===b?c&&e.indexOf(c)>-1:"$="===b?c&&e.slice(-c.length)===c:"~="===b?(" "+e.replace(Q," ")+" ").indexOf(c)>-1:"|="===b?e===c||e.slice(0,c.length+1)===c+"-":!1):!0}},CHILD:function(a,b,c,d,e){var f="nth"!==a.slice(0,3),g="last"!==a.slice(-4),h="of-type"===b;return 1===d&&0===e?function(a){return!!a.parentNode}:function(b,c,i){var j,k,l,m,n,o,p=f!==g?"nextSibling":"previousSibling",q=b.parentNode,r=h&&b.nodeName.toLowerCase(),s=!i&&!h;if(q){if(f){while(p){l=b;while(l=l[p])if(h?l.nodeName.toLowerCase()===r:1===l.nodeType)return!1;o=p="only"===a&&!o&&"nextSibling"}return!0}if(o=[g?q.firstChild:q.lastChild],g&&s){k=q[u]||(q[u]={}),j=k[a]||[],n=j[0]===w&&j[1],m=j[0]===w&&j[2],l=n&&q.childNodes[n];while(l=++n&&l&&l[p]||(m=n=0)||o.pop())if(1===l.nodeType&&++m&&l===b){k[a]=[w,n,m];break}}else if(s&&(j=(b[u]||(b[u]={}))[a])&&j[0]===w)m=j[1];else while(l=++n&&l&&l[p]||(m=n=0)||o.pop())if((h?l.nodeName.toLowerCase()===r:1===l.nodeType)&&++m&&(s&&((l[u]||(l[u]={}))[a]=[w,m]),l===b))break;return m-=e,m===d||m%d===0&&m/d>=0}}},PSEUDO:function(a,b){var c,e=d.pseudos[a]||d.setFilters[a.toLowerCase()]||ga.error("unsupported pseudo: "+a);return e[u]?e(b):e.length>1?(c=[a,a,"",b],d.setFilters.hasOwnProperty(a.toLowerCase())?ia(function(a,c){var d,f=e(a,b),g=f.length;while(g--)d=J(a,f[g]),a[d]=!(c[d]=f[g])}):function(a){return e(a,0,c)}):e}},pseudos:{not:ia(function(a){var b=[],c=[],d=h(a.replace(R,"$1"));return d[u]?ia(function(a,b,c,e){var f,g=d(a,null,e,[]),h=a.length;while(h--)(f=g[h])&&(a[h]=!(b[h]=f))}):function(a,e,f){return b[0]=a,d(b,null,f,c),b[0]=null,!c.pop()}}),has:ia(function(a){return function(b){return ga(a,b).length>0}}),contains:ia(function(a){return a=a.replace(ca,da),function(b){return(b.textContent||b.innerText||e(b)).indexOf(a)>-1}}),lang:ia(function(a){return W.test(a||"")||ga.error("unsupported lang: "+a),a=a.replace(ca,da).toLowerCase(),function(b){var c;do if(c=p?b.lang:b.getAttribute("xml:lang")||b.getAttribute("lang"))return c=c.toLowerCase(),c===a||0===c.indexOf(a+"-");while((b=b.parentNode)&&1===b.nodeType);return!1}}),target:function(b){var c=a.location&&a.location.hash;return c&&c.slice(1)===b.id},root:function(a){return a===o},focus:function(a){return a===n.activeElement&&(!n.hasFocus||n.hasFocus())&&!!(a.type||a.href||~a.tabIndex)},enabled:function(a){return a.disabled===!1},disabled:function(a){return a.disabled===!0},checked:function(a){var b=a.nodeName.toLowerCase();return"input"===b&&!!a.checked||"option"===b&&!!a.selected},selected:function(a){return a.parentNode&&a.parentNode.selectedIndex,a.selected===!0},empty:function(a){for(a=a.firstChild;a;a=a.nextSibling)if(a.nodeType<6)return!1;return!0},parent:function(a){return!d.pseudos.empty(a)},header:function(a){return Z.test(a.nodeName)},input:function(a){return Y.test(a.nodeName)},button:function(a){var b=a.nodeName.toLowerCase();return"input"===b&&"button"===a.type||"button"===b},text:function(a){var b;return"input"===a.nodeName.toLowerCase()&&"text"===a.type&&(null==(b=a.getAttribute("type"))||"text"===b.toLowerCase())},first:oa(function(){return[0]}),last:oa(function(a,b){return[b-1]}),eq:oa(function(a,b,c){return[0>c?c+b:c]}),even:oa(function(a,b){for(var c=0;b>c;c+=2)a.push(c);return a}),odd:oa(function(a,b){for(var c=1;b>c;c+=2)a.push(c);return a}),lt:oa(function(a,b,c){for(var d=0>c?c+b:c;--d>=0;)a.push(d);return a}),gt:oa(function(a,b,c){for(var d=0>c?c+b:c;++d<b;)a.push(d);return a})}},d.pseudos.nth=d.pseudos.eq;for(b in{radio:!0,checkbox:!0,file:!0,password:!0,image:!0})d.pseudos[b]=ma(b);for(b in{submit:!0,reset:!0})d.pseudos[b]=na(b);function qa(){}qa.prototype=d.filters=d.pseudos,d.setFilters=new qa,g=ga.tokenize=function(a,b){var c,e,f,g,h,i,j,k=z[a+" "];if(k)return b?0:k.slice(0);h=a,i=[],j=d.preFilter;while(h){(!c||(e=S.exec(h)))&&(e&&(h=h.slice(e[0].length)||h),i.push(f=[])),c=!1,(e=T.exec(h))&&(c=e.shift(),f.push({value:c,type:e[0].replace(R," ")}),h=h.slice(c.length));for(g in d.filter)!(e=X[g].exec(h))||j[g]&&!(e=j[g](e))||(c=e.shift(),f.push({value:c,type:g,matches:e}),h=h.slice(c.length));if(!c)break}return b?h.length:h?ga.error(a):z(a,i).slice(0)};function ra(a){for(var b=0,c=a.length,d="";c>b;b++)d+=a[b].value;return d}function sa(a,b,c){var d=b.dir,e=c&&"parentNode"===d,f=x++;return b.first?function(b,c,f){while(b=b[d])if(1===b.nodeType||e)return a(b,c,f)}:function(b,c,g){var h,i,j=[w,f];if(g){while(b=b[d])if((1===b.nodeType||e)&&a(b,c,g))return!0}else while(b=b[d])if(1===b.nodeType||e){if(i=b[u]||(b[u]={}),(h=i[d])&&h[0]===w&&h[1]===f)return j[2]=h[2];if(i[d]=j,j[2]=a(b,c,g))return!0}}}function ta(a){return a.length>1?function(b,c,d){var e=a.length;while(e--)if(!a[e](b,c,d))return!1;return!0}:a[0]}function ua(a,b,c){for(var d=0,e=b.length;e>d;d++)ga(a,b[d],c);return c}function va(a,b,c,d,e){for(var f,g=[],h=0,i=a.length,j=null!=b;i>h;h++)(f=a[h])&&(!c||c(f,d,e))&&(g.push(f),j&&b.push(h));return g}function wa(a,b,c,d,e,f){return d&&!d[u]&&(d=wa(d)),e&&!e[u]&&(e=wa(e,f)),ia(function(f,g,h,i){var j,k,l,m=[],n=[],o=g.length,p=f||ua(b||"*",h.nodeType?[h]:h,[]),q=!a||!f&&b?p:va(p,m,a,h,i),r=c?e||(f?a:o||d)?[]:g:q;if(c&&c(q,r,h,i),d){j=va(r,n),d(j,[],h,i),k=j.length;while(k--)(l=j[k])&&(r[n[k]]=!(q[n[k]]=l))}if(f){if(e||a){if(e){j=[],k=r.length;while(k--)(l=r[k])&&j.push(q[k]=l);e(null,r=[],j,i)}k=r.length;while(k--)(l=r[k])&&(j=e?J(f,l):m[k])>-1&&(f[j]=!(g[j]=l))}}else r=va(r===g?r.splice(o,r.length):r),e?e(null,g,r,i):H.apply(g,r)})}function xa(a){for(var b,c,e,f=a.length,g=d.relative[a[0].type],h=g||d.relative[" "],i=g?1:0,k=sa(function(a){return a===b},h,!0),l=sa(function(a){return J(b,a)>-1},h,!0),m=[function(a,c,d){var e=!g&&(d||c!==j)||((b=c).nodeType?k(a,c,d):l(a,c,d));return b=null,e}];f>i;i++)if(c=d.relative[a[i].type])m=[sa(ta(m),c)];else{if(c=d.filter[a[i].type].apply(null,a[i].matches),c[u]){for(e=++i;f>e;e++)if(d.relative[a[e].type])break;return wa(i>1&&ta(m),i>1&&ra(a.slice(0,i-1).concat({value:" "===a[i-2].type?"*":""})).replace(R,"$1"),c,e>i&&xa(a.slice(i,e)),f>e&&xa(a=a.slice(e)),f>e&&ra(a))}m.push(c)}return ta(m)}function ya(a,b){var c=b.length>0,e=a.length>0,f=function(f,g,h,i,k){var l,m,o,p=0,q="0",r=f&&[],s=[],t=j,u=f||e&&d.find.TAG("*",k),v=w+=null==t?1:Math.random()||.1,x=u.length;for(k&&(j=g!==n&&g);q!==x&&null!=(l=u[q]);q++){if(e&&l){m=0;while(o=a[m++])if(o(l,g,h)){i.push(l);break}k&&(w=v)}c&&((l=!o&&l)&&p--,f&&r.push(l))}if(p+=q,c&&q!==p){m=0;while(o=b[m++])o(r,s,g,h);if(f){if(p>0)while(q--)r[q]||s[q]||(s[q]=F.call(i));s=va(s)}H.apply(i,s),k&&!f&&s.length>0&&p+b.length>1&&ga.uniqueSort(i)}return k&&(w=v,j=t),r};return c?ia(f):f}return h=ga.compile=function(a,b){var c,d=[],e=[],f=A[a+" "];if(!f){b||(b=g(a)),c=b.length;while(c--)f=xa(b[c]),f[u]?d.push(f):e.push(f);f=A(a,ya(e,d)),f.selector=a}return f},i=ga.select=function(a,b,e,f){var i,j,k,l,m,n="function"==typeof a&&a,o=!f&&g(a=n.selector||a);if(e=e||[],1===o.length){if(j=o[0]=o[0].slice(0),j.length>2&&"ID"===(k=j[0]).type&&c.getById&&9===b.nodeType&&p&&d.relative[j[1].type]){if(b=(d.find.ID(k.matches[0].replace(ca,da),b)||[])[0],!b)return e;n&&(b=b.parentNode),a=a.slice(j.shift().value.length)}i=X.needsContext.test(a)?0:j.length;while(i--){if(k=j[i],d.relative[l=k.type])break;if((m=d.find[l])&&(f=m(k.matches[0].replace(ca,da),aa.test(j[0].type)&&pa(b.parentNode)||b))){if(j.splice(i,1),a=f.length&&ra(j),!a)return H.apply(e,f),e;break}}}return(n||h(a,o))(f,b,!p,e,aa.test(a)&&pa(b.parentNode)||b),e},c.sortStable=u.split("").sort(B).join("")===u,c.detectDuplicates=!!l,m(),c.sortDetached=ja(function(a){return 1&a.compareDocumentPosition(n.createElement("div"))}),ja(function(a){return a.innerHTML="<a href='#'></a>","#"===a.firstChild.getAttribute("href")})||ka("type|href|height|width",function(a,b,c){return c?void 0:a.getAttribute(b,"type"===b.toLowerCase()?1:2)}),c.attributes&&ja(function(a){return a.innerHTML="<input/>",a.firstChild.setAttribute("value",""),""===a.firstChild.getAttribute("value")})||ka("value",function(a,b,c){return c||"input"!==a.nodeName.toLowerCase()?void 0:a.defaultValue}),ja(function(a){return null==a.getAttribute("disabled")})||ka(K,function(a,b,c){var d;return c?void 0:a[b]===!0?b.toLowerCase():(d=a.getAttributeNode(b))&&d.specified?d.value:null}),ga}(a);m.find=s,m.expr=s.selectors,m.expr[":"]=m.expr.pseudos,m.unique=s.uniqueSort,m.text=s.getText,m.isXMLDoc=s.isXML,m.contains=s.contains;var t=m.expr.match.needsContext,u=/^<(\w+)\s*\/?>(?:<\/\1>|)$/,v=/^.[^:#\[\.,]*$/;function w(a,b,c){if(m.isFunction(b))return m.grep(a,function(a,d){return!!b.call(a,d,a)!==c});if(b.nodeType)return m.grep(a,function(a){return a===b!==c});if("string"==typeof b){if(v.test(b))return m.filter(b,a,c);b=m.filter(b,a)}return m.grep(a,function(a){return m.inArray(a,b)>=0!==c})}m.filter=function(a,b,c){var d=b[0];return c&&(a=":not("+a+")"),1===b.length&&1===d.nodeType?m.find.matchesSelector(d,a)?[d]:[]:m.find.matches(a,m.grep(b,function(a){return 1===a.nodeType}))},m.fn.extend({find:function(a){var b,c=[],d=this,e=d.length;if("string"!=typeof a)return this.pushStack(m(a).filter(function(){for(b=0;e>b;b++)if(m.contains(d[b],this))return!0}));for(b=0;e>b;b++)m.find(a,d[b],c);return c=this.pushStack(e>1?m.unique(c):c),c.selector=this.selector?this.selector+" "+a:a,c},filter:function(a){return this.pushStack(w(this,a||[],!1))},not:function(a){return this.pushStack(w(this,a||[],!0))},is:function(a){return!!w(this,"string"==typeof a&&t.test(a)?m(a):a||[],!1).length}});var x,y=a.document,z=/^(?:\s*(<[\w\W]+>)[^>]*|#([\w-]*))$/,A=m.fn.init=function(a,b){var c,d;if(!a)return this;if("string"==typeof a){if(c="<"===a.charAt(0)&&">"===a.charAt(a.length-1)&&a.length>=3?[null,a,null]:z.exec(a),!c||!c[1]&&b)return!b||b.jquery?(b||x).find(a):this.constructor(b).find(a);if(c[1]){if(b=b instanceof m?b[0]:b,m.merge(this,m.parseHTML(c[1],b&&b.nodeType?b.ownerDocument||b:y,!0)),u.test(c[1])&&m.isPlainObject(b))for(c in b)m.isFunction(this[c])?this[c](b[c]):this.attr(c,b[c]);return this}if(d=y.getElementById(c[2]),d&&d.parentNode){if(d.id!==c[2])return x.find(a);this.length=1,this[0]=d}return this.context=y,this.selector=a,this}return a.nodeType?(this.context=this[0]=a,this.length=1,this):m.isFunction(a)?"undefined"!=typeof x.ready?x.ready(a):a(m):(void 0!==a.selector&&(this.selector=a.selector,this.context=a.context),m.makeArray(a,this))};A.prototype=m.fn,x=m(y);var B=/^(?:parents|prev(?:Until|All))/,C={children:!0,contents:!0,next:!0,prev:!0};m.extend({dir:function(a,b,c){var d=[],e=a[b];while(e&&9!==e.nodeType&&(void 0===c||1!==e.nodeType||!m(e).is(c)))1===e.nodeType&&d.push(e),e=e[b];return d},sibling:function(a,b){for(var c=[];a;a=a.nextSibling)1===a.nodeType&&a!==b&&c.push(a);return c}}),m.fn.extend({has:function(a){var b,c=m(a,this),d=c.length;return this.filter(function(){for(b=0;d>b;b++)if(m.contains(this,c[b]))return!0})},closest:function(a,b){for(var c,d=0,e=this.length,f=[],g=t.test(a)||"string"!=typeof a?m(a,b||this.context):0;e>d;d++)for(c=this[d];c&&c!==b;c=c.parentNode)if(c.nodeType<11&&(g?g.index(c)>-1:1===c.nodeType&&m.find.matchesSelector(c,a))){f.push(c);break}return this.pushStack(f.length>1?m.unique(f):f)},index:function(a){return a?"string"==typeof a?m.inArray(this[0],m(a)):m.inArray(a.jquery?a[0]:a,this):this[0]&&this[0].parentNode?this.first().prevAll().length:-1},add:function(a,b){return this.pushStack(m.unique(m.merge(this.get(),m(a,b))))},addBack:function(a){return this.add(null==a?this.prevObject:this.prevObject.filter(a))}});function D(a,b){do a=a[b];while(a&&1!==a.nodeType);return a}m.each({parent:function(a){var b=a.parentNode;return b&&11!==b.nodeType?b:null},parents:function(a){return m.dir(a,"parentNode")},parentsUntil:function(a,b,c){return m.dir(a,"parentNode",c)},next:function(a){return D(a,"nextSibling")},prev:function(a){return D(a,"previousSibling")},nextAll:function(a){return m.dir(a,"nextSibling")},prevAll:function(a){return m.dir(a,"previousSibling")},nextUntil:function(a,b,c){return m.dir(a,"nextSibling",c)},prevUntil:function(a,b,c){return m.dir(a,"previousSibling",c)},siblings:function(a){return m.sibling((a.parentNode||{}).firstChild,a)},children:function(a){return m.sibling(a.firstChild)},contents:function(a){return m.nodeName(a,"iframe")?a.contentDocument||a.contentWindow.document:m.merge([],a.childNodes)}},function(a,b){m.fn[a]=function(c,d){var e=m.map(this,b,c);return"Until"!==a.slice(-5)&&(d=c),d&&"string"==typeof d&&(e=m.filter(d,e)),this.length>1&&(C[a]||(e=m.unique(e)),B.test(a)&&(e=e.reverse())),this.pushStack(e)}});var E=/\S+/g,F={};function G(a){var b=F[a]={};return m.each(a.match(E)||[],function(a,c){b[c]=!0}),b}m.Callbacks=function(a){a="string"==typeof a?F[a]||G(a):m.extend({},a);var b,c,d,e,f,g,h=[],i=!a.once&&[],j=function(l){for(c=a.memory&&l,d=!0,f=g||0,g=0,e=h.length,b=!0;h&&e>f;f++)if(h[f].apply(l[0],l[1])===!1&&a.stopOnFalse){c=!1;break}b=!1,h&&(i?i.length&&j(i.shift()):c?h=[]:k.disable())},k={add:function(){if(h){var d=h.length;!function f(b){m.each(b,function(b,c){var d=m.type(c);"function"===d?a.unique&&k.has(c)||h.push(c):c&&c.length&&"string"!==d&&f(c)})}(arguments),b?e=h.length:c&&(g=d,j(c))}return this},remove:function(){return h&&m.each(arguments,function(a,c){var d;while((d=m.inArray(c,h,d))>-1)h.splice(d,1),b&&(e>=d&&e--,f>=d&&f--)}),this},has:function(a){return a?m.inArray(a,h)>-1:!(!h||!h.length)},empty:function(){return h=[],e=0,this},disable:function(){return h=i=c=void 0,this},disabled:function(){return!h},lock:function(){return i=void 0,c||k.disable(),this},locked:function(){return!i},fireWith:function(a,c){return!h||d&&!i||(c=c||[],c=[a,c.slice?c.slice():c],b?i.push(c):j(c)),this},fire:function(){return k.fireWith(this,arguments),this},fired:function(){return!!d}};return k},m.extend({Deferred:function(a){var b=[["resolve","done",m.Callbacks("once memory"),"resolved"],["reject","fail",m.Callbacks("once memory"),"rejected"],["notify","progress",m.Callbacks("memory")]],c="pending",d={state:function(){return c},always:function(){return e.done(arguments).fail(arguments),this},then:function(){var a=arguments;return m.Deferred(function(c){m.each(b,function(b,f){var g=m.isFunction(a[b])&&a[b];e[f[1]](function(){var a=g&&g.apply(this,arguments);a&&m.isFunction(a.promise)?a.promise().done(c.resolve).fail(c.reject).progress(c.notify):c[f[0]+"With"](this===d?c.promise():this,g?[a]:arguments)})}),a=null}).promise()},promise:function(a){return null!=a?m.extend(a,d):d}},e={};return d.pipe=d.then,m.each(b,function(a,f){var g=f[2],h=f[3];d[f[1]]=g.add,h&&g.add(function(){c=h},b[1^a][2].disable,b[2][2].lock),e[f[0]]=function(){return e[f[0]+"With"](this===e?d:this,arguments),this},e[f[0]+"With"]=g.fireWith}),d.promise(e),a&&a.call(e,e),e},when:function(a){var b=0,c=d.call(arguments),e=c.length,f=1!==e||a&&m.isFunction(a.promise)?e:0,g=1===f?a:m.Deferred(),h=function(a,b,c){return function(e){b[a]=this,c[a]=arguments.length>1?d.call(arguments):e,c===i?g.notifyWith(b,c):--f||g.resolveWith(b,c)}},i,j,k;if(e>1)for(i=new Array(e),j=new Array(e),k=new Array(e);e>b;b++)c[b]&&m.isFunction(c[b].promise)?c[b].promise().done(h(b,k,c)).fail(g.reject).progress(h(b,j,i)):--f;return f||g.resolveWith(k,c),g.promise()}});var H;m.fn.ready=function(a){return m.ready.promise().done(a),this},m.extend({isReady:!1,readyWait:1,holdReady:function(a){a?m.readyWait++:m.ready(!0)},ready:function(a){if(a===!0?!--m.readyWait:!m.isReady){if(!y.body)return setTimeout(m.ready);m.isReady=!0,a!==!0&&--m.readyWait>0||(H.resolveWith(y,[m]),m.fn.triggerHandler&&(m(y).triggerHandler("ready"),m(y).off("ready")))}}});function I(){y.addEventListener?(y.removeEventListener("DOMContentLoaded",J,!1),a.removeEventListener("load",J,!1)):(y.detachEvent("onreadystatechange",J),a.detachEvent("onload",J))}function J(){(y.addEventListener||"load"===event.type||"complete"===y.readyState)&&(I(),m.ready())}m.ready.promise=function(b){if(!H)if(H=m.Deferred(),"complete"===y.readyState)setTimeout(m.ready);else if(y.addEventListener)y.addEventListener("DOMContentLoaded",J,!1),a.addEventListener("load",J,!1);else{y.attachEvent("onreadystatechange",J),a.attachEvent("onload",J);var c=!1;try{c=null==a.frameElement&&y.documentElement}catch(d){}c&&c.doScroll&&!function e(){if(!m.isReady){try{c.doScroll("left")}catch(a){return setTimeout(e,50)}I(),m.ready()}}()}return H.promise(b)};var K="undefined",L;for(L in m(k))break;k.ownLast="0"!==L,k.inlineBlockNeedsLayout=!1,m(function(){var a,b,c,d;c=y.getElementsByTagName("body")[0],c&&c.style&&(b=y.createElement("div"),d=y.createElement("div"),d.style.cssText="position:absolute;border:0;width:0;height:0;top:0;left:-9999px",c.appendChild(d).appendChild(b),typeof b.style.zoom!==K&&(b.style.cssText="display:inline;margin:0;border:0;padding:1px;width:1px;zoom:1",k.inlineBlockNeedsLayout=a=3===b.offsetWidth,a&&(c.style.zoom=1)),c.removeChild(d))}),function(){var a=y.createElement("div");if(null==k.deleteExpando){k.deleteExpando=!0;try{delete a.test}catch(b){k.deleteExpando=!1}}a=null}(),m.acceptData=function(a){var b=m.noData[(a.nodeName+" ").toLowerCase()],c=+a.nodeType||1;return 1!==c&&9!==c?!1:!b||b!==!0&&a.getAttribute("classid")===b};var M=/^(?:\{[\w\W]*\}|\[[\w\W]*\])$/,N=/([A-Z])/g;function O(a,b,c){if(void 0===c&&1===a.nodeType){var d="data-"+b.replace(N,"-$1").toLowerCase();if(c=a.getAttribute(d),"string"==typeof c){try{c="true"===c?!0:"false"===c?!1:"null"===c?null:+c+""===c?+c:M.test(c)?m.parseJSON(c):c}catch(e){}m.data(a,b,c)}else c=void 0}return c}function P(a){var b;for(b in a)if(("data"!==b||!m.isEmptyObject(a[b]))&&"toJSON"!==b)return!1;
return!0}function Q(a,b,d,e){if(m.acceptData(a)){var f,g,h=m.expando,i=a.nodeType,j=i?m.cache:a,k=i?a[h]:a[h]&&h;if(k&&j[k]&&(e||j[k].data)||void 0!==d||"string"!=typeof b)return k||(k=i?a[h]=c.pop()||m.guid++:h),j[k]||(j[k]=i?{}:{toJSON:m.noop}),("object"==typeof b||"function"==typeof b)&&(e?j[k]=m.extend(j[k],b):j[k].data=m.extend(j[k].data,b)),g=j[k],e||(g.data||(g.data={}),g=g.data),void 0!==d&&(g[m.camelCase(b)]=d),"string"==typeof b?(f=g[b],null==f&&(f=g[m.camelCase(b)])):f=g,f}}function R(a,b,c){if(m.acceptData(a)){var d,e,f=a.nodeType,g=f?m.cache:a,h=f?a[m.expando]:m.expando;if(g[h]){if(b&&(d=c?g[h]:g[h].data)){m.isArray(b)?b=b.concat(m.map(b,m.camelCase)):b in d?b=[b]:(b=m.camelCase(b),b=b in d?[b]:b.split(" ")),e=b.length;while(e--)delete d[b[e]];if(c?!P(d):!m.isEmptyObject(d))return}(c||(delete g[h].data,P(g[h])))&&(f?m.cleanData([a],!0):k.deleteExpando||g!=g.window?delete g[h]:g[h]=null)}}}m.extend({cache:{},noData:{"applet ":!0,"embed ":!0,"object ":"clsid:D27CDB6E-AE6D-11cf-96B8-444553540000"},hasData:function(a){return a=a.nodeType?m.cache[a[m.expando]]:a[m.expando],!!a&&!P(a)},data:function(a,b,c){return Q(a,b,c)},removeData:function(a,b){return R(a,b)},_data:function(a,b,c){return Q(a,b,c,!0)},_removeData:function(a,b){return R(a,b,!0)}}),m.fn.extend({data:function(a,b){var c,d,e,f=this[0],g=f&&f.attributes;if(void 0===a){if(this.length&&(e=m.data(f),1===f.nodeType&&!m._data(f,"parsedAttrs"))){c=g.length;while(c--)g[c]&&(d=g[c].name,0===d.indexOf("data-")&&(d=m.camelCase(d.slice(5)),O(f,d,e[d])));m._data(f,"parsedAttrs",!0)}return e}return"object"==typeof a?this.each(function(){m.data(this,a)}):arguments.length>1?this.each(function(){m.data(this,a,b)}):f?O(f,a,m.data(f,a)):void 0},removeData:function(a){return this.each(function(){m.removeData(this,a)})}}),m.extend({queue:function(a,b,c){var d;return a?(b=(b||"fx")+"queue",d=m._data(a,b),c&&(!d||m.isArray(c)?d=m._data(a,b,m.makeArray(c)):d.push(c)),d||[]):void 0},dequeue:function(a,b){b=b||"fx";var c=m.queue(a,b),d=c.length,e=c.shift(),f=m._queueHooks(a,b),g=function(){m.dequeue(a,b)};"inprogress"===e&&(e=c.shift(),d--),e&&("fx"===b&&c.unshift("inprogress"),delete f.stop,e.call(a,g,f)),!d&&f&&f.empty.fire()},_queueHooks:function(a,b){var c=b+"queueHooks";return m._data(a,c)||m._data(a,c,{empty:m.Callbacks("once memory").add(function(){m._removeData(a,b+"queue"),m._removeData(a,c)})})}}),m.fn.extend({queue:function(a,b){var c=2;return"string"!=typeof a&&(b=a,a="fx",c--),arguments.length<c?m.queue(this[0],a):void 0===b?this:this.each(function(){var c=m.queue(this,a,b);m._queueHooks(this,a),"fx"===a&&"inprogress"!==c[0]&&m.dequeue(this,a)})},dequeue:function(a){return this.each(function(){m.dequeue(this,a)})},clearQueue:function(a){return this.queue(a||"fx",[])},promise:function(a,b){var c,d=1,e=m.Deferred(),f=this,g=this.length,h=function(){--d||e.resolveWith(f,[f])};"string"!=typeof a&&(b=a,a=void 0),a=a||"fx";while(g--)c=m._data(f[g],a+"queueHooks"),c&&c.empty&&(d++,c.empty.add(h));return h(),e.promise(b)}});var S=/[+-]?(?:\d*\.|)\d+(?:[eE][+-]?\d+|)/.source,T=["Top","Right","Bottom","Left"],U=function(a,b){return a=b||a,"none"===m.css(a,"display")||!m.contains(a.ownerDocument,a)},V=m.access=function(a,b,c,d,e,f,g){var h=0,i=a.length,j=null==c;if("object"===m.type(c)){e=!0;for(h in c)m.access(a,b,h,c[h],!0,f,g)}else if(void 0!==d&&(e=!0,m.isFunction(d)||(g=!0),j&&(g?(b.call(a,d),b=null):(j=b,b=function(a,b,c){return j.call(m(a),c)})),b))for(;i>h;h++)b(a[h],c,g?d:d.call(a[h],h,b(a[h],c)));return e?a:j?b.call(a):i?b(a[0],c):f},W=/^(?:checkbox|radio)$/i;!function(){var a=y.createElement("input"),b=y.createElement("div"),c=y.createDocumentFragment();if(b.innerHTML="  <link/><table></table><a href='/a'>a</a><input type='checkbox'/>",k.leadingWhitespace=3===b.firstChild.nodeType,k.tbody=!b.getElementsByTagName("tbody").length,k.htmlSerialize=!!b.getElementsByTagName("link").length,k.html5Clone="<:nav></:nav>"!==y.createElement("nav").cloneNode(!0).outerHTML,a.type="checkbox",a.checked=!0,c.appendChild(a),k.appendChecked=a.checked,b.innerHTML="<textarea>x</textarea>",k.noCloneChecked=!!b.cloneNode(!0).lastChild.defaultValue,c.appendChild(b),b.innerHTML="<input type='radio' checked='checked' name='t'/>",k.checkClone=b.cloneNode(!0).cloneNode(!0).lastChild.checked,k.noCloneEvent=!0,b.attachEvent&&(b.attachEvent("onclick",function(){k.noCloneEvent=!1}),b.cloneNode(!0).click()),null==k.deleteExpando){k.deleteExpando=!0;try{delete b.test}catch(d){k.deleteExpando=!1}}}(),function(){var b,c,d=y.createElement("div");for(b in{submit:!0,change:!0,focusin:!0})c="on"+b,(k[b+"Bubbles"]=c in a)||(d.setAttribute(c,"t"),k[b+"Bubbles"]=d.attributes[c].expando===!1);d=null}();var X=/^(?:input|select|textarea)$/i,Y=/^key/,Z=/^(?:mouse|pointer|contextmenu)|click/,$=/^(?:focusinfocus|focusoutblur)$/,_=/^([^.]*)(?:\.(.+)|)$/;function aa(){return!0}function ba(){return!1}function ca(){try{return y.activeElement}catch(a){}}m.event={global:{},add:function(a,b,c,d,e){var f,g,h,i,j,k,l,n,o,p,q,r=m._data(a);if(r){c.handler&&(i=c,c=i.handler,e=i.selector),c.guid||(c.guid=m.guid++),(g=r.events)||(g=r.events={}),(k=r.handle)||(k=r.handle=function(a){return typeof m===K||a&&m.event.triggered===a.type?void 0:m.event.dispatch.apply(k.elem,arguments)},k.elem=a),b=(b||"").match(E)||[""],h=b.length;while(h--)f=_.exec(b[h])||[],o=q=f[1],p=(f[2]||"").split(".").sort(),o&&(j=m.event.special[o]||{},o=(e?j.delegateType:j.bindType)||o,j=m.event.special[o]||{},l=m.extend({type:o,origType:q,data:d,handler:c,guid:c.guid,selector:e,needsContext:e&&m.expr.match.needsContext.test(e),namespace:p.join(".")},i),(n=g[o])||(n=g[o]=[],n.delegateCount=0,j.setup&&j.setup.call(a,d,p,k)!==!1||(a.addEventListener?a.addEventListener(o,k,!1):a.attachEvent&&a.attachEvent("on"+o,k))),j.add&&(j.add.call(a,l),l.handler.guid||(l.handler.guid=c.guid)),e?n.splice(n.delegateCount++,0,l):n.push(l),m.event.global[o]=!0);a=null}},remove:function(a,b,c,d,e){var f,g,h,i,j,k,l,n,o,p,q,r=m.hasData(a)&&m._data(a);if(r&&(k=r.events)){b=(b||"").match(E)||[""],j=b.length;while(j--)if(h=_.exec(b[j])||[],o=q=h[1],p=(h[2]||"").split(".").sort(),o){l=m.event.special[o]||{},o=(d?l.delegateType:l.bindType)||o,n=k[o]||[],h=h[2]&&new RegExp("(^|\\.)"+p.join("\\.(?:.*\\.|)")+"(\\.|$)"),i=f=n.length;while(f--)g=n[f],!e&&q!==g.origType||c&&c.guid!==g.guid||h&&!h.test(g.namespace)||d&&d!==g.selector&&("**"!==d||!g.selector)||(n.splice(f,1),g.selector&&n.delegateCount--,l.remove&&l.remove.call(a,g));i&&!n.length&&(l.teardown&&l.teardown.call(a,p,r.handle)!==!1||m.removeEvent(a,o,r.handle),delete k[o])}else for(o in k)m.event.remove(a,o+b[j],c,d,!0);m.isEmptyObject(k)&&(delete r.handle,m._removeData(a,"events"))}},trigger:function(b,c,d,e){var f,g,h,i,k,l,n,o=[d||y],p=j.call(b,"type")?b.type:b,q=j.call(b,"namespace")?b.namespace.split("."):[];if(h=l=d=d||y,3!==d.nodeType&&8!==d.nodeType&&!$.test(p+m.event.triggered)&&(p.indexOf(".")>=0&&(q=p.split("."),p=q.shift(),q.sort()),g=p.indexOf(":")<0&&"on"+p,b=b[m.expando]?b:new m.Event(p,"object"==typeof b&&b),b.isTrigger=e?2:3,b.namespace=q.join("."),b.namespace_re=b.namespace?new RegExp("(^|\\.)"+q.join("\\.(?:.*\\.|)")+"(\\.|$)"):null,b.result=void 0,b.target||(b.target=d),c=null==c?[b]:m.makeArray(c,[b]),k=m.event.special[p]||{},e||!k.trigger||k.trigger.apply(d,c)!==!1)){if(!e&&!k.noBubble&&!m.isWindow(d)){for(i=k.delegateType||p,$.test(i+p)||(h=h.parentNode);h;h=h.parentNode)o.push(h),l=h;l===(d.ownerDocument||y)&&o.push(l.defaultView||l.parentWindow||a)}n=0;while((h=o[n++])&&!b.isPropagationStopped())b.type=n>1?i:k.bindType||p,f=(m._data(h,"events")||{})[b.type]&&m._data(h,"handle"),f&&f.apply(h,c),f=g&&h[g],f&&f.apply&&m.acceptData(h)&&(b.result=f.apply(h,c),b.result===!1&&b.preventDefault());if(b.type=p,!e&&!b.isDefaultPrevented()&&(!k._default||k._default.apply(o.pop(),c)===!1)&&m.acceptData(d)&&g&&d[p]&&!m.isWindow(d)){l=d[g],l&&(d[g]=null),m.event.triggered=p;try{d[p]()}catch(r){}m.event.triggered=void 0,l&&(d[g]=l)}return b.result}},dispatch:function(a){a=m.event.fix(a);var b,c,e,f,g,h=[],i=d.call(arguments),j=(m._data(this,"events")||{})[a.type]||[],k=m.event.special[a.type]||{};if(i[0]=a,a.delegateTarget=this,!k.preDispatch||k.preDispatch.call(this,a)!==!1){h=m.event.handlers.call(this,a,j),b=0;while((f=h[b++])&&!a.isPropagationStopped()){a.currentTarget=f.elem,g=0;while((e=f.handlers[g++])&&!a.isImmediatePropagationStopped())(!a.namespace_re||a.namespace_re.test(e.namespace))&&(a.handleObj=e,a.data=e.data,c=((m.event.special[e.origType]||{}).handle||e.handler).apply(f.elem,i),void 0!==c&&(a.result=c)===!1&&(a.preventDefault(),a.stopPropagation()))}return k.postDispatch&&k.postDispatch.call(this,a),a.result}},handlers:function(a,b){var c,d,e,f,g=[],h=b.delegateCount,i=a.target;if(h&&i.nodeType&&(!a.button||"click"!==a.type))for(;i!=this;i=i.parentNode||this)if(1===i.nodeType&&(i.disabled!==!0||"click"!==a.type)){for(e=[],f=0;h>f;f++)d=b[f],c=d.selector+" ",void 0===e[c]&&(e[c]=d.needsContext?m(c,this).index(i)>=0:m.find(c,this,null,[i]).length),e[c]&&e.push(d);e.length&&g.push({elem:i,handlers:e})}return h<b.length&&g.push({elem:this,handlers:b.slice(h)}),g},fix:function(a){if(a[m.expando])return a;var b,c,d,e=a.type,f=a,g=this.fixHooks[e];g||(this.fixHooks[e]=g=Z.test(e)?this.mouseHooks:Y.test(e)?this.keyHooks:{}),d=g.props?this.props.concat(g.props):this.props,a=new m.Event(f),b=d.length;while(b--)c=d[b],a[c]=f[c];return a.target||(a.target=f.srcElement||y),3===a.target.nodeType&&(a.target=a.target.parentNode),a.metaKey=!!a.metaKey,g.filter?g.filter(a,f):a},props:"altKey bubbles cancelable ctrlKey currentTarget eventPhase metaKey relatedTarget shiftKey target timeStamp view which".split(" "),fixHooks:{},keyHooks:{props:"char charCode key keyCode".split(" "),filter:function(a,b){return null==a.which&&(a.which=null!=b.charCode?b.charCode:b.keyCode),a}},mouseHooks:{props:"button buttons clientX clientY fromElement offsetX offsetY pageX pageY screenX screenY toElement".split(" "),filter:function(a,b){var c,d,e,f=b.button,g=b.fromElement;return null==a.pageX&&null!=b.clientX&&(d=a.target.ownerDocument||y,e=d.documentElement,c=d.body,a.pageX=b.clientX+(e&&e.scrollLeft||c&&c.scrollLeft||0)-(e&&e.clientLeft||c&&c.clientLeft||0),a.pageY=b.clientY+(e&&e.scrollTop||c&&c.scrollTop||0)-(e&&e.clientTop||c&&c.clientTop||0)),!a.relatedTarget&&g&&(a.relatedTarget=g===a.target?b.toElement:g),a.which||void 0===f||(a.which=1&f?1:2&f?3:4&f?2:0),a}},special:{load:{noBubble:!0},focus:{trigger:function(){if(this!==ca()&&this.focus)try{return this.focus(),!1}catch(a){}},delegateType:"focusin"},blur:{trigger:function(){return this===ca()&&this.blur?(this.blur(),!1):void 0},delegateType:"focusout"},click:{trigger:function(){return m.nodeName(this,"input")&&"checkbox"===this.type&&this.click?(this.click(),!1):void 0},_default:function(a){return m.nodeName(a.target,"a")}},beforeunload:{postDispatch:function(a){void 0!==a.result&&a.originalEvent&&(a.originalEvent.returnValue=a.result)}}},simulate:function(a,b,c,d){var e=m.extend(new m.Event,c,{type:a,isSimulated:!0,originalEvent:{}});d?m.event.trigger(e,null,b):m.event.dispatch.call(b,e),e.isDefaultPrevented()&&c.preventDefault()}},m.removeEvent=y.removeEventListener?function(a,b,c){a.removeEventListener&&a.removeEventListener(b,c,!1)}:function(a,b,c){var d="on"+b;a.detachEvent&&(typeof a[d]===K&&(a[d]=null),a.detachEvent(d,c))},m.Event=function(a,b){return this instanceof m.Event?(a&&a.type?(this.originalEvent=a,this.type=a.type,this.isDefaultPrevented=a.defaultPrevented||void 0===a.defaultPrevented&&a.returnValue===!1?aa:ba):this.type=a,b&&m.extend(this,b),this.timeStamp=a&&a.timeStamp||m.now(),void(this[m.expando]=!0)):new m.Event(a,b)},m.Event.prototype={isDefaultPrevented:ba,isPropagationStopped:ba,isImmediatePropagationStopped:ba,preventDefault:function(){var a=this.originalEvent;this.isDefaultPrevented=aa,a&&(a.preventDefault?a.preventDefault():a.returnValue=!1)},stopPropagation:function(){var a=this.originalEvent;this.isPropagationStopped=aa,a&&(a.stopPropagation&&a.stopPropagation(),a.cancelBubble=!0)},stopImmediatePropagation:function(){var a=this.originalEvent;this.isImmediatePropagationStopped=aa,a&&a.stopImmediatePropagation&&a.stopImmediatePropagation(),this.stopPropagation()}},m.each({mouseenter:"mouseover",mouseleave:"mouseout",pointerenter:"pointerover",pointerleave:"pointerout"},function(a,b){m.event.special[a]={delegateType:b,bindType:b,handle:function(a){var c,d=this,e=a.relatedTarget,f=a.handleObj;return(!e||e!==d&&!m.contains(d,e))&&(a.type=f.origType,c=f.handler.apply(this,arguments),a.type=b),c}}}),k.submitBubbles||(m.event.special.submit={setup:function(){return m.nodeName(this,"form")?!1:void m.event.add(this,"click._submit keypress._submit",function(a){var b=a.target,c=m.nodeName(b,"input")||m.nodeName(b,"button")?b.form:void 0;c&&!m._data(c,"submitBubbles")&&(m.event.add(c,"submit._submit",function(a){a._submit_bubble=!0}),m._data(c,"submitBubbles",!0))})},postDispatch:function(a){a._submit_bubble&&(delete a._submit_bubble,this.parentNode&&!a.isTrigger&&m.event.simulate("submit",this.parentNode,a,!0))},teardown:function(){return m.nodeName(this,"form")?!1:void m.event.remove(this,"._submit")}}),k.changeBubbles||(m.event.special.change={setup:function(){return X.test(this.nodeName)?(("checkbox"===this.type||"radio"===this.type)&&(m.event.add(this,"propertychange._change",function(a){"checked"===a.originalEvent.propertyName&&(this._just_changed=!0)}),m.event.add(this,"click._change",function(a){this._just_changed&&!a.isTrigger&&(this._just_changed=!1),m.event.simulate("change",this,a,!0)})),!1):void m.event.add(this,"beforeactivate._change",function(a){var b=a.target;X.test(b.nodeName)&&!m._data(b,"changeBubbles")&&(m.event.add(b,"change._change",function(a){!this.parentNode||a.isSimulated||a.isTrigger||m.event.simulate("change",this.parentNode,a,!0)}),m._data(b,"changeBubbles",!0))})},handle:function(a){var b=a.target;return this!==b||a.isSimulated||a.isTrigger||"radio"!==b.type&&"checkbox"!==b.type?a.handleObj.handler.apply(this,arguments):void 0},teardown:function(){return m.event.remove(this,"._change"),!X.test(this.nodeName)}}),k.focusinBubbles||m.each({focus:"focusin",blur:"focusout"},function(a,b){var c=function(a){m.event.simulate(b,a.target,m.event.fix(a),!0)};m.event.special[b]={setup:function(){var d=this.ownerDocument||this,e=m._data(d,b);e||d.addEventListener(a,c,!0),m._data(d,b,(e||0)+1)},teardown:function(){var d=this.ownerDocument||this,e=m._data(d,b)-1;e?m._data(d,b,e):(d.removeEventListener(a,c,!0),m._removeData(d,b))}}}),m.fn.extend({on:function(a,b,c,d,e){var f,g;if("object"==typeof a){"string"!=typeof b&&(c=c||b,b=void 0);for(f in a)this.on(f,b,c,a[f],e);return this}if(null==c&&null==d?(d=b,c=b=void 0):null==d&&("string"==typeof b?(d=c,c=void 0):(d=c,c=b,b=void 0)),d===!1)d=ba;else if(!d)return this;return 1===e&&(g=d,d=function(a){return m().off(a),g.apply(this,arguments)},d.guid=g.guid||(g.guid=m.guid++)),this.each(function(){m.event.add(this,a,d,c,b)})},one:function(a,b,c,d){return this.on(a,b,c,d,1)},off:function(a,b,c){var d,e;if(a&&a.preventDefault&&a.handleObj)return d=a.handleObj,m(a.delegateTarget).off(d.namespace?d.origType+"."+d.namespace:d.origType,d.selector,d.handler),this;if("object"==typeof a){for(e in a)this.off(e,b,a[e]);return this}return(b===!1||"function"==typeof b)&&(c=b,b=void 0),c===!1&&(c=ba),this.each(function(){m.event.remove(this,a,c,b)})},trigger:function(a,b){return this.each(function(){m.event.trigger(a,b,this)})},triggerHandler:function(a,b){var c=this[0];return c?m.event.trigger(a,b,c,!0):void 0}});function da(a){var b=ea.split("|"),c=a.createDocumentFragment();if(c.createElement)while(b.length)c.createElement(b.pop());return c}var ea="abbr|article|aside|audio|bdi|canvas|data|datalist|details|figcaption|figure|footer|header|hgroup|mark|meter|nav|output|progress|section|summary|time|video",fa=/ jQuery\d+="(?:null|\d+)"/g,ga=new RegExp("<(?:"+ea+")[\\s/>]","i"),ha=/^\s+/,ia=/<(?!area|br|col|embed|hr|img|input|link|meta|param)(([\w:]+)[^>]*)\/>/gi,ja=/<([\w:]+)/,ka=/<tbody/i,la=/<|&#?\w+;/,ma=/<(?:script|style|link)/i,na=/checked\s*(?:[^=]|=\s*.checked.)/i,oa=/^$|\/(?:java|ecma)script/i,pa=/^true\/(.*)/,qa=/^\s*<!(?:\[CDATA\[|--)|(?:\]\]|--)>\s*$/g,ra={option:[1,"<select multiple='multiple'>","</select>"],legend:[1,"<fieldset>","</fieldset>"],area:[1,"<map>","</map>"],param:[1,"<object>","</object>"],thead:[1,"<table>","</table>"],tr:[2,"<table><tbody>","</tbody></table>"],col:[2,"<table><tbody></tbody><colgroup>","</colgroup></table>"],td:[3,"<table><tbody><tr>","</tr></tbody></table>"],_default:k.htmlSerialize?[0,"",""]:[1,"X<div>","</div>"]},sa=da(y),ta=sa.appendChild(y.createElement("div"));ra.optgroup=ra.option,ra.tbody=ra.tfoot=ra.colgroup=ra.caption=ra.thead,ra.th=ra.td;function ua(a,b){var c,d,e=0,f=typeof a.getElementsByTagName!==K?a.getElementsByTagName(b||"*"):typeof a.querySelectorAll!==K?a.querySelectorAll(b||"*"):void 0;if(!f)for(f=[],c=a.childNodes||a;null!=(d=c[e]);e++)!b||m.nodeName(d,b)?f.push(d):m.merge(f,ua(d,b));return void 0===b||b&&m.nodeName(a,b)?m.merge([a],f):f}function va(a){W.test(a.type)&&(a.defaultChecked=a.checked)}function wa(a,b){return m.nodeName(a,"table")&&m.nodeName(11!==b.nodeType?b:b.firstChild,"tr")?a.getElementsByTagName("tbody")[0]||a.appendChild(a.ownerDocument.createElement("tbody")):a}function xa(a){return a.type=(null!==m.find.attr(a,"type"))+"/"+a.type,a}function ya(a){var b=pa.exec(a.type);return b?a.type=b[1]:a.removeAttribute("type"),a}function za(a,b){for(var c,d=0;null!=(c=a[d]);d++)m._data(c,"globalEval",!b||m._data(b[d],"globalEval"))}function Aa(a,b){if(1===b.nodeType&&m.hasData(a)){var c,d,e,f=m._data(a),g=m._data(b,f),h=f.events;if(h){delete g.handle,g.events={};for(c in h)for(d=0,e=h[c].length;e>d;d++)m.event.add(b,c,h[c][d])}g.data&&(g.data=m.extend({},g.data))}}function Ba(a,b){var c,d,e;if(1===b.nodeType){if(c=b.nodeName.toLowerCase(),!k.noCloneEvent&&b[m.expando]){e=m._data(b);for(d in e.events)m.removeEvent(b,d,e.handle);b.removeAttribute(m.expando)}"script"===c&&b.text!==a.text?(xa(b).text=a.text,ya(b)):"object"===c?(b.parentNode&&(b.outerHTML=a.outerHTML),k.html5Clone&&a.innerHTML&&!m.trim(b.innerHTML)&&(b.innerHTML=a.innerHTML)):"input"===c&&W.test(a.type)?(b.defaultChecked=b.checked=a.checked,b.value!==a.value&&(b.value=a.value)):"option"===c?b.defaultSelected=b.selected=a.defaultSelected:("input"===c||"textarea"===c)&&(b.defaultValue=a.defaultValue)}}m.extend({clone:function(a,b,c){var d,e,f,g,h,i=m.contains(a.ownerDocument,a);if(k.html5Clone||m.isXMLDoc(a)||!ga.test("<"+a.nodeName+">")?f=a.cloneNode(!0):(ta.innerHTML=a.outerHTML,ta.removeChild(f=ta.firstChild)),!(k.noCloneEvent&&k.noCloneChecked||1!==a.nodeType&&11!==a.nodeType||m.isXMLDoc(a)))for(d=ua(f),h=ua(a),g=0;null!=(e=h[g]);++g)d[g]&&Ba(e,d[g]);if(b)if(c)for(h=h||ua(a),d=d||ua(f),g=0;null!=(e=h[g]);g++)Aa(e,d[g]);else Aa(a,f);return d=ua(f,"script"),d.length>0&&za(d,!i&&ua(a,"script")),d=h=e=null,f},buildFragment:function(a,b,c,d){for(var e,f,g,h,i,j,l,n=a.length,o=da(b),p=[],q=0;n>q;q++)if(f=a[q],f||0===f)if("object"===m.type(f))m.merge(p,f.nodeType?[f]:f);else if(la.test(f)){h=h||o.appendChild(b.createElement("div")),i=(ja.exec(f)||["",""])[1].toLowerCase(),l=ra[i]||ra._default,h.innerHTML=l[1]+f.replace(ia,"<$1></$2>")+l[2],e=l[0];while(e--)h=h.lastChild;if(!k.leadingWhitespace&&ha.test(f)&&p.push(b.createTextNode(ha.exec(f)[0])),!k.tbody){f="table"!==i||ka.test(f)?"<table>"!==l[1]||ka.test(f)?0:h:h.firstChild,e=f&&f.childNodes.length;while(e--)m.nodeName(j=f.childNodes[e],"tbody")&&!j.childNodes.length&&f.removeChild(j)}m.merge(p,h.childNodes),h.textContent="";while(h.firstChild)h.removeChild(h.firstChild);h=o.lastChild}else p.push(b.createTextNode(f));h&&o.removeChild(h),k.appendChecked||m.grep(ua(p,"input"),va),q=0;while(f=p[q++])if((!d||-1===m.inArray(f,d))&&(g=m.contains(f.ownerDocument,f),h=ua(o.appendChild(f),"script"),g&&za(h),c)){e=0;while(f=h[e++])oa.test(f.type||"")&&c.push(f)}return h=null,o},cleanData:function(a,b){for(var d,e,f,g,h=0,i=m.expando,j=m.cache,l=k.deleteExpando,n=m.event.special;null!=(d=a[h]);h++)if((b||m.acceptData(d))&&(f=d[i],g=f&&j[f])){if(g.events)for(e in g.events)n[e]?m.event.remove(d,e):m.removeEvent(d,e,g.handle);j[f]&&(delete j[f],l?delete d[i]:typeof d.removeAttribute!==K?d.removeAttribute(i):d[i]=null,c.push(f))}}}),m.fn.extend({text:function(a){return V(this,function(a){return void 0===a?m.text(this):this.empty().append((this[0]&&this[0].ownerDocument||y).createTextNode(a))},null,a,arguments.length)},append:function(){return this.domManip(arguments,function(a){if(1===this.nodeType||11===this.nodeType||9===this.nodeType){var b=wa(this,a);b.appendChild(a)}})},prepend:function(){return this.domManip(arguments,function(a){if(1===this.nodeType||11===this.nodeType||9===this.nodeType){var b=wa(this,a);b.insertBefore(a,b.firstChild)}})},before:function(){return this.domManip(arguments,function(a){this.parentNode&&this.parentNode.insertBefore(a,this)})},after:function(){return this.domManip(arguments,function(a){this.parentNode&&this.parentNode.insertBefore(a,this.nextSibling)})},remove:function(a,b){for(var c,d=a?m.filter(a,this):this,e=0;null!=(c=d[e]);e++)b||1!==c.nodeType||m.cleanData(ua(c)),c.parentNode&&(b&&m.contains(c.ownerDocument,c)&&za(ua(c,"script")),c.parentNode.removeChild(c));return this},empty:function(){for(var a,b=0;null!=(a=this[b]);b++){1===a.nodeType&&m.cleanData(ua(a,!1));while(a.firstChild)a.removeChild(a.firstChild);a.options&&m.nodeName(a,"select")&&(a.options.length=0)}return this},clone:function(a,b){return a=null==a?!1:a,b=null==b?a:b,this.map(function(){return m.clone(this,a,b)})},html:function(a){return V(this,function(a){var b=this[0]||{},c=0,d=this.length;if(void 0===a)return 1===b.nodeType?b.innerHTML.replace(fa,""):void 0;if(!("string"!=typeof a||ma.test(a)||!k.htmlSerialize&&ga.test(a)||!k.leadingWhitespace&&ha.test(a)||ra[(ja.exec(a)||["",""])[1].toLowerCase()])){a=a.replace(ia,"<$1></$2>");try{for(;d>c;c++)b=this[c]||{},1===b.nodeType&&(m.cleanData(ua(b,!1)),b.innerHTML=a);b=0}catch(e){}}b&&this.empty().append(a)},null,a,arguments.length)},replaceWith:function(){var a=arguments[0];return this.domManip(arguments,function(b){a=this.parentNode,m.cleanData(ua(this)),a&&a.replaceChild(b,this)}),a&&(a.length||a.nodeType)?this:this.remove()},detach:function(a){return this.remove(a,!0)},domManip:function(a,b){a=e.apply([],a);var c,d,f,g,h,i,j=0,l=this.length,n=this,o=l-1,p=a[0],q=m.isFunction(p);if(q||l>1&&"string"==typeof p&&!k.checkClone&&na.test(p))return this.each(function(c){var d=n.eq(c);q&&(a[0]=p.call(this,c,d.html())),d.domManip(a,b)});if(l&&(i=m.buildFragment(a,this[0].ownerDocument,!1,this),c=i.firstChild,1===i.childNodes.length&&(i=c),c)){for(g=m.map(ua(i,"script"),xa),f=g.length;l>j;j++)d=i,j!==o&&(d=m.clone(d,!0,!0),f&&m.merge(g,ua(d,"script"))),b.call(this[j],d,j);if(f)for(h=g[g.length-1].ownerDocument,m.map(g,ya),j=0;f>j;j++)d=g[j],oa.test(d.type||"")&&!m._data(d,"globalEval")&&m.contains(h,d)&&(d.src?m._evalUrl&&m._evalUrl(d.src):m.globalEval((d.text||d.textContent||d.innerHTML||"").replace(qa,"")));i=c=null}return this}}),m.each({appendTo:"append",prependTo:"prepend",insertBefore:"before",insertAfter:"after",replaceAll:"replaceWith"},function(a,b){m.fn[a]=function(a){for(var c,d=0,e=[],g=m(a),h=g.length-1;h>=d;d++)c=d===h?this:this.clone(!0),m(g[d])[b](c),f.apply(e,c.get());return this.pushStack(e)}});var Ca,Da={};function Ea(b,c){var d,e=m(c.createElement(b)).appendTo(c.body),f=a.getDefaultComputedStyle&&(d=a.getDefaultComputedStyle(e[0]))?d.display:m.css(e[0],"display");return e.detach(),f}function Fa(a){var b=y,c=Da[a];return c||(c=Ea(a,b),"none"!==c&&c||(Ca=(Ca||m("<iframe frameborder='0' width='0' height='0'/>")).appendTo(b.documentElement),b=(Ca[0].contentWindow||Ca[0].contentDocument).document,b.write(),b.close(),c=Ea(a,b),Ca.detach()),Da[a]=c),c}!function(){var a;k.shrinkWrapBlocks=function(){if(null!=a)return a;a=!1;var b,c,d;return c=y.getElementsByTagName("body")[0],c&&c.style?(b=y.createElement("div"),d=y.createElement("div"),d.style.cssText="position:absolute;border:0;width:0;height:0;top:0;left:-9999px",c.appendChild(d).appendChild(b),typeof b.style.zoom!==K&&(b.style.cssText="-webkit-box-sizing:content-box;-moz-box-sizing:content-box;box-sizing:content-box;display:block;margin:0;border:0;padding:1px;width:1px;zoom:1",b.appendChild(y.createElement("div")).style.width="5px",a=3!==b.offsetWidth),c.removeChild(d),a):void 0}}();var Ga=/^margin/,Ha=new RegExp("^("+S+")(?!px)[a-z%]+$","i"),Ia,Ja,Ka=/^(top|right|bottom|left)$/;a.getComputedStyle?(Ia=function(b){return b.ownerDocument.defaultView.opener?b.ownerDocument.defaultView.getComputedStyle(b,null):a.getComputedStyle(b,null)},Ja=function(a,b,c){var d,e,f,g,h=a.style;return c=c||Ia(a),g=c?c.getPropertyValue(b)||c[b]:void 0,c&&(""!==g||m.contains(a.ownerDocument,a)||(g=m.style(a,b)),Ha.test(g)&&Ga.test(b)&&(d=h.width,e=h.minWidth,f=h.maxWidth,h.minWidth=h.maxWidth=h.width=g,g=c.width,h.width=d,h.minWidth=e,h.maxWidth=f)),void 0===g?g:g+""}):y.documentElement.currentStyle&&(Ia=function(a){return a.currentStyle},Ja=function(a,b,c){var d,e,f,g,h=a.style;return c=c||Ia(a),g=c?c[b]:void 0,null==g&&h&&h[b]&&(g=h[b]),Ha.test(g)&&!Ka.test(b)&&(d=h.left,e=a.runtimeStyle,f=e&&e.left,f&&(e.left=a.currentStyle.left),h.left="fontSize"===b?"1em":g,g=h.pixelLeft+"px",h.left=d,f&&(e.left=f)),void 0===g?g:g+""||"auto"});function La(a,b){return{get:function(){var c=a();if(null!=c)return c?void delete this.get:(this.get=b).apply(this,arguments)}}}!function(){var b,c,d,e,f,g,h;if(b=y.createElement("div"),b.innerHTML="  <link/><table></table><a href='/a'>a</a><input type='checkbox'/>",d=b.getElementsByTagName("a")[0],c=d&&d.style){c.cssText="float:left;opacity:.5",k.opacity="0.5"===c.opacity,k.cssFloat=!!c.cssFloat,b.style.backgroundClip="content-box",b.cloneNode(!0).style.backgroundClip="",k.clearCloneStyle="content-box"===b.style.backgroundClip,k.boxSizing=""===c.boxSizing||""===c.MozBoxSizing||""===c.WebkitBoxSizing,m.extend(k,{reliableHiddenOffsets:function(){return null==g&&i(),g},boxSizingReliable:function(){return null==f&&i(),f},pixelPosition:function(){return null==e&&i(),e},reliableMarginRight:function(){return null==h&&i(),h}});function i(){var b,c,d,i;c=y.getElementsByTagName("body")[0],c&&c.style&&(b=y.createElement("div"),d=y.createElement("div"),d.style.cssText="position:absolute;border:0;width:0;height:0;top:0;left:-9999px",c.appendChild(d).appendChild(b),b.style.cssText="-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;display:block;margin-top:1%;top:1%;border:1px;padding:1px;width:4px;position:absolute",e=f=!1,h=!0,a.getComputedStyle&&(e="1%"!==(a.getComputedStyle(b,null)||{}).top,f="4px"===(a.getComputedStyle(b,null)||{width:"4px"}).width,i=b.appendChild(y.createElement("div")),i.style.cssText=b.style.cssText="-webkit-box-sizing:content-box;-moz-box-sizing:content-box;box-sizing:content-box;display:block;margin:0;border:0;padding:0",i.style.marginRight=i.style.width="0",b.style.width="1px",h=!parseFloat((a.getComputedStyle(i,null)||{}).marginRight),b.removeChild(i)),b.innerHTML="<table><tr><td></td><td>t</td></tr></table>",i=b.getElementsByTagName("td"),i[0].style.cssText="margin:0;border:0;padding:0;display:none",g=0===i[0].offsetHeight,g&&(i[0].style.display="",i[1].style.display="none",g=0===i[0].offsetHeight),c.removeChild(d))}}}(),m.swap=function(a,b,c,d){var e,f,g={};for(f in b)g[f]=a.style[f],a.style[f]=b[f];e=c.apply(a,d||[]);for(f in b)a.style[f]=g[f];return e};var Ma=/alpha\([^)]*\)/i,Na=/opacity\s*=\s*([^)]*)/,Oa=/^(none|table(?!-c[ea]).+)/,Pa=new RegExp("^("+S+")(.*)$","i"),Qa=new RegExp("^([+-])=("+S+")","i"),Ra={position:"absolute",visibility:"hidden",display:"block"},Sa={letterSpacing:"0",fontWeight:"400"},Ta=["Webkit","O","Moz","ms"];function Ua(a,b){if(b in a)return b;var c=b.charAt(0).toUpperCase()+b.slice(1),d=b,e=Ta.length;while(e--)if(b=Ta[e]+c,b in a)return b;return d}function Va(a,b){for(var c,d,e,f=[],g=0,h=a.length;h>g;g++)d=a[g],d.style&&(f[g]=m._data(d,"olddisplay"),c=d.style.display,b?(f[g]||"none"!==c||(d.style.display=""),""===d.style.display&&U(d)&&(f[g]=m._data(d,"olddisplay",Fa(d.nodeName)))):(e=U(d),(c&&"none"!==c||!e)&&m._data(d,"olddisplay",e?c:m.css(d,"display"))));for(g=0;h>g;g++)d=a[g],d.style&&(b&&"none"!==d.style.display&&""!==d.style.display||(d.style.display=b?f[g]||"":"none"));return a}function Wa(a,b,c){var d=Pa.exec(b);return d?Math.max(0,d[1]-(c||0))+(d[2]||"px"):b}function Xa(a,b,c,d,e){for(var f=c===(d?"border":"content")?4:"width"===b?1:0,g=0;4>f;f+=2)"margin"===c&&(g+=m.css(a,c+T[f],!0,e)),d?("content"===c&&(g-=m.css(a,"padding"+T[f],!0,e)),"margin"!==c&&(g-=m.css(a,"border"+T[f]+"Width",!0,e))):(g+=m.css(a,"padding"+T[f],!0,e),"padding"!==c&&(g+=m.css(a,"border"+T[f]+"Width",!0,e)));return g}function Ya(a,b,c){var d=!0,e="width"===b?a.offsetWidth:a.offsetHeight,f=Ia(a),g=k.boxSizing&&"border-box"===m.css(a,"boxSizing",!1,f);if(0>=e||null==e){if(e=Ja(a,b,f),(0>e||null==e)&&(e=a.style[b]),Ha.test(e))return e;d=g&&(k.boxSizingReliable()||e===a.style[b]),e=parseFloat(e)||0}return e+Xa(a,b,c||(g?"border":"content"),d,f)+"px"}m.extend({cssHooks:{opacity:{get:function(a,b){if(b){var c=Ja(a,"opacity");return""===c?"1":c}}}},cssNumber:{columnCount:!0,fillOpacity:!0,flexGrow:!0,flexShrink:!0,fontWeight:!0,lineHeight:!0,opacity:!0,order:!0,orphans:!0,widows:!0,zIndex:!0,zoom:!0},cssProps:{"float":k.cssFloat?"cssFloat":"styleFloat"},style:function(a,b,c,d){if(a&&3!==a.nodeType&&8!==a.nodeType&&a.style){var e,f,g,h=m.camelCase(b),i=a.style;if(b=m.cssProps[h]||(m.cssProps[h]=Ua(i,h)),g=m.cssHooks[b]||m.cssHooks[h],void 0===c)return g&&"get"in g&&void 0!==(e=g.get(a,!1,d))?e:i[b];if(f=typeof c,"string"===f&&(e=Qa.exec(c))&&(c=(e[1]+1)*e[2]+parseFloat(m.css(a,b)),f="number"),null!=c&&c===c&&("number"!==f||m.cssNumber[h]||(c+="px"),k.clearCloneStyle||""!==c||0!==b.indexOf("background")||(i[b]="inherit"),!(g&&"set"in g&&void 0===(c=g.set(a,c,d)))))try{i[b]=c}catch(j){}}},css:function(a,b,c,d){var e,f,g,h=m.camelCase(b);return b=m.cssProps[h]||(m.cssProps[h]=Ua(a.style,h)),g=m.cssHooks[b]||m.cssHooks[h],g&&"get"in g&&(f=g.get(a,!0,c)),void 0===f&&(f=Ja(a,b,d)),"normal"===f&&b in Sa&&(f=Sa[b]),""===c||c?(e=parseFloat(f),c===!0||m.isNumeric(e)?e||0:f):f}}),m.each(["height","width"],function(a,b){m.cssHooks[b]={get:function(a,c,d){return c?Oa.test(m.css(a,"display"))&&0===a.offsetWidth?m.swap(a,Ra,function(){return Ya(a,b,d)}):Ya(a,b,d):void 0},set:function(a,c,d){var e=d&&Ia(a);return Wa(a,c,d?Xa(a,b,d,k.boxSizing&&"border-box"===m.css(a,"boxSizing",!1,e),e):0)}}}),k.opacity||(m.cssHooks.opacity={get:function(a,b){return Na.test((b&&a.currentStyle?a.currentStyle.filter:a.style.filter)||"")?.01*parseFloat(RegExp.$1)+"":b?"1":""},set:function(a,b){var c=a.style,d=a.currentStyle,e=m.isNumeric(b)?"alpha(opacity="+100*b+")":"",f=d&&d.filter||c.filter||"";c.zoom=1,(b>=1||""===b)&&""===m.trim(f.replace(Ma,""))&&c.removeAttribute&&(c.removeAttribute("filter"),""===b||d&&!d.filter)||(c.filter=Ma.test(f)?f.replace(Ma,e):f+" "+e)}}),m.cssHooks.marginRight=La(k.reliableMarginRight,function(a,b){return b?m.swap(a,{display:"inline-block"},Ja,[a,"marginRight"]):void 0}),m.each({margin:"",padding:"",border:"Width"},function(a,b){m.cssHooks[a+b]={expand:function(c){for(var d=0,e={},f="string"==typeof c?c.split(" "):[c];4>d;d++)e[a+T[d]+b]=f[d]||f[d-2]||f[0];return e}},Ga.test(a)||(m.cssHooks[a+b].set=Wa)}),m.fn.extend({css:function(a,b){return V(this,function(a,b,c){var d,e,f={},g=0;if(m.isArray(b)){for(d=Ia(a),e=b.length;e>g;g++)f[b[g]]=m.css(a,b[g],!1,d);return f}return void 0!==c?m.style(a,b,c):m.css(a,b)},a,b,arguments.length>1)},show:function(){return Va(this,!0)},hide:function(){return Va(this)},toggle:function(a){return"boolean"==typeof a?a?this.show():this.hide():this.each(function(){U(this)?m(this).show():m(this).hide()})}});function Za(a,b,c,d,e){
return new Za.prototype.init(a,b,c,d,e)}m.Tween=Za,Za.prototype={constructor:Za,init:function(a,b,c,d,e,f){this.elem=a,this.prop=c,this.easing=e||"swing",this.options=b,this.start=this.now=this.cur(),this.end=d,this.unit=f||(m.cssNumber[c]?"":"px")},cur:function(){var a=Za.propHooks[this.prop];return a&&a.get?a.get(this):Za.propHooks._default.get(this)},run:function(a){var b,c=Za.propHooks[this.prop];return this.options.duration?this.pos=b=m.easing[this.easing](a,this.options.duration*a,0,1,this.options.duration):this.pos=b=a,this.now=(this.end-this.start)*b+this.start,this.options.step&&this.options.step.call(this.elem,this.now,this),c&&c.set?c.set(this):Za.propHooks._default.set(this),this}},Za.prototype.init.prototype=Za.prototype,Za.propHooks={_default:{get:function(a){var b;return null==a.elem[a.prop]||a.elem.style&&null!=a.elem.style[a.prop]?(b=m.css(a.elem,a.prop,""),b&&"auto"!==b?b:0):a.elem[a.prop]},set:function(a){m.fx.step[a.prop]?m.fx.step[a.prop](a):a.elem.style&&(null!=a.elem.style[m.cssProps[a.prop]]||m.cssHooks[a.prop])?m.style(a.elem,a.prop,a.now+a.unit):a.elem[a.prop]=a.now}}},Za.propHooks.scrollTop=Za.propHooks.scrollLeft={set:function(a){a.elem.nodeType&&a.elem.parentNode&&(a.elem[a.prop]=a.now)}},m.easing={linear:function(a){return a},swing:function(a){return.5-Math.cos(a*Math.PI)/2}},m.fx=Za.prototype.init,m.fx.step={};var $a,_a,ab=/^(?:toggle|show|hide)$/,bb=new RegExp("^(?:([+-])=|)("+S+")([a-z%]*)$","i"),cb=/queueHooks$/,db=[ib],eb={"*":[function(a,b){var c=this.createTween(a,b),d=c.cur(),e=bb.exec(b),f=e&&e[3]||(m.cssNumber[a]?"":"px"),g=(m.cssNumber[a]||"px"!==f&&+d)&&bb.exec(m.css(c.elem,a)),h=1,i=20;if(g&&g[3]!==f){f=f||g[3],e=e||[],g=+d||1;do h=h||".5",g/=h,m.style(c.elem,a,g+f);while(h!==(h=c.cur()/d)&&1!==h&&--i)}return e&&(g=c.start=+g||+d||0,c.unit=f,c.end=e[1]?g+(e[1]+1)*e[2]:+e[2]),c}]};function fb(){return setTimeout(function(){$a=void 0}),$a=m.now()}function gb(a,b){var c,d={height:a},e=0;for(b=b?1:0;4>e;e+=2-b)c=T[e],d["margin"+c]=d["padding"+c]=a;return b&&(d.opacity=d.width=a),d}function hb(a,b,c){for(var d,e=(eb[b]||[]).concat(eb["*"]),f=0,g=e.length;g>f;f++)if(d=e[f].call(c,b,a))return d}function ib(a,b,c){var d,e,f,g,h,i,j,l,n=this,o={},p=a.style,q=a.nodeType&&U(a),r=m._data(a,"fxshow");c.queue||(h=m._queueHooks(a,"fx"),null==h.unqueued&&(h.unqueued=0,i=h.empty.fire,h.empty.fire=function(){h.unqueued||i()}),h.unqueued++,n.always(function(){n.always(function(){h.unqueued--,m.queue(a,"fx").length||h.empty.fire()})})),1===a.nodeType&&("height"in b||"width"in b)&&(c.overflow=[p.overflow,p.overflowX,p.overflowY],j=m.css(a,"display"),l="none"===j?m._data(a,"olddisplay")||Fa(a.nodeName):j,"inline"===l&&"none"===m.css(a,"float")&&(k.inlineBlockNeedsLayout&&"inline"!==Fa(a.nodeName)?p.zoom=1:p.display="inline-block")),c.overflow&&(p.overflow="hidden",k.shrinkWrapBlocks()||n.always(function(){p.overflow=c.overflow[0],p.overflowX=c.overflow[1],p.overflowY=c.overflow[2]}));for(d in b)if(e=b[d],ab.exec(e)){if(delete b[d],f=f||"toggle"===e,e===(q?"hide":"show")){if("show"!==e||!r||void 0===r[d])continue;q=!0}o[d]=r&&r[d]||m.style(a,d)}else j=void 0;if(m.isEmptyObject(o))"inline"===("none"===j?Fa(a.nodeName):j)&&(p.display=j);else{r?"hidden"in r&&(q=r.hidden):r=m._data(a,"fxshow",{}),f&&(r.hidden=!q),q?m(a).show():n.done(function(){m(a).hide()}),n.done(function(){var b;m._removeData(a,"fxshow");for(b in o)m.style(a,b,o[b])});for(d in o)g=hb(q?r[d]:0,d,n),d in r||(r[d]=g.start,q&&(g.end=g.start,g.start="width"===d||"height"===d?1:0))}}function jb(a,b){var c,d,e,f,g;for(c in a)if(d=m.camelCase(c),e=b[d],f=a[c],m.isArray(f)&&(e=f[1],f=a[c]=f[0]),c!==d&&(a[d]=f,delete a[c]),g=m.cssHooks[d],g&&"expand"in g){f=g.expand(f),delete a[d];for(c in f)c in a||(a[c]=f[c],b[c]=e)}else b[d]=e}function kb(a,b,c){var d,e,f=0,g=db.length,h=m.Deferred().always(function(){delete i.elem}),i=function(){if(e)return!1;for(var b=$a||fb(),c=Math.max(0,j.startTime+j.duration-b),d=c/j.duration||0,f=1-d,g=0,i=j.tweens.length;i>g;g++)j.tweens[g].run(f);return h.notifyWith(a,[j,f,c]),1>f&&i?c:(h.resolveWith(a,[j]),!1)},j=h.promise({elem:a,props:m.extend({},b),opts:m.extend(!0,{specialEasing:{}},c),originalProperties:b,originalOptions:c,startTime:$a||fb(),duration:c.duration,tweens:[],createTween:function(b,c){var d=m.Tween(a,j.opts,b,c,j.opts.specialEasing[b]||j.opts.easing);return j.tweens.push(d),d},stop:function(b){var c=0,d=b?j.tweens.length:0;if(e)return this;for(e=!0;d>c;c++)j.tweens[c].run(1);return b?h.resolveWith(a,[j,b]):h.rejectWith(a,[j,b]),this}}),k=j.props;for(jb(k,j.opts.specialEasing);g>f;f++)if(d=db[f].call(j,a,k,j.opts))return d;return m.map(k,hb,j),m.isFunction(j.opts.start)&&j.opts.start.call(a,j),m.fx.timer(m.extend(i,{elem:a,anim:j,queue:j.opts.queue})),j.progress(j.opts.progress).done(j.opts.done,j.opts.complete).fail(j.opts.fail).always(j.opts.always)}m.Animation=m.extend(kb,{tweener:function(a,b){m.isFunction(a)?(b=a,a=["*"]):a=a.split(" ");for(var c,d=0,e=a.length;e>d;d++)c=a[d],eb[c]=eb[c]||[],eb[c].unshift(b)},prefilter:function(a,b){b?db.unshift(a):db.push(a)}}),m.speed=function(a,b,c){var d=a&&"object"==typeof a?m.extend({},a):{complete:c||!c&&b||m.isFunction(a)&&a,duration:a,easing:c&&b||b&&!m.isFunction(b)&&b};return d.duration=m.fx.off?0:"number"==typeof d.duration?d.duration:d.duration in m.fx.speeds?m.fx.speeds[d.duration]:m.fx.speeds._default,(null==d.queue||d.queue===!0)&&(d.queue="fx"),d.old=d.complete,d.complete=function(){m.isFunction(d.old)&&d.old.call(this),d.queue&&m.dequeue(this,d.queue)},d},m.fn.extend({fadeTo:function(a,b,c,d){return this.filter(U).css("opacity",0).show().end().animate({opacity:b},a,c,d)},animate:function(a,b,c,d){var e=m.isEmptyObject(a),f=m.speed(b,c,d),g=function(){var b=kb(this,m.extend({},a),f);(e||m._data(this,"finish"))&&b.stop(!0)};return g.finish=g,e||f.queue===!1?this.each(g):this.queue(f.queue,g)},stop:function(a,b,c){var d=function(a){var b=a.stop;delete a.stop,b(c)};return"string"!=typeof a&&(c=b,b=a,a=void 0),b&&a!==!1&&this.queue(a||"fx",[]),this.each(function(){var b=!0,e=null!=a&&a+"queueHooks",f=m.timers,g=m._data(this);if(e)g[e]&&g[e].stop&&d(g[e]);else for(e in g)g[e]&&g[e].stop&&cb.test(e)&&d(g[e]);for(e=f.length;e--;)f[e].elem!==this||null!=a&&f[e].queue!==a||(f[e].anim.stop(c),b=!1,f.splice(e,1));(b||!c)&&m.dequeue(this,a)})},finish:function(a){return a!==!1&&(a=a||"fx"),this.each(function(){var b,c=m._data(this),d=c[a+"queue"],e=c[a+"queueHooks"],f=m.timers,g=d?d.length:0;for(c.finish=!0,m.queue(this,a,[]),e&&e.stop&&e.stop.call(this,!0),b=f.length;b--;)f[b].elem===this&&f[b].queue===a&&(f[b].anim.stop(!0),f.splice(b,1));for(b=0;g>b;b++)d[b]&&d[b].finish&&d[b].finish.call(this);delete c.finish})}}),m.each(["toggle","show","hide"],function(a,b){var c=m.fn[b];m.fn[b]=function(a,d,e){return null==a||"boolean"==typeof a?c.apply(this,arguments):this.animate(gb(b,!0),a,d,e)}}),m.each({slideDown:gb("show"),slideUp:gb("hide"),slideToggle:gb("toggle"),fadeIn:{opacity:"show"},fadeOut:{opacity:"hide"},fadeToggle:{opacity:"toggle"}},function(a,b){m.fn[a]=function(a,c,d){return this.animate(b,a,c,d)}}),m.timers=[],m.fx.tick=function(){var a,b=m.timers,c=0;for($a=m.now();c<b.length;c++)a=b[c],a()||b[c]!==a||b.splice(c--,1);b.length||m.fx.stop(),$a=void 0},m.fx.timer=function(a){m.timers.push(a),a()?m.fx.start():m.timers.pop()},m.fx.interval=13,m.fx.start=function(){_a||(_a=setInterval(m.fx.tick,m.fx.interval))},m.fx.stop=function(){clearInterval(_a),_a=null},m.fx.speeds={slow:600,fast:200,_default:400},m.fn.delay=function(a,b){return a=m.fx?m.fx.speeds[a]||a:a,b=b||"fx",this.queue(b,function(b,c){var d=setTimeout(b,a);c.stop=function(){clearTimeout(d)}})},function(){var a,b,c,d,e;b=y.createElement("div"),b.setAttribute("className","t"),b.innerHTML="  <link/><table></table><a href='/a'>a</a><input type='checkbox'/>",d=b.getElementsByTagName("a")[0],c=y.createElement("select"),e=c.appendChild(y.createElement("option")),a=b.getElementsByTagName("input")[0],d.style.cssText="top:1px",k.getSetAttribute="t"!==b.className,k.style=/top/.test(d.getAttribute("style")),k.hrefNormalized="/a"===d.getAttribute("href"),k.checkOn=!!a.value,k.optSelected=e.selected,k.enctype=!!y.createElement("form").enctype,c.disabled=!0,k.optDisabled=!e.disabled,a=y.createElement("input"),a.setAttribute("value",""),k.input=""===a.getAttribute("value"),a.value="t",a.setAttribute("type","radio"),k.radioValue="t"===a.value}();var lb=/\r/g;m.fn.extend({val:function(a){var b,c,d,e=this[0];{if(arguments.length)return d=m.isFunction(a),this.each(function(c){var e;1===this.nodeType&&(e=d?a.call(this,c,m(this).val()):a,null==e?e="":"number"==typeof e?e+="":m.isArray(e)&&(e=m.map(e,function(a){return null==a?"":a+""})),b=m.valHooks[this.type]||m.valHooks[this.nodeName.toLowerCase()],b&&"set"in b&&void 0!==b.set(this,e,"value")||(this.value=e))});if(e)return b=m.valHooks[e.type]||m.valHooks[e.nodeName.toLowerCase()],b&&"get"in b&&void 0!==(c=b.get(e,"value"))?c:(c=e.value,"string"==typeof c?c.replace(lb,""):null==c?"":c)}}}),m.extend({valHooks:{option:{get:function(a){var b=m.find.attr(a,"value");return null!=b?b:m.trim(m.text(a))}},select:{get:function(a){for(var b,c,d=a.options,e=a.selectedIndex,f="select-one"===a.type||0>e,g=f?null:[],h=f?e+1:d.length,i=0>e?h:f?e:0;h>i;i++)if(c=d[i],!(!c.selected&&i!==e||(k.optDisabled?c.disabled:null!==c.getAttribute("disabled"))||c.parentNode.disabled&&m.nodeName(c.parentNode,"optgroup"))){if(b=m(c).val(),f)return b;g.push(b)}return g},set:function(a,b){var c,d,e=a.options,f=m.makeArray(b),g=e.length;while(g--)if(d=e[g],m.inArray(m.valHooks.option.get(d),f)>=0)try{d.selected=c=!0}catch(h){d.scrollHeight}else d.selected=!1;return c||(a.selectedIndex=-1),e}}}}),m.each(["radio","checkbox"],function(){m.valHooks[this]={set:function(a,b){return m.isArray(b)?a.checked=m.inArray(m(a).val(),b)>=0:void 0}},k.checkOn||(m.valHooks[this].get=function(a){return null===a.getAttribute("value")?"on":a.value})});var mb,nb,ob=m.expr.attrHandle,pb=/^(?:checked|selected)$/i,qb=k.getSetAttribute,rb=k.input;m.fn.extend({attr:function(a,b){return V(this,m.attr,a,b,arguments.length>1)},removeAttr:function(a){return this.each(function(){m.removeAttr(this,a)})}}),m.extend({attr:function(a,b,c){var d,e,f=a.nodeType;if(a&&3!==f&&8!==f&&2!==f)return typeof a.getAttribute===K?m.prop(a,b,c):(1===f&&m.isXMLDoc(a)||(b=b.toLowerCase(),d=m.attrHooks[b]||(m.expr.match.bool.test(b)?nb:mb)),void 0===c?d&&"get"in d&&null!==(e=d.get(a,b))?e:(e=m.find.attr(a,b),null==e?void 0:e):null!==c?d&&"set"in d&&void 0!==(e=d.set(a,c,b))?e:(a.setAttribute(b,c+""),c):void m.removeAttr(a,b))},removeAttr:function(a,b){var c,d,e=0,f=b&&b.match(E);if(f&&1===a.nodeType)while(c=f[e++])d=m.propFix[c]||c,m.expr.match.bool.test(c)?rb&&qb||!pb.test(c)?a[d]=!1:a[m.camelCase("default-"+c)]=a[d]=!1:m.attr(a,c,""),a.removeAttribute(qb?c:d)},attrHooks:{type:{set:function(a,b){if(!k.radioValue&&"radio"===b&&m.nodeName(a,"input")){var c=a.value;return a.setAttribute("type",b),c&&(a.value=c),b}}}}}),nb={set:function(a,b,c){return b===!1?m.removeAttr(a,c):rb&&qb||!pb.test(c)?a.setAttribute(!qb&&m.propFix[c]||c,c):a[m.camelCase("default-"+c)]=a[c]=!0,c}},m.each(m.expr.match.bool.source.match(/\w+/g),function(a,b){var c=ob[b]||m.find.attr;ob[b]=rb&&qb||!pb.test(b)?function(a,b,d){var e,f;return d||(f=ob[b],ob[b]=e,e=null!=c(a,b,d)?b.toLowerCase():null,ob[b]=f),e}:function(a,b,c){return c?void 0:a[m.camelCase("default-"+b)]?b.toLowerCase():null}}),rb&&qb||(m.attrHooks.value={set:function(a,b,c){return m.nodeName(a,"input")?void(a.defaultValue=b):mb&&mb.set(a,b,c)}}),qb||(mb={set:function(a,b,c){var d=a.getAttributeNode(c);return d||a.setAttributeNode(d=a.ownerDocument.createAttribute(c)),d.value=b+="","value"===c||b===a.getAttribute(c)?b:void 0}},ob.id=ob.name=ob.coords=function(a,b,c){var d;return c?void 0:(d=a.getAttributeNode(b))&&""!==d.value?d.value:null},m.valHooks.button={get:function(a,b){var c=a.getAttributeNode(b);return c&&c.specified?c.value:void 0},set:mb.set},m.attrHooks.contenteditable={set:function(a,b,c){mb.set(a,""===b?!1:b,c)}},m.each(["width","height"],function(a,b){m.attrHooks[b]={set:function(a,c){return""===c?(a.setAttribute(b,"auto"),c):void 0}}})),k.style||(m.attrHooks.style={get:function(a){return a.style.cssText||void 0},set:function(a,b){return a.style.cssText=b+""}});var sb=/^(?:input|select|textarea|button|object)$/i,tb=/^(?:a|area)$/i;m.fn.extend({prop:function(a,b){return V(this,m.prop,a,b,arguments.length>1)},removeProp:function(a){return a=m.propFix[a]||a,this.each(function(){try{this[a]=void 0,delete this[a]}catch(b){}})}}),m.extend({propFix:{"for":"htmlFor","class":"className"},prop:function(a,b,c){var d,e,f,g=a.nodeType;if(a&&3!==g&&8!==g&&2!==g)return f=1!==g||!m.isXMLDoc(a),f&&(b=m.propFix[b]||b,e=m.propHooks[b]),void 0!==c?e&&"set"in e&&void 0!==(d=e.set(a,c,b))?d:a[b]=c:e&&"get"in e&&null!==(d=e.get(a,b))?d:a[b]},propHooks:{tabIndex:{get:function(a){var b=m.find.attr(a,"tabindex");return b?parseInt(b,10):sb.test(a.nodeName)||tb.test(a.nodeName)&&a.href?0:-1}}}}),k.hrefNormalized||m.each(["href","src"],function(a,b){m.propHooks[b]={get:function(a){return a.getAttribute(b,4)}}}),k.optSelected||(m.propHooks.selected={get:function(a){var b=a.parentNode;return b&&(b.selectedIndex,b.parentNode&&b.parentNode.selectedIndex),null}}),m.each(["tabIndex","readOnly","maxLength","cellSpacing","cellPadding","rowSpan","colSpan","useMap","frameBorder","contentEditable"],function(){m.propFix[this.toLowerCase()]=this}),k.enctype||(m.propFix.enctype="encoding");var ub=/[\t\r\n\f]/g;m.fn.extend({addClass:function(a){var b,c,d,e,f,g,h=0,i=this.length,j="string"==typeof a&&a;if(m.isFunction(a))return this.each(function(b){m(this).addClass(a.call(this,b,this.className))});if(j)for(b=(a||"").match(E)||[];i>h;h++)if(c=this[h],d=1===c.nodeType&&(c.className?(" "+c.className+" ").replace(ub," "):" ")){f=0;while(e=b[f++])d.indexOf(" "+e+" ")<0&&(d+=e+" ");g=m.trim(d),c.className!==g&&(c.className=g)}return this},removeClass:function(a){var b,c,d,e,f,g,h=0,i=this.length,j=0===arguments.length||"string"==typeof a&&a;if(m.isFunction(a))return this.each(function(b){m(this).removeClass(a.call(this,b,this.className))});if(j)for(b=(a||"").match(E)||[];i>h;h++)if(c=this[h],d=1===c.nodeType&&(c.className?(" "+c.className+" ").replace(ub," "):"")){f=0;while(e=b[f++])while(d.indexOf(" "+e+" ")>=0)d=d.replace(" "+e+" "," ");g=a?m.trim(d):"",c.className!==g&&(c.className=g)}return this},toggleClass:function(a,b){var c=typeof a;return"boolean"==typeof b&&"string"===c?b?this.addClass(a):this.removeClass(a):this.each(m.isFunction(a)?function(c){m(this).toggleClass(a.call(this,c,this.className,b),b)}:function(){if("string"===c){var b,d=0,e=m(this),f=a.match(E)||[];while(b=f[d++])e.hasClass(b)?e.removeClass(b):e.addClass(b)}else(c===K||"boolean"===c)&&(this.className&&m._data(this,"__className__",this.className),this.className=this.className||a===!1?"":m._data(this,"__className__")||"")})},hasClass:function(a){for(var b=" "+a+" ",c=0,d=this.length;d>c;c++)if(1===this[c].nodeType&&(" "+this[c].className+" ").replace(ub," ").indexOf(b)>=0)return!0;return!1}}),m.each("blur focus focusin focusout load resize scroll unload click dblclick mousedown mouseup mousemove mouseover mouseout mouseenter mouseleave change select submit keydown keypress keyup error contextmenu".split(" "),function(a,b){m.fn[b]=function(a,c){return arguments.length>0?this.on(b,null,a,c):this.trigger(b)}}),m.fn.extend({hover:function(a,b){return this.mouseenter(a).mouseleave(b||a)},bind:function(a,b,c){return this.on(a,null,b,c)},unbind:function(a,b){return this.off(a,null,b)},delegate:function(a,b,c,d){return this.on(b,a,c,d)},undelegate:function(a,b,c){return 1===arguments.length?this.off(a,"**"):this.off(b,a||"**",c)}});var vb=m.now(),wb=/\?/,xb=/(,)|(\[|{)|(}|])|"(?:[^"\\\r\n]|\\["\\\/bfnrt]|\\u[\da-fA-F]{4})*"\s*:?|true|false|null|-?(?!0\d)\d+(?:\.\d+|)(?:[eE][+-]?\d+|)/g;m.parseJSON=function(b){if(a.JSON&&a.JSON.parse)return a.JSON.parse(b+"");var c,d=null,e=m.trim(b+"");return e&&!m.trim(e.replace(xb,function(a,b,e,f){return c&&b&&(d=0),0===d?a:(c=e||b,d+=!f-!e,"")}))?Function("return "+e)():m.error("Invalid JSON: "+b)},m.parseXML=function(b){var c,d;if(!b||"string"!=typeof b)return null;try{a.DOMParser?(d=new DOMParser,c=d.parseFromString(b,"text/xml")):(c=new ActiveXObject("Microsoft.XMLDOM"),c.async="false",c.loadXML(b))}catch(e){c=void 0}return c&&c.documentElement&&!c.getElementsByTagName("parsererror").length||m.error("Invalid XML: "+b),c};var yb,zb,Ab=/#.*$/,Bb=/([?&])_=[^&]*/,Cb=/^(.*?):[ \t]*([^\r\n]*)\r?$/gm,Db=/^(?:about|app|app-storage|.+-extension|file|res|widget):$/,Eb=/^(?:GET|HEAD)$/,Fb=/^\/\//,Gb=/^([\w.+-]+:)(?:\/\/(?:[^\/?#]*@|)([^\/?#:]*)(?::(\d+)|)|)/,Hb={},Ib={},Jb="*/".concat("*");try{zb=location.href}catch(Kb){zb=y.createElement("a"),zb.href="",zb=zb.href}yb=Gb.exec(zb.toLowerCase())||[];function Lb(a){return function(b,c){"string"!=typeof b&&(c=b,b="*");var d,e=0,f=b.toLowerCase().match(E)||[];if(m.isFunction(c))while(d=f[e++])"+"===d.charAt(0)?(d=d.slice(1)||"*",(a[d]=a[d]||[]).unshift(c)):(a[d]=a[d]||[]).push(c)}}function Mb(a,b,c,d){var e={},f=a===Ib;function g(h){var i;return e[h]=!0,m.each(a[h]||[],function(a,h){var j=h(b,c,d);return"string"!=typeof j||f||e[j]?f?!(i=j):void 0:(b.dataTypes.unshift(j),g(j),!1)}),i}return g(b.dataTypes[0])||!e["*"]&&g("*")}function Nb(a,b){var c,d,e=m.ajaxSettings.flatOptions||{};for(d in b)void 0!==b[d]&&((e[d]?a:c||(c={}))[d]=b[d]);return c&&m.extend(!0,a,c),a}function Ob(a,b,c){var d,e,f,g,h=a.contents,i=a.dataTypes;while("*"===i[0])i.shift(),void 0===e&&(e=a.mimeType||b.getResponseHeader("Content-Type"));if(e)for(g in h)if(h[g]&&h[g].test(e)){i.unshift(g);break}if(i[0]in c)f=i[0];else{for(g in c){if(!i[0]||a.converters[g+" "+i[0]]){f=g;break}d||(d=g)}f=f||d}return f?(f!==i[0]&&i.unshift(f),c[f]):void 0}function Pb(a,b,c,d){var e,f,g,h,i,j={},k=a.dataTypes.slice();if(k[1])for(g in a.converters)j[g.toLowerCase()]=a.converters[g];f=k.shift();while(f)if(a.responseFields[f]&&(c[a.responseFields[f]]=b),!i&&d&&a.dataFilter&&(b=a.dataFilter(b,a.dataType)),i=f,f=k.shift())if("*"===f)f=i;else if("*"!==i&&i!==f){if(g=j[i+" "+f]||j["* "+f],!g)for(e in j)if(h=e.split(" "),h[1]===f&&(g=j[i+" "+h[0]]||j["* "+h[0]])){g===!0?g=j[e]:j[e]!==!0&&(f=h[0],k.unshift(h[1]));break}if(g!==!0)if(g&&a["throws"])b=g(b);else try{b=g(b)}catch(l){return{state:"parsererror",error:g?l:"No conversion from "+i+" to "+f}}}return{state:"success",data:b}}m.extend({active:0,lastModified:{},etag:{},ajaxSettings:{url:zb,type:"GET",isLocal:Db.test(yb[1]),global:!0,processData:!0,async:!0,contentType:"application/x-www-form-urlencoded; charset=UTF-8",accepts:{"*":Jb,text:"text/plain",html:"text/html",xml:"application/xml, text/xml",json:"application/json, text/javascript"},contents:{xml:/xml/,html:/html/,json:/json/},responseFields:{xml:"responseXML",text:"responseText",json:"responseJSON"},converters:{"* text":String,"text html":!0,"text json":m.parseJSON,"text xml":m.parseXML},flatOptions:{url:!0,context:!0}},ajaxSetup:function(a,b){return b?Nb(Nb(a,m.ajaxSettings),b):Nb(m.ajaxSettings,a)},ajaxPrefilter:Lb(Hb),ajaxTransport:Lb(Ib),ajax:function(a,b){"object"==typeof a&&(b=a,a=void 0),b=b||{};var c,d,e,f,g,h,i,j,k=m.ajaxSetup({},b),l=k.context||k,n=k.context&&(l.nodeType||l.jquery)?m(l):m.event,o=m.Deferred(),p=m.Callbacks("once memory"),q=k.statusCode||{},r={},s={},t=0,u="canceled",v={readyState:0,getResponseHeader:function(a){var b;if(2===t){if(!j){j={};while(b=Cb.exec(f))j[b[1].toLowerCase()]=b[2]}b=j[a.toLowerCase()]}return null==b?null:b},getAllResponseHeaders:function(){return 2===t?f:null},setRequestHeader:function(a,b){var c=a.toLowerCase();return t||(a=s[c]=s[c]||a,r[a]=b),this},overrideMimeType:function(a){return t||(k.mimeType=a),this},statusCode:function(a){var b;if(a)if(2>t)for(b in a)q[b]=[q[b],a[b]];else v.always(a[v.status]);return this},abort:function(a){var b=a||u;return i&&i.abort(b),x(0,b),this}};if(o.promise(v).complete=p.add,v.success=v.done,v.error=v.fail,k.url=((a||k.url||zb)+"").replace(Ab,"").replace(Fb,yb[1]+"//"),k.type=b.method||b.type||k.method||k.type,k.dataTypes=m.trim(k.dataType||"*").toLowerCase().match(E)||[""],null==k.crossDomain&&(c=Gb.exec(k.url.toLowerCase()),k.crossDomain=!(!c||c[1]===yb[1]&&c[2]===yb[2]&&(c[3]||("http:"===c[1]?"80":"443"))===(yb[3]||("http:"===yb[1]?"80":"443")))),k.data&&k.processData&&"string"!=typeof k.data&&(k.data=m.param(k.data,k.traditional)),Mb(Hb,k,b,v),2===t)return v;h=m.event&&k.global,h&&0===m.active++&&m.event.trigger("ajaxStart"),k.type=k.type.toUpperCase(),k.hasContent=!Eb.test(k.type),e=k.url,k.hasContent||(k.data&&(e=k.url+=(wb.test(e)?"&":"?")+k.data,delete k.data),k.cache===!1&&(k.url=Bb.test(e)?e.replace(Bb,"$1_="+vb++):e+(wb.test(e)?"&":"?")+"_="+vb++)),k.ifModified&&(m.lastModified[e]&&v.setRequestHeader("If-Modified-Since",m.lastModified[e]),m.etag[e]&&v.setRequestHeader("If-None-Match",m.etag[e])),(k.data&&k.hasContent&&k.contentType!==!1||b.contentType)&&v.setRequestHeader("Content-Type",k.contentType),v.setRequestHeader("Accept",k.dataTypes[0]&&k.accepts[k.dataTypes[0]]?k.accepts[k.dataTypes[0]]+("*"!==k.dataTypes[0]?", "+Jb+"; q=0.01":""):k.accepts["*"]);for(d in k.headers)v.setRequestHeader(d,k.headers[d]);if(k.beforeSend&&(k.beforeSend.call(l,v,k)===!1||2===t))return v.abort();u="abort";for(d in{success:1,error:1,complete:1})v[d](k[d]);if(i=Mb(Ib,k,b,v)){v.readyState=1,h&&n.trigger("ajaxSend",[v,k]),k.async&&k.timeout>0&&(g=setTimeout(function(){v.abort("timeout")},k.timeout));try{t=1,i.send(r,x)}catch(w){if(!(2>t))throw w;x(-1,w)}}else x(-1,"No Transport");function x(a,b,c,d){var j,r,s,u,w,x=b;2!==t&&(t=2,g&&clearTimeout(g),i=void 0,f=d||"",v.readyState=a>0?4:0,j=a>=200&&300>a||304===a,c&&(u=Ob(k,v,c)),u=Pb(k,u,v,j),j?(k.ifModified&&(w=v.getResponseHeader("Last-Modified"),w&&(m.lastModified[e]=w),w=v.getResponseHeader("etag"),w&&(m.etag[e]=w)),204===a||"HEAD"===k.type?x="nocontent":304===a?x="notmodified":(x=u.state,r=u.data,s=u.error,j=!s)):(s=x,(a||!x)&&(x="error",0>a&&(a=0))),v.status=a,v.statusText=(b||x)+"",j?o.resolveWith(l,[r,x,v]):o.rejectWith(l,[v,x,s]),v.statusCode(q),q=void 0,h&&n.trigger(j?"ajaxSuccess":"ajaxError",[v,k,j?r:s]),p.fireWith(l,[v,x]),h&&(n.trigger("ajaxComplete",[v,k]),--m.active||m.event.trigger("ajaxStop")))}return v},getJSON:function(a,b,c){return m.get(a,b,c,"json")},getScript:function(a,b){return m.get(a,void 0,b,"script")}}),m.each(["get","post"],function(a,b){m[b]=function(a,c,d,e){return m.isFunction(c)&&(e=e||d,d=c,c=void 0),m.ajax({url:a,type:b,dataType:e,data:c,success:d})}}),m._evalUrl=function(a){return m.ajax({url:a,type:"GET",dataType:"script",async:!1,global:!1,"throws":!0})},m.fn.extend({wrapAll:function(a){if(m.isFunction(a))return this.each(function(b){m(this).wrapAll(a.call(this,b))});if(this[0]){var b=m(a,this[0].ownerDocument).eq(0).clone(!0);this[0].parentNode&&b.insertBefore(this[0]),b.map(function(){var a=this;while(a.firstChild&&1===a.firstChild.nodeType)a=a.firstChild;return a}).append(this)}return this},wrapInner:function(a){return this.each(m.isFunction(a)?function(b){m(this).wrapInner(a.call(this,b))}:function(){var b=m(this),c=b.contents();c.length?c.wrapAll(a):b.append(a)})},wrap:function(a){var b=m.isFunction(a);return this.each(function(c){m(this).wrapAll(b?a.call(this,c):a)})},unwrap:function(){return this.parent().each(function(){m.nodeName(this,"body")||m(this).replaceWith(this.childNodes)}).end()}}),m.expr.filters.hidden=function(a){return a.offsetWidth<=0&&a.offsetHeight<=0||!k.reliableHiddenOffsets()&&"none"===(a.style&&a.style.display||m.css(a,"display"))},m.expr.filters.visible=function(a){return!m.expr.filters.hidden(a)};var Qb=/%20/g,Rb=/\[\]$/,Sb=/\r?\n/g,Tb=/^(?:submit|button|image|reset|file)$/i,Ub=/^(?:input|select|textarea|keygen)/i;function Vb(a,b,c,d){var e;if(m.isArray(b))m.each(b,function(b,e){c||Rb.test(a)?d(a,e):Vb(a+"["+("object"==typeof e?b:"")+"]",e,c,d)});else if(c||"object"!==m.type(b))d(a,b);else for(e in b)Vb(a+"["+e+"]",b[e],c,d)}m.param=function(a,b){var c,d=[],e=function(a,b){b=m.isFunction(b)?b():null==b?"":b,d[d.length]=encodeURIComponent(a)+"="+encodeURIComponent(b)};if(void 0===b&&(b=m.ajaxSettings&&m.ajaxSettings.traditional),m.isArray(a)||a.jquery&&!m.isPlainObject(a))m.each(a,function(){e(this.name,this.value)});else for(c in a)Vb(c,a[c],b,e);return d.join("&").replace(Qb,"+")},m.fn.extend({serialize:function(){return m.param(this.serializeArray())},serializeArray:function(){return this.map(function(){var a=m.prop(this,"elements");return a?m.makeArray(a):this}).filter(function(){var a=this.type;return this.name&&!m(this).is(":disabled")&&Ub.test(this.nodeName)&&!Tb.test(a)&&(this.checked||!W.test(a))}).map(function(a,b){var c=m(this).val();return null==c?null:m.isArray(c)?m.map(c,function(a){return{name:b.name,value:a.replace(Sb,"\r\n")}}):{name:b.name,value:c.replace(Sb,"\r\n")}}).get()}}),m.ajaxSettings.xhr=void 0!==a.ActiveXObject?function(){return!this.isLocal&&/^(get|post|head|put|delete|options)$/i.test(this.type)&&Zb()||$b()}:Zb;var Wb=0,Xb={},Yb=m.ajaxSettings.xhr();a.attachEvent&&a.attachEvent("onunload",function(){for(var a in Xb)Xb[a](void 0,!0)}),k.cors=!!Yb&&"withCredentials"in Yb,Yb=k.ajax=!!Yb,Yb&&m.ajaxTransport(function(a){if(!a.crossDomain||k.cors){var b;return{send:function(c,d){var e,f=a.xhr(),g=++Wb;if(f.open(a.type,a.url,a.async,a.username,a.password),a.xhrFields)for(e in a.xhrFields)f[e]=a.xhrFields[e];a.mimeType&&f.overrideMimeType&&f.overrideMimeType(a.mimeType),a.crossDomain||c["X-Requested-With"]||(c["X-Requested-With"]="XMLHttpRequest");for(e in c)void 0!==c[e]&&f.setRequestHeader(e,c[e]+"");f.send(a.hasContent&&a.data||null),b=function(c,e){var h,i,j;if(b&&(e||4===f.readyState))if(delete Xb[g],b=void 0,f.onreadystatechange=m.noop,e)4!==f.readyState&&f.abort();else{j={},h=f.status,"string"==typeof f.responseText&&(j.text=f.responseText);try{i=f.statusText}catch(k){i=""}h||!a.isLocal||a.crossDomain?1223===h&&(h=204):h=j.text?200:404}j&&d(h,i,j,f.getAllResponseHeaders())},a.async?4===f.readyState?setTimeout(b):f.onreadystatechange=Xb[g]=b:b()},abort:function(){b&&b(void 0,!0)}}}});function Zb(){try{return new a.XMLHttpRequest}catch(b){}}function $b(){try{return new a.ActiveXObject("Microsoft.XMLHTTP")}catch(b){}}m.ajaxSetup({accepts:{script:"text/javascript, application/javascript, application/ecmascript, application/x-ecmascript"},contents:{script:/(?:java|ecma)script/},converters:{"text script":function(a){return m.globalEval(a),a}}}),m.ajaxPrefilter("script",function(a){void 0===a.cache&&(a.cache=!1),a.crossDomain&&(a.type="GET",a.global=!1)}),m.ajaxTransport("script",function(a){if(a.crossDomain){var b,c=y.head||m("head")[0]||y.documentElement;return{send:function(d,e){b=y.createElement("script"),b.async=!0,a.scriptCharset&&(b.charset=a.scriptCharset),b.src=a.url,b.onload=b.onreadystatechange=function(a,c){(c||!b.readyState||/loaded|complete/.test(b.readyState))&&(b.onload=b.onreadystatechange=null,b.parentNode&&b.parentNode.removeChild(b),b=null,c||e(200,"success"))},c.insertBefore(b,c.firstChild)},abort:function(){b&&b.onload(void 0,!0)}}}});var _b=[],ac=/(=)\?(?=&|$)|\?\?/;m.ajaxSetup({jsonp:"callback",jsonpCallback:function(){var a=_b.pop()||m.expando+"_"+vb++;return this[a]=!0,a}}),m.ajaxPrefilter("json jsonp",function(b,c,d){var e,f,g,h=b.jsonp!==!1&&(ac.test(b.url)?"url":"string"==typeof b.data&&!(b.contentType||"").indexOf("application/x-www-form-urlencoded")&&ac.test(b.data)&&"data");return h||"jsonp"===b.dataTypes[0]?(e=b.jsonpCallback=m.isFunction(b.jsonpCallback)?b.jsonpCallback():b.jsonpCallback,h?b[h]=b[h].replace(ac,"$1"+e):b.jsonp!==!1&&(b.url+=(wb.test(b.url)?"&":"?")+b.jsonp+"="+e),b.converters["script json"]=function(){return g||m.error(e+" was not called"),g[0]},b.dataTypes[0]="json",f=a[e],a[e]=function(){g=arguments},d.always(function(){a[e]=f,b[e]&&(b.jsonpCallback=c.jsonpCallback,_b.push(e)),g&&m.isFunction(f)&&f(g[0]),g=f=void 0}),"script"):void 0}),m.parseHTML=function(a,b,c){if(!a||"string"!=typeof a)return null;"boolean"==typeof b&&(c=b,b=!1),b=b||y;var d=u.exec(a),e=!c&&[];return d?[b.createElement(d[1])]:(d=m.buildFragment([a],b,e),e&&e.length&&m(e).remove(),m.merge([],d.childNodes))};var bc=m.fn.load;m.fn.load=function(a,b,c){if("string"!=typeof a&&bc)return bc.apply(this,arguments);var d,e,f,g=this,h=a.indexOf(" ");return h>=0&&(d=m.trim(a.slice(h,a.length)),a=a.slice(0,h)),m.isFunction(b)?(c=b,b=void 0):b&&"object"==typeof b&&(f="POST"),g.length>0&&m.ajax({url:a,type:f,dataType:"html",data:b}).done(function(a){e=arguments,g.html(d?m("<div>").append(m.parseHTML(a)).find(d):a)}).complete(c&&function(a,b){g.each(c,e||[a.responseText,b,a])}),this},m.each(["ajaxStart","ajaxStop","ajaxComplete","ajaxError","ajaxSuccess","ajaxSend"],function(a,b){m.fn[b]=function(a){return this.on(b,a)}}),m.expr.filters.animated=function(a){return m.grep(m.timers,function(b){return a===b.elem}).length};var cc=a.document.documentElement;function dc(a){return m.isWindow(a)?a:9===a.nodeType?a.defaultView||a.parentWindow:!1}m.offset={setOffset:function(a,b,c){var d,e,f,g,h,i,j,k=m.css(a,"position"),l=m(a),n={};"static"===k&&(a.style.position="relative"),h=l.offset(),f=m.css(a,"top"),i=m.css(a,"left"),j=("absolute"===k||"fixed"===k)&&m.inArray("auto",[f,i])>-1,j?(d=l.position(),g=d.top,e=d.left):(g=parseFloat(f)||0,e=parseFloat(i)||0),m.isFunction(b)&&(b=b.call(a,c,h)),null!=b.top&&(n.top=b.top-h.top+g),null!=b.left&&(n.left=b.left-h.left+e),"using"in b?b.using.call(a,n):l.css(n)}},m.fn.extend({offset:function(a){if(arguments.length)return void 0===a?this:this.each(function(b){m.offset.setOffset(this,a,b)});var b,c,d={top:0,left:0},e=this[0],f=e&&e.ownerDocument;if(f)return b=f.documentElement,m.contains(b,e)?(typeof e.getBoundingClientRect!==K&&(d=e.getBoundingClientRect()),c=dc(f),{top:d.top+(c.pageYOffset||b.scrollTop)-(b.clientTop||0),left:d.left+(c.pageXOffset||b.scrollLeft)-(b.clientLeft||0)}):d},position:function(){if(this[0]){var a,b,c={top:0,left:0},d=this[0];return"fixed"===m.css(d,"position")?b=d.getBoundingClientRect():(a=this.offsetParent(),b=this.offset(),m.nodeName(a[0],"html")||(c=a.offset()),c.top+=m.css(a[0],"borderTopWidth",!0),c.left+=m.css(a[0],"borderLeftWidth",!0)),{top:b.top-c.top-m.css(d,"marginTop",!0),left:b.left-c.left-m.css(d,"marginLeft",!0)}}},offsetParent:function(){return this.map(function(){var a=this.offsetParent||cc;while(a&&!m.nodeName(a,"html")&&"static"===m.css(a,"position"))a=a.offsetParent;return a||cc})}}),m.each({scrollLeft:"pageXOffset",scrollTop:"pageYOffset"},function(a,b){var c=/Y/.test(b);m.fn[a]=function(d){return V(this,function(a,d,e){var f=dc(a);return void 0===e?f?b in f?f[b]:f.document.documentElement[d]:a[d]:void(f?f.scrollTo(c?m(f).scrollLeft():e,c?e:m(f).scrollTop()):a[d]=e)},a,d,arguments.length,null)}}),m.each(["top","left"],function(a,b){m.cssHooks[b]=La(k.pixelPosition,function(a,c){return c?(c=Ja(a,b),Ha.test(c)?m(a).position()[b]+"px":c):void 0})}),m.each({Height:"height",Width:"width"},function(a,b){m.each({padding:"inner"+a,content:b,"":"outer"+a},function(c,d){m.fn[d]=function(d,e){var f=arguments.length&&(c||"boolean"!=typeof d),g=c||(d===!0||e===!0?"margin":"border");return V(this,function(b,c,d){var e;return m.isWindow(b)?b.document.documentElement["client"+a]:9===b.nodeType?(e=b.documentElement,Math.max(b.body["scroll"+a],e["scroll"+a],b.body["offset"+a],e["offset"+a],e["client"+a])):void 0===d?m.css(b,c,g):m.style(b,c,d,g)},b,f?d:void 0,f,null)}})}),m.fn.size=function(){return this.length},m.fn.andSelf=m.fn.addBack,"function"==typeof define&&define.amd&&define("jquery",[],function(){return m});var ec=a.jQuery,fc=a.$;return m.noConflict=function(b){return a.$===m&&(a.$=fc),b&&a.jQuery===m&&(a.jQuery=ec),m},typeof b===K&&(a.jQuery=a.$=m),m});

jQuery.easing.jswing=jQuery.easing.swing;jQuery.extend(jQuery.easing,{def:"easeOutQuad",swing:function(e,f,a,h,g){return jQuery.easing[jQuery.easing.def](e,f,a,h,g)},easeInQuad:function(e,f,a,h,g){return h*(f/=g)*f+a},easeOutQuad:function(e,f,a,h,g){return -h*(f/=g)*(f-2)+a},easeInOutQuad:function(e,f,a,h,g){if((f/=g/2)<1){return h/2*f*f+a}return -h/2*((--f)*(f-2)-1)+a},easeInCubic:function(e,f,a,h,g){return h*(f/=g)*f*f+a},easeOutCubic:function(e,f,a,h,g){return h*((f=f/g-1)*f*f+1)+a},easeInOutCubic:function(e,f,a,h,g){if((f/=g/2)<1){return h/2*f*f*f+a}return h/2*((f-=2)*f*f+2)+a},easeInQuart:function(e,f,a,h,g){return h*(f/=g)*f*f*f+a},easeOutQuart:function(e,f,a,h,g){return -h*((f=f/g-1)*f*f*f-1)+a},easeInOutQuart:function(e,f,a,h,g){if((f/=g/2)<1){return h/2*f*f*f*f+a}return -h/2*((f-=2)*f*f*f-2)+a},easeInQuint:function(e,f,a,h,g){return h*(f/=g)*f*f*f*f+a},easeOutQuint:function(e,f,a,h,g){return h*((f=f/g-1)*f*f*f*f+1)+a},easeInOutQuint:function(e,f,a,h,g){if((f/=g/2)<1){return h/2*f*f*f*f*f+a}return h/2*((f-=2)*f*f*f*f+2)+a},easeInSine:function(e,f,a,h,g){return -h*Math.cos(f/g*(Math.PI/2))+h+a},easeOutSine:function(e,f,a,h,g){return h*Math.sin(f/g*(Math.PI/2))+a},easeInOutSine:function(e,f,a,h,g){return -h/2*(Math.cos(Math.PI*f/g)-1)+a},easeInExpo:function(e,f,a,h,g){return(f==0)?a:h*Math.pow(2,10*(f/g-1))+a},easeOutExpo:function(e,f,a,h,g){return(f==g)?a+h:h*(-Math.pow(2,-10*f/g)+1)+a},easeInOutExpo:function(e,f,a,h,g){if(f==0){return a}if(f==g){return a+h}if((f/=g/2)<1){return h/2*Math.pow(2,10*(f-1))+a}return h/2*(-Math.pow(2,-10*--f)+2)+a},easeInCirc:function(e,f,a,h,g){return -h*(Math.sqrt(1-(f/=g)*f)-1)+a},easeOutCirc:function(e,f,a,h,g){return h*Math.sqrt(1-(f=f/g-1)*f)+a},easeInOutCirc:function(e,f,a,h,g){if((f/=g/2)<1){return -h/2*(Math.sqrt(1-f*f)-1)+a}return h/2*(Math.sqrt(1-(f-=2)*f)+1)+a},easeInElastic:function(f,h,e,l,k){var i=1.70158;var j=0;var g=l;if(h==0){return e}if((h/=k)==1){return e+l}if(!j){j=k*0.3}if(g<Math.abs(l)){g=l;var i=j/4}else{var i=j/(2*Math.PI)*Math.asin(l/g)}return -(g*Math.pow(2,10*(h-=1))*Math.sin((h*k-i)*(2*Math.PI)/j))+e},easeOutElastic:function(f,h,e,l,k){var i=1.70158;var j=0;var g=l;if(h==0){return e}if((h/=k)==1){return e+l}if(!j){j=k*0.3}if(g<Math.abs(l)){g=l;var i=j/4}else{var i=j/(2*Math.PI)*Math.asin(l/g)}return g*Math.pow(2,-10*h)*Math.sin((h*k-i)*(2*Math.PI)/j)+l+e},easeInOutElastic:function(f,h,e,l,k){var i=1.70158;var j=0;var g=l;if(h==0){return e}if((h/=k/2)==2){return e+l}if(!j){j=k*(0.3*1.5)}if(g<Math.abs(l)){g=l;var i=j/4}else{var i=j/(2*Math.PI)*Math.asin(l/g)}if(h<1){return -0.5*(g*Math.pow(2,10*(h-=1))*Math.sin((h*k-i)*(2*Math.PI)/j))+e}return g*Math.pow(2,-10*(h-=1))*Math.sin((h*k-i)*(2*Math.PI)/j)*0.5+l+e},easeInBack:function(e,f,a,i,h,g){if(g==undefined){g=1.70158}return i*(f/=h)*f*((g+1)*f-g)+a},easeOutBack:function(e,f,a,i,h,g){if(g==undefined){g=1.70158}return i*((f=f/h-1)*f*((g+1)*f+g)+1)+a},easeInOutBack:function(e,f,a,i,h,g){if(g==undefined){g=1.70158}if((f/=h/2)<1){return i/2*(f*f*(((g*=(1.525))+1)*f-g))+a}return i/2*((f-=2)*f*(((g*=(1.525))+1)*f+g)+2)+a},easeInBounce:function(e,f,a,h,g){return h-jQuery.easing.easeOutBounce(e,g-f,0,h,g)+a},easeOutBounce:function(e,f,a,h,g){if((f/=g)<(1/2.75)){return h*(7.5625*f*f)+a}else{if(f<(2/2.75)){return h*(7.5625*(f-=(1.5/2.75))*f+0.75)+a}else{if(f<(2.5/2.75)){return h*(7.5625*(f-=(2.25/2.75))*f+0.9375)+a}else{return h*(7.5625*(f-=(2.625/2.75))*f+0.984375)+a}}}},easeInOutBounce:function(e,f,a,h,g){if(f<g/2){return jQuery.easing.easeInBounce(e,f*2,0,h,g)*0.5+a}return jQuery.easing.easeOutBounce(e,f*2-g,0,h,g)*0.5+h*0.5+a}});

/* Asynchronously write javascript, even with document.write., v1.3.2 https://krux.github.io/postscribe
Copyright (c) 2014 Derek Brans, MIT license https://github.com/krux/postscribe/blob/master/LICENSE */
!function(){function a(a,h){a=a||"",h=h||{};for(var i in b)b.hasOwnProperty(i)&&(h.autoFix&&(h["fix_"+i]=!0),h.fix=h.fix||h["fix_"+i]);var j=[],k=document.createElement("div"),l=function(a){return"string"==typeof a&&-1!==a.indexOf("&")?(k.innerHTML=a,k.textContent||k.innerText||a):a},m=function(b){a+=b},n=function(b){a=b+a},o={comment:/^<!--/,endTag:/^<\//,atomicTag:/^<\s*(script|style|noscript|iframe|textarea)[\s\/>]/i,startTag:/^</,chars:/^[^<]/},p={comment:function(){var b=a.indexOf("-->");return b>=0?{content:a.substr(4,b),length:b+3}:void 0},endTag:function(){var b=a.match(d);return b?{tagName:b[1],length:b[0].length}:void 0},atomicTag:function(){var b=p.startTag();if(b){var c=a.slice(b.length);if(c.match(new RegExp("</\\s*"+b.tagName+"\\s*>","i"))){var d=c.match(new RegExp("([\\s\\S]*?)</\\s*"+b.tagName+"\\s*>","i"));if(d)return{tagName:b.tagName,attrs:b.attrs,content:d[1],length:d[0].length+b.length}}}},startTag:function(){var b=a.indexOf(">");if(-1===b)return null;var d=a.match(c);if(d){var g={};return d[2].replace(e,function(a,b){var c=arguments[2]||arguments[3]||arguments[4]||f.test(b)&&b||null;g[b]=l(c)}),{tagName:d[1],attrs:g,unary:!!d[3],length:d[0].length}}},chars:function(){var b=a.indexOf("<");return{length:b>=0?b:a.length}}},q=function(){for(var b in o)if(o[b].test(a)){g&&console.log("suspected "+b);var c=p[b]();return c?(g&&console.log("parsed "+b,c),c.type=c.type||b,c.text=a.substr(0,c.length),a=a.slice(c.length),c):null}},r=function(a){for(var b;b=q();)if(a[b.type]&&a[b.type](b)===!1)return},s=function(){var b=a;return a="",b},t=function(){return a};return h.fix&&!function(){var b=/^(AREA|BASE|BASEFONT|BR|COL|FRAME|HR|IMG|INPUT|ISINDEX|LINK|META|PARAM|EMBED)$/i,c=/^(COLGROUP|DD|DT|LI|OPTIONS|P|TD|TFOOT|TH|THEAD|TR)$/i,d=[];d.last=function(){return this[this.length-1]},d.lastTagNameEq=function(a){var b=this.last();return b&&b.tagName&&b.tagName.toUpperCase()===a.toUpperCase()},d.containsTagName=function(a){for(var b,c=0;b=this[c];c++)if(b.tagName===a)return!0;return!1};var e=function(a){return a&&"startTag"===a.type&&(a.unary=b.test(a.tagName)||a.unary),a},f=q,g=function(){var b=a,c=e(f());return a=b,c},i=function(){var a=d.pop();n("</"+a.tagName+">")},j={startTag:function(a){var b=a.tagName;"TR"===b.toUpperCase()&&d.lastTagNameEq("TABLE")?(n("<TBODY>"),l()):h.fix_selfClose&&c.test(b)&&d.containsTagName(b)?d.lastTagNameEq(b)?i():(n("</"+a.tagName+">"),l()):a.unary||d.push(a)},endTag:function(a){var b=d.last();b?h.fix_tagSoup&&!d.lastTagNameEq(a.tagName)?i():d.pop():h.fix_tagSoup&&k()}},k=function(){f(),l()},l=function(){var a=g();a&&j[a.type]&&j[a.type](a)};q=function(){return l(),e(f())}}(),{append:m,readToken:q,readTokens:r,clear:s,rest:t,stack:j}}var b=function(){var a,b={},c=this.document.createElement("div");return a="<P><I></P></I>",c.innerHTML=a,b.tagSoup=c.innerHTML!==a,c.innerHTML="<P><i><P></P></i></P>",b.selfClose=2===c.childNodes.length,b}(),c=/^<([\-A-Za-z0-9_]+)((?:\s+[\w\-]+(?:\s*=?\s*(?:(?:"[^"]*")|(?:'[^']*')|[^>\s]+))?)*)\s*(\/?)>/,d=/^<\/([\-A-Za-z0-9_]+)[^>]*>/,e=/([\-A-Za-z0-9_]+)(?:\s*=\s*(?:(?:"((?:\\.|[^"])*)")|(?:'((?:\\.|[^'])*)')|([^>\s]+)))?/g,f=/^(checked|compact|declare|defer|disabled|ismap|multiple|nohref|noresize|noshade|nowrap|readonly|selected)$/i,g=!1;a.supports=b,a.tokenToString=function(a){var b={comment:function(a){return"<--"+a.content+"-->"},endTag:function(a){return"</"+a.tagName+">"},atomicTag:function(a){return console.log(a),b.startTag(a)+a.content+b.endTag(a)},startTag:function(a){var b="<"+a.tagName;for(var c in a.attrs){var d=a.attrs[c];b+=" "+c+'="'+(d?d.replace(/(^|[^\\])"/g,'$1\\"'):"")+'"'}return b+(a.unary?"/>":">")},chars:function(a){return a.text}};return b[a.type](a)},a.escapeAttributes=function(a){var b={};for(var c in a){var d=a[c];b[c]=d&&d.replace(/(^|[^\\])"/g,'$1\\"')}return b};for(var h in b)a.browserHasFlaw=a.browserHasFlaw||!b[h]&&h;this.htmlParser=a}(),function(){function a(){}function b(a){return a!==m&&null!==a}function c(a){return"function"==typeof a}function d(a,b,c){var d,e=a&&a.length||0;for(d=0;e>d;d++)b.call(c,a[d],d)}function e(a,b,c){var d;for(d in a)a.hasOwnProperty(d)&&b.call(c,d,a[d])}function f(a,b){return e(b,function(b,c){a[b]=c}),a}function g(a,c){return a=a||{},e(c,function(c,d){b(a[c])||(a[c]=d)}),a}function h(a){try{return o.call(a)}catch(b){var c=[];return d(a,function(a){c.push(a)}),c}}function i(a){return a&&"tagName"in a?!!~a.tagName.toLowerCase().indexOf("script"):!1}function j(a){return a&&"tagName"in a?!!~a.tagName.toLowerCase().indexOf("style"):!1}var k={afterAsync:a,afterDequeue:a,afterStreamStart:a,afterWrite:a,beforeEnqueue:a,beforeWrite:function(a){return a},done:a,error:function(a){throw a},releaseAsync:!1},l=this,m=void 0;if(!l.postscribe){var n=!1,o=Array.prototype.slice,p=function(a){return a[a.length-1]},q=function(){function a(a,c,d){var e=k+c;if(2===arguments.length){var f=a.getAttribute(e);return b(f)?String(f):f}b(d)&&""!==d?a.setAttribute(e,d):a.removeAttribute(e)}function g(b,c){var d=b.ownerDocument;f(this,{root:b,options:c,win:d.defaultView||d.parentWindow,doc:d,parser:htmlParser("",{autoFix:!0}),actuals:[b],proxyHistory:"",proxyRoot:d.createElement(b.nodeName),scriptStack:[],writeQueue:[]}),a(this.proxyRoot,"proxyof",0)}var k="data-ps-";return g.prototype.write=function(){[].push.apply(this.writeQueue,arguments);for(var a;!this.deferredRemote&&this.writeQueue.length;)a=this.writeQueue.shift(),c(a)?this.callFunction(a):this.writeImpl(a)},g.prototype.callFunction=function(a){var b={type:"function",value:a.name||a.toString()};this.onScriptStart(b),a.call(this.win,this.doc),this.onScriptDone(b)},g.prototype.writeImpl=function(a){this.parser.append(a);for(var b,c,d,e=[];(b=this.parser.readToken())&&!(c=i(b))&&!(d=j(b));)e.push(b);this.writeStaticTokens(e),c&&this.handleScriptToken(b),d&&this.handleStyleToken(b)},g.prototype.writeStaticTokens=function(a){var b=this.buildChunk(a);if(b.actual)return b.html=this.proxyHistory+b.actual,this.proxyHistory+=b.proxy,this.proxyRoot.innerHTML=b.html,n&&(b.proxyInnerHTML=this.proxyRoot.innerHTML),this.walkChunk(),n&&(b.actualInnerHTML=this.root.innerHTML),b},g.prototype.buildChunk=function(a){var b=this.actuals.length,c=[],e=[],f=[];return d(a,function(a){if(c.push(a.text),a.attrs){if(!/^noscript$/i.test(a.tagName)){var d=b++;e.push(a.text.replace(/(\/?>)/," "+k+"id="+d+" $1")),"ps-script"!==a.attrs.id&&"ps-style"!==a.attrs.id&&f.push("atomicTag"===a.type?"":"<"+a.tagName+" "+k+"proxyof="+d+(a.unary?" />":">"))}}else e.push(a.text),f.push("endTag"===a.type?a.text:"")}),{tokens:a,raw:c.join(""),actual:e.join(""),proxy:f.join("")}},g.prototype.walkChunk=function(){for(var c,d=[this.proxyRoot];b(c=d.shift());){var e=1===c.nodeType,f=e&&a(c,"proxyof");if(!f){e&&(this.actuals[a(c,"id")]=c,a(c,"id",null));var g=c.parentNode&&a(c.parentNode,"proxyof");g&&this.actuals[g].appendChild(c)}d.unshift.apply(d,h(c.childNodes))}},g.prototype.handleScriptToken=function(a){var b=this.parser.clear();b&&this.writeQueue.unshift(b),a.src=a.attrs.src||a.attrs.SRC,a.src&&this.scriptStack.length?this.deferredRemote=a:this.onScriptStart(a);var c=this;this.writeScriptToken(a,function(){c.onScriptDone(a)})},g.prototype.handleStyleToken=function(a){var b=this.parser.clear();b&&this.writeQueue.unshift(b),a.type=a.attrs.type||a.attrs.TYPE||"text/css",this.writeStyleToken(a),b&&this.write()},g.prototype.writeStyleToken=function(a){var b=this.buildStyle(a);this.insertStyle(b),a.content&&(b.styleSheet&&!b.sheet?b.styleSheet.cssText=a.content:b.appendChild(this.doc.createTextNode(a.content)))},g.prototype.buildStyle=function(a){var b=this.doc.createElement(a.tagName);return b.setAttribute("type",a.type),e(a.attrs,function(a,c){b.setAttribute(a,c)}),b},g.prototype.insertStyle=function(a){this.writeImpl('<span id="ps-style"/>');var b=this.doc.getElementById("ps-style");b.parentNode.replaceChild(a,b)},g.prototype.onScriptStart=function(a){a.outerWrites=this.writeQueue,this.writeQueue=[],this.scriptStack.unshift(a)},g.prototype.onScriptDone=function(a){return a!==this.scriptStack[0]?void this.options.error({message:"Bad script nesting or script finished twice"}):(this.scriptStack.shift(),this.write.apply(this,a.outerWrites),void(!this.scriptStack.length&&this.deferredRemote&&(this.onScriptStart(this.deferredRemote),this.deferredRemote=null)))},g.prototype.writeScriptToken=function(a,b){var c=this.buildScript(a),d=this.shouldRelease(c),e=this.options.afterAsync;a.src&&(c.src=a.src,this.scriptLoadHandler(c,d?e:function(){b(),e()}));try{this.insertScript(c),(!a.src||d)&&b()}catch(f){this.options.error(f),b()}},g.prototype.buildScript=function(a){var b=this.doc.createElement(a.tagName);return e(a.attrs,function(a,c){b.setAttribute(a,c)}),a.content&&(b.text=a.content),b},g.prototype.insertScript=function(a){this.writeImpl('<span id="ps-script"/>');var b=this.doc.getElementById("ps-script");b.parentNode.replaceChild(a,b)},g.prototype.scriptLoadHandler=function(a,b){function c(){a=a.onload=a.onreadystatechange=a.onerror=null}function d(){c(),b()}function e(a){c(),g(a),b()}var g=this.options.error;f(a,{onload:function(){d()},onreadystatechange:function(){/^(loaded|complete)$/.test(a.readyState)&&d()},onerror:function(){e({message:"remote script failed "+a.src})}})},g.prototype.shouldRelease=function(a){var b=/^script$/i.test(a.nodeName);return!b||!!(this.options.releaseAsync&&a.src&&a.hasAttribute("async"))},g}();l.postscribe=function(){function b(){var a,b=j.shift();b&&(a=p(b),a.afterDequeue(),b.stream=d.apply(null,b),a.afterStreamStart())}function d(c,d,g){function j(a){a=g.beforeWrite(a),m.write(a),g.afterWrite(a)}m=new q(c,g),m.id=i++,m.name=g.name||m.id,e.streams[m.name]=m;var k=c.ownerDocument,l={close:k.close,open:k.open,write:k.write,writeln:k.writeln};f(k,{close:a,open:a,write:function(){return j(h(arguments).join(""))},writeln:function(){return j(h(arguments).join("")+"\n")}});var n=m.win.onerror||a;return m.win.onerror=function(a,b,c){g.error({msg:a+" - "+b+":"+c}),n.apply(m.win,arguments)},m.write(d,function(){f(k,l),m.win.onerror=n,g.done(),m=null,b()}),m}function e(d,e,f){c(f)&&(f={done:f}),f=g(f,k),d=/^#/.test(d)?l.document.getElementById(d.substr(1)):d.jquery?d[0]:d;var h=[d,e,f];return d.postscribe={cancel:function(){h.stream?h.stream.abort():h[1]=a}},f.beforeEnqueue(h),j.push(h),m||b(),d.postscribe}var i=0,j=[],m=null;return f(e,{streams:{},queue:j,WriteStream:q})}()}}();

//Sharrre 1.3.5 by Julien Hany https://github.com/Julienh/Sharrre
!function(t,o,n,i){function a(e,o){this.element=e,this.options=t.extend(!0,{},l,o),this.options.share=o.share,this._defaults=l,this._name=r,this.init()}var r="sharrre",l={className:"sharrre",share:{googlePlus:!1,facebook:!1,twitter:!1,digg:!1,delicious:!1,stumbleupon:!1,linkedin:!1,pinterest:!1},shareTotal:0,template:"",title:"",url:n.location.href,text:n.title,urlCurl:"sharrre.php",count:{},total:0,shorterTotal:!0,enableHover:!0,enableCounter:!0,enableTracking:!1,hover:function(){},hide:function(){},click:function(){},render:function(){},buttons:{googlePlus:{url:"",urlCount:!1,size:"medium",lang:"en-US",annotation:""},facebook:{url:"",urlCount:!1,action:"like",layout:"button_count",width:"",send:"false",faces:"false",colorscheme:"",font:"",lang:"en_US"},twitter:{url:"",urlCount:!1,count:"horizontal",hashtags:"",via:"",related:"",lang:"en"},digg:{url:"",urlCount:!1,type:"DiggCompact"},delicious:{url:"",urlCount:!1,size:"medium"},stumbleupon:{url:"",urlCount:!1,layout:"1"},linkedin:{url:"",urlCount:!1,counter:""},pinterest:{url:"",media:"",description:"",layout:"horizontal"}}},u={googlePlus:"",facebook:"https://graph.facebook.com/fql?q=SELECT%20url,%20normalized_url,%20share_count,%20like_count,%20comment_count,%20total_count,commentsbox_count,%20comments_fbid,%20click_count%20FROM%20link_stat%20WHERE%20url=%27{url}%27&callback=?",twitter:"http://opensharecount.com/count.json?url={url}",digg:"http://services.digg.com/2.0/story.getInfo?links={url}&type=javascript&callback=?",delicious:"http://feeds.delicious.com/v2/json/urlinfo/data?url={url}&callback=?",stumbleupon:"",linkedin:"http://www.linkedin.com/countserv/count/share?format=jsonp&url={url}&callback=?",pinterest:"http://api.pinterest.com/v1/urls/count.json?url={url}&callback=?"},c={googlePlus:function(e){var i=e.options.buttons.googlePlus;t(e.element).find(".buttons").append('<div class="button googleplus"><div class="g-plusone" data-size="'+i.size+'" data-href="'+(""!==i.url?i.url:e.options.url)+'" data-annotation="'+i.annotation+'"></div></div>'),o.___gcfg={lang:e.options.buttons.googlePlus.lang};var s=0;"undefined"==typeof gapi&&0==s?(s=1,function(){var t=n.createElement("script");t.type="text/javascript",t.async=!0,t.src="//apis.google.com/js/plusone.js";var e=n.getElementsByTagName("script")[0];e.parentNode.insertBefore(t,e)}()):gapi.plusone.go()},facebook:function(e){var o=e.options.buttons.facebook;t(e.element).find(".buttons").append('<div class="button facebook"><div id="fb-root"></div><div class="fb-like" data-href="'+(""!==o.url?o.url:e.options.url)+'" data-send="'+o.send+'" data-layout="'+o.layout+'" data-width="'+o.width+'" data-show-faces="'+o.faces+'" data-action="'+o.action+'" data-colorscheme="'+o.colorscheme+'" data-font="'+o.font+'" data-via="'+o.via+'"></div></div>');var i=0;"undefined"==typeof FB&&0==i?(i=1,function(t,e,n){var i,s=t.getElementsByTagName(e)[0];t.getElementById(n)||(i=t.createElement(e),i.id=n,i.src="//connect.facebook.net/"+o.lang+"/all.js#xfbml=1",s.parentNode.insertBefore(i,s))}(n,"script","facebook-jssdk")):FB.XFBML.parse()},twitter:function(e){var o=e.options.buttons.twitter;t(e.element).find(".buttons").append('<div class="button twitter"><a href="https://twitter.com/share" class="twitter-share-button" data-url="'+(""!==o.url?o.url:e.options.url)+'" data-count="'+o.count+'" data-text="'+e.options.text+'" data-via="'+o.via+'" data-hashtags="'+o.hashtags+'" data-related="'+o.related+'" data-lang="'+o.lang+'">Tweet</a></div>');var i=0;"undefined"==typeof twttr&&0==i?(i=1,function(){var t=n.createElement("script");t.type="text/javascript",t.async=!0,t.src="//platform.twitter.com/widgets.js";var e=n.getElementsByTagName("script")[0];e.parentNode.insertBefore(t,e)}()):t.ajax({url:"//platform.twitter.com/widgets.js",dataType:"script",cache:!0})},digg:function(e){var o=e.options.buttons.digg;t(e.element).find(".buttons").append('<div class="button digg"><a class="DiggThisButton '+o.type+'" rel="nofollow external" href="http://digg.com/submit?url='+encodeURIComponent(""!==o.url?o.url:e.options.url)+'"></a></div>');var i=0;"undefined"==typeof __DBW&&0==i&&(i=1,function(){var t=n.createElement("SCRIPT"),e=n.getElementsByTagName("SCRIPT")[0];t.type="text/javascript",t.async=!0,t.src="//widgets.digg.com/buttons.js",e.parentNode.insertBefore(t,e)}())},delicious:function(e){if("tall"==e.options.buttons.delicious.size)var o="width:50px;",n="height:35px;width:50px;font-size:15px;line-height:35px;",i="height:18px;line-height:18px;margin-top:3px;";else var o="width:93px;",n="float:right;padding:0 3px;height:20px;width:26px;line-height:20px;",i="float:left;height:20px;line-height:20px;";var s=e.shorterTotal(e.options.count.delicious);"undefined"==typeof s&&(s=0),t(e.element).find(".buttons").append('<div class="button delicious"><div style="'+o+'font:12px Arial,Helvetica,sans-serif;cursor:pointer;color:#666666;display:inline-block;float:none;height:20px;line-height:normal;margin:0;padding:0;text-indent:0;vertical-align:baseline;"><div style="'+n+'background-color:#fff;margin-bottom:5px;overflow:hidden;text-align:center;border:1px solid #ccc;border-radius:3px;">'+s+'</div><div style="'+i+'display:block;padding:0;text-align:center;text-decoration:none;width:50px;background-color:#7EACEE;border:1px solid #40679C;border-radius:3px;color:#fff;"><img src="http://www.delicious.com/static/img/delicious.small.gif" height="10" width="10" alt="Delicious" /> Add</div></div></div>'),t(e.element).find(".delicious").on("click",function(){e.openPopup("delicious")})},stumbleupon:function(e){var i=e.options.buttons.stumbleupon;t(e.element).find(".buttons").append('<div class="button stumbleupon"><su:badge layout="'+i.layout+'" location="'+(""!==i.url?i.url:e.options.url)+'"></su:badge></div>');var a=0;"undefined"==typeof STMBLPN&&0==a?(a=1,function(){var t=n.createElement("script");t.type="text/javascript",t.async=!0,t.src="//platform.stumbleupon.com/1/widgets.js";var e=n.getElementsByTagName("script")[0];e.parentNode.insertBefore(t,e)}(),s=o.setTimeout(function(){"undefined"!=typeof STMBLPN&&(STMBLPN.processWidgets(),clearInterval(s))},500)):STMBLPN.processWidgets()},linkedin:function(e){var i=e.options.buttons.linkedin;t(e.element).find(".buttons").append('<div class="button linkedin"><script type="in/share" data-url="'+(""!==i.url?i.url:e.options.url)+'" data-counter="'+i.counter+'"/></div>');var s=0;"undefined"==typeof o.IN&&0==s?(s=1,function(){var t=n.createElement("script");t.type="text/javascript",t.async=!0,t.src="//platform.linkedin.com/in.js";var e=n.getElementsByTagName("script")[0];e.parentNode.insertBefore(t,e)}()):o.IN.init()},pinterest:function(e){var o=e.options.buttons.pinterest;t(e.element).find(".buttons").append('<div class="button pinterest"><a href="http://pinterest.com/pin/create/button/?url='+(""!==o.url?o.url:e.options.url)+"&media="+o.media+"&description="+o.description+'" class="pin-it-button" count-layout="'+o.layout+'">Pin It</a></div>'),function(){var t=n.createElement("script");t.type="text/javascript",t.async=!0,t.src="//assets.pinterest.com/js/pinit.js";var e=n.getElementsByTagName("script")[0];e.parentNode.insertBefore(t,e)}()}},p={googlePlus:function(){},facebook:function(){fb=o.setInterval(function(){"undefined"!=typeof FB&&(FB.Event.subscribe("edge.create",function(t){_gaq.push(["_trackSocial","facebook","like",t])}),FB.Event.subscribe("edge.remove",function(t){_gaq.push(["_trackSocial","facebook","unlike",t])}),FB.Event.subscribe("message.send",function(t){_gaq.push(["_trackSocial","facebook","send",t])}),clearInterval(fb))},1e3)},twitter:function(){tw=o.setInterval(function(){"undefined"!=typeof twttr&&(twttr.events.bind("tweet",function(t){t&&_gaq.push(["_trackSocial","twitter","tweet"])}),clearInterval(tw))},1e3)},digg:function(){},delicious:function(){},stumbleupon:function(){},linkedin:function(){},pinterest:function(){}},d={googlePlus:function(t){o.open("https://plus.google.com/share?hl="+t.buttons.googlePlus.lang+"&url="+encodeURIComponent(""!==t.buttons.googlePlus.url?t.buttons.googlePlus.url:t.url),"","toolbar=0, status=0, width=900, height=500")},facebook:function(t){o.open("http://www.facebook.com/sharer/sharer.php?u="+encodeURIComponent(""!==t.buttons.facebook.url?t.buttons.facebook.url:t.url)+"&t="+t.text,"","toolbar=0, status=0, width=900, height=500")},twitter:function(t){o.open("https://twitter.com/intent/tweet?text="+encodeURIComponent(t.text)+"&url="+encodeURIComponent(""!==t.buttons.twitter.url?t.buttons.twitter.url:t.url)+(""!==t.buttons.twitter.via?"&via="+t.buttons.twitter.via:""),"","toolbar=0, status=0, width=650, height=360")},digg:function(t){o.open("http://digg.com/tools/diggthis/submit?url="+encodeURIComponent(""!==t.buttons.digg.url?t.buttons.digg.url:t.url)+"&title="+t.text+"&related=true&style=true","","toolbar=0, status=0, width=650, height=360")},delicious:function(t){o.open("http://www.delicious.com/save?v=5&noui&jump=close&url="+encodeURIComponent(""!==t.buttons.delicious.url?t.buttons.delicious.url:t.url)+"&title="+t.text,"delicious","toolbar=no,width=550,height=550")},stumbleupon:function(t){o.open("http://www.stumbleupon.com/badge/?url="+encodeURIComponent(""!==t.buttons.stumbleupon.url?t.buttons.stumbleupon.url:t.url),"stumbleupon","toolbar=no,width=550,height=550")},linkedin:function(t){o.open("https://www.linkedin.com/cws/share?url="+encodeURIComponent(""!==t.buttons.linkedin.url?t.buttons.linkedin.url:t.url)+"&token=&isFramed=true","linkedin","toolbar=no,width=550,height=550")},pinterest:function(t){o.open("http://pinterest.com/pin/create/button/?url="+encodeURIComponent(""!==t.buttons.pinterest.url?t.buttons.pinterest.url:t.url)+"&media="+encodeURIComponent(t.buttons.pinterest.media)+"&description="+t.buttons.pinterest.description,"pinterest","toolbar=no,width=700,height=300")}};a.prototype.init=function(){var e=this;""!==this.options.urlCurl&&(u.googlePlus=this.options.urlCurl+"?url={url}&type=googlePlus",u.stumbleupon=this.options.urlCurl+"?url={url}&type=stumbleupon"),t(this.element).addClass(this.options.className),"undefined"!=typeof t(this.element).data("title")&&(this.options.title=t(this.element).attr("data-title")),"undefined"!=typeof t(this.element).data("url")&&(this.options.url=t(this.element).data("url")),"undefined"!=typeof t(this.element).data("text")&&(this.options.text=t(this.element).data("text")),t.each(this.options.share,function(t,o){o===!0&&e.options.shareTotal++}),e.options.enableCounter===!0?t.each(this.options.share,function(t,o){if(o===!0)try{e.getSocialJson(t)}catch(n){}}):""!==e.options.template?this.options.render(this,this.options):this.loadButtons(),t(this.element).hover(function(){0===t(this).find(".buttons").length&&e.options.enableHover===!0&&e.loadButtons(),e.options.hover(e,e.options)},function(){e.options.hide(e,e.options)}),t(this.element).click(function(){return e.options.click(e,e.options),!1})},a.prototype.loadButtons=function(){var e=this;t(this.element).append('<div class="buttons"></div>'),t.each(e.options.share,function(t,o){1==o&&(c[t](e),e.options.enableTracking===!0&&p[t]())})},a.prototype.getSocialJson=function(e){var o=this,n=0,i=u[e].replace("{url}",encodeURIComponent(this.options.url));this.options.buttons[e].urlCount===!0&&""!==this.options.buttons[e].url&&(i=u[e].replace("{url}",this.options.buttons[e].url)),""!=i&&""!==o.options.urlCurl?t.getJSON(i,function(t){if("undefined"!=typeof t.count){var i=t.count+"";i=i.replace("Â ",""),n+=parseInt(i,10)}else t.data&&t.data.length>0&&"undefined"!=typeof t.data[0].total_count?n+=parseInt(t.data[0].total_count,10):"undefined"!=typeof t[0]?n+=parseInt(t[0].total_posts,10):"undefined"!=typeof t[0];o.options.count[e]=n,o.options.total+=n,o.renderer(),o.rendererPerso()}).error(function(){o.options.count[e]=0,o.rendererPerso()}):(o.renderer(),o.options.count[e]=0,o.rendererPerso())},a.prototype.rendererPerso=function(){var t=0;for(e in this.options.count)t++;t===this.options.shareTotal&&this.options.render(this,this.options)},a.prototype.renderer=function(){var e=this.options.total,o=this.options.template;this.options.shorterTotal===!0&&(e=this.shorterTotal(e)),""!==o?(o=o.replace(/\{total\}/g,e),t(this.element).html(o)):t(this.element).html('<div class="box"><a class="count" href="#">'+e+"</a>"+(""!==this.options.title?'<a class="share" href="#">'+this.options.title+"</a>":"")+"</div>")},a.prototype.shorterTotal=function(t){return t>=1e6?t=(t/1e6).toFixed(2)+"M":t>=1e3&&(t=(t/1e3).toFixed(1)+"k"),t},a.prototype.openPopup=function(t){if(d[t](this.options),this.options.enableTracking===!0){var e={googlePlus:{site:"Google",action:"+1"},facebook:{site:"facebook",action:"like"},twitter:{site:"twitter",action:"tweet"},digg:{site:"digg",action:"add"},delicious:{site:"delicious",action:"add"},stumbleupon:{site:"stumbleupon",action:"add"},linkedin:{site:"linkedin",action:"share"},pinterest:{site:"pinterest",action:"pin"}};_gaq.push(["_trackSocial",e[t].site,e[t].action])}},a.prototype.simulateClick=function(){var e=t(this.element).html();t(this.element).html(e.replace(this.options.total,this.options.total+1))},a.prototype.update=function(t,e){""!==t&&(this.options.url=t),""!==e&&(this.options.text=e)},t.fn[r]=function(e){var o=arguments;return e===i||"object"==typeof e?this.each(function(){t.data(this,"plugin_"+r)||t.data(this,"plugin_"+r,new a(this,e))}):"string"==typeof e&&"_"!==e[0]&&"init"!==e?this.each(function(){var n=t.data(this,"plugin_"+r);n instanceof a&&"function"==typeof n[e]&&n[e].apply(n,Array.prototype.slice.call(o,1))}):void 0}}(jQuery,window,document);

/* == jquery mousewheel plugin == Version: 3.1.12, License: MIT License (MIT) */
!function(a){"function"==typeof define&&define.amd?define(["jquery"],a):"object"==typeof exports?module.exports=a:a(jQuery)}(function(a){function b(b){var g=b||window.event,h=i.call(arguments,1),j=0,l=0,m=0,n=0,o=0,p=0;if(b=a.event.fix(g),b.type="mousewheel","detail"in g&&(m=-1*g.detail),"wheelDelta"in g&&(m=g.wheelDelta),"wheelDeltaY"in g&&(m=g.wheelDeltaY),"wheelDeltaX"in g&&(l=-1*g.wheelDeltaX),"axis"in g&&g.axis===g.HORIZONTAL_AXIS&&(l=-1*m,m=0),j=0===m?l:m,"deltaY"in g&&(m=-1*g.deltaY,j=m),"deltaX"in g&&(l=g.deltaX,0===m&&(j=-1*l)),0!==m||0!==l){if(1===g.deltaMode){var q=a.data(this,"mousewheel-line-height");j*=q,m*=q,l*=q}else if(2===g.deltaMode){var r=a.data(this,"mousewheel-page-height");j*=r,m*=r,l*=r}if(n=Math.max(Math.abs(m),Math.abs(l)),(!f||f>n)&&(f=n,d(g,n)&&(f/=40)),d(g,n)&&(j/=40,l/=40,m/=40),j=Math[j>=1?"floor":"ceil"](j/f),l=Math[l>=1?"floor":"ceil"](l/f),m=Math[m>=1?"floor":"ceil"](m/f),k.settings.normalizeOffset&&this.getBoundingClientRect){var s=this.getBoundingClientRect();o=b.clientX-s.left,p=b.clientY-s.top}return b.deltaX=l,b.deltaY=m,b.deltaFactor=f,b.offsetX=o,b.offsetY=p,b.deltaMode=0,h.unshift(b,j,l,m),e&&clearTimeout(e),e=setTimeout(c,200),(a.event.dispatch||a.event.handle).apply(this,h)}}function c(){f=null}function d(a,b){return k.settings.adjustOldDeltas&&"mousewheel"===a.type&&b%120===0}var e,f,g=["wheel","mousewheel","DOMMouseScroll","MozMousePixelScroll"],h="onwheel"in document||document.documentMode>=9?["wheel"]:["mousewheel","DomMouseScroll","MozMousePixelScroll"],i=Array.prototype.slice;if(a.event.fixHooks)for(var j=g.length;j;)a.event.fixHooks[g[--j]]=a.event.mouseHooks;var k=a.event.special.mousewheel={version:"3.1.12",setup:function(){if(this.addEventListener)for(var c=h.length;c;)this.addEventListener(h[--c],b,!1);else this.onmousewheel=b;a.data(this,"mousewheel-line-height",k.getLineHeight(this)),a.data(this,"mousewheel-page-height",k.getPageHeight(this))},teardown:function(){if(this.removeEventListener)for(var c=h.length;c;)this.removeEventListener(h[--c],b,!1);else this.onmousewheel=null;a.removeData(this,"mousewheel-line-height"),a.removeData(this,"mousewheel-page-height")},getLineHeight:function(b){var c=a(b),d=c["offsetParent"in a.fn?"offsetParent":"parent"]();return d.length||(d=a("body")),parseInt(d.css("fontSize"),10)||parseInt(c.css("fontSize"),10)||16},getPageHeight:function(b){return a(b).height()},settings:{adjustOldDeltas:!0,normalizeOffset:!0}};a.fn.extend({mousewheel:function(a){return a?this.bind("mousewheel",a):this.trigger("mousewheel")},unmousewheel:function(a){return this.unbind("mousewheel",a)}})});
/* == malihu jquery custom scrollbar plugin == Version: 3.0.8, License: MIT License (MIT) */
!function(e){"undefined"!=typeof module&&module.exports?module.exports=e:e(jQuery,window,document)}(function(e){!function(t){var o="function"==typeof define&&define.amd,a="undefined"!=typeof module&&module.exports,n="https:"==document.location.protocol?"https:":"http:",i="cdnjs.cloudflare.com/ajax/libs/jquery-mousewheel/3.1.12/jquery.mousewheel.min.js";o||(a?require("jquery-mousewheel")(e):e.event.special.mousewheel||e("head").append(decodeURI("%3Cscript src="+n+"//"+i+"%3E%3C/script%3E"))),t()}(function(){var t,o="mCustomScrollbar",a="mCS",n=".mCustomScrollbar",i={setTop:0,setLeft:0,axis:"y",scrollbarPosition:"inside",scrollInertia:950,autoDraggerLength:!0,alwaysShowScrollbar:0,snapOffset:0,mouseWheel:{enable:!0,scrollAmount:"auto",axis:"y",deltaFactor:"auto",disableOver:["select","option","keygen","datalist","textarea"]},scrollButtons:{scrollType:"stepless",scrollAmount:"auto"},keyboard:{enable:!0,scrollType:"stepless",scrollAmount:"auto"},contentTouchScroll:25,advanced:{autoScrollOnFocus:"input,textarea,select,button,datalist,keygen,a[tabindex],area,object,[contenteditable='true']",updateOnContentResize:!0,updateOnImageLoad:!0},theme:"light",callbacks:{onTotalScrollOffset:0,onTotalScrollBackOffset:0,alwaysTriggerOffsets:!0}},r=0,l={},s=window.attachEvent&&!window.addEventListener?1:0,c=!1,d=["mCSB_dragger_onDrag","mCSB_scrollTools_onDrag","mCS_img_loaded","mCS_disabled","mCS_destroyed","mCS_no_scrollbar","mCS-autoHide","mCS-dir-rtl","mCS_no_scrollbar_y","mCS_no_scrollbar_x","mCS_y_hidden","mCS_x_hidden","mCSB_draggerContainer","mCSB_buttonUp","mCSB_buttonDown","mCSB_buttonLeft","mCSB_buttonRight"],u={init:function(t){var t=e.extend(!0,{},i,t),o=f.call(this);if(t.live){var s=t.liveSelector||this.selector||n,c=e(s);if("off"===t.live)return void m(s);l[s]=setTimeout(function(){c.mCustomScrollbar(t),"once"===t.live&&c.length&&m(s)},500)}else m(s);return t.setWidth=t.set_width?t.set_width:t.setWidth,t.setHeight=t.set_height?t.set_height:t.setHeight,t.axis=t.horizontalScroll?"x":p(t.axis),t.scrollInertia=t.scrollInertia>0&&t.scrollInertia<17?17:t.scrollInertia,"object"!=typeof t.mouseWheel&&1==t.mouseWheel&&(t.mouseWheel={enable:!0,scrollAmount:"auto",axis:"y",preventDefault:!1,deltaFactor:"auto",normalizeDelta:!1,invert:!1}),t.mouseWheel.scrollAmount=t.mouseWheelPixels?t.mouseWheelPixels:t.mouseWheel.scrollAmount,t.mouseWheel.normalizeDelta=t.advanced.normalizeMouseWheelDelta?t.advanced.normalizeMouseWheelDelta:t.mouseWheel.normalizeDelta,t.scrollButtons.scrollType=g(t.scrollButtons.scrollType),h(t),e(o).each(function(){var o=e(this);if(!o.data(a)){o.data(a,{idx:++r,opt:t,scrollRatio:{y:null,x:null},overflowed:null,contentReset:{y:null,x:null},bindEvents:!1,tweenRunning:!1,sequential:{},langDir:o.css("direction"),cbOffsets:null,trigger:null});var n=o.data(a),i=n.opt,l=o.data("mcs-axis"),s=o.data("mcs-scrollbar-position"),c=o.data("mcs-theme");l&&(i.axis=l),s&&(i.scrollbarPosition=s),c&&(i.theme=c,h(i)),v.call(this),e("#mCSB_"+n.idx+"_container img:not(."+d[2]+")").addClass(d[2]),u.update.call(null,o)}})},update:function(t,o){var n=t||f.call(this);return e(n).each(function(){var t=e(this);if(t.data(a)){var n=t.data(a),i=n.opt,r=e("#mCSB_"+n.idx+"_container"),l=[e("#mCSB_"+n.idx+"_dragger_vertical"),e("#mCSB_"+n.idx+"_dragger_horizontal")];if(!r.length)return;n.tweenRunning&&V(t),t.hasClass(d[3])&&t.removeClass(d[3]),t.hasClass(d[4])&&t.removeClass(d[4]),S.call(this),_.call(this),"y"===i.axis||i.advanced.autoExpandHorizontalScroll||r.css("width",x(r.children())),n.overflowed=B.call(this),O.call(this),i.autoDraggerLength&&b.call(this),C.call(this),k.call(this);var s=[Math.abs(r[0].offsetTop),Math.abs(r[0].offsetLeft)];"x"!==i.axis&&(n.overflowed[0]?l[0].height()>l[0].parent().height()?T.call(this):(Q(t,s[0].toString(),{dir:"y",dur:0,overwrite:"none"}),n.contentReset.y=null):(T.call(this),"y"===i.axis?M.call(this):"yx"===i.axis&&n.overflowed[1]&&Q(t,s[1].toString(),{dir:"x",dur:0,overwrite:"none"}))),"y"!==i.axis&&(n.overflowed[1]?l[1].width()>l[1].parent().width()?T.call(this):(Q(t,s[1].toString(),{dir:"x",dur:0,overwrite:"none"}),n.contentReset.x=null):(T.call(this),"x"===i.axis?M.call(this):"yx"===i.axis&&n.overflowed[0]&&Q(t,s[0].toString(),{dir:"y",dur:0,overwrite:"none"}))),o&&n&&(2===o&&i.callbacks.onImageLoad&&"function"==typeof i.callbacks.onImageLoad?i.callbacks.onImageLoad.call(this):3===o&&i.callbacks.onSelectorChange&&"function"==typeof i.callbacks.onSelectorChange?i.callbacks.onSelectorChange.call(this):i.callbacks.onUpdate&&"function"==typeof i.callbacks.onUpdate&&i.callbacks.onUpdate.call(this)),X.call(this)}})},scrollTo:function(t,o){if("undefined"!=typeof t&&null!=t){var n=f.call(this);return e(n).each(function(){var n=e(this);if(n.data(a)){var i=n.data(a),r=i.opt,l={trigger:"external",scrollInertia:r.scrollInertia,scrollEasing:"mcsEaseInOut",moveDragger:!1,timeout:60,callbacks:!0,onStart:!0,onUpdate:!0,onComplete:!0},s=e.extend(!0,{},l,o),c=Y.call(this,t),d=s.scrollInertia>0&&s.scrollInertia<17?17:s.scrollInertia;c[0]=j.call(this,c[0],"y"),c[1]=j.call(this,c[1],"x"),s.moveDragger&&(c[0]*=i.scrollRatio.y,c[1]*=i.scrollRatio.x),s.dur=d,setTimeout(function(){null!==c[0]&&"undefined"!=typeof c[0]&&"x"!==r.axis&&i.overflowed[0]&&(s.dir="y",s.overwrite="all",Q(n,c[0].toString(),s)),null!==c[1]&&"undefined"!=typeof c[1]&&"y"!==r.axis&&i.overflowed[1]&&(s.dir="x",s.overwrite="none",Q(n,c[1].toString(),s))},s.timeout)}})}},stop:function(){var t=f.call(this);return e(t).each(function(){var t=e(this);t.data(a)&&V(t)})},disable:function(t){var o=f.call(this);return e(o).each(function(){var o=e(this);if(o.data(a)){{o.data(a)}X.call(this,"remove"),M.call(this),t&&T.call(this),O.call(this,!0),o.addClass(d[3])}})},destroy:function(){var t=f.call(this);return e(t).each(function(){var n=e(this);if(n.data(a)){var i=n.data(a),r=i.opt,l=e("#mCSB_"+i.idx),s=e("#mCSB_"+i.idx+"_container"),c=e(".mCSB_"+i.idx+"_scrollbar");r.live&&m(r.liveSelector||e(t).selector),X.call(this,"remove"),M.call(this),T.call(this),n.removeData(a),Z(this,"mcs"),c.remove(),s.find("img."+d[2]).removeClass(d[2]),l.replaceWith(s.contents()),n.removeClass(o+" _"+a+"_"+i.idx+" "+d[6]+" "+d[7]+" "+d[5]+" "+d[3]).addClass(d[4])}})}},f=function(){return"object"!=typeof e(this)||e(this).length<1?n:this},h=function(t){var o=["rounded","rounded-dark","rounded-dots","rounded-dots-dark"],a=["rounded-dots","rounded-dots-dark","3d","3d-dark","3d-thick","3d-thick-dark","inset","inset-dark","inset-2","inset-2-dark","inset-3","inset-3-dark"],n=["minimal","minimal-dark"],i=["minimal","minimal-dark"],r=["minimal","minimal-dark"];t.autoDraggerLength=e.inArray(t.theme,o)>-1?!1:t.autoDraggerLength,t.autoExpandScrollbar=e.inArray(t.theme,a)>-1?!1:t.autoExpandScrollbar,t.scrollButtons.enable=e.inArray(t.theme,n)>-1?!1:t.scrollButtons.enable,t.autoHideScrollbar=e.inArray(t.theme,i)>-1?!0:t.autoHideScrollbar,t.scrollbarPosition=e.inArray(t.theme,r)>-1?"outside":t.scrollbarPosition},m=function(e){l[e]&&(clearTimeout(l[e]),Z(l,e))},p=function(e){return"yx"===e||"xy"===e||"auto"===e?"yx":"x"===e||"horizontal"===e?"x":"y"},g=function(e){return"stepped"===e||"pixels"===e||"step"===e||"click"===e?"stepped":"stepless"},v=function(){var t=e(this),n=t.data(a),i=n.opt,r=i.autoExpandScrollbar?" "+d[1]+"_expand":"",l=["<div id='mCSB_"+n.idx+"_scrollbar_vertical' class='mCSB_scrollTools mCSB_"+n.idx+"_scrollbar mCS-"+i.theme+" mCSB_scrollTools_vertical"+r+"'><div class='"+d[12]+"'><div id='mCSB_"+n.idx+"_dragger_vertical' class='mCSB_dragger' style='position:absolute;' oncontextmenu='return false;'><div class='mCSB_dragger_bar' /></div><div class='mCSB_draggerRail' /></div></div>","<div id='mCSB_"+n.idx+"_scrollbar_horizontal' class='mCSB_scrollTools mCSB_"+n.idx+"_scrollbar mCS-"+i.theme+" mCSB_scrollTools_horizontal"+r+"'><div class='"+d[12]+"'><div id='mCSB_"+n.idx+"_dragger_horizontal' class='mCSB_dragger' style='position:absolute;' oncontextmenu='return false;'><div class='mCSB_dragger_bar' /></div><div class='mCSB_draggerRail' /></div></div>"],s="yx"===i.axis?"mCSB_vertical_horizontal":"x"===i.axis?"mCSB_horizontal":"mCSB_vertical",c="yx"===i.axis?l[0]+l[1]:"x"===i.axis?l[1]:l[0],u="yx"===i.axis?"<div id='mCSB_"+n.idx+"_container_wrapper' class='mCSB_container_wrapper' />":"",f=i.autoHideScrollbar?" "+d[6]:"",h="x"!==i.axis&&"rtl"===n.langDir?" "+d[7]:"";i.setWidth&&t.css("width",i.setWidth),i.setHeight&&t.css("height",i.setHeight),i.setLeft="y"!==i.axis&&"rtl"===n.langDir?"989999px":i.setLeft,t.addClass(o+" _"+a+"_"+n.idx+f+h).wrapInner("<div id='mCSB_"+n.idx+"' class='mCustomScrollBox mCS-"+i.theme+" "+s+"'><div id='mCSB_"+n.idx+"_container' class='mCSB_container' style='position:relative; top:"+i.setTop+"; left:"+i.setLeft+";' dir="+n.langDir+" /></div>");var m=e("#mCSB_"+n.idx),p=e("#mCSB_"+n.idx+"_container");"y"===i.axis||i.advanced.autoExpandHorizontalScroll||p.css("width",x(p.children())),"outside"===i.scrollbarPosition?("static"===t.css("position")&&t.css("position","relative"),t.css("overflow","visible"),m.addClass("mCSB_outside").after(c)):(m.addClass("mCSB_inside").append(c),p.wrap(u)),w.call(this);var g=[e("#mCSB_"+n.idx+"_dragger_vertical"),e("#mCSB_"+n.idx+"_dragger_horizontal")];g[0].css("min-height",g[0].height()),g[1].css("min-width",g[1].width())},x=function(t){return Math.max.apply(Math,t.map(function(){return e(this).outerWidth(!0)}).get())},_=function(){var t=e(this),o=t.data(a),n=o.opt,i=e("#mCSB_"+o.idx+"_container");n.advanced.autoExpandHorizontalScroll&&"y"!==n.axis&&i.css({position:"absolute",width:"auto"}).wrap("<div class='mCSB_h_wrapper' style='position:relative; left:0; width:999999px;' />").css({width:Math.ceil(i[0].getBoundingClientRect().right+.4)-Math.floor(i[0].getBoundingClientRect().left),position:"relative"}).unwrap()},w=function(){var t=e(this),o=t.data(a),n=o.opt,i=e(".mCSB_"+o.idx+"_scrollbar:first"),r=tt(n.scrollButtons.tabindex)?"tabindex='"+n.scrollButtons.tabindex+"'":"",l=["<a href='#' class='"+d[13]+"' oncontextmenu='return false;' "+r+" />","<a href='#' class='"+d[14]+"' oncontextmenu='return false;' "+r+" />","<a href='#' class='"+d[15]+"' oncontextmenu='return false;' "+r+" />","<a href='#' class='"+d[16]+"' oncontextmenu='return false;' "+r+" />"],s=["x"===n.axis?l[2]:l[0],"x"===n.axis?l[3]:l[1],l[2],l[3]];n.scrollButtons.enable&&i.prepend(s[0]).append(s[1]).next(".mCSB_scrollTools").prepend(s[2]).append(s[3])},S=function(){var t=e(this),o=t.data(a),n=e("#mCSB_"+o.idx),i=t.css("max-height")||"none",r=-1!==i.indexOf("%"),l=t.css("box-sizing");if("none"!==i){var s=r?t.parent().height()*parseInt(i)/100:parseInt(i);"border-box"===l&&(s-=t.innerHeight()-t.height()+(t.outerHeight()-t.innerHeight())),n.css("max-height",Math.round(s))}},b=function(){var t=e(this),o=t.data(a),n=e("#mCSB_"+o.idx),i=e("#mCSB_"+o.idx+"_container"),r=[e("#mCSB_"+o.idx+"_dragger_vertical"),e("#mCSB_"+o.idx+"_dragger_horizontal")],l=[n.height()/i.outerHeight(!1),n.width()/i.outerWidth(!1)],c=[parseInt(r[0].css("min-height")),Math.round(l[0]*r[0].parent().height()),parseInt(r[1].css("min-width")),Math.round(l[1]*r[1].parent().width())],d=s&&c[1]<c[0]?c[0]:c[1],u=s&&c[3]<c[2]?c[2]:c[3];r[0].css({height:d,"max-height":r[0].parent().height()-10}).find(".mCSB_dragger_bar").css({"line-height":c[0]+"px"}),r[1].css({width:u,"max-width":r[1].parent().width()-10})},C=function(){var t=e(this),o=t.data(a),n=e("#mCSB_"+o.idx),i=e("#mCSB_"+o.idx+"_container"),r=[e("#mCSB_"+o.idx+"_dragger_vertical"),e("#mCSB_"+o.idx+"_dragger_horizontal")],l=[i.outerHeight(!1)-n.height(),i.outerWidth(!1)-n.width()],s=[l[0]/(r[0].parent().height()-r[0].height()),l[1]/(r[1].parent().width()-r[1].width())];o.scrollRatio={y:s[0],x:s[1]}},y=function(e,t,o){var a=o?d[0]+"_expanded":"",n=e.closest(".mCSB_scrollTools");"active"===t?(e.toggleClass(d[0]+" "+a),n.toggleClass(d[1]),e[0]._draggable=e[0]._draggable?0:1):e[0]._draggable||("hide"===t?(e.removeClass(d[0]),n.removeClass(d[1])):(e.addClass(d[0]),n.addClass(d[1])))},B=function(){var t=e(this),o=t.data(a),n=e("#mCSB_"+o.idx),i=e("#mCSB_"+o.idx+"_container"),r=null==o.overflowed?i.height():i.outerHeight(!1),l=null==o.overflowed?i.width():i.outerWidth(!1);return[r>n.height(),l>n.width()]},T=function(){var t=e(this),o=t.data(a),n=o.opt,i=e("#mCSB_"+o.idx),r=e("#mCSB_"+o.idx+"_container"),l=[e("#mCSB_"+o.idx+"_dragger_vertical"),e("#mCSB_"+o.idx+"_dragger_horizontal")];if(V(t),("x"!==n.axis&&!o.overflowed[0]||"y"===n.axis&&o.overflowed[0])&&(l[0].add(r).css("top",0),Q(t,"_resetY")),"y"!==n.axis&&!o.overflowed[1]||"x"===n.axis&&o.overflowed[1]){var s=dx=0;"rtl"===o.langDir&&(s=i.width()-r.outerWidth(!1),dx=Math.abs(s/o.scrollRatio.x)),r.css("left",s),l[1].css("left",dx),Q(t,"_resetX")}},k=function(){function t(){r=setTimeout(function(){e.event.special.mousewheel?(clearTimeout(r),W.call(o[0])):t()},100)}var o=e(this),n=o.data(a),i=n.opt;if(!n.bindEvents){if(R.call(this),i.contentTouchScroll&&E.call(this),D.call(this),i.mouseWheel.enable){var r;t()}P.call(this),H.call(this),i.advanced.autoScrollOnFocus&&z.call(this),i.scrollButtons.enable&&U.call(this),i.keyboard.enable&&q.call(this),n.bindEvents=!0}},M=function(){var t=e(this),o=t.data(a),n=o.opt,i=a+"_"+o.idx,r=".mCSB_"+o.idx+"_scrollbar",l=e("#mCSB_"+o.idx+",#mCSB_"+o.idx+"_container,#mCSB_"+o.idx+"_container_wrapper,"+r+" ."+d[12]+",#mCSB_"+o.idx+"_dragger_vertical,#mCSB_"+o.idx+"_dragger_horizontal,"+r+">a"),s=e("#mCSB_"+o.idx+"_container");n.advanced.releaseDraggableSelectors&&l.add(e(n.advanced.releaseDraggableSelectors)),o.bindEvents&&(e(document).unbind("."+i),l.each(function(){e(this).unbind("."+i)}),clearTimeout(t[0]._focusTimeout),Z(t[0],"_focusTimeout"),clearTimeout(o.sequential.step),Z(o.sequential,"step"),clearTimeout(s[0].onCompleteTimeout),Z(s[0],"onCompleteTimeout"),o.bindEvents=!1)},O=function(t){var o=e(this),n=o.data(a),i=n.opt,r=e("#mCSB_"+n.idx+"_container_wrapper"),l=r.length?r:e("#mCSB_"+n.idx+"_container"),s=[e("#mCSB_"+n.idx+"_scrollbar_vertical"),e("#mCSB_"+n.idx+"_scrollbar_horizontal")],c=[s[0].find(".mCSB_dragger"),s[1].find(".mCSB_dragger")];"x"!==i.axis&&(n.overflowed[0]&&!t?(s[0].add(c[0]).add(s[0].children("a")).css("display","block"),l.removeClass(d[8]+" "+d[10])):(i.alwaysShowScrollbar?(2!==i.alwaysShowScrollbar&&c[0].css("display","none"),l.removeClass(d[10])):(s[0].css("display","none"),l.addClass(d[10])),l.addClass(d[8]))),"y"!==i.axis&&(n.overflowed[1]&&!t?(s[1].add(c[1]).add(s[1].children("a")).css("display","block"),l.removeClass(d[9]+" "+d[11])):(i.alwaysShowScrollbar?(2!==i.alwaysShowScrollbar&&c[1].css("display","none"),l.removeClass(d[11])):(s[1].css("display","none"),l.addClass(d[11])),l.addClass(d[9]))),n.overflowed[0]||n.overflowed[1]?o.removeClass(d[5]):o.addClass(d[5])},I=function(e){var t=e.type;switch(t){case"pointerdown":case"MSPointerDown":case"pointermove":case"MSPointerMove":case"pointerup":case"MSPointerUp":return e.target.ownerDocument!==document?[e.originalEvent.screenY,e.originalEvent.screenX,!1]:[e.originalEvent.pageY,e.originalEvent.pageX,!1];case"touchstart":case"touchmove":case"touchend":var o=e.originalEvent.touches[0]||e.originalEvent.changedTouches[0],a=e.originalEvent.touches.length||e.originalEvent.changedTouches.length;return e.target.ownerDocument!==document?[o.screenY,o.screenX,a>1]:[o.pageY,o.pageX,a>1];default:return[e.pageY,e.pageX,!1]}},R=function(){function t(e){var t=m.find("iframe");if(t.length){var o=e?"auto":"none";t.css("pointer-events",o)}}function o(e,t,o,a){if(m[0].idleTimer=u.scrollInertia<233?250:0,n.attr("id")===h[1])var i="x",r=(n[0].offsetLeft-t+a)*d.scrollRatio.x;else var i="y",r=(n[0].offsetTop-e+o)*d.scrollRatio.y;Q(l,r.toString(),{dir:i,drag:!0})}var n,i,r,l=e(this),d=l.data(a),u=d.opt,f=a+"_"+d.idx,h=["mCSB_"+d.idx+"_dragger_vertical","mCSB_"+d.idx+"_dragger_horizontal"],m=e("#mCSB_"+d.idx+"_container"),p=e("#"+h[0]+",#"+h[1]),g=u.advanced.releaseDraggableSelectors?p.add(e(u.advanced.releaseDraggableSelectors)):p;p.bind("mousedown."+f+" touchstart."+f+" pointerdown."+f+" MSPointerDown."+f,function(o){if(o.stopImmediatePropagation(),o.preventDefault(),$(o)){c=!0,s&&(document.onselectstart=function(){return!1}),t(!1),V(l),n=e(this);var a=n.offset(),d=I(o)[0]-a.top,f=I(o)[1]-a.left,h=n.height()+a.top,m=n.width()+a.left;h>d&&d>0&&m>f&&f>0&&(i=d,r=f),y(n,"active",u.autoExpandScrollbar)}}).bind("touchmove."+f,function(e){e.stopImmediatePropagation(),e.preventDefault();var t=n.offset(),a=I(e)[0]-t.top,l=I(e)[1]-t.left;o(i,r,a,l)}),e(document).bind("mousemove."+f+" pointermove."+f+" MSPointerMove."+f,function(e){if(n){var t=n.offset(),a=I(e)[0]-t.top,l=I(e)[1]-t.left;if(i===a)return;o(i,r,a,l)}}).add(g).bind("mouseup."+f+" touchend."+f+" pointerup."+f+" MSPointerUp."+f,function(){n&&(y(n,"active",u.autoExpandScrollbar),n=null),c=!1,s&&(document.onselectstart=null),t(!0)})},E=function(){function o(e){if(!et(e)||c||I(e)[2])return void(t=0);t=1,S=0,b=0;var o=M.offset();d=I(e)[0]-o.top,u=I(e)[1]-o.left,A=[I(e)[0],I(e)[1]]}function n(e){if(et(e)&&!c&&!I(e)[2]&&(e.stopImmediatePropagation(),!b||S)){p=J();var t=k.offset(),o=I(e)[0]-t.top,a=I(e)[1]-t.left,n="mcsLinearOut";if(R.push(o),E.push(a),A[2]=Math.abs(I(e)[0]-A[0]),A[3]=Math.abs(I(e)[1]-A[1]),y.overflowed[0])var i=O[0].parent().height()-O[0].height(),r=d-o>0&&o-d>-(i*y.scrollRatio.y)&&(2*A[3]<A[2]||"yx"===B.axis);if(y.overflowed[1])var l=O[1].parent().width()-O[1].width(),f=u-a>0&&a-u>-(l*y.scrollRatio.x)&&(2*A[2]<A[3]||"yx"===B.axis);r||f?(e.preventDefault(),S=1):b=1,_="yx"===B.axis?[d-o,u-a]:"x"===B.axis?[null,u-a]:[d-o,null],M[0].idleTimer=250,y.overflowed[0]&&s(_[0],D,n,"y","all",!0),y.overflowed[1]&&s(_[1],D,n,"x",W,!0)}}function i(e){if(!et(e)||c||I(e)[2])return void(t=0);t=1,e.stopImmediatePropagation(),V(C),m=J();var o=k.offset();f=I(e)[0]-o.top,h=I(e)[1]-o.left,R=[],E=[]}function r(e){if(et(e)&&!c&&!I(e)[2]){e.stopImmediatePropagation(),S=0,b=0,g=J();var t=k.offset(),o=I(e)[0]-t.top,a=I(e)[1]-t.left;if(!(g-p>30)){x=1e3/(g-m);var n="mcsEaseOut",i=2.5>x,r=i?[R[R.length-2],E[E.length-2]]:[0,0];v=i?[o-r[0],a-r[1]]:[o-f,a-h];var d=[Math.abs(v[0]),Math.abs(v[1])];x=i?[Math.abs(v[0]/4),Math.abs(v[1]/4)]:[x,x];var u=[Math.abs(M[0].offsetTop)-v[0]*l(d[0]/x[0],x[0]),Math.abs(M[0].offsetLeft)-v[1]*l(d[1]/x[1],x[1])];_="yx"===B.axis?[u[0],u[1]]:"x"===B.axis?[null,u[1]]:[u[0],null],w=[4*d[0]+B.scrollInertia,4*d[1]+B.scrollInertia];var C=parseInt(B.contentTouchScroll)||0;_[0]=d[0]>C?_[0]:0,_[1]=d[1]>C?_[1]:0,y.overflowed[0]&&s(_[0],w[0],n,"y",W,!1),y.overflowed[1]&&s(_[1],w[1],n,"x",W,!1)}}}function l(e,t){var o=[1.5*t,2*t,t/1.5,t/2];return e>90?t>4?o[0]:o[3]:e>60?t>3?o[3]:o[2]:e>30?t>8?o[1]:t>6?o[0]:t>4?t:o[2]:t>8?t:o[3]}function s(e,t,o,a,n,i){e&&Q(C,e.toString(),{dur:t,scrollEasing:o,dir:a,overwrite:n,drag:i})}var d,u,f,h,m,p,g,v,x,_,w,S,b,C=e(this),y=C.data(a),B=y.opt,T=a+"_"+y.idx,k=e("#mCSB_"+y.idx),M=e("#mCSB_"+y.idx+"_container"),O=[e("#mCSB_"+y.idx+"_dragger_vertical"),e("#mCSB_"+y.idx+"_dragger_horizontal")],R=[],E=[],D=0,W="yx"===B.axis?"none":"all",A=[],P=M.find("iframe"),z=["touchstart."+T+" pointerdown."+T+" MSPointerDown."+T,"touchmove."+T+" pointermove."+T+" MSPointerMove."+T,"touchend."+T+" pointerup."+T+" MSPointerUp."+T];M.bind(z[0],function(e){o(e)}).bind(z[1],function(e){n(e)}),k.bind(z[0],function(e){i(e)}).bind(z[2],function(e){r(e)}),P.length&&P.each(function(){e(this).load(function(){L(this)&&e(this.contentDocument||this.contentWindow.document).bind(z[0],function(e){o(e),i(e)}).bind(z[1],function(e){n(e)}).bind(z[2],function(e){r(e)})})})},D=function(){function o(){return window.getSelection?window.getSelection().toString():document.selection&&"Control"!=document.selection.type?document.selection.createRange().text:0}function n(e,t,o){d.type=o&&i?"stepped":"stepless",d.scrollAmount=10,F(r,e,t,"mcsLinearOut",o?60:null)}var i,r=e(this),l=r.data(a),s=l.opt,d=l.sequential,u=a+"_"+l.idx,f=e("#mCSB_"+l.idx+"_container"),h=f.parent();f.bind("mousedown."+u,function(){t||i||(i=1,c=!0)}).add(document).bind("mousemove."+u,function(e){if(!t&&i&&o()){var a=f.offset(),r=I(e)[0]-a.top+f[0].offsetTop,c=I(e)[1]-a.left+f[0].offsetLeft;r>0&&r<h.height()&&c>0&&c<h.width()?d.step&&n("off",null,"stepped"):("x"!==s.axis&&l.overflowed[0]&&(0>r?n("on",38):r>h.height()&&n("on",40)),"y"!==s.axis&&l.overflowed[1]&&(0>c?n("on",37):c>h.width()&&n("on",39)))}}).bind("mouseup."+u,function(){t||(i&&(i=0,n("off",null)),c=!1)})},W=function(){function t(t,a){if(V(o),!A(o,t.target)){var r="auto"!==i.mouseWheel.deltaFactor?parseInt(i.mouseWheel.deltaFactor):s&&t.deltaFactor<100?100:t.deltaFactor||100;if("x"===i.axis||"x"===i.mouseWheel.axis)var d="x",u=[Math.round(r*n.scrollRatio.x),parseInt(i.mouseWheel.scrollAmount)],f="auto"!==i.mouseWheel.scrollAmount?u[1]:u[0]>=l.width()?.9*l.width():u[0],h=Math.abs(e("#mCSB_"+n.idx+"_container")[0].offsetLeft),m=c[1][0].offsetLeft,p=c[1].parent().width()-c[1].width(),g=t.deltaX||t.deltaY||a;else var d="y",u=[Math.round(r*n.scrollRatio.y),parseInt(i.mouseWheel.scrollAmount)],f="auto"!==i.mouseWheel.scrollAmount?u[1]:u[0]>=l.height()?.9*l.height():u[0],h=Math.abs(e("#mCSB_"+n.idx+"_container")[0].offsetTop),m=c[0][0].offsetTop,p=c[0].parent().height()-c[0].height(),g=t.deltaY||a;"y"===d&&!n.overflowed[0]||"x"===d&&!n.overflowed[1]||(i.mouseWheel.invert&&(g=-g),i.mouseWheel.normalizeDelta&&(g=0>g?-1:1),(g>0&&0!==m||0>g&&m!==p||i.mouseWheel.preventDefault)&&(t.stopImmediatePropagation(),t.preventDefault()),Q(o,(h-g*f).toString(),{dir:d}))}}var o=e(this),n=o.data(a),i=n.opt,r=a+"_"+n.idx,l=e("#mCSB_"+n.idx),c=[e("#mCSB_"+n.idx+"_dragger_vertical"),e("#mCSB_"+n.idx+"_dragger_horizontal")],d=e("#mCSB_"+n.idx+"_container").find("iframe");n&&(d.length&&d.each(function(){e(this).load(function(){L(this)&&e(this.contentDocument||this.contentWindow.document).bind("mousewheel."+r,function(e,o){t(e,o)})})}),l.bind("mousewheel."+r,function(e,o){t(e,o)}))},L=function(e){var t=null;try{var o=e.contentDocument||e.contentWindow.document;t=o.body.innerHTML}catch(a){}return null!==t},A=function(t,o){var n=o.nodeName.toLowerCase(),i=t.data(a).opt.mouseWheel.disableOver,r=["select","textarea"];return e.inArray(n,i)>-1&&!(e.inArray(n,r)>-1&&!e(o).is(":focus"))},P=function(){var t=e(this),o=t.data(a),n=a+"_"+o.idx,i=e("#mCSB_"+o.idx+"_container"),r=i.parent(),l=e(".mCSB_"+o.idx+"_scrollbar ."+d[12]);l.bind("touchstart."+n+" pointerdown."+n+" MSPointerDown."+n,function(){c=!0}).bind("touchend."+n+" pointerup."+n+" MSPointerUp."+n,function(){c=!1}).bind("click."+n,function(a){if(e(a.target).hasClass(d[12])||e(a.target).hasClass("mCSB_draggerRail")){V(t);var n=e(this),l=n.find(".mCSB_dragger");if(n.parent(".mCSB_scrollTools_horizontal").length>0){if(!o.overflowed[1])return;var s="x",c=a.pageX>l.offset().left?-1:1,u=Math.abs(i[0].offsetLeft)-.9*c*r.width()}else{if(!o.overflowed[0])return;var s="y",c=a.pageY>l.offset().top?-1:1,u=Math.abs(i[0].offsetTop)-.9*c*r.height()}Q(t,u.toString(),{dir:s,scrollEasing:"mcsEaseInOut"})}})},z=function(){var t=e(this),o=t.data(a),n=o.opt,i=a+"_"+o.idx,r=e("#mCSB_"+o.idx+"_container"),l=r.parent();r.bind("focusin."+i,function(){var o=e(document.activeElement),a=r.find(".mCustomScrollBox").length,i=0;o.is(n.advanced.autoScrollOnFocus)&&(V(t),clearTimeout(t[0]._focusTimeout),t[0]._focusTimer=a?(i+17)*a:0,t[0]._focusTimeout=setTimeout(function(){var e=[ot(o)[0],ot(o)[1]],a=[r[0].offsetTop,r[0].offsetLeft],s=[a[0]+e[0]>=0&&a[0]+e[0]<l.height()-o.outerHeight(!1),a[1]+e[1]>=0&&a[0]+e[1]<l.width()-o.outerWidth(!1)],c="yx"!==n.axis||s[0]||s[1]?"all":"none";"x"===n.axis||s[0]||Q(t,e[0].toString(),{dir:"y",scrollEasing:"mcsEaseInOut",overwrite:c,dur:i}),"y"===n.axis||s[1]||Q(t,e[1].toString(),{dir:"x",scrollEasing:"mcsEaseInOut",overwrite:c,dur:i})},t[0]._focusTimer))})},H=function(){var t=e(this),o=t.data(a),n=a+"_"+o.idx,i=e("#mCSB_"+o.idx+"_container").parent();i.bind("scroll."+n,function(){(0!==i.scrollTop()||0!==i.scrollLeft())&&e(".mCSB_"+o.idx+"_scrollbar").css("visibility","hidden")})},U=function(){var t=e(this),o=t.data(a),n=o.opt,i=o.sequential,r=a+"_"+o.idx,l=".mCSB_"+o.idx+"_scrollbar",s=e(l+">a");s.bind("mousedown."+r+" touchstart."+r+" pointerdown."+r+" MSPointerDown."+r+" mouseup."+r+" touchend."+r+" pointerup."+r+" MSPointerUp."+r+" mouseout."+r+" pointerout."+r+" MSPointerOut."+r+" click."+r,function(a){function r(e,o){i.scrollAmount=n.snapAmount||n.scrollButtons.scrollAmount,F(t,e,o)}if(a.preventDefault(),$(a)){var l=e(this).attr("class");switch(i.type=n.scrollButtons.scrollType,a.type){case"mousedown":case"touchstart":case"pointerdown":case"MSPointerDown":if("stepped"===i.type)return;c=!0,o.tweenRunning=!1,r("on",l);break;case"mouseup":case"touchend":case"pointerup":case"MSPointerUp":case"mouseout":case"pointerout":case"MSPointerOut":if("stepped"===i.type)return;c=!1,i.dir&&r("off",l);break;case"click":if("stepped"!==i.type||o.tweenRunning)return;r("on",l)}}})},q=function(){function t(t){function a(e,t){r.type=i.keyboard.scrollType,r.scrollAmount=i.snapAmount||i.keyboard.scrollAmount,"stepped"===r.type&&n.tweenRunning||F(o,e,t)}switch(t.type){case"blur":n.tweenRunning&&r.dir&&a("off",null);break;case"keydown":case"keyup":var l=t.keyCode?t.keyCode:t.which,s="on";if("x"!==i.axis&&(38===l||40===l)||"y"!==i.axis&&(37===l||39===l)){if((38===l||40===l)&&!n.overflowed[0]||(37===l||39===l)&&!n.overflowed[1])return;"keyup"===t.type&&(s="off"),e(document.activeElement).is(u)||(t.preventDefault(),t.stopImmediatePropagation(),a(s,l))}else if(33===l||34===l){if((n.overflowed[0]||n.overflowed[1])&&(t.preventDefault(),t.stopImmediatePropagation()),"keyup"===t.type){V(o);var f=34===l?-1:1;if("x"===i.axis||"yx"===i.axis&&n.overflowed[1]&&!n.overflowed[0])var h="x",m=Math.abs(c[0].offsetLeft)-.9*f*d.width();else var h="y",m=Math.abs(c[0].offsetTop)-.9*f*d.height();Q(o,m.toString(),{dir:h,scrollEasing:"mcsEaseInOut"})}}else if((35===l||36===l)&&!e(document.activeElement).is(u)&&((n.overflowed[0]||n.overflowed[1])&&(t.preventDefault(),t.stopImmediatePropagation()),"keyup"===t.type)){if("x"===i.axis||"yx"===i.axis&&n.overflowed[1]&&!n.overflowed[0])var h="x",m=35===l?Math.abs(d.width()-c.outerWidth(!1)):0;else var h="y",m=35===l?Math.abs(d.height()-c.outerHeight(!1)):0;Q(o,m.toString(),{dir:h,scrollEasing:"mcsEaseInOut"})}}}var o=e(this),n=o.data(a),i=n.opt,r=n.sequential,l=a+"_"+n.idx,s=e("#mCSB_"+n.idx),c=e("#mCSB_"+n.idx+"_container"),d=c.parent(),u="input,textarea,select,datalist,keygen,[contenteditable='true']",f=c.find("iframe"),h=["blur."+l+" keydown."+l+" keyup."+l];f.length&&f.each(function(){e(this).load(function(){L(this)&&e(this.contentDocument||this.contentWindow.document).bind(h[0],function(e){t(e)})})}),s.attr("tabindex","0").bind(h[0],function(e){t(e)})},F=function(t,o,n,i,r){function l(e){var o="stepped"!==f.type,a=r?r:e?o?p/1.5:g:1e3/60,n=e?o?7.5:40:2.5,s=[Math.abs(h[0].offsetTop),Math.abs(h[0].offsetLeft)],d=[c.scrollRatio.y>10?10:c.scrollRatio.y,c.scrollRatio.x>10?10:c.scrollRatio.x],u="x"===f.dir[0]?s[1]+f.dir[1]*d[1]*n:s[0]+f.dir[1]*d[0]*n,m="x"===f.dir[0]?s[1]+f.dir[1]*parseInt(f.scrollAmount):s[0]+f.dir[1]*parseInt(f.scrollAmount),v="auto"!==f.scrollAmount?m:u,x=i?i:e?o?"mcsLinearOut":"mcsEaseInOut":"mcsLinear",_=e?!0:!1;return e&&17>a&&(v="x"===f.dir[0]?s[1]:s[0]),Q(t,v.toString(),{dir:f.dir[0],scrollEasing:x,dur:a,onComplete:_}),e?void(f.dir=!1):(clearTimeout(f.step),void(f.step=setTimeout(function(){l()},a)))}function s(){clearTimeout(f.step),Z(f,"step"),V(t)}var c=t.data(a),u=c.opt,f=c.sequential,h=e("#mCSB_"+c.idx+"_container"),m="stepped"===f.type?!0:!1,p=u.scrollInertia<26?26:u.scrollInertia,g=u.scrollInertia<1?17:u.scrollInertia;switch(o){case"on":if(f.dir=[n===d[16]||n===d[15]||39===n||37===n?"x":"y",n===d[13]||n===d[15]||38===n||37===n?-1:1],V(t),tt(n)&&"stepped"===f.type)return;l(m);break;case"off":s(),(m||c.tweenRunning&&f.dir)&&l(!0)}},Y=function(t){var o=e(this).data(a).opt,n=[];return"function"==typeof t&&(t=t()),t instanceof Array?n=t.length>1?[t[0],t[1]]:"x"===o.axis?[null,t[0]]:[t[0],null]:(n[0]=t.y?t.y:t.x||"x"===o.axis?null:t,n[1]=t.x?t.x:t.y||"y"===o.axis?null:t),"function"==typeof n[0]&&(n[0]=n[0]()),"function"==typeof n[1]&&(n[1]=n[1]()),n},j=function(t,o){if(null!=t&&"undefined"!=typeof t){var n=e(this),i=n.data(a),r=i.opt,l=e("#mCSB_"+i.idx+"_container"),s=l.parent(),c=typeof t;o||(o="x"===r.axis?"x":"y");var d="x"===o?l.outerWidth(!1):l.outerHeight(!1),f="x"===o?l[0].offsetLeft:l[0].offsetTop,h="x"===o?"left":"top";switch(c){case"function":return t();case"object":var m=t.jquery?t:e(t);if(!m.length)return;return"x"===o?ot(m)[1]:ot(m)[0];case"string":case"number":if(tt(t))return Math.abs(t);if(-1!==t.indexOf("%"))return Math.abs(d*parseInt(t)/100);if(-1!==t.indexOf("-="))return Math.abs(f-parseInt(t.split("-=")[1]));if(-1!==t.indexOf("+=")){var p=f+parseInt(t.split("+=")[1]);return p>=0?0:Math.abs(p)}if(-1!==t.indexOf("px")&&tt(t.split("px")[0]))return Math.abs(t.split("px")[0]);if("top"===t||"left"===t)return 0;if("bottom"===t)return Math.abs(s.height()-l.outerHeight(!1));if("right"===t)return Math.abs(s.width()-l.outerWidth(!1));if("first"===t||"last"===t){var m=l.find(":"+t);return"x"===o?ot(m)[1]:ot(m)[0]}return e(t).length?"x"===o?ot(e(t))[1]:ot(e(t))[0]:(l.css(h,t),void u.update.call(null,n[0]))}}},X=function(t){function o(){clearTimeout(h[0].autoUpdate),h[0].autoUpdate=setTimeout(function(){return f.advanced.updateOnSelectorChange&&(m=r(),m!==w)?(l(3),void(w=m)):(f.advanced.updateOnContentResize&&(p=[h.outerHeight(!1),h.outerWidth(!1),v.height(),v.width(),_()[0],_()[1]],(p[0]!==S[0]||p[1]!==S[1]||p[2]!==S[2]||p[3]!==S[3]||p[4]!==S[4]||p[5]!==S[5])&&(l(p[0]!==S[0]||p[1]!==S[1]),S=p)),f.advanced.updateOnImageLoad&&(g=n(),g!==b&&(h.find("img").each(function(){i(this)}),b=g)),void((f.advanced.updateOnSelectorChange||f.advanced.updateOnContentResize||f.advanced.updateOnImageLoad)&&o()))},60)}function n(){var e=0;return f.advanced.updateOnImageLoad&&(e=h.find("img").length),e}function i(t){function o(e,t){return function(){return t.apply(e,arguments)}}function a(){this.onload=null,e(t).addClass(d[2]),l(2)}if(e(t).hasClass(d[2]))return void l();var n=new Image;n.onload=o(n,a),n.src=t.src}function r(){f.advanced.updateOnSelectorChange===!0&&(f.advanced.updateOnSelectorChange="*");var t=0,o=h.find(f.advanced.updateOnSelectorChange);return f.advanced.updateOnSelectorChange&&o.length>0&&o.each(function(){t+=e(this).height()+e(this).width()}),t}function l(e){clearTimeout(h[0].autoUpdate),u.update.call(null,s[0],e)}var s=e(this),c=s.data(a),f=c.opt,h=e("#mCSB_"+c.idx+"_container");if(t)return clearTimeout(h[0].autoUpdate),void Z(h[0],"autoUpdate");var m,p,g,v=h.parent(),x=[e("#mCSB_"+c.idx+"_scrollbar_vertical"),e("#mCSB_"+c.idx+"_scrollbar_horizontal")],_=function(){return[x[0].is(":visible")?x[0].outerHeight(!0):0,x[1].is(":visible")?x[1].outerWidth(!0):0]},w=r(),S=[h.outerHeight(!1),h.outerWidth(!1),v.height(),v.width(),_()[0],_()[1]],b=n();o()},N=function(e,t,o){return Math.round(e/t)*t-o},V=function(t){var o=t.data(a),n=e("#mCSB_"+o.idx+"_container,#mCSB_"+o.idx+"_container_wrapper,#mCSB_"+o.idx+"_dragger_vertical,#mCSB_"+o.idx+"_dragger_horizontal");n.each(function(){K.call(this)})},Q=function(t,o,n){function i(e){return s&&c.callbacks[e]&&"function"==typeof c.callbacks[e]}function r(){return[c.callbacks.alwaysTriggerOffsets||_>=w[0]+b,c.callbacks.alwaysTriggerOffsets||-C>=_]}function l(){var e=[h[0].offsetTop,h[0].offsetLeft],o=[v[0].offsetTop,v[0].offsetLeft],a=[h.outerHeight(!1),h.outerWidth(!1)],i=[f.height(),f.width()];t[0].mcs={content:h,top:e[0],left:e[1],draggerTop:o[0],draggerLeft:o[1],topPct:Math.round(100*Math.abs(e[0])/(Math.abs(a[0])-i[0])),leftPct:Math.round(100*Math.abs(e[1])/(Math.abs(a[1])-i[1])),direction:n.dir}}var s=t.data(a),c=s.opt,d={trigger:"internal",dir:"y",scrollEasing:"mcsEaseOut",drag:!1,dur:c.scrollInertia,overwrite:"all",callbacks:!0,onStart:!0,onUpdate:!0,onComplete:!0},n=e.extend(d,n),u=[n.dur,n.drag?0:n.dur],f=e("#mCSB_"+s.idx),h=e("#mCSB_"+s.idx+"_container"),m=h.parent(),p=c.callbacks.onTotalScrollOffset?Y.call(t,c.callbacks.onTotalScrollOffset):[0,0],g=c.callbacks.onTotalScrollBackOffset?Y.call(t,c.callbacks.onTotalScrollBackOffset):[0,0];
if(s.trigger=n.trigger,(0!==m.scrollTop()||0!==m.scrollLeft())&&(e(".mCSB_"+s.idx+"_scrollbar").css("visibility","visible"),m.scrollTop(0).scrollLeft(0)),"_resetY"!==o||s.contentReset.y||(i("onOverflowYNone")&&c.callbacks.onOverflowYNone.call(t[0]),s.contentReset.y=1),"_resetX"!==o||s.contentReset.x||(i("onOverflowXNone")&&c.callbacks.onOverflowXNone.call(t[0]),s.contentReset.x=1),"_resetY"!==o&&"_resetX"!==o){switch(!s.contentReset.y&&t[0].mcs||!s.overflowed[0]||(i("onOverflowY")&&c.callbacks.onOverflowY.call(t[0]),s.contentReset.x=null),!s.contentReset.x&&t[0].mcs||!s.overflowed[1]||(i("onOverflowX")&&c.callbacks.onOverflowX.call(t[0]),s.contentReset.x=null),c.snapAmount&&(o=N(o,c.snapAmount,c.snapOffset)),n.dir){case"x":var v=e("#mCSB_"+s.idx+"_dragger_horizontal"),x="left",_=h[0].offsetLeft,w=[f.width()-h.outerWidth(!1),v.parent().width()-v.width()],S=[o,0===o?0:o/s.scrollRatio.x],b=p[1],C=g[1],B=b>0?b/s.scrollRatio.x:0,T=C>0?C/s.scrollRatio.x:0;break;case"y":var v=e("#mCSB_"+s.idx+"_dragger_vertical"),x="top",_=h[0].offsetTop,w=[f.height()-h.outerHeight(!1),v.parent().height()-v.height()],S=[o,0===o?0:o/s.scrollRatio.y],b=p[0],C=g[0],B=b>0?b/s.scrollRatio.y:0,T=C>0?C/s.scrollRatio.y:0}S[1]<0||0===S[0]&&0===S[1]?S=[0,0]:S[1]>=w[1]?S=[w[0],w[1]]:S[0]=-S[0],t[0].mcs||(l(),i("onInit")&&c.callbacks.onInit.call(t[0])),clearTimeout(h[0].onCompleteTimeout),(s.tweenRunning||!(0===_&&S[0]>=0||_===w[0]&&S[0]<=w[0]))&&(G(v[0],x,Math.round(S[1]),u[1],n.scrollEasing),G(h[0],x,Math.round(S[0]),u[0],n.scrollEasing,n.overwrite,{onStart:function(){n.callbacks&&n.onStart&&!s.tweenRunning&&(i("onScrollStart")&&(l(),c.callbacks.onScrollStart.call(t[0])),s.tweenRunning=!0,y(v),s.cbOffsets=r())},onUpdate:function(){n.callbacks&&n.onUpdate&&i("whileScrolling")&&(l(),c.callbacks.whileScrolling.call(t[0]))},onComplete:function(){if(n.callbacks&&n.onComplete){"yx"===c.axis&&clearTimeout(h[0].onCompleteTimeout);var e=h[0].idleTimer||0;h[0].onCompleteTimeout=setTimeout(function(){i("onScroll")&&(l(),c.callbacks.onScroll.call(t[0])),i("onTotalScroll")&&S[1]>=w[1]-B&&s.cbOffsets[0]&&(l(),c.callbacks.onTotalScroll.call(t[0])),i("onTotalScrollBack")&&S[1]<=T&&s.cbOffsets[1]&&(l(),c.callbacks.onTotalScrollBack.call(t[0])),s.tweenRunning=!1,h[0].idleTimer=0,y(v,"hide")},e)}}}))}},G=function(e,t,o,a,n,i,r){function l(){S.stop||(x||m.call(),x=J()-v,s(),x>=S.time&&(S.time=x>S.time?x+f-(x-S.time):x+f-1,S.time<x+1&&(S.time=x+1)),S.time<a?S.id=h(l):g.call())}function s(){a>0?(S.currVal=u(S.time,_,b,a,n),w[t]=Math.round(S.currVal)+"px"):w[t]=o+"px",p.call()}function c(){f=1e3/60,S.time=x+f,h=window.requestAnimationFrame?window.requestAnimationFrame:function(e){return s(),setTimeout(e,.01)},S.id=h(l)}function d(){null!=S.id&&(window.requestAnimationFrame?window.cancelAnimationFrame(S.id):clearTimeout(S.id),S.id=null)}function u(e,t,o,a,n){switch(n){case"linear":case"mcsLinear":return o*e/a+t;case"mcsLinearOut":return e/=a,e--,o*Math.sqrt(1-e*e)+t;case"easeInOutSmooth":return e/=a/2,1>e?o/2*e*e+t:(e--,-o/2*(e*(e-2)-1)+t);case"easeInOutStrong":return e/=a/2,1>e?o/2*Math.pow(2,10*(e-1))+t:(e--,o/2*(-Math.pow(2,-10*e)+2)+t);case"easeInOut":case"mcsEaseInOut":return e/=a/2,1>e?o/2*e*e*e+t:(e-=2,o/2*(e*e*e+2)+t);case"easeOutSmooth":return e/=a,e--,-o*(e*e*e*e-1)+t;case"easeOutStrong":return o*(-Math.pow(2,-10*e/a)+1)+t;case"easeOut":case"mcsEaseOut":default:var i=(e/=a)*e,r=i*e;return t+o*(.499999999999997*r*i+-2.5*i*i+5.5*r+-6.5*i+4*e)}}e._mTween||(e._mTween={top:{},left:{}});var f,h,r=r||{},m=r.onStart||function(){},p=r.onUpdate||function(){},g=r.onComplete||function(){},v=J(),x=0,_=e.offsetTop,w=e.style,S=e._mTween[t];"left"===t&&(_=e.offsetLeft);var b=o-_;S.stop=0,"none"!==i&&d(),c()},J=function(){return window.performance&&window.performance.now?window.performance.now():window.performance&&window.performance.webkitNow?window.performance.webkitNow():Date.now?Date.now():(new Date).getTime()},K=function(){var e=this;e._mTween||(e._mTween={top:{},left:{}});for(var t=["top","left"],o=0;o<t.length;o++){var a=t[o];e._mTween[a].id&&(window.requestAnimationFrame?window.cancelAnimationFrame(e._mTween[a].id):clearTimeout(e._mTween[a].id),e._mTween[a].id=null,e._mTween[a].stop=1)}},Z=function(e,t){try{delete e[t]}catch(o){e[t]=null}},$=function(e){return!(e.which&&1!==e.which)},et=function(e){var t=e.originalEvent.pointerType;return!(t&&"touch"!==t&&2!==t)},tt=function(e){return!isNaN(parseFloat(e))&&isFinite(e)},ot=function(e){var t=e.parents(".mCSB_container");return[e.offset().top-t.offset().top,e.offset().left-t.offset().left]};e.fn[o]=function(t){return u[t]?u[t].apply(this,Array.prototype.slice.call(arguments,1)):"object"!=typeof t&&t?void e.error("Method "+t+" does not exist"):u.init.apply(this,arguments)},e[o]=function(t){return u[t]?u[t].apply(this,Array.prototype.slice.call(arguments,1)):"object"!=typeof t&&t?void e.error("Method "+t+" does not exist"):u.init.apply(this,arguments)},e[o].defaults=i,window[o]=!0,e(window).load(function(){e(n)[o](),e.extend(e.expr[":"],{mcsInView:e.expr[":"].mcsInView||function(t){var o,a,n=e(t),i=n.parents(".mCSB_container");if(i.length)return o=i.parent(),a=[i[0].offsetTop,i[0].offsetLeft],a[0]+ot(n)[0]>=0&&a[0]+ot(n)[0]<o.height()-n.outerHeight(!1)&&a[1]+ot(n)[1]>=0&&a[1]+ot(n)[1]<o.width()-n.outerWidth(!1)},mcsOverflow:e.expr[":"].mcsOverflow||function(t){var o=e(t).data(a);if(o)return o.overflowed[0]||o.overflowed[1]}})})})});	
	
var atag = 'a',imgtag = 'img', ifrtag = 'iframe';
//JS Cookie    
function createCookie(c,d,e){if(e){var b=new Date();b.setTime(b.getTime()+(e*24*60*60*1000));var a="; expires="+b.toGMTString()}else{var a=""}document.cookie=c+"="+d+a+"; path=/"}function readCookie(b){var e=b+"=";var a=document.cookie.split(";");for(var d=0;d<a.length;d++){var f=a[d];while(f.charAt(0)==" "){f=f.substring(1,f.length)}if(f.indexOf(e)==0){return f.substring(e.length,f.length)}}return null}function eraseCookie(a){createCookie(a,"",-1)};

//jquery replacetext plugin https://github.com/cowboy/jquery-replacetext
(function(e){e.fn.replaceText=function(t,n,r){return this.each(function(){var i=this.firstChild,s,o,u=[];if(i){do{if(i.nodeType===3){s=i.nodeValue;o=s.replace(t,n);if(o!==s){if(!r&&/</.test(o)){e(i).before(o);u.push(i)}else{i.nodeValue=o}}}}while(i=i.nextSibling)}u.length&&e(u).remove()})}})(jQuery);
function ts_isRTL(){var t=$("#dectdirect").hasClass("rtl")?!0:!1;return t}

// Simple Tab JQuery Plugin by Taufik Nurrohman https://plus.google.com/108949996304093815163/about
!function(a){a.fn.simpleTab=function(e){return e=jQuery.extend({active:1,fx:null,showSpeed:400,hideSpeed:400,showEasing:null,hideEasing:null,show:function(){},hide:function(){},change:function(){}},e),this.each(function(){var i=a(this),n=i.children("[data-tab]"),t=e.active-1;i.addClass("simpleTab").prepend('<ul class="tab-wrapper"></ul>'),n.addClass("tab-content").each(function(){a(this).hide(),i.find(".tab-wrapper").append("<li><"+atag+' href="#">'+a(this).data("tab")+"</"+atag+"></li>")}).eq(t).show(),i.find(".tab-wrapper a").on("click",function(){var i=a(this).parent().index();return a(this).closest(".tab-wrapper").find(".activeTab").removeClass("activeTab"),a(this).addClass("activeTab"),n.eq(i).is(":hidden")&&n.hide().eq(i).fadeIn(e.showSpeed),!1}).eq(t).addClass("activeTab")})}}(jQuery);

// JQuery hover event with timeout by Taufik Nurrohman https://plus.google.com/108949996304093815163/about
!function(n){n.fn.hoverTimeout=function(t,u,e,i){return this.each(function(){var o=null,c=n(this);c.hover(function(){clearTimeout(o),o=setTimeout(function(){u.call(c)},t)},function(){clearTimeout(o),o=setTimeout(function(){i.call(c)},e)})})}}(jQuery);

//jQuery OwlCarousel v2.00 - http://owlcarousel.owlgraphic.com/
!function(a,b,c,d){function e(b,c){this.settings=null,this.options=a.extend({},e.Defaults,c),this.$element=a(b),this._handlers={},this._plugins={},this._supress={},this._current=null,this._speed=null,this._coordinates=[],this._breakpoint=null,this._width=null,this._items=[],this._clones=[],this._mergers=[],this._widths=[],this._invalidated={},this._pipe=[],this._drag={time:null,target:null,pointer:null,stage:{start:null,current:null},direction:null},this._states={current:{},tags:{initializing:["busy"],animating:["busy"],dragging:["interacting"]}},a.each(["onResize","onThrottledResize"],a.proxy(function(b,c){this._handlers[c]=a.proxy(this[c],this)},this)),a.each(e.Plugins,a.proxy(function(a,b){this._plugins[a.charAt(0).toLowerCase()+a.slice(1)]=new b(this)},this)),a.each(e.Workers,a.proxy(function(b,c){this._pipe.push({filter:c.filter,run:a.proxy(c.run,this)})},this)),this.setup(),this.initialize()}e.Defaults={items:3,loop:!1,center:!1,rewind:!1,mouseDrag:!0,touchDrag:!0,pullDrag:!0,freeDrag:!1,margin:0,stagePadding:0,merge:!1,mergeFit:!0,autoWidth:!1,startPosition:0,rtl:!1,smartSpeed:250,fluidSpeed:!1,dragEndSpeed:!1,responsive:{},responsiveRefreshRate:200,responsiveBaseElement:b,fallbackEasing:"swing",info:!1,nestedItemSelector:!1,itemElement:"div",stageElement:"div",refreshClass:"owl-refresh",loadedClass:"owl-loaded",loadingClass:"owl-loading",rtlClass:"owl-rtl",responsiveClass:"owl-responsive",dragClass:"owl-drag",itemClass:"owl-item",stageClass:"owl-stage",stageOuterClass:"owl-stage-outer",grabClass:"owl-grab"},e.Width={Default:"default",Inner:"inner",Outer:"outer"},e.Type={Event:"event",State:"state"},e.Plugins={},e.Workers=[{filter:["width","settings"],run:function(){this._width=this.$element.width()}},{filter:["width","items","settings"],run:function(a){a.current=this._items&&this._items[this.relative(this._current)]}},{filter:["items","settings"],run:function(){this.$stage.children(".cloned").remove()}},{filter:["width","items","settings"],run:function(a){var b=this.settings.margin||"",c=!this.settings.autoWidth,d=this.settings.rtl,e={width:"auto","margin-left":d?b:"","margin-right":d?"":b};!c&&this.$stage.children().css(e),a.css=e}},{filter:["width","items","settings"],run:function(a){var b=(this.width()/this.settings.items).toFixed(3)-this.settings.margin,c=null,d=this._items.length,e=!this.settings.autoWidth,f=[];for(a.items={merge:!1,width:b};d--;)c=this._mergers[d],c=this.settings.mergeFit&&Math.min(c,this.settings.items)||c,a.items.merge=c>1||a.items.merge,f[d]=e?b*c:this._items[d].width();this._widths=f}},{filter:["items","settings"],run:function(){var b=[],c=this._items,d=this.settings,e=Math.max(2*d.items,4),f=2*Math.ceil(c.length/2),g=d.loop&&c.length?d.rewind?e:Math.max(e,f):0,h="",i="";for(g/=2;g--;)b.push(this.normalize(b.length/2,!0)),h+=c[b[b.length-1]][0].outerHTML,b.push(this.normalize(c.length-1-(b.length-1)/2,!0)),i=c[b[b.length-1]][0].outerHTML+i;this._clones=b,a(h).addClass("cloned").appendTo(this.$stage),a(i).addClass("cloned").prependTo(this.$stage)}},{filter:["width","items","settings"],run:function(){for(var a=this.settings.rtl?1:-1,b=this._clones.length+this._items.length,c=-1,d=0,e=0,f=[];++c<b;)d=f[c-1]||0,e=this._widths[this.relative(c)]+this.settings.margin,f.push(d+e*a);this._coordinates=f}},{filter:["width","items","settings"],run:function(){var a=this.settings.stagePadding,b=this._coordinates,c={width:Math.ceil(Math.abs(b[b.length-1]))+2*a,"padding-left":a||"","padding-right":a||""};this.$stage.css(c)}},{filter:["width","items","settings"],run:function(a){var b=this._coordinates.length,c=!this.settings.autoWidth,d=this.$stage.children();if(c&&a.items.merge)for(;b--;)a.css.width=this._widths[this.relative(b)],d.eq(b).css(a.css);else c&&(a.css.width=a.items.width,d.css(a.css))}},{filter:["items"],run:function(){this._coordinates.length<1&&this.$stage.removeAttr("style")}},{filter:["width","items","settings"],run:function(a){a.current=a.current?this.$stage.children().index(a.current):0,a.current=Math.max(this.minimum(),Math.min(this.maximum(),a.current)),this.reset(a.current)}},{filter:["position"],run:function(){this.animate(this.coordinates(this._current))}},{filter:["width","position","items","settings"],run:function(){var a,b,c,d,e=this.settings.rtl?1:-1,f=2*this.settings.stagePadding,g=this.coordinates(this.current())+f,h=g+this.width()*e,i=[];for(c=0,d=this._coordinates.length;d>c;c++)a=this._coordinates[c-1]||0,b=Math.abs(this._coordinates[c])+f*e,(this.op(a,"<=",g)&&this.op(a,">",h)||this.op(b,"<",g)&&this.op(b,">",h))&&i.push(c);this.$stage.children(".active").removeClass("active"),this.$stage.children(":eq("+i.join("), :eq(")+")").addClass("active"),this.settings.center&&(this.$stage.children(".center").removeClass("center"),this.$stage.children().eq(this.current()).addClass("center"))}}],e.prototype.initialize=function(){if(this.enter("initializing"),this.trigger("initialize"),this.$element.toggleClass(this.settings.rtlClass,this.settings.rtl),this.settings.autoWidth&&!this.is("pre-loading")){var b,c,e;b=this.$element.find("img"),c=this.settings.nestedItemSelector?"."+this.settings.nestedItemSelector:d,e=this.$element.children(c).width(),b.length&&0>=e&&this.preloadAutoWidthImages(b)}this.$element.addClass(this.options.loadingClass),this.$stage=a("<"+this.settings.stageElement+' class="'+this.settings.stageClass+'"/>').wrap('<div class="'+this.settings.stageOuterClass+'"/>'),this.$element.append(this.$stage.parent()),this.replace(this.$element.children().not(this.$stage.parent())),this.$element.is(":visible")?this.refresh():this.invalidate("width"),this.$element.removeClass(this.options.loadingClass).addClass(this.options.loadedClass),this.registerEventHandlers(),this.leave("initializing"),this.trigger("initialized")},e.prototype.setup=function(){var b=this.viewport(),c=this.options.responsive,d=-1,e=null;c?(a.each(c,function(a){b>=a&&a>d&&(d=Number(a))}),e=a.extend({},this.options,c[d]),delete e.responsive,e.responsiveClass&&this.$element.attr("class",this.$element.attr("class").replace(new RegExp("("+this.options.responsiveClass+"-)\\S+\\s","g"),"$1"+d))):e=a.extend({},this.options),(null===this.settings||this._breakpoint!==d)&&(this.trigger("change",{property:{name:"settings",value:e}}),this._breakpoint=d,this.settings=e,this.invalidate("settings"),this.trigger("changed",{property:{name:"settings",value:this.settings}}))},e.prototype.optionsLogic=function(){this.settings.autoWidth&&(this.settings.stagePadding=!1,this.settings.merge=!1)},e.prototype.prepare=function(b){var c=this.trigger("prepare",{content:b});return c.data||(c.data=a("<"+this.settings.itemElement+"/>").addClass(this.options.itemClass).append(b)),this.trigger("prepared",{content:c.data}),c.data},e.prototype.update=function(){for(var b=0,c=this._pipe.length,d=a.proxy(function(a){return this[a]},this._invalidated),e={};c>b;)(this._invalidated.all||a.grep(this._pipe[b].filter,d).length>0)&&this._pipe[b].run(e),b++;this._invalidated={},!this.is("valid")&&this.enter("valid")},e.prototype.width=function(a){switch(a=a||e.Width.Default){case e.Width.Inner:case e.Width.Outer:return this._width;default:return this._width-2*this.settings.stagePadding+this.settings.margin}},e.prototype.refresh=function(){this.enter("refreshing"),this.trigger("refresh"),this.setup(),this.optionsLogic(),this.$element.addClass(this.options.refreshClass),this.update(),this.$element.removeClass(this.options.refreshClass),this.leave("refreshing"),this.trigger("refreshed")},e.prototype.onThrottledResize=function(){b.clearTimeout(this.resizeTimer),this.resizeTimer=b.setTimeout(this._handlers.onResize,this.settings.responsiveRefreshRate)},e.prototype.onResize=function(){return this._items.length?this._width===this.$element.width()?!1:this.$element.is(":visible")?(this.enter("resizing"),this.trigger("resize").isDefaultPrevented()?(this.leave("resizing"),!1):(this.invalidate("width"),this.refresh(),this.leave("resizing"),void this.trigger("resized"))):!1:!1},e.prototype.registerEventHandlers=function(){a.support.transition&&this.$stage.on(a.support.transition.end+".owl.core",a.proxy(this.onTransitionEnd,this)),this.settings.responsive!==!1&&this.on(b,"resize",this._handlers.onThrottledResize),this.settings.mouseDrag&&(this.$element.addClass(this.options.dragClass),this.$stage.on("mousedown.owl.core",a.proxy(this.onDragStart,this)),this.$stage.on("dragstart.owl.core selectstart.owl.core",function(){return!1})),this.settings.touchDrag&&(this.$stage.on("touchstart.owl.core",a.proxy(this.onDragStart,this)),this.$stage.on("touchcancel.owl.core",a.proxy(this.onDragEnd,this)))},e.prototype.onDragStart=function(b){var d=null;3!==b.which&&(a.support.transform?(d=this.$stage.css("transform").replace(/.*\(|\)| /g,"").split(","),d={x:d[16===d.length?12:4],y:d[16===d.length?13:5]}):(d=this.$stage.position(),d={x:this.settings.rtl?d.left+this.$stage.width()-this.width()+this.settings.margin:d.left,y:d.top}),this.is("animating")&&(a.support.transform?this.animate(d.x):this.$stage.stop(),this.invalidate("position")),this.$element.toggleClass(this.options.grabClass,"mousedown"===b.type),this.speed(0),this._drag.time=(new Date).getTime(),this._drag.target=a(b.target),this._drag.stage.start=d,this._drag.stage.current=d,this._drag.pointer=this.pointer(b),a(c).on("mouseup.owl.core touchend.owl.core",a.proxy(this.onDragEnd,this)),a(c).one("mousemove.owl.core touchmove.owl.core",a.proxy(function(b){var d=this.difference(this._drag.pointer,this.pointer(b));a(c).on("mousemove.owl.core touchmove.owl.core",a.proxy(this.onDragMove,this)),Math.abs(d.x)<Math.abs(d.y)&&this.is("valid")||(b.preventDefault(),this.enter("dragging"),this.trigger("drag"))},this)))},e.prototype.onDragMove=function(a){var b=null,c=null,d=null,e=this.difference(this._drag.pointer,this.pointer(a)),f=this.difference(this._drag.stage.start,e);this.is("dragging")&&(a.preventDefault(),this.settings.loop?(b=this.coordinates(this.minimum()),c=this.coordinates(this.maximum()+1)-b,f.x=((f.x-b)%c+c)%c+b):(b=this.coordinates(this.settings.rtl?this.maximum():this.minimum()),c=this.coordinates(this.settings.rtl?this.minimum():this.maximum()),d=this.settings.pullDrag?-1*e.x/5:0,f.x=Math.max(Math.min(f.x,b+d),c+d)),this._drag.stage.current=f,this.animate(f.x))},e.prototype.onDragEnd=function(b){var d=this.difference(this._drag.pointer,this.pointer(b)),e=this._drag.stage.current,f=d.x>0^this.settings.rtl?"left":"right";a(c).off(".owl.core"),this.$element.removeClass(this.options.grabClass),(0!==d.x&&this.is("dragging")||!this.is("valid"))&&(this.speed(this.settings.dragEndSpeed||this.settings.smartSpeed),this.current(this.closest(e.x,0!==d.x?f:this._drag.direction)),this.invalidate("position"),this.update(),this._drag.direction=f,(Math.abs(d.x)>3||(new Date).getTime()-this._drag.time>300)&&this._drag.target.one("click.owl.core",function(){return!1})),this.is("dragging")&&(this.leave("dragging"),this.trigger("dragged"))},e.prototype.closest=function(b,c){var d=-1,e=30,f=this.width(),g=this.coordinates();return this.settings.freeDrag||a.each(g,a.proxy(function(a,h){return b>h-e&&h+e>b?d=a:this.op(b,"<",h)&&this.op(b,">",g[a+1]||h-f)&&(d="left"===c?a+1:a),-1===d},this)),this.settings.loop||(this.op(b,">",g[this.minimum()])?d=b=this.minimum():this.op(b,"<",g[this.maximum()])&&(d=b=this.maximum())),d},e.prototype.animate=function(b){var c=this.speed()>0;this.is("animating")&&this.onTransitionEnd(),c&&(this.enter("animating"),this.trigger("translate")),a.support.transform3d&&a.support.transition?this.$stage.css({transform:"translate3d("+b+"px,0px,0px)",transition:this.speed()/1e3+"s"}):c?this.$stage.animate({left:b+"px"},this.speed(),this.settings.fallbackEasing,a.proxy(this.onTransitionEnd,this)):this.$stage.css({left:b+"px"})},e.prototype.is=function(a){return this._states.current[a]&&this._states.current[a]>0},e.prototype.current=function(a){if(a===d)return this._current;if(0===this._items.length)return d;if(a=this.normalize(a),this._current!==a){var b=this.trigger("change",{property:{name:"position",value:a}});b.data!==d&&(a=this.normalize(b.data)),this._current=a,this.invalidate("position"),this.trigger("changed",{property:{name:"position",value:this._current}})}return this._current},e.prototype.invalidate=function(b){return"string"===a.type(b)&&(this._invalidated[b]=!0,this.is("valid")&&this.leave("valid")),a.map(this._invalidated,function(a,b){return b})},e.prototype.reset=function(a){a=this.normalize(a),a!==d&&(this._speed=0,this._current=a,this.suppress(["translate","translated"]),this.animate(this.coordinates(a)),this.release(["translate","translated"]))},e.prototype.normalize=function(b,c){var e=this._items.length,f=c?0:this._clones.length;return!a.isNumeric(b)||1>e?b=d:(0>b||b>=e+f)&&(b=((b-f/2)%e+e)%e+f/2),b},e.prototype.relative=function(a){return a-=this._clones.length/2,this.normalize(a,!0)},e.prototype.maximum=function(a){var b,c=this.settings,d=this._coordinates.length,e=Math.abs(this._coordinates[d-1])-this._width,f=-1;if(c.loop)d=this._clones.length/2+this._items.length-1;else if(c.autoWidth||c.merge)for(;d-f>1;)Math.abs(this._coordinates[b=d+f>>1])<e?f=b:d=b;else d=c.center?this._items.length-1:this._items.length-c.items;return a&&(d-=this._clones.length/2),Math.max(d,0)},e.prototype.minimum=function(a){return a?0:this._clones.length/2},e.prototype.items=function(a){return a===d?this._items.slice():(a=this.normalize(a,!0),this._items[a])},e.prototype.mergers=function(a){return a===d?this._mergers.slice():(a=this.normalize(a,!0),this._mergers[a])},e.prototype.clones=function(b){var c=this._clones.length/2,e=c+this._items.length,f=function(a){return a%2===0?e+a/2:c-(a+1)/2};return b===d?a.map(this._clones,function(a,b){return f(b)}):a.map(this._clones,function(a,c){return a===b?f(c):null})},e.prototype.speed=function(a){return a!==d&&(this._speed=a),this._speed},e.prototype.coordinates=function(b){var c=null;return b===d?a.map(this._coordinates,a.proxy(function(a,b){return this.coordinates(b)},this)):(this.settings.center?(c=this._coordinates[b],c+=(this.width()-c+(this._coordinates[b-1]||0))/2*(this.settings.rtl?-1:1)):c=this._coordinates[b-1]||0,c)},e.prototype.duration=function(a,b,c){return Math.min(Math.max(Math.abs(b-a),1),6)*Math.abs(c||this.settings.smartSpeed)},e.prototype.to=function(a,b){var c=this.current(),d=null,e=a-this.relative(c),f=(e>0)-(0>e),g=this._items.length,h=this.minimum(),i=this.maximum();this.settings.loop?(!this.settings.rewind&&Math.abs(e)>g/2&&(e+=-1*f*g),a=c+e,d=((a-h)%g+g)%g+h,d!==a&&i>=d-e&&d-e>0&&(c=d-e,a=d,this.reset(c))):this.settings.rewind?(i+=1,a=(a%i+i)%i):a=Math.max(h,Math.min(i,a)),this.speed(this.duration(c,a,b)),this.current(a),this.$element.is(":visible")&&this.update()},e.prototype.next=function(a){a=a||!1,this.to(this.relative(this.current())+1,a)},e.prototype.prev=function(a){a=a||!1,this.to(this.relative(this.current())-1,a)},e.prototype.onTransitionEnd=function(a){return a!==d&&(a.stopPropagation(),(a.target||a.srcElement||a.originalTarget)!==this.$stage.get(0))?!1:(this.leave("animating"),void this.trigger("translated"))},e.prototype.viewport=function(){var d;if(this.options.responsiveBaseElement!==b)d=a(this.options.responsiveBaseElement).width();else if(b.innerWidth)d=b.innerWidth;else{if(!c.documentElement||!c.documentElement.clientWidth)throw"Can not detect viewport width.";d=c.documentElement.clientWidth}return d},e.prototype.replace=function(b){this.$stage.empty(),this._items=[],b&&(b=b instanceof jQuery?b:a(b)),this.settings.nestedItemSelector&&(b=b.find("."+this.settings.nestedItemSelector)),b.filter(function(){return 1===this.nodeType}).each(a.proxy(function(a,b){b=this.prepare(b),this.$stage.append(b),this._items.push(b),this._mergers.push(1*b.find("[data-merge]").andSelf("[data-merge]").attr("data-merge")||1)},this)),this.reset(a.isNumeric(this.settings.startPosition)?this.settings.startPosition:0),this.invalidate("items")},e.prototype.add=function(b,c){var e=this.relative(this._current);c=c===d?this._items.length:this.normalize(c,!0),b=b instanceof jQuery?b:a(b),this.trigger("add",{content:b,position:c}),b=this.prepare(b),0===this._items.length||c===this._items.length?(0===this._items.length&&this.$stage.append(b),0!==this._items.length&&this._items[c-1].after(b),this._items.push(b),this._mergers.push(1*b.find("[data-merge]").andSelf("[data-merge]").attr("data-merge")||1)):(this._items[c].before(b),this._items.splice(c,0,b),this._mergers.splice(c,0,1*b.find("[data-merge]").andSelf("[data-merge]").attr("data-merge")||1)),this._items[e]&&this.reset(this._items[e].index()),this.invalidate("items"),this.trigger("added",{content:b,position:c})},e.prototype.remove=function(a){a=this.normalize(a,!0),a!==d&&(this.trigger("remove",{content:this._items[a],position:a}),this._items[a].remove(),this._items.splice(a,1),this._mergers.splice(a,1),this.invalidate("items"),this.trigger("removed",{content:null,position:a}))},e.prototype.preloadAutoWidthImages=function(b){b.each(a.proxy(function(b,c){this.enter("pre-loading"),c=a(c),a(new Image).one("load",a.proxy(function(a){c.attr("src",a.target.src),c.css("opacity",1),this.leave("pre-loading"),!this.is("pre-loading")&&!this.is("initializing")&&this.refresh()},this)).attr("src",c.attr("src")||c.attr("data-src")||c.attr("data-src-retina"))},this))},e.prototype.destroy=function(){this.$element.off(".owl.core"),this.$stage.off(".owl.core"),a(c).off(".owl.core"),this.settings.responsive!==!1&&(b.clearTimeout(this.resizeTimer),this.off(b,"resize",this._handlers.onThrottledResize));for(var d in this._plugins)this._plugins[d].destroy();this.$stage.children(".cloned").remove(),this.$stage.unwrap(),this.$stage.children().contents().unwrap(),this.$stage.children().unwrap(),this.$element.removeClass(this.options.refreshClass).removeClass(this.options.loadingClass).removeClass(this.options.loadedClass).removeClass(this.options.rtlClass).removeClass(this.options.dragClass).removeClass(this.options.grabClass).attr("class",this.$element.attr("class").replace(new RegExp(this.options.responsiveClass+"-\\S+\\s","g"),"")).removeData("owl.carousel")},e.prototype.op=function(a,b,c){var d=this.settings.rtl;switch(b){case"<":return d?a>c:c>a;case">":return d?c>a:a>c;case">=":return d?c>=a:a>=c;case"<=":return d?a>=c:c>=a}},e.prototype.on=function(a,b,c,d){a.addEventListener?a.addEventListener(b,c,d):a.attachEvent&&a.attachEvent("on"+b,c)},e.prototype.off=function(a,b,c,d){a.removeEventListener?a.removeEventListener(b,c,d):a.detachEvent&&a.detachEvent("on"+b,c)},e.prototype.trigger=function(b,c,d,f,g){var h={item:{count:this._items.length,index:this.current()}},i=a.camelCase(a.grep(["on",b,d],function(a){return a}).join("-").toLowerCase()),j=a.Event([b,"owl",d||"carousel"].join(".").toLowerCase(),a.extend({relatedTarget:this},h,c));return this._supress[b]||(a.each(this._plugins,function(a,b){b.onTrigger&&b.onTrigger(j)}),this.register({type:e.Type.Event,name:b}),this.$element.trigger(j),this.settings&&"function"==typeof this.settings[i]&&this.settings[i].call(this,j)),j},e.prototype.enter=function(b){a.each([b].concat(this._states.tags[b]||[]),a.proxy(function(a,b){this._states.current[b]===d&&(this._states.current[b]=0),this._states.current[b]++},this))},e.prototype.leave=function(b){a.each([b].concat(this._states.tags[b]||[]),a.proxy(function(a,b){this._states.current[b]--},this))},e.prototype.register=function(b){if(b.type===e.Type.Event){if(a.event.special[b.name]||(a.event.special[b.name]={}),!a.event.special[b.name].owl){var c=a.event.special[b.name]._default;a.event.special[b.name]._default=function(a){return!c||!c.apply||a.namespace&&-1!==a.namespace.indexOf("owl")?a.namespace&&a.namespace.indexOf("owl")>-1:c.apply(this,arguments)},a.event.special[b.name].owl=!0}}else b.type===e.Type.State&&(this._states.tags[b.name]?this._states.tags[b.name]=this._states.tags[b.name].concat(b.tags):this._states.tags[b.name]=b.tags,this._states.tags[b.name]=a.grep(this._states.tags[b.name],a.proxy(function(c,d){return a.inArray(c,this._states.tags[b.name])===d},this)))},e.prototype.suppress=function(b){a.each(b,a.proxy(function(a,b){this._supress[b]=!0},this))},e.prototype.release=function(b){a.each(b,a.proxy(function(a,b){delete this._supress[b]},this))},e.prototype.pointer=function(a){var c={x:null,y:null};return a=a.originalEvent||a||b.event,a=a.touches&&a.touches.length?a.touches[0]:a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:a,a.pageX?(c.x=a.pageX,c.y=a.pageY):(c.x=a.clientX,c.y=a.clientY),c},e.prototype.difference=function(a,b){return{x:a.x-b.x,y:a.y-b.y}},a.fn.owlCarousel=function(b){var c=Array.prototype.slice.call(arguments,1);return this.each(function(){var d=a(this),f=d.data("owl.carousel");f||(f=new e(this,"object"==typeof b&&b),d.data("owl.carousel",f),a.each(["next","prev","to","destroy","refresh","replace","add","remove"],function(b,c){f.register({type:e.Type.Event,name:c}),f.$element.on(c+".owl.carousel.core",a.proxy(function(a){a.namespace&&a.relatedTarget!==this&&(this.suppress([c]),f[c].apply(this,[].slice.call(arguments,1)),this.release([c]))},f))})),"string"==typeof b&&"_"!==b.charAt(0)&&f[b].apply(f,c)})},a.fn.owlCarousel.Constructor=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._interval=null,this._visible=null,this._handlers={"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoRefresh&&this.watch()},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers)};e.Defaults={autoRefresh:!0,autoRefreshInterval:500},e.prototype.watch=function(){this._interval||(this._visible=this._core.$element.is(":visible"),this._interval=b.setInterval(a.proxy(this.refresh,this),this._core.settings.autoRefreshInterval))},e.prototype.refresh=function(){this._core.$element.is(":visible")!==this._visible&&(this._visible=!this._visible,this._core.$element.toggleClass("owl-hidden",!this._visible),this._visible&&this._core.invalidate("width")&&this._core.refresh())},e.prototype.destroy=function(){var a,c;b.clearInterval(this._interval);for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},a.fn.owlCarousel.Constructor.Plugins.AutoRefresh=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._loaded=[],this._handlers={"initialized.owl.carousel change.owl.carousel":a.proxy(function(b){if(b.namespace&&this._core.settings&&this._core.settings.lazyLoad&&(b.property&&"position"==b.property.name||"initialized"==b.type))for(var c=this._core.settings,d=c.center&&Math.ceil(c.items/2)||c.items,e=c.center&&-1*d||0,f=(b.property&&b.property.value||this._core.current())+e,g=this._core.clones().length,h=a.proxy(function(a,b){this.load(b)},this);e++<d;)this.load(g/2+this._core.relative(f)),g&&a.each(this._core.clones(this._core.relative(f)),h),f++},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers)};e.Defaults={lazyLoad:!1},e.prototype.load=function(c){var d=this._core.$stage.children().eq(c),e=d&&d.find(".owl-lazy");!e||a.inArray(d.get(0),this._loaded)>-1||(e.each(a.proxy(function(c,d){var e,f=a(d),g=b.devicePixelRatio>1&&f.attr("data-src-retina")||f.attr("data-src");this._core.trigger("load",{element:f,url:g},"lazy"),f.is("img")?f.one("load.owl.lazy",a.proxy(function(){f.css("opacity",1),this._core.trigger("loaded",{element:f,url:g},"lazy")},this)).attr("src",g):(e=new Image,e.onload=a.proxy(function(){f.css({"background-image":"url("+g+")",opacity:"1"}),this._core.trigger("loaded",{element:f,url:g},"lazy")},this),e.src=g)},this)),this._loaded.push(d.get(0)))},e.prototype.destroy=function(){var a,b;for(a in this.handlers)this._core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Lazy=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._handlers={"initialized.owl.carousel refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&this.update()},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&"position"==a.property.name&&this.update()},this),"loaded.owl.lazy":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&a.element.closest("."+this._core.settings.itemClass).index()===this._core.current()&&this.update()},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers)};e.Defaults={autoHeight:!1,autoHeightClass:"owl-height"},e.prototype.update=function(){var b=this._core._current,c=b+this._core.settings.items,d=this._core.$stage.children().toArray().slice(b,c);heights=[],maxheight=0,a.each(d,function(b,c){heights.push(a(c).height())}),maxheight=Math.max.apply(null,heights),this._core.$stage.parent().height(maxheight).addClass(this._core.settings.autoHeightClass)},e.prototype.destroy=function(){var a,b;for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.AutoHeight=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._videos={},this._playing=null,this._handlers={"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.register({type:"state",name:"playing",tags:["interacting"]})},this),"resize.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.video&&this.isInFullScreen()&&a.preventDefault()},this),"refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.is("resizing")&&this._core.$stage.find(".cloned .owl-video-frame").remove()},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&"position"===a.property.name&&this._playing&&this.stop()},this),"prepared.owl.carousel":a.proxy(function(b){if(b.namespace){var c=a(b.content).find(".owl-video");c.length&&(c.css("display","none"),this.fetch(c,a(b.content)))}},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers),this._core.$element.on("click.owl.video",".owl-video-play-icon",a.proxy(function(a){this.play(a)},this))};e.Defaults={video:!1,videoHeight:!1,videoWidth:!1},e.prototype.fetch=function(a,b){var c=a.attr("data-vimeo-id")?"vimeo":"youtube",d=a.attr("data-vimeo-id")||a.attr("data-youtube-id"),e=a.attr("data-width")||this._core.settings.videoWidth,f=a.attr("data-height")||this._core.settings.videoHeight,g=a.attr("href");if(!g)throw new Error("Missing video URL.");if(d=g.match(/(http:|https:|)\/\/(player.|www.)?(vimeo\.com|youtu(be\.com|\.be|be\.googleapis\.com))\/(video\/|embed\/|watch\?v=|v\/)?([A-Za-z0-9._%-]*)(\&\S+)?/),d[3].indexOf("youtu")>-1)c="youtube";else{if(!(d[3].indexOf("vimeo")>-1))throw new Error("Video URL not supported.");c="vimeo"}d=d[6],this._videos[g]={type:c,id:d,width:e,height:f},b.attr("data-video",g),this.thumbnail(a,this._videos[g])},e.prototype.thumbnail=function(b,c){var d,e,f,g=c.width&&c.height?'style="width:'+c.width+"px;height:"+c.height+'px;"':"",h=b.find("img"),i="src",j="",k=this._core.settings,l=function(a){e='<div class="owl-video-play-icon"></div>',d=k.lazyLoad?'<div class="owl-video-tn '+j+'" '+i+'="'+a+'"></div>':'<div class="owl-video-tn" style="opacity:1;background-image:url('+a+')"></div>',b.after(d),b.after(e)};return b.wrap('<div class="owl-video-wrapper"'+g+"></div>"),this._core.settings.lazyLoad&&(i="data-src",j="owl-lazy"),h.length?(l(h.attr(i)),h.remove(),!1):void("youtube"===c.type?(f="http://img.youtube.com/vi/"+c.id+"/hqdefault.jpg",l(f)):"vimeo"===c.type&&a.ajax({type:"GET",url:"http://vimeo.com/api/v2/video/"+c.id+".json",jsonp:"callback",dataType:"jsonp",success:function(a){f=a[0].thumbnail_large,l(f)}}))},e.prototype.stop=function(){this._core.trigger("stop",null,"video"),this._playing.find(".owl-video-frame").remove(),this._playing.removeClass("owl-video-playing"),this._playing=null,this._core.leave("playing"),this._core.trigger("stopped",null,"video")},e.prototype.play=function(b){var c,d=a(b.target),e=d.closest("."+this._core.settings.itemClass),f=this._videos[e.attr("data-video")],g=f.width||"100%",h=f.height||this._core.$stage.height();this._playing||(this._core.enter("playing"),this._core.trigger("play",null,"video"),e=this._core.items(this._core.relative(e.index())),this._core.reset(e.index()),"youtube"===f.type?c='<iframe width="'+g+'" height="'+h+'" src="http://www.youtube.com/embed/'+f.id+"?autoplay=1&v="+f.id+'" frameborder="0" allowfullscreen></iframe>':"vimeo"===f.type&&(c='<iframe src="http://player.vimeo.com/video/'+f.id+'?autoplay=1" width="'+g+'" height="'+h+'" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>'),a('<div class="owl-video-frame">'+c+"</div>").insertAfter(e.find(".owl-video")),this._playing=e.addClass("owl-video-playing"))},e.prototype.isInFullScreen=function(){var b=c.fullscreenElement||c.mozFullScreenElement||c.webkitFullscreenElement;return b&&a(b).parent().hasClass("owl-video-frame")},e.prototype.destroy=function(){var a,b;this._core.$element.off("click.owl.video");for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Video=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this.core=b,this.core.options=a.extend({},e.Defaults,this.core.options),this.swapping=!0,this.previous=d,this.next=d,this.handlers={"change.owl.carousel":a.proxy(function(a){a.namespace&&"position"==a.property.name&&(this.previous=this.core.current(),this.next=a.property.value)},this),"drag.owl.carousel dragged.owl.carousel translated.owl.carousel":a.proxy(function(a){a.namespace&&(this.swapping="translated"==a.type)},this),"translate.owl.carousel":a.proxy(function(a){a.namespace&&this.swapping&&(this.core.options.animateOut||this.core.options.animateIn)&&this.swap()},this)},this.core.$element.on(this.handlers)};e.Defaults={animateOut:!1,animateIn:!1},e.prototype.swap=function(){if(1===this.core.settings.items&&a.support.animation&&a.support.transition){this.core.speed(0);var b,c=a.proxy(this.clear,this),d=this.core.$stage.children().eq(this.previous),e=this.core.$stage.children().eq(this.next),f=this.core.settings.animateIn,g=this.core.settings.animateOut;this.core.current()!==this.previous&&(g&&(b=this.core.coordinates(this.previous)-this.core.coordinates(this.next),d.one(a.support.animation.end,c).css({left:b+"px"}).addClass("animated owl-animated-out").addClass(g)),f&&e.one(a.support.animation.end,c).addClass("animated owl-animated-in").addClass(f))}},e.prototype.clear=function(b){a(b.target).css({left:""}).removeClass("animated owl-animated-out owl-animated-in").removeClass(this.core.settings.animateIn).removeClass(this.core.settings.animateOut),this.core.onTransitionEnd()},e.prototype.destroy=function(){var a,b;for(a in this.handlers)this.core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Animate=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._interval=null,this._paused=!1,this._handlers={"changed.owl.carousel":a.proxy(function(a){a.namespace&&"settings"===a.property.name&&(this._core.settings.autoplay?this.play():this.stop())},this),"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoplay&&this.play()},this),"play.owl.autoplay":a.proxy(function(a,b,c){a.namespace&&this.play(b,c)},this),"stop.owl.autoplay":a.proxy(function(a){a.namespace&&this.stop()},this),"mouseover.owl.autoplay":a.proxy(function(){this._core.settings.autoplayHoverPause&&this._core.is("rotating")&&this.pause()},this),"mouseleave.owl.autoplay":a.proxy(function(){
this._core.settings.autoplayHoverPause&&this._core.is("rotating")&&this.play()},this)},this._core.$element.on(this._handlers),this._core.options=a.extend({},e.Defaults,this._core.options)};e.Defaults={autoplay:!1,autoplayTimeout:5e3,autoplayHoverPause:!1,autoplaySpeed:!1},e.prototype.play=function(d,e){this._paused=!1,this._core.is("rotating")||(this._core.enter("rotating"),this._interval=b.setInterval(a.proxy(function(){this._paused||this._core.is("busy")||this._core.is("interacting")||c.hidden||this._core.next(e||this._core.settings.autoplaySpeed)},this),d||this._core.settings.autoplayTimeout))},e.prototype.stop=function(){this._core.is("rotating")&&(b.clearInterval(this._interval),this._core.leave("rotating"))},e.prototype.pause=function(){this._core.is("rotating")&&(this._paused=!0)},e.prototype.destroy=function(){var a,b;this.stop();for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.autoplay=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){"use strict";var e=function(b){this._core=b,this._initialized=!1,this._pages=[],this._controls={},this._templates=[],this.$element=this._core.$element,this._overrides={next:this._core.next,prev:this._core.prev,to:this._core.to},this._handlers={"prepared.owl.carousel":a.proxy(function(b){b.namespace&&this._core.settings.dotsData&&this._templates.push('<div class="'+this._core.settings.dotClass+'">'+a(b.content).find("[data-dot]").andSelf("[data-dot]").attr("data-dot")+"</div>")},this),"added.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.dotsData&&this._templates.splice(a.position,0,this._templates.pop())},this),"remove.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.dotsData&&this._templates.splice(a.position,1)},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&"position"==a.property.name&&this.draw()},this),"initialized.owl.carousel":a.proxy(function(a){a.namespace&&!this._initialized&&(this._core.trigger("initialize",null,"navigation"),this.initialize(),this.update(),this.draw(),this._initialized=!0,this._core.trigger("initialized",null,"navigation"))},this),"refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._initialized&&(this._core.trigger("refresh",null,"navigation"),this.update(),this.draw(),this._core.trigger("refreshed",null,"navigation"))},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this.$element.on(this._handlers)};e.Defaults={nav:!1,navText:["prev","next"],navSpeed:!1,navElement:"div",navContainer:!1,navContainerClass:"owl-nav",navClass:["owl-prev","owl-next"],slideBy:1,dotClass:"owl-dot",dotsClass:"owl-dots",dots:!0,dotsEach:!1,dotsData:!1,dotsSpeed:!1,dotsContainer:!1},e.prototype.initialize=function(){var b,c=this._core.settings;this._controls.$relative=(c.navContainer?a(c.navContainer):a("<div>").addClass(c.navContainerClass).appendTo(this.$element)).addClass("disabled"),this._controls.$previous=a("<"+c.navElement+">").addClass(c.navClass[0]).html(c.navText[0]).prependTo(this._controls.$relative).on("click",a.proxy(function(a){this.prev(c.navSpeed)},this)),this._controls.$next=a("<"+c.navElement+">").addClass(c.navClass[1]).html(c.navText[1]).appendTo(this._controls.$relative).on("click",a.proxy(function(a){this.next(c.navSpeed)},this)),c.dotsData||(this._templates=[a("<div>").addClass(c.dotClass).append(a("<span>")).prop("outerHTML")]),this._controls.$absolute=(c.dotsContainer?a(c.dotsContainer):a("<div>").addClass(c.dotsClass).appendTo(this.$element)).addClass("disabled"),this._controls.$absolute.on("click","div",a.proxy(function(b){var d=a(b.target).parent().is(this._controls.$absolute)?a(b.target).index():a(b.target).parent().index();b.preventDefault(),this.to(d,c.dotsSpeed)},this));for(b in this._overrides)this._core[b]=a.proxy(this[b],this)},e.prototype.destroy=function(){var a,b,c,d;for(a in this._handlers)this.$element.off(a,this._handlers[a]);for(b in this._controls)this._controls[b].remove();for(d in this.overides)this._core[d]=this._overrides[d];for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},e.prototype.update=function(){var a,b,c,d=this._core.clones().length/2,e=d+this._core.items().length,f=this._core.maximum(!0),g=this._core.settings,h=g.center||g.autoWidth||g.dotsData?1:g.dotsEach||g.items;if("page"!==g.slideBy&&(g.slideBy=Math.min(g.slideBy,g.items)),g.dots||"page"==g.slideBy)for(this._pages=[],a=d,b=0,c=0;e>a;a++){if(b>=h||0===b){if(this._pages.push({start:Math.min(f,a-d),end:a-d+h-1}),Math.min(f,a-d)===f)break;b=0,++c}b+=this._core.mergers(this._core.relative(a))}},e.prototype.draw=function(){var b,c=this._core.settings,d=this._core.items().length<=c.items,e=this._core.relative(this._core.current()),f=c.loop||c.rewind;this._controls.$relative.toggleClass("disabled",!c.nav||d),c.nav&&(this._controls.$previous.toggleClass("disabled",!f&&e<=this._core.minimum(!0)),this._controls.$next.toggleClass("disabled",!f&&e>=this._core.maximum(!0))),this._controls.$absolute.toggleClass("disabled",!c.dots||d),c.dots&&(b=this._pages.length-this._controls.$absolute.children().length,c.dotsData&&0!==b?this._controls.$absolute.html(this._templates.join("")):b>0?this._controls.$absolute.append(new Array(b+1).join(this._templates[0])):0>b&&this._controls.$absolute.children().slice(b).remove(),this._controls.$absolute.find(".active").removeClass("active"),this._controls.$absolute.children().eq(a.inArray(this.current(),this._pages)).addClass("active"))},e.prototype.onTrigger=function(b){var c=this._core.settings;b.page={index:a.inArray(this.current(),this._pages),count:this._pages.length,size:c&&(c.center||c.autoWidth||c.dotsData?1:c.dotsEach||c.items)}},e.prototype.current=function(){var b=this._core.relative(this._core.current());return a.grep(this._pages,a.proxy(function(a,c){return a.start<=b&&a.end>=b},this)).pop()},e.prototype.getPosition=function(b){var c,d,e=this._core.settings;return"page"==e.slideBy?(c=a.inArray(this.current(),this._pages),d=this._pages.length,b?++c:--c,c=this._pages[(c%d+d)%d].start):(c=this._core.relative(this._core.current()),d=this._core.items().length,b?c+=e.slideBy:c-=e.slideBy),c},e.prototype.next=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!0),b)},e.prototype.prev=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!1),b)},e.prototype.to=function(b,c,d){var e;d?a.proxy(this._overrides.to,this._core)(b,c):(e=this._pages.length,a.proxy(this._overrides.to,this._core)(this._pages[(b%e+e)%e].start,c))},a.fn.owlCarousel.Constructor.Plugins.Navigation=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){"use strict";var e=function(c){this._core=c,this._hashes={},this.$element=this._core.$element,this._handlers={"initialized.owl.carousel":a.proxy(function(c){c.namespace&&"URLHash"===this._core.settings.startPosition&&a(b).trigger("hashchange.owl.navigation")},this),"prepared.owl.carousel":a.proxy(function(b){if(b.namespace){var c=a(b.content).find("[data-hash]").andSelf("[data-hash]").attr("data-hash");if(!c)return;this._hashes[c]=b.content}},this),"changed.owl.carousel":a.proxy(function(c){if(c.namespace&&"position"===c.property.name){var d=this._core.items(this._core.relative(this._core.current())),e=a.map(this._hashes,function(a,b){return a===d?b:null}).join();if(!e||b.location.hash.slice(1)===e)return;b.location.hash=e}},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this.$element.on(this._handlers),a(b).on("hashchange.owl.navigation",a.proxy(function(a){var c=b.location.hash.substring(1),e=this._core.$stage.children(),f=this._hashes[c]&&e.index(this._hashes[c]);f!==d&&f!==this._core.current()&&this._core.to(this._core.relative(f),!1,!0)},this))};e.Defaults={URLhashListener:!1},e.prototype.destroy=function(){var c,d;a(b).off("hashchange.owl.navigation");for(c in this._handlers)this._core.$element.off(c,this._handlers[c]);for(d in Object.getOwnPropertyNames(this))"function"!=typeof this[d]&&(this[d]=null)},a.fn.owlCarousel.Constructor.Plugins.Hash=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){function e(b,c){var e=!1,f=b.charAt(0).toUpperCase()+b.slice(1);return a.each((b+" "+h.join(f+" ")+f).split(" "),function(a,b){return g[b]!==d?(e=c?b:!0,!1):void 0}),e}function f(a){return e(a,!0)}var g=a("<support>").get(0).style,h="Webkit Moz O ms".split(" "),i={transition:{end:{WebkitTransition:"webkitTransitionEnd",MozTransition:"transitionend",OTransition:"oTransitionEnd",transition:"transitionend"}},animation:{end:{WebkitAnimation:"webkitAnimationEnd",MozAnimation:"animationend",OAnimation:"oAnimationEnd",animation:"animationend"}}},j={csstransforms:function(){return!!e("transform")},csstransforms3d:function(){return!!e("perspective")},csstransitions:function(){return!!e("transition")},cssanimations:function(){return!!e("animation")}};j.csstransitions()&&(a.support.transition=new String(f("transition")),a.support.transition.end=i.transition.end[a.support.transition]),j.cssanimations()&&(a.support.animation=new String(f("animation")),a.support.animation.end=i.animation.end[a.support.animation]),j.csstransforms()&&(a.support.transform=new String(f("transform")),a.support.transform3d=j.csstransforms3d())}(window.Zepto||window.jQuery,window,document);

// JQUERY NEWS TICKER by Rhodimus http://github.com/rhodimus/jQuery-News-Ticker modified by MKRdezign
(function(b){b.fn.ticker=function(k){var c=b.extend({},b.fn.ticker.defaults,k);if(0==b(this).length)return window.console&&window.console.log?window.console.log("Element does not exist in DOM!"):alert("Element does not exist in DOM!"),!1;var l=b(this);return this.each(function(){function f(a){var b=0,c;for(c in a)a.hasOwnProperty(c)&&b++;return b}function k(a){c.debugMode&&(window.console&&window.console.log?window.console.log(a):alert(a))}function r(){if(0==a.contentLoaded)if(0<l.find(".items").length)l.find(".items").each(function(h){a.newsArr["item-"+
h]={type:c.titleText,content:b(this).html()}});else return k("Couldn't find HTML any content for the ticker to use!"),!1}function m(){a.contentLoaded=!0;b(a.dom.titleElem).html(a.newsArr["item-"+a.position].type);b(a.dom.contentID).html(a.newsArr["item-"+a.position].content);a.position==f(a.newsArr)-1?a.position=0:a.position++;distance=b(a.dom.contentID).width();time=distance/c.speed;t();p()}function t(){b(a.dom.contentID).css("opacity","1");if(a.play){var h=b(a.dom.titleID).width()+20;b(a.dom.revealID).css(c.direction,
h+"px");"fade"==c.displayType?b(a.dom.revealID).hide(0,function(){b(a.dom.contentID).css(c.direction,h+"px").fadeIn(c.fadeInSpeed,g)}):"scroll"!=c.displayType&&b(a.dom.revealElem).show(0,function(){b(a.dom.contentID).css(c.direction,h+"px").show();animationAction="right"==c.direction?{marginRight:distance+"px"}:{marginLeft:distance+"px"};b(a.dom.revealID).css("margin-"+c.direction,"0px").delay(20).animate(animationAction,time,"linear",g)})}else return!1}function g(){a.play?(b(a.dom.contentID).delay(c.pauseOnItems).fadeOut(c.fadeOutSpeed),
"fade"==c.displayType?b(a.dom.contentID).fadeOut(c.fadeOutSpeed,function(){b(a.dom.wrapperID).find(a.dom.revealElem+","+a.dom.contentID).hide().end().find(a.dom.tickerID+","+a.dom.revealID).show().end().find(a.dom.tickerID+","+a.dom.revealID).removeAttr("style");m()}):b(a.dom.revealID).hide(0,function(){b(a.dom.contentID).fadeOut(c.fadeOutSpeed,function(){b(a.dom.wrapperID).find(a.dom.revealElem+","+a.dom.contentID).hide().end().find(a.dom.tickerID+","+a.dom.revealID).show().end().find(a.dom.tickerID+
","+a.dom.revealID).removeAttr("style");m()})})):b(a.dom.revealElem).hide()}function n(){a.play=!1;b(a.dom.tickerID+","+a.dom.revealID+","+a.dom.titleID+","+a.dom.titleElem+","+a.dom.revealElem+","+a.dom.contentID).stop(!0,!0);b(a.dom.revealID+","+a.dom.revealElem).hide();b(a.dom.wrapperID).find(a.dom.titleID+","+a.dom.titleElem).show().end().find(a.dom.contentID).show()}function q(c){n();switch(c){case "prev":a.position=0==a.position?f(a.newsArr)-2:1==a.position?f(a.newsArr)-1:a.position-2;b(a.dom.titleElem).html(a.newsArr["item-"+
a.position].type);b(a.dom.contentID).html(a.newsArr["item-"+a.position].content);break;case "next":b(a.dom.titleElem).html(a.newsArr["item-"+a.position].type),b(a.dom.contentID).html(a.newsArr["item-"+a.position].content)}a.position==f(a.newsArr)-1?a.position=0:a.position++;p()}function p(){b(a.dom.wrapperID).find(".hoveffect").hover(function(){var a=b(this),c=a.parents(".items").html(),d=a.height(),f=a.offset(),e,g=b(document.body).width();e=f.left;ts_isRTL()&&(e=e+a.width()-320);e+320>g?e=g-330:
10>e&&(e=10);b(".newsmoreinfo").css({top:f.top+d,left:e}).addClass("active").html(c)},function(){b(".newsmoreinfo").removeClass("active").html("")})}var d=(new Date).getTime(),a={position:0,time:0,distance:0,newsArr:{},play:!0,paused:!1,contentLoaded:!1,dom:{contentID:"#ticker-content-"+d,titleID:"#ticker-title-"+d,titleElem:"#ticker-title-"+d+" SPAN",tickerID:"#ticker-"+d,wrapperID:"#ticker-wrapper-"+d,revealID:"#ticker-swipe-"+d,revealElem:"#ticker-swipe-"+d+" SPAN",controlsID:"#ticker-controls-"+
d,prevID:"#prev-"+d,nextID:"#next-"+d,playPauseID:"#play-pause-"+d}};"rtl"==c.direction?c.direction="right":c.direction="left";(function(){r();l.wrap('<div id="'+a.dom.wrapperID.replace("#","")+'"></div>');b(a.dom.wrapperID).children().remove();b(a.dom.wrapperID).append('<div id="'+a.dom.tickerID.replace("#","")+'" class="ticker"><div id="'+a.dom.titleID.replace("#","")+'" class="ticker-title"><span>\x3c!-- --\x3e</span></div><p id="'+a.dom.contentID.replace("#","")+'" class="ticker-content items"></p><div id="'+
a.dom.revealID.replace("#","")+'" class="ticker-swipe"><span>\x3c!-- --\x3e</span></div></div>');b(a.dom.wrapperID).removeClass("no-js").addClass("ticker-wrapper has-js "+c.direction);b(a.dom.tickerElem+","+a.dom.contentID).hide();c.controls&&(b(document).on("click mouseover mousedown mouseout mouseup",a.dom.controlsID,function(c){var d=c.target.id;if("click"==c.type)switch(d){case a.dom.prevID.replace("#",""):a.paused=!0;b(a.dom.playPauseID).addClass("paused");q("prev");break;case a.dom.nextID.replace("#",
""):a.paused=!0;b(a.dom.playPauseID).addClass("paused");q("next");break;case a.dom.playPauseID.replace("#",""):1==a.play?(a.paused=!0,b(a.dom.playPauseID).addClass("paused"),n()):(a.paused=!1,b(a.dom.playPauseID).removeClass("paused"),a.play=!0,a.paused=!1,g())}else"mouseover"==c.type&&b("#"+d).hasClass("controls")?b("#"+d).addClass("over"):"mousedown"==c.type&&b("#"+d).hasClass("controls")?b("#"+d).addClass("down"):"mouseup"==c.type&&b("#"+d).hasClass("controls")?b("#"+d).removeClass("down"):"mouseout"==
c.type&&b("#"+d).hasClass("controls")&&b("#"+d).removeClass("over")}),b(a.dom.wrapperID).append('<ul id="'+a.dom.controlsID.replace("#","")+'" class="ticker-controls"><li id="'+a.dom.playPauseID.replace("#","")+'" class="jnt-play-pause controls"></li><li id="'+a.dom.prevID.replace("#","")+'" class="jnt-prev controls"></li><li id="'+a.dom.nextID.replace("#","")+'" class="jnt-next controls"></li></ul>'));"fade"!=c.displayType&&b(a.dom.contentID).mouseover(function(){0==a.paused&&n()}).mouseout(function(){0==
a.paused&&(a.play=!0,a.paused=!1,g())});m()})()})};b.fn.ticker.defaults={speed:.1,displayType:"reveal",htmlFeed:!0,debugMode:!0,controls:!0,titleText:"Latest",direction:"ltr",pauseOnItems:3E3,fadeInSpeed:600,fadeOutSpeed:300}})(jQuery);

//jQuery Simple Spy 
(function(a){a.simpleSpy=function(d,f){var b=this;b.$el=a(d);b.init=function(){b.options=a.extend({},a.simpleSpy.defaultOptions,f);var c=b.$el,d=!0,g=[],e=b.options.limit,h=0,l=c.find("> .items:first").outerHeight(!0),m=c.find("> .items:first").height();c.find("> .items").each(function(){g.push('<div class="items">'+a(this).html()+"</div>")});h=g.length;c.wrap('<div class="spyWrapper" />').parent().css({height:l*b.options.limit});c.find("> .items").filter(":gt("+(b.options.limit-1)+")").remove();
c.bind("stop",function(){d=!1}).bind("start",function(){d=!0});var k=function(){if(d){var f=a(g[e]).css({height:0,opacity:0}).prependTo(c);c.find("> .items:last").animate({opacity:0},1E3,function(){f.animate({height:m},1E3).animate({opacity:1},1E3);a(this).remove()});e++;e>=h&&(e=0)}setTimeout(k,b.options.interval)};k()};b.init()};a.simpleSpy.defaultOptions={limit:4,interval:4E3};a.fn.simpleSpy=function(d){return this.each(function(){new a.simpleSpy(this,d)})}})(jQuery);

// highlight v4 by Johann Burkard http://johannburkard.de
(function(e){e.fn.highlight=function(c){function e(b,c){var d=0;if(3==b.nodeType){var a=b.data.toUpperCase().indexOf(c);if(0<=a){d=document.createElement("span");d.className="highlight";a=b.splitText(a);a.splitText(c.length);var f=a.cloneNode(!0);d.appendChild(f);a.parentNode.replaceChild(d,a);d=1}}else if(1==b.nodeType&&b.childNodes&&!/(script|style)/i.test(b.tagName))for(a=0;a<b.childNodes.length;++a)a+=e(b.childNodes[a],c);return d}return this.length&&c&&c.length?this.each(function(){e(this,c.toUpperCase())}):
this};e.fn.removeHighlight=function(){return this.find("span.highlight").each(function(){this.parentNode.firstChild.nodeName;with(this.parentNode)replaceChild(this.firstChild,this),normalize()}).end()}})(jQuery);

var _$_4a9d=["1l z$q=[\"\\1c\\E\\U\\J\",\"\\A\\1a\\F\\O\\D\",\"\\B\",\"\\V\\1a\\D\\G\\B\\Z\\U\\J\\A\\L\\1e\\E\\1c\",\"\\E\\F\\E\\J\\A\",\"\\V\\1a\\D\\G\\1g\\F\\1r\\2k\\A\\L\\Z\",\"\\L\",\"\\V\\1a\\D\\G\\U\\H\\L\\E\\1c\\2E\\D\\U\\A\",\"\\1X\",\"\\N\",\"\\5l\\D\\L\\N\\3a\\A\\1d\\N\\2k\\D\\G\\N\\1S\\R\\G\\N\\2k\\D\\1q\\N\\5l\\Z\\L\\N\\5l\\Z\\J\\N\\1S\\Z\\1e\\N\\2O\\A\\R\\N\\4q\\K\\E\\N\\2E\\H\\1a\\N\\3o\\A\\K\",\"\\V\\1a\\D\\G\\3a\\Z\\J\\J\\U\\H\\L\\E\\1c\\2E\\D\\U\\A\",\"\\5l\\D\\L\\Z\\D\\G\\1q\\N\\3a\\A\\1d\\G\\Z\\D\\G\\1q\\N\\2k\\D\\G\\K\\1c\\N\\1S\\R\\G\\F\\J\\N\\2k\\D\\1q\\N\\5l\\Z\\L\\A\\N\\5l\\Z\\J\\1q\\N\\1S\\Z\\1e\\Z\\B\\E\\N\\2O\\A\\R\\E\\A\\U\\1d\\A\\G\\N\\4q\\K\\E\\H\\1d\\A\\G\\N\\2E\\H\\1a\\A\\U\\1d\\A\\G\\N\\3o\\A\\K\\A\\U\\1d\\A\\G\",\"\\V\\1a\\D\\G\\O\\D\\E\\A\\1g\\H\\G\\U\\D\\E\",\"\\4l\\4l\\4l\\4l\\P\\2k\\2k\\P\\3o\\3o\",\"\\V\\1a\\D\\G\\B\\E\\F\\K\\1o\\1q\\2k\\A\\L\\Z\",\"\\V\\1a\\D\\G\\B\\J\\F\\O\\A\\G\\B\\R\\A\\A\\O\",\"\\V\\1a\\D\\G\\L\\D\\1a\\F\\R\\H\\B\\E\\R\\D\\1e\\A\",\"\\V\\1a\\D\\G\\G\\K\\D\\O\\U\\F\\L\\3v\\J\\H\\1e\",\"\\1q\",\"\\V\\1a\\D\\G\\B\\1c\\F\\O\\A\\D\\Z\\E\\1c\\H\\G\",\"\\V\\1a\\D\\G\\1c\\F\\O\\A\\3p\\D\\E\\A\\B\\E\",\"\\V\\1a\\D\\G\\K\\B\\A\\2Q\\3o\",\"\",\"\\V\\1a\\D\\G\\1c\\F\\O\\A\\3D\\U\\H\",\"\\V\\1a\\D\\G\\1c\\H\\U\\A\\J\\F\\B\\E\",\"\\V\\1a\\D\\G\\O\\F\\B\\D\\1d\\J\\A\\E\\F\\U\\A\",\"\\V\\1a\\D\\G\\1c\\H\\U\\A\\2m\\D\\1e\\A\\2E\\D\\1a\\F\",\"\\V\\1a\\D\\G\\1g\\1d\\D\\R\\R\\B\\F\\O\",\"\\2w\\5T\\3g\\6F\\1N\\1J\\5T\\2c\\2w\\4j\\3g\\1J\\6F\\1J\\5j\",\"\\V\\1a\\D\\G\\1g\\1d\\J\\D\\L\\1e\",\"\\A\\L\\1P\\4d\\2O\",\"\\V\\1a\\D\\G\\O\\D\\1T\\D\\1r\\2m\\D\\1e\\A\\2E\\D\\1a\\F\",\"\\V\\1a\\D\\G\\B\\G\\K\\E\\A\\1r\\E\",\"\\2p\\1q\\R\\A\\N\\D\\L\\O\\N\\1c\\F\\E\\N\\A\\L\\E\\A\\G\\N\\E\\H\\N\\B\\A\\D\\G\\K\\1c\\V\\V\\V\",\"\\V\\1a\\D\\G\\L\\E\\A\\1r\\E\",\"\\2E\\A\\1r\\E\",\"\\V\\1a\\D\\G\\R\\E\\A\\1r\\E\",\"\\2m\\G\\A\\1a\\F\\H\\Z\\B\",\"\\V\\1a\\D\\G\\U\\E\\A\\1r\\E\",\"\\2k\\H\\G\\A\",\"\\V\\1a\\D\\G\\J\\U\\E\\A\\1r\\E\",\"\\3p\\H\\D\\O\\N\\2k\\H\\G\\A\\N\\2m\\H\\B\\E\",\"\\V\\1a\\D\\G\\1a\\U\\E\\A\\1r\\E\",\"\\ci\\F\\A\\1k\\N\\2k\\H\\G\\A\\N\\1S\\1d\\H\\Z\\E\",\"\\V\\1a\\D\\G\\G\\A\\J\\E\\A\\1r\\E\",\"\\4W\\A\\J\\D\\E\\A\\O\\N\\2m\\H\\B\\E\",\"\\V\\1a\\D\\G\\G\\A\\K\\E\\A\\1r\\E\",\"\\4W\\A\\K\\A\\L\\E\\N\\2m\\H\\B\\E\",\"\\V\\1a\\D\\G\\G\\A\\K\\H\\E\\A\\1r\\E\",\"\\4W\\A\\K\\H\\U\\U\\A\\L\\O\\A\\O\\N\\2m\\H\\B\\E\",\"\\V\\1a\\D\\G\\E\\1k\\A\\A\\E\\E\\A\\1r\\E\",\"\\2p\\1k\\A\\A\\E\",\"\\V\\1a\\D\\G\\J\\F\\1o\\A\\E\\A\\1r\\E\",\"\\3p\\F\\1o\\A\",\"\\V\\1a\\D\\G\\B\\1c\\D\\G\\A\\E\\A\\1r\\E\",\"\\2O\\1c\\D\\G\\A\",\"\\V\\1a\\D\\G\\G\\A\\D\\O\\U\\H\\G\\A\\E\\A\\1r\\E\",\"\\4W\\A\\D\\O\\N\\U\\H\\G\\A\\N\\dL\",\"\\V\\1a\\D\\G\\E\\1k\\F\\E\\E\\A\\G\\D\\Z\\E\\1c\\H\\G\",\"\\2O\\D\\E\\D\\L\\1o\\2k\\4Y\\4W\",\"\\V\\1a\\D\\G\\O\\F\\B\\2j\\Z\\B\\B\\1c\\H\\G\\E\\L\\D\\U\\A\",\"\\V\\1a\\D\\G\\1g\\J\\F\\K\\1o\\G\\F\\O\",\"\\V\\1a\\D\\G\\G\\A\\J\\B\\E\\1q\\J\\A\",\"\\K\\D\\G\\H\\Z\\B\\A\\J\",\"\\V\\1a\\D\\G\\1T\\B\\H\\L\\J\\H\\D\\O\",\"\\O\\A\\1g\\D\\Z\\J\\E\",\"\\V\\1a\\D\\G\\1c\\G\\A\\1a\\F\\A\\1k\",\"\\V\\1a\\D\\G\\B\\1c\\H\\1k\\G\\A\\J\\D\\E\\A\\O\",\"\\V\\1a\\D\\G\\B\\1c\\H\\1k\\G\\A\\K\\H\\U\\U\\A\\L\\O\\A\\O\",\"\\V\\1a\\D\\G\\E\\F\\E\\J\\A\\D\\O\\B\",\"\\V\\1a\\D\\G\\1c\\A\\1r\\K\\A\\G\\R\\E\",\"\\V\\1a\\D\\G\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\",\"\\V\\1a\\D\\G\\1g\\F\\G\\B\\E\\E\\1c\\Z\\U\\1d\",\"\\B\\1N\\5j\\1J\\1J\",\"\\V\\1a\\D\\G\\E\\1c\\Z\\U\\1d\",\"\\V\\1a\\D\\G\\B\\J\\F\\O\\A\\G\\E\\1c\\Z\\U\\1d\",\"\\V\\1a\\D\\G\\1g\\A\\D\\E\\R\\H\\B\\E\",\"\\V\\1a\\D\\G\\E\\H\\R\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\",\"\\V\\1a\\D\\G\\1d\\H\\E\\E\\H\\U\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\",\"\\V\\1a\\D\\G\\D\\Z\\E\\H\\R\\J\\D\\1q\",\"\\V\\1a\\D\\G\\E\\H\\R\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\\J\\H\\D\\O\",\"\\G\\A\\K\\A\\L\\E\",\"\\V\\1a\\D\\G\\1d\\H\\E\\E\\H\\U\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\\J\\H\\D\\O\",\"\\V\\1a\\D\\G\\O\\D\\1T\\D\\1r\\B\\G\\K\",\"\\V\\1a\\D\\G\\G\\A\\K\\A\\L\\E\\R\\H\\B\\E\",\"\\V\\1a\\D\\G\\G\\D\\L\\O\\H\\U\\R\\H\\B\\E\",\"\\V\\1a\\D\\G\\1g\\A\\D\\E\\Z\\G\\A\\O\\R\\H\\B\\E\",\"\\V\\1a\\D\\G\\G\\A\\K\\A\\L\\E\\K\\H\\U\\U\\A\\L\\E\",\"\\V\\1a\\D\\G\\1g\\1d\\F\\1e\\1N\",\"\\V\\1a\\D\\G\\1g\\1d\\F\\1e\\2a\",\"\\V\\1a\\D\\G\\1e\\D\\J\\J\\A\\G\\1q\\1N\",\"\\V\\1a\\D\\G\\1e\\D\\J\\J\\A\\G\\1q\\2a\",\"\\V\\1a\\D\\G\\1e\\D\\J\\J\\A\\G\\1q\\2c\",\"\\V\\1a\\D\\G\\K\\H\\J\\Z\\U\\L\\1N\",\"\\V\\1a\\D\\G\\K\\H\\J\\Z\\U\\L\\2a\",\"\\V\\1a\\D\\G\\L\\A\\1k\\B\\E\\F\\K\\1o\\A\\G\",\"\\V\\1a\\D\\G\\B\\J\\F\\O\\A\\G\",\"\\V\\1a\\D\\G\\K\\D\\G\\H\\Z\\B\\A\\J\\1N\",\"\\V\\1a\\D\\G\\K\\D\\G\\H\\Z\\B\\A\\J\\2a\",\"\\V\\1a\\D\\G\\G\\A\\J\\D\\E\\A\\O\",\"\\V\\1a\\D\\G\\1a\\F\\O\\A\\H\",\"\\V\\1a\\D\\G\\1g\\A\\D\\E\\Z\\G\\A\\O\\1N\",\"\\V\\1a\\D\\G\\1g\\A\\D\\E\\Z\\G\\A\\O\\2a\",\"\\V\\1a\\D\\G\\1g\\A\\D\\E\\Z\\G\\A\\O\\2c\",\"\\V\\1a\\D\\G\\1g\\A\\D\\E\\Z\\G\\A\\O\\2w\",\"\\V\\1a\\D\\G\\1g\\A\\D\\E\\Z\\G\\A\\O\\4j\",\"\\V\\1a\\D\\G\\1d\\F\\1e\\R\\H\\B\\E\",\"\\V\\1a\\D\\G\\1c\\D\\J\\1g\\R\\H\\B\\E\",\"\\V\\1a\\D\\G\\D\\L\\F\\U\\D\\E\\A\\O\\R\\H\\B\\E\",\"\\V\\1a\\D\\G\\1d\\J\\H\\1e\\R\\H\\B\\E\",\"\\V\\1a\\D\\G\\B\\F\\U\\R\\J\\A\\R\\H\\B\\E\",\"\\V\\1a\\D\\G\\J\\F\\B\\E\",\"\\V\\1a\\D\\G\\1c\\H\\E\",\"\\V\\1a\\D\\G\\O\\F\\B\\2j\\Z\\B\\K\\H\\U\\U\\A\\L\\E\",\"\\V\\1a\\D\\G\\1g\\J\\F\\K\\1o\\G\\1d\\D\\O\\1e\\A\",\"\\V\\1a\\D\\G\\E\\F\\U\\A\\J\\F\\L\\A\",\"\\Z\\L\\O\\A\\1g\\F\\L\\A\\O\",\"\\V\\B\\F\\O\\A\\1d\\D\\G\\P\\G\\F\\1e\\1c\\E\",\"\\1L\\B\\F\\O\\A\\1d\\D\\G\\P\\E\\H\\R\",\"\\1L\\B\\F\\O\\A\\1d\\D\\G\\E\\D\\1d\\B\",\"\\1L\\B\\F\\O\\A\\1d\\D\\G\\P\\1d\\H\\E\\E\\H\\U\",\"\\V\\B\\F\\O\\A\\1d\\D\\G\\P\\G\\F\\1e\\1c\\E\\N\\V\\F\\L\\L\\A\\G\\1k\\G\\D\\R\",\"\\1z\\1L\\1N\\3g\\1N\\1G\",\"\\J\\F\\B\\E\",\"\\1c\\J\\F\\B\\E\",\"\\1c\\1e\\G\\F\\R\",\"\\1z\\1L\\1N\\5T\\3g\\1G\",\"\\1b\\1b\",\"\\R\\D\\1e\\A\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\H\\1k\\R\\D\\1e\\A\\Q\\X\\W\",\"\\N\\1c\\G\\A\\1g\\Y\\Q\\Q\\X\",\"\\W\\1b\",\"\\X\\W\\1b\\B\\R\\D\\L\\X\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\H\\1k\\R\\D\\1e\\A\\2E\\Z\\U\\Q\\X\\W\",\"\\N\\1c\\G\\A\\1g\\Y\\Q\\1b\\B\\A\\D\\G\\K\\1c\\1b\\J\\D\\1d\\A\\J\\1b\",\"\\1M\\1z\\U\\D\\1r\\P\\G\\A\\B\\Z\\J\\E\\B\\Y\",\"\\Q\\X\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\1r\\R\\D\\1e\\A\\1r\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\1L\\Q\\N\\D\\J\\E\\Y\\Q\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\1r\\J\\D\\1d\\A\\J\\1r\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\1L\\Q\\N\\D\\J\\E\\Y\\Q\",\"\\N\\1c\\G\\A\\1g\\Y\\Q\\Q\\X\\1N\\W\\1b\",\"\\Q\\X\\1N\\W\\1b\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\O\\H\\E\\1r\\R\\D\\1e\\A\\Q\\X\\N\\V\\V\\V\\N\\W\\1b\\B\\R\\D\\L\\X\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\H\\1k\\R\\D\\1e\\A\\2m\\H\\F\\L\\E\\Q\\X\",\"\\W\\1b\\B\\R\\D\\L\\X\",\"\\N\\1c\\G\\A\\1g\\Y\\Q\\1L\\Q\\N\\K\\J\\D\\B\\B\\Y\\Q\\1r\\R\\D\\1e\\A\\1r\\Q\\N\\D\\J\\E\\Y\\Q\",\"\\N\\1c\\G\\A\\1g\\Y\\Q\\1L\\Q\\N\\K\\J\\D\\B\\B\\Y\\Q\\1r\\J\\D\\1d\\A\\J\\1r\\Q\\N\\D\\J\\E\\Y\\Q\",\"\\R\\D\\1e\\A\\1S\\G\\A\\D\",\"\\1d\\J\\H\\1e\\P\\R\\D\\1e\\A\\G\\F\\L\\O\\A\\1r\",\"\\O\\F\\B\\R\\J\\D\\1q\",\"\\1d\\J\\H\\K\\1o\",\"\\1L\\1d\\J\\H\\1e\\P\\R\\D\\1e\\A\\G\\F\\L\\O\\A\\1r\",\"\\D\\J\\E\",\"\\1b\\1g\\A\\A\\O\\B\\1b\\R\\H\\B\\E\\B\\1b\\B\\Z\\U\\U\\D\\G\\1q\\1M\\B\\E\\D\\G\\E\\P\\F\\L\\O\\A\\1r\\Y\",\"\\1z\\U\\D\\1r\\P\\G\\A\\B\\Z\\J\\E\\B\\Y\\1N\\1z\\D\\J\\E\\Y\\1T\\B\\H\\L\\P\\F\\L\\P\\B\\K\\G\\F\\R\\E\",\"\\1T\\B\\H\\L\\R\",\"\\1b\\1g\\A\\A\\O\\B\\1b\\R\\H\\B\\E\\B\\1b\\B\\Z\\U\\U\\D\\G\\1q\\1b\\P\\1b\",\"\\1M\\B\\E\\D\\G\\E\\P\\F\\L\\O\\A\\1r\\Y\",\"\\1L\\1d\\J\\H\\1e\\P\\R\\D\\1e\\A\\G\\F\\L\\O\\A\\1r\\N\\D\\V\\1r\\R\\D\\1e\\A\\1r\\1X\\N\\1L\\1d\\J\\H\\1e\\P\\R\\D\\1e\\A\\G\\F\\L\\O\\A\\1r\\N\\D\\V\\1r\\J\\D\\1d\\A\\J\\1r\",\"\\1b\\B\\A\\D\\G\\K\\1c\\1b\\J\\D\\1d\\A\\J\\1b\",\"\\1M\\Z\\R\\O\\D\\E\\A\\O\\P\\U\\D\\1r\",\"\\1M\\U\\D\\1r\",\"\\1M\\1z\\U\\D\\1r\",\"\\1b\",\"\\1M\\2j\\Y\",\"\\V\\1c\\E\\U\\J\",\"\\U\\D\\1r\\P\\G\\A\\B\\Z\\J\\E\\B\\Y\",\"\\1L\\2m\\D\\1e\\A\\2E\\H\\Y\",\"\\1b\\1g\\A\\A\\O\\B\\1b\\R\\H\\B\\E\\B\\1b\\B\\Z\\U\\U\\D\\G\\1q\\1M\\U\\D\\1r\\P\\G\\A\\B\\Z\\J\\E\\B\\Y\\1N\\1z\\D\\J\\E\\Y\\1T\\B\\H\\L\\P\\F\\L\\P\\B\\K\\G\\F\\R\\E\",\"\\J\\D\\1d\\A\\J\",\"\\1M\\U\\D\\1r\\P\\G\\A\\B\\Z\\J\\E\\B\\Y\\1N\\1z\\D\\J\\E\\Y\\1T\\B\\H\\L\\P\\F\\L\\P\\B\\K\\G\\F\\R\\E\",\"\\1b\\B\\A\\D\\G\\K\\1c\\1M\\Z\\R\\O\\D\\E\\A\\O\\P\\U\\D\\1r\\Y\",\"\\1z\\U\\D\\1r\\P\\G\\A\\B\\Z\\J\\E\\B\\Y\",\"\\1M\\Z\\R\\O\\D\\E\\A\\O\\P\\U\\D\\1r\\Y\",\"\\V\\R\\H\\B\\E\\P\\H\\Z\\E\\A\\G\",\"\\O\\F\\1a\\V\\1d\\J\\H\\1e\\P\\R\\H\\B\\E\\B\",\"\\W\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\R\\H\\B\\E\\P\\B\\Z\\U\\U\\D\\G\\1q\",\"\\1L\\U\\D\\F\\L\",\"\\1c\\E\\U\\J\\1X\\N\\1d\\H\\O\\1q\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\",\"\\V\\O\\F\\B\\2j\\Z\\B\\V\\K\\H\\U\\1b\\1d\\J\\H\\1e\\1e\\A\\G\\1P\\F\\L\\O\\A\\1r\\V\\1T\\B\",\"\\D\",\"\\F\\U\\1e\",\"\\D\\V\\1d\\J\\H\\1e\\P\\R\\D\\1e\\A\\G\\P\\H\\J\\O\\A\\G\\P\\J\\F\\L\\1o\",\"\\1c\\G\\A\\1g\",\"\\1P\\E\\G\\D\\K\\1o\\2m\\D\\1e\\A\\1a\\F\\A\\1k\",\"\\1c\\E\\E\\R\\B\\1x\\1b\\1b\\J\\1c\\2c\\V\\1e\\H\\H\\1e\\J\\A\\Z\\B\\A\\G\\K\\H\\L\\E\\A\\L\\E\\V\\K\\H\\U\\1b\\P\\3a\\F\\4V\\2T\\1q\\4q\\4Y\\2w\\2k\\A\\1k\\1b\\2p\\2w\\D\\1S\\1T\\2a\\Z\\ci\\5l\\4Y\\2Q\\1b\\1S\\1S\\1S\\1S\\1S\\1S\\1S\\1S\\2m\\D\\4l\\1b\\1r\\2a\\2c\\E\\1T\\7r\\2Q\\6o\\3g\\J\\B\\1b\\B\\2c\\2a\\1b\\D\\1T\\D\\1r\\P\\J\\H\\D\\O\\A\\G\\V\\1e\\F\\1g\",\"\\1e\\G\\F\\O\",\"\\1a\\J\\F\\B\\E\",\"\\1a\\1e\\G\\F\\O\",\"\\F\\E\\A\\U\",\"\\W\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\J\\H\\D\\O\\R\\H\\B\\E\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\1T\\D\\1a\\D\\B\\K\\G\\F\\R\\E\\1x\\1G\\Q\\X\",\"\\X\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\F\\U\\1e\\J\\H\\D\\O\\Q\\N\\B\\G\\K\\Y\\Q\",\"\\Q\\N\\B\\E\\1q\\J\\A\\Y\\Q\\O\\F\\B\\R\\J\\D\\1q\\1x\\N\\L\\H\\L\\A\\1G\\Q\\X\",\"\\W\\O\\F\\1a\\N\\B\\E\\1q\\J\\A\\Y\\Q\\E\\A\\1r\\E\\P\\D\\J\\F\\1e\\L\\1x\\N\\K\\A\\L\\E\\A\\G\\1G\\N\\1g\\H\\L\\E\\P\\B\\F\\2T\\A\\1x\\N\\1N\\2a\\1J\\5U\\1G\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\R\\H\\B\\E\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\R\\H\\B\\E\\O\\D\\E\\A\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\W\\B\\E\\G\\H\\L\\1e\\X\",\"\\W\\1b\\B\\E\\G\\H\\L\\1e\\X\\W\\B\\R\\D\\L\\X\",\"\\W\\1b\\B\\R\\D\\L\\X\\W\\B\\U\\D\\J\\J\\X\",\"\\W\\1b\\B\\U\\D\\J\\J\\X\",\"\\V\\R\\H\\B\\E\\O\\D\\E\\A\",\"\\D\\1d\\1d\\G\\V\\R\\Z\\1d\\J\\F\\B\\1c\\A\\O\",\"\\1a\\1e\\G\\F\\R\",\"\\V\\1d\\J\\H\\1e\\P\\R\\H\\B\\E\\B\\V\\1c\\1g\\A\\A\\O\",\"\\1L\\1a\\F\\A\\1k\\N\\V\\1e\\G\\F\\O\",\"\\1L\\1a\\F\\A\\1k\\N\\V\\J\\F\\B\\E\",\"\\D\\K\\E\\F\\1a\\A\",\"\\O\\R\\J\\D\\K\\A\",\"\\E\\R\\J\\D\\K\\A\",\"\\1N\\2a\",\"\\1X\\N\",\"\\1J\",\"\\1S\\2k\",\"\\2m\\2k\",\"\\1x\",\"\\L\\H\\1P\\F\\U\\D\\1e\\A\",\"\\2O\\A\\D\\G\\K\\1c\\N\\G\\A\\B\\Z\\J\\E\\B\\N\\1g\\H\\G\\N\\1o\\A\\1q\\1k\\H\\G\\O\",\"\\2E\\H\\N\\G\\A\\B\\Z\\J\\E\\c5\",\"\\2O\\A\\D\\G\\K\\1c\\F\\L\\1e\\V\\V\\V\",\"\\1L\\D\\1T\\D\\1r\\P\\B\\A\\D\\G\\K\\1c\\P\\1g\\H\\G\\U\",\"\\1x\\E\\A\\1r\\E\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\G\\K\\P\\G\\A\\B\\Z\\J\\E\\Q\\N\\F\\O\\Y\\Q\\B\\A\\D\\G\\K\\1c\\P\\G\\A\\B\\Z\\J\\E\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\1L\\B\\A\\D\\G\\K\\1c\\P\\G\\A\\B\\Z\\J\\E\",\"\\B\\Z\\1d\\U\\F\\E\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\J\\H\\D\\O\\Q\\X\",\"\\W\\1b\\O\\F\\1a\\X\",\"\\1b\\1g\\A\\A\\O\\B\\1b\\R\\H\\B\\E\\B\\1b\\O\\A\\1g\\D\\Z\\J\\E\\1M\\D\\J\\E\\Y\\1T\\B\\H\\L\\P\\F\\L\\P\\B\\K\\G\\F\\R\\E\\1z\\2j\\Y\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\G\\K\\P\\1c\\A\\D\\O\\A\\G\\Q\\X\",\"\\N\\1z\\2j\\Z\\H\\E\\1G\",\"\\1z\\2j\\Z\\H\\E\\1G\\W\\1b\\B\\R\\D\\L\\X\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\K\\J\\H\\B\\A\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\1b\\Q\\X\\1z\\E\\F\\U\\A\\B\\1G\\W\\1b\",\"\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\G\\K\\P\\D\\G\\A\\D\\Q\\X\",\"\\F\\1e\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\1A\\B\\G\\K\\P\\U\\D\\G\\1o\\1A\\X\",\"\\D\\J\\E\\A\\G\\L\\D\\E\\A\",\"\\A\\L\\K\\J\\H\\B\\Z\\G\\A\",\"\\E\\A\\1r\\E\",\"\\K\\H\\L\\E\\A\\L\\E\",\"\\B\\Z\\U\\U\\D\\G\\1q\",\"\\U\\A\\O\\F\\D\\8g\\E\\1c\\Z\\U\\1d\\L\\D\\F\\J\",\"\\1b\\B\",\"\\P\\K\\1b\",\"\\F\\U\\1e\\V\\1q\\H\\Z\\E\\Z\\1d\\A\\V\\K\\H\\U\",\"\\U\\2j\\O\\A\\1g\\D\\Z\\J\\E\",\"\\1a\\F\\O\\A\\H\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\F\\U\\1e\\V\\1q\\H\\Z\\E\\Z\\1d\\A\\V\\K\\H\\U\\1b\\1a\\F\\1b\",\"\\1b\\U\\2j\\O\\A\\1g\\D\\Z\\J\\E\\V\\1T\\R\\1e\",\"\\U\\Z\\B\\F\\K\",\"\\1e\\D\\J\\J\\A\\G\\1q\",\"\\W\\1d\\J\\H\\K\\1o\\2j\\Z\\H\\E\\A\\X\",\"\\2j\\Z\\H\\E\\A\",\"\\1z\\2j\\Z\\H\\E\\1G\",\"\\V\\V\\V\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\G\\K\\P\\F\\E\\A\\U\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\G\\K\\P\\F\\U\\1e\\P\\H\\Z\\E\\A\\G\\Q\\X\\W\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\G\\K\\P\\F\\U\\1e\\Q\\N\\B\\E\\1q\\J\\A\\Y\\Q\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\1x\\N\",\"\\G\\1e\\1d\\D\\1O\\1J\\1X\\N\\1J\\1X\\N\\1J\\1X\\N\\1J\\V\\1N\\4j\\1K\",\"\\Z\\G\\J\\1O\\1A\",\"\\1A\\1K\",\"\\N\\L\\H\\P\\G\\A\\R\\A\\D\\E\\N\\K\\A\\L\\E\\A\\G\\N\\K\\A\\L\\E\\A\\G\\1G\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\P\\B\\F\\2T\\A\\1x\\N\\K\\H\\1a\\A\\G\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\Q\\N\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\R\\H\\B\\E\\P\\E\\1q\\R\\A\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\",\"\\Q\\X\\W\\1b\\F\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\",\"\\X\\W\\1b\\O\\F\\1a\\X\\W\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\G\\K\\P\\E\\F\\E\\J\\A\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\W\\R\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\G\\K\\P\\B\\Z\\U\\U\\D\\G\\1q\\Q\\N\\X\",\"\\W\\1b\\R\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\G\\K\\P\\U\\H\\G\\A\\R\\H\\B\\E\\Q\\X\\W\",\"\\N\\E\\F\\E\\J\\A\\Y\\Q\\U\\H\\G\\A\\N\\1d\\Z\\E\\E\\H\\L\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\1b\\B\\A\\D\\G\\K\\1c\\1M\\2j\\Y\",\"\\1z\\2j\\Z\\H\\E\\1G\\W\\1b\",\"\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\B\\G\\K\\P\\D\\G\\A\\D\",\"\\X\\W\\B\\E\\G\\H\\L\\1e\\X\",\"\\W\\1b\\B\\E\\G\\H\\L\\1e\\X\",\"\\K\\J\\F\\K\\1o\",\"\\V\\K\\J\\H\\B\\A\",\"\\F\\O\",\"\\V\\B\\Z\\U\\U\\D\\G\\1q\\P\\K\\H\\L\\E\\A\\L\\E\",\"\\V\\L\\H\\F\\U\\D\\1e\\A\",\"\\V\\B\\1c\\D\\G\\A\\B\\1d\\H\\E\\E\\H\\U\",\"\\V\\E\\1c\\Z\\U\\1d\\P\\F\\U\\1e\",\"\\V\\R\\H\\B\\E\\P\\E\\1q\\R\\A\",\"\\O\\D\\E\\D\\P\\F\\U\\1e\",\"\\B\\3g\\2a\\P\\K\",\"\\1b\\O\\A\\1g\\D\\Z\\J\\E\\V\\1T\\R\\1e\",\"\\1b\\B\\1N\\5j\\1J\\1J\\1b\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\1q\\H\\Z\\E\\Z\\1d\\A\\R\\J\\D\\1q\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\R\\J\\D\\1q\\P\\K\\F\\G\\K\\J\\A\\P\\H\\Q\\X\\W\\1b\\F\\X\\W\\1b\\B\\R\\D\\L\\X\",\"\\1c\\1q\\H\\Z\\E\\Z\\1d\\A\",\"\\V\\J\\D\\E\\A\\B\\E\\P\\F\\U\\1e\",\"\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\",\"\\Q\\X\\W\\1b\\F\\X\",\"\\8g\\1N\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\F\\A\\1k\\P\\R\\J\\D\\K\\A\\Q\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\F\\A\\1k\\P\\1a\\D\\J\\Z\\A\\Q\\X\",\"\\W\\1b\\B\\R\\D\\L\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\J\\F\\K\\A\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\1d\\D\\G\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\1k\\F\\O\\E\\1c\",\"\\5U\",\"\\V\\1d\\D\\G\",\"\\B\\E\\1q\\J\\A\",\"\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\1x\",\"\\1c\\E\\E\\R\",\"\\Z\\G\\J\\1O\",\"\\1K\",\"\\N\\L\\H\\P\\G\\A\\R\\A\\D\\E\\N\\K\\A\\L\\E\\A\\G\\N\\K\\A\\L\\E\\A\\G\\1G\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\P\\B\\F\\2T\\A\\1x\\N\\K\\H\\1a\\A\\G\",\"\\B\\1c\\K\\J\\F\\K\\1o\",\"\\V\\B\\1c\\D\\G\\A\\B\\F\\L\\1g\\H\",\"\\O\\1c\\G\\A\\1g\\P\\O\\H\\L\\A\",\"\\F\\K\\H\\L\\B\\P\\R\\F\\L\\E\\A\\G\\A\\B\\E\",\"\\1b\\1k\\2w\\1J\\1J\\1b\",\"\\F\\K\\H\\L\\B\\P\\E\\1k\\F\\E\\E\\A\\G\",\"\\F\\K\\H\\L\\B\\P\\1g\\D\\K\\A\\1d\\H\\H\\1o\",\"\\E\\1k\\F\\E\\E\\A\\G\",\"\\1g\\D\\K\\A\\1d\\H\\H\\1o\",\"\\F\\K\\H\\L\\B\\P\\1e\\R\\J\\Z\\B\",\"\\1e\\H\\H\\1e\\J\\A\\P\\R\\J\\Z\\B\",\"\\R\\F\\L\\E\\A\\G\\A\\B\\E\",\"\\F\\K\\H\\L\\B\\P\\J\\F\\L\\1o\\A\\O\\F\\L\",\"\\J\\F\\L\\1o\\A\\O\\F\\L\",\"\\B\\E\\Z\\U\\1d\\J\\A\\Z\\R\\H\\L\",\"\\1e\\H\\H\\1e\\J\\A\\2m\\J\\Z\\B\",\"\\F\\K\\H\\L\\B\\P\\B\\E\\Z\\U\\1d\\J\\A\\Z\\R\\H\\L\",\"\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\",\"\\Q\\X\\W\\1b\\F\\X\\W\\B\\R\\D\\L\\X\\W\\1d\\X\\8y\\E\\H\\E\\D\\J\\8S\\W\\1b\\1d\\X\\N\",\"\\B\\1c\\D\\G\\G\\G\\A\\V\\R\\1c\\R\",\"\\V\\O\\1c\\G\\A\\1g\",\"\\1G\",\"\\Y\",\"\\E\\A\\B\\E\",\"\\H\\1o\",\"\\1G\\A\\1r\\R\\F\\G\\A\\B\\Y\",\"\\1G\\R\\D\\E\\1c\\Y\\1b\",\"\\K\\H\\H\\1o\\F\\A\",\"\\V\\1c\\H\\U\\A\\P\\D\\G\\A\\D\\N\\1L\\3v\\J\\H\\1e\\1N\\1X\\V\\1c\\H\\U\\A\\P\\D\\G\\A\\D\\N\\V\\R\\H\\B\\E\\B\\P\\E\\F\\E\\J\\A\",\"\\N\\1k\\D\\B\\Z\\R\\R\\H\\G\\E\",\"\\V\\A\\1r\\K\\A\\G\\R\\E\",\"\\W\\J\\F\\X\\W\\Z\\J\\N\\K\\J\\D\\B\\B\\Y\\1A\",\"\\1A\\X\",\"\\F\",\"\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\",\"\\K\\J\\D\\B\\B\",\"\\1P\",\"\\P\",\"\\W\\J\\F\\X\\W\",\"\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\X\\W\\1b\\J\\F\\X\",\"\\W\\1b\\Z\\J\\X\\W\\1b\\J\\F\\X\\W\\J\\F\\X\\W\",\"\\X\\W\\Z\\J\\N\\K\\J\\D\\B\\B\\Y\\Q\",\"\\J\\F\",\"\\W\\1b\\Z\\J\\X\\W\\1b\\J\\F\\X\",\"\\Z\\J\",\"\\B\\K\\G\\F\\R\\E\",\"\\E\\A\\1r\\E\\1b\\1T\\D\\1a\\D\\B\\K\\G\\F\\R\\E\",\"\\1c\\E\\E\\R\\B\",\"\\1c\\E\\E\\R\\B\\1x\",\"\\1c\\E\\E\\R\\1x\",\"\\1b\\1b\\1k\\1k\\1k\\V\\1e\\H\\H\\1e\\J\\A\\V\\K\\H\\U\\1b\\K\\B\\A\\1b\\K\\B\\A\\V\\1T\\B\\1M\\K\\1r\\Y\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\1e\\K\\B\\A\\P\\G\\A\\B\\Z\\J\\E\\R\\J\\D\\K\\A\\Q\\X\\W\\1e\\K\\B\\A\\1x\\B\\A\\D\\G\\K\\1c\\G\\A\\B\\Z\\J\\E\\B\\P\\H\\L\\J\\1q\\X\\W\\1b\\1e\\K\\B\\A\\1x\\B\\A\\D\\G\\K\\1c\\G\\A\\B\\Z\\J\\E\\B\\P\\H\\L\\J\\1q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\1L\\1d\\H\\O\\1q\\P\\D\\G\\A\\D\",\"\\K\\Z\\B\\E\\H\\U\\P\\K\\B\\A\\P\\B\\A\\1a\\F\\O\\D\",\"\\B\\A\\D\\G\\K\\1c\\G\\A\\B\\Z\\J\\E\\B\\P\\H\\L\\J\\1q\\1J\",\"\\V\\K\\H\\U\\U\\A\\L\\E\\B\\P\\E\\D\\1d\\B\",\"\\V\\K\\D\\L\\4d\\G\\J\",\"\\V\\1d\\R\\H\\B\\2Q\\O\",\"\\V\\R\\B\\E\\4d\\G\\J\",\"\\W\\O\\F\\1a\\N\\O\\D\\E\\D\\P\\E\\D\\1d\\Y\\1A\\3a\\D\\K\\A\\1d\\H\\H\\1o\\1A\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\1A\\E\\D\\1d\\P\\1g\\D\\K\\A\\1d\\H\\H\\1o\\1A\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\1A\\1g\\1d\\P\\K\\H\\U\\U\\A\\L\\E\\B\\1A\\N\\O\\D\\E\\D\\P\\K\\H\\J\\H\\G\\B\\K\\1c\\A\\U\\A\\Y\\1A\\J\\F\\1e\\1c\\E\\1A\\N\\O\\D\\E\\D\\P\\L\\Z\\U\\R\\H\\B\\E\\B\\Y\\1A\\4j\\1A\\N\\O\\D\\E\\D\\P\\1k\\F\\O\\E\\1c\\Y\\1A\\1N\\1J\\1J\\5U\\1A\\N\\O\\D\\E\\D\\P\\1c\\G\\A\\1g\\Y\\1A\",\"\\1A\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\W\\O\\F\\1a\\N\\O\\D\\E\\D\\P\\E\\D\\1d\\Y\\1A\\2O\\R\\H\\E\\V\\2Q\\2k\\1A\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\1A\\E\\D\\1d\\P\\B\\R\\H\\E\\F\\U\\1A\\X\\W\\O\\F\\1a\\N\\F\\O\\Y\\1A\\B\\R\\H\\E\\P\\F\\U\\P\\1g\\G\\D\\U\\A\\P\\F\\L\\R\\D\\1e\\A\\1A\\N\\O\\D\\E\\D\\P\\R\\H\\B\\E\\P\\F\\O\\Y\\1A\",\"\\W\\O\\F\\1a\\N\\O\\D\\E\\D\\P\\E\\D\\1d\\Y\\1A\\3o\\F\\B\\2j\\Z\\B\\1A\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\1A\\E\\D\\1d\\P\\O\\F\\B\\2j\\Z\\B\\1A\\X\\W\\O\\F\\1a\\N\\F\\O\\Y\\1A\\O\\F\\B\\2j\\Z\\B\\1P\\E\\1c\\G\\A\\D\\O\\1A\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\W\\O\\F\\1a\\N\\O\\D\\E\\D\\P\\E\\D\\1d\\Y\\1A\\3v\\J\\H\\1e\\1e\\A\\G\\1A\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\1A\\E\\D\\1d\\P\\1d\\J\\H\\1e\\1e\\A\\G\\1A\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\F\\1g\\N\\1O\\E\\1c\\F\\B\\V\\1a\\D\\J\\Z\\A\\N\\Y\\Y\\N\\Q\\Q\\1K\\N\\8y\\E\\1c\\F\\B\\V\\1a\\D\\J\\Z\\A\\N\\Y\\N\\Q\",\"\\Q\\1G\\8S\",\"\\F\\1g\\N\\1O\\E\\1c\\F\\B\\V\\1a\\D\\J\\Z\\A\\N\\Y\\Y\\N\\Q\",\"\\Q\\1K\\N\\8y\\E\\1c\\F\\B\\V\\1a\\D\\J\\Z\\A\\N\\Y\\N\\Q\\Q\\1G\\8S\",\"\\V\\A\\G\\G\\H\\G\\B\\G\\K\\N\\F\\L\\R\\Z\\E\\1X\\V\\B\\A\\D\\G\\K\\1c\\P\\1g\\H\\G\\U\\N\\F\\L\\R\\Z\\E\",\"\\1L\\E\\A\\1r\\E\\P\\1g\\F\\L\\O\\A\\G\",\"\\V\\R\\H\\B\\E\\P\\1d\\H\\O\\1q\",\"\\1o\\A\\1q\\Z\\R\",\"\\B\\R\\D\\L\\V\\1c\\F\\1e\\1c\\J\\F\\1e\\1c\\E\",\"\\1g\\H\\K\\Z\\B\",\"\\1g\\H\\L\\E\\1P\\B\\F\\2T\\A\",\"\\1g\\H\\L\\E\\P\\B\\F\\2T\\A\",\"\\R\\1r\",\"\\2T\\H\\H\\U\\P\\F\\L\\P\\E\\A\\1r\\E\",\"\\V\\2T\\H\\H\\U\\P\\E\\A\\1r\\E\",\"\\V\\1d\\E\\L\\E\\A\\1r\\E\\3a\\F\\L\\O\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\1c\\J\\F\\L\\A\\Q\\X\\W\\1b\\B\\R\\D\\L\\X\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\E\\F\\E\\J\\A\\P\\1k\\G\\D\\R\\Q\\X\\W\\1b\\B\\R\\D\\L\\X\",\"\\V\\1k\\F\\O\\1e\\A\\E\\N\\X\\N\\1c\\2a\",\"\\B\\Z\\1d\\P\\U\\A\\L\\Z\",\"\\B\\1c\\H\\1k\",\"\\V\\U\\A\\L\\Z\",\"\\B\\Z\\1d\\P\\B\\Z\\1d\\P\\U\\A\\L\\Z\",\"\\V\\B\\Z\\1d\\P\\U\\A\\L\\Z\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\Z\\1d\\P\\F\\K\\H\\L\\Q\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\Z\\1d\\P\\1d\\Z\\E\\E\\H\\L\\N\\1d\\E\\L\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\K\\D\\G\\A\\E\\P\\O\\H\\1k\\L\\Q\\X\\W\\1b\\F\\X\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\O\\F\\1a\\X\",\"\\B\\Z\\1d\\U\\A\\L\\Z\",\"\\Z\\J\\V\\B\\Z\\1d\\P\\U\\A\\L\\Z\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\Z\\1d\\P\\F\\K\\H\\L\\Q\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\Z\\1d\\P\\1d\\Z\\E\\E\\H\\L\\N\\1d\\E\\L\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\K\\D\\G\\A\\E\\P\\G\\F\\1e\\1c\\E\\Q\\X\\W\\1b\\F\\X\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\O\\F\\1a\\X\",\"\\B\\Z\\1d\\B\\Z\\1d\\U\\A\\L\\Z\",\"\\Z\\J\\V\\B\\Z\\1d\\P\\B\\Z\\1d\\P\\U\\A\\L\\Z\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\1A\\U\\A\\L\\Z\\P\\O\\A\\B\\K\\1A\\X\",\"\\V\\U\\A\\L\\Z\\N\\J\\F\\N\\D\",\"\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\F\\K\\H\\P\\H\\1a\\U\\N\\1g\\D\\P\",\"\\V\\H\\1a\\U\\P\\F\\K\\H\",\"\\1c\\D\\1a\\A\\P\\O\\A\\B\\K\",\"\\V\\U\\A\\L\\Z\\P\\O\\A\\B\\K\",\"\\V\\U\\D\\F\\L\\P\\U\\A\\L\\Z\\N\\J\\F\",\"\\V\\B\\K\\P\\U\\H\\1a\\A\",\"\\V\\B\\Z\\1d\\U\\A\\L\\Z\",\"\\R\\D\\O\\O\\F\\L\\1e\\P\\J\\A\\1g\\E\",\"\\V\\U\\D\\F\\L\\P\\U\\A\\L\\Z\\N\\D\",\"\\D\\V\\1c\\H\\U\\A\\P\\F\\K\\H\\L\",\"\\J\\A\\1g\\E\",\"\\V\\U\\D\\F\\L\\P\\U\\A\\L\\Z\\N\\D\\2u\\1c\\G\\A\\1g\\6v\\Y\\Q\\1L\\Q\\2U\",\"\\A\\D\\B\\A\\4q\\Z\\E\\gQ\\Z\\D\\O\",\"\\L\\H\\1c\\H\\1a\\A\\G\",\"\\V\\U\\D\\F\\L\\P\\U\\A\\L\\Z\\N\\X\\N\\J\\F\",\"\\1x\\L\\H\\E\\1O\\1x\\D\\L\\F\\U\\D\\E\\A\\O\\1K\",\"\\A\\D\\B\\A\\2Q\\L\\3D\\1r\\R\\H\",\"\\V\\U\\A\\L\\Z\\N\\J\\F\",\"\\V\\U\\A\\L\\Z\\P\\B\\A\\D\\G\\K\\1c\",\"\\B\\G\\K\\P\\B\\1c\\H\\1k\",\"\\E\\H\\1e\\1e\\J\\A\\P\\H\\L\",\"\\V\\B\\G\\K\\L\\D\\1a\\1d\\Z\\E\\E\\H\\L\",\"\\V\\3p\\F\\L\\1o\\3p\\F\\B\\E\",\"\\3p\\F\\1o\\A\\B\",\"\\V\\F\\E\\A\\U\\P\\E\\A\\1r\\E\",\"\\V\\F\\K\\H\\L\\P\\1g\\D\\K\\A\\1d\\H\\H\\1o\",\"\\2O\\Z\\1d\\B\\K\\G\\F\\1d\\A\\B\",\"\\V\\F\\K\\H\\L\\P\\G\\B\\B\\1X\\V\\F\\K\\H\\L\\P\\1q\\H\\Z\\E\\Z\\1d\\A\",\"\\2u\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\F\\E\\A\\U\\P\\K\\H\\Z\\L\\E\\Q\\X\",\"\\6v\",\"\\2U\",\"\\V\\1c\\F\\O\\A\\P\\K\\H\\Z\\L\\E\",\"\\V\\F\\E\\A\\U\\P\\K\\H\\Z\\L\\E\",\"\\V\\B\\H\\K\\F\\D\\J\\P\\1k\\G\\D\\R\",\"\\V\\J\\D\\1d\\A\\J\\1c\\F\\O\\A\",\"\\V\\R\\J\\D\\1d\\A\\J\\B\",\"\\4V\\Z\\B\\E\\H\\U\\2O\\K\\G\\H\\J\\J\\1d\\D\\G\",\"\\V\\R\\J\\D\\1d\\A\\J\\B\\1d\\E\\L\",\"\\1c\\2a\",\"\\O\\D\\E\\D\\P\\E\\D\\1d\",\"\\V\\1k\\F\\O\\1e\\A\\E\",\"\\1L\\B\\F\\O\\A\\1d\\D\\G\\P\\E\\D\\1d\\B\\1N\",\"\\1g\\D\\O\\A\",\"\\V\\F\\L\\O\\A\\1r\\N\\V\\R\\H\\B\\E\\1X\\N\\V\\D\\G\\K\\1c\\F\\1a\\A\\N\\V\\R\\H\\B\\E\",\"\\R\\V\\K\\H\\U\\U\\A\\L\\E\\P\\K\\H\\L\\E\\A\\L\\E\\1X\\N\\O\\F\\1a\\V\\A\\U\\H\\6w\\G\\D\\R\",\"\\4V\\J\\F\\K\\1o\\N\\E\\H\\N\\B\\A\\A\\N\\E\\1c\\A\\N\\K\\H\\O\\A\\c5\",\"\\2p\\H\\N\\F\\L\\B\\A\\G\\E\\N\\A\\U\\H\\E\\F\\K\\H\\L\\N\\1q\\H\\Z\\N\\U\\Z\\B\\E\\N\\D\\O\\O\\A\\O\\N\\D\\E\\N\\J\\A\\D\\B\\E\\N\\H\\L\\A\\N\\B\\R\\D\\K\\A\\N\\1d\\A\\1g\\H\\G\\A\\N\\E\\1c\\A\\N\\K\\H\\O\\A\\V\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\A\\U\\H\\P\\1d\\Z\\E\\E\\H\\L\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\B\\U\\F\\J\\A\\P\\H\\Q\\X\\W\\1b\\F\\X\\3D\\U\\H\\E\\F\\K\\H\\L\\W\\1b\\B\\R\\D\\L\\X\\W\\O\\F\\1a\\N\\B\\E\\1q\\J\\A\\Y\\Q\\E\\A\\1r\\E\\P\\D\\J\\F\\1e\\L\\1x\\K\\A\\L\\E\\A\\G\\Q\\N\\K\\J\\D\\B\\B\\Y\\Q\\A\\U\\H\\6w\\G\\D\\R\\Q\\X\\N\\1x\\1K\\N\\1x\\1K\\1K\\N\\1G\\1O\\1O\\N\\1x\\P\\1K\\N\\Y\\1K\\1K\\N\\1G\\1O\\N\\1G\\P\\1O\\N\\1x\\O\\N\\1x\\P\\O\\N\\cy\\P\\1K\\N\\1x\\R\\N\\1x\\H\\N\\1x\\1z\\1e\\E\\1G\\1K\\N\\1O\\H\\1K\\N\\2u\\P\\1O\\N\\1x\\P\\1M\\N\\1O\\R\\1K\\N\\1x\\P\\B\\N\\1O\\U\\1K\\N\\5T\\P\\1K\\N\\1x\\P\\E\\N\\1x\\P\\1d\\N\\N\\1d\\P\\1O\\N\\1x\\P\\1L\\N\\Y\\R\\dg\\N\\8g\\P\\1K\\N\\1O\\1d\\1K\\N\\1O\\1g\\1K\\N\\1r\\P\\1K\\N\\1O\\1o\\1K\\N\\1O\\1c\\1K\\N\\1O\\K\\1K\\N\\K\\1c\\A\\A\\G\\N\\W\\1d\\G\\1b\\X\\W\\1d\\X\",\"\\W\\1b\\1d\\X\\W\\1d\\G\\1b\\X\",\"\\F\\1g\\G\\D\\U\\A\\1L\\K\\H\\U\\U\\A\\L\\E\\P\\A\\O\\F\\E\\H\\G\",\"\\N\\W\",\"\\N\\1k\\F\\O\\E\\1c\\Y\\1A\\2c\\5j\\1A\\N\\1c\\A\\F\\1e\\1c\\E\\Y\\1A\\2c\\5j\\1A\\N\\B\\E\\1q\\J\\A\\Y\\1A\\U\\D\\1r\\P\\1c\\A\\F\\1e\\1c\\E\\1x\\2a\\2w\\R\\1r\\1G\\U\\D\\1r\\P\\1k\\F\\O\\E\\1c\\1x\\2a\\2w\\R\\1r\\1A\\N\\B\\G\\K\\Y\\1A\",\"\\1A\\N\\K\\J\\D\\B\\B\\Y\\1A\\A\\U\\H\\N\\O\\A\\J\\D\\1q\\3p\\H\\D\\O\\1A\\N\\D\\J\\E\\Y\\1A\",\"\\1A\\N\\1b\\X\",\"\\W\\1d\\G\\X\\N\\wC\",\"\\W\\1d\\G\\X\\N\\Y\",\"\\W\\1d\\G\\X\\N\\1G\",\"\\W\\1d\\G\\X\\N\\1x\",\"\\1x\\1K\\1K\",\"\\1G\\1O\\1O\",\"\\1x\\1K\",\"\\1x\\P\\1K\",\"\\Y\\1K\\1K\",\"\\1G\\1O\",\"\\1G\\P\\1O\",\"\\1x\\O\",\"\\1x\\P\\O\",\"\\cy\\P\\1K\",\"\\1x\\R\",\"\\1x\\H\",\"\\1x\\1z\\1e\\E\\1G\\1K\",\"\\1O\\H\\1K\",\"\\2u\\P\\1O\",\"\\1x\\P\\1M\",\"\\1O\\R\\1K\",\"\\1x\\P\\B\",\"\\1O\\U\\1K\",\"\\5T\\P\\1K\",\"\\1x\\P\\E\",\"\\1x\\P\\1d\",\"\\1d\\P\\1O\",\"\\1x\\P\\1L\",\"\\Y\\R\\dg\",\"\\8g\\P\\1K\",\"\\1O\\1d\\1K\",\"\\1O\\1g\\1K\",\"\\1r\\P\\1K\",\"\\1O\\1o\\1K\",\"\\1O\\1c\\1K\",\"\\1O\\K\\1K\",\"\\K\\1c\\A\\A\\G\",\"\\V\\A\\U\\H\\4Y\\A\\1q\",\"\\W\\F\\L\\R\\Z\\E\\N\\K\\J\\D\\B\\B\\Y\\Q\\A\\U\\H\\4Y\\A\\1q\\Q\\N\\E\\1q\\R\\A\\Y\\Q\\E\\A\\1r\\E\\Q\\N\\B\\F\\2T\\A\\Y\\Q\",\"\\Q\\N\\1a\\D\\J\\Z\\A\\Y\\Q\\N\",\"\\Q\\N\\1b\\X\",\"\\B\\A\\J\\A\\K\\E\",\"\\K\\Z\\G\\B\\H\\G\",\"\\R\\H\\F\\L\\E\\A\\G\",\"\\V\\A\\U\\H\",\"\\V\\A\\U\\H\\6w\\G\\D\\R\",\"\\V\\A\\U\\H\\P\\1d\\Z\\E\\E\\H\\L\",\"\\V\\R\\H\\B\\E\\P\\H\\Z\\E\\A\\G\\N\\X\\N\\V\\K\\H\\U\\U\\A\\L\\E\\B\",\"\\1c\\H\\U\\A\\P\\D\\G\\A\\D\",\"\\1L\\H\\Z\\E\\A\\G\\P\\1k\\G\\D\\R\\R\\A\\G\",\"\\V\\1d\\J\\H\\1e\\P\\R\\H\\B\\E\\B\",\"\\F\\L\\O\\A\\1r\",\"\\V\\B\\A\\D\\G\\K\\1c\\gQ\\Z\\A\\G\\A\\O\",\"\\D\\G\\K\\1c\\F\\1a\\A\",\"\\D\\1d\\J\\F\\B\\E\",\"\\D\\1d\\1e\\G\\F\\R\",\"\\B\\E\\1q\\J\\A\\Y\\Q\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\P\\K\\H\\J\\H\\G\\1x\",\"\\Q\\N\",\"\\V\\6o\\2p\\2k\\3p\",\"\\W\\O\\F\\1a\\N\",\"\\1g\\2a\",\"\\B\\J\\F\\O\\A\\P\\1k\\F\\O\\E\\1c\\Y\\5j\\2c\\1J\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\1k\\F\\O\\1e\\A\\E\\P\\D\\G\\A\\D\\N\\J\\H\\D\\O\\F\\L\\1e\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\1k\\F\\O\\P\\R\\D\\1e\\A\\L\\Z\\U\\1d\\A\\G\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\",\"\\W\\D\\N\",\"\\K\\J\\D\\B\\B\\Y\\Q\\1k\\F\\O\\P\\R\\D\\1e\\A\\L\\Z\\U\\N\\1d\\E\\L\\Q\\N\\D\\J\\E\\Y\\Q\\1N\\Q\\X\\1z\\1L\\1N\\3g\\1N\\1G\\W\\1b\\D\\X\",\"\\K\\J\\D\\B\\B\\Y\\Q\\1k\\F\\O\\P\\R\\D\\1e\\A\\L\\Z\\U\\N\\1d\\E\\L\\Q\\N\\D\\J\\E\\Y\\Q\",\"\\Q\\X\\1z\\1L\\1N\\3g\\1N\\1G\\W\\1b\\D\\X\",\"\\K\\J\\D\\B\\B\\Y\\Q\\1k\\F\\O\\P\\R\\D\\1e\\A\\L\\Z\\U\\N\\1d\\E\\L\\Q\\N\\D\\J\\E\\Y\\Q\\1N\\Q\\X\\1N\\W\\1b\\D\\X\",\"\\W\\B\\R\\D\\L\\X\\N\\V\\V\\V\\N\\W\\1b\\B\\R\\D\\L\\X\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\K\\E\\Z\\D\\J\\Q\\X\",\"\\W\\1b\\D\\X\",\"\\Q\\X\\1z\\1L\\1N\\5T\\3g\\1G\\W\\1b\\D\\X\",\"\\V\\1k\\F\\O\\P\\R\\D\\1e\\A\\L\\Z\\U\\1d\\A\\G\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\1c\\D\\L\\O\\J\\A\\N\\1T\\B\\H\\L\\P\\R\\G\\H\\K\\A\\B\\B\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\1k\\F\\O\\1e\\A\\E\\P\\D\\G\\A\\D\",\"\\V\\1c\\D\\L\\O\\J\\A\",\"\\O\\D\\E\\D\\P\\E\\D\\1e\",\"\\1b\\1g\\A\\A\\O\\B\\1b\\R\\H\\B\\E\\B\\1b\\O\\A\\1g\\D\\Z\\J\\E\\1M\\B\\E\\D\\G\\E\\P\\F\\L\\O\\A\\1r\\Y\",\"\\1z\\H\\G\\O\\A\\G\\1d\\1q\\Y\\R\\Z\\1d\\J\\F\\B\\1c\\A\\O\\1z\\D\\J\\E\\Y\\1T\\B\\H\\L\\P\\F\\L\\P\\B\\K\\G\\F\\R\\E\",\"\\1b\\1g\\A\\A\\O\\B\\1b\\R\\H\\B\\E\\B\\1b\\O\\A\\1g\\D\\Z\\J\\E\\1b\\P\\1b\",\"\\V\\1k\\F\\O\\P\\R\\D\\1e\\A\\L\\Z\\U\",\"\\G\\A\\R\\J\\F\\A\\B\",\"\\E\\A\\1r\\E\\1b\\1c\\E\\U\\J\",\"\\1g\\B\",\"\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\F\\A\\1k\\P\\R\\J\\D\\K\\A\\Q\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\F\\A\\1k\\P\\1a\\D\\J\\Z\\A\\Q\\X\",\"\\W\\1b\\B\\R\\D\\L\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\J\\F\\K\\A\\Q\\X\\W\\O\\F\\1a\\N\\B\\E\\1q\\J\\A\\Y\\Q\\1k\\F\\O\\E\\1c\\1x\",\"\\5U\\Q\\N\\K\\J\\D\\B\\B\\Y\\Q\\1d\\D\\G\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\1d\\J\\H\\1e\\B\\R\\H\\E\",\"\\K\\H\\U\",\"\\V\\1d\\J\\H\\1e\\B\\R\\H\\E\\V\\K\\H\\U\",\"\\J\\H\\D\\O\\P\\D\\O\\O\\A\\O\",\"\\V\\F\\E\\A\\U\\B\\1x\\1e\\E\\1O\",\"\\V\\1g\\1d\\F\\1e\\P\\1k\\F\\O\\1e\\A\\E\\P\\D\\G\\A\\D\",\"\\H\\1k\\J\\P\\K\\D\\G\\H\\Z\\B\\A\\J\",\"\\1g\\D\\O\\A\\4q\\Z\\E\",\"\\1g\\J\\F\\R\",\"\\B\\J\\F\\O\\A\\4q\\Z\\E\\3o\\H\\1k\\L\",\"\\1g\\J\\F\\R\\2Q\\L\\bV\",\"\\K\",\"\\V\\H\\1k\\J\\P\\L\\D\\1a\",\"\\V\\L\\A\\1k\\B\\E\\F\\K\\1o\\A\\G\",\"\\G\\E\\J\",\"\\J\\E\\G\",\"\\V\\E\\F\\K\\1o\\A\\G\\P\\E\\F\\E\\J\\A\",\"\\B\\J\\F\\O\\A\\P\\1k\\F\\O\\E\\1c\",\"\\V\\H\\1k\\J\\P\\R\\G\\A\\1a\\1X\\V\\H\\1k\\J\\P\\L\\A\\1r\\E\",\"\\L\\H\\P\\1d\\1e\\P\\F\\U\\D\\1e\\A\",\"\\V\\F\\E\\A\\U\\B\",\"\\1N\\1J\\R\\1r\",\"\\V\\H\\1k\\J\\P\\B\\E\\D\\1e\\A\",\"\\5j\\2c\\1J\\R\\1r\",\"\\P\\5j\\2c\\1J\\R\\1r\",\"\\V\\1g\\J\\Z\\F\\O\\P\\1k\\F\\O\\E\\1c\\P\\1a\\F\\O\\A\\H\\P\\1k\\G\\D\\R\\R\\A\\G\",\"\\F\\1g\\G\\D\\U\\A\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\1A\\1k\\G\\D\\R\\F\\E\\A\\U\\1A\\X\\W\\1b\\O\\F\\1a\\X\",\"\\1g\\2c\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\1A\\1g\\A\\D\\E\\P\\1k\\G\\D\\R\\F\\E\\A\\U\\1A\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\1g\\A\\D\\E\\P\\1k\\G\\D\\R\\F\\E\\A\\U\\1x\\1g\\F\\G\\B\\E\\P\\K\\1c\\F\\J\\O\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\1A\\D\\L\\F\\U\\D\\E\\A\\O\\P\\F\\E\\A\\U\\1A\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\D\\L\\F\\U\\D\\E\\A\\O\\P\\F\\E\\A\\U\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\L\\F\\U\\D\\E\\A\\O\\P\\D\\G\\A\\D\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\U\\H\\Z\\B\\A\\J\\A\\D\\1a\\A\\N\\E\\H\\Z\\K\\1c\\A\\L\\O\",\"\\B\\E\\D\\G\\E\",\"\\U\\H\\Z\\B\\A\\A\\L\\E\\A\\G\\N\\E\\H\\Z\\K\\1c\\B\\E\\D\\G\\E\",\"\\B\\E\\H\\R\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\1A\\1g\\1d\\F\\1e\\P\\1k\\F\\O\\1e\\A\\E\\P\\D\\G\\A\\D\\1A\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\1d\\H\\E\\E\\H\\U\\P\\U\\H\\G\\A\\R\\H\\B\\E\",\"\\U\\4V\\Z\\B\\E\\H\\U\\2O\\K\\G\\H\\J\\J\\1d\\D\\G\",\"\\O\\A\\B\\E\\G\\H\\1q\",\"\\V\\L\\A\\1k\\B\\U\\H\\G\\A\\F\\L\\1g\\H\",\"\\V\\1d\\H\\O\\1q\\P\\D\\G\\A\\D\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\L\\A\\1k\\B\\U\\H\\G\\A\\F\\L\\1g\\H\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\N\\1c\\H\\1a\\A\\G\\1e\\D\\J\\J\\A\\G\\1q\",\"\\D\\K\\E\\F\\1a\\A\\N\\1d\\H\\E\\1k\\F\\O\",\"\\V\\1c\\H\\1a\\A\\1g\\1g\\A\\K\\E\",\"\\1a\\F\\B\\F\\1d\\F\\J\\F\\E\\1q\",\"\\1a\\F\\B\\F\\1d\\J\\A\",\"\\J\\H\\D\\O\\F\\L\\1e\",\"\\V\\H\\1k\\J\\P\\K\\D\\G\\H\\Z\\B\\A\\J\",\"\\V\\H\\1k\\J\\P\\O\\H\\E\",\"\\B\\K\\H\\G\\A\",\"\\O\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\",\"\\1g\\F\\G\\B\\E\\P\\F\\E\\A\\U\\N\",\"\\F\\E\\A\\U\\B\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\F\\E\\A\\U\\B\\P\\F\\L\\L\\A\\G\\Q\\X\",\"\\K\\J\\D\\B\\B\\Y\\Q\\R\\H\\B\\E\\O\\D\\E\\A\\Q\\X\\W\\B\\E\\G\\H\\L\\1e\\X\",\"\\W\\1b\\B\\U\\D\\J\\J\\X\\W\\1b\\O\\F\\1a\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\E\\1c\\Z\\U\\1d\\P\\H\\Z\\E\\A\\G\",\"\\N\\1c\\H\\1a\\A\\1g\\1g\\A\\K\\E\",\"\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\E\\1c\\Z\\U\\1d\\P\\D\\G\\A\\D\",\"\\N\\1g\\F\\G\\B\\E\\P\\F\\U\\D\\1e\\A\",\"\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\R\\H\\B\\E\\P\\E\\1q\\R\\A\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\",\"\\Q\\X\\W\\1b\\F\\X\\W\\1b\\O\\F\\1a\\X\\W\",\"\\1g\",\"\\1g\\A\\D\\E\\E\\1c\\Z\\U\\1d\",\"\\G\\K\\E\\1c\\Z\\U\\1d\",\"\\Q\\N\\E\\F\\E\\J\\A\\Y\\Q\",\"\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\Q\\N\\B\\E\\1q\\J\\A\\Y\\Q\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\1x\",\"\\N\\L\\H\\P\\G\\A\\R\\A\\D\\E\\N\\K\\A\\L\\E\\A\\G\\N\\K\\A\\L\\E\\A\\G\\1G\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\P\\B\\F\\2T\\A\\1x\\N\\K\\H\\1a\\A\\G\\Q\\X\",\"\\1q\\E\\F\\U\\1e\\V\\1e\\H\\H\\1e\\J\\A\\Z\\B\\A\\G\\K\\H\\L\\E\\A\\L\\E\\V\\K\\H\\U\",\"\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\",\"\\1g\\F\\G\\B\\E\\P\\D\\G\\A\\D\",\"\\K\\H\\L\\E\\A\\L\\E\\P\\D\\G\\A\\D\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\K\\R\\E\\D\\1e\\B\\Q\\X\\W\",\"\\K\\J\\D\\B\\B\\Y\\Q\\1d\\E\\L\\Q\\N\\E\\F\\E\\J\\A\\Y\\Q\",\"\\1M\\U\\D\\1r\\P\\G\\A\\B\\Z\\J\\E\\B\\Y\",\"\\W\\1c\\2c\",\"\\N\\B\\E\\1q\\J\\A\\Y\\Q\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\P\\K\\H\\J\\H\\G\\1x\",\"\\Q\",\"\\X\\W\",\"\\K\\J\\D\\B\\B\\Y\\Q\\1c\\H\\1a\\A\\1g\\1g\\A\\K\\E\\Q\",\"\\X\\W\\1b\\1c\\2c\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\R\\B\\E\\U\\A\\E\\D\\F\\L\\1g\\H\\Q\\X\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\1k\\F\\O\\P\\D\\Z\\E\\1c\\H\\G\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\Z\\B\\A\\G\\Q\\X\\W\\1b\\F\\X\\N\",\"\\W\\1b\\B\\R\\D\\L\\X\\N\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\1k\\F\\O\\P\\O\\D\\E\\A\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\K\\D\\J\\A\\L\\O\\D\\G\\Q\\X\\W\\1b\\F\\X\\N\",\"\\3o\\3o\",\"\\2k\\2k\",\"\\4l\\4l\\4l\\4l\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\1k\\F\\O\\K\\H\\U\\U\\A\\L\\E\\B\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\K\\H\\U\\U\\A\\L\\E\\B\\Q\\X\\W\\1b\\F\\X\\N\\W\",\"\\1L\\K\\H\\U\\U\\A\\L\\E\\P\\1g\\H\\G\\U\\Q\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\R\\B\\Z\\U\\U\\D\\G\\1q\\Q\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\K\\G\\A\\D\\O\\2k\\H\\G\\A\\Q\\X\\W\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\D\\O\\U\\H\\G\\A\\1d\\Z\\E\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\1L\\U\\H\\G\\A\\Q\\N\\E\\F\\E\\J\\A\\Y\\Q\\4W\\A\\D\\O\\N\\U\\H\\G\\A\\N\\dL\\N\",\"\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\D\\2u\\K\\J\\D\\B\\B\\Y\\Q\\F\\E\\A\\U\\P\\E\\D\\1e\\Q\\2U\\1x\\J\\E\\1O\",\"\\W\\1c\\2w\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\E\\F\\E\\J\\A\\P\\1k\\G\\D\\R\\Q\\X\",\"\\W\\1b\\B\\R\\D\\L\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\1c\\J\\F\\L\\A\\Q\\X\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\1c\\2w\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\H\\1k\\J\\P\\L\\D\\1a\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\1b\\1g\\A\\A\\O\\B\\1b\\R\\H\\B\\E\\B\\1b\\B\\Z\\U\\U\\D\\G\\1q\\1M\\U\\D\\1r\\P\\G\\A\\B\\Z\\J\\E\\B\\Y\\1J\\1z\\H\\G\\O\\A\\G\\1d\\1q\\Y\\R\\Z\\1d\\J\\F\\B\\1c\\A\\O\\1z\\D\\J\\E\\Y\\1T\\B\\H\\L\\P\\F\\L\\P\\B\\K\\G\\F\\R\\E\",\"\\1b\\1g\\A\\A\\O\\B\\1b\\R\\H\\B\\E\\B\\1b\",\"\\1z\\H\\G\\O\\A\\G\\1d\\1q\\Y\\R\\Z\\1d\\J\\F\\B\\1c\\A\\O\\1z\\B\\E\\D\\G\\E\\P\\F\\L\\O\\A\\1r\\Y\",\"\\1z\\D\\J\\E\\Y\\1T\\B\\H\\L\\P\\F\\L\\P\\B\\K\\G\\F\\R\\E\",\"\\1b\\P\\1b\",\"\\1b\\1g\\A\\A\\O\\B\\1b\\K\\H\\U\\U\\A\\L\\E\\B\\1b\\O\\A\\1g\\D\\Z\\J\\E\\1M\\D\\J\\E\\Y\\1T\\B\\H\\L\\P\\F\\L\\P\\B\\K\\G\\F\\R\\E\\1z\\H\\G\\O\\A\\G\\1d\\1q\\Y\\R\\Z\\1d\\J\\F\\B\\1c\\A\\O\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\K\\H\\U\\U\\A\\L\\E\\P\\D\\G\\A\\D\\Q\\X\",\"\\1d\\J\\H\\1e\\1e\\A\\G\\V\\O\\F\\B\\R\\J\\D\\1q\\2p\\F\\U\\A\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\K\\H\\U\\U\\A\\L\\E\\P\\F\\E\\A\\U\",\"\\N\\G\\K\\D\\O\\U\\F\\L\",\"\\N\\G\\K\\1e\\Z\\A\\B\\E\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\K\\H\\U\\U\\A\\L\\E\\P\\F\\U\\1e\\Q\\N\\E\\D\\G\\1e\\A\\E\\Y\\Q\\1P\\1d\\J\\D\\L\\1o\\Q\\N\\G\\A\\J\\Y\\Q\\L\\H\\1g\\H\\J\\J\\H\\1k\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\Q\\X\\W\\F\\U\\1e\\N\\D\\J\\E\\Y\\Q\",\"\\Q\\N\\B\\G\\K\\Y\\Q\",\"\\Q\\1b\\X\\W\\1b\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\K\\H\\U\\U\\A\\L\\E\\P\\F\\L\\1g\\H\\Q\\X\\W\",\"\\N\\E\\D\\G\\1e\\A\\E\\Y\\Q\\1P\\1d\\J\\D\\L\\1o\\Q\\N\\G\\A\\J\\Y\\Q\\L\\H\\1g\\H\\J\\J\\H\\1k\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\X\\N\\H\\L\\N\\W\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\K\\H\\U\\U\\A\\L\\E\\P\\E\\F\\E\\J\\A\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\K\\H\\U\\U\\A\\L\\E\\P\\U\\A\\E\\D\\Q\\X\",\"\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\K\\H\\U\\U\\A\\L\\E\\P\\B\\Z\\U\\U\\D\\G\\1q\\Q\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\K\\J\\A\\D\\G\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\N\\B\\G\\K\\Y\\1A\",\"\\1A\\N\\K\\J\\D\\B\\B\\Y\\1A\\A\\U\\H\\1A\\N\\D\\J\\E\\Y\\1A\",\"\\V\\G\\K\\H\\U\\U\\A\\L\\E\\P\\B\\Z\\U\\U\\D\\G\\1q\",\"\\W\\B\\R\\D\\L\\X\\2E\\H\\N\\G\\A\\B\\Z\\J\\E\\c5\\W\\1b\\B\\R\\D\\L\\X\",\"\\1S\\L\\H\\L\\1q\\U\\H\\Z\\B\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\2w\\V\\1d\\R\\V\\1d\\J\\H\\1e\\B\\R\\H\\E\\V\\K\\H\\U\\1b\\P\\1S\\3D\\6w\\1o\\B\\4Y\\6F\\2w\\2a\\4q\\3D\\1b\\4d\\3a\\F\\1q\\3p\\2T\\bV\\5l\\1c\\F\\2Q\\1b\\1S\\1S\\1S\\1S\\1S\\1S\\1S\\1S\\3a\\4Y\\3D\\1b\\1T\\3v\\A\\1e\\D\\7r\\2m\\4V\\J\\1r\\2Q\\1b\\B\\3g\\1J\\1b\\Z\\B\\A\\G\\P\\D\\L\\H\\L\\1q\\U\\H\\Z\\B\\P\\F\\K\\H\\L\\V\\R\\L\\1e\",\"\\E\\H\\H\\J\\E\\F\\R\\N\\O\\D\\F\\J\\1q\\U\\H\\E\\F\\H\\L\\N\\1q\\H\\Z\\E\\Z\\1d\\A\\N\\B\\H\\Z\\L\\O\\K\\J\\H\\Z\\O\\N\\K\\H\\O\\A\\N\\D\\K\\K\\H\\G\\O\\F\\H\\L\\N\\K\\H\\L\\E\\A\\L\\E\\N\\F\\E\\A\\U\\N\\D\\J\\A\\G\\E\\N\\B\\Z\\K\\K\\A\\B\\B\\N\\1k\\D\\G\\L\\F\\L\\1e\\N\\Z\\R\\O\\D\\E\\A\\N\\A\\G\\G\\H\\G\\N\\F\\L\\1g\\H\\N\\E\\D\\1d\\N\\1a\\E\\D\\1d\\N\\1e\\D\\J\\J\\A\\G\\1q\\N\\1d\\1e\\D\\J\\J\\A\\G\\1q\\N\\F\\U\\1e\\N\\K\\H\\L\\E\\D\\K\\E\\N\\2a\\K\\H\\J\\Z\\U\\L\\N\\2c\\K\\H\\J\\Z\\U\\L\\N\\2w\\K\\H\\J\\Z\\U\\L\\N\\B\\J\\F\\O\\A\\N\\K\\D\\G\\H\\Z\\B\\A\\J\\N\\U\\D\\R\\N\\G\\A\\1a\\F\\A\\1k\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\G\\E\\N\\B\\1c\\G\\E\\P\",\"\\2u\\1b\",\"\\1b\\2U\",\"\\1L\\O\\G\\K\\U\\E\",\"\\W\\B\\K\\G\\F\\R\\E\\N\\E\\1q\\R\\A\\Y\\Q\\E\\A\\1r\\E\\1b\\1T\\D\\1a\\D\\B\\K\\G\\F\\R\\E\\Q\\N\\B\\G\\K\\Y\\Q\\1c\\E\\E\\R\\1x\\1b\\1b\",\"\\V\\O\\F\\B\\2j\\Z\\B\\V\\K\\H\\U\\1b\\G\\A\\K\\A\\L\\E\\1P\\K\\H\\U\\U\\A\\L\\E\\B\\1P\\1k\\F\\O\\1e\\A\\E\\V\\1T\\B\\1M\\L\\Z\\U\\1P\\F\\E\\A\\U\\B\\Y\",\"\\1z\\D\\1a\\D\\E\\D\\G\\1P\\B\\F\\2T\\A\\Y\\2c\\2a\\1z\\A\\1r\\K\\A\\G\\R\\E\\1P\\J\\A\\L\\1e\\E\\1c\\Y\\1N\\1J\\1J\\1z\\1c\\F\\O\\A\\1P\\U\\H\\O\\B\\Y\\1J\\Q\\N\\X\\W\\1b\\B\\K\\G\\F\\R\\E\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\K\\H\\U\\U\\A\\L\\E\\P\\B\\Z\\U\\U\\D\\G\\1q\\Q\\N\\1b\\X\",\"\\V\\O\\B\\2j\\P\\1k\\F\\O\\1e\\A\\E\\P\\Z\\B\\A\\G\\1X\\V\\O\\B\\2j\\P\\1k\\F\\O\\1e\\A\\E\\P\\K\\H\\U\\U\\A\\L\\E\\1X\\V\\O\\B\\2j\\P\\1k\\F\\O\\1e\\A\\E\\P\\U\\A\\E\\D\",\"\\V\\O\\B\\2j\\P\\1k\\F\\O\\1e\\A\\E\\P\\F\\E\\A\\U\",\"\\1L\\1g\\J\\F\\K\\1o\\G\\F\\O\",\"\\W\\B\\K\\G\\F\\R\\E\\N\\E\\1q\\R\\A\\Y\\Q\\E\\A\\1r\\E\\1b\\1T\\D\\1a\\D\\B\\K\\G\\F\\R\\E\\Q\\N\\B\\G\\K\\Y\\Q\\1c\\E\\E\\R\\1x\\1b\\1b\\1k\\1k\\1k\\V\\1g\\J\\F\\K\\1o\\G\\V\\K\\H\\U\\1b\\1d\\D\\O\\1e\\A\\1P\\K\\H\\O\\A\\1P\\1a\\2a\\V\\1e\\L\\A\\1M\\K\\H\\Z\\L\\E\\Y\",\"\\1z\\O\\F\\B\\R\\J\\D\\1q\\Y\\J\\D\\E\\A\\B\\E\\1z\\B\\F\\2T\\A\\Y\\B\\1z\\J\\D\\1q\\H\\Z\\E\\Y\\1r\\1z\\B\\H\\Z\\G\\K\\A\\Y\\Z\\B\\A\\G\\1z\\Z\\B\\A\\G\\Y\",\"\\Q\\X\\W\\1b\\B\\K\\G\\F\\R\\E\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\A\\1a\\F\\O\\D\\P\\1g\\J\\F\\K\\1o\\G\\Q\\X\",\"\\V\\F\\U\\D\\1e\\A\\P\\U\\D\\L\\Z\\D\\J\\P\\B\\J\\F\\O\\A\",\"\\V\\2Q\\U\\D\\1e\\A\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\D\\L\\Z\\D\\J\\P\\B\\J\\F\\O\\A\\P\\R\\J\\D\\K\\A\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\U\\D\\L\\Z\\D\\J\\P\\F\\U\\1e\\P\\G\\D\\1k\",\"\\O\\D\\E\\D\\P\\E\\F\\E\\J\\A\",\"\\O\\D\\E\\D\\P\\J\\F\\L\\1o\",\"\\O\\D\\E\\D\\P\\K\\D\\R\\E\\F\\H\\L\",\"\\V\\U\\D\\L\\Z\\D\\J\\P\\B\\J\\F\\O\\A\\P\\R\\J\\D\\K\\A\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\B\\J\\F\\O\\A\\P\\F\\E\\A\\U\\Q\\X\\W\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\B\\J\\F\\O\\A\\P\\F\\U\\1e\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\Q\\X\\W\",\"\\N\\B\\G\\K\\Y\\Q\",\"\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\B\\J\\F\\O\\A\\P\\F\\L\\1g\\H\\Q\\X\\W\\1c\\2c\\X\\W\",\"\\X\\W\\1b\\1c\\2c\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\K\\D\\R\\E\\F\\H\\L\\Q\\X\",\"\\1g\\D\\K\\A\\1d\\H\\H\\1o\\P\\1T\\B\\B\\O\\1o\",\"\\1b\\1b\\K\\H\\L\\L\\A\\K\\E\\V\\1g\\D\\K\\A\\1d\\H\\H\\1o\\V\\L\\A\\E\\1b\",\"\\1b\\B\\O\\1o\\V\\1T\\B\",\"\\1a\\2a\\V\\2w\",\"\\A\\O\\1e\\A\\V\\K\\G\\A\\D\\E\\A\",\"\\Z\\L\\J\\H\\K\\1o\\1P\\K\\H\\L\\E\\A\\L\\E\",\"\\U\\A\\B\\B\\D\\1e\\A\\V\\B\\A\\L\\O\",\"\\1r\\1g\\1d\\U\\J\\V\\G\\A\\L\\O\\A\\G\",\"\\V\\3a\\3v\\1d\\H\\1r\\2O\\A\\1a\\F\\O\\D\",\"\\J\\H\\D\\O\\P\\O\\H\\L\\A\",\"\\8y\",\"\\8S\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\K\\A\\L\\E\\P\\E\\D\\1d\\Q\\X\",\"\\W\\O\\F\\1a\\N\\O\\D\\E\\D\\P\\E\\D\\1d\\Y\\Q\",\"\\V\\G\\A\\K\\A\\L\\E\\P\\E\\D\\1d\",\"\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\B\\E\\D\\G\\P\\H\\Q\\X\\W\\1b\\F\\X\\N\\N\",\"\\N\\1c\\G\\A\\1g\\Y\\Q\\1b\\B\\A\\D\\G\\K\\1c\",\"\\1b\\J\\D\\1d\\A\\J\\1b\",\"\\Q\\X\\W\\1b\",\"\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\G\\B\\B\\P\\B\\2j\\Z\\D\\G\\A\\Q\\X\\W\\1b\\F\\X\\N\",\"\\V\\E\\F\\E\\J\\A\\P\\1k\\G\\D\\R\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\H\\G\\A\\R\\H\\B\\E\\N\\1d\\E\\L\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\1b\\B\\A\\D\\G\\K\\1c\",\"\\B\\J\\F\\O\\A\\G\\N\",\"\\K\\H\\J\\Z\\U\\L\\N\",\"\\1g\\1d\\F\\1e\\N\",\"\\1e\\D\\J\\J\\A\\G\\1q\\N\",\"\\1g\\A\\D\\E\\Z\\G\\A\\O\\N\",\"\\K\\D\\G\\H\\Z\\B\\A\\J\\N\",\"\\U\\1o\\1d\\J\\H\\K\\1o\\N\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\H\\1k\\J\\P\\K\\H\\L\\E\\G\\H\\J\\B\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\H\\1k\\J\\P\\L\\D\\1a\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\N\\B\\A\\1a\\F\\O\\D\\P\\1k\\F\\O\\1e\\A\\E\\N\\K\\H\\U\\R\\J\\A\\1r\",\"\\K\\H\\L\\E\\A\\L\\E\\P\\J\\D\\1q\\H\\Z\\E\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\1d\\H\\E\\E\\H\\U\\P\\U\\H\\G\\A\\R\\H\\B\\E\\N\\1d\\E\\L\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\1b\\B\\A\\D\\G\\K\\1c\",\"\\V\\E\\D\\1d\\P\\K\\H\\L\\E\\A\\L\\E\",\"\\1b\\B\\A\\D\\G\\K\\1c\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\H\\G\\A\\R\\H\\B\\E\\N\\1d\\E\\L\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\N\\B\\A\\1a\\F\\O\\D\\P\\1k\\F\\O\\1e\\A\\E\",\"\\K\\J\\D\\B\\B\\Y\\Q\\1d\\H\\E\\E\\H\\U\\P\\U\\H\\G\\A\\R\\H\\B\\E\\N\\1d\\E\\L\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\B\\F\\U\\R\\J\\A\",\"\\3a\\3v\\1d\\H\\1r\\2O\\A\\1a\\F\\O\\D\",\"\\W\\O\\F\\1a\\N\\F\\O\\Y\\Q\\3a\\3v\\1d\\H\\1r\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\1d\\P\\R\\D\\1e\\A\\Q\\N\\O\\D\\E\\D\\P\\1c\\G\\A\\1g\\Y\\Q\",\"\\Q\\N\\O\\D\\E\\D\\P\\1k\\F\\O\\E\\1c\\Y\\Q\\4j\\1J\\1J\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\1k\\F\\O\\1e\\A\\E\\P\\J\\H\\D\\O\\A\\O\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\K\\B\\E\\P\\B\\H\\K\\F\\D\\J\\P\\B\\1c\\D\\G\\A\\Q\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\K\\B\\E\\P\\K\\J\\H\\B\\A\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\E\\F\\U\\A\\B\\Q\\X\\W\\1b\\F\\X\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\O\\F\\1a\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\K\\B\\E\\P\\B\\1c\\D\\G\\A\\P\\1d\\E\\L\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\B\\1c\\D\\G\\A\\P\\D\\J\\E\\Q\\X\\W\\1b\\F\\X\\W\\1b\\B\\R\\D\\L\\X\",\"\\V\\K\\B\\E\\P\\B\\H\\K\\F\\D\\J\\P\\B\\1c\\D\\G\\A\",\"\\B\\G\\K\",\"\\V\\R\\H\\B\\E\\P\\1d\\H\\O\\1q\\N\\F\\U\\1e\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\K\\B\\E\\P\\B\\1c\\D\\G\\A\\P\\F\\L\\L\\A\\G\\Q\\X\",\"\\4l\\D\\1c\\H\\H\\U\\D\\F\\J\",\"\\A\\L\\1a\\A\\J\\H\\R\\A\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\K\\H\\U\\R\\H\\B\\A\\V\\U\\D\\F\\J\\V\\1q\\D\\1c\\H\\H\\V\\K\\H\\U\\1b\\1M\\1d\\H\\O\\1q\\Y\",\"\\7r\\H\\H\\1e\\J\\A\\N\\2m\\J\\Z\\B\",\"\\1c\\E\\E\\R\\B\\1x\\1b\\1b\\R\\J\\Z\\B\\V\\1e\\H\\H\\1e\\J\\A\\V\\K\\H\\U\\1b\\B\\1c\\D\\G\\A\\1M\\Z\\G\\J\\Y\",\"\\1z\\D\\U\\R\\1G\\E\\Y\",\"\\2p\\1k\\F\\E\\E\\A\\G\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\E\\1k\\F\\E\\E\\A\\G\\V\\K\\H\\U\\1b\\B\\1c\\D\\G\\A\\1M\\E\\A\\1r\\E\\Y\",\"\\1z\\D\\U\\R\\1G\\Z\\G\\J\\Y\",\"\\1z\\D\\U\\R\\1G\\1a\\F\\D\\Y\",\"\\3a\\D\\K\\A\\1d\\H\\H\\1o\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\1k\\1k\\1k\\V\\1g\\D\\K\\A\\1d\\H\\H\\1o\\V\\K\\H\\U\\1b\\B\\1c\\D\\G\\A\\G\\V\\R\\1c\\R\\1M\\Z\\Y\",\"\\3o\\F\\1e\\1e\",\"\\O\\F\\1e\\1e\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\O\\F\\1e\\1e\\V\\K\\H\\U\\1b\\B\\Z\\1d\\U\\F\\E\\1M\\Z\\G\\J\\Y\",\"\\1z\\D\\U\\R\\1G\\E\\F\\E\\J\\A\\Y\",\"\\2m\\F\\L\\E\\A\\G\\A\\B\\E\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\R\\F\\L\\E\\A\\G\\A\\B\\E\\V\\K\\H\\U\\1b\\R\\F\\L\\1b\\K\\G\\A\\D\\E\\A\\1b\\1d\\Z\\E\\E\\H\\L\\1b\\1M\\Z\\G\\J\\Y\",\"\\1z\\D\\U\\R\\1G\\U\\A\\O\\F\\D\\Y\",\"\\1z\\D\\U\\R\\1G\\O\\A\\B\\K\\G\\F\\R\\E\\F\\H\\L\\Y\",\"\\7r\\U\\D\\F\\J\",\"\\1c\\E\\E\\R\\B\\1x\\1b\\1b\\U\\D\\F\\J\\V\\1e\\H\\H\\1e\\J\\A\\V\\K\\H\\U\\1b\\U\\D\\F\\J\\1b\\Z\\1b\\1J\\1b\\1M\\1a\\F\\A\\1k\\Y\\K\\U\\1z\\D\\U\\R\\1G\\1g\\B\\Y\\1N\\1z\\D\\U\\R\\1G\\B\\Z\\Y\",\"\\1z\\D\\U\\R\\1G\\1d\\H\\O\\1q\\Y\",\"\\1z\\D\\U\\R\\1G\\Z\\F\\Y\\2a\\1z\\D\\U\\R\\1G\\E\\1g\\Y\\1N\",\"\\3o\\A\\J\\F\\K\\F\\H\\Z\\B\",\"\\O\\A\\J\\F\\K\\F\\H\\Z\\B\",\"\\1c\\E\\E\\R\\B\\1x\\1b\\1b\\O\\A\\J\\F\\K\\F\\H\\Z\\B\\V\\K\\H\\U\\1b\\R\\H\\B\\E\\1M\\Z\\G\\J\\Y\",\"\\2O\\E\\Z\\U\\1d\\J\\A\\4d\\R\\H\\L\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\1k\\1k\\1k\\V\\B\\E\\Z\\U\\1d\\J\\A\\Z\\R\\H\\L\\V\\K\\H\\U\\1b\\1d\\D\\O\\1e\\A\\1M\\Z\\G\\J\\Y\",\"\\6o\\D\\K\\1o\\A\\G\\2E\\A\\1k\\B\",\"\\1c\\D\\K\\1o\\A\\G\\P\\L\\A\\1k\\B\",\"\\1c\\E\\E\\R\\B\\1x\\1b\\1b\\L\\A\\1k\\B\\V\\1q\\K\\H\\U\\1d\\F\\L\\D\\E\\H\\G\\V\\K\\H\\U\\1b\\B\\Z\\1d\\U\\F\\E\\J\\F\\L\\1o\\1M\\Z\\Y\",\"\\2m\\G\\F\\L\\E\\3a\\G\\F\\A\\L\\O\\J\\1q\",\"\\R\\G\\F\\L\\E\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\1k\\1k\\1k\\V\\R\\G\\F\\L\\E\\1g\\G\\F\\A\\L\\O\\J\\1q\\V\\K\\H\\U\\1b\\R\\G\\F\\L\\E\\1M\\Z\\G\\J\\Y\",\"\\2p\\Z\\U\\1d\\J\\G\",\"\\E\\Z\\U\\1d\\J\\G\",\"\\1c\\E\\E\\R\\B\\1x\\1b\\1b\\1k\\1k\\1k\\V\\E\\Z\\U\\1d\\J\\G\\V\\K\\H\\U\\1b\\B\\1c\\D\\G\\A\\1M\\1a\\Y\\2c\\1z\\D\\U\\R\\1G\\Z\\Y\",\"\\4W\\A\\O\\O\\F\\E\",\"\\G\\A\\O\\O\\F\\E\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\1k\\1k\\1k\\V\\G\\A\\O\\O\\F\\E\\V\\K\\H\\U\\1b\\B\\Z\\1d\\U\\F\\E\\1M\\Z\\G\\J\\Y\",\"\\ci\\1o\\H\\L\\E\\D\\1o\\E\\A\",\"\\1a\\1o\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\1a\\1o\\V\\K\\H\\U\\1b\\B\\1c\\D\\G\\A\\V\\R\\1c\\R\\1M\\Z\\G\\J\\Y\",\"\\3p\\F\\L\\1o\\A\\O\\F\\L\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\1k\\1k\\1k\\V\\J\\F\\L\\1o\\A\\O\\F\\L\\V\\K\\H\\U\\1b\\B\\1c\\D\\G\\A\\1S\\G\\E\\F\\K\\J\\A\\1M\\U\\F\\L\\F\\Y\\E\\G\\Z\\A\\1z\\D\\U\\R\\1G\\Z\\G\\J\\Y\",\"\\6w\\1c\\D\\E\\B\\D\\R\\R\",\"\\1k\\1c\\D\\E\\B\\D\\R\\R\",\"\\1k\\1c\\D\\E\\B\\D\\R\\R\\1x\\1b\\1b\\B\\A\\L\\O\\1M\\E\\A\\1r\\E\\Y\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\K\\B\\E\\P\\B\\1c\\D\\G\\A\\P\\F\\E\\A\\U\\Q\\X\\W\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\K\\B\\E\\P\\B\\1c\\D\\G\\A\\N\\K\\B\\E\\P\",\"\\Q\\N\\E\\D\\G\\1e\\A\\E\\Y\\Q\\1P\\1d\\J\\D\\L\\1o\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\",\"\\Q\\X\\W\\1b\\F\\X\\W\\B\\R\\D\\L\\X\",\"\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\",\"\\V\\F\\L\\L\\A\\G\\1k\\G\\D\\R\",\"\\V\\1k\\G\\D\\R\\P\\F\\L\\L\\A\\G\",\"\\D\\1d\\B\\H\\J\\Z\\E\\A\",\"\\B\\F\\O\\A\\P\\1g\\F\\1r\\A\\O\",\"\\D\\Z\\E\\H\",\"\\V\\R\\H\\B\\E\\P\\1d\\H\\O\\1q\\1X\\R\\V\\K\\H\\U\\U\\A\\L\\E\\P\\K\\H\\L\\E\\A\\L\\E\\1X\\V\\6o\\2p\\2k\\3p\\N\\V\\1k\\F\\O\\1e\\A\\E\\P\\K\\H\\L\\E\\A\\L\\E\",\"\\F\\K\\H\\L\",\"\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\B\\1c\\G\\E\\P\\F\\K\\H\\L\\N\",\"\\1g\\D\\P\",\"\\2p\\D\\1d\",\"\\3o\\H\\L\\E\\N\\6o\\D\\1a\\A\\N\\D\\L\\1q\\N\\E\\A\\1r\\E\\N\\K\\H\\L\\E\\A\\L\\E\",\"\\V\\B\\1c\\G\\E\\P\\K\\H\\L\\E\\A\\L\\E\",\"\\V\\B\\1c\\G\\E\\P\\E\\D\\1d\\1X\\V\\B\\1c\\G\\E\\P\\1a\\E\\D\\1d\",\"\\W\\1c\\2c\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\K\\G\\O\\P\\E\\H\\1e\\1e\\J\\A\\Q\\X\",\"\\1S\\K\\K\\H\\G\\O\\F\\H\\L\\N\\2p\\F\\E\\J\\A\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\L\\K\\1c\\H\\G\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\R\\J\\Z\\B\\Q\\X\\W\\1b\\F\\X\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\1c\\2c\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\K\\G\\O\\P\\K\\H\\L\\E\\A\\L\\E\\Q\\X\",\"\\2k\\1q\\N\\D\\K\\K\\H\\G\\O\\F\\H\\L\",\"\\V\\B\\1c\\G\\E\\P\\F\\E\\A\\U\",\"\\K\\Z\\G\\G\\A\\L\\E\",\"\\V\\D\\K\\G\\O\\P\\E\\H\\1e\\1e\\J\\A\",\"\\V\\D\\K\\G\\O\\P\\K\\H\\L\\E\\A\\L\\E\",\"\\V\\B\\1c\\G\\E\\P\\D\\K\\K\\H\\G\\O\\F\\H\\L\",\"\\1g\\D\\B\\E\",\"\\B\\1c\\H\\1k\\A\\O\",\"\\V\\D\\K\\G\\O\\P\\K\\H\\L\\E\\A\\L\\E\\1x\\1a\\F\\B\\F\\1d\\J\\A\",\"\\1c\\2c\\V\\D\\K\\G\\O\\P\\E\\H\\1e\\1e\\J\\A\",\"\\V\\B\\1c\\G\\E\\P\\D\\K\\K\\H\\G\\O\\F\\H\\L\\N\\V\\D\\K\\G\\O\\P\\E\\H\\1e\\1e\\J\\A\",\"\\K\\H\\J\\H\\G\",\"\\1g\\A\\D\\E\\Z\\G\\A\\O\",\"\\1c\\A\\F\\1e\\1c\\E\",\"\\1a\\F\\B\\Z\\D\\J\",\"\\K\\H\\U\\U\\A\\L\\E\\B\",\"\\Z\\B\\A\\G\",\"\\R\\J\\D\\1q\\J\\F\\B\\E\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\F\\L\\J\\F\\L\\A\\B\\E\\1q\\J\\A\\N\\1g\\G\\D\\U\\A\\P\\B\\1c\\G\\E\\P\\B\\H\\Z\\L\\O\\K\\J\\H\\Z\\O\",\"\\N\\R\\1g\\A\\D\\E\\Z\\G\\A\\O\",\"\\Q\\X\\W\\F\\1g\\G\\D\\U\\A\\N\\1k\\F\\O\\E\\1c\\Y\\Q\",\"\\1N\\1J\\1J\\5U\",\"\\Q\\N\\1c\\A\\F\\1e\\1c\\E\\Y\\Q\",\"\\1N\\2c\\1J\",\"\\Q\\N\\B\\K\\G\\H\\J\\J\\F\\L\\1e\\Y\\Q\\L\\H\\Q\\N\\1g\\G\\D\\U\\A\\1d\\H\\G\\O\\A\\G\\Y\\Q\\L\\H\\Q\\N\\B\\G\\K\\Y\\Q\\1c\\E\\E\\R\\B\\1x\\1b\\1b\\1k\\V\\B\\H\\Z\\L\\O\\K\\J\\H\\Z\\O\\V\\K\\H\\U\\1b\\R\\J\\D\\1q\\A\\G\\1b\\1M\\Z\\G\\J\\Y\\1c\\E\\E\\R\\B\\5U\\2c\\1S\\1b\\1b\\D\\R\\F\\V\\B\\H\\Z\\L\\O\\K\\J\\H\\Z\\O\\V\\K\\H\\U\\1b\",\"\\E\\G\\D\\K\\1o\\B\",\"\\Z\\B\\A\\G\\B\",\"\\1r\\1r\\1r\\1r\\1r\\1r\\1r\",\"\\1z\\D\\U\\R\\1G\\K\\H\\J\\H\\G\\Y\",\"\\1g\\1g\\4j\\4j\\1J\\1J\",\"\\1z\\D\\U\\R\\1G\\D\\Z\\E\\H\\1P\\R\\J\\D\\1q\\Y\",\"\\1g\\D\\J\\B\\A\",\"\\1z\\D\\U\\R\\1G\\1c\\F\\O\\A\\1P\\G\\A\\J\\D\\E\\A\\O\\Y\\1g\\D\\J\\B\\A\\1z\\D\\U\\R\\1G\\B\\1c\\H\\1k\\1P\\K\\H\\U\\U\\A\\L\\E\\B\\Y\",\"\\1z\\D\\U\\R\\1G\\B\\1c\\H\\1k\\1P\\Z\\B\\A\\G\\Y\",\"\\E\\G\\Z\\A\",\"\\1z\\D\\U\\R\\1G\\B\\1c\\H\\1k\\1P\\G\\A\\R\\H\\B\\E\\B\\Y\\1g\\D\\J\\B\\A\\1z\\D\\U\\R\\1G\\1a\\F\\B\\Z\\D\\J\\Y\",\"\\Q\\X\\W\\1b\\F\\1g\\G\\D\\U\\A\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\B\\1c\\G\\E\\P\\B\\H\\Z\\L\\O\\K\\J\\H\\Z\\O\",\"\\1c\\F\\1e\\1c\\J\\F\\1e\\1c\\E\",\"\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\",\"\\F\\L\\1g\\H\",\"\\J\\H\\1e\\H\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\F\\L\\J\\F\\L\\A\\B\\E\\1q\\J\\A\\N\\1g\\G\\D\\U\\A\\P\\B\\1c\\G\\E\\P\\O\\D\\F\\J\\1q\\U\\H\\E\\F\\H\\L\",\"\\Q\\X\\W\\F\\1g\\G\\D\\U\\A\\N\\1g\\G\\D\\U\\A\\1d\\H\\G\\O\\A\\G\\Y\\Q\\1J\\Q\\N\\1k\\F\\O\\E\\1c\\Y\\Q\",\"\\2a\\3g\\1J\",\"\\Q\\N\\B\\G\\K\\Y\\Q\\1c\\E\\E\\R\\1x\\1b\\1b\\1k\\1k\\1k\\V\\O\\D\\F\\J\\1q\\U\\H\\E\\F\\H\\L\\V\\K\\H\\U\\1b\\A\\U\\1d\\A\\O\\1b\\1a\\F\\O\\A\\H\\1b\",\"\\1r\\1N\\2a\\1o\\4j\\2w\\2a\",\"\\1M\\J\\H\\1e\\H\\Y\",\"\\1N\",\"\\1z\\F\\L\\1g\\H\\Y\",\"\\1z\\1c\\F\\1e\\1c\\J\\F\\1e\\1c\\E\\Y\",\"\\2a\\6F\\1d\\3g\\1g\\1g\",\"\\1z\\1g\\H\\G\\A\\1e\\G\\H\\Z\\L\\O\\Y\",\"\\1g\\1g\\1g\\1g\\1g\\1g\",\"\\1z\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\Y\",\"\\1J\\1J\\1J\\1J\\1J\\1J\",\"\\Q\\N\\D\\J\\J\\H\\1k\\1g\\Z\\J\\J\\B\\K\\G\\A\\A\\L\\X\\W\\1b\\F\\1g\\G\\D\\U\\A\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\B\\1c\\G\\E\\P\\O\\D\\F\\J\\1q\\U\\H\\E\\F\\H\\L\",\"\\K\\H\\L\\E\\G\\H\\J\",\"\\G\\A\\J\\D\\E\\A\\O\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\F\\L\\J\\F\\L\\A\\B\\E\\1q\\J\\A\\N\\1g\\G\\D\\U\\A\\P\\B\\1c\\G\\E\\P\\1q\\H\\Z\\E\\Z\\1d\\A\",\"\\2w\\1J\\1J\",\"\\Q\\N\\B\\G\\K\\Y\\Q\\1c\\E\\E\\R\\B\\1x\\1b\\1b\\1k\\1k\\1k\\V\\1q\\H\\Z\\E\\Z\\1d\\A\\V\\K\\H\\U\\1b\\A\\U\\1d\\A\\O\\1b\",\"\\6F\\Z\\D\\1P\\2w\\D\\1T\\R\\2m\\4j\\5T\",\"\\1M\\J\\F\\B\\E\\Y\",\"\\1z\\D\\U\\R\\1G\\G\\A\\J\\Y\",\"\\1z\\D\\U\\R\\1G\\K\\H\\L\\E\\G\\H\\J\\B\\Y\",\"\\1z\\D\\U\\R\\1G\\B\\1c\\H\\1k\\F\\L\\1g\\H\\Y\",\"\\Q\\N\\1g\\G\\D\\U\\A\\1d\\H\\G\\O\\A\\G\\Y\\Q\\1J\\Q\\N\\D\\J\\J\\H\\1k\\1g\\Z\\J\\J\\B\\K\\G\\A\\A\\L\\X\\W\\1b\\F\\1g\\G\\D\\U\\A\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\B\\1c\\G\\E\\P\\1q\\H\\Z\\E\\Z\\1d\\A\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\F\\L\\J\\F\\L\\A\\B\\E\\1q\\J\\A\\N\\1g\\G\\D\\U\\A\\P\\B\\1c\\G\\E\\P\\U\\D\\R\",\"\\Q\\N\\B\\G\\K\\Y\\Q\\1c\\E\\E\\R\\B\\1x\\1b\\1b\\1k\\1k\\1k\\V\\1e\\H\\H\\1e\\J\\A\\V\\K\\H\\U\\1b\\U\\D\\R\\B\\1b\\A\\U\\1d\\A\\O\\1M\\R\\1d\\Y\",\"\\Q\\N\\1g\\G\\D\\U\\A\\1d\\H\\G\\O\\A\\G\\Y\\Q\\1J\\Q\\X\\W\\1b\\F\\1g\\G\\D\\U\\A\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\B\\1c\\G\\E\\P\\U\\D\\R\",\"\\B\\1c\\G\\E\\P\\U\\A\\B\\B\\D\\1e\\A\",\"\\V\\B\\1c\\G\\E\\P\\D\\J\\A\\G\\E\\1X\\N\\V\\B\\1c\\G\\E\\P\\1k\\D\\G\\L\\F\\L\\1e\\1X\\N\\V\\B\\1c\\G\\E\\P\\Z\\R\\O\\D\\E\\A\\1X\\N\\V\\B\\1c\\G\\E\\P\\B\\Z\\K\\K\\A\\B\\B\\1X\\N\\V\\B\\1c\\G\\E\\P\\F\\L\\1g\\H\\1X\\N\\V\\B\\1c\\G\\E\\P\\A\\G\\G\\H\\G\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\1c\\A\\D\\O\\J\\F\\L\\A\\Q\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\A\\B\\B\\D\\1e\\A\\P\\1k\\G\\D\\R\\R\\A\\G\\Q\\X\",\"\\V\\B\\1c\\G\\E\\P\\U\\A\\B\\B\\D\\1e\\A\",\"\\Z\\G\\J\",\"\\G\\A\\J\",\"\\1c\\G\\A\\1g\\Y\\Q\",\"\\W\\1d\\G\\1b\\X\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\G\\E\\2Q\\U\\1e\\4d\\G\\J\\N\",\"\\N\\G\\A\\J\\Y\\Q\",\"\\W\\F\\U\\1e\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\G\\E\\2Q\\U\\1e\",\"\\Q\\N\\1k\\F\\O\\E\\1c\\Y\\Q\",\"\\1c\\E\\E\\R\\1x\\1b\\1b\\1N\\V\\1d\\R\\V\\1d\\J\\H\\1e\\B\\R\\H\\E\\V\\K\\H\\U\\1b\\P\\1c\\E\\7r\\3g\\1a\\1q\\6F\\1a\\2Q\\1S\\1S\\1b\\2p\\R\\1J\\4Y\\G\\2k\\4d\\O\\H\\6w\\2Q\\1b\\1S\\1S\\1S\\1S\\1S\\1S\\1S\\1S\\3v\\1S\\4d\\1b\\A\\3g\\bV\\1o\\3a\\E\\3D\\G\\2j\\B\\4d\\1b\\B\\3g\\2a\\P\\K\\1b\\1e\\G\\A\\1q\\V\\1e\\F\\1g\",\"\\Q\\1b\\X\",\"\\V\\B\\1c\\G\\E\\P\\F\\U\\1e\",\"\\1d\\G\",\"\\V\\B\\1c\\G\\E\\P\\1e\\D\\J\\J\\A\\G\\1q\\1X\\V\\B\\1c\\G\\E\\P\\1d\\1e\\D\\J\\J\\A\\G\\1q\",\"\\E\\1q\\R\\A\",\"\\W\\R\\G\\A\\N\\O\\D\\E\\D\\P\\K\\H\\O\\A\\E\\1q\\R\\A\\Y\\Q\",\"\\6o\\2p\\2k\\3p\",\"\\1S\\O\\O\\N\\B\\H\\U\\A\\N\\K\\H\\O\\A\\N\\1c\\A\\G\\A\",\"\\W\\1b\\R\\G\\A\\X\",\"\\V\\B\\1c\\G\\E\\P\\K\\H\\O\\A\",\"\\R\\G\\A\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\J\\F\\L\\A\\P\\L\\Z\\U\\1d\\A\\G\\Q\\X\\W\\1b\\B\\R\\D\\L\\X\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\K\\J\\Q\\X\\W\\1b\\B\\R\\D\\L\\X\",\"\\B\\R\\D\\L\",\"\\W\\B\\R\\D\\L\\X\",\"\\1L\\K\\H\\L\\E\\D\\K\\E\",\"\\V\\B\\1c\\G\\E\\P\\K\\H\\L\\E\\D\\K\\E\",\"\\1L\",\"\\Q\\N\\K\\J\\D\\B\\B\\Y\\Q\\1T\\O\\B\\1c\\G\\E\\P\\E\\H\\H\\J\\E\\F\\R\\Q\\X\",\"\\2Q\\L\\B\\A\\G\\E\\N\\3p\\F\\L\\1o\\N\\2p\\F\\E\\J\\A\",\"\\2Q\\L\\B\\A\\G\\E\\N\\2p\\H\\H\\J\\E\\F\\R\\N\\2p\\A\\1r\\E\",\"\\V\\B\\1c\\G\\E\\P\\E\\H\\H\\J\\E\\F\\R\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\G\\E\\P\\B\\J\\F\\O\\A\\P\\F\\E\\A\\U\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\G\\E\\P\\F\\L\\L\\A\\G\\Q\\X\\W\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\G\\E\\P\\H\\1k\\J\\P\\F\\U\\1e\\Q\\N\\B\\E\\1q\\J\\A\\Y\\Q\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\1x\\N\\Z\\G\\J\\1O\",\"\\1K\\N\\L\\H\\P\\G\\A\\R\\A\\D\\E\\N\\K\\A\\L\\E\\A\\G\\N\\K\\A\\L\\E\\A\\G\\1G\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\P\\B\\F\\2T\\A\\1x\\N\\K\\H\\1a\\A\\G\\1G\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\G\\E\\P\\B\\Z\\U\\U\\D\\G\\1q\\Q\\X\",\"\\W\\1c\\2c\\X\\W\",\"\\X\\W\\1b\\1c\\2c\\X\",\"\\W\\R\\X\",\"\\V\\B\\1c\\G\\E\\P\\B\\J\\F\\O\\A\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\G\\E\\P\\K\\D\\G\\H\\Z\\B\\A\\J\\P\\F\\E\\A\\U\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\1c\\G\\E\\P\\F\\L\\L\\A\\G\\Q\\X\\W\",\"\\V\\B\\1c\\G\\E\\P\\K\\D\\G\\H\\Z\\B\\A\\J\",\"\\G\\A\\1a\\F\\A\\1k\\P\\1a\\D\\J\\Z\\A\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\P\\F\\E\\A\\U\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\P\\O\\A\\B\\K\\Q\\X\",\"\\2E\\H\\N\\3o\\A\\E\\D\\F\\J\",\"\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\O\\F\\1a\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\P\\1a\\D\\J\\Z\\A\\P\\H\\Z\\E\\A\\G\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\P\\1a\\D\\J\\Z\\A\\Q\\N\\O\\D\\E\\D\\P\\1a\\D\\J\\Z\\A\\Y\\Q\",\"\\Q\\N\\B\\E\\1q\\J\\A\\Y\\Q\\1k\\F\\O\\E\\1c\\1x\",\"\\5U\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\P\\B\\Z\\U\\U\\D\\G\\1q\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\P\\O\\A\\B\\K\\P\\R\\J\\D\\K\\A\\Q\\X\\W\\1c\\2w\\X\",\"\\2E\\H\\N\\2p\\F\\E\\J\\A\",\"\\W\\1b\\1c\\2w\\X\\W\\B\\R\\D\\L\\X\",\"\\2E\\H\\N\\3o\\A\\B\\K\\G\\F\\R\\E\\F\\H\\L\",\"\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\O\\F\\1a\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\P\\H\\1a\\A\\G\\D\\J\\J\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\H\\1a\\A\\G\\D\\J\\J\\P\\F\\L\\L\\A\\G\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\P\\K\\F\\G\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\J\\F\\K\\A\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\A\\E\\A\\G\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\1a\\P\\B\\K\\H\\G\\A\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\B\\R\\D\\L\\X\",\"\\2E\\H\\N\\3p\\D\\1d\\A\\J\",\"\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\G\\A\\1a\\P\\1a\\D\\J\\Z\\A\",\"\\O\\D\\E\\D\\P\\1a\\D\\J\\Z\\A\",\"\\V\\G\\A\\1a\\P\\B\\K\\H\\G\\A\",\"\\V\\U\\A\\E\\A\\G\",\"\\V\\B\\1c\\G\\E\\P\\G\\A\\1a\\F\\A\\1k\",\"\\V\\1k\\F\\O\\1e\\A\\E\\P\\K\\H\\L\\E\\A\\L\\E\",\"\\2u\\F\\O\\Y\",\"\\B\\E\\G\\F\\L\\1e\",\"\\E\\G\\D\\L\\B\\F\\E\\F\\H\\L\\F\\L\\1e\",\"\\1N\\B\\N\\A\\D\\B\\A\\P\\F\\L\\P\\H\\Z\\E\",\"\\D\\2u\\1c\\G\\A\\1g\\6v\\Y\\1L\\2U\\1x\\L\\H\\E\\1O\\2u\\1c\\G\\A\\1g\\Y\\1L\\2U\\1K\",\"\\E\\G\\D\\L\\B\\F\\E\\F\\H\\L\\A\\L\\O\\N\\1k\\A\\1d\\1o\\F\\E\\2p\\G\\D\\L\\B\\F\\E\\F\\H\\L\\3D\\L\\O\\N\\U\\B\\2p\\G\\D\\L\\B\\F\\E\\F\\H\\L\\3D\\L\\O\\N\\H\\2p\\G\\D\\L\\B\\F\\E\\F\\H\\L\\3D\\L\\O\",\"\\1L\\1k\\A\\1d\\R\\D\\1e\\A\",\"\\B\\E\\D\\E\\F\\K\\1P\\R\\D\\1e\\A\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\1A\\K\\H\\U\\U\\A\\L\\E\\B\\P\\E\\D\\1d\\B\\P\\1c\\A\\D\\O\\A\\G\\1A\\1b\\X\",\"\\V\\K\\H\\U\\U\\A\\L\\E\\B\\P\\E\\D\\1d\\B\\V\\B\\F\\U\\R\\J\\A\\2p\\D\\1d\\N\\V\\E\\D\\1d\\P\\1k\\G\\D\\R\\R\\A\\G\",\"\\W\\1c\\2c\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\E\\F\\E\\J\\A\\P\\1k\\G\\D\\R\\Q\\X\",\"\\1L\\K\\H\\U\\U\\A\\L\\E\\P\\R\\H\\B\\E\\P\\U\\A\\B\\B\\D\\1e\\A\",\"\\W\\1b\\B\\R\\D\\L\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\1c\\J\\F\\L\\A\\Q\\X\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\1c\\2c\\X\",\"\\V\\K\\H\\U\\U\\A\\L\\E\\B\\P\\E\\D\\1d\\B\\P\\1c\\A\\D\\O\\A\\G\",\"\\V\\K\\H\\U\\U\\A\\L\\E\\B\\P\\E\\D\\1d\\B\\N\\V\\E\\D\\1d\\P\\1k\\G\\D\\R\\R\\A\\G\\N\\J\\F\",\"\\V\\K\\H\\U\\U\\A\\L\\E\\B\\P\\E\\D\\1d\\B\\N\\V\\E\\D\\1d\\P\\1k\\G\\D\\R\\R\\A\\G\",\"\\V\\R\\H\\B\\E\\P\\1d\\H\\O\\1q\\N\\B\\E\\G\\F\\1o\\A\",\"\\V\\R\\H\\B\\E\\P\\E\\F\\E\\J\\A\",\"\\V\\R\\H\\B\\E\\P\\1d\\H\\O\\1q\\N\\1c\\2a\\N\\B\\E\\G\\F\\1o\\A\",\"\\V\\R\\H\\B\\E\\P\\1d\\H\\O\\1q\\N\\1c\\2c\\N\\B\\E\\G\\F\\1o\\A\",\"\\V\\R\\H\\B\\E\\P\\B\\Z\\1d\\E\\F\\E\\J\\A\",\"\\V\\R\\G\\H\\1g\\F\\J\\A\\P\\B\\A\\K\\N\\V\\1k\\F\\O\\1e\\A\\E\",\"\\N\\F\\K\\H\\L\\D\\Z\\E\\1c\\H\\G\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\F\\K\\H\\L\\P\",\"\\Q\\1b\\X\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\O\\F\\1a\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\Z\\E\\1c\\H\\G\\P\\F\\U\\1e\\Q\\X\\W\\B\\R\\D\\L\\N\\X\\W\\F\\U\\1e\\N\\B\\G\\K\\Y\\Q\",\"\\V\\F\\K\\H\\L\\D\\Z\\E\\1c\\H\\G\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\1A\\D\\Z\\E\\1c\\H\\G\\F\\K\\H\\L\\3v\\H\\1r\\1A\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\R\\G\\H\\1g\\F\\J\\A\\P\\B\\A\\K\\N\\V\\1k\\F\\O\\1e\\A\\E\\P\\K\\H\\L\\E\\A\\L\\E\",\"\\V\\F\\E\\A\\U\\P\\E\\H\\R\\U\\A\\E\\D\\N\\V\\1g\\L\",\"\\2O\\D\\E\\D\\L\\1o\\N\\2k\\4Y\\4W\",\"\\V\\D\\Z\\E\\1c\\H\\G\\P\\F\\U\\1e\",\"\\V\\D\\Z\\E\\1c\\H\\G\\F\\K\\H\\L\\3v\\H\\1r\",\"\\V\\D\\Z\\E\\1c\\H\\G\\2m\\G\\H\\1g\\F\\J\\A\\N\\R\",\"\\V\\D\\Z\\E\\1c\\H\\G\\2O\\H\\K\\F\\D\\J\",\"\\V\\F\\E\\A\\U\\N\\V\\R\\H\\B\\E\\N\\6v\\1X\\N\\V\\B\\E\\D\\E\\F\\K\\1P\\R\\D\\1e\\A\\N\\V\\R\\H\\B\\E\\N\\6v\",\"\\V\\D\\O\\B\\F\\L\\B\\F\\O\\A\",\"\\V\\B\\F\\O\\A\\1d\\D\\G\\P\\J\\A\\1g\\E\",\"\\J\\A\\1g\\E\\P\\R\\H\\B\\E\",\"\\1d\\H\\O\\1q\",\"\\G\\F\\1e\\1c\\E\\P\\R\\H\\B\\E\",\"\\J\\A\\1g\\E\\P\\B\\F\\O\\A\",\"\\G\\F\\1e\\1c\\E\\P\\B\\F\\O\\A\",\"\\1g\\Z\\J\\J\\P\\R\\H\\B\\E\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\O\\B\\F\\L\\B\\F\\O\\A\\P\\F\\E\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\D\\O\\B\\F\\L\\B\\F\\O\\A\\P\\F\\E\",\"\\V\\D\\O\\B\\1d\\A\\J\\H\\1k\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\O\\B\\E\\F\\E\\J\\A\",\"\\N\\1c\\1a\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\",\"\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\O\\B\\R\\J\\E\\H\\R\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\E\\H\\R\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\\Q\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\E\\H\\R\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\\R\\J\\N\\B\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\D\\O\\B\\R\\J\\E\\H\\R\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\O\\A\\1r\\K\\A\\G\\R\\E\\Q\\X\",\"\\V\\E\\H\\R\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\",\"\\V\\E\\H\\R\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\\R\\J\",\"\\V\\O\\A\\1r\\K\\A\\G\\R\\E\",\"\\G\\D\\L\\O\\H\\U\",\"\\V\\D\\O\\B\\A\\L\\O\\R\\H\\B\\E\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\O\\B\\1d\\H\\E\\E\\H\\U\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\1d\\H\\E\\E\\H\\U\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\\N\\B\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\O\\B\\R\\J\\1d\\H\\E\\E\\H\\U\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\1d\\H\\E\\E\\H\\U\\P\\F\\L\\1g\\H\\F\\E\\A\\U\",\"\\V\\D\\O\\B\\R\\J\\1d\\H\\E\\E\\H\\U\",\"\\V\\1d\\H\\E\\E\\H\\U\\1d\\G\\A\\D\\1o\\J\\F\\L\\A\",\"\\W\\F\\L\\R\\Z\\E\\N\\E\\1q\\R\\A\\Y\\Q\\1c\\F\\O\\O\\A\\L\\Q\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\A\\1a\\F\\O\\D\\P\\R\\D\\1e\\A\\Q\\X\\W\\1b\\F\\L\\R\\Z\\E\\X\\W\\F\\L\\R\\Z\\E\\N\\E\\1q\\R\\A\\Y\\Q\\1c\\F\\O\\O\\A\\L\\Q\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\A\\1a\\F\\O\\D\\P\\R\\A\\G\\P\\R\\D\\1e\\A\\Q\\X\\W\\1b\\F\\L\\R\\Z\\E\\X\",\"\\2u\\J\\L\\E\\2U\",\"\\2u\\1g\\L\\E\\2U\",\"\\W\\1b\\O\\F\\1a\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\R\\D\\1e\\A\\P\\F\\E\\A\\U\\Q\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\R\\D\\1e\\A\\P\\F\\E\\A\\U\\Q\\X\",\"\\V\\R\\D\\1e\\A\\P\\R\\J\\D\\K\\A\",\"\\V\\B\\A\\1a\\F\\O\\D\\P\\R\\D\\1e\\A\",\"\\V\\B\\A\\1a\\F\\O\\D\\P\\R\\A\\G\\P\\R\\D\\1e\\A\",\"\\W\\D\\N\\K\\J\\D\\B\\B\\Y\\Q\\R\\G\\A\\1a\\F\\H\\Z\\B\\1P\\J\\F\\L\\1o\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\K\\1c\\A\\1a\\G\\H\\L\\P\\J\\A\\1g\\E\\Q\\X\\W\\1b\\F\\X\\W\\1b\\D\\X\",\"\\W\\D\\N\\K\\J\\D\\B\\B\\Y\\Q\\R\\D\\1e\\A\\1P\\J\\F\\L\\1o\\Q\\N\\O\\D\\E\\D\\P\\E\\F\\E\\J\\A\\Y\\Q\",\"\\Q\\N\\J\\H\\L\\1e\\O\\A\\B\\K\\Y\\Q\",\"\\W\\D\\N\\K\\J\\D\\B\\B\\Y\\Q\\L\\A\\1r\\E\\1P\\J\\F\\L\\1o\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\K\\1c\\A\\1a\\G\\H\\L\\P\\G\\F\\1e\\1c\\E\\Q\\X\\W\\1b\\F\\X\\W\\1b\\D\\X\\W\\D\\N\\K\\J\\D\\B\\B\\Y\\Q\\D\\J\\J\\1P\\J\\F\\L\\1o\\Q\\X\\1a\\F\\A\\1k\\N\\D\\J\\J\\W\\1b\\D\\X\",\"\\D\\K\\E\\F\\1a\\A\\1P\\R\\D\\1e\\A\",\"\\V\\R\\D\\1e\\A\\1P\\J\\F\\L\\1o\\1x\\1g\\F\\G\\B\\E\",\"\\L\\H\\L\\A\",\"\\V\\D\\K\\E\\F\\1a\\A\\1P\\R\\D\\1e\\A\",\"\\V\\R\\D\\1e\\A\\1P\\J\\F\\L\\1o\\2u\\J\\H\\L\\1e\\O\\A\\B\\K\\Y\",\"\\V\\R\\D\\1e\\A\\1P\\J\\F\\L\\1o\",\"\\V\\R\\G\\A\\1a\\F\\H\\Z\\B\\1P\\J\\F\\L\\1o\",\"\\V\\L\\A\\1r\\E\\1P\\J\\F\\L\\1o\",\"\\V\\D\\J\\J\\1P\\J\\F\\L\\1o\",\"\\1L\\R\\H\\B\\E\\P\\Z\\G\\J\",\"\\Z\\L\\J\\H\\K\\1o\\A\\O\",\"\\Z\\L\\J\\H\\K\\1o\\A\\O\\P\",\"\\W\\1b\\J\\H\\K\\1o\\E\\D\\1e\\X\",\"\\W\\J\\H\\K\\1o\\E\\D\\1e\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\J\\H\\K\\1o\\A\\O\\P\\K\\H\\L\\E\\A\\L\\E\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\F\\L\\L\\A\\G\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\K\\H\\J\\H\\G\\N\\1g\\D\\N\\1g\\D\\P\\J\\H\\K\\1o\\Q\\X\\W\\1b\\F\\X\\W\\1c\\2a\\N\\K\\J\\D\\B\\B\\Y\\Q\\J\\H\\K\\1o\\A\\O\\P\\K\\H\\L\\E\\A\\L\\E\\P\\E\\F\\E\\J\\A\\Q\\X\\2m\\4W\\3D\\2k\\2Q\\4d\\2k\\N\\4V\\4q\\2E\\2p\\3D\\2E\\2p\\W\\1b\\1c\\2a\\X\\W\\1c\\2c\\N\\K\\J\\D\\B\\B\\Y\\Q\\J\\H\\K\\1o\\A\\O\\P\\K\\H\\L\\E\\A\\L\\E\\P\\B\\Z\\1d\\P\\E\\F\\E\\J\\A\\Q\\X\\2m\\J\\A\\D\\B\\A\\N\\B\\1c\\D\\G\\A\\N\\E\\H\\N\\Z\\L\\J\\H\\K\\1o\\W\\1b\\1c\\2c\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\J\\H\\K\\1o\\A\\O\\P\\K\\H\\L\\E\\A\\L\\E\\P\\D\\K\\E\\F\\H\\L\\B\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\J\\H\\K\\1o\\A\\O\\P\\K\\H\\L\\E\\A\\L\\E\\P\\D\\K\\E\\F\\H\\L\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\1d\\P\\J\\F\\1o\\A\\Q\\N\\O\\D\\E\\D\\P\\1c\\G\\A\\1g\\Y\\Q\",\"\\Q\\N\\O\\D\\E\\D\\P\\J\\D\\1q\\H\\Z\\E\\Y\\Q\\1d\\Z\\E\\E\\H\\L\\Q\\N\\O\\D\\E\\D\\P\\D\\K\\E\\F\\H\\L\\Y\\Q\\J\\F\\1o\\A\\Q\\N\\O\\D\\E\\D\\P\\B\\1c\\H\\1k\\P\\1g\\D\\K\\A\\B\\Y\\Q\\1g\\D\\J\\B\\A\\Q\\N\\O\\D\\E\\D\\P\\B\\1c\\D\\G\\A\\Y\\Q\\1g\\D\\J\\B\\A\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\J\\H\\K\\1o\\A\\O\\P\\K\\H\\L\\E\\A\\L\\E\\P\\D\\K\\E\\F\\H\\L\\Q\\X\\W\\D\\N\\1c\\G\\A\\1g\\Y\\Q\\1c\\E\\E\\R\\B\\1x\\1b\\1b\\E\\1k\\F\\E\\E\\A\\G\\V\\K\\H\\U\\1b\\F\\L\\E\\A\\L\\E\\1b\\E\\1k\\A\\A\\E\\Q\\N\\K\\J\\D\\B\\B\\Y\\Q\\E\\1k\\F\\E\\E\\A\\G\\P\\B\\1c\\D\\G\\A\\P\\1d\\Z\\E\\E\\H\\L\\Q\\N\\O\\D\\E\\D\\P\\K\\H\\Z\\L\\E\\Y\\Q\\1a\\A\\G\\E\\F\\K\\D\\J\\Q\\N\\B\\E\\1q\\J\\A\\Y\\Q\\Q\\X\\2p\\1k\\A\\A\\E\\W\\1b\\D\\X\\W\\1b\\O\\F\\1a\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\K\\J\\A\\D\\G\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\J\\H\\K\\1o\\E\\D\\1e\",\"\\V\\F\\E\\A\\U\\P\\R\\H\\B\\E\\N\\V\\R\\H\\B\\E\\P\\1d\\H\\O\\1q\",\"\\V\\J\\H\\K\\1o\\A\\O\\P\\K\\H\\L\\E\\A\\L\\E\",\"\\V\\E\\1k\\F\\E\\E\\A\\G\\P\\B\\1c\\D\\G\\A\\P\\1d\\Z\\E\\E\\H\\L\",\"\\E\\1k\\F\\E\\E\\A\\G\\P\\1k\\1T\\B\",\"\\1c\\E\\E\\R\\B\\1x\\1b\\1b\\R\\J\\D\\E\\1g\\H\\G\\U\\V\\E\\1k\\F\\E\\E\\A\\G\\V\\K\\H\\U\\1b\\1k\\F\\O\\1e\\A\\E\\B\\V\\1T\\B\",\"\\E\\1k\\A\\A\\E\",\"\\V\\3a\\3v\\1d\\H\\1r\",\"\\V\\1g\\1d\\P\\J\\F\\1o\\A\",\"\\E\\D\\1d\\J\\A\",\"\\R\\1g\\A\\D\\E\\Z\\G\\A\\O\",\"\\1c\\F\\O\\A\",\"\\V\\E\\G\\P\\K\\D\\R\\E\\F\\H\\L\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\R\\K\\D\\R\\E\\F\\H\\L\\Q\\X\",\"\\V\\R\\1g\\A\\D\\E\\Z\\G\\A\\O\",\"\\V\\R\\H\\B\\E\\P\\1g\\A\\D\\E\\Z\\G\\A\\O\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\B\\J\\F\\O\\A\\P\\R\\1g\\A\\D\\E\\Z\\G\\A\\O\\Q\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\B\\J\\F\\O\\A\\P\\R\\1g\\A\\D\\E\\Z\\G\\A\\O\",\"\\1c\\D\\1a\\A\\P\\R\\1g\\A\\D\\E\\Z\\G\\A\\O\",\"\\V\\1e\\J\\R\\H\\B\\E\",\"\\V\\B\\A\\R\\D\\G\\D\\E\\H\\G\",\"\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\R\\K\\D\\R\\E\\F\\H\\L\\N\\D\\1d\\B\\H\\J\\Z\\E\\A\\Q\\X\",\"\\V\\R\\H\\B\\E\\P\\1g\\A\\D\\E\\Z\\G\\A\\O\\N\\D\",\"\\V\\R\\H\\B\\E\\P\\1g\\A\\D\\E\\Z\\G\\A\\O\\N\\X\\N\\D\",\"\\V\\R\\H\\B\\E\\P\\1g\\A\\D\\E\\Z\\G\\A\\O\\N\\F\\U\\1e\",\"\\V\\F\\E\\A\\U\\P\\B\\L\\F\\R\\R\\A\\E\",\"\\V\\K\\H\\L\\E\\D\\K\\E\\P\\B\\A\\K\",\"\\K\\H\\L\\E\\D\\K\\E\\P\\B\\1c\\H\\1k\",\"\\B\\1c\\H\\1k\\P\\R\\H\\R\\Z\\R\",\"\\V\\K\\H\\L\\E\\D\\K\\E\\P\\1d\\Z\\E\\E\\H\\L\",\"\\V\\K\\H\\L\\E\\D\\K\\E\\P\\K\\J\\H\\B\\A\",\"\\K\\B\\E\\P\\B\\1c\\D\\G\\A\\P\\B\\1c\\H\\1k\",\"\\K\\B\\E\\P\\B\\1c\\H\\1k\",\"\\V\\K\\B\\E\\P\\B\\1c\\D\\G\\A\\P\\1d\\E\\L\",\"\\V\\K\\B\\E\\P\\K\\J\\H\\B\\A\",\"\\V\\K\\H\\L\\E\\D\\K\\E\\P\\B\\A\\K\\1X\\V\\K\\H\\L\\E\\D\\K\\E\\P\\B\\A\\K\\N\\F\\L\\R\\Z\\E\\1X\\V\\K\\H\\L\\E\\D\\K\\E\\P\\B\\A\\K\\N\\E\\A\\1r\\E\\D\\G\\A\\D\\1X\\V\\K\\H\\L\\E\\D\\K\\E\\P\\B\\A\\K\\N\\1g\\H\\G\\U\\1X\\V\\K\\B\\E\\P\\B\\1c\\H\\1k\\1X\\V\\K\\B\\E\\P\\B\\1c\\H\\1k\\N\\O\\F\\1a\\1X\\V\\K\\B\\E\\P\\B\\1c\\H\\1k\\N\\D\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\B\\R\\H\\L\\B\\F\\1a\\A\\P\\U\\A\\L\\Z\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\B\\P\\U\\A\\L\\Z\\P\\D\\G\\A\\D\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\B\\U\\A\\L\\Z\\P\\F\\L\\L\\L\\A\\G\\Q\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\B\\P\\U\\A\\L\\Z\\P\\F\\L\\L\\A\\G\\Q\\X\\W\\Z\\J\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\B\\P\\U\\A\\L\\Z\\Q\\X\\W\\1b\\Z\\J\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\G\\A\\B\\P\\U\\A\\L\\Z\",\"\\V\\L\\D\\1a\\F\\N\\V\\U\\A\\L\\Z\",\"\\V\\G\\A\\B\\R\\H\\L\\B\\F\\1a\\A\\P\\U\\A\\L\\Z\",\"\\U\\A\\1e\\D\\P\\U\\A\\L\\Z\",\"\\1e\\G\\F\\R\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\A\\L\\Z\\P\\U\\H\\G\\A\\R\\H\\B\\E\",\"\\N\\G\\D\\L\\O\\H\\U\",\"\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\1b\\B\\A\\D\\G\\K\\1c\",\"\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\R\\J\\Z\\B\\Q\\X\\W\\1b\\F\\X\\W\\1b\",\"\\L\\H\\1d\\H\\G\\O\\A\\G\\N\\U\\G\\A\\K\\R\\N\\U\\1o\\1d\\J\\H\\K\\1o\",\"\\U\\K\\D\\G\\H\\Z\\B\\A\\J\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\H\\1k\\J\\P\\L\\D\\1a\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\D\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\A\\L\\Z\\P\\U\\H\\G\\A\\R\\H\\B\\E\",\"\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\R\\J\\Z\\B\\Q\\X\\W\\1b\\F\\X\\W\\1b\\D\\X\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\L\\H\\G\\U\\D\\J\\P\\E\\D\\1d\\Q\\X\",\"\\V\\L\\H\\G\\U\\D\\J\\P\\E\\D\\1d\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\A\\L\\Z\\P\\U\\H\\G\\A\\R\\H\\B\\E\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\1b\\B\\A\\D\\G\\K\\1c\\1b\\J\\D\\1d\\A\\J\\1b\",\"\\U\\E\\D\\1d\",\"\\U\\1d\\F\\1e\",\"\\U\\A\\L\\Z\\J\\F\\L\\1o\\B\",\"\\V\\J\\F\\L\\1o\\B\\P\\B\\Z\\1d\\U\\A\\L\\Z\\N\\V\\1k\\F\\O\\1e\\A\\E\",\"\\V\\J\\F\\L\\1o\\B\\P\\B\\Z\\1d\\U\\A\\L\\Z\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\J\\F\\L\\1o\\B\\P\\K\\H\\L\\E\\A\\L\\E\\Q\\X\\W\\1c\\2a\\X\",\"\\W\\1b\\1c\\2a\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\1k\\F\\O\\1e\\A\\E\\P\\K\\H\\L\\E\\A\\L\\E\\Q\\X\",\"\\V\\J\\F\\L\\1o\\B\\P\\K\\H\\L\\E\\A\\L\\E\",\"\\1e\\G\\F\\O\\R\\H\\B\\E\",\"\\W\\D\\N\\K\\J\\D\\B\\B\\Y\\Q\\1e\\G\\F\\O\\P\\1c\\2a\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\1b\\B\\A\\D\\G\\K\\1c\",\"\\Q\\X\\W\\1b\\D\\X\",\"\\1c\\2a\\N\\V\\E\\F\\E\\J\\A\\P\\1k\\G\\D\\R\",\"\\W\\D\\N\\K\\J\\D\\B\\B\\Y\\Q\\U\\H\\G\\A\\R\\H\\B\\E\\N\\1d\\E\\L\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\1b\\B\\A\\D\\G\\K\\1c\",\"\\J\\F\\V\\B\\Z\\1d\\U\\A\\L\\Z\",\"\\1x\\1c\\F\\O\\O\\A\\L\",\"\\V\\G\\A\\B\\P\\U\\A\\L\\Z\\N\\V\\B\\Z\\1d\\P\\F\\K\\H\\L\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\1d\\J\\H\\1e\\P\\R\\D\\1e\\A\\G\\P\\H\\J\\O\\A\\G\\P\\J\\F\\L\\1o\\P\\F\\E\\A\\U\\N\\H\\J\\O\\A\\G\\L\\A\\1k\\A\\G\\G\\F\\1e\\1c\\E\\Q\\N\\E\\F\\E\\J\\A\\Y\\Q\\4q\\J\\O\\A\\G\\N\\2m\\H\\B\\E\\N\\P\\N\\2u\\E\\F\\E\\J\\A\\2U\\N\\P\\N\\R\\H\\B\\E\\A\\O\\N\\H\\L\\N\\2u\\O\\D\\E\\A\\2U\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\2u\\Z\\G\\J\\2U\\Q\\X\\2u\\F\\U\\1e\\2U\\W\\B\\R\\D\\L\\X\",\"\\W\\1b\\B\\R\\D\\L\\X\\W\\O\\F\\1a\\X\\2u\\E\\F\\E\\J\\A\\2U\\W\\1b\\O\\F\\1a\\X\\W\\1b\",\"\\N\\K\\J\\D\\B\\B\\Y\\Q\\1d\\J\\H\\1e\\P\\R\\D\\1e\\A\\G\\P\\L\\A\\1k\\A\\G\\P\\J\\F\\L\\1o\\P\\F\\E\\A\\U\\N\\H\\J\\O\\A\\G\\L\\A\\1k\\A\\G\\J\\A\\1g\\E\\Q\\N\\E\\F\\E\\J\\A\\Y\\Q\\2E\\A\\1k\\A\\G\\N\\2m\\H\\B\\E\\N\\P\\N\\2u\\E\\F\\E\\J\\A\\2U\\N\\P\\N\\R\\H\\B\\E\\A\\O\\N\\H\\L\\N\\2u\\O\\D\\E\\A\\2U\\Q\\N\\1c\\G\\A\\1g\\Y\\Q\\2u\\Z\\G\\J\\2U\\Q\\X\\2u\\F\\U\\1e\\2U\\W\\B\\R\\D\\L\\X\",\"\\D\\V\\1d\\J\\H\\1e\\P\\R\\D\\1e\\A\\G\\P\\H\\J\\O\\A\\G\\P\\J\\F\\L\\1o\\P\\F\\E\\A\\U\",\"\\V\\R\\Z\\1d\\J\\F\\B\\1c\\A\\O\",\"\\O\\D\\E\\D\\P\\E\\G\\D\\L\\B\",\"\\1L\\1d\\H\\O\\1q\\P\\D\\G\\A\\D\\N\\6v\",\"\\B\\R\\D\\L\\V\\E\\G\\D\\L\\B\",\"\\B\\K\\G\\H\\J\\J\",\"\\V\\1c\\A\\D\\O\\A\\G\\P\\1k\\G\\D\\R\",\"\\B\\K\\G\\H\\J\\J\\A\\O\",\"\\V\\K\\H\\L\\E\\D\\F\\L\\A\\G\",\"\\B\\K\\G\\H\\J\\J\\P\\Z\\R\",\"\\1g\\F\\1r\\U\\A\\L\\Z\\P\\1k\\H\\G\\1o\",\"\\V\\B\\A\\1a\\F\\O\\D\\1c\\E\\U\\J\",\"\\1N\\4j\\R\\1r\",\"\\B\\E\\F\\K\\1o\\1q\\B\\F\\O\\A\\P\\1k\\H\\G\\1o\",\"\\V\\1k\\F\\O\\1e\\A\\E\\P\\J\\H\\D\\O\\A\\O\",\"\\B\\1c\\H\\1k\\Z\\R\",\"\\V\\1e\\H\\E\\H\\R\\1X\\V\\K\\B\\E\\P\\B\\1c\\D\\G\\A\\P\\1d\\E\\L\\1X\\V\\K\\H\\L\\E\\D\\K\\E\\P\\1d\\E\\L\\P\\D\\G\\A\\D\",\"\\1L\\1g\\D\\K\\A\\1d\\H\\H\\1o\\P\\1T\\B\\B\\O\\1o\",\"\\V\\E\\D\\1d\\P\\O\\F\\B\\2j\\Z\\B\",\"\\O\\F\\B\\2j\\Z\\B\\P\\J\\H\\D\\O\\A\\O\",\"\\V\\O\\F\\B\\2j\\Z\\B\\V\\K\\H\\U\\1b\\A\\U\\1d\\A\\O\\V\\1T\\B\",\"\\O\\D\\E\\D\\P\\E\\F\\U\\A\\B\\E\\D\\U\\R\",\"\\V\\1a\\D\\G\\B\\R\\H\\E\\F\\U\\F\\O\",\"\\V\\E\\D\\1d\\P\\B\\R\\H\\E\\F\\U\",\"\\B\\R\\H\\E\\F\\U\\P\\J\\H\\D\\O\\A\\O\",\"\\1b\\1b\\1k\\1k\\1k\\V\\B\\R\\H\\E\\V\\F\\U\\1b\\J\\D\\Z\\L\\K\\1c\\A\\G\\1b\\1d\\Z\\L\\O\\J\\A\\V\\1T\\B\",\"\\D\\V\\F\\K\\H\\L\\B\\P\\1g\\D\\K\\A\\1d\\H\\H\\1o\",\"\\D\\V\\O\\1c\\G\\A\\1g\\P\\O\\H\\L\\A\",\"\\V\\F\\U\\1e\\P\\B\\G\\K\\P\\J\\H\\D\\O\",\"\\F\\U\\1e\\P\\B\\G\\K\\P\\J\\H\\D\\O\",\"\\F\\E\\A\\U\\P\\R\\D\\1e\\A\\P\\J\\H\\D\\O\\A\\O\",\"\\V\\R\\D\\1e\\A\\G\\P\\F\\B\\F\",\"\\1M\\D\\J\\E\\Y\\1T\\B\\H\\L\\P\\F\\L\\P\\B\\K\\G\\F\\R\\E\\1z\\R\\Z\\1d\\J\\F\\B\\1c\\A\\O\\P\\U\\F\\L\\Y\",\"\\1z\\U\\D\\1r\\P\\G\\A\\B\\Z\\J\\E\\B\\Y\\1J\\1z\\K\\D\\J\\J\\1d\\D\\K\\1o\\Y\\1M\",\"\\1M\\D\\J\\E\\Y\\1T\\B\\H\\L\\P\\F\\L\\P\\B\\K\\G\\F\\R\\E\\1z\\B\\E\\D\\G\\E\\P\\F\\L\\O\\A\\1r\\Y\",\"\\1z\\U\\D\\1r\\P\\G\\A\\B\\Z\\J\\E\\B\\Y\\2c\\1z\\K\\D\\J\\J\\1d\\D\\K\\1o\\Y\\1M\",\"\\D\\V\\1d\\J\\H\\1e\\P\\R\\D\\1e\\A\\G\\P\\L\\A\\1k\\A\\G\\P\\J\\F\\L\\1o\\P\\F\\E\\A\\U\",\"\\1M\\D\\J\\E\\Y\\1T\\B\\H\\L\\P\\F\\L\\P\\B\\K\\G\\F\\R\\E\\1z\\B\\E\\D\\G\\E\\P\\F\\L\\O\\A\\1r\\Y\\2a\\1z\\U\\D\\1r\\P\\G\\A\\B\\Z\\J\\E\\B\\Y\\1N\\1z\\K\\D\\J\\J\\1d\\D\\K\\1o\\Y\\1M\",\"\\V\\R\\H\\R\\Z\\J\\D\\G\\B\\P\\F\\U\\1e\",\"\\V\\F\\U\\1e\\P\\K\\1c\\D\\L\\1e\\A\",\"\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\1x\\Z\\G\\J\\1O\\Q\",\"\\Q\\1K\\N\\L\\H\\P\\G\\A\\R\\A\\D\\E\\N\\K\\A\\L\\E\\A\\G\\N\\K\\A\\L\\E\\A\\G\\1G\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\P\\B\\F\\2T\\A\\1x\\N\\K\\H\\1a\\A\\G\",\"\\F\\U\\1e\\P\\K\\1c\\D\\L\\1e\\A\",\"\\V\\F\\E\\A\\U\\P\\E\\D\\1e\",\"\\V\\G\\A\\K\\H\\P\\R\\J\\D\\K\\A\",\"\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\K\\H\\P\\R\\J\\D\\K\\A\\N\\1d\\J\\H\\1e\\P\\R\\H\\B\\E\\B\\Q\\X\\W\\1c\\2w\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\E\\F\\E\\J\\A\\P\\1k\\G\\D\\R\\Q\\X\",\"\\W\\1b\\B\\R\\D\\L\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\1c\\J\\F\\L\\A\\Q\\X\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\1c\\2w\\X\\W\\O\\F\\1a\\N\\K\\J\\D\\B\\B\\Y\\Q\\G\\A\\K\\H\\P\\F\\L\\L\\A\\G\\Q\\X\\W\\1b\\O\\F\\1a\\X\\W\\B\\R\\D\\L\\N\\K\\J\\D\\B\\B\\Y\\Q\\1d\\E\\L\\N\\G\\A\\K\\H\\P\\K\\J\\H\\B\\A\\Q\\X\\W\\F\\N\\K\\J\\D\\B\\B\\Y\\Q\\1g\\D\\N\\1g\\D\\P\\K\\J\\H\\B\\A\\Q\\X\\W\\1b\\F\\X\\W\\1b\\B\\R\\D\\L\\X\\W\\1b\\O\\F\\1a\\X\",\"\\V\\G\\A\\K\\H\\P\\F\\L\\L\\A\\G\",\"\\B\\1c\\H\\1k\\2Q\\E\",\"\\G\\A\\K\\H\\P\\K\\J\\F\\K\\1o\",\"\\V\\G\\A\\K\\H\\P\\K\\J\\H\\B\\A\",\"\\V\\F\\E\\A\\U\\E\\D\\1e\\B\",\"\\V\\1g\\H\\H\\E\\A\\G\\P\\D\\G\\A\\D\",\"\\1L\\G\\A\\J\\D\\E\\A\\O\\1P\\R\\H\\B\\E\\B\",\"\\G\\A\\J\\P\",\"\\1g\\1d\\F\\1e\",\"\\O\\D\\E\\D\\P\\J\\D\\1d\\A\\J\",\"\\O\\D\\E\\D\\P\\K\\H\\Z\\L\\E\",\"\\W\\B\\R\\D\\L\\X\\1O\",\"\\1K\\W\\1b\\B\\R\\D\\L\\X\",\"\\V\\1c\\F\\O\\A\\P\\J\\D\\1d\\A\\J\",\"\\G\\A\\B\\F\\2T\\A\",\"\\3a\\3v\\1d\\H\\1r\",\"\\V\\E\\D\\1d\\P\\1d\\J\\H\\1e\\1e\\A\\G\\N\\1L\\1d\\J\\H\\1e\\1e\\A\\G\\1P\\K\\U\",\"\\1L\\1d\\J\\H\\1e\\1e\\A\\G\\1P\\K\\U\",\"\\V\\E\\D\\1d\\P\\1d\\J\\H\\1e\\1e\\A\\G\",\"\\1L\\1e\\2m\\J\\Z\\B\\4V\\H\\U\\U\\A\\L\\E\",\"\\1L\\3v\\J\\H\\1e\\1N\",\"\\1L\\1e\\2m\\J\\Z\\B\\4V\\H\\U\\U\\A\\L\\E\\N\\X\\N\\O\\F\\1a\",\"\\R\\H\\G\\E\\G\\D\\F\\E\",\"\\J\\D\\L\\O\\B\\K\\D\\R\\A\",\"\\R\",\"\\P\\1k\\A\\1d\\1o\\F\\E\\P\\E\\G\\D\\L\\B\\1g\\H\\G\\U\",\"\\P\\H\\P\\E\\G\\D\\L\\B\\1g\\H\\G\\U\",\"\\P\\U\\B\\P\\E\\G\\D\\L\\B\\1g\\H\\G\\U\",\"\\P\\U\\H\\2T\\P\\E\\G\\D\\L\\B\\1g\\H\\G\\U\",\"\\E\\G\\D\\L\\B\\1g\\H\\G\\U\",\"\\E\\G\\D\\L\\B\\J\\D\\E\\A\\2c\\O\\1O\\1N\\R\\1r\\1X\\1N\\R\\1r\\1X\\1N\\R\\1r\\1K\",\"\\V\\G\\A\\B\\1d\\Z\\E\\E\\H\\L\",\"\\H\\L\\E\\H\\Z\\K\\1c\\B\\E\\D\\G\\E\",\"\\E\\H\\Z\\K\\1c\",\"\\2O\\D\\1g\\D\\G\\F\",\"\\4V\\G\\F\\4q\\2O\",\"\\B\\E\\D\\L\\O\\D\\J\\H\\L\\A\",\"\\N\\E\\G\\D\\L\\B\\J\\D\\E\\A\\wB\\1O\\1J\\1K\",\"\\H\\L\\H\\G\\F\\A\\L\\E\\D\\E\\F\\H\\L\\K\\1c\\D\\L\\1e\\A\",\"\\H\\G\\F\\A\\L\\E\\D\\E\\F\\H\\L\\K\\1c\\D\\L\\1e\\A\",\"\\K\\J\\F\\K\\1o\\N\\E\\H\\Z\\K\\1c\\B\\E\\D\\G\\E\",\"\\U\\H\\Z\\B\\A\\O\\H\\1k\\L\",\"\\E\\H\\Z\\K\\1c\\U\\H\\1a\\A\",\"\\U\\H\\Z\\B\\A\\U\\H\\1a\\A\",\"\\E\\H\\Z\\K\\1c\\A\\L\\O\",\"\\U\\H\\Z\\B\\A\\Z\\R\",\"\\1J\\B\",\"\\V\\G\\A\\B\\P\\U\\A\\L\\Z\\N\\V\\E\\D\\1d\\P\\1k\\G\\D\\R\\R\\A\\G\\N\\D\\1X\\V\\B\\Z\\1d\\P\\1d\\Z\\E\\E\\H\\L\\1X\\V\\B\\Z\\1d\\P\\1d\\Z\\E\\E\\H\\L\\N\\V\\1g\\D\",\"\\U\\B\",\"\\E\\G\\D\\L\\B\\J\\D\\E\\A\\1O\",\"\\R\\1r\\1X\\1J\\1K\",\"\\B\\1c\\H\\1k\\P\\R\\H\\R\\Z\\R\\P\\G\\A\\B\",\"\\B\\1c\\H\\1k\\P\\G\\A\\B\\P\\U\\A\\L\\Z\",\"\\1L\\B\\A\\1a\\F\\O\\D\\1c\\E\\U\\J\",\"\\V\\D\\O\\B\\1d\\1q\\1e\\H\\H\\1e\\J\\A\",\"\\1k\\A\\1d\\R\\D\\1e\\A\"];1l fa=z$q[0],nW=z$q[1],1y=[/(\\<|\\[)bS +(.*?)4h=(['\"])([^'\"]+?)(['\"])(.*?) *\\/?(\\>|\\])/i,/(dN.be\\/|9O.7m\\/(wA\\?(.*&)?v=|(wz|v)\\/))([^\\?&\\\"\\'>]+)/i,/\\/s\\d+(\\-c)?\\//i,/\\[9O +(.*?)4h=(['\"])([^'\"]+?)(['\"])(.*?) *\\/?\\]/i,/wx.7m\\/|cT.7m\\/|9O.7m\\/|dN.be\\/|\\[cT|\\[9O/i,/df.7m\\/|\\[df/i,/\\[5e\\]|\\[5e|\\[ww/i,/\\<wv\\>/i,/<(?:6B|6C)\\b[^<]*(?:(?!<\\/(?:6B|6C)>)<[^<]*)*<\\/(?:6B|6C)>/gi,/<6B\\b[^<]*(?:(?!<\\/6B>)<[^<]*)*<\\/6B>/gi,/<\\S[^>]*>/g,/\\[\\S[^\\]]*\\]/g,/(:?\\?|\\&)m\\=(1|0)/g,/[^[\\]]+(?=])/g,/bM/g,/bL/g,/7B/g,/7B\\//g,/wu/g,/wt/g,/bJ/g,/ws/g,/ij/g,/ij\\//g,/\\[wq *4a-8v=(\"[^\"]+\") *\\]/g],8B=2d.4g(z$q[2]+nW+fa),7Z=$(z$q[3]).1j?$(z$q[3]).1i(z$q[4]):9g,ff=!$(z$q[5]).1j||z$q[6]!=$(z$q[5]).1i(z$q[4]),bB=$(z$q[7]).1j?$(z$q[7]).1i(z$q[4]).2x(z$q[8]):z$q[10].2x(z$q[9]),i6=$(z$q[11]).1j?$(z$q[11]).1i(z$q[4]).2x(z$q[8]):z$q[12].2x(z$q[9]),cD=$(z$q[13]).1j&&z$q[6]!=$(z$q[13]).1i(z$q[4])?$(z$q[13]).1i(z$q[4]):z$q[14],bq=!$(z$q[15]).1j||z$q[6]!=$(z$q[15]).1i(z$q[4]),8b=$(z$q[16]).1j?$(z$q[16]).1i(z$q[4]):8c,3h=$(z$q[17]).1j?$(z$q[17]).1i(z$q[4]):20,eh=!$(z$q[18]).1j||z$q[19]!=$(z$q[18]).1i(z$q[4]),8j=!$(z$q[20]).1j||z$q[19]!=$(z$q[20]).1i(z$q[4]),fs=!(!$(z$q[21]).1j||z$q[19]!=$(z$q[21]).1i(z$q[4])),bj=!(!$(z$q[22]).1j||z$q[6]==$(z$q[22]).1i(z$q[4])),h6=$(z$q[22]).1j&&z$q[6]!=$(z$q[22]).1i(z$q[4])?$(z$q[22]).1i(z$q[4]):z$q[23],bf=!$(z$q[24]).1j||z$q[19]!=$(z$q[24]).1i(z$q[4]),bb=!(!$(z$q[25]).1j||z$q[19]!=$(z$q[25]).1i(z$q[4])),i5=!$(z$q[26]).1j||z$q[19]!=$(z$q[26]).1i(z$q[4]),b7=!(!$(z$q[27]).1j||z$q[19]!=$(z$q[27]).1i(z$q[4])),ib=$(z$q[28]).1j?$(z$q[28]).1i(z$q[4]):z$q[29],ih=$(z$q[30]).1j?$(z$q[30]).1i(z$q[4]):z$q[31],cp=!$(z$q[32]).1j||z$q[19]!=$(z$q[32]).1i(z$q[4]),8p=$(z$q[33]).1j&&z$q[6]!=$(z$q[33]).1i(z$q[4])?$(z$q[33]).1i(z$q[4]):z$q[34],cQ=$(z$q[35]).1j&&z$q[6]!=$(z$q[35]).1i(z$q[4])?$(z$q[35]).1i(z$q[4]):z$q[36],d1=$(z$q[37]).1j&&z$q[6]!=$(z$q[37]).1i(z$q[4])?$(z$q[37]).1i(z$q[4]):z$q[38],8F=$(z$q[39]).1j&&z$q[6]!=$(z$q[39]).1i(z$q[4])?$(z$q[39]).1i(z$q[4]):z$q[40],8L=$(z$q[41]).1j&&z$q[6]!=$(z$q[41]).1i(z$q[4])?$(z$q[41]).1i(z$q[4]):z$q[42],8R=$(z$q[43]).1j&&z$q[6]!=$(z$q[43]).1i(z$q[4])?$(z$q[43]).1i(z$q[4]):z$q[44],eV=$(z$q[45]).1j&&z$q[6]!=$(z$q[45]).1i(z$q[4])?$(z$q[45]).1i(z$q[4]):z$q[46],f7=$(z$q[47]).1j&&z$q[6]!=$(z$q[47]).1i(z$q[4])?$(z$q[47]).1i(z$q[4]):z$q[48],fp=$(z$q[49]).1j&&z$q[6]!=$(z$q[49]).1i(z$q[4])?$(z$q[49]).1i(z$q[4]):z$q[50],gO=$(z$q[51]).1j&&z$q[6]!=$(z$q[51]).1i(z$q[4])?$(z$q[51]).1i(z$q[4]):z$q[52],h4=$(z$q[53]).1j&&z$q[6]!=$(z$q[53]).1i(z$q[4])?$(z$q[53]).1i(z$q[4]):z$q[54],hm=$(z$q[55]).1j&&z$q[6]!=$(z$q[55]).1i(z$q[4])?$(z$q[55]).1i(z$q[4]):z$q[56],hE=$(z$q[57]).1j&&z$q[6]!=$(z$q[57]).1i(z$q[4])?$(z$q[57]).1i(z$q[4]):z$q[58],hR=$(z$q[59]).1j&&z$q[6]!=$(z$q[59]).1i(z$q[4])?$(z$q[59]).1i(z$q[4]):z$q[60],a0=$(z$q[61]).1j&&z$q[6]!=$(z$q[61]).1i(z$q[4])?$(z$q[61]).1i(z$q[4]):z$q[23],i8=$(z$q[62]).1j&&z$q[6]!=$(z$q[62]).1i(z$q[4])?$(z$q[62]).1i(z$q[4]):z$q[23],6W=$(z$q[63]).1j?$(z$q[63]).1i(z$q[4]):z$q[64],3G=$(z$q[65]).1j&&z$q[6]!=$(z$q[65]).1i(z$q[4])?$(z$q[65]).1i(z$q[4]):z$q[66],4T=!(!$(z$q[67]).1j||z$q[19]!=$(z$q[67]).1i(z$q[4])),it=!$(z$q[68]).1j||z$q[6]!=$(z$q[68]).1i(z$q[4]),iR=!(!$(z$q[69]).1j||z$q[19]!=$(z$q[69]).1i(z$q[4])),wm=!$(z$q[70]).1j||z$q[6]!=$(z$q[70]).1i(z$q[4]),aa=!(!$(z$q[71]).1j||z$q[19]!=$(z$q[71]).1i(z$q[4])),wl=!$(z$q[72]).1j||z$q[6]!=$(z$q[72]).1i(z$q[4]),4S=$(z$q[73]).1j&&z$q[6]!=$(z$q[73]).1i(z$q[4])?$(z$q[73]).1i(z$q[4]):z$q[74],9s=$(z$q[75]).1j&&z$q[6]!=$(z$q[75]).1i(z$q[4])?$(z$q[75]).1i(z$q[4]):z$q[74],an=$(z$q[76]).1j&&z$q[6]!=$(z$q[76]).1i(z$q[4])?$(z$q[76]).1i(z$q[4]):z$q[74],cZ=!(!$(z$q[77]).1j||z$q[19]!=$(z$q[77]).1i(z$q[4])),aF=!(!$(z$q[78]).1j||z$q[19]!=$(z$q[78]).1i(z$q[4])),aX=!(!$(z$q[79]).1j||z$q[19]!=$(z$q[79]).1i(z$q[4])),8w=!(!$(z$q[80]).1j||z$q[19]!=$(z$q[80]).1i(z$q[4])),b6=$(z$q[81]).1j?$(z$q[81]).1i(z$q[4]):z$q[82],bh=$(z$q[83]).1j?$(z$q[83]).1i(z$q[4]):z$q[82],dH=!(!$(z$q[84]).1j||z$q[19]!=$(z$q[84]).1i(z$q[4])),1F={bM:$(z$q[85]).1j?$(z$q[85]).1i(z$q[4]):4,bL:$(z$q[86]).1j?$(z$q[86]).1i(z$q[4]):4,7B:$(z$q[87]).1j?$(z$q[87]).1i(z$q[4]):4,bJ:$(z$q[88]).1j?$(z$q[88]).1i(z$q[4]):5,6I:$(z$q[89]).1j?$(z$q[89]).1i(z$q[4]):5,5g:$(z$q[90]).1j?$(z$q[90]).1i(z$q[4]):5,5C:$(z$q[91]).1j?$(z$q[91]).1i(z$q[4]):10,5D:$(z$q[92]).1j?$(z$q[92]).1i(z$q[4]):5,7c:$(z$q[93]).1j?$(z$q[93]).1i(z$q[4]):6,8a:$(z$q[94]).1j?$(z$q[94]).1i(z$q[4]):5,4Q:$(z$q[95]).1j?$(z$q[95]).1i(z$q[4]):5,4P:$(z$q[96]).1j?$(z$q[96]).1i(z$q[4]):9,5I:$(z$q[97]).1j?$(z$q[97]).1i(z$q[4]):5,7a:$(z$q[98]).1j?$(z$q[98]).1i(z$q[4]):9,6Z:$(z$q[99]).1j?$(z$q[99]).1i(z$q[4]):9,gI:$(z$q[3B]).1j?$(z$q[3B]).1i(z$q[4]):9,5N:$(z$q[gP]).1j?$(z$q[gP]).1i(z$q[4]):6,4O:$(z$q[gR]).1j?$(z$q[gR]).1i(z$q[4]):8,4N:$(z$q[h0]).1j?$(z$q[h0]).1i(z$q[4]):10,5Q:$(z$q[h5]).1j?$(z$q[h5]).1i(z$q[4]):10,6Y:$(z$q[h8]).1j?$(z$q[h8]).1i(z$q[4]):5,4x:$(z$q[hi]).1j?$(z$q[hi]).1i(z$q[4]):7,bx:$(z$q[hn]).1j?$(z$q[hn]).1i(z$q[4]):4,by:$(z$q[hp]).1j?$(z$q[hp]).1i(z$q[4]):4,bC:$(z$q[hz]).1j?$(z$q[hz]).1i(z$q[4]):9,bE:$(z$q[hJ]).1j?$(z$q[hJ]).1i(z$q[4]):4,bF:$(z$q[hL]).1j?$(z$q[hL]).1i(z$q[4]):4,3X:$(z$q[hQ]).1j?$(z$q[hQ]).1i(z$q[4]):6,4c:$(z$q[hT]).1j?$(z$q[hT]).1i(z$q[4]):3,hU:$(z$q[hW]).1j?$(z$q[hW]).1i(z$q[4]):4,hX:$(z$q[hY]).1j?$(z$q[hY]).1i(z$q[4]):8,4w:$(z$q[i3]).1j?$(z$q[i3]).1i(z$q[4]):5};if(z$q[8T]!=7P 8B&&1w!=8B){1l 8K=1h(t){if(t.1Y(z$q[8C]).1j&&bq){t=$(z$q[wk]).2J();1l e=$(z$q[ik]).2J(),a=$(z$q[wj]).2J();t=t+e+a+30,$(z$q[wi]).1Q({2J:t})}},8u=1h(t){!1h(e){1l a,s,i,o,r={2I:3h,7D:3,7A:z$q[wg],cu:cp,2D:z$q[3F],2s:z$q[bP],2r:z$q[bQ],5x:z$q[wf]},r=e.6e({},r,t),n=1I.2q.5A+z$q[6z]+1I.2q.7i,l=2q.3z.1t(1y[12],z$q[23]),d=1h(t){1l l=z$q[23];1W(4v=2h(r.7D/2),4v==r.7D-4v&&(r.7D=2*4v+1),3m=i-4v,1>3m&&(3m=1),2t=2h(t/r.2I)+1,2t-1==t/r.2I&&--2t,3C=3m+r.7D-1,3C>2t&&(3C=2t),t=2h(i)-1,i>1&&(l=2==i?z$q[4n]==s?l+(z$q[we]+1u+z$q[wd]+r.7A+z$q[2i]+1u+z$q[2W]):l+(z$q[3u]+1u+z$q[bW]+o+z$q[bX]+r.2I+z$q[1V]+r.7A+z$q[2i]+1u+z$q[2W]):z$q[4n]==s?l+(z$q[3u]+1u+z$q[wc]+t+z$q[1V]+r.7A+z$q[2i]+1u+z$q[2W]):l+(z$q[3u]+1u+z$q[wa]+t+z$q[1V]+r.7A+z$q[2i]+1u+z$q[2W])),1<3m&&(l=z$q[4n]==s?l+(z$q[3u]+1u+z$q[eM]+1u+z$q[2W]):l+(z$q[3u]+1u+z$q[bW]+o+z$q[bX]+r.2I+z$q[eN]+1u+z$q[2W])),2<3m&&(l+=z$q[eP]),t=3m;t<=3C;t++){l=i==t?l+(z$q[w9]+t+z$q[3Q]):1==t?z$q[4n]==s?l+(z$q[3u]+1u+z$q[eM]+1u+z$q[2W]):l+(z$q[3u]+1u+z$q[bW]+o+z$q[bX]+r.2I+z$q[eN]+1u+z$q[2W]):z$q[4n]==s?l+(z$q[3u]+1u+z$q[bY]+t+z$q[1V]+t+z$q[2i]+1u+z$q[2W]):l+(z$q[3u]+1u+z$q[bZ]+t+z$q[1V]+t+z$q[2i]+1u+z$q[2W])};3C<2t-1&&(l+=z$q[eP]),3C<2t&&(l=z$q[4n]==s?l+(z$q[3u]+1u+z$q[bY]+2t+z$q[1V]+2t+z$q[2i]+1u+z$q[2W]):l+(z$q[3u]+1u+z$q[bZ]+2t+z$q[1V]+2t+z$q[2i]+1u+z$q[2W])),t=2h(i)+1,i<2t&&(l=z$q[4n]==s?l+(z$q[3u]+1u+z$q[bY]+t+z$q[1V]+r.5x+z$q[2i]+1u+z$q[2W]):l+(z$q[3u]+1u+z$q[bZ]+t+z$q[1V]+r.5x+z$q[2i]+1u+z$q[2W])),t=2d.w8(z$q[w7]);1W(1l d=2d.4g(z$q[w6]),c=0;c<t.1j;c++){t[c].4J=l};t&&0<t.1j&&(l=z$q[23]),d&&(d.4J=l),e(z$q[c4]).1Q(z$q[6r],z$q[6q]),e(z$q[w4]).2K(1h(){1l t=e(1f).1i(z$q[fm]);1H ce=(t-1)*r.2I,a=t,z$q[4n]==s?e.2Y(n+z$q[w3]+ce+z$q[fv],m,z$q[3i]):e.2Y(n+z$q[gs]+o+z$q[gy]+ce+z$q[fv],m,z$q[3i]),!1})},c=1h(t){t=2h(t.2v.4i$5b.$t,10),d(t)},p=1h(){1l t=l;-1!=t.1E(z$q[5J])&&(o=-1!=t.1E(z$q[gS])?t.2e(t.1E(z$q[5J])+14,t.1E(z$q[gS])):-1!=t.1E(z$q[gW])?t.2e(t.1E(z$q[5J])+14,t.1E(z$q[gW])):-1!=t.1E(z$q[gY])?t.2e(t.1E(z$q[5J])+14,t.1E(z$q[gY])):t.6n(t.9R(z$q[3t]))),-1==t.1E(z$q[w2])&&-1==t.1E(z$q[vM])&&(-1==t.1E(z$q[5J])?(s=z$q[4n],-1!=t.1E(z$q[5i])&&-1!=t.1E(z$q[4f])?r.2I=t.2e(t.1E(z$q[5i])+12,t.1E(z$q[4f])):-1!=t.1E(z$q[5i])?r.2I=t.2e(t.1E(z$q[5i])+12):r.2I=r.2I,i=-1!=l.1E(z$q[4f])?l.2e(l.1E(z$q[4f])+8,l.1j):1,e.2Y(n+z$q[vK],c,z$q[3i])):(s=z$q[hh],-1!=t.1E(z$q[5i])&&-1!=t.1E(z$q[4f])?r.2I=t.2e(t.1E(z$q[5i])+12,t.1E(z$q[4f])):-1!=t.1E(z$q[5i])?r.2I=t.2e(t.1E(z$q[5i])+12):r.2I=r.2I,i=-1!=l.1E(z$q[4f])?l.2e(l.1E(z$q[4f])+8,l.1j):1,e.2Y(n+z$q[gs]+o+z$q[vE],c,z$q[3i])))};p();1l m=1h(t){3W=t.2v.1U[0],t=3W.7R.$t.2e(0,19)+3W.7R.$t.2e(23,29),t=9j(t);1l i=z$q[4n]==s?z$q[vu]+t+z$q[7b]+r.2I+z$q[4f]+a:z$q[5J]+o+z$q[vt]+t+z$q[7b]+r.2I+z$q[4f]+a;if(r.cu){1l n=1y[9];e.2Y(i,1h(){},z$q[0]).6l(1h(t){t=e(z$q[hD]).1R(t.1t(n,z$q[23])).1p(z$q[cj]).2b(z$q[6G]),t.1p(z$q[hN]).1B(1h(){8U(e(1f)),8A(e(1f)),8m(e(1f))}),e(z$q[cj]).1s(t),5a({2D:r.2D,2s:r.2s,2r:r.2r}),l=i,p(),e(z$q[6S]).4p(e(z$q[vs]).3E().3d-50),1I.5t&&1I.5t.6k&&1I.5t.6k.go&&1I.5t.6k.go(),1I.9k&&e.ia(z$q[cg]+1I.9k+z$q[ic]),1I.2V&&1I.2V.4U&&1I.2V.4U.6m&&1I.2V.4U.6m()})}3b{2q.3z=i}}}(3j)},9l=1h(t){!1h(e){1h a(){if(!s.9y){if(s.9y=!0,s.5k){1H s.3Z.1p(z$q[5M]).3P(),s.3Z.1p(z$q[iE]).8q(),e.2Y(s.5k,1h(){},z$q[0]).6l(1h(t){t=e(z$q[hD]).1R(t.1t(o,z$q[23]));1l a=t.1p(z$q[iN]);a?s.5k=a.1i(z$q[5u]):(s.5k=z$q[23],s.3Z.3P()),t=t.1p(s.cd).2b(z$q[6G]),t.1p(z$q[hN]).1B(1h(){8U(e(1f)),8A(e(1f)),8m(e(1f))}),e(s.cd).1R(t),5a({2D:s.2D,2s:s.2s,2r:s.2r}),1I.iV&&1I.iV.8X([z$q[vk],s.5k]),1I.5t&&1I.5t.6k&&1I.5t.6k.go&&1I.5t.6k.go(),1I.9k&&e.ia(z$q[cg]+1I.9k+z$q[ic]),1I.2V&&1I.2V.4U&&1I.2V.4U.6m&&1I.2V.4U.6m(),s.3Z.1p(z$q[iE]).3P(),s.3Z.1p(z$q[5M]).8q(),s.9y=!1}),!1};s.3Z.3P()}}1l s={iX:z$q[vd],5k:z$q[23],3Z:1w,vc:6h,7U:3B,cd:z$q[cj],ct:8L,2D:z$q[4K],2s:z$q[6s],2r:z$q[vb],9y:!1},s=e.6e({},s,t);e(1I);1l i=e(2d),o=1y[9];i.c7(1h(){if(z$q[6t]!=v8.v3().v2.uX&&(s.5k=e(z$q[iN]).1i(z$q[5u]),s.5k)){1l t=e(z$q[2C]+1u+z$q[uP]+s.ct+z$q[2i]+1u+z$q[2M]);t.2K(a);1l i=e(z$q[2C]+7v+z$q[uO]+s.iX+z$q[uN]);s.3Z=e(z$q[uE]),s.3Z.1R(t),s.3Z.1R(i),s.3Z.7w(e(z$q[c4])),e(z$q[c4]).3P()}})}(3j)},8m=1h(t){t.1p(z$q[uC]).1B(1h(){1l t=$(1f).1i(z$q[4]),e=bB;if(z$q[23]!=t){1l a=t.2e(0,10),s=a.2e(0,4),i=a.2e(5,7),a=a.2e(8,10),i=e[2h(i,10)-1]};e=$(1f).1Y(z$q[6a]),e.1R(z$q[uB]),e.2b(z$q[uA]).1s(z$q[9g]+a+z$q[d5]+i+z$q[d6]+s+z$q[uw])})},5a=1h(t){!1h(e){1l a={2D:z$q[4K],2s:z$q[6s],2r:z$q[7Q]},a=e.6e({},a,t),s=e(z$q[uu]).1p(z$q[6G]),i=e(z$q[ut]),o=e(z$q[us]);e=1h(){1H s.1v(z$q[4K]).1Z(z$q[3F]),i.1v(z$q[3e]),o.1Z(z$q[3e]),9a(a.2r,1w,dk),4B(a.2s),!1};1l r=1h(){1H s.1Z(z$q[4K]).1v(z$q[3F]),i.1Z(z$q[3e]),o.1v(z$q[3e]),9a(a.2s,1w,dk),4B(a.2r),!1};6x(a.2s)&&z$q[4K]!=a.2D?(r(),4B(a.2s)):6x(a.2r)&&z$q[4K]!=a.2D?(e(),4B(a.2r)):6x(a.2s)?(r(),4B(a.2s)):6x(a.2r)?(e(),4B(a.2r)):z$q[4K]!=a.2D?(r(),4B(a.2s)):(e(),4B(a.2r)),i.2K(e),o.2K(r)}(3j)},dn=1h(t){!1h(e){1l a={dr:i6,ds:z$q[uq],bU:z$q[up],dz:z$q[dE]},a=e.6e({},a,t),s=4r 6y;e=s.dJ();1l i=s.uo(),s=s.un(),s=5B>s?s+um:s;2d.4g(a.ds).4J=a.dr[i]+z$q[9]+e+z$q[ul]+s;1l o=1h(t){1H 10>t&&(t=z$q[4A]+t),t};z$q[dE]===a.dz?dS(1h(){1l t;t=4r 6y;1l e=t.dT(),s=t.dU(),i=t.dV();t=12>e?z$q[uk]:z$q[uj],0==e&&(e=12),e>12&&(e-=12),e=o(e),s=o(s),i=o(i),2d.4g(a.bU).4J=e+z$q[7l]+s+z$q[7l]+i+z$q[9]+t},2G):dS(1h(){1l t=4r 6y,e=t.dT(),s=t.dU(),t=t.dV(),e=o(e),s=o(s),t=o(t);2d.4g(a.bU).4J=e+z$q[7l]+s+z$q[7l]+t},2G)}(3j)},e3=1h(t){!1h(e){1l a={3R:z$q[23],ec:z$q[6A],ej:z$q[u8],em:z$q[tY],tX:!0,eo:z$q[tP],er:8R,bN:50,et:10,7U:3B},a=e.6e({},a,t),s=e(z$q[ev]),i=s.1p(z$q[eB]);s.1R(z$q[tK]);1l o=e(z$q[tF]);s.on(z$q[eJ],1h(){1l t=i.4E();1H o.8q().1s(z$q[tD]+a.eo+z$q[2z]),e.2Y((z$q[23]===a.3R?1I.2q.5A+z$q[6z]+1I.2q.7i:a.3R)+z$q[tC]+t+z$q[7b]+a.et,1h(e){1l s,i,r,n,l,d,c=e.2v.1U;if(4k(0)!==c){d=z$q[tB]+a.ej+z$q[eW]+t+z$q[tA],d+=z$q[2C]+1u+z$q[eY]+1u+z$q[tz];1W(1l p=0,m=c.1j;m>p;p++){1l h=4r ty(t,z$q[tx]);1W(r=c[p].4H.$t.1t(h,z$q[f5]+t+z$q[3Q]),s=c[p].2N.1j,i=0;s>i;i++){z$q[8Q]==c[p].2N[i].6g&&(n=c[p].2N[i].3z)};1W(i=0;s>i;i++){if(z$q[f9]==c[p].2N[i].6g){l=c[p].2N[i].5y;5X};l=z$q[6E]};s=z$q[8Z]in c[p]?c[p].7Y.$t:z$q[bD]in c[p]?c[p].3M.$t:z$q[23],z$q[bz]in c[p]?(i=c[p].4M$5v.2g.1t(1y[2],z$q[9m]+a.bN+z$q[9o]),-1!=c[p].4M$5v.2g.1E(z$q[9r])&&(i=c[p].4M$5v.2g.1t(z$q[66],z$q[gJ]),l=z$q[5c])):1y[1].1m(s)||1y[3].1m(s)?(l=1y[1].3q(1y[1]),i=1y[3].3q(s),i=z$q[9C]+(1w!=l?l[5]:i[3])+z$q[5E],l=z$q[5c]):1y[0].1m(s)?(i=1y[0].3q(s),i=i[4].1t(1y[2],z$q[9m]+a.bN+z$q[9o])):i=a.ec,1y[4].1m(s)?l=z$q[5c]:1y[5].1m(s)?l=z$q[bw]:1y[6].1m(s)?l=z$q[6H]:1y[7].1m(s)&&(l=0==s.1E(z$q[bs])?z$q[bp]:z$q[6E]),s=s.1t(1y[10],z$q[23]).1t(/\"/g,z$q[9K]).1t(1y[11],z$q[23]),s.1j>a.7U&&(s=s.2e(0,a.7U)+z$q[7d]),s=s.1t(h,z$q[f5]+t+z$q[3Q]),d+=z$q[tq]+1u+z$q[to]+(z$q[6A]===i?z$q[7e]:z$q[tk]+i+z$q[tj])+z$q[tf]+n+z$q[te]+l+z$q[t8]+1u+z$q[t5]+1u+z$q[t3]+n+z$q[1V]+r+z$q[2i]+1u+z$q[2M]+(0<a.7U?z$q[t2]+s+z$q[bn]:z$q[23])+z$q[2z]};d+=z$q[2z]+(e.2v.4i$5b.$t>e.2v.4i$t1.$t?z$q[t0]+1u+z$q[sZ]+t+z$q[1V]+a.er+z$q[eW]+t+z$q[sU]+1u+z$q[8e]:z$q[23]),o.1s(d),o.1p(z$q[sR]).8f()}3b{o.1s(z$q[2C]+1u+z$q[eY]+1u+z$q[sP]+a.em+z$q[sG])}},z$q[3i]),!1}),s.on(z$q[3f],z$q[sF],1h(){1H o.8i(),!1})}(3j)},8U=1h(t){t.1i(z$q[hw]);1l e,a=t.1p(z$q[sE]),s=a.1s(),i=[];e=[];1l i=z$q[6E],o=t.1p(z$q[sA]),r=t.1p(z$q[sy]),n=t.1p(z$q[hC]);if(t=t.1p(z$q[sv]),n.1i(z$q[4m],1h(t,e){1H e.1t(z$q[hF],z$q[5E]).1t(z$q[st],z$q[74])}),o.1j&&(1y[1].1m(s)||1y[3].1m(s)?(i=1y[1].3q(1y[1]),e=1y[3].3q(s),e=1w!=i?i[5]:e[3],e=z$q[9C]+e+z$q[5E],i=z$q[5c]):1y[0].1m(s)?(e=1y[0].3q(s),e=e[4].1t(1y[2],z$q[hH])):e=z$q[6A],o.1i(z$q[4m],z$q[6A]===e?z$q[7e]:e)),-1!=n.1i(z$q[4m]).1E(z$q[9r])&&(n.1R(z$q[hI]),n.3k(z$q[ba]).1v(z$q[ss])),1y[4].1m(s)?i=z$q[5c]:1y[5].1m(s)?i=z$q[bw]:1y[6].1m(s)?i=z$q[6H]:1y[7].1m(s)&&(i=0==s.1E(z$q[bs])?z$q[bp]:z$q[6E]),t.3T(z$q[sr]+i+z$q[6K]),1y[24].1m(s)&&!4T){1W(o=[],t=0,o=s.5V(1y[24]),e=o.1j,i=0;e>i;i++){t+=2h(o[i].1t(1y[24],z$q[hS]).1t(/\"/g,z$q[23]).1t(/'/g,z$q[23]))};o=t/e,n.1R(z$q[sq]+o.7n(1)+z$q[sj]),n.1p(z$q[sh]).1Q(z$q[3U],10*o.7n(1)+z$q[ck])};s=s.1t(1y[10],z$q[23]).1t(1y[11],z$q[23]).1t(/\"/g,z$q[9K]),s.1j>7Z&&(s=s.2e(0,7Z)+z$q[7d]),a.1s(s),n.1i(z$q[7q],z$q[8z]+(-1!=n.1i(z$q[4m]).1E(z$q[aZ])?z$q[aY]+n.1i(z$q[4m])+z$q[7t]:z$q[7e])+z$q[i7]),r.on(z$q[3f],1h(){1l t=$(1f).1Y(z$q[6a]);1H t.1D(z$q[aW])?(t.1p(z$q[i9]).8i(),t.1Z(z$q[aW])):(t.1v(z$q[aW]),t.1p(z$q[i9]).aV()),!1})},8A=1h(t){t.1p(z$q[sf]).1B(1h(){1l t=$(1f),e=t.1D(z$q[8H])?t.1i(z$q[4m]).1t(/\\/s\\d+(\\-c)?\\//i,z$q[sd]):z$q[23],a=t.1D(z$q[8I])?gO:t.1D(z$q[8J])?h4:hm,s=t.1D(z$q[8I])?z$q[aU]:t.1D(z$q[8J])?z$q[aT]:t.1D(z$q[8M])?z$q[ii]:t.1D(z$q[8H])?z$q[aQ]:t.1D(z$q[aN])?z$q[aJ]:z$q[aI],i=t.1D(z$q[8I])?z$q[aU]:t.1D(z$q[8J])?z$q[aT]:t.1D(z$q[8M])?z$q[aH]:t.1D(z$q[8H])?z$q[aQ]:t.1D(z$q[aN])?z$q[aJ]:z$q[aI];t.sa({s9:{iu:t.1D(z$q[8I]),iv:t.1D(z$q[8J]),s0:t.1D(z$q[8M]),iy:t.1D(z$q[8H]),rZ:t.1D(z$q[aN]),rS:t.1D(z$q[iD])},rR:z$q[rP]+s+z$q[rJ]+a+z$q[3Q],rH:!1,rG:!0,rF:t.1D(z$q[8M])||t.1D(z$q[iD])?z$q[23]:z$q[rC],rA:{iu:{rx:hR},iy:{4M:e}},2K:1h(t){t.rv(),t.rt(i)}})}).8Y(z$q[5u]).1v(z$q[rs])},4B=1h(t){1H 6P()?iY(t):aw()?cl(t):z$q[23]},6x=1h(t){1H 6P()?cm(t):aw()?av(t):z$q[23]},9a=1h(t,e){1H 6P()?co(t,e):aw()?9c(t,e):!1},iY=1h(t){9d.ro(t)},cm=1h(t){1H 6P()&&(t=9d.rk(t))?t:z$q[23]},co=1h(t,e){1H 6P()?(9d.rb(t,e),!0):!1},6P=1h(){1H z$q[8T]!=7P 9d},cl=1h(t){9c(t,z$q[23],-1)},av=1h(t){if(!r9()){1H z$q[23]};1l e,a,s,i=2d.au.2x(z$q[qW]);1W(e=0;e<i.1j;e++){if(a=i[e].6n(0,i[e].1E(z$q[at])),s=i[e].6n(i[e].1E(z$q[at])+1),a=a.1t(/^\\s+|\\s+$/g,z$q[23]),a==t){1H qV(s)}};1H z$q[23]},qT=1h(){1H!!9c(z$q[qR],z$q[qQ])},9c=1h(t,e,a){if(!cz()){1H!1};1l s=4r 6y;1H s.qN(s.dJ()+a),a=qJ(e)+(1w==a?z$q[23]:z$q[cC]+s.qH())+z$q[qD],2d.au=t+z$q[at]+a,av(t)===e},cz=1h(){1H z$q[qm]in 2d};$.ql({qk:!0}),fs&&$(z$q[qj]).3P(),5P.7I.5V(/qi|cM/i)&&!5P.7I.5V(/cN|qh/i)&&(8B.ai+=z$q[q7]),aa&&$(z$q[9p]).3P(),1h(t){1h e(e,a){1l s=z$q[pW]+e+z$q[pT];t(z$q[4o],a).1B(1h(){1l a=t(1f).2B(),i=a.6n(0,1),o=a.6n(1),r=t(1f).1p(z$q[cW]).1j?z$q[pO]+t(1f).1p(z$q[cW]).1i(z$q[9t])+z$q[6K]:z$q[23],n=t(1f).1p(z$q[5M]).1i(z$q[5u]);s=z$q[pL]==i||z$q[ad]==i?s+(z$q[pt]+1u+z$q[4R]+n+z$q[1V]+r+o+z$q[2i]+1u+z$q[pg]):s+(z$q[p8]+1u+z$q[4R]+n+z$q[1V]+r+a+z$q[2i]+1u+z$q[oZ]+e+z$q[1V])}),s+=z$q[oQ],t(a).1s(s),t(z$q[7N],a).1B(1h(){1l e=t(1f);0==e.1s().1t(/\\s|&ab;/g,z$q[23]).1j&&e.2X()}),t(z$q[4o],a).1B(1h(){1l e=t(1f);0==e.1s().1t(/\\s|&ab;/g,z$q[23]).1j&&e.2X()})}if(bj){!1h(){1l t=h6,e=2d.6R(z$q[5G]);e.5y=z$q[da],e.db=!0,e.4h=(z$q[dc]==2d.2q.5A?z$q[dd]:z$q[oP])+z$q[oO]+t,t=2d.6T(z$q[5G])[0],t.9H.7w(e,t)}(),t(z$q[oN]).1R(z$q[oL]);1l a=t(z$q[ev]),s=a.1p(z$q[eB]);a.1v(z$q[oJ]),a.on(z$q[eJ],1h(){1l t=s.4E(),e=oH.oG.oF.3w.oA(z$q[oz]);1H z$q[23]==t?e.ow():e.ou(t),!1})};1l a=t(z$q[a6]).2B(),i=t(z$q[ot]).1i(z$q[4]),o=t(z$q[ol]).1i(z$q[4]);t(z$q[oj]).1i(z$q[4]),i=z$q[oi]+i+z$q[dw],o=z$q[of]+o+z$q[dw],t(z$q[a6]).1s(a.1t(/\\[oe\\]/g,z$q[od]).1t(/\\[oc\\]/g,z$q[ob]).1t(/\\[iv\\]/g,i).1t(/\\[o9\\]/g,o)),t(z$q[o7]).1i({o6:z$q[o4]+8p+z$q[o2],np:z$q[nf]+8p+z$q[nb],8v:8p});1l r=t(z$q[na]).2b().6X(),a=r.5x(),n=t(z$q[2n]),l=t(z$q[6S]);if(r.on(z$q[n7],1h(){n.dM().n6(1f.8v),n.1p(z$q[dO]).1j&&l.4p(n.1p(z$q[dO]).6X().3E().3d-3B)}),a.on(z$q[3f],1h(){1H n.dM(),r.4E(z$q[23]).4u(z$q[n5]),l.4p(0),!1}),a=n3(z$q[dR]),z$q[23]!=a&&1w!=a&&t(z$q[2n]).1Q(z$q[9X],a+z$q[4t]),t(z$q[mY]).2K(1h(){1l e=t(z$q[2n]).1Q(z$q[9X]),e=e.1t(z$q[4t],z$q[23]),a=t(1f).1i(z$q[9t]),e=5n(e);1H-1!=a.1E(z$q[mV])?e++:--e,mU(z$q[dR],e),t(z$q[2n]).1Q(z$q[9X],e+z$q[4t]),!1}),t(z$q[mT]).2K(1h(){1l e=t(1f).3k();1H e.1D(z$q[3e])?e.1Z(z$q[3e]):e.1v(z$q[3e]),!1}),t(z$q[mR]).7X(z$q[mO]).1R(z$q[mN]),t(z$q[mM]).1B(1h(){e(z$q[mL],1f),t(1f).1v(z$q[7W])}),t(z$q[mK]).1B(1h(){e(z$q[mJ],1f)}),t(z$q[mI]).3k(z$q[4o]).1v(z$q[mH]).1R(z$q[mF]),t(z$q[mE]).3k(z$q[4o]).1v(z$q[mD]).1R(z$q[mC]),t(z$q[a5]).1B(1h(){t(1f).1s(t(1f).1s().1t(/\\[/g,z$q[6h]).1t(/\\]/g,z$q[3Q]))}),t(z$q[mB]).1B(1h(){t(1f).3r(z$q[mA]+t(1f).1s()+z$q[6K])}),t(z$q[mz]).1Y(z$q[4o]).1v(z$q[my]),0<t(z$q[mx]).1j){1l d=t(z$q[mw]),c=0,p=0;t(z$q[ei]).1B(1h(){1l e=t(1f);if(e.1i(z$q[5u])==1I.2q.3z&&e.1Y(z$q[5o]).1j){1l a=2h(e.1Y(z$q[5o]).1Q(z$q[9F]));c=e.1Y(z$q[5o]).5q().2S+a,p=e.1Y(z$q[5o]).2y()};d.1Q({2y:p,2S:c})}),0==c&&(c=t(z$q[9D]).5q().2S,d.1Q(z$q[9B],c)),t(z$q[mu]).2K(1h(){1l e=2h(t(1f).3k().1Q(z$q[9F]));c=t(1f).3k().5q().2S+e,p=t(1f).3k().2y()}),t(1I).9x(1h(){t(z$q[ei]).1B(1h(){1l e=t(1f);if(e.1i(z$q[5u])==1I.2q.3z&&e.1Y(z$q[5o]).1j){1l a=2h(e.1Y(z$q[5o]).1Q(z$q[9F]));c=e.1Y(z$q[5o]).5q().2S+a,p=e.1Y(z$q[5o]).2y()};d.1Q({2y:p,2S:c})}),0==c&&(c=t(z$q[9D]).5q().2S,d.1Q(z$q[9B],c))}),t(z$q[mt]).eu(1h(){1l e=2h(t(1f).1Q(z$q[9F]));d.7K({2y:t(1f).2y(),2S:t(1f).5q().2S+e},{ew:!1,ex:z$q[ey],ez:5E}),t(z$q[9D]).1v(z$q[eA])},1h(){d.7K({2y:p,2S:c},{ew:!1,ex:z$q[ey],ez:5E}),t(z$q[9D]).1Z(z$q[eA])})};t(z$q[ms]).mq(3B,1h(){t(1f).2b(z$q[7N]).mp(z$q[mo]).eF()},8z,1h(){t(1f).2b(z$q[7N]).ag(2G,z$q[mm])}),t(z$q[mh]).on(z$q[3f],1h(){1l e=t(z$q[eI]);e.1D(z$q[ah])?(t(1f).1Z(z$q[eK]),e.8i().1Z(z$q[ah])):(t(1f).1v(z$q[eK]),e.aV().1v(z$q[ah]))}),t(z$q[me]).1B(1h(){1l e=t(1f),a=t(1f).1p(z$q[4o]);0===a.1j&&e.1Y(z$q[md]).2X(),e.1v(z$q[7W]),e.1p(z$q[mb]).1Y(z$q[4o]).1p(z$q[eO]).2B(z$q[ma]),e.1p(z$q[m0]).1Y(z$q[4o]).1p(z$q[eO]).2B(z$q[lZ]),t(z$q[eR],e).am(z$q[eT],z$q[lV]),t(z$q[eR],e).am(z$q[7H],z$q[3Q]),a.1B(1h(){1l e=t(1f).1p(z$q[lP]),a=t(1f).1p(z$q[lG]);t(e).7F(t(a)),t(e).2X()})}),t(z$q[7E]).1R(t(z$q[eZ]).1s()),t(z$q[eZ]).3k().2X(),t(z$q[lz]).2K(1h(){1l e=t(1f);1H e.1D(z$q[3e])?(t(z$q[7E]).8i(),e.1Z(z$q[3e])):(e.1v(z$q[3e]),t(z$q[7E]).aV(),t(z$q[7E]).1D(z$q[ly])||t(z$q[7E]).8f()),!1}),t(z$q[f2]).1p(z$q[5F]).1B(1h(){4H=t(1f).1p(z$q[3S]).2B(),t(1f).1i(z$q[lw],4H)}),t(z$q[f2]).7C({9f:1,fx:z$q[4X]})}(3j);1l f8=1h(t){1l e,a,s=t.1j;if(0===s){1H!1};1W(;--s;){e=4e.ax(4e.2f()*(s+1)),a=t[s],t[s]=t[e],t[e]=a};1H t},fb=1h(t,e){1H 4e.ax(4e.2f()*(e-t+1))+t};$(z$q[lt]).1B(1h(){8U($(1f))}),1I.fd=1h(){1l t=1h(t){t=t||{};1l e=t.lr||z$q[lj],a=t.lg||z$q[la],s=t.l9||z$q[l7];$(t.l3||z$q[l1]).7F(z$q[kZ]+a+z$q[kY]+s+z$q[2z]),t=1h(t,a,s){$(e).1B(1h(){$(1f).1s($(1f).1s().1t(/<br>:/g,z$q[kX]).1t(/<br>;/g,z$q[kV]).1t(/<br>=/g,z$q[kU]).1t(/<br>\\^/g,z$q[kT]).1t(t,z$q[fr]+7v+z$q[kS]+a+z$q[kQ]+s+z$q[fu]))})},t(/\\s:\\)\\)+/g,1C.fw,z$q[fy]),t(/\\s;\\(\\(+/g,1C.fz,z$q[fA]),t(/\\s:\\)+/g,1C.fB,z$q[fC]),t(/\\s:-\\)+/g,1C.fD,z$q[fE]),t(/\\s=\\)\\)+/g,1C.fF,z$q[fG]),t(/\\s;\\(+/g,1C.fH,z$q[fI]),t(/\\s;-\\(+/g,1C.fJ,z$q[fK]),t(/\\s:d/gi,1C.fL,z$q[fM]),t(/\\s:-d/gi,1C.fN,z$q[fO]),t(/\\s@-\\)+/g,1C.fP,z$q[fQ]),t(/\\s:p/gi,1C.fR,z$q[fS]),t(/\\s:o/gi,1C.fT,z$q[fU]),t(/\\s:&gt;\\)+/g,1C.fV,z$q[fW]),t(/\\s\\(o\\)+/gi,1C.fX,z$q[fY]),t(/\\s\\[-\\(+/g,1C.fZ,z$q[g0]),t(/\\s:-\\?/g,1C.g1,z$q[g2]),t(/\\s\\(p\\)+/gi,1C.g3,z$q[g4]),t(/\\s:-s/gi,1C.g5,z$q[g6]),t(/\\s\\(m\\)+/gi,1C.g7,z$q[g8]),t(/\\s8-\\)+/gi,1C.g9,z$q[aG]),t(/\\s:-t/gi,1C.ga,z$q[gb]),t(/\\s:-b/gi,1C.gc,z$q[ge]),t(/\\sb-\\(+/gi,1C.gf,z$q[gg]),t(/\\s:-#/gi,1C.gh,z$q[gj]),t(/\\s=p~/gi,1C.gk,z$q[gl]),t(/\\s\\$-\\)+/gi,1C.gn,z$q[gp]),t(/\\s\\(b\\)+/gi,1C.gq,z$q[gr]),t(/\\s\\(f\\)+/gi,1C.gu,z$q[gv]),t(/\\sx-\\)+/gi,1C.gw,z$q[gx]),t(/\\s\\(k\\)+/gi,1C.gz,z$q[gA]),t(/\\s\\(h\\)+/gi,1C.gB,z$q[gC]),t(/\\s\\(c\\)+/gi,1C.gD,z$q[gE]),t(/\\gF/gi,1C.gG,z$q[gH]),$(z$q[kP]).1Q(z$q[kO],z$q[2G]).on(z$q[3f],1h(t){$(z$q[8P]).2X(),$(1f).aK(z$q[kN]+1f.gM.1j+z$q[kM]+1f.gM+z$q[kL]),$(z$q[8P]).4u(z$q[kK]),t.kJ()}),$(z$q[8P]).on(z$q[3f],1h(){$(1f).kI().kG()}),$(z$q[kF]).on(z$q[3f],1h(){$(z$q[aP]).1D(z$q[3e])?$(z$q[aP]).1Z(z$q[3e]):$(z$q[aP]).1v(z$q[3e])}),$(2d).on(z$q[3f],1h(){$(z$q[8P]).2X()})};1H 1h(e){t(e)}}(),i5&&dn(),bj||dH||e3(),8m($(z$q[6a])),$(z$q[kE]).1j&&bf&&fd(),1h(t){if(t(z$q[8N]).1D(z$q[gX])&&!b7){bb?(9l({2D:z$q[3F]}),5a({2D:z$q[3F]})):(9l(),5a())}3b{if(t(z$q[8N]).1D(z$q[gX])&&b7){1l e=t(z$q[aR]).1p(z$q[6G]).1j;bb?(8u({2I:e,2D:z$q[3F],2s:z$q[6s],2r:z$q[7Q]}),5a({2D:z$q[3F],2s:z$q[6s],2r:z$q[7Q]})):(8u({2D:z$q[4K],2I:e,2s:z$q[6s],2r:z$q[7Q]}),5a({2D:z$q[4K],2s:z$q[6s],2r:z$q[7Q]}))}};t(z$q[8N]).1D(z$q[kD])&&(8u({2D:z$q[3F],2s:z$q[bP],2r:z$q[bQ]}),5a({2D:z$q[3F],2s:z$q[bP],2r:z$q[bQ]})),(t(z$q[kC]).1j||t(z$q[8N]).1D(z$q[kz]))&&(9l({2D:z$q[3F],2s:z$q[h2],2r:z$q[h3]}),5a({2D:z$q[3F],2s:z$q[h2],2r:z$q[h3]}))}(3j),1h(t){t.2H=1h(e,a){1l s=1f;s.$el=t(e),s.7u=1h(){s.1n=t.6e({},t.2H.8E,a);1l e=z$q[23]===s.1n.2R?z$q[23]:z$q[7s]+s.1n.2R+z$q[6L],i=s.$el.1Y(z$q[4Z]).1i(z$q[9t]);s.$el.1s(z$q[8x]+(z$q[23]!=s.1n.2R&&/4c/.1m(i)?z$q[7s]+s.1n.2R+z$q[6L]:z$q[23])+(z$q[7o]===s.1n.2F?z$q[hg]:z$q[23])+z$q[kx]+(s.1n.5H?z$q[ks]:z$q[23]));1l o,r,n=0,l=1w,d=2q.3z.1t(/(:?\\?|\\&)m\\=(1|0)/g,z$q[23]),c=2d.2q.b5.2x(z$q[hl]),p=s.1n.3n,m=3,h=1,u=z$q[23]===s.1n.3R?1I.2q.5A+z$q[6z]+1I.2q.7i:s.1n.3R,g=1h(a){1W(1s=z$q[23],4v=2h(m/2),4v==m-4v&&(m=2*4v+1),3m=h-4v,1>3m&&(3m=1),2t=2h(a/p)+1,2t-1==a/p&&--2t,3C=3m+m-1,3C>2t&&(3C=2t),a=2h(h)-1,h>1&&(1s=2==h?1s+(z$q[6d]+e+z$q[kj]):1s+(z$q[6d]+e+z$q[8o]+a+z$q[kg])),1<3m&&(1s+=z$q[6d]+e+z$q[hr]),2<3m&&(1s+=z$q[hs]),a=3m;a<=3C;a++){1s=h==a?1s+(z$q[kc]+a+z$q[3Q]):1==a?1s+(z$q[6d]+e+z$q[hr]):1s+(z$q[6d]+e+z$q[8o]+a+z$q[1V]+a+z$q[8n])};3C<2t-1&&(1s+=z$q[hs]),3C<2t&&(1s+=z$q[6d]+e+z$q[8o]+2t+z$q[1V]+2t+z$q[8n]),a=2h(h)+1,h<2t&&(1s+=z$q[6d]+e+z$q[8o]+a+z$q[k9]),s.$el.1p(z$q[bc]).1s(1s),s.$el.1p(z$q[k1]).2K(1h(){1l e=5n(t(1f).1i(z$q[fm]));s.$el.1p(z$q[3I]).aK(z$q[k0]),s.$el.1p(z$q[hA]).1s(s.$el.1p(z$q[3I]).1s()),s.$el.1p(z$q[3I]).1s(z$q[23]);1l a=e*p-(p-1),i=s.$el.1p(z$q[bc]).1i(z$q[hB]);1w==i||4k(0)==i?t.2Y(u+z$q[jQ]+a+z$q[7b]+p+z$q[8l],f,z$q[3i]):t.2Y(u+z$q[jN]+i+z$q[gy]+a+z$q[7b]+p+z$q[8l],f,z$q[3i]),h=e})},f=1h(a){if(s.1n.5H){1l i=2h(a.2v.4i$5b.$t,10);g(i)};1W(n++,r=a.2v.2N.1j,i=0;r>i;i++){if(z$q[8Q]==a.2v.2N[i].6g){o=a.2v.2N[i].3z;5X}};if(1U=!0===s.1n.2f?f8(a.2v.1U):a.2v.1U,4k(0)!==1U){1W(1l l=1U.1j,i=0;l>i;i++){1l p,m,h,u,f,b,x,w,y=1U[i].2N.1j;h=[],m=[];1l k,$,C,T,I=z$q[23];1W(k=0;y>k;k++){if(z$q[8Q]==1U[i].2N[k].6g){p=1U[i].2N[k].3z;5X}};1W(k=0;y>k;k++){if(z$q[jM]==1U[i].2N[k].6g&&z$q[jL]==1U[i].2N[k].5y){u=5n(1U[i].2N[k].4H.2x(z$q[9])[0]);5X}};1W(k=0;y>k;k++){if(z$q[f9]==1U[i].2N[k].6g){T=1U[i].2N[k].5y;5X};T=z$q[6E]};if(C=z$q[9N]===s.1n.2F&&o!==1I.2q.5A+z$q[6z]+1I.2q.7i+z$q[3t]?o.6n(o.9R(z$q[3t])+1):4k(0)!==1U[i].hO?1U[i].hO[0].jI:z$q[23],k=s.1n.2Z&&1U[i]===1U[0],$=1U[i]!==1U[0],y=z$q[8Z]in 1U[i]?1U[i].7Y.$t:z$q[bD]in 1U[i]?1U[i].3M.$t:z$q[23],z$q[bz]in 1U[i]?(h=1U[i].4M$5v.2g.1t(1y[2],z$q[3t]+s.1n.5m+z$q[3t]),-1!=1U[i].4M$5v.2g.1E(z$q[9r])?(h=1U[i].4M$5v.2g.1t(z$q[66],z$q[gJ]),T=z$q[5c]):k&&(h=1U[i].4M$5v.2g.1t(1y[2],z$q[3t]+s.1n.9J+z$q[3t]))):1y[1].1m(y)||1y[3].1m(y)?(h=1y[1].3q(1y[1]),m=1y[3].3q(y),h=z$q[9C]+(1w!=h?h[5]:m[3])+z$q[5E],T=z$q[5c]):1y[0].1m(y)?(m=1y[0].3q(y),h=m[4].1t(1y[2],z$q[3t]+s.1n.5m+z$q[3t])):h=z$q[6A],1y[4].1m(y)?T=z$q[5c]:1y[5].1m(y)?T=z$q[bw]:1y[6].1m(y)?T=z$q[6H]:1y[7].1m(y)&&(T=0==y.1E(z$q[bs])?z$q[bp]:z$q[6E]),1y[24].1m(y)&&s.1n.4a){1W(I=[],m=0,I=y.5V(1y[24]),b=I.1j,x=0;b>x;x++){m+=2h(I[x].1t(1y[24],z$q[hS]).1t(/\"/g,z$q[23]).1t(/'/g,z$q[23]))};I=m/b,I=z$q[8x]+e+z$q[jH]+I.7n(1)+z$q[jF]+10*I.7n(1)+z$q[jE]};y=y.1t(1y[10],z$q[23]).1t(1y[11],z$q[23]).1t(/\"/g,z$q[9K]),y.1j>s.1n.3M&&(y=y.2e(0,s.1n.3M)+z$q[7d]),m=1U[i].4H.$t.1t(/\"/g,z$q[9K]),f=1U[i].7R.$t.2e(0,10),bv=f.2e(0,4),b=5n(f.2e(0,2)).9G()+5n(f.2e(2,4)).9G(),x=f.2e(5,7),w=f.2e(8,10),f=1U[i].4I[0].2o.$t,-1<1I.2q.3z.1E(z$q[jD])&&z$q[jx]!=c[c.1j-1]&&(d=z$q[cg]+c[0]+z$q[jw]+2d.2q.bA),s.$el.1Y(z$q[aR]).1j?d.i4()!=p.i4()&&v(p,m,h,y,b,w,x,u,f,k,$,C,T,I,bv):v(p,m,h,y,b,w,x,u,f,k,$,C,T,I,bv)}};if(n>=s.1n.2l.1j){if(0<s.1n.2A&&!s.$el.1D(z$q[3O])&&t(z$q[jv]+(s.1n.2A-1)+z$q[7t],s.$el.1p(s.1n.2Z&&s.$el.1D(z$q[3O])?z$q[6D]:z$q[3I])).2X(),p=s.$el.1p(z$q[3I]),z$q[2]===s.1n.2F){p.4D({4C:!0,4z:3s(),3A:s.1n.3Y,4L:[z$q[23],z$q[23]],5s:s.1n.5w,4y:!0,5O:!0,4G:!0,9z:z$q[4X]===s.1n.5f?z$q[bT]:z$q[9i]===s.1n.5f?z$q[io]:!1,ip:z$q[9i]===s.1n.5f?z$q[iq]:!1,5S:2G,3c:1,5K:2G}).1v(z$q[5Z])}3b{if(z$q[5W]===s.1n.2F){p.4D({3A:s.1n.3Y,8h:2,4y:!0,5s:s.1n.5w,4z:3s(),4C:!0,4G:!0,4L:[z$q[23],z$q[23]],ix:s.$el,js:s.$el.1Y(z$q[5F]).1p(z$q[iz]),iA:{0:{3c:1},a5:{3c:2},c2:{3c:3},5B:{3c:4}}}).1v(z$q[5Z])}3b{if(z$q[6]===s.1n.2F){p.jr({jq:s.$el.1Y(z$q[jn]).1p(z$q[3S]).2B(),jm:3s()?z$q[jj]:z$q[ji]}),s.$el.1Y(z$q[4Z]).1p(z$q[jh]).1Q({\"\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\P\\K\\H\\J\\H\\G\":s.1n.2R})}3b{if(z$q[7o]===s.1n.2F){1l M=s.$el.2y();p.1v(z$q[5Z]).4D({jg:!1,4z:3s(),4y:!0,8h:1,5O:!0,jf:!0,3c:3,4L:[z$q[23],z$q[23]],4C:!0,3A:s.1n.3Y,5s:s.1n.5w,je:!0,5S:2G,5K:2G,4G:!0,jd:1h(t){1l e=1f.$3w.1i(z$q[ca]);t=1w!=1f.cb?1f.cb:M,e=(t-e-2*1f.1n.8h)/2,e>0&&1f.$3w.1p(z$q[9e]).1Q(z$q[3U],e+z$q[4t]),50>e?1f.$3w.1p(z$q[9e]).1v(z$q[iQ]):1f.$3w.1p(z$q[9e]).1Z(z$q[iQ]),7j>t?(e=t-20,1f.$3w.1p(z$q[3K]).1Q(z$q[3U],e+z$q[4t]).1i(z$q[ca],e),1f.$3w.1p(z$q[9e]).1Q(z$q[3U],z$q[jc]),!0===3s()&&1f.$3w.1p(z$q[iT]).1Q(z$q[9B],z$q[ad]+e+z$q[4t])):(1f.$3w.1p(z$q[3K]).1Q(z$q[3U],z$q[jb]),!0===3s()&&1f.$3w.1p(z$q[iT]).1Q(z$q[9B],z$q[ja]))},j9:1h(){1f.j5()},j3:1h(t){t=1f.$3w.1i(z$q[ca]);1l e=1f.cb;7j>e&&(t=e-20),e=7j>e?eI*t/7j:1f.$3w.2J(),1f.$3w.1p(z$q[j2]).pV(z$q[j1]).1Q({2J:e+z$q[4t],2y:t+z$q[4t]})}})}3b{if(z$q[9N]===s.1n.2F){1W(u=p.2b(z$q[3K]),i=0;i<u.1j;i+=s.1n.6f){u.4F(i,i+s.1n.6f).5L(z$q[j4])};p.4D({4C:!0,4z:3s(),3A:s.1n.3Y,4L:[z$q[23],z$q[23]],5s:s.1n.5w,4y:!0,9z:z$q[4X]===s.1n.5f?z$q[bT]:!1,5O:!0,4G:!0,5S:2G,3c:1,5K:2G}).1v(z$q[5Z])}3b{if(z$q[ch]===s.1n.2F){1W(u=p.2b(z$q[3K]),i=0;i<u.1j;i+=s.1n.6f){u.4F(i,i+s.1n.6f).5L(z$q[j6])};p.1p(z$q[j7]).4D({4C:!0,4z:3s(),3A:s.1n.3Y,4L:[z$q[23],z$q[23]],5s:s.1n.5w,4y:!0,j8:!1,9z:z$q[4X]===s.1n.5f?z$q[bT]:!1,5O:!0,4G:!0,5S:2G,3c:1,5K:2G}).1v(z$q[5Z])}}}}}};if(s.1n.3V){if(s.1n.9L){1W(u=p.2b(z$q[3K]),i=0;i<u.1j;i+=u.1j){u.4F(1,i+u.1j).5L(z$q[iU])};i=s.$el.1p(z$q[iS]),i.c9(z$q[iL]),i.iK().on(z$q[c8],1h(){3j(1f).4u(z$q[iI])}).on(z$q[iH],1h(){3j(1f).4u(z$q[iG])})}3b{1W(u=p.2b(z$q[3K]),i=0;i<u.1j;i+=u.1j+1){u.4F(i,i+u.1j+1).5L(z$q[iU])};i=s.$el.1p(z$q[iS]),i.c9(z$q[iL]),i.iK({jk:5}).on(z$q[c8],1h(){3j(1f).4u(z$q[iI])}).on(z$q[iH],1h(){3j(1f).4u(z$q[iG])})}};if(s.1n.2Z){1W(u=p.2b(z$q[3K]),i=0;i<u.1j;i+=u.1j){u.4F(1,i+u.1j).5L(z$q[jl])}};i=s.$el.1p(z$q[3K]),(i.1j>=a.2v.4i$5b.$t||s.1n.2f||s.1n.3V)&&s.$el.1p(z$q[c6]).3P(),s.1n.5d&&i.1j>s.1n.2A&&(s.$el.1p(s.1n.2Z&&s.$el.1D(z$q[3O])?z$q[6D]:z$q[3I]).1D(z$q[jo])&&s.$el.1p(s.1n.2Z&&s.$el.1D(z$q[3O])?z$q[6D]:z$q[3I]).8f(z$q[jp]),s.$el.1p(s.1n.2Z&&s.$el.1D(z$q[3O])?z$q[6D]:z$q[3I]).8f()),s.1n.8d&&(0===t(z$q[5R]).1p(z$q[c1]).1j&&t(z$q[5R]).1R(z$q[jt]),s.$el.1p(z$q[ju]).eu(1h(){1l e,a=t(1f),i=a.1Y(z$q[3K]).1s(),o=a.2J(),r=a.3E(),n=t(2d.6i).2y(),l=t(1f).1Y(z$q[5F]).1D(z$q[6H])?z$q[i2]:z$q[23];e=r.2S,3s()&&(e=e+a.2y()-aH),e+aH>n?e=n-cC:10>e&&(e=10),t(z$q[c1]).1Q({3d:z$q[6]===s.1n.2F?r.3d+o:r.3d-7N,2S:e}).1v(z$q[i1]+l).1s(i)},1h(){1l e=t(1f).1Y(z$q[5F]).1D(z$q[6H])?z$q[i2]:z$q[23];t(z$q[c1]).1Z(z$q[i1]+e).1s(z$q[23])})),s.1n.5H&&s.$el.1p(z$q[hA]).2X(),s.$el.1Y(z$q[4Z]).1Q(z$q[jy],z$q[jz]),s.$el.1p(z$q[3I]).1Z(z$q[jA]),8K(s.$el),z$q[23]!==s.1n.2R&&s.$el.1Y(z$q[4Z]).1p(z$q[jB]).1j&&(s.$el.1Y(z$q[4Z]).1p(z$q[iz]).2b().1Q({\"\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\P\\K\\H\\J\\H\\G\":s.1n.2R}),s.$el.1Y(z$q[4Z]).1p(z$q[jC]).1Q({\"\\1d\\D\\K\\1o\\1e\\G\\H\\Z\\L\\O\\P\\K\\H\\J\\H\\G\":s.1n.2R}))}},v=1h(e,a,o,r,n,l,d,c,p,m,h,u,g,f,v){1W(1l x=t(z$q[3K],s.$el.1p(s.1n.2Z&&s.$el.1D(z$q[3O])?z$q[6D]:z$q[3I])),w=0,y=x.1j;y>w;w++){1l k=t(z$q[5M],x.eq(w)),$=b(k);if(k.1i(z$q[5u])==e){1W(e=k,a=++$,e.1i(z$q[hV],a),s.1n.bu&&e.1i(z$q[4],s.1n.bu.1t(z$q[jG],a)),s.1n.bt&&e.1i(z$q[9t],s.1n.bt+a),e=w-1;e>=0;e--){if(a=t(z$q[5M],x.eq(e)),b(a)>$){1H 4k((w-e>1&&x.eq(e).aK(x.eq(w))))}};1H 4k((w>0&&x.eq(0).7F(x.eq(w))))}};s.$el.1p(s.1n.2Z&&s.$el.1D(z$q[3O])?z$q[6D]:z$q[3I]).1R(z$q[8x]+(z$q[7o]===s.1n.2F?z$q[hg]:z$q[23])+z$q[hP]+(m?z$q[jJ]:z$q[23])+z$q[jK]+(m||z$q[5W]===s.1n.2F||/(3J|3y|3x)/.1m(i)?z$q[8x]+(z$q[23]===s.1n.2R?z$q[23]:z$q[7s]+s.1n.2R+z$q[6L])+z$q[jO]+l+z$q[d5]+bB[2h(d,10)-1]+z$q[d6]+v+z$q[jP]:z$q[23])+(s.1n.3N?z$q[jR]+(s.$el.1Y(z$q[5F]).1D(z$q[6H])?z$q[jS]:z$q[23])+z$q[jT]+(m?z$q[jU]:z$q[23])+z$q[jV]+g+z$q[jW]+1u+z$q[hP]+(z$q[jX]===s.1n.2F?z$q[jY]:z$q[jZ])+z$q[bg]+a+z$q[bd]+e+z$q[k2]+(z$q[6A]===o?z$q[7e]:z$q[aY]+o+z$q[7t])+z$q[k3]+(-1!=o.1E(z$q[9r])||-1!=o.1E(z$q[k4])?z$q[hI]:z$q[23])+(s.1n.4a?f:z$q[23])+z$q[2i]+1u+z$q[k5]:z$q[23])+z$q[k6]+(m?z$q[k7]:z$q[k8])+z$q[1V]+(s.1n.5Y?z$q[ka]+1u+z$q[9]+(z$q[23]===s.1n.2R?z$q[23]:z$q[7s]+s.1n.2R+z$q[6L])+z$q[kb]+u+z$q[bd]+s.1n.3R+z$q[5J]+u+z$q[2L]+3h+z$q[1V]+u+z$q[2i]+1u+z$q[2W]:z$q[23])+z$q[kd]+(/ke/.1m(i)&&z$q[23]!==s.1n.2R?z$q[kf]+s.1n.2R+z$q[b9]:z$q[23])+z$q[7j]+1u+z$q[9]+(z$q[6]===s.1n.2F||s.$el.1Y(z$q[5F]).1D(z$q[3F])?z$q[kh]:z$q[23])+z$q[4R]+e+z$q[1V]+a+z$q[2i]+1u+z$q[ki]+(s.1n.6b?z$q[kk]+p+z$q[kl]:z$q[23])+z$q[km]+cD.1t(z$q[kn],n).1t(z$q[ko],5n(d).9G()).1t(z$q[kp],5n(l).9G())+z$q[3Q]+(c>0?z$q[kq]+1u+z$q[4R]+e+z$q[kr]+c+z$q[2i]+1u+z$q[2W]:z$q[23])+z$q[2z]+(h&&!s.1n.6J?z$q[23]:z$q[kt]+r+(m&&/5g/.1m(i)||/(3J|3y|3x)/.1m(i)?z$q[ku]+1u+z$q[kv]+e+z$q[kw]+a+z$q[1V]+hE+z$q[2i]+1u+z$q[8e]:z$q[23])+z$q[2z])+z$q[8s])},b=1h(t){1H t=2h(t.1i(z$q[hV])),t>0?t:1};!1h(){l=s.$el;1l e=l.1Y(z$q[aR]);if(s.1n.2l||(s.1n.2l=[],t(z$q[ky]+s.1n.h1+z$q[7t]).1B(1h(){1l e=t.kA(t(1f).2B().1t(/\\n/g,z$q[23]));-1==t.kB(e,s.1n.2l)&&(s.1n.2l[s.1n.2l.1j]=e)}),e.1j||(s.1n.2l=[])),0!==s.1n.2l.1j||s.1n.aS){if(0===s.1n.2l.1j&&e.1j?t(z$q[gZ]+s.1n.aS+z$q[gV]).gT(l):s.1n.aO&&e.1j&&t(z$q[gZ]+s.1n.aO+z$q[gV]).gT(l),0===s.1n.2l.1j){s.1n.2f?t.2Y(u+z$q[kH],1h(e){e=s.1n.2A>e.2v.4i$5b.$t?1:fb(1,e.2v.4i$5b.$t-s.1n.2A),t.2Y(u+z$q[5z]+s.1n.3l+z$q[2L]+s.1n.2A+z$q[aM]+e+z$q[aL],f,z$q[3i])},z$q[3i]):(e=t.2Y(u+z$q[5z]+s.1n.3l+z$q[2L]+s.1n.3n+z$q[8l],f,z$q[3i]),t.gN(e).6l(1h(){s.1n.5d&&s.$el.1p(z$q[c6]).2K(1h(){s.$el.1D(z$q[3O])||s.$el.1v(z$q[3O]);1l e=s.$el.1p(z$q[3K]).1j+1;1H t.2Y(u+z$q[5z]+s.1n.3l+z$q[2L]+s.1n.3n+z$q[aM]+e+z$q[aL],f,z$q[3i]),!1})}))}3b{1W(e=0;e<s.1n.2l.1j;e++){1l a=t.2Y(u+z$q[5z]+s.1n.3l+z$q[gL]+s.1n.2l[e]+z$q[2L]+s.1n.3n+z$q[8l],f,z$q[3i]);s.1n.5H&&s.$el.1p(z$q[bc]).1i(z$q[hB],s.1n.2l[0]),t.gN(a).6l(1h(){s.1n.5d&&s.$el.1p(z$q[c6]).2K(1h(){s.$el.1D(z$q[3O])||s.$el.1v(z$q[3O]);1W(1l e=s.$el.1p(z$q[3K]).1j+1,a=0;a<s.1n.2l.1j;a++){t.2Y(u+z$q[5z]+s.1n.3l+z$q[gL]+s.1n.2l[a]+z$q[2L]+s.1n.3n+z$q[aM]+e+z$q[aL],f,z$q[3i])};1H!1})})}}}}()},s.7u()},t.2H.8E={3R:z$q[23],2A:5,h1:4,3n:6,2l:1w,3l:z$q[66],6M:!0,3N:!0,5Y:!1,6b:!0,6J:!1,8d:!1,2f:!1,2Z:!1,9L:!1,3V:!1,3Y:!1,5H:!1,5f:!1,4a:!1,5d:!1,6f:4,3M:ik,2R:z$q[23],aO:eV,9J:4S,5m:9s,aS:f7,bt:z$q[23],bu:z$q[23],5w:8c,2F:z$q[23]},t.fn.2H=1h(e){1H 1f.1B(1h(){4r t.2H(1f,e)})}}(3j),1h(t){t.6O=1h(e,a){1l s=1f;s.$el=t(e),s.7u=1h(){s.1n=t.6e({},t.6O.8E,a),t.2Y((z$q[23]===s.1n.3R?1I.2q.5A+z$q[6z]+1I.2q.7i:s.1n.3R)+z$q[kR],1h(e){1l a=z$q[23],i=z$q[23],o=e.2v;e=o.4I[0].2o?o.4I[0].2o.$t:s.1n.aE;1l r=o.4I[0].gd$fq.4h.1t(1y[2],z$q[9m]+s.1n.aC+z$q[9o]);if(o.1U&&0!==o.1U.1j){1W(1l a=a+z$q[kW],o=o.1U,n=0,l=0,d=o.1j;d>l;++l){1l c=o[l],p=c.7R.$t,m=c.4I[0].2o?c.4I[0].2o.$t:s.1n.aE,h=c.4I[0].fo?c.4I[0].fo.$t:!1,u=c.4I[0].gd$fq.4h.1t(1y[2],z$q[9m]+s.1n.aC+z$q[9o]),g=c.7Y?c.7Y.$t:c.3M.$t,g=g.1t(/<br *\\/?>|[\\s]+/gi,z$q[9]).1t(/<.*?>|[<>]/g,z$q[23]).1t(1y[11],z$q[23]),g=z$q[23]!==g&&g.1j>s.1n.aA?g.2e(0,s.1n.aA)+z$q[7d]:g,f=!1,v=m===e||u===r;if(!v||s.1n.fl){1W(1l b=0,x=c.2N.1j;x>b;++b){i=c.2N[b],z$q[8Q]==i.6g&&(f=i.3z)};1W(1l i=f.9R(z$q[3t])+1,b=f.9R(z$q[hl]),b=f.2x(z$q[ad]).l0(z$q[9]).2e(i,b)+z$q[7d],x=0,w=c.gd$fk.1j;w>x;++x){if(i=c.gd$fk[x],z$q[l2]==i.2o){p=i.8v;5X}};n<s.1n.fj&&(n++,a+=z$q[l4]+(v?z$q[l5]:z$q[l6])+z$q[1V],a+=s.1n.fi?z$q[2C]+1u+z$q[c2]+h+z$q[l8]+m+z$q[bg]+m+z$q[fh]+u+z$q[fg]+1u+z$q[2M]:z$q[23],a+=z$q[lb]+1u+z$q[lc]+h+z$q[1V]+m+z$q[2i]+1u+z$q[ld]+1u+z$q[le]+f+z$q[1V]+b+z$q[2i]+1u+z$q[lf]+p+z$q[az],a+=z$q[lh]+g+z$q[2z],a+=z$q[li])}};s.$el.1s(a+z$q[2z]),s.1n.fe&&(a=1h(e,a,s){t(z$q[lk]).1B(1h(){t(1f).1s(t(1f).1s().1t(e,z$q[fr]+7v+z$q[ll]+a+z$q[lm]+s+z$q[fu]))})},a(/\\s:\\)\\)+/g,1C.fw,z$q[fy]),a(/\\s;\\(\\(+/g,1C.fz,z$q[fA]),a(/\\s:\\)+/g,1C.fB,z$q[fC]),a(/\\s:-\\)+/g,1C.fD,z$q[fE]),a(/\\s=\\)\\)+/g,1C.fF,z$q[fG]),a(/\\s;\\(+/g,1C.fH,z$q[fI]),a(/\\s;-\\(+/g,1C.fJ,z$q[fK]),a(/\\s:d/gi,1C.fL,z$q[fM]),a(/\\s:-d/gi,1C.fN,z$q[fO]),a(/\\s@-\\)+/g,1C.fP,z$q[fQ]),a(/\\s:p/gi,1C.fR,z$q[fS]),a(/\\s:o/gi,1C.fT,z$q[fU]),a(/\\s:&gt;\\)+/g,1C.fV,z$q[fW]),a(/\\s\\(o\\)+/gi,1C.fX,z$q[fY]),a(/\\s\\[-\\(+/g,1C.fZ,z$q[g0]),a(/\\s:-\\?/g,1C.g1,z$q[g2]),a(/\\s\\(p\\)+/gi,1C.g3,z$q[g4]),a(/\\s:-s/gi,1C.g5,z$q[g6]),a(/\\s\\(m\\)+/gi,1C.g7,z$q[g8]),a(/\\s8-\\)+/gi,1C.g9,z$q[aG]),a(/\\s:-t/gi,1C.ga,z$q[gb]),a(/\\s:-b/gi,1C.gc,z$q[ge]),a(/\\sb-\\(+/gi,1C.gf,z$q[gg]),a(/\\s:-#/gi,1C.gh,z$q[gj]),a(/\\s=p~/gi,1C.gk,z$q[gl]),a(/\\s\\$-\\)+/gi,1C.gn,z$q[gp]),a(/\\s\\(b\\)+/gi,1C.gq,z$q[gr]),a(/\\s\\(f\\)+/gi,1C.gu,z$q[gv]),a(/\\sx-\\)+/gi,1C.gw,z$q[gx]),a(/\\s\\(k\\)+/gi,1C.gz,z$q[gA]),a(/\\s\\(h\\)+/gi,1C.gB,z$q[gC]),a(/\\s\\(c\\)+/gi,1C.gD,z$q[gE]),a(/\\gF/gi,1C.gG,z$q[gH])),8K(s.$el)}3b{s.$el.1s(z$q[ln])}},z$q[3i])},s.7u()},t.6O.8E={3R:z$q[23],fj:1F.bJ,aA:3B,aC:40,fe:bf,fl:eh,aE:z$q[lo],fi:!0,lp:z$q[lq]},t.fn.6O=1h(e){1H 1f.1B(1h(){4r t.6O(1f,e)})}}(3j);1l 7z=z$q[ls].2x(z$q[9]),fc=1h(t){1W(1l e=!1,a=0;a<7z.1j;a++){1l s=z$q[eT]+7z[a],i=z$q[lu]+7z[a]+z$q[b9],o=z$q[lv]+7z[a]+z$q[7H],r=0,n=0,l=0;1W(j=0;3B>j;j++){1l r=t.1E(s,r),d=!0,c=z$q[23];if(-1==r){5X};1l p=t.1E(o,r),m=t.1E(z$q[lx],r);-1!=p&&-1==m||-1!=p&&-1!=m&&m>p?(c=t.2e(r,p+o.1j),c=c.1t(o,z$q[2z]),n=p,l=o.1j):-1==p&&-1!=m||-1!=p&&-1!=m&&p>m?(c=t.2e(r,m+2),c=c.1t(o,z$q[8e]),n=m,l=2):d=!1,d&&(e=!0,c=c.1t(s,i),c=c.1t(z$q[7H],z$q[2M]),t=t.2e(0,r)+c+t.2e(n+l)),r++}};1H e?t:z$q[23]};!1h(t){1h e(e){t(1h(){f1(z$q[as],z$q[lA]+a0+z$q[lB]+1F.hU+z$q[lC],{6l:1h(){1l a=t(z$q[as]).1s().1t(1y[8],z$q[23]);e.1s(a),t(z$q[lD]).1B(1h(){t(1f).1p(z$q[lE]).5L(z$q[lF])}),t(z$q[as]).1s(z$q[23])}})})}1h a(e){t(1h(){f1(z$q[ap],z$q[lH]+1F.hX+z$q[lI]+i8+z$q[lJ],{6l:1h(){1l a=t(z$q[ap]).1s().1t(1y[9],z$q[23]);e.1s(z$q[lK]+a+z$q[2z]),t(z$q[ap]).1s(z$q[23])}})})}1h s(e){1l a=t(z$q[lL]),s=a.2b(z$q[lM]);s.1j&&(a.1R(z$q[lN]),s.1B(1h(){1l e,a,s,i;i=t(1f).1p(z$q[lO]),e=i.1i(z$q[ao]),a=i.1i(z$q[4m]),s=i.1i(z$q[lQ]),i=i.1i(z$q[lR]),t(z$q[lS]+1u+z$q[lT]+s+z$q[lU]+7v+z$q[eU]+a+z$q[fg]+1u+z$q[lW]+1u+z$q[4R]+s+z$q[1V]+e+z$q[2i]+1u+z$q[lX]+i+z$q[8s]).lY(z$q[eQ]),t(1f).2X()})),e.1s(a.1s()),e.2b(z$q[eQ]).1v(z$q[5Z]).4D({4C:!0,4z:3s(),3A:!0,4L:[z$q[23],z$q[23]],5s:8b,4y:!0,5O:!0,4G:!0,9z:z$q[io],ip:z$q[iq],5S:2G,3c:1,5K:2G}),a.2X()}1h i(){!1h(t,e,a){1l s=t.6T(e)[0];t.4g(a)||(t=t.6R(e),t.id=a,t.4h=z$q[m1]+ih+z$q[m2],s.9H.7w(t,s))}(2d,z$q[5G],z$q[m3]),1I.m4=1h(){2V.7u({m5:ib,m6:!0,m7:!0,au:!1,m8:z$q[m9]}),2V.al.ak(z$q[mc],1h(e){t.aj.4u({5y:z$q[9n],2g:e})}),2V.al.ak(z$q[mf],1h(e){t.aj.4u({5y:z$q[9n],2g:e})}),2V.al.ak(z$q[mg],1h(){8K(t(z$q[eH])),t(z$q[eH]).1v(z$q[mi])})}}1h o(e,a,s){1l i,o=e.2e(e.1E(z$q[3t])+1),r=e.2e(e.1E(z$q[mj])+1,e.1E(z$q[mk]));e=o.2x(z$q[8]);1W(1l n=z$q[ml],l=0;l<e.1j;l++){n+=z$q[eG]+e[l]+z$q[1V]+e[l]+z$q[2z]};s.1s(n+z$q[2z]),s.1p(z$q[mn]).7C();1l d=r.1t(/3A/g,z$q[23]),c=/5I/.1m(d);e=/5D/.1m(d);1l p=/4O/.1m(d),m=/6Y/.1m(d),h=/5r/.1m(d),u=/6Q/.1m(d),g=/3V/.1m(d),f=/4P/.1m(d),v=/(?=.*4Q)(?=.*3V).*/.1m(d),b=/(?=.*5g)(?=.*3V).*/.1m(d);f?a.1p(z$q[3S]).3T(z$q[eC]):-1===o.1E(z$q[8])?a.1p(z$q[3S]).1R(z$q[2C]+1u+z$q[mr]+(z$q[82]===o?z$q[23]:z$q[3L]+o)+z$q[2L]+3h+z$q[1V]+8F+z$q[2i]+1u+z$q[2M]).1p(z$q[7L]).3T(z$q[9A]).7X(z$q[2C]+1u+z$q[mv]+(z$q[82]===o?z$q[23]:z$q[3L]+o)+z$q[2L]+3h+z$q[7V]+1u+z$q[2M]):a.1p(z$q[3S]).1p(z$q[7L]).3T(z$q[9A]),i=g?1F.bC:/6I/.1m(d)?1F.6I:/5g/.1m(d)?1F.5g:/5C/.1m(d)?1F.5C:e?1F.5D:c?1F.5I:/8a/.1m(d)?1F.8a:/4Q/.1m(d)?1F.4Q:/7a/.1m(d)?1F.7a:/6Z/.1m(d)?1F.6Z:/5N/.1m(d)?1F.5N:f?1F.4P:p?1F.4O:m?1F.6Y:/4x/.1m(d)?1F.4x:/3X/.1m(d)?1F.3X:/7c/.1m(d)?1F.7c:/4w/.1m(d)?1F.4w:/4N/.1m(d)?1F.4N:/5Q/.1m(d)?1F.5Q:/4c/.1m(d)?1F.4c:/eg/.1m(d)?1F.bF:/3J/.1m(d)?1F.bE:/3y/.1m(d)?1F.by:/3x/.1m(d)?1F.bx:5,o=c?z$q[ef]+d:/ee/.1m(d)?z$q[ed]+d:/2Z/.1m(d)?z$q[eb]+d:/5e/.1m(d)?z$q[ea]+d:h?z$q[e9]+d:u?z$q[e8]+d:/(3y|3J|3x)/.1m(d)?z$q[e7]+d:d,a.1v(o+z$q[mG]).1R(u?z$q[e6]:z$q[23]),s.1v(z$q[e5]),s.1p(z$q[e4]).1B(1h(){1l e=t(1f).2B();t(1f).2H({2A:i,3n:p&&-1!==e.1E(z$q[8])?1:-1!==e.1E(z$q[8])?5:i,5Y:!(!f&&!h),2l:/(3H|2f)/.1m(e)?1w:e.2x(z$q[8]),2F:c?z$q[2]:u?z$q[5W]:f?z$q[6]:/(4O|4N|5Q)/.1m(d)?z$q[9N]:/4x/.1m(d)?z$q[ch]:m?z$q[7o]:z$q[23],6M:!0,3N:!0,3l:3G,5H:!!/e2/.1m(d),3Y:!!/3A/.1m(r),4a:!4T,8d:!!/(3X|5e|4P)/.1m(d),2f:!!/2f/.1m(e),5m:c||h||/3x/.1m(d)?an:/(6Q|e1|3X|4c|4P|5N|3J|3y)/.1m(d)?4S:9s,9J:4S,5f:/e0/.1m(d)?z$q[4X]:/dZ/.1m(d)?z$q[9i]:!1,6J:!!(c||f||/(5r|4w|3X|3J|3y|3x)/.1m(d)),6f:/(4O|4x)/.1m(d)?4:(/4N/.1m(d),5),3M:c||f||m?9g:/4w/.1m(d)?85:/(3J|3y|3x)/.1m(d)?7Z:6q,6b:8j,5d:!!/5d/.1m(d),2Z:!!/(2Z|4Q|5C|5D|4c)/g.1m(d),3V:!!g,9L:!(!v&&!b),5w:8b}),/(6Q|5I|5r|5e)/.1m(d)||t(1f).1R(z$q[2C]+1u+z$q[mP]+(z$q[82]===e?z$q[23]:z$q[3L]+e)+z$q[2L]+3h+z$q[1V]+(z$q[82]===e?8L:8R+z$q[9]+e)+z$q[2i]+1u+z$q[2M])})}1h r(t,r,n){if(1y[13].1m(t)){1l l;l=t.5V(1y[13]);1l d=l[0],c=l[1],p=l[1].1t(/3A/g,z$q[23]);l=4k(0)!==l[2]?l[2]:z$q[23];1l m=/mQ/.1m(l)?l:z$q[23],h=/5I/.1m(p),u=/5D/.1m(p),g=/4O/.1m(p),f=/6Y/.1m(p),v=/5r/.1m(p),b=/6Q/.1m(p),x=/3V/.1m(p),w=/4P/.1m(p),y=/(?=.*4Q)(?=.*3V).*/.1m(p);dY=/(?=.*5g)(?=.*3V).*/.1m(p),w?n.1p(z$q[3S]).3T(z$q[eC]):-1===d.1E(z$q[8])?n.1p(z$q[3S]).1R(z$q[2C]+1u+z$q[mS]+m+z$q[a2]+(z$q[82]===d?z$q[23]:z$q[3L]+d)+z$q[2L]+3h+z$q[1V]+8F+z$q[2i]+1u+z$q[2M]).1p(z$q[7L]).3T(z$q[9A]).7X(z$q[2C]+1u+z$q[4R]+m+z$q[a2]+(z$q[82]===d?z$q[23]:z$q[3L]+d)+z$q[2L]+3h+z$q[7V]+1u+z$q[2M]):n.1p(z$q[3S]).1p(z$q[7L]).3T(z$q[9A]),a1=x?1F.bC:/6I/.1m(p)?1F.6I:/5g/.1m(p)?1F.5g:/5C/.1m(p)?1F.5C:u?1F.5D:h?1F.5I:/8a/.1m(p)?1F.8a:/4Q/.1m(p)?1F.4Q:/7a/.1m(p)?1F.7a:/6Z/.1m(p)?1F.6Z:/5N/.1m(p)?1F.5N:w?1F.4P:g?1F.4O:f?1F.6Y:/4x/.1m(p)?1F.4x:/3X/.1m(p)?1F.3X:/7c/.1m(p)?1F.7c:/4w/.1m(p)?1F.4w:/4N/.1m(p)?1F.4N:/5Q/.1m(p)?1F.5Q:/4c/.1m(p)?1F.4c:/eg/.1m(p)?1F.bF:/3J/.1m(p)?1F.bE:/3y/.1m(p)?1F.by:/3x/.1m(p)?1F.bx:5,dW=h?z$q[ef]+p:/ee/.1m(p)?z$q[ed]+p:/2Z/.1m(p)?z$q[eb]+p:/5e/.1m(p)?z$q[ea]+p:v?z$q[e9]+p:b?z$q[e8]+p:/(3y|3J|3x)/.1m(p)?z$q[e7]+p:p,/#/.1m(l)&&n.2b(z$q[3S]).1Q({2R:l}),n.1v(dW+z$q[mW]).1R(b?z$q[e6]:z$q[23]),r.1v(z$q[e5]),r.2H({3R:m,2A:a1,3n:g&&-1!==d.1E(z$q[8])?1:-1!==d.1E(z$q[8])?5:a1,5Y:!(!w&&!v),2l:/(3H|2f)/.1m(d)?1w:d.2x(z$q[8]),2F:h?z$q[2]:b?z$q[5W]:w?z$q[6]:/(4O|4N|5Q)/.1m(p)?z$q[9N]:/4x/.1m(p)?z$q[ch]:f?z$q[7o]:z$q[23],6M:!0,3N:!0,3l:3G,5H:!!/e2/.1m(p),3Y:!!/3A/.1m(c),4a:!4T,2R:/#/.1m(l)?l:z$q[23],8d:!!/(3X|5e|4P)/.1m(p),2f:!!/2f/.1m(d),5m:h||v||/3x/.1m(p)?an:/(6Q|e1|3X|4c|4P|5N|3J|3y)/.1m(p)?4S:9s,9J:4S,5f:/e0/.1m(p)?z$q[4X]:/dZ/.1m(p)?z$q[9i]:!1,6J:!!(h||w||/(5r|4w|3X|3J|3y|3x)/.1m(p)),6f:/(4O|4x)/.1m(p)?4:(/4N/.1m(p),5),3M:h||w||f?9g:/4w/.1m(p)?85:/(3J|3y|3x)/.1m(p)?7Z:6q,6b:8j,5d:!!/5d/.1m(p),2Z:!!/(2Z|4Q|5C|5D|4c)/.1m(p),3V:!!x,9L:!(!y&&!dY),5w:8b}),/(6Q|5I|5r|5e)/.1m(p)||r.1R(z$q[2C]+1u+z$q[9]+(/#/.1m(l)?z$q[7s]+l+z$q[6L]:z$q[23])+z$q[mX]+m+z$q[a2]+(z$q[82]===d?z$q[23]:z$q[3L]+d)+z$q[2L]+3h+z$q[1V]+(z$q[82]===d?8L:8R+z$q[9]+d)+z$q[2i]+1u+z$q[2M])}3b{1y[14].1m(t)?(n.1v(z$q[9Z]),r.2H({3n:1F.bM})):1y[15].1m(t)?(n.1v(z$q[9Z]),r.2H({2A:1F.bL,2f:!0})):1y[16].1m(t)?(n.1v(z$q[9Z]),d=-1!=t.1E(z$q[3t])?t.1t(1y[17],z$q[23]):z$q[23],r.2H({2A:1F.7B,3n:z$q[23]===d?1F.7B:2,2l:d.2x(z$q[8]),2f:z$q[23]===d})):1y[18].1m(t)?e(r):1y[19].1m(t)?a(r):1y[20].1m(t)?(n.1v(t),r.6O()):1y[21].1m(t)&&(n.1v(t),s(r))};1y[22].1m(t)&&(d=t.1t(1y[23],z$q[23]),n.1v(z$q[mZ]),r.1s(z$q[n0]+d+z$q[n1]),i()),/n2/g.1m(t)&&o(t,n,r),n.1v(z$q[9W])}1h n(){t(z$q[5R]).1R(z$q[n4]);1W(1l e=t(z$q[dQ]),a=9j(2d.4H),s=9j(2q.3z),i=t(z$q[9V]).6X().1i(z$q[4b]),o=z$q[n8],a=[{2o:z$q[n9],2P:z$q[dI],2g:z$q[nc]+s},{2o:z$q[nd],2P:z$q[ii],2g:z$q[ne]+s+z$q[9S]+a},{2o:z$q[ng],2P:z$q[aU],2g:z$q[nh]+a+z$q[ni]+s+z$q[nj]},{2o:z$q[nk],2P:z$q[aT],2g:z$q[nl]+s+z$q[9S]+a},{2o:z$q[nm],2P:z$q[nn],2g:z$q[no]+s+z$q[6j]+a},{2o:z$q[nq],2P:z$q[aQ],2g:z$q[nr]+s+z$q[ns]+i+z$q[nt]+a},{2o:z$q[nu],2P:z$q[dI],2g:z$q[nv]+a+z$q[nw]+s+z$q[nx]},{2o:z$q[ny],2P:z$q[nz],2g:z$q[nA]+s+z$q[6j]+a},{2o:z$q[nB],2P:z$q[aI],2g:z$q[nC]+s+z$q[6j]+a},{2o:z$q[nD],2P:z$q[nE],2g:z$q[nF]+s+z$q[9S]+a},{2o:z$q[nG],2P:z$q[nH],2g:z$q[nI]+s+z$q[6j]+a},{2o:z$q[nJ],2P:z$q[nK],2g:z$q[nL]+s+z$q[9S]+a},{2o:z$q[nM],2P:z$q[nN],2g:z$q[nO]+s+z$q[6j]+a},{2o:z$q[nP],2P:z$q[nQ],2g:z$q[nR]+s},{2o:z$q[nS],2P:z$q[aJ],2g:z$q[nT]+s+z$q[6j]+a},{2o:z$q[nU],2P:z$q[nV],2g:z$q[nX]+a+z$q[9]+s}],s=0;s<a.1j;s++){o+=z$q[nY]+1u+z$q[nZ]+a[s].2P+z$q[bd]+a[s].2g+z$q[bg]+a[s].2o+z$q[o0]+a[s].2P+z$q[o1]+a[s].2o+z$q[dG]+1u+z$q[8e]};e.1R(o+z$q[2z])}1h l(t,e,a){1l s=t.2b(z$q[o3]),i=t.3E().3d,o=t.2J()-s.2J()+i,r=s.2J()+z$q[4t],n=e;t.2b(z$q[dF]).1j&&(n=t.2b(z$q[dF]).o5(!0)+15,i+=n),i>a?s.1Z(z$q[b0]).1Q({5q:z$q[dD],3d:n}):a>o?s.1Z(z$q[b0]).1Q({5q:z$q[dD],o8:z$q[4A],3d:z$q[dC]}):s.1v(z$q[b0]).1Q({3d:e,2J:r})}t(z$q[oa]).1B(1h(){1l e=t(1f).1s(),e=fc(e);z$q[23]!=e&&t(1f).1s(e)}),t(z$q[dB]).1B(1h(){t(1f).1p(z$q[dA]).1B(1h(){1l e=t(1f).1i(z$q[4]),a=t(1f).1i(z$q[9U]),s=z$q[9Y]+(1w==a||z$q[23]==a?z$q[23]:z$q[a3]+a)+z$q[6K],i=t(1f).1s();t(1f).1s(1w==i||z$q[23]==i?z$q[og]:i).1i({\"\\O\\D\\E\\D\\P\\E\\D\\1d\":(1w==a||z$q[23]==a?z$q[23]:s)+(1w==e||z$q[23]==e?z$q[oh]:e),4H:z$q[23]})})}),t(z$q[dB]).7C({9f:1,fx:z$q[4X],dv:6h,du:6h}),t(z$q[ok]).1B(1h(){1l e=z$q[23];t(1f).1p(z$q[9M]).1B(1h(){1l a=t(1f).1i(z$q[4]),s=t(1f).1i(z$q[9U]),i=z$q[9Y]+(1w==s||z$q[23]==s?z$q[23]:z$q[a3]+s)+z$q[6K],o=t(1f).1s();e+=z$q[om]+(1w==s||z$q[23]==s?z$q[23]:i)+(1w==a||z$q[oo]==a?z$q[23]:a)+z$q[op]+(z$q[oq]+(1w==o||z$q[23]==o?z$q[or]:o)+z$q[2z])}),t(1f).1s(e),t(1f).2b(z$q[os]).6X().1v(z$q[a4]),t(1f).2b(z$q[dq]).6X().8q()}),t(z$q[ov]).2K(1h(){t(1f).5x(z$q[dq]).1v(z$q[dp]).oy(z$q[do]).a7(z$q[oB]).1Z(z$q[dp]).ag(z$q[do]),t(1f).oC(z$q[a4]),t(1f).a7(z$q[oD]).1Z(z$q[a4])}),t(z$q[oE]).1B(1h(){1l e=t(1f),a=e.1i(z$q[dC]),s=e.1i(z$q[4b]),i=e.1i(z$q[dm]),o=e.1i(z$q[3U]),r=e.1i(z$q[7T]),n=e.1i(z$q[7S]),l=e.1i(z$q[oI]),d=e.1i(z$q[dj]),c=e.1i(z$q[oK]),p=e.1i(z$q[di]);e.3r(z$q[oM]+(1w==r||z$q[23]==r||z$q[4A]==r?z$q[23]:z$q[6U])+z$q[a8]+(1w==o||z$q[23]==o?z$q[9T]:o)+z$q[7M]+(1w==n||z$q[23]==n?z$q[oR]:n)+z$q[oS]+(1w==p||z$q[23]==p?z$q[oT]:1==p?z$q[oU]:p)+z$q[3t]+(1w==s||z$q[23]==s?z$q[oV]:s)+z$q[oW]+(1w==i||z$q[23]==i?z$q[oX]:i)+z$q[oY]+(1w==a||z$q[23]==a?z$q[ac]:a)+z$q[p0]+(1w==d||z$q[23]==d?z$q[ac]:d)+z$q[p1]+(1w==c||z$q[23]==c?z$q[p2]:c)+z$q[p3]+(1w==l||z$q[23]==l?z$q[ac]:l)+z$q[p4])}),t(z$q[p5]).1B(1h(){1l e=t(1f),a=e.1i(z$q[p6]),s=e.1i(z$q[p7]),i=e.1i(z$q[dm]),o=e.1i(z$q[4b]),r=e.1i(z$q[3U]),n=e.1i(z$q[7T]),l=e.1i(z$q[7S]),d=e.1i(z$q[d3]),c=e.1i(z$q[p9]);e.3r(z$q[pa]+(1w==n||z$q[23]==n||z$q[4A]==n?z$q[23]:z$q[6U])+z$q[pb]+(1w==r||z$q[23]==r?z$q[9T]:r)+z$q[7M]+(1w==l||z$q[23]==l?z$q[pc]:l)+z$q[pd]+(1w==o||z$q[23]==o?z$q[pe]:o)+z$q[pf]+(1w==c||z$q[23]==c?z$q[9w]:c)+z$q[ph]+(1w==d||z$q[23]==d?z$q[9w]:d)+z$q[pi]+(1w==a||z$q[23]==a?z$q[pj]:a)+z$q[pk]+(1w==i||z$q[23]==i?z$q[pl]:i)+z$q[pm]+(1w==s||z$q[23]==s?z$q[pn]:s)+z$q[po])}),t(z$q[pp]).1B(1h(){1l e=t(1f),a=e.1i(z$q[4b]),s=e.1i(z$q[3U]),i=e.1i(z$q[7S]),o=e.1i(z$q[d3]),r=e.1i(z$q[7T]),n=e.1i(z$q[pq]),l=e.1i(z$q[di]),d=e.1i(z$q[pr]);e.3r(z$q[ps]+(1w==r||z$q[23]==r||z$q[4A]==r?z$q[23]:z$q[6U])+z$q[a8]+(1w==s||z$q[23]==s?z$q[9T]:s)+z$q[7M]+(1w==i||z$q[23]==i?z$q[d0]:i)+z$q[pu]+(1w==a||z$q[23]==a?z$q[pv]:a)+z$q[pw]+(1w==l||z$q[23]==l?z$q[23]:l)+z$q[px]+(1w==d||z$q[23]==d?z$q[4A]:d)+z$q[py]+(1w==n||z$q[23]==n?z$q[9w]:n)+z$q[pz]+(1w==o||z$q[23]==o?z$q[9w]:o)+z$q[pA])}),t(z$q[pB]).1B(1h(){1l e=t(1f),a=e.1i(z$q[4b]),s=e.1i(z$q[3U]),i=e.1i(z$q[7T]),o=e.1i(z$q[7S]);e.3r(z$q[pC]+(1w==i||z$q[23]==i||z$q[4A]==i?z$q[23]:z$q[6U])+z$q[a8]+(1w==s||z$q[23]==s?z$q[9T]:s)+z$q[7M]+(1w==o||z$q[23]==o?z$q[d0]:o)+z$q[pD]+(1w==a||z$q[23]==a?z$q[23]:a)+z$q[pE])}),t(z$q[pF]).1v(z$q[pG]),t(z$q[pH]).1B(1h(){1l e=t(1f).1i(z$q[4]),a=t(1f).1i(z$q[9U]),s=z$q[9Y]+(1w==a||z$q[23]==a?z$q[23]:z$q[a3]+a)+z$q[6K],i=t(1f).1s();1w==e&&(e=z$q[23]),z$q[23]!=e&&(e=z$q[pI]+(1w==a||z$q[23]==a?z$q[23]:s)+e+z$q[2z]),t(1f).1s(z$q[pJ]+e+(1w==i?z$q[23]:i)+z$q[2z])}),t(z$q[pK]).1B(1h(){1l e=t(1f),a=e.1i(z$q[4b]),s=e.1i(z$q[9u]),i=e.1i(z$q[pM]),o=z$q[pN]+s+z$q[b9],r=e.1i(z$q[3U]),n=e.1i(z$q[7T]),l=e.1i(z$q[7S]);e.3r(z$q[cX]+(1w==s||z$q[23]==s?z$q[23]:z$q[2C]+1u+z$q[pP]+(1w==n||z$q[23]==n||z$q[4A]==n?z$q[23]:z$q[6U])+z$q[6L]+(1w==s||z$q[23]==s?z$q[23]:o)+z$q[pQ]+(1w==i||z$q[23]==i?z$q[23]:i)+z$q[1V])+z$q[pR]+(1w==n||z$q[23]==n||z$q[4A]==n?z$q[23]:z$q[6U])+z$q[pS]+(1w==r||z$q[23]==r?z$q[23]:r)+z$q[7M]+(1w==l||z$q[23]==l?z$q[23]:l)+z$q[fh]+(1w==a||z$q[23]==a?z$q[9q]:a)+z$q[pU]+(1w==s||z$q[23]==s?z$q[23]:z$q[2i]+1u+z$q[2M])+z$q[cX])}),t(z$q[j0]).1B(1h(){t(1f).2b(z$q[cS]).2X()}),t(z$q[pX]).1B(1h(){1l e=t(1f).1i(z$q[pY]),a=t(1f).1s(),e=z$q[pZ]+(1w==e||z$q[23]==e?z$q[q0]:e)+z$q[1V]+(1w==a||z$q[23]==a?z$q[q1]:a)+z$q[q2];t(1f).3r(e)});1W(1l d=2d.6T(z$q[q3]),c=d.1j,p=0;c>p;p++){d[p].4J=z$q[q4]+d[p].4J+z$q[q5];1W(1l m=d[p].4J.2x(/\\n/).1j,h=0;m>h;h++){d[p].6T(z$q[q6])[0].4J+=z$q[ae]+(h+1)+z$q[3Q]}};t(z$q[q8]).1B(1h(){t(1f).1s(t(z$q[q9]).1s())}),t(z$q[qa]).1B(1h(){1l e=t(1f).1i(z$q[9u]),a=t(1f).1i(z$q[4]),s=t(1f).1s(),e=z$q[2C]+1u+z$q[4R]+(1w==e||z$q[23]==e?z$q[qb]:e)+z$q[qc]+(1w==a||z$q[23]==a?z$q[qd]:a)+z$q[ae]+(1w==s||z$q[23]==s?z$q[qe]:s)+z$q[dG]+1u+z$q[2M];t(1f).3r(e)}),t(z$q[qf]).1B(1h(){1l e=z$q[23];t(1f).1p(z$q[9M]).1B(1h(){1l a=t(1f).1i(z$q[4]),s=t(1f).1i(z$q[9u]),i=t(1f).1i(z$q[4b]),o=t(1f).1s();e+=z$q[qg]+1u+z$q[cO]+i+z$q[cL]+(1w==s||z$q[23]==s?i:s)+z$q[7V]+1u+z$q[cI]+(1w==a||z$q[23]==a?z$q[23]:z$q[cH]+1u+z$q[4R]+(1w==s||z$q[23]==s?i:s)+z$q[1V]+a+z$q[2i]+1u+z$q[cG])+(z$q[23]==o?z$q[23]:z$q[cF]+o+z$q[bn])+z$q[8s]}),t(1f).1s(e),t(1f).4D({4C:!0,4z:3s(),3A:!0,4L:[z$q[23],z$q[23]],5s:8c,4y:!0,5O:!0,4G:!0,5S:2G,3c:1,5K:2G})}),t(z$q[qn]).1B(1h(){1l e=z$q[23],a=t(1f);a.1p(z$q[9M]).1B(1h(){1l a=t(1f).1i(z$q[4]),s=t(1f).1i(z$q[9u]),i=t(1f).1i(z$q[4b]),o=t(1f).1s();e+=z$q[qo]+1u+z$q[cO]+i+z$q[cL]+(1w==s||z$q[23]==s?i:s)+z$q[7V]+1u+z$q[cI]+(1w==a||z$q[23]==a?z$q[23]:z$q[cH]+1u+z$q[4R]+(1w==s||z$q[23]==s?i:s)+z$q[1V]+a+z$q[2i]+1u+z$q[cG])+(z$q[23]==o?z$q[23]:z$q[cF]+o+z$q[bn])+z$q[8s]}),a.1s(e),a.4D({3A:!0,8h:2,4y:!0,5s:8c,4z:3s(),4C:!0,4G:!0,ix:a,4L:[z$q[23],z$q[23]],iA:{0:{3c:1},a5:{3c:2},c2:{3c:3},5B:{3c:4}}})}),t(z$q[qp]).1B(1h(){1l e=t(1f);e.1s(e.1s().1t(/&ab;/g,z$q[23])),e.2b(z$q[cS]).2X(),e.1p(z$q[9M]).1B(1h(){1l e=t(1f),a=e.1i(z$q[qq]),a=5n(1w==a||z$q[23]==a?0:a),s=e.1s();e.3r(z$q[qr]+(1w==s||z$q[23]==s?z$q[qs]:s)+z$q[ae]+a+z$q[qt]+a+z$q[qu]+10*a+z$q[qv])}),e.1p(z$q[dA]).1B(1h(){1l e=t(1f),a=e.1i(z$q[4]),s=e.1i(z$q[hh]),i=e.1s();e.3r(z$q[qw]+(1w==a||z$q[23]==a?z$q[qx]:a)+z$q[qy]+(1w==i||z$q[23]==i?z$q[qz]:i)+z$q[qA]+(1w==s||z$q[23]==s?z$q[qB]:s)+z$q[qC])});1l a=e.1p(z$q[cE]),s=a.1j,i=0;a.1B(1h(){i+=2h(t(1f).1i(z$q[qE]))}),a=(i/s).7n(1),e.1p(z$q[qF]).1s(a),e.1p(z$q[qG]).1Q(z$q[3U],10*a+z$q[ck])});1l u=t(1I).2J();t(z$q[4Z]).1B(1h(){1l e=t(1f),a=e.2b(z$q[7G]),s=a.2B(),i=0.1*t(1f).2J()-u+e.3E().3d,o=t(2d).4p();e.1D(z$q[9W])||o>i&&r(s,a,e)});1l g,f;if(t(z$q[qI]).on(z$q[3f],1h(e){2q.bA.1t(/^\\//,z$q[23])==1f.bA.1t(/^\\//,z$q[23])&&2q.b5==1f.b5&&(g=t(1f.cB),g=g.1j?g:t(z$q[qK]+1f.cB.4F(1)+z$q[7H]),g.1j&&(z$q[qL]==7P 2d.6i.6C.qM?(e.cA(),e=t(2d).2J()-t(1I).2J(),f=g.3E().3d,f>e&&(f=e),t(z$q[0]).1Q({\"\\U\\D\\G\\1e\\F\\L\\P\\E\\H\\R\":t(1I).4p()-f+z$q[4t],qO:z$q[qP]}).aq(z$q[ar],!0)):t(z$q[6S]).7K({4p:f},5B)))}),t(z$q[0]).on(z$q[qS],1h(e){e.9h==e.qU&&!0===t(1f).aq(z$q[ar])&&(t(1f).8Y(z$q[7q]).aq(z$q[ar],!1),t(z$q[6S]).4p(f))}),t(z$q[5h]).1D(z$q[6t])||t(z$q[5h]).1D(z$q[cv])){if(t(z$q[a6]).7C({9f:1,fx:z$q[4X],dv:6h,du:6h}),t(z$q[qX]).c9(z$q[qY]),t(z$q[qZ]).3T(z$q[r0]+t(z$q[r1]).2B()+z$q[r2]),1==t(z$q[r3]).1j&&t(z$q[r4]).3P(),n(),t(z$q[r5]).1j&&(d=t(z$q[r6]),c=t(z$q[r7]),p=t(z$q[r8]),d.2B().1t(/(\\r\\n|\\n|\\r)/gm,z$q[23])==c.2B().1t(/(\\r\\n|\\n|\\r)/gm,z$q[23])&&(d.1s(c.1s()),c.3k().2X()),p.1j&&(t(z$q[ra]).1s(p.1s()),p.3k().2X())),0<t(z$q[cs]).1j&&t(z$q[5h]).1D(z$q[6t])&&(t(z$q[rc]).1B(1h(){1l e=t(1f).1s().1t(/\\{rd\\#/,z$q[re]).1t(/\\}/,z$q[rf]).1t(/\\{/g,z$q[2C]+1u+z$q[rg]).1t(/\\#/g,z$q[rh]).1t(/\\}/g,z$q[7V]+1u+z$q[2M]);t(1f).1s(e);1W(1l e=t(1f).2b(z$q[ri]),a=0;a<e.1j;a+=e.1j+1){e.4F(a,a+e.1j+1).5L(z$q[rj])}}),t(z$q[cs]).1B(1h(){1l e=/(\\r\\n|\\n|\\r)/gm,a=t(z$q[cr]).1j?t(z$q[cr]).2B().1t(e,z$q[23]):z$q[rl],s=t(1f),e=s.1p(z$q[7L]).1s().1t(e,z$q[23]),i=s.1p(z$q[7G]).1s().1t(1y[10],z$q[23]);s.1p(z$q[rm]).1s(),s=s.1p(z$q[rn]).1s(),a===e&&(z$q[23]===t(z$q[cq]).1s()&&t(z$q[cq]).1s(i),t(z$q[rp]).1s(s))})),t(z$q[rq]),d=t(z$q[2n]).1s(),c=t(z$q[rr]),t(z$q[8C]).2y(),t(z$q[ay]).2y(),/\\[2S-3W\\]/.1m(d)?(t(z$q[2n]).1s(d.1t(/\\[2S-3W\\]/,z$q[23])),t(z$q[7y]).1v(z$q[ru])):/\\[8W-3W\\]/.1m(d)?(t(z$q[2n]).1s(d.1t(/\\[8W-3W\\]/,z$q[23])),t(z$q[7y]).1v(z$q[rw])):/\\[2S-8V\\]/.1m(d)?(t(z$q[2n]).1s(d.1t(/\\[2S-8V\\]/,z$q[23])),t(z$q[7y]).1v(z$q[ry])):/\\[8W-8V\\]/.1m(d)?(t(z$q[2n]).1s(d.1t(/\\[8W-8V\\]/,z$q[23])),t(z$q[7y]).1v(z$q[rz])):/\\[iP-3W\\]/.1m(d)&&(t(z$q[2n]).1s(d.1t(/\\[iP-3W\\]/,z$q[23])),t(z$q[7y]).1v(z$q[rB])),d=t(z$q[2n]).1s(),/\\[iO-3W\\]/.1m(d)&&(t(z$q[2n]).1s(d.1t(/\\[iO-3W\\]/,z$q[rD])),t(z$q[rE]).1s(c.aB())),d=t(z$q[2n]).1s(),t(z$q[iM]).1j&&!/\\[aD\\]/.1m(d)&&(t(z$q[2n]).7F(z$q[rI]+(aF?z$q[iJ]:z$q[23])+z$q[rK]+(aF?z$q[rL]:z$q[23])+z$q[az]),t(z$q[rM]).1s(t(z$q[iM]).aB()),!aa&&t(z$q[9p]).1j&&(t(z$q[rN]).3T(z$q[rO]+t(z$q[9p]).1s()+z$q[2z]),t(z$q[9p]).2X()),t(z$q[iF]).1j&&(c=t(z$q[rQ]).1j?3:8,t(z$q[iF]).2H({2A:c,3n:9,3N:!1,6M:!1,2f:z$q[4s]===b6,2l:/(3H|2f)/.1m(b6)?[]:1w,6b:!1}))),t(z$q[iC]).1j&&!/\\[rT\\]/.1m(d)&&(t(z$q[rU]).7F(z$q[rV]+(aX?z$q[iJ]:z$q[23])+z$q[1V]+(aX?z$q[rW]:z$q[23])+z$q[rX]),t(z$q[rY]).1s(t(z$q[iC]).aB()),t(z$q[iB]).1j&&t(z$q[iB]).2H({2A:8,3n:9,3l:3G,3N:!1,6M:!1,2f:z$q[4s]===bh,2l:/(3H|2f)/.1m(bh)?[]:1w,6b:!1})),/\\[(aD|iw)\\]/.1m(d)&&t(z$q[2n]).1s(d.1t(/\\[(aD|iw)\\]/g,z$q[23])),d=t(z$q[2n]).1s(),/\\[5x\\]/.1m(d)){t(z$q[6a]).3T(z$q[s1]),t(z$q[2n]).3T(z$q[s2]).1R(z$q[s3]),d=t(z$q[2n]).1s(),t(z$q[2n]).1s(d.1t(/\\[s4\\]/g,z$q[s5]).1t(/\\[5x\\]/g,z$q[s6]).1t(/\\[s7\\]/g,z$q[2z]));1l v=t(z$q[6a]);1W(6N=v.1p(z$q[2n]),ir=6N.2b().sc(),ie=4e.se(ir/1),8G=v.1p(z$q[sg]),7p=v.1p(z$q[si]),b1=v.1p(z$q[sk]),7p.4E(0),b1.4E(1),d=z$q[sl],c=0;ie>c;){d+=z$q[sm]+c+z$q[sn]+c+z$q[1V]+(c+1)+z$q[8n],c++};8G.1s(d+z$q[so]),8G.1p(z$q[sp]).1v(z$q[b3]),6N.2b().1Q(z$q[6r],z$q[b4]),6N.2b().4F(0,1).1Q(z$q[6r],z$q[6q]);1l b=1h(e){1l a=2h(b1.4E());b8=e*a,hG=b8+a,6N.2b().1Q(z$q[6r],z$q[b4]).4F(b8,hG).1Q(z$q[6r],z$q[6q]),v.1p(z$q[su]+e+z$q[7H]).1v(z$q[b3]).a7(z$q[bi]).1Z(z$q[b3]),7p.4E(e),t(z$q[6S]).7K({4p:t(z$q[2n]).3E().3d-80},5B)};v.1p(z$q[sw]).on(z$q[3f],1h(){1l t=v.1p(z$q[bi]);1H 8k=2h(7p.4E())-1,1==t.sz(z$q[bk]).1j&&b(8k),!1}),v.1p(z$q[sB]).on(z$q[3f],1h(){1l t=v.1p(z$q[bi]);1H 8k=2h(7p.4E())+1,1==t.5x(z$q[bk]).1j&&b(8k),!1}),v.1p(z$q[bk]).on(z$q[3f],1h(){1l e=t(1f).1i(z$q[ao]);1H b(e),!1}),v.1p(z$q[sC]).on(z$q[3f],1h(){1H t(1f).1i(z$q[ao]),6N.2b().1Q(z$q[6r],z$q[6q]),8G.3P(),t(z$q[6S]).7K({4p:t(z$q[2n]).3E().3d-80},5B),!1})};t(z$q[2n]).1B(1h(){1l e=[],a=t(1f).1s(),s=t(z$q[6a]).1i(z$q[hw]),i=t(z$q[sD]).1i(z$q[8Z]),o=/\\[hx\\]/g,r=/\\[\\/hx\\]/g;o.1m(a)&&r.1m(a)&&(z$q[hu]==6x(z$q[hq]+s)?(a=a.1t(o,z$q[23]).1t(r,z$q[23]),t(1f).1s(a)):(t(1f).1s(t(1f).1s().1t(o,z$q[sH]).1t(r,z$q[sI])),t(1f).1p(z$q[sJ]).1B(1h(){e.8X(t(1f).1s()),t(1f).3r(z$q[sK]+i+z$q[sL])}),t(2d).on(z$q[9n],1h(i){if(z$q[8T]!=7P i){1l o=1I.2q.3z;if((i=i.2g)&&(-1!=i.1E(o)||-1!=o.1E(i))){a=t(z$q[sM]).1s();1l r=0;t(z$q[sN]).1B(1h(){z$q[8T]!=7P e[r]&&t(1f).3r(e[r]),r++}),9a(z$q[hq]+s,z$q[hu])}}})))}),t(z$q[sO]).1j&&(1I.bl=1h(t,e,a){1l s,i=t.6T(e)[0];1H t.4g(a)?4k(0):(t=t.6R(e),t.id=a,t.4h=z$q[sQ],i.9H.7w(t,i),1I.bl||(s={ho:[],c7:1h(t){s.ho.8X(t)}}))}(2d,z$q[5G],z$q[sS]),bl.c7(1h(e){e.sT.7h(z$q[sV],1h(e){t.aj.4u({5y:z$q[9n],2g:e.9h.sW})})})),(t(z$q[sX]).1j||t(z$q[sY]).1j)&&i(),t(z$q[9V]).1B(1h(){1l e=t(1f),a=e.1i(z$q[4]),s=e.3k(z$q[5M]),i=e.1Y(z$q[hk]);1w==a&&z$q[23]==a||!/\\{5r\\}/.3q(a)||(e.1i(z$q[4],a.1t(/\\{5r\\}/,z$q[23])),s.1j?s.1v(z$q[hj]):e.1v(z$q[hj]),i.1j&&(i.1v(z$q[bm]),e=i.1p(z$q[hf]).2B(),i.1p(z$q[he]).1R(z$q[t4]+e+z$q[3Q])))}),c=t(z$q[2n]).1s(),d=[],d=/<bS\\s+[^>]*4h=\"([^\"]*)\"[^>]*>/.3q(c),c=t(z$q[he]),c.1j?(c.1B(1h(){t(z$q[7g]).1R(t(1f))}),1<c.1j&&(t(z$q[7g]).1v(z$q[7W]).7X(z$q[t6]),t(z$q[t7]).4D({4C:!0,4z:3s(),4L:[z$q[23],z$q[23]],4y:!0,5O:!0,4G:!0,5S:2G,3c:1,5K:2G}).1v(z$q[5Z])),t(z$q[6G]).1v(z$q[hc]),t(z$q[7g]).1v(z$q[7W])):1w!=d&&aG>=d.t9&&cZ&&(c=t(z$q[9V]).6X(),p=c.3k(z$q[5M]),d=c.1Y(z$q[hk]),m=c.1Y(z$q[ta]),h=c.1Y(z$q[tb]),m.1j||(t(z$q[7g]).1R(p.1j?p:c),h.1v(z$q[bm]),d.1j&&(c=d.1p(z$q[hf]).2B(),t(z$q[tc]).1R(z$q[td]+c+z$q[3Q]),d.1v(z$q[bm])),t(z$q[hb]).1j&&t(z$q[hb]).8Y(z$q[7q]),d=t(z$q[ha]).1i(z$q[4b]),t(z$q[ha]).1i(z$q[4b],d.1t(1y[7],z$q[hH])),t(z$q[7g]).1v(z$q[7W]),t(z$q[6G]).1v(z$q[hc])))};t(z$q[tg]).1B(1h(){t(1f).1s(t(1f).1s().1t(1y[11],z$q[23]))});1l x=t(z$q[5R]),w=t(z$q[th]),y=t(z$q[dQ]);t(z$q[ti]).2K(1h(){1H w.1D(z$q[9Q])||(w.1v(z$q[9Q]),x.1v(z$q[7f])),!1}),t(z$q[tl]).2K(1h(){1H w.1Z(z$q[9Q]),x.1Z(z$q[7f]),!1}),t(z$q[tm]).2K(1h(){1H y.1D(z$q[tn])||(y.1v(z$q[bo]),x.1v(z$q[7f])),!1}),t(z$q[tp]).2K(1h(){1H y.1Z(z$q[bo]),x.1Z(z$q[7f]),!1}),t(2d).on(z$q[3f],1h(e){t(e.9h).is(z$q[tr])||(w.1Z(z$q[9Q]),y.1Z(z$q[bo]),x.1Z(z$q[7f]))}),t(z$q[5R]).1R(z$q[ts]),t(z$q[tt]).1B(1h(){1l e=t(1f);e.1Y(z$q[5F]),e=e.1s(),t(z$q[tu]).1R(e)}),t(z$q[tv]).tw(z$q[c8],1h(){1l e=t(1f),a=e.1p(z$q[4o]),s=e.1Y(z$q[bG]),i=a.2B();if(/f3/g.1m(i)){i=i.1t(/f3\\//g,z$q[23]),e.1v(z$q[7J]),a.2H({2A:4,2f:z$q[4s]===i,5m:4S,3N:!s.1j,3l:3G,4a:!4T,5Y:!!/(3H|2f)/.1m(i),2l:/(3H|2f)/.1m(i)?1w:i.2x(z$q[8])}),a.1R(z$q[2C]+1u+z$q[eX]+(z$q[4s]===i?z$q[bH]:z$q[23])+z$q[bI]+(z$q[82]===i?z$q[23]:z$q[3L]+i)+z$q[2L]+3h+z$q[bK]+1u+z$q[2M]).1v(z$q[tE])}3b{if(/eE/g.1m(i)){s=e.1Y(z$q[bG]),i=i.1t(/eE\\//g,z$q[23]),e.1v(z$q[7J]),a.2H({2A:9,2f:z$q[4s]===i,4a:!4T,3l:3G,3Y:8w,2F:s.1j?z$q[23]:z$q[5W],5Y:!!/(3H|2f)/.1m(i),2l:/(3H|2f)/.1m(i)?1w:i.2x(z$q[8])}).1v(z$q[tG]),a.1R(z$q[tH]+(z$q[4s]===i?z$q[bH]:z$q[23])+z$q[bI]+(z$q[82]===i?z$q[23]:z$q[3L]+i)+z$q[2L]+3h+z$q[tI]).1v(z$q[tJ])}3b{if(/eD/g.1m(i)){1W(1l i=i.1t(/eD\\//g,z$q[23]),i=i.2x(z$q[8]),o=z$q[tL],r=0;r<i.1j;r++){o+=z$q[eG]+i[r]+z$q[1V]+i[r]+z$q[2z]};a.1s(o+z$q[2z]),a.1p(z$q[tM]).7C({9f:1,fx:z$q[4X]}),e.1v(z$q[7J]),a.1p(z$q[e4]).1B(1h(){1l e=t(1f).2B();t(1f).2H({2A:4,5m:4S,3l:3G,3N:!s.1j,4a:!4T,2l:e.2x(z$q[8])}),t(1f).1R(z$q[2C]+1u+z$q[tN]+e+z$q[2L]+3h+z$q[bK]+1u+z$q[2M])}),a.1v(z$q[tO])}3b{/ep/g.1m(i)?(i=i.1t(/ep\\//g,z$q[23]),e.1v(z$q[7J]),a.2H({2A:7,2f:z$q[4s]===i,3n:/(3H|2f)/.1m(i)||1==i.2x(z$q[8]).1j?7:4,2l:/(3H|2f)/.1m(i)?1w:i.2x(z$q[8]),2Z:!0,3l:3G,3N:!s.1j,4a:!4T,3M:3B}),a.1R(z$q[2C]+1u+z$q[eX]+(z$q[4s]===i?z$q[bH]:z$q[23])+z$q[bI]+(z$q[82]===i?z$q[23]:z$q[3L]+i)+z$q[2L]+3h+z$q[bK]+1u+z$q[2M]).1v(z$q[tQ])):/tR/g.1m(i)&&(e.1v(z$q[7J]),a.1s(z$q[23]),a.1v(z$q[tS]),e=t(z$q[tT]),t(z$q[tU]).3P(),e.1B(1h(){1l e=t(1f).2b(z$q[3S]).1s(),s=t(1f).2b(z$q[7G]).1s();a.1R(z$q[tV]+e+z$q[tW]+s+z$q[az])}),a.1p(z$q[7G]).1B(1h(){if(bO=t(1f).2B(),/en/g.1m(bO)){1l e=bO.1t(/en\\//g,z$q[23]).1t(/(\\r\\n|\\n|\\r)/gm,z$q[23]);t(1f).2H({2A:4,2f:z$q[4s]===e,5Y:!!/(3H|2f)/.1m(e),4a:!4T,3Y:8w,3l:3G,3N:!s.1j,2F:s.1j?z$q[23]:z$q[5W],2l:/(3H|2f)/.1m(e)?1w:e.2x(z$q[8])});1l a=t(1f).3k(z$q[tZ]);a.1v(z$q[u0]),z$q[4s]!==e&&(a.1p(z$q[u1]).7X(z$q[u2]+(z$q[82]===e?z$q[23]:z$q[3L]+e)+z$q[2L]+3h+z$q[u3]),a.1p(z$q[3S]).1R(z$q[u4]+(z$q[82]===e?z$q[23]:z$q[3L]+e)+z$q[2L]+3h+z$q[1V]+8F+z$q[8n]))}}))}}}}),t(z$q[u5]).2K(1h(){1l e=t(1f).3k(z$q[4o]).2b(z$q[7N]);1H e.is(z$q[u6])?(e.eF(),t(1f).1v(z$q[3e])):(e.ag(),t(1f).1Z(z$q[3e])),!1});1l k=z$q[2C]+1u+z$q[u7]+d1+z$q[ek]+1u+z$q[2M],$=z$q[2C]+1u+z$q[u9]+cQ+z$q[ek]+1u+z$q[2M],C=1h(e,a,s,i){s=i.7R.$t.5V(/\\d+/g);1l o,r;s=4r 6y(s[0],s[1]-1,s[2],s[3],s[4],s[5]);1l n=t(e).1i(z$q[5u]);o=z$q[8Z]in i?i.7Y.$t:z$q[bD]in i?i.3M.$t:z$q[23],z$q[bz]in i?r=i.4M$5v.2g:1y[1].1m(o)||1y[3].1m(o)?(r=1y[1].3q(1y[1]),o=1y[3].3q(o),r=z$q[9C]+(1w!=r?r[5]:o[3])+z$q[hF]):1y[0].1m(o)?(o=1y[0].3q(o),r=o[4]):r=z$q[9q],a=a.1t(/\\[4H\\]/g,i.4H.$t),a=a.1t(/\\[ua\\]/g,s.ub()),a=a.1t(/\\[uc\\]/g,r),a=a.1t(/\\[2g\\]/g,n),i=z$q[23],z$q[23]!=r&&(i=z$q[2C]+7v+z$q[eU]+r+z$q[1V]),a=a.1t(/\\[bS\\]/g,i),t(e).3r(a)},T=1h(t){C(z$q[ud],k,z$q[9q],t)},I=t(z$q[ue]).1i(z$q[4]);t(z$q[uf]).1B(1h(){1l e=t(1f).1i(z$q[4]),a=t(1f).1i(z$q[ug]);t(z$q[uh]).am(e,a)});1l M=0;t(1I).on(z$q[ui],1h(){1l e=t(1f).4p();ff&&(e>=t(z$q[9I]).2J()+60?(t(z$q[dX]).1v(z$q[dP]),e>M?t(z$q[9I]).1D(z$q[bR])&&t(z$q[9I]).1Z(z$q[bR]):t(z$q[9I]).1v(z$q[bR]),M=e):t(z$q[dX]).1Z(z$q[dP]),t(z$q[9v]).1D(z$q[dK])||t(z$q[9v]).1v(z$q[dK])),bq&&cE<t(1f).2y()&&(1<t(z$q[8C]).2y()&&l(t(z$q[8C]),z$q[hM],e),1<t(z$q[ay]).2y()&&l(t(z$q[ay]),z$q[hM],e),t(z$q[9v]).1D(z$q[dt])||t(z$q[9v]).1v(z$q[dt]));1l a=t(z$q[4Z]).1j;if(t(z$q[ur]).1j<a){1l s=e>=1;t(z$q[4Z]).1B(1h(){if(!t(1f).1D(z$q[9W])){1l e=t(1f),a=e.2b(z$q[7G]),i=a.2B();s&&r(i,a,e)}})};if(e>5E?t(z$q[de]).1v(z$q[d9]):t(z$q[de]).1Z(z$q[d9]),t(z$q[d8]).1j||i(),t(z$q[61]).1j&&(t(z$q[5h]).1D(z$q[6t])||t(z$q[5h]).1D(z$q[cv]))&&t(z$q[uv]).1j&&!t(z$q[61]).1D(z$q[d7])&&(1h(){1l t=2d,e=t.6R(z$q[5G]);e.4h=z$q[6z]+a0+z$q[ux],e.uy(z$q[uz],+4r 6y),(t.d4||t.6i).d2(e)}(),t(z$q[61]).1v(z$q[d7])),t(z$q[8r]).1j&&t(z$q[uD]).1j&&!t(z$q[8r]).1D(z$q[cY])){1l o=t(z$q[8r]).1i(z$q[4]);!1h(t,e,a){1l s=1h(){1l t=e.6T(z$q[5G]);1H t[t.1j-1].9H}();t.uF=o,t.uG=s,1h(t){1l s=e.6R(z$q[5G]);s.5y=z$q[da],s.db=!0,s.4h=(z$q[dd]===e.2q.5A?z$q[dc]:z$q[aZ])+z$q[7l]+a,(t||e.6i||e.d4).d2(s)}(s)}(1I.uH={},2d,z$q[uI]),t(z$q[8r]).1v(z$q[cY])};t(z$q[uJ]).1j&&!t(z$q[uK]).1j&&8A(t(z$q[6a])),t(z$q[ba]).1j&&!t(z$q[uL]).1j&&t(z$q[ba]).1B(1h(){1l e=t(1f).1p(z$q[hC]),a=e.1i(z$q[4m]);e.1i(z$q[7q],z$q[8z]+(-1!=a.1E(z$q[aZ])?z$q[aY]+a+z$q[7t]:z$q[7e])+z$q[i7]).1v(z$q[uM])}),I&&z$q[23]!=I&&t(z$q[5h]).1D(z$q[6t])&&!t(z$q[cV]).1D(z$q[cU])&&(t(z$q[cV]).1v(z$q[cU]),t.c3(z$q[5z]+3G+z$q[uQ]+9j(I)+z$q[uR],1h(e){e=2h(e.2v.4i$5b.$t),e>1?t.c3(z$q[5z]+3G+z$q[uS]+(e-1)+z$q[uT],1h(t){C(z$q[uU],$,z$q[9q],t.2v.1U[0]);1l e=2h(t.2v.4i$5b.$t),a=2h(t.2v.4i$uV.$t);e-a>1&&T(t.2v.1U[2])}):t.c3(z$q[5z]+3G+z$q[uW],1h(t){T(t.2v.1U[0])})})),t(z$q[cK]).1j&&!t(z$q[uY]).1j&&t(z$q[cK]).1B(1h(){t(1f).1i(z$q[7q],z$q[uZ]+t(1f).1i(z$q[4m])+z$q[v0]),t(1f).8Y(z$q[4m]),t(1f).1v(z$q[v1])}),iR&&t(z$q[cJ]).1j&&t(z$q[5h]).1D(z$q[6t])&&(t(z$q[6u]).1j||(t(z$q[5R]).1R(z$q[v4]+fp+z$q[v5]),t(z$q[v6]).2H({2A:3,3n:5,6M:!0,3N:!0,6J:!1,3M:3B,6b:8j}),t(z$q[v7]).on(z$q[3f],1h(){1H t(z$q[6u]).1D(z$q[7k])?t(z$q[6u]).1Z(z$q[7k]).1v(z$q[v9]):t(z$q[6u]).1v(z$q[7k]),!1})),e>t(z$q[va]).3E().3d-6h&&e<t(z$q[cx]).3E().3d-t(z$q[cx]).2J()?t(z$q[6u]).1v(z$q[7k]):t(z$q[6u]).1Z(z$q[7k]))}),!t(z$q[cn]).1p(z$q[3I]).1j&&it&&t(z$q[cn]).2H({2A:z$q[64]===6W?1F.gI:z$q[iZ]===6W?1F.6I:6,2F:z$q[64]===6W?z$q[5W]:z$q[23],5m:4S,3Y:8w,6J:z$q[iZ]===6W}).1v(z$q[ve]+6W),t(z$q[cJ]).1B(1h(){1l e,a=1,s=t(1f);e=t(1f).2B().1t(/(\\r\\n|\\n|\\r)/gm,z$q[23]),t(z$q[vf]).1B(1h(){1l i,o=t(1f);i=o.1i(z$q[vg]).1t(/(\\r\\n|\\n|\\r)/gm,z$q[23]),a=o.1i(z$q[vh]),e==i&&s.1R(z$q[vi]+a+z$q[vj])})}),t(1I).on(z$q[cc],1h(){if(t(z$q[d8]).1j&&1I.2V&&1I.2V.4U&&1I.2V.4U.6m&&1I.2V.4U.6m(2d.4g(z$q[vl])),t(z$q[vm]).1j||t(z$q[vn]).1R(t(z$q[vo])).1v(z$q[dj]),t(z$q[vp]).1j){1l e=t(z$q[vq]).2y();t(z$q[vr]).1Q({2y:e})};1l e=t(1I).2y(),a=t(1I).2J(),s=t(z$q[5h]);e>a?(s.1Z(z$q[i0]),s.1v(z$q[hy])):(s.1Z(z$q[hy]),s.1v(z$q[i0]))}).4u(z$q[cc])}(3j);1l ht=1h(t,e){1h a(){1l a,s=e.6R(z$q[vv]),i={vw:z$q[vx],vy:z$q[vz],vA:z$q[vB],vC:z$q[vD],cf:z$q[vF]};e.6i.7w(s,1w);1W(1l o in i){4k(0)!==s.6C[o]&&(s.6C[o]=z$q[vG],a=t.vH(s).vI(i[o]))};1H e.6i.vJ(s),4k(0)!==a&&0<a.1j&&z$q[b4]!==a}$(z$q[hd]);1l s=$(z$q[5R]),o=s.2b(z$q[bG]),r=1h(){1l a=!1;1H z$q[vL]in t||t.h7&&e vN h7?(a=!0,$(z$q[0]).1v(z$q[vO])):$(z$q[0]).1v(z$q[2G]),a}(),n=1h(){1l e=0;1H 5P.7I.5V(/(cM|cN)/i)&&-1!=5P.7I.1E(z$q[vP])&&-1==5P.7I.1E(z$q[vQ])&&(e=60),z$q[vR]in t.5P&&t.5P.vS&&(e=0),e}(),l=(a=a())?z$q[vT]:z$q[23],d=z$q[vU]in t?z$q[vV]:z$q[cc],c=r?z$q[vW]:z$q[vX],p=r?z$q[vY]:z$q[vZ],m=r?z$q[w0]:z$q[w1],h=1h(e){1f.1n={9P:!0,ft:5B,6p:8z,w5:50,6c:1w,9x:1w};1W(i in e){1f.1n[i]=e[i]};1f.c0(),$(t).on(d,1f.c0.7h(1f)),s.on(c,1f.f4.7h(1f)),o.on(p,1f.eS.7h(1f)),s.on(m,1f.eL.7h(1f))};1H h.wb={5p:{},x:0,dx:0,ox:1w,9E:1w,7x:!1,wh:1h(){1H[1f.5p.7O,1f.5p.im]},3E:1h(){1H n},c0:1h(){1f.5p.im=$(t).2J(),1f.5p.7O=$(t).2y(),1f.ig(),1f.6c=1w===1f.1n.6c?4e.cw(0.25*1f.5p.7O):/%/.1m(1f.1n.6c)?4e.cw(1f.5p.7O*1f.1n.6c.1t(z$q[ck],z$q[23])/3B):1f.1n.6c,1f.1n.9x&&1f.1n.9x()},ig:1h(){1f.7x=!(1f.5p.7O<1f.1n.ft),1f.iW()},iW:1h(){},f4:1h(t){1f.9E=$(t.9h),1f.6V||1f.7x||!1f.1n.9P||(t=r?t.a9.h9[0]:t,1f.6V=!0,1f.af=t.9b,1f.f6=t.es,1f.8O=1f.8D=0,1f.b2=!1,1f.x=o.3E().2S+1f.1n.6p,1f.ox=-1f.x+1f.af,o.1Q({\"\\E\\G\\D\\L\\B\\F\\E\\F\\H\\L\\P\\O\\Z\\G\\D\\E\\F\\H\\L\":z$q[wn]}))},eS:1h(t){if(1f.6V&&!1f.7x&&1f.1n.9P){1l e=r?t.a9.h9[0]:t;1f.8D+=4e.cP(e.9b-1f.af),1f.8O+=4e.cP(e.es-1f.f6),10>1f.8D&&10>1f.8O||(!1f.b2&&1f.8O>1f.8D?1f.6V=!1:(t.cA(),1f.b2=!0,1f.ox&&(t=2h(e.9b)-1f.ox,1f.dx=t-1f.x,1f.x=t,1f.il(t))))}},eL:1h(t){1f.6V&&!1f.7x&&1f.1n.9P&&(t=2h((r?t.a9.wo[0]:t).9b)-2h(1f.ox),0>=1f.dx&&!1f.9E.is(z$q[wp])?1f.8t(t,0):1f.8t(t,1f.1n.6p),0===1f.dx&&0===t&&1f.9E.is(z$q[hd])&&1f.8t(1f.1n.6p,1f.1n.6p),1f.ox=1w,1f.dx=0,1f.6V=!1)},8t:1h(t,e){o.1Q({\"\\E\\G\\D\\L\\B\\F\\E\\F\\H\\L\\P\\O\\Z\\G\\D\\E\\F\\H\\L\":4e.ax(3B*t/1f.6c)+z$q[wr],cf:z$q[hZ]+e+z$q[hK]+l}),1f.hv(e)},il:1h(t){o.1Q({cf:z$q[hZ]+t+z$q[hK]+l})},hv:1h(t){t>1f.1n.6p-50?(s.1v(z$q[dl]),$(z$q[dh]).1v(z$q[cR])):(s.1Z(z$q[dl]),$(z$q[dh]).1Z(z$q[cR]))}},h}(1I,2d),wy=4r ht;if($(z$q[gU]).1j){1l gK=1h(){$(z$q[gU]).1B(1h(){(f0=1I.f0||[]).8X({})})};gK()};2d.4g(z$q[dy]).ai=2d.4g(z$q[dy]).ai.1t(/(?:^|\\s)wD(?!\\S)/g,z$q[23])}","|","||||||||||||||||||||||||||_179f|||||||||_|x65|x73||x61|x74|x69|x72|x6F||x6C|x63|x6E||x20|x64|x2D|x22|x70|||x6D|x2E|x3C|x3E|x3D|x75|||||||||||x76|x2F|x68|x62|x67|this|x66|function|attr|length|x77|var|test|options|x6B|find|x79|x78|html|replace|atag|addClass|null|x3A|rgx|x26|x27|each|emoIMG|hasClass|indexOf|maxitem|x3B|return|window|x30|x29|x23|x3F|x31|x28|x5F|css|append|x41|x6A|entry|137|for|x2C|parents|removeClass|||||||||||x32|children|x33|document|substring|random|url|parseInt|132|x71|x4D|tags|x50|376|name|x54|location|cgrid|clist|maksimal|x5B|feed|x34|split|width|229|maxPosts|text|192|viewdefault|x4E|postType|500|RCWid|postperpage|height|click|626|194|link|x53|pos|x49|color|left|x7A|x5D|FB|133|remove|get|fbig|||||||||||x46|else|items|top|210|276|x37|NaviPostpage|155|jQuery|parent|lfrom|mulai|maxPostsPerTag|x44|x4C|exec|replaceWith|ts_isRTL|163|134|x42|element|bigpost|halfpost|href|autoplay|100|akhir|x45|offset|124|lofrom|recent|533|blogpost|566|725|summary|ShowImage|549|hide|144|blogURL|441|prepend|296|animated|post|list|auto|loadMoreDiv|||||||||||review|753|hot|x55|Math|167|getElementById|src|openSearch|x35|void|x59|284|129|348|scrollTop|x4F|new|1022|382|trigger|nomerkiri|timeline|featured5|loop|rtl|215|delCookieLocal|nav|owlCarousel|val|slice|autoplayHoverPause|title|author|innerHTML|188|navText|media|featured2|featured1|newsticker|column2|344|fthumb|hrev|XFBML|x43|x52|445|x4B|515|||||||||||vmode|totalResults|248|ajaxload|gallery|effect|fbig2|972|166|x36|olderPostsLink|x4A|thumb|Number|408|info|position|featured|autoplayTimeout|gapi|185|thumbnail|slideSpeed|next|type|650|protocol|1e3|gallery1|gallery2|250|443|351|ShowPage|slider|159|responsiveRefreshRate|wrapAll|182|video|responsiveClass|navigator|featured3|589|smartSpeed|x38|x25|match|557|break|ShowTags|552|||||||||||198|ShowAuthor|snapThreshold|522|extend|wrapNum|rel|400|body|771|plusone|done|parse|substr|x48|menuWidth|150|149|189|191|1174|x2A|x57|getCookieLocal|Date|128|219|script|style|551|240|x39|174|252|fbig1|ShowDesc|292|514|ShowComment|contentnya|RComments|checkLocal|carousel|createElement|179|getElementsByTagName|846|initiated|relst|first|featured4|carousel2|||||||||||carousel1|172|gallery3|256|259|1086|1073|bind|host|630|1178|218|com|toFixed|517|curpagenya|299|x47|513|303|init|imgtag|insertBefore|desktop|1005|shortcodeTags|previous|featuredpost|simpleTab|numshowpage|438|before|965|433|userAgent|1098|animate|728|849|350|docWidth|typeof|206|published|840|839|summaryLength|726|390|wrapInner|content|sumLength|||||||||||column1|SliderSpeed|5e3|hoverEffect|272|mCustomScrollbar|x24|margin|fadeOut|shideauthor|new_page|537|cdate|529|524|stx|show|1152|645|_animateTo|pageNavi|value|aplay|516|x7B|300|socialct|elmt|118|stepsX|defaultOptions|mtx|pageplace|308|310|311|chside|lmtx|314|506|stepsY|494|238|vmtx|x7D|117|cpost|side|right|push|removeAttr|241|||||||||||setCookieLocal|pageX|setCookie|localStorage|564|active|200|target|554|encodeURIComponent|disqus_shortname|lMore|244|713|245|335|914|246|mthumb|340|906|1141|875|resize|loading|animateOut|727|412|249|411|tgt|409|toLocaleString|parentNode|1136|first_thumb|255|startFirst|828|542|youtube|menu|1085|lastIndexOf|761|848|816|754|750|381|817|746|dsqsn|number|742|818|829|401|361|siblings|847|originalEvent|hecpt|nbsp|858|342|929|pointX|slideUp|421|className|event|subscribe|Event|replaceText|sthumb|698|689|data|968|682|327|cookie|getCookie|testCookie|floor|1003|669|characters|detach|avatarSize|hidetitleads|anon|tbline|480|320|319|318|after|652|651|317|relatedTitle|502|316|507|recentTitle|313|312|fadeIn|305|bbline|302|301|813|perpagenya|directionLocked|1042|1044|hostname|blinest|hpagenav|start_from|629|290|homelist|531|616||hideEmo|615|btlinest|1045|googleCSE|1047|twttr|1069|268|1090|254|stickyMenu||253|postScoreClass|relevantTip|dyn|251|bpst|hpst|243|pathname|monthName|hva|242|blpost|spst|1097|1101|1102|recentcomment|1103|randompost|recentpost|scrthumbSize|texnya|125|126|1139|img|553|timeplace|x58|135|136|145|146|resizeSite|588|660|getJSON|151|x21|585|ready|582|wrap|563|_width|1191|postContainerSelector|jsonstart|transform|180|574|x56|175|297|delCookie|getLocal|1183|setLocal|pajax|999|995|987|MoreText|loadAjax|973|round|1182|x40|haveCookie|preventDefault|hash|330|dformat|960|943|942|941|940|1173|1168|939|iPhone|iPod|938|abs|ntx|1229|917|dailymotion|1160|1161|338|909|1154|fpost|888|ptx|appendChild|867|head|201|202|1149|1147|1145|352|async|353|354|1146|soundcloud|x7E|1230|844|842|1e4|1228|838|datetime|833|834|831|months|dateplace|1143|hideSpeed|showSpeed|366||1232|timeFormat|821|822|814|812|213|811|809|dajaxsrc|757|getDate|1140|xBB|removeHighlight|youtu|378|1137|752|380|setInterval|getHours|getMinutes|getSeconds|classname|1138|fb1ani|flip|fade|galler|pagenumber|ajaxsrc|741|739|737|736|735|734|733|732|srcBlank|731|column|730|simplepost|rcadminBlog|410|findText|1128||NotfindText|gridpost|LoadingText|mbig||viewMoreText|pageY|MaxPost|hover|223|queue|easing|414|duration|415|224|723|mtab|mcarousel|slideDown|721|716|420|227|422|_end|140|141|426|142|701|432|_move|430|705|reltx|232|1100|234|437|adsbygoogle|postscribe|444|grip|_start|237|pointY|rectx|shuffleArray|239|xab|getRandomInt|tagregex|sevidaemo|emoShow|fixMenu|663|662|Showimage|numComments|extendedProperty|showAdmin|152||uri|recotx|image|453|hideLatest|breakpoint|456|154|emo1||461|emo2|462|emo3|463|emo4|464|emo5|465|emo6|466|emo7|467|emo8|468|emo9|469|emo10|470|emo11|471|emo12|472|emo13|473|emo14|474|emo15|475|emo16|476|emo17|477|emo18|478|emo19|479|emo20|emo21|481|emo22||482|emo23|483|emo24||484|emo25|485||emo26||486|emo27|487|156||emo28|488|emo29|489|157|emo30|490|emo31|491|emo32|492|scheer|emo33|493|related|247|displayGoogleAds|653|alt|when|twtx|101|x51|102|160|prependTo|1231|648|161|505|162|647|103|maxTags|511|512|lktx|104|cseID|DocumentTouch|105|touches|1082|1081|1076|1208|1072|1070|518|169|106|1068|1067|521|shtx|107|_e|108|1053|526|527|Bamboo|1052|_toggleCover|278|lock|1200|109|534|535|282|176|rmtx|286|end_on|287|288|110|1227|111|1142|177|category|601|112|twau|293|113|dsqcom|599|114|flbadge|115|1226|1199|592|591|116|toLowerCase|dtime|FullmonthName|304|flickrid|306|getScript|fbappsid|181||number_of_pages||layout|fblang|315|FBbox|120|_moveContainer|docHeight||555|animateIn|556|number_of_items||shrel|twitter|facebook|hideendads|responsiveBaseElement|pinterest|558|responsive|1029|1023|321|183|1020|581|580|583|1014|simpleSpy|579|1012|184|ads|full|565|shreco|578|568|577|_gaq|hideAddressBar|loadingGif|delLocal|1185|918|571|572|onRefreshed|573|refresh|575|576|navigationText|onInitialized|570|569|567|onRefresh|autoWidth|center|pagination|562|561|560|limit|584|direction|559|586|587|titleText|ticker|navContainer|590|593|550|548|547|594|595|596|597|598|546|545|544|600|543|term|602|603|541|540|538|604|605|536|606|607|608|609|610|611|612|613|614|532|539|617|618|619|620|621|622|623|530|624|625|528|627|slider1|628|525|631|632|523|633|634|635|638|637|636|639|640|520|641|642|643|644|519|646|510|trim|inArray|509|508|504|503|select|649|focus|stopPropagation|498|497|496|495|499|501|455|654|454|457|458|459|655|460|451|450|join|452|656|putEmoAbove|657|658|659|449|661|emoMessage|448|664|665|666|667|668|topText|670|671|447|674|672|673|675|676|defaultAvatar|677|emoRange|678|446|679|680|442|681|439|440|683|684|685|688|687|686|435|690|691|692|693|694|695|696|697|434|699|700|702|703|704|431|706|707|appendTo|428|429|709|710|708|fbAsyncInit|appId|status|xfbml|version|711|425|427|712|424|436|714|715|423|717|718|719|720|418|722|417|filter|hoverTimeout|729|419|416|413|724|407|406|404|405|402|403|397|398|399|394|738|395|396|392|393|389|391|386|387|740|http|388|743|385|createCookie|383|744|745|384|747|748|749|complex|readCookie|751|379|highlight|377|755|756|375|373|758|759|760|372|762|763|764|765|766|767|768|769|770|onfocus|772|773|774|775|776|777|778|779|780|781|782|783|784|785|786|787|788|789|790|791|792|793|794|795|796|797|798|799|800|801|802|803||804|805|806|807|808|371|810|370|outerHeight|onblur|374|bottom|spotim|815|368|disqus|369|blogger|367|820|819|365|364|832|363|823||824|825|826|827|830|362|execute|837|clearAllResults||slideToggle|360|getElement|835|toggleClass|836|864|cse|search|google|841|359|843|357|845|358|356|355|349|850|851|852|853|854|855|856|857|347|859|860|861|862|863|884|865|866|346|868|869|870|871|872|873|874|345|876|877|878|879|880|881|882|883|896|885|886|887|343|889|890|891|892|893|894|895|900|897|898|899|902|901|905|903|904|916|341|907|908|339|910|911|912|913|337|915|closest|336|924|919|920|921|922|923|925|926|927|928|334|931|930|936|932|933|934|935|944|937|iPad|Android|333|cache|ajaxSetup|332|946|945|964|947|948|949|950|951|952|953|954|955|956|957|958|959|331|961|962|963|toUTCString|970|escape|966|967|transitionProperty|setDate|transition|969|329|328|971|testcookie|currentTarget|unescape|326|975|974|979|976|977|978|980|981|982|983|984|985|havecookie|986|setItem|994|picture|991|990|989|988|992|993|getItem|996|997|998|removeItem|1000|1001|1002|307|openPopup|1004|simulateClick|1006|via|1007|1008|buttons|1009|324|1010|1011|urlCurl|enableTracking|enableHover|1013|323|1015|1016|1017|1019|1018|322|1021|template|stumbleupon|hidebottomads|1027|1024|1025|1026|1028|linkedin|googlePlus|1030|1032|1031|fnt|1034|1033|lnt||share|sharrre||size|309|ceil|325|1035|298|1036|295|1037|1038|1039|1040|1041|1043|294|291|289|285|1046|283|1048||281|prev|280|1049|1050|1051|279|277|275|1055|1054|1058|1056|1057|1059|1060|1061|274|1063|273|1062|events|271|1064|baseURI|1065|1066|270|269|itemsPerPage|267|266|1071|265|1074|1075|264|index|1077|1078|1080|1079|263|262|1083|1084|1087|261|260|1088|1091|1089|258|1092|257|1093|1094|1096|1095|1124|one|236|RegExp|235|233|231|230|228|1099|226|1104|1106|1107|1105|225|1108|1109|1110|1111|222|1112|links|1113|1114|1115|1116|1117|Showthumb|221|1118|1119|1122|1120|1121|1123|1126|1125|1127|220|1129|date|toLocaleDateString|thumburl|1130|1131|1134|1132|1133|1135|217|216|214|1900|getYear|getMonth|212|211|1144|209|208|207|1148|203|1150|setAttribute|1151|204|199|205|1153|197|spotId|parentElement|SPOTIM|1155|1156|1157|1158|1159|196|195|193|1162|1163|1164|1165|1166|startIndex|1167|pageType|1169|1170|1171|1172|blog|_GetAllData|1175|1176|1177|1180|_WidgetManager|1179|1181|190|thumbnailSize|187|1184|1190|1186|1187|1188|1189|186|1192|1193|1195|1194|1196|1197|1198|178|173|171|1201|webkitTransform|1202|OTransform|1203|msTransform|1204|MozTransform|1205|170|1206|1207|getComputedStyle|getPropertyValue|removeChild|168|1209|165|instanceof|1210|1211|1212|1213|standalone|1214|1215|1216|1217|1218|1219|1220|1221|1222|164|153|158|headerHeight|148|147|getElementsByName|143|139|prototype|138|131|130|127|123|dimensions|122|121|119|bline|tads|1223|changedTouches|1224|item|1225|manualslide|flickrbadge|disquscomment|blockquote|bgallery|vimeo|site|embed|watch|x5A|x5E|loadinghtml","","\\w+","\\b","g"];eval(function(p,a,c,k,e,r){e= function(c){return (c< a?_$_4a9d[3]:e(parseInt(c/ a)))+ ((c= c% a)> 35?String.fromCharCode(c+ 29):c.toString(36))};if(!_$_4a9d[3].replace(/^/,String)){while(c--){r[e(c)]= k[c]|| e(c)};k= [function(e){return r[e]}];e= function(){return _$_4a9d[4]};c= 1};while(c--){if(k[c]){p= p.replace( new RegExp(_$_4a9d[5]+ e(c)+ _$_4a9d[5],_$_4a9d[6]),k[c])}};return p}(_$_4a9d[0],62,2024,_$_4a9d[2].split(_$_4a9d[1]),0,{}))
//]]>
</script>
<div class='gads-mainfile hide'>
  <b:section class='gads-mainfile-sec' id='gadsmain-file1' showaddelement='no'>
    <b:widget id='HTML877' locked='true' title='Google ads Main JS' type='HTML' version='1'>
      <b:widget-settings>
        <b:widget-setting name='content'>y</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>        
		<b:if cond='data:content == &quot;n&quot; or data:content == &quot;&quot;'><b:else/>
        <script async='' src='//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js'/>
		</b:if>	 
      </b:includable>
    </b:widget>
  </b:section>
</div>
</body>
</html>
