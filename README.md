# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
home html

```
<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj-Private Limited</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="company.html">Home</a></div>
        <div class="menuitem"><a href="product.html">Products</a></div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="static/images/iron.png" style="width:300px; height:300px;" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
                Copyright &#169; 2022 Aj-Private.LTD, Developed by Ajay Aswin.M

      </div>
    </div>
  </body>
</html>
```
product html

```
<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj-Private Limited</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="company.html">Home</a></div>
        <div class="menuitemselected">
          <a href="product.html">Products</a>
        </div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
    </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img1.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Simple Steps</div>
                  <div class="itemprice">Price: Rs.12,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img2.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Author edision </div>
                  <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img3.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally GST</div>
                  <div class="itemprice">Price: Rs.15,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img4.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally PRIME</div>
                  <div class="itemprice">Price: Rs.18,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img5.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Essential</div>
                  <div class="itemprice">Price: Rs.11,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img6.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Power of simplcity </div>
                  <div class="itemprice">Price: Rs.13,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img7.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Impleating</div>
                  <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img8.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Advance</div>
                  <div class="itemprice">Price: Rs.20,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img9.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally GST 4th edision</div>
                  <div class="itemprice">Price: Rs.19,000.00 </div>
              </div>

              
            
              
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2022 Aj-Private.LTD, Developed by Ajay Aswin.M
      </div>
    </div>
  </body>
</html>
```
people html

```
<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj-Private Limited</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="company.html">Home</a></div>
         <div class="menuitem">
          <a href="product.html">Products</a></div>
        <div class="menuitemselected"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
        
        <div class="content">
        <div class="productcontent">    
          <h1>People Of Company </h1>
          <figure>

        
        <p>
            <img src="static/images/img2/pre.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>PRESIDENT</h2></figcaption>
        <hr>
        
      
        <p>
            <img src="static/images/img2/fou.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>FOUNDER</h2></figcaption>
        <hr>
        
        
       <p>
            <img src="static/images/img2/mang.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>CO-FOUNDER</h2></figcaption>
        <hr>
        
        
        <p>
            <img src="static/images/img2/head.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>DIRECTOR</h2></figcaption>
        <hr>
        
        
        <p>
            <img src="static/images/img2/vk.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>MANAGER</h2></figcaption>
        <hr>

        <p>
            <img src="static/images/img2/aj.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>HEAD</h2></figcaption>
        <hr>
       </figure>
          </div>
      </div>
       <div class="footer">
       Copyright &#169; 2022 Aj-Private.LTD, Developed by Ajay Aswin.M
     </div>
    </div>
    
    
    
  </body>
 
</html>
```
contant html

```
<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="company.html">Home</a></div>
        <div class="menuitem"><a href="product.html">Products</a></div>  
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitemselected"><a href="contact.html">Contact Us</a></div>
      </div>
      
        <div class="content">
           <h1>Our Contact Address</h1>  
        
          <div class="contacttext">
           Phone:8248965167
           <br>Email-address:ajprivatelimited@email.com
          </div>
        </div>

     
<div class="footer">
  Copyright &#169; 2022 Aj-Private.LTD, Developed by Ajay Aswin.M
</div>
</div>
</body>
</html>
```
css

```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: lightblue;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid BLACK;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/images/back.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: BLACK;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: rgb(255, 123, 0);
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #f80d1d;
}

.menuitem a {
  text-decoration: none;
  color: #fdfdfd;
}

.content {
  display: block;
  width: 100%;
  background-color: lemonchiffon;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: rgb(255, 123, 0);
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}
.contact{
    border:100px;
}
.contenttext {
  text-align: justify;
}
```


## OUTPUT:
![Screenshot (94)](https://user-images.githubusercontent.com/119433834/215321199-e5fc1401-14fc-42e1-b457-2b7723497f50.png)

![Screenshot (93)](https://user-images.githubusercontent.com/119433834/215321225-ba1f1a47-4039-4bb0-8d2b-accdef871b24.png)

![kgcbvyhmjb](https://user-images.githubusercontent.com/119433834/215321235-c67d6040-4c93-47c1-a922-0e3cd5903f90.png)


![Screenshot (95)](https://user-images.githubusercontent.com/119433834/215321247-aec8d103-3390-4cf4-af95-324ade1e17c2.png)





## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
