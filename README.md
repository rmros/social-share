# Social Share

Having ways for your website user to quickly share links via social media is a necessity today. However, many plugins and third-party resources we rely on to achieve this functionality include unnecessary complexities. Because of this, [Solodev](https://www.solodev.com/) has develoed an inline "Social Share" toolbar that's extremely simple to implement. Add this toolbar to your website in order to enable your website visitors to share via Facebook, Twitter, and LinkedIn.

## Tutorial

For instructions, view Solodev's [Implementing Social Share on your Solodev Website](https://www.solodev.com/blog/web-design/code-examples/implementing-social-share-on-your-solodev-website.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/aje9gg2x/).

## HTML

The social share toolbar uses basic HTML markup:
```
<div class="social_container">
   <ul class="socials">
	  <li>
		 <span>SHARE</span>
	  </li>
	  <li class="facebook">
		 <a href="//www.facebook.com/sharer/sharer.php?u=http://www.yourdomain.com" target="_blank"><img alt="facebook" src="https://www.solodev.com/assets/social-share/facebook.jpg"></a>
	  </li>
	  <li class="twitter">
		 <a href="//twitter.com/intent/tweet?text=A+New+Page&url=http://www.yourdomain.com" target="_blank"><img alt="twitter" src="https://www.solodev.com/assets/social-share/twitter.jpg"></a>
	  </li>
	  <li class="linkedin">
		 <a href="//www.linkedin.com/cws/share?url=http://www.yourdomain.com" target="_blank"><img alt="linkedin" src="https://www.solodev.com/assets/social-share/linkedin.jpg"></a>
	  </li>
   </ul>
</div>
```

## CSS

All CSS is included in social-share.css and includes:
```
ul.socials {
 margin-top: 10px;
 float: right;
}

ul.socials li {
 display: inline-block;
}

ul.socials li span {
 font-size: 13px;
 margin-right: 10px;
}
```
