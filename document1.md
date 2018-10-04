<script>
$('.responsive').slick({
dots: true,
prevArrow: $('.prev'),
nextArrow: $('.next'),
infinite: false,
speed: 300,
slidesToShow: 4,
slidesToScroll: 4,
responsive: [
{
  breakpoint: 1024,
  settings: {
    slidesToShow: 3,
    slidesToScroll: 3,
    infinite: true,
    dots: true
  }
},
{
  breakpoint: 600,
  settings: {
    slidesToShow: 2,
    slidesToScroll: 2
  }
},
{
  breakpoint: 480,
  settings: {
    slidesToShow: 1,
    slidesToScroll: 1
  }
}
// You can unslick at a given breakpoint now by adding:
// settings: "unslick"
// instead of a settings object
]
});
</script>
<style type="text/css">
html {box-sizing: border-box;}
*, *:before, *:after {box-sizing: inherit;}

img {
  width: 100%;
  height: auto;
  padding: 5px;
}

h2 {
  text-align:center;
  padding-bottom: 1em;
}

.slick-dots {
  text-align: center;
  margin: 0 0 10px 0;
  padding: 0;
  li {
    display:inline-block;
    margin-left: 4px;
    margin-right: 4px;
    &.slick-active {
      button {
        background-color:black;
      }
    }
    button {
      font: 0/0 a;
      text-shadow: none;
      color: transparent;
      background-color:#999;
      border:none;
      width: 15px;
      height: 15px;
      border-radius:50%;
    }
    :hover{
      background-color: black;
    }
  }
}

/* Custom Arrow */
.prev{
  color: #999;
  position: absolute;
  top: 38%;
  left: -2em;
  font-size: 1.5em;
    :hover{
      cursor: pointer;
      color: black;
    }
}
.next{
  color: #999;
  position: absolute;
  top: 38%;
  right: -2em;
  font-size: 1.5em;
  :hover{
      cursor: pointer;
      color: black;
    }
}

@media screen and (max-width: 800px) {
    .next {
        display: none !important;
    }
}
</style>

## Document n°1

![Branching](./img/doc1/doc1_1.jpg)
![Branching](./img/doc1/doc1_2.jpg)


<div class="container">
  <h2>Slider - Multpile Items & Responsive</h2>
    <div class="row">
      <div class="col-md-12 heroSlider-fixed">
        <div class="overlay">
      </div>
         <!-- Slider -->
        <div class="slider responsive">
          <div>
						<img src="http://placehold.it/200x150" alt="" />
					</div>
					<div>
						<img src="http://placehold.it/200x150" alt="" />
					</div>
					<div>
						<img src="http://placehold.it/200x150" alt="" />
					</div>
					<div>
						<img src="http://placehold.it/200x150" alt="" />
					</div>
					<div>
						<img src="http://placehold.it/200x150" alt="" />
					</div>
					<div>
						<img src="http://placehold.it/200x150" alt="" />
					</div>
					<div>
						<img src="http://placehold.it/200x150" alt="" />
					</div>
					<div>
						<img src="http://placehold.it/200x150" alt="" />
					</div>
        </div>
				 <!-- control arrows -->
				<div class="prev">
					<span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
				</div>
				<div class="next">
					<span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
				</div>

      </div>
    </div>
  </div>
### Cartel

**Titre** : ????  
**Date de publication** : ????  
**Editeur** : ??????  
**Cote** : ??????  

[Consulter le document numérisé sur la bibliothèque numérique de l'INHA](https://bibliotheque-numerique.inha.fr/collection/item/13543-lettres-familieres-de-m-winckelmann-premiere-partie?offset=2)

### Description de l'objet

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque ac vestibulum metus, ac suscipit tellus. Nullam suscipit risus mollis ultricies semper. Aliquam imperdiet risus ac quam congue, eget volutpat sem porttitor[^1]. Fusce condimentum dolor vel metus scelerisque pharetra. Aenean bibendum semper libero, nec aliquet justo mattis a. Nam a ipsum posuere, accumsan ipsum eu, vestibulum odio. Vestibulum rutrum lectus nisi, at accumsan est euismod non. Suspendisse tincidunt sodales posuere. Ut condimentum finibus neque, eu ornare nisi dignissim et. Praesent aliquet mi sed nibh dictum, non eleifend sapien fermentum. Morbi eget sem vel tellus vulputate auctor. Proin vitae elementum tortor. Nulla nec fermentum urna.

Donec vitae enim efficitur metus tincidunt viverra. Phasellus ut turpis ante. Nulla at gravida orci, et sagittis neque. Integer feugiat lorem vitae sapien efficitur, eu porttitor nisi congue. Aliquam condimentum mollis ligula vel pellentesque. Vestibulum sollicitudin velit magna, quis consequat ex rhoncus eget. Integer eu tristique lacus. Nullam vitae enim efficitur, rutrum nunc ultricies, finibus nisl.

<p>
<small>
[^1]: Note de bas de page
</small>
</p>
