---
layout: bootstrap
displayName: Carousel
pageLink: carousel
pageWeight: 10
---


# Carousel
---

### Basic Example:

<div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
        <li data-target="#myCarousel" data-slide-to="2"></li>
        <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
        <div class="item active">
            <img src="images/car1.jpg" alt="Car1">
        </div>

        <div class="item">
            <img src="images/car2.jpg" alt="Car2">
        </div>

        <div class="item">
            <img src="images/car3.jpg" alt="Car3">
        </div>

        <div class="item">
            <img src="images/car4.jpg" alt="Car4">
        </div>

        <div class="item">
            <img src="images/car5.jpg" alt="Car5">
        </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>




<br> 
### Basic Example Codes:

```html
<div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
        <li data-target="#myCarousel" data-slide-to="2"></li>
        <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
        <div class="item active">
            <img src="images/car1.jpg" alt="Car1">
        </div>

        <div class="item">
            <img src="images/car2.jpg" alt="Car2">
        </div>

        <div class="item">
            <img src="images/car3.jpg" alt="Car3">
        </div>

        <div class="item">
            <img src="images/car4.jpg" alt="Car4">
        </div>

        <div class="item">
            <img src="images/car5.jpg" alt="Car5">
        </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>
```


<br><br>

### Example With Caption:

<div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
        <li data-target="#myCarousel" data-slide-to="2"></li>
        <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
        <div class="item active">
            <img src="images/car1.jpg" alt="Car1">
            <div class="carousel-caption">
            	<h3>Lorem Ipsum</h3>
            	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
        </div>

        <div class="item">
            <img src="images/car2.jpg" alt="Car2">
            <div class="carousel-caption">
            	<h3>Lorem Ipsum</h3>
            	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
        </div>

        <div class="item">
            <img src="images/car3.jpg" alt="Car3">
            <div class="carousel-caption">
            	<h3>Lorem Ipsum</h3>
            	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
        </div>

        <div class="item">
            <img src="images/car4.jpg" alt="Car4">
            <div class="carousel-caption">
            	<h3>Lorem Ipsum</h3>
            	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
        </div>

        <div class="item">
            <img src="images/car5.jpg" alt="Car5">
            <div class="carousel-caption">
            	<h3>Lorem Ipsum</h3>
            	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
        </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>




<br> 
### Example Caption Codes:

```html
<div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
        <li data-target="#myCarousel" data-slide-to="2"></li>
        <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
        <div class="item active">
            <img src="images/car1.jpg" alt="Car1">
            <div class="carousel-caption">
            	<h3>Lorem Ipsum</h3>
            	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
        </div>

        <div class="item">
            <img src="images/car2.jpg" alt="Car2">
            <div class="carousel-caption">
            	<h3>Lorem Ipsum</h3>
            	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
        </div>

        <div class="item">
            <img src="images/car3.jpg" alt="Car3">
            <div class="carousel-caption">
            	<h3>Lorem Ipsum</h3>
            	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
        </div>

        <div class="item">
            <img src="images/car4.jpg" alt="Car4">
            <div class="carousel-caption">
            	<h3>Lorem Ipsum</h3>
            	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
        </div>

        <div class="item">
            <img src="images/car5.jpg" alt="Car5">
            <div class="carousel-caption">
            	<h3>Lorem Ipsum</h3>
            	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
        </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>
```