# myblog
codigo de plantilla


<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<HTML b:css='false' b:responsive='true' b:version='2' class='v2' expr:dir='data:blog.languageDirection'>
&lt;head&gt;
<meta charset='utf-8'/>
<meta content='width=device-width, initial-scale=1' name='viewport'/>
<meta content='blogger' name='generator'/>
<link expr:href='data:blog.url' hreflang='x-default' rel='alternate'/>
<link href='http://www.blogger.com/openid-server.g' rel='openid.server'/>
<link expr:href='data:blog.homepageUrl' rel='openid.delegate'/>
<link expr:href='data:blog.url' rel='canonical'/>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<title><data:blog.pageTitle/></title>
<b:else/>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<title><data:blog.pageName/> - <data:blog.title/></title>
</b:if></b:if>
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
<title>Page Not Found - <data:blog.title/></title>
</b:if>
<b:if cond='data:blog.pageType == &quot;archive&quot;'>
<meta content='noindex' name='robots'/>
</b:if>
<b:if cond='data:blog.searchLabel'>
<meta content='noindex,nofollow' name='robots'/>
</b:if>
<b:if cond='data:blog.isMobile'>
<meta content='noindex,nofollow' name='robots'/>
</b:if>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<meta expr:content='data:blog.metaDescription' name='description'/>
<script type='application/ld+json'>{ &quot;@context&quot;: &quot;http://schema.org&quot;, &quot;@type&quot;: &quot;WebSite&quot;, &quot;url&quot;: &quot;<data:blog.homepageUrl/>&quot;, &quot;potentialAction&quot;: { &quot;@type&quot;: &quot;SearchAction&quot;, &quot;target&quot;: &quot;<data:blog.homepageUrl/>?q={search_term}&quot;, &quot;query-input&quot;: &quot;required name=search_term&quot; } }</script>
<b:if cond='data:blog.homepageUrl != data:blog.url'>
<meta expr:content='data:blog.pageName + &quot;, &quot; + data:blog.pageTitle + &quot;, &quot; + data:blog.title' name='keywords'/>
</b:if></b:if>
<b:if cond='data:blog.url == data:blog.homepageUrl'>
<meta content='DESKRIPSI-BLOG' name='keywords'/></b:if>
<link expr:href='data:blog.homepageUrl + &quot;feeds/posts/default&quot;' expr:title='data:blog.title + &quot; - Atom&quot;' rel='alternate' type='application/atom+xml'/>
<link expr:href='data:blog.homepageUrl + &quot;feeds/posts/default?alt=rss&quot;' expr:title='data:blog.title + &quot; - RSS&quot;' rel='alternate' type='application/rss+xml'/>
<link expr:href='&quot;http://www.blogger.com/feeds/&quot; + data:blog.blogId + &quot;/posts/default&quot;' expr:title='data:blog.title + &quot; - Atom&quot;' rel='alternate' type='application/atom+xml'/>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<b:if cond='data:blog.postImageThumbnailUrl'>
<link expr:href='data:blog.postImageThumbnailUrl' rel='image_src'/>
</b:if></b:if>
<link expr:href='data:blog.url' hreflang='x-default' rel='alternate'/>
<link href='/favicon.ico' rel='icon' type='image/x-icon'/>
<meta content='CODE-VALIDATION-GOOGLE-WEBMASTER' name='google-site-verification'/>
<meta content='CODE-VALIDATION-BING-WEBMASTER' name='msvalidate.01'/>
<meta content='Indonesia' name='geo.placename'/>
<meta content='ADMIN-NAME' name='Author'/>
<meta content='general' name='rating'/>
<meta content='id' name='geo.country'/>
<!-- [ Social Media Meta Tag ] -->
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<meta expr:content='data:blog.pageName' property='og:title'/>
<meta expr:content='data:blog.canonicalUrl' property='og:url'/>
<meta content='article' property='og:type'/>
</b:if>
<meta expr:content='data:blog.title' property='og:site_name'/>
<b:if cond='data:blog.url == data:blog.homepageUrl'>
<meta expr:content='data:blog.title' property='og:title'/>
<meta content='website' property='og:type'/>
<b:if cond='data:blog.metaDescription'>
<meta expr:content='data:blog.metaDescription' property='og:description'/>
<b:else/>
<meta expr:content='&quot;Please visit &quot; + data:blog.pageTitle + &quot; To read interesting posts.&quot;' property='og:description'/>
</b:if>
</b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<meta expr:content='data:blog.metaDescription' property='og:description'/>
</b:if>
<b:if cond='data:blog.postImageUrl'>
<meta expr:content='data:blog.postImageUrl' property='og:image'/>
<b:else/>
<b:if cond='data:blog.postImageThumbnailUrl'>
<meta expr:content='data:blog.postThumbnailUrl' property='og:image'/>
<b:else/>
<meta content='https://4.bp.blogspot.com/-SKh7CYM3lB0/WZlRLgH8wII/AAAAAAAACjQ/vx5PJdQYhSo136-Wg-A633KcElrfkHNNACLcBGAs/s1600/non.png' property='og:image'/>
</b:if>
</b:if>
<meta content='https://www.facebook.com/josmary.palenciacentella' property='article:author'/>
<meta content='https://www.facebook.com/FAN-PAGE-FACEBOOK' property='article:publisher'/>
<meta content='CODE-APPLICATION-FACEBOOK' property='fb:app_id'/>
<meta content='CODE-ADMIN-FACEBOOK' property='fb:admins'/>
<meta content='en_US' property='og:locale'/>
<meta content='en_GB' property='og:locale:alternate'/>
<meta content='id_ID' property='og:locale:alternate'/>
<meta content='summary' name='twitter:card'/>
<meta expr:content='data:blog.pageTitle' name='twitter:title'/>
<meta content='USER-TWITTER' name='twitter:site'/>
<meta content='USER-TWITTER' name='twitter:creator'/>
<meta content='summary_large_image' name='twitter:card'/>
<meta content='#021f2d' name='theme-color'/>
<meta content='#021f2d' name='msapplication-navbutton-color'/>
<meta content='yes' name='apple-mobile-web-app-capable'/>
<meta content='#021f2d' name='apple-mobile-web-app-status-bar-style'/>
&lt;style type=&quot;text/css&quot;&gt;
&lt;!-- /*<b:skin><![CDATA[
#layout #header{float:left;overflow:hidden}
#header,.main-wrapper,.sidebar-wrapper{overflow:hidden}
#layout .header-wrap{position:relative;width:1000px}
#layout #header{width:330px!important;padding:0}
#layout .outerpic-wrapper{width:1000px;padding:0;margin:0 auto;overflow:hidden}
#layout .content-wrapper{position:relative;max-width:1000px;display: inline-block;margin:0 auto}
#layout .outer-wrapper{position:relative;width:1000px;padding:0}
#layout .main-wrapper{width:690px;margin:0;float:right}
#layout .box2,#layout .box4,#layout .box5,#layout .box7,#layout .box8,#layout .box9,h2.section-title,p.main-text{display:none}
#layout .left,#layout .right{width:50%}#layout .right{float:right}#layout .left{float:left}
#layout .sidebar-wrapper{width:310px;float:left;word-wrap:break-word}
#layout .footer{float:left;width:207px!important;}
#layout .footer{margin:10px}
#layout ul,#layout li,#layout ol{list-style:none}
<Group description="(Contempo, Soho, Emporio, Notable)">
<Variable name="body.background" description="Body Background" type="background" color="#dddfe2" default="#dddfe2 none repeat scroll top left" value="#dddfe2 none repeat scroll top left"/>
<Variable name="body.font" description="Font" type="font" default="normal 400 14px Roboto, Arial, sans-serif" value="normal 400 14px Arial,sans-serif"/>
<Variable name="body.text.color" description="Text Color" type="color" default="#1d2129" value="#1d2129"/>
<Variable name="body.text.font" description="1" type="font" default="$(body.font)" value="normal 400 14px Roboto,Arial,sans-serif"/>
<Variable name="posts.background.color" description="2" type="color" default="#fff" value="#ffffff"/>
<Variable name="body.link.color" description="3" type="color" default="#fab702" value="#fab702"/>
<Variable name="body.link.visited.color" description="4" type="color" default="#fab702" value="#fab702"/>
<Variable name="body.link.hover.color" description="5" type="color" default="#1d2129" value="#1d2129"/>
<Variable name="blog.title.font" description="6" type="font" default="$(body.text.font)" value="normal 400 14px Roboto, Arial, sans-serif"/>
<Variable name="blog.title.color" description="7" type="color" default="#fff" value="#ffffff"/>
<Variable name="header.icons.color" description="8" type="color" default="#fff" value="#ffffff"/>
<Variable name="tabs.font" description="9" type="font" default="$(body.text.font)" value="normal 400 14px Roboto, Arial,sans-serif"/>
<Variable name="tabs.color" description="10" type="color" default="#ccc" value="#cccccc"/>
<Variable name="tabs.selected.color" description="11" type="color" default="#fff" value="#ffffff"/>
<Variable name="tabs.overflow.background.color" description="12" type="color" default="#fff" value="#ffffff"/>
<Variable name="tabs.overflow.color" description="13" type="color" default="$(body.text.color)" value="#1d2129"/>
<Variable name="tabs.overflow.selected.color" description="14" type="color" default="$(body.text.color)" value="#1d2129"/>
<Variable name="posts.title.color" description="15" type="color" default="$(body.text.color)" value="#1d2129"/>
<Variable name="posts.title.font" description="16" type="font" default="$(body.text.font)" value="normal 400 14px Roboto, Arial,sans-serif"/>
<Variable name="posts.text.font" description="17" type="font" default="$(body.text.font)" value="normal 400 14px Roboto, Arial,sans-serif"/>
<Variable name="posts.text.color" description="18" type="color" default="$(body.text.color)" value="#1d2129"/>
<Variable name="posts.icons.color" description="19" type="color" default="$(body.text.color)" value="#6c6f74"/>
<Variable name="labels.background.color" description="20" type="color" default="#fab702" value="#fab702"/>
</Group>
*/]]></b:skin>
<style>
/*=======================HOMEPAGE
TEMPLATE NAME: RAGHDA COMPANY PROFIL
AUTHOR: BASRI MATINDAS
DESIGN: http://www.goomsite.net
================================*/

/* http://meyerweb.com/eric/tools/css/reset/ */
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,sub,sup,tt,var,u,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline;text-decoration:none}

/* HTML5 display-role reset for older browsers */
.CSS_LIGHTBOX{z-index:999999!important}
.separator a{clear:none!important;float:none!important;margin-left:0!important;margin-right:0!important}
article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block}ol,ul{list-style:none}blockquote,q{quotes:none}blockquote:before,blockquote:after,q:before,q:after{content:&#39;&#39;;content:none}
table{border-collapse:collapse;border-spacing:0}

@font-face {
  font-family: &#39;Muli&#39;;
  font-style: italic;
  font-weight: 300;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aujp_0qiz-afTfcIyoiGtm2P0wG089z4eqVxVqBrzI.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: italic;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aujp_0qiz-afTfcIyoiGtm2P0wG05Fz4eqVxVqBrzI.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: italic;
  font-weight: 500;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aujp_0qiz-afTfcIyoiGtm2P0wG06Nz4eqVxVqBrzI.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: italic;
  font-weight: 600;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aujp_0qiz-afTfcIyoiGtm2P0wG00904eqVxVqBrzI.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: italic;
  font-weight: 700;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aujp_0qiz-afTfcIyoiGtm2P0wG03Z04eqVxVqBrzI.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: italic;
  font-weight: 800;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aujp_0qiz-afTfcIyoiGtm2P0wG0xF04eqVxVqBrzI.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: normal;
  font-weight: 300;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aulp_0qiz-aVz7u3PJLcUMYOFmQkEk30e6fxHiD.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: normal;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aulp_0qiz-aVz7u3PJLcUMYOFnOkEk30e6fxHiD.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: normal;
  font-weight: 500;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aulp_0qiz-aVz7u3PJLcUMYOFn8kEk30e6fxHiD.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: normal;
  font-weight: 600;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aulp_0qiz-aVz7u3PJLcUMYOFkQl0k30e6fxHiD.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: normal;
  font-weight: 700;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aulp_0qiz-aVz7u3PJLcUMYOFkpl0k30e6fxHiD.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: normal;
  font-weight: 800;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aulp_0qiz-aVz7u3PJLcUMYOFlOl0k30e6fxHiD.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Muli&#39;;
  font-style: normal;
  font-weight: 900;
  src: url(https://fonts.gstatic.com/s/muli/v19/7Aulp_0qiz-aVz7u3PJLcUMYOFlnl0k30e6fxHiD.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: italic;
  font-weight: 300;
  src: local(&#39;Poppins Light Italic&#39;), local(&#39;Poppins-LightItalic&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiDyp8kv8JHgFVrJJLm21lVF9eIYktMqg.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: italic;
  font-weight: 400;
  src: local(&#39;Poppins Italic&#39;), local(&#39;Poppins-Italic&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiGyp8kv8JHgFVrJJLucHtGOvWDSA.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: italic;
  font-weight: 500;
  src: local(&#39;Poppins Medium Italic&#39;), local(&#39;Poppins-MediumItalic&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiDyp8kv8JHgFVrJJLmg1hVF9eIYktMqg.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: italic;
  font-weight: 600;
  src: local(&#39;Poppins SemiBold Italic&#39;), local(&#39;Poppins-SemiBoldItalic&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiDyp8kv8JHgFVrJJLmr19VF9eIYktMqg.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: italic;
  font-weight: 700;
  src: local(&#39;Poppins Bold Italic&#39;), local(&#39;Poppins-BoldItalic&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiDyp8kv8JHgFVrJJLmy15VF9eIYktMqg.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: italic;
  font-weight: 800;
  src: local(&#39;Poppins ExtraBold Italic&#39;), local(&#39;Poppins-ExtraBoldItalic&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiDyp8kv8JHgFVrJJLm111VF9eIYktMqg.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: normal;
  font-weight: 300;
  src: local(&#39;Poppins Light&#39;), local(&#39;Poppins-Light&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLDz8Z1xlE92JQEk.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: normal;
  font-weight: 400;
  src: local(&#39;Poppins Regular&#39;), local(&#39;Poppins-Regular&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiEyp8kv8JHgFVrJJfedHFHGPc.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: normal;
  font-weight: 500;
  src: local(&#39;Poppins Medium&#39;), local(&#39;Poppins-Medium&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLGT9Z1xlE92JQEk.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: normal;
  font-weight: 600;
  src: local(&#39;Poppins SemiBold&#39;), local(&#39;Poppins-SemiBold&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLEj6Z1xlE92JQEk.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: normal;
  font-weight: 700;
  src: local(&#39;Poppins Bold&#39;), local(&#39;Poppins-Bold&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLCz7Z1xlE92JQEk.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: normal;
  font-weight: 800;
  src: local(&#39;Poppins ExtraBold&#39;), local(&#39;Poppins-ExtraBold&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLDD4Z1xlE92JQEk.woff) format(&#39;woff&#39;);
}
@font-face {
  font-family: &#39;Poppins&#39;;
  font-style: normal;
  font-weight: 900;
  src: local(&#39;Poppins Black&#39;), local(&#39;Poppins-Black&#39;), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLBT5Z1xlE92JQEk.woff) format(&#39;woff&#39;);
}
/* heading */
h1,h2,h3,h4,h5,h6 {font-family:&quot;Poppins&quot;,sans-serif;font-weight:800;line-height:1.3;margin-bottom:15px;}
h1{font-size:1.6rem}
h2{font-size:1.4rem}
h3{font-size:1.2rem}
h4{font-size:1rem}
h5{font-size:.9rem}
h6{font-size:0.7rem}
body{background:#fff;color:#021f2d;height:100%;font-weight:400;font-family:Muli,sans-serif;line-height:22px;margin:0;padding:0}
#cssmenu&gt;ul&gt;li&gt;a,a,a:active,a:hover,a:link,a:visited,body{text-decoration:none}
#navbar-iframe,a.quickedit{height:0;visibility:hidden;display:none}
#cssmenu ul,#header img{margin:0 auto;height:65px}
.comslider .NextArrow:before,.comslider .PrevArrow:before,.slick-dots li button:before{font-family:&quot;Font Awesome 5 Pro&quot;}
a,a:link,a:visited{color:#fab702}
a:active,a:hover{color:#333}

::selection{background:#fab702;color:#021f2d;text-shadow:none}
::-moz-selection{background:#fab702;color:#021f2d;text-shadow:none}
::-webkit-selection{background:#fab702;color:#021f2d;text-shadow:none}
::-o-selection{background:#fab702;color:#021f2d;text-shadow:none}
h2.date-header,.postmeta h3.date-header:after{display:none}

.headerpic-wrapper{background:#fff;width:100%;padding:0;margin:0 auto}
.header-wrapper{width:1170px;color:#777;position:relative;margin:0 auto;overflow:hidden}
#header{float:left;overflow:hidden;z-index:10;margin:0;padding:0}
#header-inner{margin:10px 0;padding:0}
#header h1,#header p{text-transform:uppercase;line-height:1.4;color:#484848;margin:0;font-size:25px;font-weight:900}
#header h1 a,#header h1.title a:hover{color:#fab702;text-decoration:none}
#header .description{color:#aaa;text-shadow:none;font-size:12px;font-style:italic}
#header img{border:0;background:none;width:auto}
.header-fixed{position:sticky;left:0;top:0;background:#fff;right:0;-webkit-transition-duration:.5s;transition-duration:.5s;-webkit-transition-timing-function:cubic-bezier(.46,.6,0,1);transition-timing-function:cubic-bezier(.46,.6,0,1);z-index:99}
.scroll{top:-150px;box-shadow:0 0 5px 0 rgba(0,0,0,.14)}
.no-scroll{top:0;z-index:999}

#cssmenu #head-mobile,#cssmenu ul li a,#cssmenu ul li.has-sub{position:relative}
#cssmenu,#cssmenu ul,#cssmenu ul li,#cssmenu ul li a{border:0;list-style:none;line-height:1;display:block;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}
#cssmenu{width:100%;margin:0 auto;background:#021f2d}
#cssmenu&gt;ul&gt;li&gt;a.menuactive{color:#fab702}
#cssmenu ul{display:block;width:1170px}
#cssmenu&gt;ul&gt;li{display:inline-block;margin:0}
#cssmenu&gt;ul&gt;li&gt;a{padding:0 20px 0 0;line-height:65px;font-size:14px;font-weight:700;letter-spacing:.8px;text-transform:uppercase;color:#ebebeb}
#cssmenu ul li.active a,#cssmenu&gt;ul&gt;li:hover&gt;a{color:#fab702}
#cssmenu ul li.active,#cssmenu ul li.active:hover,#cssmenu ul li.has-sub.active:hover,#cssmenu&gt;ul&gt;li:hover{background:rgba(64,64,64,.1);-webkit-transition:background .2s ease;-ms-transition:background .2s ease;transition:background .2s ease}
#cssmenu ul ul li:hover,#menu li.social{background:#fab702}
#cssmenu ul ul li.has-sub&gt;a::after,#cssmenu&gt;ul&gt;li.has-sub&gt;a::after{content:&quot;\f078&quot;;font-family:&quot;Font Awesome 5 Pro&quot;;font-size:10px;font-weight:400;text-decoration:inherit;margin-left:10px}
#cssmenu ul ul li.has-sub&gt;a::after{content:&quot;\f0da&quot;}
#cssmenu&gt;ul&gt;li.has-sub:hover&gt;a::after{content:&quot;\f077&quot;}
#cssmenu ul ul{height:auto;width:240px;position:absolute;left:-9999px;z-index:10;-webkit-box-shadow:0 2px 8px 0 rgba(0,0,0,.15);box-shadow:0 2px 8px 0 rgba(0,0,0,.15);opacity:0;transform:translateY(-2em);transition:all 0.3s ease-in-out 0s;}
#cssmenu li:hover&gt;ul{left:auto;opacity:1;transform:translateY(0%);transition-delay:0s, 0s, 0.3s;}
#cssmenu ul ul li{background:#fff;margin:0}
#cssmenu ul ul li a:hover{color:#021f2d;border-bottom:1px solid #fab702}
#cssmenu ul ul ul{margin-left:100%;top:0}
#cssmenu ul ul li a{border-bottom:1px solid #eee;padding:0 17px;line-height:42px;max-width:100%;text-decoration:none;font-size:14px;color:#021f2d;white-space:nowrap;text-overflow:ellipsis;overflow:hidden}
#cssmenu ul ul li.last-item&gt;a,#cssmenu ul ul li:last-child&gt;a{border-bottom:0}
#cssmenu ul li.has-sub ul li.has-sub ul li:hover,#cssmenu ul ul li.has-sub:hover{background:#eaeaea}
.btn-close,.btn-open{display:none}
@media screen and (min-width:801px){#cssmenu ul{display:block!important}}
#menu{float:right;padding:1rem 0;margin:0}
#menu li,#menu ul{margin:0 auto;padding:0;list-style:none}
#menu li.icon-box{display:inline-block;position:relative;font-size:15px;font-weight:600;margin-right:2rem}
#menu .close,.menubtnone{display:none}
#menu li.icon-box i{font-size:22px;padding:0;height:35px;color:#fab702;text-align:center;line-height:35px;margin-top:5px;position:absolute;width:35px;float:left;margin-right:.55556rem;border-radius:50%;border:2px solid #f1f1f1;vertical-align:middle}
#menu li,.box-slider,.img-full,.img-full img{position:relative}
#menu li .icon-box__title{margin:0;padding-top:.05556rem;font-size:14px;font-weight:800;text-transform:uppercase;display:block;color:#021f2d}
#menu li .icon-box__text{font-size:.88889rem;font-weight:700;color:#999;margin-left:50px}
#menu li.child{margin-right:1rem;padding-right:20px;border-right:1px solid #eee}
#menu li span.icon-box__subtitle{font-size:13px;font-weight:600;color:#a9a9a9}
#menu li{display:inline-block;font-size:15px;font-weight:600}
#menu li.social{margin:0 0 5px 5px;font-size:17px;padding:0;height:30px;color:#021f2d;text-align:center;line-height:30px;width:30px;border-radius:50%;vertical-align:text-bottom}
.img-full,.slick-dots{width:100%;text-align:center}
#menu li.social a{color:#021f2d}
#cssmenu&gt;ul&gt;li.request{float:right;background:#fab702}
#cssmenu&gt;ul&gt;li.request a{color:#021f2d;padding:0 20px}

.breadcrumbs,.breadcrumbs a{color:#bbbaba}
.breadcrumbs{padding:5px 0;margin:20px auto;font-size:12px}

.box-slider,.img-full{overflow:hidden;position:relative}
.box-slider{height:600px;visibility:visible}
.img-full{display:block}
.img-full img{height:100%;min-width:100%;display:inline-block;max-width:none}
.blocks-box,.slick-slider{margin:0;padding:0!important}
.slick-slide{padding:0}
.slick-dots{position:absolute;bottom:35px;display:block;padding:0;margin:0;list-style:none}
.slick-dots li,.slick-dots li button{width:20px;height:20px;cursor:pointer}
.slick-dots li{position:relative;display:inline-block;margin:0 5px;padding:0}
.slick-dots li button{font-size:0;line-height:0;display:block;padding:5px;color:transparent;border:0;outline:0;background:none}
.slick-dots li button:focus,.slick-dots li button:hover{outline:0}
.slick-dots li button:focus:before,.slick-dots li button:hover:before{opacity:1}
.slick-dots li button:before{font-size:10px;line-height:15px;position:absolute;top:0;font-weight:900;left:0;border-radius:50%;width:15px;height:15px;border:2px solid #eee;content:&#39;\f111&#39;;text-align:center;opacity:.2;color:transparent;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}
.slick-dots li.slick-active button:before{opacity:.75;color:#fab702;padding-left:1px}
.comslider{position:relative}
.comslider .NextArrow,.comslider .PrevArrow{background:rgba(255,255,255,.3);color:#fff;height:50px;line-height:50px;cursor:pointer;margin:0;border:none;position:absolute;font-size:30px;text-align:center;outline:0;top:45%;width:50px;z-index:9;border-radius:50%}
.comslider .NextArrow:hover,.comslider .PrevArrow:hover{transition:all 1s;background:rgba(240,185,54,.58)}
.comslider .PrevArrow:before{content:&#39;\f104&#39;}
.comslider .NextArrow:before{content:&#39;\f105&#39;}
.comslider .PrevArrow{left:-50px;transition:all .5s}
.comslider .NextArrow{right:-50px;transition:all .5s}
.comslider:hover .PrevArrow{left:65px;transition:all 1s;opacity:1;z-index:999999}
.comslider:hover .NextArrow{right:65px;transition:all 1s}
.comslider .img-full{height:600px;background:#021f2d}
.comslider .img-full:before{content:&#39;&#39;;display:block;width:100%;height:100%;top:0;left:0;z-index:2;position:absolute}
.comslider .img-full .info{position:absolute;left:0;width:100%;z-index:3;top:25%;padding:0}
.comslider .img-full h1{font-size:65px;color:#fff;line-height:1em;padding:0;margin:2% 0;overflow:hidden;text-transform:uppercase}
.comslider .img-full h3{z-index:5;white-space:nowrap;font-size:20px;line-height:1.5em;font-weight:700;color:#fab702;transition:none 0 ease 0;text-align:center;border-width:0;margin:0;padding:0;letter-spacing:0;min-height:0;min-width:0;max-height:none;max-width:none;opacity:1;transform-origin:50% 50% 0;transform:matrix3d(1,0,0,0,0,1,0,0,0,0,1,0,0,0,0,1)}
.comslider .img-full p{max-width:545px;font-size:15px;text-align:center;color:#fff;line-height:2;margin:30px auto;overflow:hidden;text-transform:capitalize}
.box-list h3.lefth3,.btn-effect,.left-heading{text-transform:uppercase}
.comslider .slick-active h3{animation:fadeInDown 1s both .2s;visibility:visible}
.comslider .slick-active h1{animation:fadeInDown 1.2s both .6s;visibility:visible}
.comslider .slick-active p{animation:fadeInDown 1.4s both .1s;visibility:visible}
.comslider .slick-active a.btn-wp{animation:fadeInUp 3s both .12s;visibility:visible}
.YouTubePopUp-Hide,.YouTubePopUp-animation{animation-duration:.5s;animation-fill-mode:both}
.backtop,.slick-loading .slick-slide,.slick-loading .slick-track{visibility:hidden}
.comslider a.btn-wp{transform-origin:50% 50% 0;transform:matrix3d(1,0,0,0,0,1,0,0,0,0,1,0,0,0,0,1);margin:0 10px}
.slick-slider{position:relative;display:block;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;-webkit-touch-callout:none;-khtml-user-select:none;-ms-touch-action:pan-y;touch-action:pan-y;-webkit-tap-highlight-color:transparent}
.slick-list{position:relative;display:block;overflow:hidden;margin:0;padding:0}
.slick-list:focus{outline:0}
.slick-slider .slick-list,.slick-slider .slick-track{-webkit-transform:translate3d(0,0,0);-ms-transform:translate3d(0,0,0);transform:translate3d(0,0,0)}
.slick-track{position:relative;top:0;left:0;display:block}
.slick-track:after,.slick-track:before{display:table;content:&#39;&#39;}
.slick-track:after{clear:both}
.slick-slide{display:none;float:left;height:100%;min-height:1px}
.slick-slide.dragging img{pointer-events:none}
.slick-initialized .slick-slide{display:block}
.slick-vertical .slick-slide{display:block;height:auto;border:1px solid transparent}

.box1,.box10,.box11,.box2,.box3,.box4,.box5,.box6,.box7,.box8,.box9{overflow:hidden;position:relative}
.box-grid-s{position:relative;float:left;text-align:center;width:33.3333333%;background:#fab702;height:250px;padding:0;color:#021f2d;overflow:hidden}
.right,.right img{float:right}
.padding{padding:50px}
.box-grid-s h4,.box-grid-s p{z-index:50;position:relative}
.box-grid-s h4{font-size:30px;line-height:1em;font-weight:200}
.box-grid-s p{margin:0;font-size:16px;font-weight:300}
.tengah{color:#fff;background:#021f2d}
.left,.right{width:48%}
.boxwhite{background:#fff}
.right img{width:100%;height:auto}
.about,.box-list,.left{float:left}
.box2{width:100%;overflow:hidden;padding:5rem 0;margin:0}
.left-heading{font-weight:800;font-size:24px;color:#021f2d;position:relative;padding-bottom:25px}
.left-heading:after{content:&#39;&#39;;width:45px;height:3px;background:#fab702;position:absolute;top:38px;left:0}
.box2 .left p{font-size:16px;color:#4a4a4a;font-weight:400;line-height:29px;margin:0 0 10px}
.box-grid-list{overflow:hidden;margin:40px 0 30px;position:relative;display:block}
.box-list{width:50%}
.box-list h3.lefth3{font-weight:700;font-size:14px;margin-bottom:20px}
.box-list h3.lefth3 i{color:#fab702;margin-right:5px}

.box-btn{margin:0 0 0 10px}
.btn-effect{letter-spacing:2px;position:relative}
.btn-effect:after,.btn-effect:before{-webkit-transition:all .25s;transition:all .25s;border-style:solid;border-width:0;content:&quot;&quot;;height:24px;position:absolute;width:24px}
.brand-box:hover,.polio li .recent-content{-webkit-transition:all .5s ease-out;-moz-transition:all .5s ease-out;-ms-transition:all .5s ease-out;-o-transition:all .5s ease-out}
.btn-effect:before{border-color:#fab702;border-left-width:2px;border-top-width:2px;left:-5px;top:-5px}
.btn-effect:after{border-bottom-width:2px;border-color:#fab702;border-right-width:2px;bottom:-5px;right:-5px}
.btn-effect:hover:after,.btn-effect:hover:before{height:100%;width:100%}
.site-button{padding:10px 20px;display:inline-block;font-size:14px;cursor:pointer;outline:0;border-width:0;border-style:solid;border-color:transparent;line-height:1.42857;margin-left:-1px;text-decoration:none!important}
a.site-button{background-color:#fab702;color:#021f2d}
.active&gt;.site-button,.site-button:active,.site-button:focus,.site-button:hover{background-color:#f5bf23;color:#fff}
.readbtn{margin-top:15px;margin-left:5px}
.site-button:hover{background-color:#021f2d;color:#fff}
.site-button.btn-effect:after,.site-button.btn-effect:before{border-color:#f5bf23}
.site-button:hover.btn-effect:after,.site-button:hover.btn-effect:before{border-color:#021f2d}

#profile{background:#fab702;overflow:hidden;margin:30px 0;padding:20px}
.about{width:490px}
.about .photo-inner{float:left;width:190px;padding:0}
.about .photo-inner img{background-color:#ffcc42;width:100%;height:auto;margin:0 auto;padding:5px}
.about h1,.about h3{margin-bottom:0!important;text-transform:uppercase}
.about h1{color:#fff!important;line-height:30px!important;margin-top:8px!important;font-size:35px!important}
.about h3{font-size:21px;font-weight:500;color:#fff;padding:0}
.about p{font-size:14px;color:#021f2d;font-weight:400;line-height:20px;margin:0}
.personal-info{float:right;background:url(https://1.bp.blogspot.com/-BjJ2Ka91LMk/Xh1xl89sQlI/AAAAAAAAB5A/hPET4R6dp3cFGWiBKYvkFQGhm7E2Z3G7wCLcBGAsYHQ/s1600/list.png) left top no-repeat;padding:0 0 0 20px!important;margin-top:0!important}
.personal-info li{font-size:14px;overflow:hidden}
.personal-info li label{color:#021f2d;float:left;padding:4px 7px;font-weight:800;font-size:14px;border-radius:3px;-moz-border-radius:3px;-webkit-border-radius:3px}
.personal-info li span{float:right;width:220px;padding-top:4px;font-weight:300;color:#021f2d}
.profilimg{display:block;text-align:start;position:relative;z-index:auto;float:left;width:160px;height:100%;margin:5px 0 0}

.company-wrapper h2,.profilimg ul li:before,ul.personal-info li:before{display:none}
.profilimg ul{text-align:left;float:none;position:absolute;top:0;right:auto;bottom:auto;left:0;margin:0;width:765px;height:188px}
.box3 p,.brand-box img,h2.section-title,p.nmsp{text-align:center}
p.nmsp{font-size:15px;position:relative;margin:5px auto}
p.nmsp:after{content:&quot;&quot;;height:1px;width:50px;position:absolute;bottom:-6px;left:0;right:0;margin:0 auto;background:#fab702}
.brand-box{border:2px solid #fff;padding:10px 20px;margin:0 auto}
.brand-box img{height:auto;width:100%;margin:0 auto;position:relative}
.brand-box:hover{background:#021f2d;border:2px solid #021f2d;transition:all .5s ease-out}
.box3{width:100%;overflow:hidden;padding:0;margin:0;z-index:1}
.box3 p{color:#555;line-height:24px;font-size:14px;padding:0 15rem}
h2.section-title{color:#021f2d;font-weight:900;font-size:31px;text-transform:uppercase;letter-spacing:1px}
.theme_color{color:#fab702}
.company-wrapper{overflow:hidden;margin-top:3rem}

.polio li:hover .recent-content{padding-bottom:15px}
.polio ul li{width:25%;height:240px;overflow:hidden;float:left;display:inline-block;position:relative;padding:0;margin:0}
.polio ul li .box-image{width:100%;height:100%;display:block}
.polio li .recent-content{opacity:0;top:50%;transform:translateY(-50%);-ms-transform:translateY(-50%);-webkit-transform:translateY(-50%);position:absolute;text-align:center;right:0;left:0;z-index:2;transition:all .5s ease-out}
.polio li:hover .recent-content,.polio-overlay{-webkit-transition:all .5s ease-out;-moz-transition:all .5s ease-out;-ms-transition:all .5s ease-out;-o-transition:all .5s ease-out}
.polio li:hover .recent-content{opacity:1;transition:all .5s ease-out}
.category-polio a{display:block;font-size:14px;color:#ffe802;font-weight:700;line-height:1.5em;margin:10px 0}
.polio h3.recent-title{margin:0}
.polio .recent-title a{display:inline-block;font-size:17px;padding:0 20px;color:#fff;font-weight:700;line-height:1.5em;margin:0;text-transform:uppercase}
.polio-overlay{filter:alpha(opacity=50);opacity:.2;z-index:1;position:absolute;height:100%;width:100%;background-color:rgba(253,194,54,.8);transition:all .5s ease-out}
.content-overlay,.polio li:hover .polio-overlay{-webkit-transition:all .5s ease-out;-moz-transition:all .5s ease-out;-ms-transition:all .5s ease-out;-o-transition:all .5s ease-out}
.polio li:hover .polio-overlay{opacity:1;transition:all .5s ease-out}

.widget-download-wrapper{border:4px solid #fbbe3f;padding:13px;margin-bottom:10px}
.widget-download-wrapper:last-child{margin-bottom:0}
.widget-download-wrapper .widget-download-icon{color:#fbbe3f;float:left}
.widget-download-wrapper .widget-download-icon i{margin-right:12px;font-size:30px}
.widget-download-wrapper .widget-download-title{font-size:14px;line-height:17px;color:#2a2f35}
.widget-download-wrapper .widget-download-title a{color:#2a2f35}
.widget-download-link-wrapper .widget-download-title a:hover{color:#fbbe3f;text-decoration:none}
.widget .widget-download-wrapper .widget-download-title a:hover{text-decoration:none}
.widget-download-wrapper .widget-download-subtitle{font-size:12px;line-height:14px;color:#828282}
.widget-download-wrapper .widget-download-details{display:table}

.recentlist{position:relative;overflow:hidden}
.recentlist .recent-date,.recentlist h2{display:none}
.recentlist ul{margin:0}
.recentlist ul li{background:#fff;width:31.625%;height:330px;overflow:hidden;float:left;display:inline-block;position:relative;padding:0;margin:10px}
.boxall{position:relative;height:220px;width:100%}
.recentlist ul li .box-image{width:100%;height:100%;display:block}
.recentlist ul li p{padding:0 20px;text-align:left;color:#555;line-height:1.5;font-size:14px;position:relative}
.recentlist .recent-content{position:absolute;bottom:20px;left:20px;z-index:2;padding:10px;text-align:left;box-sizing:border-box}
.recentlist .recent-content h3.recent-title{margin:15px 0;line-height:1.4em;color:#fff}
.recentlist .recent-content h3.recent-title a{color:#fff;font-weight:400;font-size:21px;line-height:1.1;font-family:Muli,sans-serif;text-transform:uppercase}

a.Architecture:before,a.Building:before,a.Construction:before,a.House:before,a.Interior:before,a.Planning:before{font-family:&quot;Font Awesome 5 Pro&quot;}
.category-gallery a:before{display:block;color:#fab702;font-size:31px;font-weight:400;text-transform:uppercase;transition:all .3s ease}
a.Construction:before{content:&quot;\f85d&quot;}
a.House:before{content:&quot;\f015&quot;}
a.Architecture:before{content:&quot;\f0e8&quot;}
a.Interior:before{content:&quot;\f8ef&quot;}
a.Building:before{content:&quot;\f552&quot;}
a.Planning:before{content:&quot;\f61c&quot;}

a.asmall{padding:4px 10px;font-size:12px}
.content-overlay{filter:alpha(opacity=50);opacity:.6;z-index:1;position:absolute;height:100%;width:100%;background-color:#000;transition:all .5s ease-out}
.recentlist ul li:hover .content-overlay{opacity:.4;-webkit-transition:all .5s ease-out;-moz-transition:all .5s ease-out;-ms-transition:all .5s ease-out;-o-transition:all .5s ease-out;transition:all .5s ease-out}

.FollowByEmail .follow-by-email-inner .follow-by-email-address{width:100%;height:40px;background:#fff;font-size:13px;border:none;padding:0 10px;outline:0}
.FollowByEmail .follow-by-email-inner .follow-by-email-submit{margin-left:13px;border:0;width:auto;border-radius:0;background:#fab702;color:#021f2d;cursor:pointer;font-size:13px;font-weight:600;height:40px;padding:0 10px;z-index:0;text-align:center;outline:0;text-transform:uppercase}
.FollowByEmail .follow-by-email-inner input{font-family:Poppins,sans-serif}

.accordion__item&gt;.accordion-header:after,.backtop:before,.box-testimonial .NextArrow:before,.box-testimonial .PrevArrow:before,.boxteam .NextArrow:before,.boxteam .PrevArrow:before,.post ul li:before,.post-body blockquote::before{font-family:&quot;Font Awesome 5 Pro&quot;}
.FollowByEmail .follow-by-email-inner table,.FollowByEmail .follow-by-email-inner table td{width:100%}
.box4{padding:0}
.company-right{float:right;width:60%}
.company-left{float:left;background:url(https://1.bp.blogspot.com/-gd-vdeiK9oY/Xh1NmGB9oaI/AAAAAAAAB20/Q1DOFQzRK0EbPTP_KDh2kqlAO7U61nJIQCLcBGAsYHQ/s1600/bgleft.jpg) left top no-repeat;background-size:75%}
.padding-percent5{padding:16%}
.box-company-right{float:left;width:50%;height:360px;text-align:center;background:#f9f9f9}
.bgcolor{background:#f1f1f1!important}
.bgcolor2{background:#04283a!important}
.bgcolor3{background:#021f2d!important}
.box-company-right h4{text-transform:uppercase;font-size:20px;font-weight:800;line-height:120%;margin:15px 0}
.box-company-right p{color:#727272;margin:0 0 10px;font-size:14px}
.bg,.box5{padding:0;margin:0}
.box-company-right i{font-size:50px;color:#fab702}
.accordion-header,.putih,.text p{color:#fff}
.box5{background:#021f2d}
.bg{position:relative;width:100%;left:0;top:0;float:left;z-index:2;background:url(https://1.bp.blogspot.com/-SesNFKVuyVQ/Xh1S-YZDEbI/AAAAAAAAB4Y/64nUUvI4CpE0cHmpBS3cbsIENgatV2j5gCLcBGAsYHQ/s1600/bgmap.png) center no-repeat fixed;background-origin:initial;background-clip:initial;background-size:contain}
.bgopacity{padding:5rem 0;background-color:#001925}
h2.section-title2{color:#fff;font-weight:900;font-size:31px;letter-spacing:1px}
.accordion{font-size:1rem;margin:0 auto;background:rgba(0,44,66,.62)}
.accordion-header{padding:10px 20px;cursor:pointer;font-size:15px;font-weight:400;transition:all .3s}
.accordion-body{background:#fab702;display:none}
.accordion-body__contents{padding:1.5em;font-size:14px;color:#021f2d;font-weight:500}
.accordion__item .accordion__item .accordion-header{background:#fff;color:#021f2d;padding:10px 20px;font-size:14px}
.accordion__item.active:last-child .accordion-header{border-radius:0}
.accordion:first-child&gt;.accordion__item&gt;.accordion-header{border-bottom:1px solid transparent}
.accordion__item&gt;.accordion-header:after{content:&quot;\f067&quot;;float:right;position:relative;top:-2px;transition:.3s all;transform:rotate(0);font-size:13px;font-weight:400}
.accordion__item.active&gt;.accordion-header:after{content:&quot;\f068&quot;;font-family:&quot;Font Awesome 5 Pro&quot;}
.company-flex{overflow:hidden;color:#fff;font-size:14px}
.company-flex-list li{margin:20px 0}
.company-flex-list li strong{display:block;font-size:18px;font-weight:700;color:#fab702;margin:5px 0}
.box6{padding:5rem 0;background-size:initial;background-repeat:no-repeat;background-color:#f9f5e9;background-image:url(https://1.bp.blogspot.com/-2GcDSieSyLQ/Xh1RLPfVarI/AAAAAAAAB4E/VEEgqHrbfO4yt4eXe5oPOj3Hqjs5MmP8wCLcBGAsYHQ/s1600/bglist.png);background-attachment:scroll}
p.main-text{color:#555;text-align:center;line-height:24px;font-size:14px;padding:0 15rem}
.box8{padding:0}
.box-right{float:right;padding:5rem 0}
.box-left{float:left;background:#021f2d;padding:5rem 0}
.box-left,.box-right{width:50%}
.company-box{width:100%;overflow:hidden}
.bg-color{width:50%;height:100%;position:absolute;left:0;top:0;z-index:-1}
.bg-dark{background-color:#021f2d}
.quote,.quote:after{background-color:#f9f9f9}
.quote{position:relative;padding:25px;margin-bottom:30px;border-radius:5px}
.quote p{color:#333;margin:0;font-size:15px}
.quote:after{content:&#39;&#39;;width:25px;height:25px;-webkit-transform:rotate(45deg);transform:rotate(45deg);position:absolute;left:45px;bottom:-13px}
.student{overflow:hidden;display:block;padding:0 20px}
.student .photo{width:80px;height:80px;float:left;border-radius:100px;margin-right:10px;border:3px solid #f0f0f0}
.student .photo img{width:100%;height:100%;border-radius:100px}
.student p{position:relative;top:5px;text-transform:uppercase;font-weight:800;font-size:14px;line-height:1.2;color:#333;margin-bottom:7px}
.box-testimonial{margin:20px}
.testimonial{margin:10px}
.rating{margin-left:5px}
.rating li{display:inline-block;margin-right:-1px;font-size:13px}
.rating li i{color:#fab702}

.box-testimonial .NextArrow,.box-testimonial .PrevArrow{background-color:#fab702;display:block;text-align:center;width:35px;outline:0;height:35px;line-height:35px;color:#021f2d;cursor:pointer;font-size:18px;border:none;position:absolute;bottom:20%;transition:all .3s linear}
.box-testimonial .PrevArrow{right:50px}
.box-testimonial .NextArrow{right:10px}
.box-testimonial .PrevArrow:before{content:&#39;\f104&#39;}
.box-testimonial .NextArrow:before{content:&#39;\f105&#39;}

.marginleft{margin-left:5%;margin-bottom:0}
.title-skills{font-size:2em;text-transform:uppercase;letter-spacing:10px;transition:all .4s ease-in-out;margin:4rem auto;text-align:center}
.bar{margin:30px 30px 30px 0}
.skill{color:#fff;font-weight:800;font-size:15px;text-transform:uppercase;margin-bottom:.25em}
.speech-bubble{font-size:.75em;line-height:2em;position:absolute;top:-2.7em;text-align:center;min-width:3em;border-radius:.3em;display:none}
.boxteam,.col_fourth i,.team_content,.team_photo,.team_social{display:block}
.factory{left:calc(75% - 1.5em)}
.fluent{left:calc(55% - 1.5em)}
.construction{left:calc(90% - 1.5em)}
.indesign{left:calc(85% - 1.5em)}
.speech-bubble:after{border:.5em solid transparent;content:&quot;&quot;;margin-left:-.5em;position:absolute;top:100%;left:50%}
.bar-inner,.bar-outer{height:5px;border-radius:.3em}
.bar-outer{background:#132f3c;position:relative}
.bar-inner{width:0}
.col_fourth,.team_list{width:23%;position:relative;float:left}
.factory,.ph{background:#104eb9}
.factory:after{border-top-color:#104eb9}
.construction,.il{background:#fab702}
.construction:after{border-top-color:#fab702}
.in,.indesign{background:#d200bb}
.indesign:after{border-top-color:#d200bb}
.fl,.fluent{background:#00adaa}
.fluent:after{border-top-color:#00adaa}

.col_fourth{margin:10px;text-align:center}
.counter{padding:0}
.count-text,.count-title{vertical-align:middle;font-size:35px;font-weight:800;color:#fab702;text-align:center;margin:20px 0}
.col_fourth i{font-size:40px;color:#fab702;margin:20px 0}
p.count-text{text-transform:uppercase;color:#fff;font-size:17px;padding:0!important;font-weight:700;line-height:1.1}

.box9{padding:5rem 0}
.boxteam{margin-top:2rem}
.team_list{margin:10px}
.team_photo{border:5px solid #fab702;border-radius:50%;width:130px;height:130px;right:0;clear:both;position:relative;margin:0 auto -50px;z-index:99;overflow:hidden}
.team_content-c{padding:55px 20px 20px;background:#fff}
.team_photo img{width:100%;height:100%}
.team_content p.deco{font-style:italic;text-align:center;font-size:14px}
.team_social{margin:0 auto;background:#fab702;position:relative;overflow:hidden;padding:0;text-align:center}
.team_social li{display:inline-block;margin:10px;text-align:center;position:relative}
#mapscon h2,#mapscon2 h2,.contact-form-widget img{display:none}
.team_social li a{color:#021f2d;font-size:21px}
h2.names{margin:20px auto 0;font-size:18px;text-align:center;text-transform:uppercase;font-weight:800}
.boxteam .NextArrow,.boxteam .PrevArrow{background:none;color:transparent;height:50px;line-height:50px;cursor:pointer;margin:0;border:none;opacity:0;position:absolute;font-size:30px;text-align:center;outline:0;top:50%;width:50px;z-index:9;border-radius:50%}
.bg10,.box-mc{position:relative}
.boxteam .NextArrow:hover,.boxteam .PrevArrow:hover{transition:all 1s;background:rgba(240,185,54,.58)}
.boxteam .PrevArrow:before{content:&#39;\f104&#39;}
.boxteam .NextArrow:before{content:&#39;\f105&#39;}
.boxteam .PrevArrow,.boxteam:hover .PrevArrow{left:20px;transition:all .5s}
.boxteam .NextArrow,.boxteam:hover .NextArrow{right:20px;transition:all .5s}
.boxteam:hover .NextArrow,.boxteam:hover .PrevArrow{background:rgba(0,0,0,.82);color:#fab702;opacity:1;transition:all 1s}
.bg10{width:100%;padding:5rem 0;margin:0;left:0;top:0;float:left;z-index:2;background:url(https://1.bp.blogspot.com/-sUpG37-GCtg/Xh1Qty7bu_I/AAAAAAAAB38/SgtFIUHq1ZEdnAM001zAb-0u4YY5D0d2QCLcBGAsYHQ/s1600/bgfoot.jpg) center no-repeat fixed;background-origin:initial;background-clip:initial;background-size:cover}
#mapscon .contact-form-widget,#mapscon2 .widget-content{box-shadow:0 20px 60px rgba(0,0,0,.06);padding:15px}
input.contact-form-button,input.contact-form-button-submit{padding:10px 55px!important;background:#fab702!important;color:#fff;text-transform:uppercase;cursor:pointer;font-weight:800;width:initial!important;transition:all .15s ease-in-out;-moz-transition:all .15s ease-in-out;border:none;-webkit-transition:all .15s ease-in-out;text-align:center;margin:0 auto}
#mapscon .contact-form-widget input,.contact-form-email-message{border:none;box-shadow:inset 0 0 0 1px rgba(0,0,0,.02),inset 1px 1px 5px rgba(0,0,0,.05);background:rgba(0,0,0,.02);outline:0;border-radius:2px;line-height:18px;padding:10px;margin:0 auto 37px;width:96%}
.backtop,.box11{background:#fab702}
.contact-form-widget p{margin:0 0 10px;font-size:14px;font-weight:600;text-transform:uppercase}
.box-mc{margin:50px 0 0;clear:both;display:block}
.box11{padding:3rem 0}
.customer-parnert .slick-slide{margin:0 20px;-webkit-filter:saturate(.1);filter:saturate(.1);-webkit-transition:all .5s ease-in-out;-moz-transition:all .5s ease-in-out;-ms-transition:all .5s ease-in-out;-o-transition:all .5s ease-in-out;transition:all .5s ease-in-out}
.customer-parnert{width:100%;height:auto;outline:0;overflow:hidden;overflow-x:hidden;white-space:nowrap;margin:0 auto}
#credit-right ul li{display:inline-block;margin:0 0 0 15px}

.backtop{position:fixed;text-align:center;opacity:0;overflow:hidden;z-index:99;color:#021f2d;width:50px;height:50px;line-height:50px;right:25px;bottom:-25px;text-transform:uppercase;-webkit-transition:all .5s ease-in-out;-moz-transition:all .5s ease-in-out;-ms-transition:all .5s ease-in-out;-o-transition:all .5s ease-in-out;transition:all .5s ease-in-out;-webkit-transition-delay:.2s;-moz-transition-delay:.2s;-ms-transition-delay:.2s;-o-transition-delay:.2s;transition-delay:.2s}
.backtop span{position:absolute;bottom:-7px;display:block;text-align:center;width:100%;font-size:12px;font-weight:700;text-transform:uppercase}
.backtop:before{display:block;content:&quot;\f106&quot;;font-size:17px;font-weight:400;margin-top:-5px}
.backtop:hover{background-color:#021f2d;transition:all .2s ease-in-out;transition-delay:0;color:#fff}
.backtop.show{visibility:visible;cursor:pointer;opacity:1;bottom:30px}

.container{position:relative;max-width:1170px;margin:0 auto}
.outer-wrapper{position:relative;width:100%;padding:0}
.main-wrapper{width:75%;margin:0;float:right;word-wrap:break-word;overflow:hidden}
.clr{clear:both;float:none}
h3.date-header{text-transform:none;color:#666;margin:0;font-size:13px;font-weight:400;margin-bottom:20px!important;}
#comments h4,.footer h2,.postage a,.postage span{text-transform:uppercase}

.post{margin:0;padding:0}
.post h1,.post h2{font-size:200%;color:#021f2d;line-height:initial;margin:0;padding:0}
.post h1 a,.post h1 a:visited,.post h1 strong,.post h2 a,.post h2 a:visited,.post h2 strong{display:block;text-decoration:none;color:#021f2d}
.post-body{margin:0;line-height:1.8em}
.post-body h1,.post-body h2,.post-body h3,.post-body h4,.post-body h5,.post-body h5{line-height:1.2em;display:block;margin:0 0 10px 0;padding:0 0 10px;position:relative;overflow:hidden}
.post-body h1:after,.post-body h2:after,.post-body h3:after,.post-body h4:after,.post-body h5:after,.post-body h6:after{display:inline-block;width:30%;border-bottom:2px dotted #fab702;z-index:1;content:&quot;&quot;;position:absolute;bottom:0;left:0}
.post-body blockquote{display:block;background:#f4f4f4;padding:25px 25px 25px 66px;margin:0;position:relative;color:#666}
.post-body blockquote::before{content:&quot;\f10d&quot;;font-size:38px;font-weight:700;color:#fab702;position:absolute;left:15px;top:25px}
.PopularPosts .item-snippet,.postmeta h3:before{display:none}
.postmeta h3 a{color:#666}
.post img,.sidebar img{max-width:100%;width:auto;border:0;height:auto}
.post ol,.post ul{margin:15px 0 5px 20px;padding:0 0 0 5px}
.post ul li:before{content:&#39;\f00c&#39;;color:#fab702;margin-right:10px}
.post ol{list-style:none;counter-reset:my-awesome-counter;display:block;flex-wrap:wrap}
.post ol li{counter-increment:my-awesome-counter;margin-bottom:.5rem}
.post ol li::before{content:&quot;0&quot;counter(my-awesome-counter);font-weight:800;margin-right:.5rem;line-height:1;color:#fab702}

#comments h4:after,#comments h4:before{content:&quot;&quot;;position:absolute;left:0;bottom:0}
#comments h4,.post ol li a,.post ul li a{font-weight:700}
#comments{clear:both;margin:35px auto;padding:0;list-style:none;position:relative}
#comments h4{line-height:1.2em;display:inline-block;margin:0 0 10px;position:relative;padding:5px 0;font-size:17px;color:#222}
#comments h4:before{display:block;right:0;z-index:0}
#comments h4:after{border-bottom:2px solid #fab702;display:inline-block;width:100%;z-index:1}
#comments-block .avatar-image-container,.comments .comments-content .comment-thread:empty{display:none}
#comment-editor,.comment-thread .user{position:relative}
.comments-content{padding:0 0 15px}
#comments-block{margin:15px 0}
.comment-body{padding:15px 0;margin:0}
.comment-body p{margin:0}
.comment-footer{margin:0 0 30px}
h4#comment-post-message{display:none;margin:0}
.comments{clear:both;margin-top:10px;margin-bottom:0}
.comments .comments-content{font-size:14px;margin-bottom:30px}
.comments .comments-content .comment-thread ol{text-align:left;margin:13px 0;padding:0;list-style:none}
.comments .comment-block{position:relative;margin-left:55px;margin-right:3px;padding:15px;word-break:break-word;border-radius:7px;box-shadow:0 2px 3px rgba(103,103,103,.06),0 2px 6px rgba(156,156,156,.1)}
.comments .comment-replies .comment-block{margin-left:50px}
.comments .comments-content .comment-replies{margin:10px 0 10px 45px}
.comments .comment-replybox-single{margin:20px 0}
.comments .comment-replybox-thread{margin:0}
.comments .comments-content .comment{margin-bottom:6px;padding:0}
.comments .comments-content .comment:first-child,.comments .comments-content .comment:last-child{padding:0;margin:0}
.comments .comments-content .inline-thread{background:#fff;margin:0}
.comments .comments-content .comment-header{font-size:14px;margin:0 0 5px}
.comments .comments-content .comment-content{margin:10px 0;text-align:left;line-height:1.4;font:400 13px/1.71em AcuminPro,arial,helvetica,sans-serif}
.comments .comments-content .datetime{float:right}
.comments .comments-content .datetime a{color:#555}
.comments .comments-content .user{font-weight:700;font-style:normal}
.comments .comment .comment-actions a{display:inline-block;font-size:13px;line-height:15px;margin:4px 8px 0 0}
.comments .continue a{display:inline-block;font-size:13px;padding:.5em}
.comments .comment .comment-actions a:hover,.comments .continue a:hover{color:#dd4a45}
.deleted-comment{font-style:italic;opacity:.5}
.comments .comments-content .loadmore{cursor:pointer;margin-top:3em;max-height:3em}
.comments .comments-content .loadmore.loaded{max-height:0;opacity:0;overflow:hidden}
.comments .continue,.comments .thread-chrome.thread-collapsed{display:none}
.comments .thread-toggle{display:inline-block}
.comments .thread-toggle .thread-arrow{display:inline-block;height:6px;margin:.3em;overflow:visible;padding-right:4px;width:7px}
.comments .thread-collapsed .thread-arrow,.comments .thread-expanded .thread-arrow{width:24px;height:24px;vertical-align:middle;display:inline-block}
.comments .hidden{display:none}
.item-control a,.secondary-text a.comment-reply{color:#909090;text-align:center;padding:0!important;font-weight:400;text-decoration:none}
.comment-thread .user,.comment-thread .user a{font-size:13px;font-weight:700;padding:0;text-decoration:none}
.secondary-text a.comment-reply{color:#777}
.item-control a:hover,.secondary-text a:hover.comment-reply{color:#000!important}
#comment-editor{width:100%!important;background:url(https://1.bp.blogspot.com/-kAp4OwqTq28/XhxAOb139ZI/AAAAAAAAB0o/F-S8gdjOSXwtilbEYncR5S7e2WQElHVYwCLcBGAsYHQ/s1600/loader.gif) 50% 25% no-repeat;max-height:310px!important;transition:all 1.3s ease-out}
.comment-thread .user a{color:#000}
.comment-thread .user a:hover{color:inherit}
.comment-thread .datetime a{text-decoration:none;color:#909090;font-size:11px;font-weight:400}
.comment-thread .datetime a:hover{color:#000}
.item-control{margin-left:0}
.thread-chrome a.comment-reply{margin-top:20px!important;display:block;text-align:center;border-radius:99em;background-color:#f4f4f4}
.thread-chrome a:hover.comment-reply{color:#999}
#comments .comments-content .icon.blog-author{width:18px;height:18px;line-height:18px;margin-left:5px;vertical-align:middle;margin-top:-5px;display:inline-block}
#comments .comments-content .icon.blog-author:before{content:&quot;\f005&quot;;font-family:&quot;Font Awesome 5 Pro&quot;;color:#fab702;font-size:11px;vertical-align:middle}
.comment .avatar-image-container{width:40px;height:40px;overflow:hidden;float:left;border-radius:99em}
#comments .comment-replies .comment-thread .comment .avatar-image-container img,.comment .avatar-image-container img{display:block;padding:0;margin:0 auto}
#comments .comment-replies .comment-thread .comment .avatar-image-container{width:35px;height:35px;max-width:35px;max-height:35px}
#comments .avatar-image-container img{width:40px;height:40px;max-width:40px;max-height:40px;background:url(https://1.bp.blogspot.com/-ITY2zUo6O8w/XhxBWisGHeI/AAAAAAAAB0w/a_379aQsD6E3RdyzR0zSSeZOBwX2L86pwCLcBGAsYHQ/s1600/no.jpg) center center no-repeat}
#comments .comment-replies .avatar-image-container img{width:35px;height:35px;max-width:35px;max-height:35px;background:url(https://1.bp.blogspot.com/-ITY2zUo6O8w/XhxBWisGHeI/AAAAAAAAB0w/a_379aQsD6E3RdyzR0zSSeZOBwX2L86pwCLcBGAsYHQ/s1600/no.jpg) center center no-repeat}
.threaded_comments_text{display:block;margin:20px 0}
.threaded_comments_text p{font-size:100%;line-height:inherit}
@media screen and (max-device-width:480px){.comments .comments-content .comment-replies{margin-left:0}}

.postage{margin:20px 0;overflow:hidden;display:block}
.postage a,.postage span{font-size:11px;margin-top:2px;margin-right:3px;font-weight:700;padding:5px 15px;border:1px solid #eee;color:#7a7a7a;-webkit-border-radius:3px;-moz-border-radius:3px;border-radius:3px}

.sidebar-wrapper{position:sticky;width:270px;font-size:13px;float:left;top:0;word-wrap:break-word;overflow:hidden}
#sidebar1 h2,#sidebar2 h2,#sidebar3 h2{font-size:17px;font-weight:700;font-family:Muli,sans-serif;text-transform:uppercase;margin:0}
#sidebar1 h2{color:#fff;border-bottom:1px solid #02834;padding:15px 20px}
#sidebar2 h2{color:#000;padding:10px 0}
#sidebar3 h2{color:#021f2d;border-bottom:1px solid #e9e9e9;padding:15px 20px}
#sidebar1{color:#021f2d;line-height:1em;margin:5px 0;font-size:14px}
#sidebar1 li{line-height:1.3em;margin:0;padding:7px 0}
#sidebar1 .widget{margin:25px 0 40px;padding:0;background-color:#021f2d}
#sidebar2 .widget{margin:0 0 40px}
#sidebar3 li{line-height:1.3em;margin:0;padding:7px 0}
#sidebar3 .widget{margin:0 0 40px;padding:0;background-color:#f5f5f5}
#sidebar1 .widget-content,#sidebar3 .widget-content{margin:0 auto;padding:0 20px}
#sidebar1 a:link,#sidebar1 a:visited{color:#e4e4e4;text-decoration:none;font-weight:400}
#sidebar3 a:link,#sidebar3 a:visited{color:#021f2d;text-decoration:none;font-weight:400}
.sidebar li a:hover,a.btsn{color:#fab702}
.sidebar ul{list-style:none;margin:0;padding:5px 0}

.sidebar-contact{background-image:url(https://1.bp.blogspot.com/-Qej3JfLg8a4/XhxTbuZZUfI/AAAAAAAAB08/-TeF6p5j3dM-vbrAVh8Mo-8-3qA1NQHIQCLcBGAsYHQ/s1600/sm.jpg);background-repeat:no-repeat;background-position:center center;background-size:cover;width:100%;height:300px;overflow:hidden;position:relative}
.bgs{background-color:#fab702;position:absolute;height:100%;width:100%;top:0;bottom:0;-webkit-transition:all .6s ease;transition:all .6s ease}
.bgs:hover{background-color:rgba(255,255,255,.73)}
.sidebar-contact-inside{padding:40px 40px 30px}
p.p-contact-inside{font-size:14px;margin:20px 0}
a.btsn{background-color:#021f2d}
.site-button.btsn:after,.site-button.btsn:before{border-color:#021f2d}
.sbtn{margin:30px 0}

#footer{background:#021f2d;width:100%;padding:0}
.footer-wrapper{color:#777;height:100%;line-height:2em;overflow:hidden;padding:0;font-size:14px}
.footer{float:left;width:23%;margin:10px}
.footer .widget{margin:40px 0}
.footer h2{margin-bottom:12px;line-height:1.3em;font-size:15px;color:#fff;font-weight:500}
.footer .widget-content{line-height:21px;color:#adb5b9}
.footer .widget-content img{width:100%;height:auto}
.footer ul{list-style:none;color:#777;margin:0;padding:0}
.footer li{color:#777;line-height:1.2em;margin:0;padding:10px 0}
.footer a:link,.footer li a:visited{color:#adb5b9;text-decoration:none;font-weight:600;position:relative;-webkit-transition:all .6s ease;transition:all .6s ease}
.footer li a::before{content:&quot;\f105&quot;;display:inline-block;font-family:&quot;Font Awesome 5 Pro&quot;;font-style:normal;font-weight:400;margin-right:10px;color:#fab702}
.footer li a:hover{color:#ccc}
.texfoot{position:relative;padding:0 0 0 20px}
.texfoot p i{margin-right:8px;position:absolute;left:0;padding-top:4px;font-size:13px}
.maps-bx{overflow:hidden;position:relative;clear:both;padding:45.5%}
.maps-bx iframe{left:0;top:0;height:100%;width:100%;position:absolute}
span.post-author{display:none}

.errorcompany{text-align:center;overflow:hidden;margin:0 auto}
.errorcompany i{font-size:88px;padding:20px 0;color:#fab702}
.errorcompany h4{font-size:18px}
.status-msg-body{text-align:center}

.YouTubePopUp-Wrap{position:fixed;width:100%;height:100%;background-color:rgba(0,0,0,.8);top:0;left:0;z-index:9999999999999}
.YouTubePopUp-animation{opacity:0;animation-name:YouTubePopUp}
@-webkit-keyframes YouTubePopUp{0{opacity:0}
100%{opacity:1}}
@keyframes YouTubePopUp{0{opacity:0}
100%{opacity:1}}
.YouTubePopUp-Content{max-width:680px;display:block;margin:0 auto;height:100%;position:relative}
.YouTubePopUp-Content iframe{max-width:100%!important;width:100%!important;display:block!important;height:480px!important;border:none!important;position:absolute;top:0;bottom:0;margin:auto 0}
.YouTubePopUp-Hide{animation-name:YouTubePopUpHide}
@-webkit-keyframes YouTubePopUpHide{0{opacity:1}
100%{opacity:0}}
@keyframes YouTubePopUpHide{0{opacity:1}
100%{opacity:0}}
.YouTubePopUp-Close{position:absolute;top:0;cursor:pointer;bottom:484px;z-index:10;right:-13px;margin:auto 0;width:24px;color:#fab702;height:24px;background:#fff;border-radius:50px;line-height:24px;text-align:center}
#blog-pager,#credit,.blog-pager{overflow:hidden;clear:both;position:relative}
.YouTubePopUp-Close:hover{opacity:.5}
.YouTubePopUp-Close:before{content:&quot;\f00d&quot;;font-family:&quot;Font Awesome 5 Pro&quot;}

#blog-pager,.blog-pager{display:none;text-align:center;margin:40px auto 60px}
.blog-pager a{background:#fab702;color:#021f2d;display:inline-block;overflow:hidden;text-align:center;list-style:none;padding:5px 10px}
.blog-pager a:hover{color:#fff}
.feed-links{clear:both;display:none}

#credit{font-size:13px;color:#e7e7e7;width:100%;padding:20px 0;line-height:18px;background:#001823}
#credit a,#credit a:hover{color:#e7e7e7;text-decoration:none}
#credit-right{float:right}
#credit-left{float:left}

.play-now,.play-now .icon{display:block;-webkit-transform:translateX(-50%) translateY(-50%);top:50%;left:50%}
.play-now .icon,a.more-button{color:#fff;line-height:50px;font-size:18px}
.video-box{text-align:center;overflow:hidden;position:relative;margin:0 auto 20px;background:url(https://1.bp.blogspot.com/-mtiR9iYavNc/XhxziM5FJgI/AAAAAAAAB2E/Liyh-50NWLU0tRHuuwEZ59lDKfZcefmugCLcBGAsYHQ/s1600/vdg.jpg) center no-repeat;background-origin:initial;background-clip:initial;background-size:cover;z-index:1;padding:0;height:200px;max-width:100%;width:100%}
.video-box .bg-transparent{background-color:rgba(31,23,0,.74);height:100%}
.play-now{position:absolute;border-radius:50%;z-index:10;width:60px;height:60px;transform:translateX(-50%) translateY(-50%);transform-origin:center center}
.morepost,.play-now .icon{position:absolute;z-index:1;text-align:center}
.play-now .icon{height:50px;width:48px;font-weight:400;background-color:#fab702;padding-left:2px;transform:translateX(-50%) translateY(-50%);-webkit-transform-origin:center;transform-origin:center center;-webkit-border-radius:50%;-moz-border-radius:50%;-ms-border-radius:50%;-o-border-radius:50%;border-radius:50%;-webkit-box-shadow:0 5px 10px 0 rgba(250,183,2,.4);-moz-box-shadow:0 5px 10px 0 rgba(250,183,2,.4);-ms-box-shadow:0 5px 10px 0 rgba(250,183,2,.4);-o-box-shadow:0 5px 10px 0 rgba(250,183,2,.4);box-shadow:0 5px 10px 0 rgba(250,183,2,.4)}
.play-now .ripple,.play-now .ripple:after,.play-now .ripple:before{position:absolute;top:50%;left:50%;height:50px;width:50px;-webkit-transform:translateX(-50%) translateY(-50%);transform:translateX(-50%) translateY(-50%);-webkit-transform-origin:center;transform-origin:center center;-webkit-border-radius:50%;-moz-border-radius:50%;-ms-border-radius:50%;-o-border-radius:50%;border-radius:50%;-webkit-box-shadow:0 0 0 0 rgba(250,183,2,.4);-moz-box-shadow:0 0 0 0 rgba(250,183,2,.4);-ms-box-shadow:0 0 0 0 rgba(250,183,2,.4);-o-box-shadow:0 0 0 0 rgba(250,183,2,.4);box-shadow:0 0 0 0 rgba(250,183,2,.4);-webkit-animation:ripple 3s infinite;-moz-animation:ripple 3s infinite;-ms-animation:ripple 3s infinite;-o-animation:ripple 3s infinite;animation:ripple 3s infinite}
.play-now .ripple:before{-webkit-animation-delay:.9s;-moz-animation-delay:.9s;-ms-animation-delay:.9s;-o-animation-delay:.9s;animation-delay:.9s;content:&quot;&quot;;position:absolute}
.play-now .ripple:after{-webkit-animation-delay:.6s;-moz-animation-delay:.6s;-ms-animation-delay:.6s;-o-animation-delay:.6s;animation-delay:.6s;content:&quot;&quot;;position:absolute}
@-webkit-keyframes ripple{70%{box-shadow:0 0 0 20px rgba(255,255,255,0)}
100%{box-shadow:0 0 0 0 rgba(255,255,255,0)}}
@keyframes ripple{70%{box-shadow:0 0 0 20px rgba(255,255,255,0)}
100%{box-shadow:0 0 0 0 rgba(255,255,255,0)}}

.morepost{right:0;left:0;bottom:0;top:40%}
a.more-button{display:table;width:50px;height:50px;text-align:center;margin:0 auto;border-radius:25px;background:rgba(0,0,0,.6);position:relative;opacity:0;-webkit-transition:all .6s ease;transition:all .6s ease}
.post:hover a.more-button{opacity:1}
a.more-button:hover{background-color:rgba(250,183,2,.8588235294117647)}

@media screen and (max-width:1170px){#cssmenu ul,.container,.header-wrapper{width:98%}
.recentlist ul li{width:31.54999%}
.main-wrapper{width:74%}}
@media screen and (max-width:1150px){.recentlist ul li{width:31.5%}}
@media screen and (max-width:1100px){.padding-percent5{padding:10%}
.company-left{background-size:85%}
.main-wrapper{width:73%}
.recentlist ul li{width:31.449%}
.about{float:left;width:100%;border-bottom:1px solid #ffcf4d;margin-bottom:20px;padding-bottom:20px}
.about .photo-inner{width:170px}
.profilimg{width:140px}
.personal-info{float:left;display:block;width:100%;background:none;padding:0!important;margin:0!important}}
@media screen and (max-width:1024px){#header img{height:55px}
.company-left{background-size:92%}
.recentlist ul li{width:31.3%}
.col_fourth{width:22%}
.main-wrapper{width:70%}}
@media screen and (max-width:991px){.recentlist ul li{width:31.2%}
.main-wrapper{margin:0 auto;width:95%;float:none}
.post-body h1,.post-body h2,.post-body h3,.post-body h4,.post-body h5,.post-body h6{line-height:1.2}
.footer{float:none;width:98%;margin:10px auto}
.img-mobile{display:none}
.left,.right{width:100%;float:none}
.company-left{background:none}
.company-right{float:none;width:100%}
.box-company-right{height:300px}
.bg-dark{background-color:#fff}
.box-left,.box-right{float:none;padding:5rem 3rem}
.box-left{width:100%}
.box-right{width:88%}}
@media screen and (max-width:970px){.recentlist ul li{width:31%}
@media screen and (max-width:800px){#cssmenu ul li,#cssmenu ul ul li,#cssmenu ul ul li:hover,.box-menu{background:#021f2d}
#menu .close:hover,.box-menu .btn-close:hover,.btn-open{cursor:pointer}
.headerpic-wrapper{width:100%;margin:0 auto}
.header-wrapper{margin-right:0;min-height:0;width:100%}
#header{text-align:center;width:100%;max-width:none}
#header-inner{margin:10px}
.box-grid-s{float:none;width:100%;height:auto}
.comslider .img-full .info{top:20%}
.comslider .img-full h1{font-size:40px}
.comslider .img-full p{margin:20px auto}
.box-slider,.comslider .img-full{height:400px}
.btn-open{font-size:26px;position:absolute;top:25px;left:15px;display:block;color:#fab702}
.box-menu{margin:0;top:0;left:0;z-index:1000;position:fixed;width:250px;height:100%;overflow-y:auto;transition:left .3s linear}
.box-menu .btn-close{font-size:17px;position:relative;text-align:center;color:#fab702;float:right;margin:10px;display:block;border:2px solid #fff;border-radius:50%;padding:5px;height:15px;line-height:15px;width:15px}
#btnsearch{margin:10px;right:0;top:0;position:absolute}
.box-close{left:-250px;transition:all .3s linear}
#cssmenu{float:none}
#cssmenu ul{width:100%;height:auto;-webkit-box-shadow:0 2px 8px 0 rgba(0,0,0,.15);box-shadow:0 2px 8px 0 rgba(0,0,0,.15)}
#cssmenu ul ul{-webkit-box-shadow:none;box-shadow:none;display:none;opacity:1;transform:translateY(0);transition:unset}
#cssmenu ul ul li{margin:0}
#cssmenu li:hover&gt;ul{transition-delay:0,0,0}
#cssmenu ul li{width:100%;border-top:1px solid #022536;border-bottom:1px solid #01121b}
#cssmenu&gt;ul&gt;li&gt;a{padding:0 20px;line-height:43px}
#cssmenu ul li.active a,#cssmenu&gt;ul&gt;li:hover&gt;a{color:#555}
#cssmenu ul ul li a{padding:0 25px}
#cssmenu ul li a,#cssmenu ul ul li a{width:100%;border-bottom:0;color:#fff}
#cssmenu ul li a:hover,#cssmenu ul ul li a:hover{color:#eee;border-bottom:none}
#cssmenu&gt;ul&gt;li{float:none;position:relative}
#cssmenu ul ul li.has-sub ul li a{padding-left:35px}
#cssmenu ul ul,#cssmenu ul ul ul{position:relative;left:0;width:100%;margin:0;text-align:left}
#cssmenu ul ul&gt;li.has-sub&gt;a::after,#cssmenu&gt;ul&gt;li.has-sub&gt;a::after{display:none}
#menu .close,#menu li,.menubtnone{display:block}
#cssmenu .submenu-button{position:absolute;z-index:99;right:0;top:0;cursor:pointer}
#cssmenu .submenu-button::after{content:&quot;\f078&quot;;font-family:&quot;Font Awesome 5 Pro&quot;;font-style:normal;font-weight:400;text-decoration:inherit;margin:0 20px;color:#555;line-height:42px}
#menu .close,.menubtnone,.menubtnone a{color:#fab702}
#cssmenu .submenu-opened::after{content:&quot;\f077&quot;}
#cssmenu ul ul .submenu-button::after{line-height:36px}
#cssmenu ul ul ul li.active a{border-left:none}
#cssmenu&gt;ul ul&gt;li.has-sub&gt;ul&gt;li.active&gt;a,#cssmenu&gt;ul&gt;li.has-sub&gt;ul&gt;li.active&gt;a{border-top:none}
.menubtnone{position:absolute;top:20px;right:7px;font-size:22px}
#menu{position:fixed;z-index:9999;top:0;left:0;width:100%;height:100%;background-color:#fff;-webkit-transition:all .1s ease-in-out;-moz-transition:all .1s ease-in-out;-o-transition:all .1s ease-in-out;-ms-transition:all .1s ease-in-out;transition:all .1s ease-in-out;-webkit-transform:translate(0,-100%) scale(0,0);-moz-transform:translate(0,-100%) scale(0,0);-o-transform:translate(0,-100%) scale(0,0);-ms-transform:translate(0,-100%) scale(0,0);transform:translate(0,-100%) scale(0,0);opacity:0}
#menu.open{-webkit-transform:translate(0,0) scale(1,1);-moz-transform:translate(0,0) scale(1,1);-o-transform:translate(0,0) scale(1,1);-ms-transform:translate(0,0) scale(1,1);transform:translate(0,0) scale(1,1);opacity:1;z-index:9999}
#menu .close{position:absolute;top:3%;right:2%;background-color:transparent;opacity:.8;font-size:40px;border:none;outline:0;z-index:9999}
#menu li.icon-box{display:block;font-size:15px;margin-right:0;margin-bottom:22px;width:100%}
#menu li.child{margin-right:0;padding-right:0;border-right:none}
#menu li.social{display:inline-block;text-align:center}
#menu li,#menu ul{width:97%}
.polio ul li{height:160px}
.polio .recent-title a{font-size:14px}
.box3 p,p.main-text{padding:0 5rem}
.recentlist ul li{width:100%;margin:0 auto 20px}
.comslider .NextArrow,.comslider .PrevArrow{display:none!important}
.main-wrapper{margin-left:0;width:100%}
.sidebar-wrapper{width:100%;margin:0 auto}
#credit-left,#credit-right{float:none;margin:0 auto 10px;text-align:center}}
@media all and(max-width:768px) and(min-width:10px){.YouTubePopUp-Content{max-width:90%}}
@media all and(max-width:600px) and(min-width:10px){.YouTubePopUp-Content iframe{height:320px!important}
.YouTubePopUp-Close{bottom:362px}}
@media all and(max-width:480px) and(min-width:10px){.YouTubePopUp-Content iframe{height:220px!important}
.YouTubePopUp-Close{bottom:262px}}
@media screen and (max-width:768px){.col_fourth{width:45%}
#cssmenu ul,.container,.header-wrapper{width:95%}}
@media screen and (max-width:640px){.box-left{width:90%}
.box-list{float:none;width:100%}
.box-testimonial{margin:0}}
@media screen and (max-width:600px){.box-slider,.comslider .img-full{height:315px}
.comslider .img-full p{line-height:1.4}
.img-full img{height:100%;min-width:100%;width:100%;display:block;max-width:none}
.comslider .img-full h1{font-size:30px}
.comslider .img-full .info{top:10%}
.polio ul li{width:50%}}
@media screen and (max-width:480px){.comslider .img-full p{margin:10px auto}
.box3 p,p.main-text{padding:0 1rem}
.box-company-right{height:auto;float:none;width:100%}}
@media screen and (max-width:414px){.comslider .img-full h1{margin:20px 0}
.comslider .img-full p{display:none}
.box-slider,.comslider .img-full{height:215px}
.slick-dots{bottom:15px}
.box-right{width:95%;padding:5rem 0}
.box-left{width:100%;padding:5rem 1rem}
.col_fourth{width:100%;height:auto;margin:0 auto 20px}
#mapscon .contact-form-widget input,.contact-form-email-message{width:94%}
.about h1{line-height:20px!important;font-size:24px!important}}
.about h3{font-size:13px}
</style>
<b:if cond='data:blog.pageType != &quot;static_page&quot; and data:blog.pageType != &quot;item&quot;'>
<style>
.main-wrapper{margin:5rem 0;float:none;width:100%}
.post{margin:10px;padding:0 0 20px;width:31.625266%;float:left;background:#f9f9f9;height:420px}
.post h2{line-height:1.2em;margin:8px 0;padding:0;font-size:20px;font-weight:400;letter-spacing:initial}
.post h2 a{color:#021f2d}
.post:hover h2 a{color:#fab702}
.post-body{color:#555;line-height:1.5;font-size:14px;padding:5px 20px 20px;position:relative}
.img-home{margin:0;padding:0;position:relative;height:220px;width:100%}
.img-home img{height:100%;width:100%;margin:0;z-index:1;-webkit-transition:all .5s ease-out;-moz-transition:all .5s ease-out;-ms-transition:all .5s ease-out;-o-transition:all .5s ease-out;transition:all .5s ease-out;-webkit-filter:brightness(.5);filter:brightness(.5)}
.post:hover .img-home img{-webkit-filter:brightness(.7);filter:brightness(.7)}
.post h2:after,.post h3:after,.post h4:after,.post h5:after,.post h6:after,.postmeta,.sidebar-wrapper{display:none}
.date_holder{background:#fab702;color:#fff;padding:0;position:absolute;z-index:1;bottom:0;left:0;text-align:center}
.date_holder .day,.date_holder .month{padding:10px;display:block;font-weight:700}
.date_holder .month{text-transform:uppercase;font-size:13px;background:#021f2d}
.date_holder .day{font-size:20px;margin-bottom:2px}

@media screen and (max-width:1170px){.post{width:31.54999%}}
@media screen and (max-width:1150px){.post{width:31.5%}}
@media screen and (max-width:1100px){.post{width:31.449%}}
@media screen and (max-width:1024px){.post{width:31.3%}}
@media screen and (max-width:991px){.post{width:31.2%}}
@media screen and (max-width:970px){.post{width:31%}.post h2{font-size:13px;}}
@media screen and (max-width:800px){.img-home,.post{height:auto;width:100%}post h2{font-size:20px;}.post{margin:0 auto 20px}.date_holder{bottom:5px}}
</style>
</b:if>
<script>
//<![CDATA[
function loadCSS(e,t,o){"use strict";var i=window.document.createElement("link"),s=t||window.document.getElementsByTagName("script")[0];i.rel="stylesheet",i.href=e,i.media="only x",s.parentNode.insertBefore(i,s),setTimeout(function(){i.media=o||"all"})}loadCSS("https://kit-pro.fontawesome.com/releases/v5.11.2/css/pro.min.css"),loadCSS("https://goomsite.github.io/cssslider.css"),"undefined"==typeof jQuery&&document.write('<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"><\/script>'),"undefined"==typeof jQuery&&document.write('<script src="//cdn.jsdelivr.net/jquery.slick/1.5.5/slick.min.js"><\/script>');
//]]>
</script>
&lt;/head&gt;&lt;!--<head/>--&gt;
<body itemscope='itemscope' itemtype='http://schema.org/WebPage'>
<header class='headerpic-wrapper header-fixed'>
             <div class='header-wrapper'>
                 <b:section class='header' id='header' maxwidgets='1' showaddelement='yes'>
                   <b:widget id='Header1' locked='true' title='Josmary Palencia (cabecera)' type='Header' version='1'>
                     <b:widget-settings>
                       <b:widget-setting name='displayUrl'>https://blogger.googleusercontent.com/img/a/AVvXsEhfNntQ4aSQDzeXm36bvSz9cQjEM-Dg8gYpDutwcB3O9x5uOxaeUf3dpwpVfA4d5BDhDREUkLE0btdpNojiQh9x9Ux2sCU8XcFh60d7BkgXctWS83h_s2XxEphElY_H1zs03EGeYDgKtswGkfnsu9Y0PKaUj5-c4bTlfl7oQftSOOnCTJ9QiMGYnKDJow=s332</b:widget-setting>
                       <b:widget-setting name='displayHeight'>269</b:widget-setting>
                       <b:widget-setting name='sectionWidth'>332</b:widget-setting>
                       <b:widget-setting name='useImage'>true</b:widget-setting>
                       <b:widget-setting name='shrinkToFit'>true</b:widget-setting>
                       <b:widget-setting name='imagePlacement'>REPLACE</b:widget-setting>
                       <b:widget-setting name='displayWidth'>332</b:widget-setting>
                     </b:widget-settings>
                     <b:includable id='main'>
  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
          <div id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
          <b:if cond='data:blog.pageType != &quot;item&quot;'>
          <h1 class='title' style='background: transparent; border-width: 0px'>
            <b:include name='title'/>
          </h1>
<b:else/>
          <p class='title' style='background: transparent; border-width: 0px'>
            <b:include name='title'/>
          </p>
</b:if>
            </div>
            <b:include name='description'/>
          </div>
        <b:else/>
          <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                        + &quot;background-position: &quot;                        + data:backgroundPositionStyleStr + &quot;; &quot;                        + data:widthStyleStr                        + &quot;min-height: &quot; + data:height                        + &quot;_height: &quot; + data:height                        + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
          <b:if cond='data:blog.pageType != &quot;item&quot;'>
          <h1 class='title' style='background: transparent; border-width: 0px'>
            <b:include name='title'/>
          </h1>
<b:else/>
          <p class='title' style='background: transparent; border-width: 0px'>
            <b:include name='title'/>
          </p>
</b:if>
            </div>
            <b:include name='description'/>
          </div>
        </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <b:if cond='data:blog.pageType != &quot;item&quot;'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
<b:else/>
        <p class='title'>
          <b:include name='title'/>
        </p>
</b:if>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
                     <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
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
<div class='menubtnone'><a href='#menu' title=''><i class='fal fa-signal-4'/></a></div>
<nav id='menu'>
<button class='close' type='button'>&#215;</button>
<ul>
<li class='icon-box'>
<i class='far fa-map-marker-alt'/>
<div class='icon-box__text'>
<span class='icon-box__title'>Dirección</span>
<span class='icon-box__subtitle'>Ejido 5111, Ve</span>
</div>
</li>
<li class='icon-box'>
<i class='fal fa-envelope'/>
<div class='icon-box__text'>
<span class='icon-box__title'>E-mail</span>
<span class='icon-box__subtitle'>Josmaryp93@gmail.com</span>
</div>
</li>
<li class='icon-box child'>
<i class='fal fa-phone'/>
<div class='icon-box__text'>
<span class='icon-box__title'>Contáctanos</span>
<span class='icon-box__subtitle'>+58-414-4626818</span>
</div>
</li>
<li class='social'><a href='https://www.facebook.com/josmary.palenciacentella' title=''><i class='fab fa-facebook-f'/></a></li>
<li class='social'><a href='https://www.twitter.com/Jossie21P' title=''><i class='fab fa-twitter'/></a></li>
<li class='social'><a href='https://www.instagram.com/josmisionera' title=''><i class='fab fa-instagram'/></a></li>
</ul>
</nav>
</div>

<span class='btn-open'><i class='fal fa-bars'/></span>
</header><!-- /header-wrapper -->
<div class='box-menu box-close'>
<span class='btn-close'><i class='fal fa-times'/></span>
<nav id='cssmenu'>
<ul>
<li><a class='menuactive' href='/' title=''>Inicio</a></li>
<li><a href='#' title=''>Portafolio</a>
<ul>
<li><a href='#' title=''>Corporate Identity</a></li>
<li><a href='#' title=''>Editorial Design</a></li>
<li><a href='#' title=''>Advertising Design</a></li>
<li><a href='#' title=''>Production and Audiovisual Edition</a></li>
<li><a href='#' title=''>Digital Marketing</a></li>
</ul>
</li>
<li><a href='#' title=''>About me</a></li>
<li><a href='#' title=''>Services</a>
<ul>
<li><a href='#' title=''>Submenu 1</a></li>
<li><a href='#' title=''>Submenu 2</a></li>
<li><a href='#' title=''>Submenu 3</a></li>
<li><a href='#' title=''>Submenu 4</a></li>
<li><a href='#' title=''>Submenu 5</a></li>
</ul>
</li>
<li><a href='#' title=''>Promotions</a></li>
<li class='request'><a href='#' title=''>Request a quote</a></li>
</ul>
<!-- menu navigasi header end -->
</nav>
</div>
<div class='clr'/>

<b:if cond='data:blog.canonicalUrl == data:blog.canonicalHomepageUrl'> 
<div class='box-slider'>
<div class='comslider'>
<div class='img-full'>
      <img alt='' src='https://i.postimg.cc/j2BpPjJm/alexander-shatov-mr4-JG4-SYOF8-unsplash-01.jpg'/>
      <div class='info'>
 <h3>MANEJO Y DISEÑO PARA</h3>
        <h1>REDES SOCIALES</h1>
        <p>Si quieres destacar en el mundo digital, es imprescindible tener un manejo estratégico y creativo en redes sociales.</p>
<div class='box-btn'>
<a class='site-button btn-effect btn-wp' href='#' title='more'>Leer más</a>
</div>
      </div>
    </div>
<div class='img-full'>
      <img alt='' src='https://i.postimg.cc/rsgJ2ZqJ/theme-photos-CGpif-H3-Fj-OA-unsplash-01.jpg'/>
      <div class='info'>
 <h3>DISEÑO Y CREACIÓN DE</h3>
        <h1>IDENTIDAD CORPORATIVA</h1>
        <p>Con nuestro servicio de diseño de identidad corporativa, tu presencia será imparable</p>
<div class='box-btn'>
<a class='site-button btn-effect btn-wp' href='#' title='more'>Leer más</a>
</div>
      </div>
    </div>
<div class='img-full'>
      <img alt='' src='https://i.postimg.cc/MKT2LhDv/slidebean-p2-E8-RQDZ-Zg-unsplash-01.jpg'/>
      <div class='info'>
 <h3>ESTRATEGIAS DE</h3>
        <h1>CREACIÓN DE CONTENIDO</h1>
        <p>La creación de contenido es una forma de expresión, una oportunidad de conectar con la audiencia</p>
<div class='box-btn'>
<a class='site-button btn-effect btn-wp' href='#' title='more'>Leer más</a>
</div>
      </div>
    </div>
</div>  
</div>

<div class='box1'>
<div class='box-grid'>
<div class='box-grid-s'>
<div class='padding'>
<h4>Architecture Design</h4>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Proin nibh augue conseqaut nibbhi ellit ipsum consectetur.</p>
</div>
</div>
<div class='box-grid-s tengah'>
<div class='padding'>
<h4>Building Construction</h4>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Proin nibh augue conseqaut nibbhi ellit ipsum consectetur.</p>
</div>
</div>
<div class='box-grid-s'>
<div class='padding'>
<h4>House Renovation</h4>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Proin nibh augue conseqaut nibbhi ellit ipsum consectetur.</p>
</div>
</div>
</div>
</div>
<div class='clr'/>

<div class='box2'>
<div class='container'>
<div class='right img-mobile'>
<img alt='' src='https://1.bp.blogspot.com/-BLbuoAx3rXs/Xh1PDkO0bcI/AAAAAAAAB3Y/7rTzoA7GlwsT-BXH46hMBC_PfVZJLXFvgCLcBGAsYHQ/s1600/bgright.png'/>
</div>
<div class='left'>
<h2 class='left-heading'>Welcome <span class='theme_color'>Sibling</span></h2>
<p>Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi  cillum dolore eu fugiat.</p>
<div class='box-grid-list'>
<div class='box-list'>
<h3 class='lefth3'><i class='far fa-check-circle'/> Consectetur adipiscing elit</h3>
</div>
<div class='box-list'>
<h3 class='lefth3'><i class='far fa-check-circle'/> Consectetur adipiscing elit</h3>
</div>
<div class='box-list'>
<h3 class='lefth3'><i class='far fa-check-circle'/> Consectetur adipiscing elit</h3>
</div>
<div class='box-list'>
<h3 class='lefth3'><i class='far fa-check-circle'/> Consectetur adipiscing elit</h3>
</div>
<div class='box-list'>
<h3 class='lefth3'><i class='far fa-check-circle'/> Consectetur adipiscing elit</h3>
</div>
<div class='box-list'>
<h3 class='lefth3'><i class='far fa-check-circle'/> Consectetur adipiscing elit</h3>
</div>
<div class='clr'/>
</div>
<div class='box-btn'>
<a class='site-button btn-effect' href='#' title='view all'>View All</a>
</div>
</div>
</div>

</div>
<div class='clr'/>

<div class='box3'>
<div class='container'>
<h2 class='section-title'>FEATURED <span class='theme_color'>WORKS</span></h2>
<p>We are focused on complying with quality the commitments assumed with our clients, seeking to exceed their expectations and offering them continuously and timely improvement solutions.</p>
</div>
        <div class='company-wrapper'> 
          <b:section class='mgbx' id='polio' showaddelement='yes'>
             <b:widget id='HTML1' locked='false' title='polio' type='HTML' version='1'>
               <b:widget-settings>
                 <b:widget-setting name='content'><![CDATA[<span data-type="polio" data-label="Work"></span>]]></b:widget-setting>
               </b:widget-settings>
               <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
             </b:widget>
           </b:section>
        </div>
</div>

<div class='clr'/>

<div class='box6'>
<div class='container'>
<h2 class='section-title'>Trabajos <span class='theme_color'>Destacados</span></h2>
<p class='main-text'>Estamos enfocados en cumplir con calidad los compromisos asumidos con nuestros clientes, buscando superar sus expectativas y ofreciéndoles continua y oportunamente soluciones de mejora.</p>
        <div class='company-wrapper'> 
          <b:section class='mgbx' id='services' showaddelement='yes'>
             <b:widget id='HTML2' locked='false' title='Serives' type='HTML' version='1'>
               <b:widget-settings>
                 <b:widget-setting name='content'><![CDATA[<span data-type="recentlist" data-label="Service" data-no="6"></span>]]></b:widget-setting>
               </b:widget-settings>
               <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
             </b:widget>
           </b:section>
        </div>
</div>
</div>

</b:if>

<footer id='footer'>
<div class='container'>
<div class='footer-wrapper'>
<b:section class='footer' id='footer1' preferred='yes'>
  <b:widget id='HTML4' locked='false' title='' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;img src=&quot;https://1.bp.blogspot.com/-csDynEog6IM/XhxoW1c8btI/AAAAAAAAB14/NcEDoEvhOkM-UupR_wquc8OHfcBPS_BkwCLcBGAsYHQ/s1600/logofooter.png&quot;/&gt;

We remain true to the same principles on which our company was founded over a hundred years ago.</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
  </b:widget>
</b:section>
<b:section class='footer' id='footer2' preferred='yes'>
  <b:widget id='HTML5' locked='false' title='TOP SERVICES' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;ul id=&quot;menu-footer&quot;&gt;
&lt;li&gt;&lt;a href=&quot;#&quot;&gt;Architecture Design&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&quot;#&quot;&gt;Building Construction&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&quot;#&quot;&gt;House Renovation&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&quot;#&quot;&gt;General Contracting&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&quot;#&quot;&gt;Construction Management&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&quot;#&quot;&gt;Preconstruction &amp; Planning&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&quot;#&quot;&gt;Special Projects&lt;/a&gt;&lt;/li&gt;
&lt;/ul&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
  </b:widget>
</b:section>
<b:section class='footer' id='footer3' preferred='yes'>
  <b:widget id='HTML6' locked='false' title='CONTACT INFO' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;p&gt;You can always contact with us via email or phone. Get in touch with contact and get a quote form.&lt;/p&gt;
&lt;div class=&quot;texfoot&quot;&gt;
&lt;p&gt;&lt;i class=&quot;fal fa-map-marker theme_color 
&quot;&gt;&lt;/i&gt;1220 Manado Trans Sulawesi, BolTim  38555&lt;/p&gt;
&lt;p&gt;&lt;i class=&quot;fal fa-phone-square theme_color 
&quot;&gt;&lt;/i&gt;0438-123-4567&lt;/p&gt;
&lt;p&gt;&lt;i class=&quot;fal fa-envelope theme_color 
&quot;&gt;&lt;/i&gt;contact@example.com&lt;/p&gt;
&lt;p&gt;&lt;i class=&quot;fal fa-fax theme_color 
&quot;&gt;&lt;/i&gt;
FAX: (123) 123-4567&lt;/p&gt;&lt;/div&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
  </b:widget>
</b:section>
<b:section class='footer' id='footer4' preferred='yes'>
  <b:widget id='HTML7' locked='false' title='Suport' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;img src=&quot;https://1.bp.blogspot.com/-2ATYBOdPuQg/Xh1SihYOfsI/AAAAAAAAB4Q/9k6HGYmwoVMXvt8kVbYZB8OS0D8m3TcuQCLcBGAsYHQ/s1600/world-map.png&quot;/&gt;
&lt;p&gt;Get in touch with contact and get a quote form.&lt;/p&gt;
&lt;div class=&quot;texfoot&quot;&gt;
&lt;p&gt;&lt;i class=&quot;far fa-clock&quot;&quot;&gt;&lt;/i&gt;Monday-Friday: 9am to 5pm&lt;/p&gt;
&lt;p&gt;&lt;i class=&quot;far fa-clock&quot;&gt;&lt;/i&gt;Saturday: 10am to 2pm&lt;/p&gt;
&lt;p&gt;&lt;i class=&quot;fal fa-times-circle&quot;&gt;&lt;/i&gt;Sunday: Closed&lt;/p&gt;
&lt;/div&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
  </b:widget>
</b:section>
<div class='clr'/>
</div>
</div>
<div id='credit'>
<div class='container'>
<div id='credit-right'>
<ul>
<li><a href='#' title=''>Privacy Policy</a></li>
<li><a href='#' title=''>Disclaimer</a></li>
<li><a href='#' title=''>Faq</a></li>
<li><a href='#' title=''>Blog</a></li>
</ul>
</div>
<div id='credit-left'>
&#169; Copyright <script>var creditsyear = new Date();document.write(creditsyear.getFullYear());</script> - <a expr:href='data:blog.homepageUrl' expr:title='data:blog.title'><data:blog.title/></a> | Distributed By <a href='https://www.jojo-themes.net/best-blogger-templates/' rel='dofollow' style='color:#ff4545;' target='_blank' title='JOJO Themes'>JOJO Themes</a>
</div>
</div>
<div class='backtop'><span>Top</span></div>
</div>
</footer>  
<script>
//<![CDATA[
// accordion
var accordion=function(){var o=$(".js-accordion"),c=o.find(".js-accordion-header"),e=($(".js-accordion-item"),{speed:400,oneOpen:!1});return{init:function(o){c.on("click",function(){accordion.toggle($(this))}),$.extend(e,o),e.oneOpen&&$(".js-accordion-item.active").length>1&&$(".js-accordion-item.active:not(:first)").removeClass("active"),$(".js-accordion-item.active").find("> .js-accordion-body").show()},toggle:function(o){e.oneOpen&&o[0]!=o.closest(".js-accordion").find("> .js-accordion-item.active > .js-accordion-header")[0]&&o.closest(".js-accordion").find("> .js-accordion-item").removeClass("active").find(".js-accordion-body").slideUp(),o.closest(".js-accordion-item").toggleClass("active"),o.next().stop().slideToggle(e.speed)}}}();$(document).ready(function(){accordion.init({speed:300,oneOpen:!0})});$("#toTop").click(function () {$("html,body").animate({scrollTop: 0}, 500);});

// btn menu
$(".btn-close").on("click",function(){$(".box-menu").addClass("box-close")}),$(".btn-open").on("click",function(){$(".box-menu").removeClass("box-close")});
!function(s){s.fn.menumaker=function(n){var e=s(this),o=s.extend({format:"dropdown",sticky:!1},n);return this.each(function(){s(this).find(".button").on("click",function(){s(this).toggleClass("menu-opened");var n=s(this).next("ul");n.hasClass("open")?n.slideToggle(150).removeClass("open"):(n.slideToggle(150).addClass("open"),"dropdown"===o.format&&n.find("ul").show())}),e.find("li ul").parent().addClass("has-sub"),multiTg=function(){e.find(".has-sub").prepend('<span class="submenu-button"></span>'),e.find(".submenu-button").on("click",function(){s(this).toggleClass("submenu-opened"),s(this).siblings("ul").hasClass("open")?s(this).siblings("ul").removeClass("open").slideToggle(150):s(this).siblings("ul").addClass("open").slideToggle(150)})},"multitoggle"===o.format?multiTg():e.addClass("dropdown"),!0===o.sticky&&e.css("position","fixed")})}}(jQuery),function(s){s(document).ready(function(){s("#cssmenu").menumaker({format:"multitoggle"})})}(jQuery);

// youtube
!function(o){"use strict";var e=o(document),u=function(o){if(o.match(/(youtube.com)/))var e="v=",u=1;else if(o.match(/(youtu.be)/)||o.match(/(vimeo.com\/)+[0-9]/))var e="/",u=3;else if(o.match(/(vimeo.com\/)+[a-zA-Z]/))var e="/",u=5;return o=o.split(e)[u]};o.fn.YouTubePopUp=function(a){var p=o.extend({autoplay:1},a),t=o(this);t.on("click",function(a){a.preventDefault();var i=t.attr("href"),c=u(i),n=c.replace(/(&)+(.*)/,"");if(i.match(/(youtu.be)/)||i.match(/(youtube.com)/))var m="https://www.youtube.com/embed/"+n+"?autoplay="+p.autoplay;else if(i.match(/(vimeo.com\/)+[0-9]/)||i.match(/(vimeo.com\/)+[a-zA-Z]/))var m="https://player.vimeo.com/video/"+n+"?autoplay="+p.autoplay;var s='<div class="YouTubePopUp-Wrap YouTubePopUp-animation"><div class="YouTubePopUp-Content"><span class="YouTubePopUp-Close"></span><iframe src="'+m+'" allowfullscreen></iframe></div></div>';o("body").append(s),o(".YouTubePopUp-Wrap").hasClass("YouTubePopUp-animation")&&setTimeout(function(){o(".YouTubePopUp-Wrap").removeClass("YouTubePopUp-animation")},600),e.on("click",".YouTubePopUp-Wrap, .YouTubePopUp-Close",function(){o(".YouTubePopUp-Wrap").addClass("YouTubePopUp-Hide").delay(515).queue(function(){o(this).remove()})})}),e.on("keyup",function(e){27==e.keyCode&&o(".YouTubePopUp-Wrap:visible").click()})}}(jQuery),$(function(){$(".js-modal-video").YouTubePopUp()});

// slider option
$(document).ready(function(){$(".comslider").slick({autoplay:!0,autoplaySpeed:9e3,speed:700,dots:!0,mobileFirst:!0,slidesToShow:1,slidesToScroll:1,fade:!0,pauseOnHover:!1,respondTo:"min",cssEase:"linear",prevArrow:'<button class="PrevArrow"></button>',nextArrow:'<button class="NextArrow"></button>'})}),$(document).ready(function(){$(".box-testimonial").slick({autoplay:!0,autoplaySpeed:9e3,speed:700,dots:!1,mobileFirst:!0,slidesToShow:1,slidesToScroll:1,fade:!1,pauseOnHover:!1,respondTo:"min",cssEase:"linear",prevArrow:'<button class="PrevArrow"></button>',nextArrow:'<button class="NextArrow"></button>'})}),$(document).ready(function(){$(".boxteam").slick({slidesToShow:4,slidesToScroll:1,autoplay:!0,autoplaySpeed:5e3,arrows:!0,dots:!1,prevArrow:'<button class="PrevArrow"></button>',nextArrow:'<button class="NextArrow"></button>',pauseOnHover:!1,responsive:[{breakpoint:768,settings:{slidesToShow:3}},{breakpoint:520,settings:{slidesToShow:1}}]})}),$(document).ready(function(){$(".customer-parnert").slick({slidesToShow:6,slidesToScroll:1,autoplay:!0,autoplaySpeed:4e3,arrows:!1,dots:!1,pauseOnHover:!0,responsive:[{breakpoint:768,settings:{slidesToShow:4}},{breakpoint:520,settings:{slidesToShow:3}}]})});

// recent
var no_image = "https://4.bp.blogspot.com/-SKh7CYM3lB0/WZlRLgH8wII/AAAAAAAACjQ/vx5PJdQYhSo136-Wg-A633KcElrfkHNNACLcBGAs/s1600/non.png";
var month_format = [, "Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sept", "Oct", "Nov", "Dec"];
$(".company-wrapper .HTML .widget-content").each(function(){var e=$(this).find("span").attr("data-label"),t=($(this).find("span").attr("data-no"),$(this).parent().attr("id")),a=$(this).find("span").attr("data-type");a.match("polio")&&$.ajax({url:"/feeds/posts/default/-/"+e+"?alt=json-in-script&max-results=8",type:"get",dataType:"jsonp",success:function(e){for(var a="",n="<ul>",r=0;r<e.feed.entry.length;r++){for(var i=0;i<e.feed.entry[r].link.length;i++)if("alternate"==e.feed.entry[r].link[i].rel){a=e.feed.entry[r].link[i].href;break}var s=e.feed.entry[r].title.$t,l=e.feed.entry[r].category[0].term,c=(e.feed.entry[r].author[0].name.$t,e.feed.entry[r].content.$t),d=$("<div>").html(c);if(c.indexOf("//www.youtube.com/embed/")>-1)var o=e.feed.entry[r].media$thumbnail.url,f=o;else if(c.indexOf("<img")>-1)var h=d.find("img:first").attr("src"),f=h;else var f=no_image;n+='<li><a class="box-image" href="'+a+'" style="background:url('+f+') no-repeat center center;background-size: cover" title="'+s+'"><span class="polio-overlay"/></a><div class="recent-content"><h3 class="recent-title"><a href="'+a+'" title="'+s+'">'+s+'</a></h3><div class="category-polio"><a href="/search/label/'+l+'">'+l+'</a></div></div><div class="clr"/></li>'}n+="</ul>",$(".company-wrapper .HTML .widget-content").each(function(){var e=$(this).parent().attr("id");e==t&&($(this).html(n),$(this).parent().addClass("polio"),$(this).find(".box-image").each(function(){$(this).attr("style",function(e,t){return t.replace("/default.jpg","/mqdefault.jpg")}).attr("style",function(e,t){return t.replace("s72-c","s1600")})}))})}})}),$(".company-wrapper .HTML .widget-content").each(function(){var e=$(this).find("span").attr("data-label"),t=$(this).find("span").attr("data-no"),a=($(this).prev("h2").text(),$(this).parent().attr("id")),n=$(this).find("span").attr("data-type");n.match("recentlist")&&$.ajax({url:"/feeds/posts/default/-/"+e+"?alt=json-in-script&max-results="+t,type:"get",dataType:"jsonp",success:function(e){for(var t="",n="<ul>",r=0;r<e.feed.entry.length;r++){for(var i=0;i<e.feed.entry[r].link.length;i++)if("alternate"==e.feed.entry[r].link[i].rel){t=e.feed.entry[r].link[i].href;break}var s=e.feed.entry[r].category[0].term,l=e.feed.entry[r].title.$t,c=e.feed.entry[r].content.$t,d=(e.feed.entry[r].author[0].name.$t,e.feed.entry[r].published.$t),o=d.substring(0,4),f=d.substring(5,7),h=d.substring(8,10),u=month_format[parseInt(f,10)]+" "+h+", "+o,p=$("<div>").html(c),y=c.replace(/<\S[^>]*>/g,"");if(50<y.length&&(y=y.substring(0,130)+"..."),-1<c.indexOf("//www.youtube.com/embed/"))var g=e.feed.entry[r].media$thumbnail.url;else g=-1<c.indexOf("<img")?p.find("img:first").attr("src"):no_image;n+='<li><div class="boxall"><span class="content-overlay"/><a class="box-image" href="'+t+'" style="background:url('+g+') no-repeat center center;background-size: cover" title="'+l+'"></a><div class="recent-content"><div class="category-gallery"><a class="icon '+s+'" href="/search/label/'+s+'"></a></div><h3 class="recent-title"><a href="'+t+'" title="'+l+'">'+l+'</a></h3><div class="category-recentlist"><a class="site-button btn-effect asmall" href="'+t+'" title="more"> Read More</a><span class="recent-date">'+u+"</span></div></div></div><p>"+y+'</p><div class="clear"/></li>'}n+="</ul>",$(".company-wrapper .HTML .widget-content").each(function(){$(this).parent().attr("id")==a&&($(this).html(n),$(this).parent().addClass("recentlist"),$(this).prev("h2").wrap('<div class="box-title"></div>'),$(this).find(".box-image").each(function(){$(this).attr("style",function(e,t){return t.replace("/default.jpg","/mqdefault.jpg")}).attr("style",function(e,t){return t.replace("s72-c","s1600")})}))})}})});

// menu
$(function(){$('a[href="#menu"]').on("click",function(e){e.preventDefault(),$("#menu").addClass("open"),$('#menu > form > input[type="search"]').focus()}),$("#menu, #menu button.close").on("click keyup",function(e){e.target!=this&&"close"!=e.target.className&&27!=e.keyCode||$(this).removeClass("open")})});

// timer
!function(t){function e(t,e){return t.toFixed(e.decimals)}t.fn.countTo=function(e){return e=e||{},t(this).each(function(){function n(){u+=l,f++,o(u),"function"==typeof a.onUpdate&&a.onUpdate.call(i,u),f>=r&&(c.removeData("countTo"),clearInterval(d.interval),u=a.to,"function"==typeof a.onComplete&&a.onComplete.call(i,u))}function o(t){var e=a.formatter.call(i,t,a);c.html(e)}var a=t.extend({},t.fn.countTo.defaults,{from:t(this).data("from"),to:t(this).data("to"),speed:t(this).data("speed"),refreshInterval:t(this).data("refresh-interval"),decimals:t(this).data("decimals")},e),r=Math.ceil(a.speed/a.refreshInterval),l=(a.to-a.from)/r,i=this,c=t(this),f=0,u=a.from,d=c.data("countTo")||{};c.data("countTo",d),d.interval&&clearInterval(d.interval),d.interval=setInterval(n,a.refreshInterval),o(u)})},t.fn.countTo.defaults={from:0,to:0,speed:1e3,refreshInterval:100,decimals:0,formatter:e,onUpdate:null,onComplete:null}}(jQuery),jQuery(function(t){function e(e){var n=t(this);e=t.extend({},e||{},n.data("countToOptions")||{}),n.countTo(e)}t(".count-number").data("countToOptions",{formatter:function(t,e){return t.toFixed(e.decimals).replace(/\B(?=(?:\d{3})+(?!\d))/g,",")}}),t(".timer").each(e)});

// progres
var skills={ht:75,jq:25,sk:90,ph:75,il:90,"in":85,fl:55};$.each(skills,function(i,e){var l=$("."+i);l.animate({width:e+"%"},3e3,function(){$(".speech-bubble").fadeIn()})});

// backtop
function scrollToTop(){verticalOffset="undefined"!=typeof verticalOffset?verticalOffset:0,element=$("body"),offset=element.offset(),offsetTop=offset.top,$("html, body").animate({scrollTop:offsetTop},600,"linear")}$(function(){$(document).on("scroll",function(){100<$(window).scrollTop()?$(".backtop").addClass("show"):$(".backtop").removeClass("show")}),$(".backtop").on("click",scrollToTop)});

// header
$(function(){var e=$(document).scrollTop(),o=$(".header-fixed").outerHeight();$(window).scroll(function(){var s=$(document).scrollTop();$(document).scrollTop()>=50?$(".header-fixed").css("position","sticky"):$(".header-fixed").css("position","sticky"),s>o?$(".header-fixed").addClass("scroll"):$(".header-fixed").removeClass("scroll"),s>e?$(".header-fixed").removeClass("no-scroll"):$(".header-fixed").addClass("no-scroll"),e=$(document).scrollTop()})});

// Comment
for(var content=document.getElementById("comments").getElementsByTagName("p"),i=0;i<content.length;i++)-1!==content[i].innerHTML.indexOf("</a>")&&(content[i].innerHTML="Sorry, may not enter an active link here! Your comment is automatically disabled");
//]]>
</script>
</body>
</HTML>
