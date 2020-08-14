# module5-solution
<!doctype html>

<title>David Chu's China Bistro</title>
      <div class="navbar-brand">
        <a href="index.html"><h1>David Chu's China Bistro</h1></a>
        <p>
          <img src="images/star-k-logo.png" alt="Kosher certification">
          <span>Kosher Certified</span>
        </p>
      </div>

      <button id="navbarToggle" type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#collapsable-nav" aria-expanded="false">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
    </div>
    
    <div id="collapsable-nav" class="collapse navbar-collapse">
       <ul id="nav-list" class="nav navbar-nav navbar-right">
        <li id="navHomeButton" class="visible-xs active">
          <a href="index.html">
            <span class="glyphicon glyphicon-home"></span> Home</a>
        </li>
        <li id="navMenuButton">
          <a href="#" onclick="$dc.loadMenuCategories();">
            <span class="glyphicon glyphicon-cutlery"></span><br class="hidden-xs"> Menu</a>
        </li>
        <li>
          <a href="#">
            <span class="glyphicon glyphicon-info-sign"></span><br class="hidden-xs"> About</a>
        </li>
        <li>
          <a href="#">
            <span class="glyphicon glyphicon-certificate"></span><br class="hidden-xs"> Awards</a>
        </li>
        <li id="phone" class="hidden-xs">
          <a href="tel:410-602-5008">
            <span>410-602-5008</span></a><div>* We Deliver</div>
        </li>
      </ul><!-- #nav-list -->
    </div><!-- .collapse .navbar-collapse -->
  </div><!-- .container -->
</nav><!-- #header-nav -->
