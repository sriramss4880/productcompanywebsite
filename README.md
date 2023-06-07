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
### HOME.HTML
```python
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
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
        Copyright &#169; 2021 EduSoft Private Limited, Developed by SRIRAM.S.S.
      </div>
    </div>
  </body>
</html>
```
### PRODUCT.HTML
```python
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by SRIRAM.S.S.
      </div>
    </div>
  </body>
</html>
```
### PEOPLE.HTML
  ```python
  <!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMING' IS NOT A CRIME</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/banner1.jpg" type="image/x-icon" />
  </head>
  <body>
   <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
            <h1>Our Team</h1>
            <div class="peopleitems">
                <div class="peopleitem">
                    <div class="peopleimage">
                    <img src="./img/sriram.jpg" width="130" height="155" alt="people1 image">
                    </div>
                    <div class="peoplename">Mr.Sriram</div>
                    <div class="peoplepos">MD and CEO</div>
                </div>
                <div class="peoplecontent"> 
                  <div class="peopleitems">
                      <div class="peopleitem"> 
                          <div class="peopleimage">
                          <img src="./img/leann.jpg" width="130" height="145" alt="people2 image">
                          </div>
                          <div class="peoplename">Ms.Leann</div>
                          <div class="peoplepos">CPO</div>
                      </div>
                      <div class="peoplecontent">   
                        <div class="peopleitems">
                            <div class="peopleitem"> 
                                <div class="peopleimage">
                                <img src="./img/yogi.jpg" width="130" height="145" alt="people3 image">
                                </div>
                                <div class="peoplename">Mr.Yogeshwar</div>
                                <div class="peoplepos">CHRO</div>
                            </div>
                        <div class="peoplecontent">  
                                    <div class="peopleitems">
                                        <div class="peopleitem"> 
                                            <div class="peopleimage">
                                            <img src="./img/kaviya.jpg" width="130" height="155" alt="people4 image">
                                            </div>
                                            <div class="peoplename">Mr.Kaviya shree</div>
                                            <div class="peoplepos">Joint MD and CTO</div>
                              </div>
                        <div class="peoplecontent"> 
                                          <div class="peopleitems">
                                              <div class="peopleitem"> 
                                                  <div class="peopleimage">
                                                  <img src="./img/teja.jpg" width="130" height="145" alt="people5 image">
                                                  </div>
                                                  <div class="peoplename">Ms.Tejaswini</div>
                                                  <div class="peoplepos">Head,Retail Sales</div>
                               </div>
                               <div class="peoplecontent">    
                           
                                <div class="peopleitems">
                                    <div class="peopleitem"> 
                                        <div class="peopleimage">
                                        <img src="./img/dinesh.jpg" width="130" height="145" alt="people6 image">
                                        </div>
                                        <div class="peoplename">Mr.Dinesh Karthick</div>
                                        <div class="peoplepos">CFO</div>
                     </div>
          </div>
        </div>
      <div>
      <div class="footer">
        Copyright &#169; 2023 Gamer'sworld.MGamers.org, Developed by SRIRAM.S.S.
      </div>
     </div>
     </body>
</html>
```
### CONTACT.HTML
```python 
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>GAMIN' IS NOT A CRIME</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/banner1.jpg" type="image/x-icon" />    
    </head>
    <body>
        <div class="container">
            <div class="banner">EduSoft Private Limited.</div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>    
                <div class="menuitem"><a href="/static/products.html">Products</a></div>   
                <div class="menuitem"><a href="/static/people.html">People</a></div>  
                <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>           
            </div>
            <div class="content">
                <div class="contactcontent">
                    <div class="contactitems">
                        <div class="contactitem">
                            <h2><u>Contact Us</u></h2>
                            <h3>Gloabal headquarters</h3>
                            <h3>Head Quarters-Chennai,India</h3>
                            <div class="address"> 60,Krishna Block Rajaji Salai,<br/>
                                Opp.Dist.Collectorate,<br/>
                                Chennai,<br/>
                                Tamil Nadu 600001</div>
                            <div class="number">phone: +91 57853 22746 </div>
                            <div class="email">E-mail: Gamer'sworldind@MGamers.org</div>
                            <div class="socials">Instagram/Twitter/Facebook: @-=Gamer's world=-</div>

                            <h3>Regional Head Quarters-London,UK</h3>
                            <div class="address">42 Earlham St,<br/>
                                London WC2H 9LA,<br/>
                                 CA 94025,<br/>
                                 United Kingdom</div>
                            <div class="number">phone: +44 (0) 20 7234 3456 </div>
                            <div class="email">E-mail: Gamer'sworlduk@MGamers.org</div>
                            <div class="socials">Instagram/Twitter/Facebook: @-=Gamer's world=-UK</div>

                            <h3>Regional Head Quarters-Seoul,South Korea</h3>
                            <div class="address">42 Teheran-ro 108-gil,  <br/>
                                Daechi-dong,<br/>
                                Gangnam-gu,Seoul,<br/>
                                South Korea</div>
                            <div class="number">phone: +82 2 312 3456 </div>
                            <div class="email">E-mail: Gamer'sworldsk@MGamers.org</div>
                            <div class="socials">Instagram/Twitter/Facebook: @-=Gamer's world=-Kor</div>

                            <h3>Regional Head Quarters</h3>
                            <div class="address">1 Hacker Way,<br/>
                                 Menlo Park,<br/>
                                 CA 94025,<br/>
                                 United States</div>
                            <div class="number">phone: +1 650-543-4834 </div>
                            <div class="email">-mail: Gamer'sworldusa@MGamers.org</div>
                            <div class="socials">Instagram/Twitter/Facebook: @-=Gamer's world=-USA</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2023 Gamer'sworld.MGamers.org, SRIRAM.S.S.
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:

### Home Page:


![Screenshot (30)](https://github.com/sriramss4880/productcompanywebsite/assets/120554177/77ffc7c7-c4ac-4c96-b5a1-ee5d6bad8133)
![Screenshot (27)](https://github.com/sriramss4880/productcompanywebsite/assets/120554177/a25fc20a-2a37-45a5-9070-5e77d6b3ceb3)
![Screenshot (28)](https://github.com/sriramss4880/productcompanywebsite/assets/120554177/80ba613e-f85f-4f46-846f-0463e8de99ad)
![Screenshot (29)](https://github.com/sriramss4880/productcompanywebsite/assets/120554177/9cc0d719-fce4-4b16-bbf5-ce8cb857d0ae)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
