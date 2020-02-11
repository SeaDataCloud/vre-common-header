# Common header template for services
Here you can find a simple common responsive Header template using pure HTML5/CSS3. please, use it in your SeaDataNet VRE service.

## Files 
`header-exemple.html` : HTML header example.  
`header.css` : Header styles.  
`header-title.png` & `logo.png` : Images displayed in the header.  ls

## How to proceed ?
1 - Copy the content of the `<header>` tag from the HTML file in your application pages.  
2 - Copy the header.css file in you project and declare it in the pages were you add the header (like in `header-exemple.html` for example).  
```
<link rel="stylesheet" href="path/to/css/header.css">
```
3 - Edit `header.css` to define the right path to the two PNG files.  

## My container is executed with jupyterhub and I need a button to shutdown it
In this case you just have to uncomment following code in `header-exemple.html` :  
```
<div class="ph-container">
  <div class="ph-float">
      <a href='/hub/logout' class='ph-button ph-btn-red'>Leave my service</a>
  </div>    
</div>
```
