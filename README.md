# Fix your content typography with tailwindcss

This will faster the process to make a theme with proper typography for any HTML templates, Ghost Themes, Jekyll Themes, WordPress Theme etc.

## How it works

Typography-fix will work if you add the class 'typofix' in your content markup. But make sure you added the typofix.css in your project.
Example :

```
<div class="entry-content">
	<p>Here is my content need to fix</p>
	<blockquote>
	   <p>Stay hungry. Stay foolish.</p>
	</blockquote>	
</div>
```

To change the design you can customize the css variables used in typography-fix.

Example

```
.entry-content {
	--link-color:blue;  
	--figcaption-align: center; 
	--figcaption-color: silver; 
	--table-border-color: LightGrey;  
	--blockquote-bg: white; 
	--blockquote-border-width: 1px;   
	--blockquote-border-style: solid; 
	--blockquote-border-radius: 0; 
	--blockquote-font-family: "Times New Roman", Times, serif;
	--blockquote-font-color: gray;
	--blockquote-font-style: normal;
	--blockquote-font-weight: 700; 
	--blockquote-px: 24px;
	--blockquote-py: 15px;
	--base-font-size: 16px;
	--text-font-family: Arial, Helvetica, sans-serif;
	--text-font-color: gray;
	--text-font-weight: 400;
	--text-line-height: 1.6;
	--heading-font-family: "Times New Roman", Times, serif;
	--heading-font-color: black; 
	--heading-font-weight: 700; 
	--heading-line-height: 1.3;
	--medium-max-width: 1096px;  
	--spacing-size: 16px;  
}  

```
