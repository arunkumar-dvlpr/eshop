# eshop / Sample Theme Creation

## Header Section
Usig Magento_Theme/layout/default.xml page's unwanted blocks are remove and elemets are moved as per given front end design
## Banner Section
1. Using Admin Dasboard/Content/Blocks option create a one custom block, name it as 'category_banner'
2. Using pagebuilder option row layout added, ad set its apperance option as 'Full Bleed'
3. Set its background as 'Black' and set 30px margin bottom
4. After that add the below code in 'HTML Code' element

~~~
<div class="cat-pg-bnr">
<p class="cat-pg-bnr-title">Shop / Left Side Bar</p>
<p class="cat-pg-bnr-desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
</div>
~~~
## Footer Social Links Section
1. Using Admin Dasboard/Content/Blocks option create a one custom block with Block Title as 'Footer Social Links Block' and identifier as 'footer_social_links'
2. With help of page builder option add the below code in 'HTML Code' element
~~~
<div class="footer-social">
<ul>
<li><i class="fa fa-facebook"></i></li>
<li><i class="fa fa-twitter"></i></li>
<li><i class="fa fa-tumblr"></i></li>
<li><i class="fa fa-pinterest-p"></i></li>
<li><i class="fa fa-linkedin"></i></li>
</ul>
</div>
~~~
3. Using Admin Dashboard/Content/Widget create one new widget, name it as 'Footer Social Icons'
4. Add layout update then choose container 'Page Footer Container'
5. Then widget option and choos the block we created one 'Footer Social Links Block'
## Footer Hot Links Section
1. Using Admin Dasboard/Content/Blocks option create a one custom block with Block Title as 'Footer Hotline Block' and identifier it as 'footer_hotline_block'
2. With help of page builder option add the below code in 'HTML Code' element
~~~
<div class="footer-hotline-section">
<p>Hotline: 001-888-8888</p>
</div>
~~~
3. Using Admin Dashboard/Content/Widget create one new widget, name it as 'Footer Hotline'
4. Add layout update then choose container 'Page Footer Container'
5. Then widget option and choos the block we created one 'Footer Hotline Block'
