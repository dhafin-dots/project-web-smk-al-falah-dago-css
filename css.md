s#art-main, table
{
   font-family: monospace;
   font-style: normal;
   font-weight: normal;
   font-size: 13px;
   text-align: justify;
}


html, body
{
   height:100%;
}

#art-main
{
   position: relative;
   z-index: 0;
   width: 100%;
   min-height: 100%;
   left: 0;
   top: 0;
   cursor:default;
   overflow:hidden;
}

body
{
   padding: 0;
   margin:0;
   width: 1349px;
   min-width: 1349px;
   color: #0F2A38;
      background-color: #C5C5AF;
   background-image: url('rabek.jpg');
   background-repeat: repeat;
}

.cleared
{
   display:block;
   clear: both;
   float: none;
   margin: 0;
   padding: 0;
   border: none;
   font-size: 0;
   height:0;
   overflow:hidden;
}

.reset-box
{
   overflow:hidden;
   display:table;
}

form
{
   padding: 0 !important;
   margin: 0 !important;
}

table.position
{
   position: relative;
   width: 100%;
   table-layout: fixed;
}

/* Start Box */
.art-box, .art-box-body {
   margin:0 auto;
   position:relative;
}
.art-box:before, .art-box:after, .art-box-body:before, .art-box-body:after {
   position:absolute;
   top:0;
   bottom:0;
   content:' ';
   background-repeat: no-repeat;
   line-height:0;
}
.art-box:before,.art-box-body:before{
   left:0;
}
.art-box:after,.art-box-body:after{
   right:0;
}
.art-box:before {
   overflow:hidden;
   background-position: bottom left;
   direction: ltr;
   z-index:-3;
}
.art-box:after {
   background-position: bottom right;
   z-index:-3;
}
.art-box-body:before, .art-box-body:after {
   background-repeat:repeat-y;
}
.art-box-body:before {
   background-position: top left;
   z-index:-3;
}
.art-box-body:after {
   background-position: top right;
   z-index:-3;
}

.art-box .art-box:before, .art-box .art-box:after, .art-box-body .art-box-body:before, .art-box-body .art-box-body:after {
   z-index:-2;
}
.art-box .art-box .art-box:before, .art-box .art-box .art-box:after, .art-box-body .art-box-body .art-box-body:before, .art-box-body .art-box-body .art-box-body:after {
   z-index:-1;
}
/* End Box */

/* Start Bar */
.art-bar {
   position:relative;
}
.art-bar:before, .art-bar:after {
   position:absolute;
   top:0;
   bottom:0;
   content:' ';
   background-repeat:repeat;
   z-index:-1;
}
.art-bar:before {
   left:0;
   background-position: top left;
}
.art-bar:after {
   right:0;
   background-position: top right;
}
/* End Bar */

li h1, .art-postcontent li h1, .art-blockcontent-body li h1 
{
   margin:1px;
} 
li h2, .art-postcontent li h2, .art-blockcontent-body li h2 
{
   margin:1px;
} 
li h3, .art-postcontent li h3, .art-blockcontent-body li h3 
{
   margin:1px;
} 
li h4, .art-postcontent li h4, .art-blockcontent-body li h4 
{
   margin:1px;
} 
li h5, .art-postcontent li h5, .art-blockcontent-body li h5 
{
   margin:1px;
} 
li h6, .art-postcontent li h6, .art-blockcontent-body li h6 
{
   margin:1px;
} 
li p, .art-postcontent li p, .art-blockcontent-body li p 
{
   margin:1px;
}

/* end Page */

/* begin Header */
div.art-header
{
   margin: 0 auto;
   position: relative;
   z-index: -5;
   width:995px;
   height: 225px;
   margin-top: 0;
   margin-bottom: 0;
}
.art-header-position
{
   position: absolute;
   top: 0;
   right: 0;
   left: 0;
} 

.art-header-wrapper 
{
   position: relative;
   top:0;
   width:1000px;
   margin:0 auto;
}
.art-header-inner 
{
   position: relative;
   margin: 0 6px;
}

.art-header:before
{
   position: absolute;
   display:block;
   content:' ';
   z-index:-2;
   top: 0;
   width:100%;
   height: 225px;
   background-image: url('bikers.jpg');
   background-repeat: no-repeat;
   background-position:top left;
}


/* end Header */

/* begin HeaderObject */
div.art-headerobject
{
   display: block;
   left: 67%;
   margin-left: -263px;
   position: absolute;
   top: 0;
   width: 394px;
   height: 225px;
   background-image: url('images/header-object.png');
}
/* end HeaderObject */

/* begin Flash */
#art-flash-area
{
   position: absolute;
   top: 0;
   left: 0;
   width: 988px;
   height: 225px;
   overflow: hidden;
}

#art-flash-container
{
   height: 247px;
   top: -10px;
   position: absolute;
   width: 988px;
   left: 50%;
   margin-left:-494px;
}

#art-flash-container div.art-flash-alt
{
   position: relative;
   width: 110px;
   height: 30px;
   margin: 0 auto;
   top: 10px;
}

/* end Flash */

/* begin Logo */
div.art-logo
{
   display: block;
   position: absolute;
   top: 93px;
   left: 0;
   margin-left: 12px;
   background-image: urlS('1.jpg');
}

.art-logo-name
{
   display: block;
   text-align: left;
   font-weight: bold;
   padding: 0;
   margin: 0;
   color: #0D2430 !important;
}
.art-logo-name a, 
.art-logo-name a:link, 
.art-logo-name a:visited, 
.art-logo-name a:hover
{
   font-weight: bold;
   padding: 0;
   margin: 0;
   color: #0D2430 !important;
}

.art-logo-text
{
   display: block;
   text-align: left;
   font-family: Tahoma, Arial, Helvetica, Sans-Serif;
   font-size: 14px;
   padding: 0;
   margin: 0;
   color: #0D2430 !important;
}
.art-logo-text a,
.art-logo-text a:link,
.art-logo-text a:visited,
.art-logo-text a:hover
{
   font-family: Tahoma, Arial, Helvetica, Sans-Serif;
   font-size: 14px;
   padding: 0;
   margin: 0;
   color: #0D2430 !important;
}

#headline, #slogan 
{
   display: block;
   min-width: 150px;
   text-align: left;
}
/* end Logo */

/* begin Menu */
/* menu structure */

ul.art-hmenu a, ul.art-hmenu a:link, ul.art-hmenu a:visited, ul.art-hmenu a:hover 
{
   outline: none;
   position: relative;
   z-index: 11;
}

ul.art-hmenu, ul.art-hmenu ul
{
   display: block;
   margin: 0;
   padding: 0;
   border: 0;
   list-style-type: none;
}

ul.art-hmenu li
{
   margin: 0;
   padding: 0;
   border: 0;
   display: block;
   float: left;
   position: relative;
   z-index: 5;
   background: none;
}

ul.art-hmenu li:hover{
   z-index: 10000;
   white-space: normal;
}
ul.art-hmenu li li{
   float: none;
   width: auto;
}
ul.art-hmenu li:hover>ul {
   visibility: visible;
   top: 100%;
}
ul.art-hmenu li li:hover>ul {
   top: 0;
   left: 100%;
}
ul.art-hmenu:after, ul.art-hmenu ul:after
{
   content: ".";
   height: 0;
   display: block;
   visibility: hidden;
   overflow: hidden;
   clear: both;
}
ul.art-hmenu, ul.art-hmenu ul {
   min-height: 0;
}

ul.art-hmenu ul
{
   visibility: hidden;
   position: absolute;
   z-index: 10;
   left: 0;
   top: 0;
   background-image: url('images/spacer.gif');
   padding: 10px 30px 30px 30px;
   margin: -10px 0 0 -30px;
}

ul.art-hmenu ul.art-hmenu-left-to-right {
   right: auto;
   left: 0;
   margin: -10px 0 0 -30px;
}
ul.art-hmenu ul.art-hmenu-right-to-left {
   left: auto;
   right: 0;
   margin: -10px -30px 0 0;
}

ul.art-hmenu ul ul
{
   padding: 30px 30px 30px 10px;
   margin: -30px 0 0 -10px;
   margin-left: -11px;
   z-index: -1;
}

ul.art-hmenu ul ul.art-hmenu-left-to-right
{
   right: auto;
   left: 0;
   padding: 30px 30px 30px 10px;
   margin: -30px 0 0 -10px;
   margin-left: -11px;
}

ul.art-hmenu ul ul.art-hmenu-right-to-left
{
   left: auto;
   right: 0;
   padding: 30px 10px 30px 30px;
   margin: -30px -10px 0 0;
   margin-right: -11px;
}

ul.art-hmenu li li:hover>ul.art-hmenu-left-to-right {
   right: auto;
   left: 100%;
}
ul.art-hmenu li li:hover>ul.art-hmenu-right-to-left {
   left: auto;
   right: 100%;
}

ul.art-hmenu{
   position:relative;
   padding: 6px 6px 12px 6px;
   float: left;
}

/* end menu structure */

/* menu bar */

.art-nav
{
   width:1000px;
   margin:0 auto;
   min-height: 50px;
   z-index: 100;
   margin-top: 3px;
   margin-bottom: -14px;
}

.art-nav:before, .art-nav:after{
   background-image: url('images/nav.png');
}
.art-nav:before{
   right: 11px;
}
.art-nav:after{
   width: 11px;
}
/* end menu bar */
.art-nav-outer{
   position:absolute;
   width:100%;
}
.art-nav-wrapper 
{
   position: relative;
   width:1000px;
   margin:0 auto;
}

.art-nav-inner{
   margin: 0 13px;
}

/* end Menu */

/* begin MenuItem */
ul.art-hmenu>li>a
{
   position: relative;
   display: block;
   height: 32px;
   cursor: pointer;
   text-decoration: none;
   color: #E0E0E0;
   padding: 0 18px;
   line-height: 32px;
   text-align: center;
}

ul.art-hmenu>li>a:before, ul.art-hmenu>li>a:after
{
   position: absolute;
   display: block;
   content:' ';
   top: 0;
   bottom:0;
   z-index: -1;
   background-color: #189fff:
}

ul.art-hmenu>li>a:before
{
   left: 0;
   right: 1px;
   background-position: top left;
}

ul.art-hmenu>li>a:after
{
   width: 1px;
   right: 0;
   background-position: top right;
}

.art-hmenu a, .art-hmenu a:link, .art-hmenu a:visited, .art-hmenu a:hover
{
   font-size: 18px;
   text-align: left;
   text-decoration: none;
  
}

ul.art-hmenu>li>a.active:before {
   background-position: bottom left;
} 
ul.art-hmenu>li>a.active:after {
   background-position: bottom right;
}
ul.art-hmenu>li>a.active {
   color: #fff;
}

ul.art-hmenu>li>a:hover:before, ul.art-hmenu>li:hover>a:before {
   background-position: center left;
}
ul.art-hmenu>li>a:hover:after, ul.art-hmenu>li:hover>a:after {
   background-position: center right;
}
ul.art-hmenu>li>a:hover, ul.art-hmenu>li:hover>a{
   color: #777;
}

/* end MenuItem */

/* begin MenuSeparator */
ul.art-hmenu>li:before
{
   position:absolute;
   display: block;
   content:' ';
   top:0;
   left:  -7px;
   width:300px;
   height: 32px;
   background-color:#00ff; center center no-repeat;
}

ul.art-hmenu>li {
   margin-left:7px;
}
ul.art-hmenu>li:first-child {
   margin-left:0;
}

ul.art-hmenu>li:first-child:before{
   display:none;
}
/* end MenuSeparator */

/* begin MenuSubItem */
.art-hmenu ul a
{
   display: block;
   white-space: nowrap;
   height: 25px;
   background-color: 33ff66;
   background-position: left top;
   background-repeat: repeat-x;
   border-width: 1px;
   border-style: solid;
   border-top-width: 0;
   border-color: #56A7D2;
   min-width: 7em;
   text-align: left;
   text-decoration: none;
   line-height: 25px;
   color: #1F1F1F;
   font-size: 11px;
   margin:0;
   padding: 0 12px;
}

.art-hmenu ul>li:first-child>a
{
   border-top-width: 1px;
}

.art-hmenu ul a:link, .art-hmenu ul a:visited, .art-hmenu ul a:hover, .art-hmenu ul a:active
{
   text-align: left;
   text-decoration: none;
   line-height: 25px;
   color: #1F1F1F;
   font-size: 11px;
   margin:0;
   padding: 0 12px;
}

.art-hmenu ul li a:hover
{
   color: #000000;
   background-position: left bottom;
   border-color: #82BEDE;
   border-top-width: 1px !important;
}

.art-hmenu ul li a.art-hmenu-before-hovered
{
   border-bottom-width: 0 !important;
}

.art-hmenu ul li:hover>a
{
   color: #000000;
   background-position: left bottom;
   border-color: #82BEDE;
   border-top-width: 1px !important;
}

/* end MenuSubItem */

/* begin Box, Sheet */
.art-sheet
{
   max-width:1000px;
   margin-top: 5px;
   margin-bottom: -5px;
   cursor:auto;
   width: 1000px;
}
.art-sheet-body 
{
   padding:13px;
   min-width:16px;
   min-height:16px;
   padding-top:13px;
   padding-bottom:13px;
}
.art-sheet:before, .art-sheet:after 
{
   content: url('images/sheet_t.png');
   font-size: 0;
   background-image: url('images/sheet_b.png');
}
.art-sheet:after{
   clip:rect(auto, auto, auto, 979px);
}
.art-sheet:before,.art-sheet-body:before{
   right:21px;
}
.art-sheet-body:after{
   width: 21px;
   top:21px;
   bottom:21px;
   background-image:url('images/sheet.png');
}
.art-sheet-body:before{
   top:21px;
   bottom:21px;
   background-image:url('images/sheet.png');
}

/* end Box, Sheet */

/* begin Layout */
.art-layout-wrapper
{
   position:relative;
   margin:0 auto 0 auto;
}

.art-content-layout
{
   display: table;
   width:100%;
   table-layout: fixed;
   border-collapse: collapse;
}

.art-content-layout-row {
   display: table-row;
}

.art-layout-cell
{
   display: table-cell;
   vertical-align: top;
}
/* end Layout */

/* begin Box, Block */
.art-block
{
   max-width:974px;
   margin: 5px;
}
.art-block-body 
{
   padding:5px;
   min-width:26px;
   min-height:26px;
}
.art-block:before, .art-block:after 
{
   content: url('images/block_t.png');
   font-size: 0;
   background-image: url('images/block_b.png');
}
.art-block:after{
   clip:rect(auto, auto, auto, 956px);
}
.art-block:before,.art-block-body:before{
   right:18px;
}
.art-block-body:after{
   width: 18px;
   top:18px;
   bottom:18px;
   background-image:url('images/block.png');
}
.art-block-body:before{
   top:18px;
   bottom:18px;
   background-image:url('images/block.png');
}

div.art-block img
{
   /* WARNING do NOT collapse this to 'border' - inheritance! */
  border-width: 1px;
   border-color: #33ff66;
   border-style: solid;
   margin: 10px;
}

/* end Box, Block */

/* begin BlockHeader */
.art-blockheader {
   margin-bottom: 2px;
   min-height: 38px;
   line-height:38px;
}
.art-blockheader:before, .art-blockheader:after{
   background-image: url('images/blockheader.png');
}
.art-blockheader:before{
   right: 25px;
}
.art-blockheader:after{
   width: 25px;
}

.art-blockheader .t
{
   min-height: 38px;
   line-height:38px;
   color: #000000;
   font-family: Tahoma, Arial, Helvetica, Sans-Serif;
   font-size: 14px;
   margin:0;
   padding: 0 10px 0 31px;
   white-space: nowrap;
}

.art-blockheader .t a,
.art-blockheader .t a:link,
.art-blockheader .t a:visited, 
.art-blockheader .t a:hover
{
   color: #000000;
   font-family: Tahoma, Arial, Helvetica, Sans-Serif;
   font-size: 14px;
}

/* end BlockHeader */

/* begin Box, BlockContent */
.art-blockcontent
{
   max-width:974px;
}
.art-blockcontent-body 
{
   padding:5px;
   color: #0F2A38;
   font-family: Tahoma, Arial, Helvetica, Sans-Serif;
   font-size: 12px;
}
.art-blockcontent-body table,
.art-blockcontent-body li, 
.art-blockcontent-body a,
.art-blockcontent-body a:link,
.art-blockcontent-body a:visited,
.art-blockcontent-body a:hover
{
   color: #0F2A38;
   font-family: Tahoma, Arial, Helvetica, Sans-Serif;
   font-size: 12px;
}

.art-blockcontent-body p
{
   margin: 0 5px;
}

.art-blockcontent-body a, .art-blockcontent-body a:link
{
   color: #A22101;
   text-decoration: underline;
}

.art-blockcontent-body a:visited, .art-blockcontent-body a.visited
{
   color: #525252;
   text-decoration: none;
}

.art-blockcontent-body a:hover, .art-blockcontent-body a.hover
{
   color: #D52B01;
   text-decoration: underline;
}

.art-blockcontent-body ul li
{
   font-size: 13px;
   line-height: 125%;
   color: #0F2A38;
   margin: 2px;
   padding: 0 0 0 2px;
   background-image: url('images/blockcontentbullets.png');
   background-repeat: no-repeat;
   background-position: top left;
}
/* end Box, BlockContent */

/* begin Button */
span.art-button-wrapper>a.art-button,
span.art-button-wrapper>a.art-button:link,
span.art-button-wrapper>input.art-button,
span.art-button-wrapper>button.art-button
{
   text-decoration: none;
   font-family: Tahoma, Arial, Helvetica, Sans-Serif;
   font-style: normal;
   font-weight: bold;
   font-size: 12px;
   text-transform: uppercase;
   position:relative;
   top:0;
   display: inline-block;
   vertical-align: middle;
   white-space: nowrap;
   text-align: center;
   color: #292929 !important;
   width: auto;
   outline: none;
   border: none;
   background: none;
   line-height: 32px;
   height: 32px;
   margin: 0 !important;
   padding: 0 19px !important;
   overflow: visible;
   cursor: pointer;
   text-indent: 0;
}

.art-button img, span.art-button-wrapper img
{
   margin: 0;
   vertical-align: middle;
}

span.art-button-wrapper
{
   vertical-align: middle;
   display: inline-block;
   position: relative;
   height: 32px;
   overflow: hidden;
   white-space: nowrap;
   text-indent: 0;
   width: auto;
   max-width:974px;
   margin: 0;
   padding: 0;
   z-index: 0;
}

.firefox2 span.art-button-wrapper
{
   display: block;
   float: left;
}

input, select, textarea
{
   vertical-align: middle;
   font-family: Tahoma, Arial, Helvetica, Sans-Serif;
   font-style: normal;
   font-weight: bold;
   font-size: 12px;
   text-transform: uppercase;
}

div.art-block select 
{
   width:96%;
}

span.art-button-wrapper.hover>.art-button, span.art-button-wrapper.hover>a.art-button:link
{
   color: #0E2734 !important;
   text-decoration: none !important;
}

span.art-button-wrapper.active>.art-button, span.art-button-wrapper.active>a.art-button:link
{
   color: #380B00 !important;
}

span.art-button-wrapper>span.art-button-l, span.art-button-wrapper>span.art-button-r
{
   display: block;
   position: absolute;
   top: 0;
   bottom: 0;
   margin: 0;
   padding: 0;
   background-image: url('images/button.png');
   background-repeat: no-repeat;
}

span.art-button-wrapper>span.art-button-l
{
   left: 0;
   right: 12px;
   background-position: top left;
}

span.art-button-wrapper>span.art-button-r
{
   width: 12px;
   right: 0;
   background-position: top right;
}

span.art-button-wrapper.hover>span.art-button-l
{
   background-position: center left;
}

span.art-button-wrapper.hover>span.art-button-r
{
   background-position: center right;
}

span.art-button-wrapper.active>span.art-button-l
{
   background-position: bottom left;
}

span.art-button-wrapper.active>span.art-button-r
{
   background-position: bottom right;
}

span.art-button-wrapper input
{
   float: none !important;
}
/* end Button */

/* begin Box, Post */
.art-post
{
   max-width:974px;
   margin: 5px;
}
.art-post-body 
{
   padding:21px;
}
.art-post:before, .art-post:after 
{
   content: url('images/post_t.png');
   font-size: 0;
   background-image: url('images/post_b.png');
}
.art-post:after{
   clip:rect(auto, auto, auto, 965px);
}
.art-post:before,.art-post-body:before{
   right:9px;
}
.art-post-body:after{
   width: 9px;
   top:9px;
   bottom:9px;
   background-image:url('images/post.png');
}
.art-post-body:before{
   top:9px;
   bottom:9px;
   background-image:url('images/post.png');
}

a img
{
   border: 0;
}

.art-article img, img.art-article, .art-block img, .art-footer img
{
   border-color: #C7C7C7;
   border-style: solid;
   border-width: 1px;
}

.art-metadata-icons img
{
   border: none;
   vertical-align: middle;
   margin: 2px;
}

.art-article table, table.art-article
{
   border-collapse: collapse;
   margin: 1px;
}

.art-post .art-content-layout-br
{
   height: 0;
}

.art-article th
{
   padding: 2px;
   border: solid 1px #B5B5B5;
   vertical-align: top;
   text-align: left;
}

.art-article th
{
   text-align: center;
   vertical-align: middle;
   padding: 7px;
}

pre
{
   overflow: auto;
   padding: 0.1em;
}

#preview-image
{
   float: left;
   }

.preview-cms-logo
{
   border: 0;
   margin: 1em 1em 0 0;
   float: left;
}

.preview-sharepoint-logo
{
   border: 0;
   margin: 5px;
   float: left;
}
/* end Box, Post */




.menu_content
   {
    background-image: url('bikers.jpg');
    background-repeat: no-repeat;
    background-position:top center;
    margin: 5px;
    width: 510px;
    height: 280px;
    
   } 
   



/* begin Footer */
.art-footer
{
   position: relative;
   margin-top:0;
   margin-bottom:0;
   width: 100%;
}

.art-footer-body
{
   position:relative;
   padding: 10px;
  color: #000;
 font-size: 18px;
}

.art-footer-body ul li
{
   font-size: 13px;
   line-height: 125%;
   color: #0D2430;
   margin: 5px 0 0 5px;
   padding: 0 0 0 13px;
   background-image: url('images/footerbullets.png');
   background-repeat: no-repeat;
   background-position: top left;
}

.art-footer-body:before
{
   position: absolute;
   content:' ';
   z-index:-2;
   left:0;
   right:0;
   top:0;
   bottom:0;
   background-image: url('images/footer.png');
   background-position:bottom left;
}

.art-footer-body .art-rss-tag-icon
{
   position: absolute;
   left:   6px;
   bottom:10px;
   z-index:1;
}

.art-rss-tag-icon
{
   display: block;
   background-image: url('images/rssicon.png');
   background-position: center right;
   background-repeat: no-repeat;
   height: 32px;
   width: 32px;
   cursor: default;
}

.art-footer-text p
{
   padding:0;
   margin:0;
   text-align: center;
}

.art-footer-body a,
.art-footer-body a:link,
.art-footer-body a:visited,
.art-footer-body a:hover,
.art-footer-body td, 
.art-footer-body th,
.art-footer-body caption
{
   color: #1F1F1F;
   font-size: 11px;
}

.art-footer-text
{
   min-height: 32px;
   padding-left: 10px;
   padding-right: 10px;
   text-align: center;
}

.art-footer-body a,
.art-footer-body a:link
{
   color: #1F5775;
   text-decoration: none;
}

.art-footer-body a:visited
{
   color: #4A4A4A;
}

.art-footer-body a:hover
{
   color: #297299;
   text-decoration: underline;
}

div.art-footer img
{
   margin: 10px;
}/* end Footer */

/* begin PageFooter */
.art-page-footer, 
.art-page-footer a,
.art-page-footer a:link,
.art-page-footer a:visited,
.art-page-footer a:hover
{
   font-family: monospace;
   font-size: 10px;
   letter-spacing: normal;
   word-spacing: normal;
   font-style: normal;
   font-weight: normal;
   text-decoration: underline;
   color: #1C4E69;
}

.art-page-footer
{
   position: relative;
   z-index: 10;
   padding: 1em;
   text-align: center;
   text-decoration: none;
   color: #424242;
}
/* end PageFooter */

/* begin LayoutCell, sidebar1 */
.art-content-layout .art-sidebar1
{
   width: 200px;
}
.art-content-layout .art-sidebar1:before
{
   position: absolute;
   z-index: -2;
   direction: ltr;
   left:   0;
   bottom: 0;
   top: 0;
   content: ' ';
   overflow: hidden;
   display: block;
   background-image: url('images/sidebar_bg.png');
   width: 200px;
}
/* end LayoutCell, sidebar1 */

/* begin LayoutCell, sidebar2 */
.art-content-layout .art-sidebar2
{
   width: 200px;
}
.art-content-layout .art-sidebar2:before
{
   position: absolute;
   z-index: -2;
   direction: ltr;
   right:   0;
   bottom: 0;
   top: 0;
   content: ' ';
   overflow: hidden;
   display: block;
   background-image: url('images/sidebar_bg.png');
   width: 200px;
}
/* end LayoutCell, sidebar2 */


