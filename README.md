# sectional-boxes
Add a pop of branding to your sectional boxes with icons and images unique to your organization.

Sectional boxes can be one of the most direct navigational elements on your website. They often improve user experience by giving website visitors straightforward options to where your website can take them, and they can be enormously helpful in directing your users precisely where you'd want them to go.

## Tutorial		  
For detailed instruction's, view Solodev's [Creating Sectional Boxes with Icons and Background Images](https://www.solodev.com/blog/creating-sectional-boxes-with-icons-and-background-images.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/rnx5vot3/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="container">
<div class="row">
  <div class="col-sm-12">
  	<h1 class="display-3 text-center my-5">Solodev Web Experience Platform</h1>
  </div>
</div>
	<div class="row">
		<div class="col-md-3 col-sm-6">
			<div class="context" onclick="location.href='https://www.solodev.com/'">
				<img src="https://raw.githubusercontent.com/solodev/sectional-boxes/master/solodev-logo.jpg" alt="" class="img-fluid mx-auto d-block">
				<div class="overlay green">
					<div class="text text-white text-center">
						<div>
							<p><i class="fab fa-angellist fa-2x"></i></p>
							<p>For Web Developers</p>
						</div>
					</div>
			</div>	
			</div>
		</div>
		<div class="col-md-3 col-sm-6">
			<div class="context" onclick="location.href='https://www.solodev.com/'">
				<img src="https://raw.githubusercontent.com/solodev/sectional-boxes/master/solodev-logo.jpg" alt="" class="img-fluid mx-auto d-block">
				<div class="overlay darkblue  ">
					<div class="text text-white text-center">
						<div>
							<p><i class="fab fa-aws fa-2x"></i></p>
							<p>Cloud Hosting</p>
						</div>
					</div>
				</div>
			</div>	
		</div>
		<div class="col-md-3 col-sm-6">
			<div class="context" onclick="location.href='https://www.solodev.com/'">
				<img src="https://raw.githubusercontent.com/solodev/sectional-boxes/master/solodev-logo.jpg" alt="" class="img-fluid mx-auto d-block">
				<div class="overlay gold">
						<div class="text text-white text-center">
							<div>
								<p><i class="fas fa-building fa-2x"></i></p>
								<p>Corporate Services</p>
							</div>
						</div>
				</div>
			</div>	
		</div>
		<div class="col-md-3 col-sm-6">
			<div class="context" onclick="location.href='https://www.solodev.com/'">
				<img src="https://raw.githubusercontent.com/solodev/sectional-boxes/master/solodev-logo.jpg" alt="" class="img-fluid mx-auto d-block">
				<div class="pink overlay">
					<div class="text text-white text-center">
						<div>
							<p><i class="fas fa-chart-line fa-2x"></i></p>
							<p>Digital Marketing</p>
						</div>
					</div>
				</div>
			</div>	
		</div>
	</div>
</div>
```

## CSS

All required CSS is contained with style.css


## External Resources

This tutorial includes the following third party resources.

```
<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" rel="stylesheet">
<link href="https://use.fontawesome.com/releases/v5.1.0/css/all.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js"></script>

```

