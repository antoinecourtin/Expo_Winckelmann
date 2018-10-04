<style type="text/css">
.pic {
  width:100%;
  height:100%;
}
.carousel {
    border-style:solid;
    border-width:1px;
    border-color:rgba(0, 0, 0, 0.05);
    box-shadow: 0px 1px 6px rgba(0, 0, 0, 0.1);
    width:100%;
    height:590px;
  border-width:3px;
  border-radius:2px;
  border-color:#FCFCFC;
}

.carousel-inner {
    position: relative;
    overflow: hidden;
    width: 100%;
    height:590px;
}

.carousel-open:checked + .carousel-item {
    position: absolute;
    opacity: 100;
    background-color:black;
    width:100%;
    height:590px;
}

.carousel-item {
    position: absolute;
    opacity: 0;
    text-align:center;
}

.carousel-control {
  width: 150px;
  height: 150px;
  padding:0px;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0);
  border: 2px solid rgba(255, 255, 255, 0.9);
  background-clip: content-box;
  margin:0 auto;
  color:rgba(255, 255, 255, 0.9);

    cursor: pointer;
    display: none;
    font-size: 30px;
    height: 40px;
    line-height: 25px;
    position: absolute;
    top: 50%;
    -webkit-transform: translate(0, -50%);
    cursor: pointer;
    -ms-transform: translate(0, -50%);
    transform: translate(0, -50%);
    text-align: center;
    width: 30px;
    height:30px;
    z-index: 10;
}

.carousel-control.prev {
    left: 2%;
}

.carousel-control.next {
    right: 2%;
}

.carousel-control:hover {
    color: #4F94CD;
    background-color:rgba(255, 255, 255, 0.9);
}
 .carousel-control:hover:after {
  content: '';
  position: absolute;
  border-radius:50%;
  background:transparent;
  border: 1.5px solid rgba(255, 255, 255, 0.1);
  background:rgba(255, 255, 255, 0.1);
  top: -4px;
  left: -5px;
  right: -5px;
  bottom: -5px;
  z-index: -5;
}

#carousel-1:checked ~ .control-1,
#carousel-2:checked ~ .control-2,
#carousel-3:checked ~ .control-3{
    display: block;
}

.carousel-indicators {
    margin: 0;
    padding: 2px;
    position: absolute;
    bottom: -4.5px;
    left: 0;
    right: 0;
    text-align: center;
}

.carousel-indicators li {
    display: inline-block;
    margin: 0 5px;
    position: relative;

    /*You are required to do this*/
}
.carousel-indicators .carousel-preview {
    position: absolute;
    width: 108px;
    top: -0;
    left: 50%;
    margin-left: -52px;
    height:0px;
    transition:0 all;
    overflow: hidden;
}
.carousel-indicators .carousel-preview img {
    max-width:100px;
    max-height:50px;
    padding: 2px;
    background-color: white;
}
.carousel-indicators li:hover .carousel-preview {
    height:54px;
    top:-50px;
    transition:0.5s all;
}
.carousel-bullet {
    color: rgba(255, 255, 255, 0.7);
    cursor: pointer;
    font-size: 20px;
}

.carousel-bullet:hover {
    color: rgba(255, 255, 255, 0.9);
}

.HRConnectImage
{width:375px;
padding-top:50px;
display:inline-block;}

#carousel-1:checked ~ .control-1 ~ .carousel-indicators li:nth-child(1) .carousel-bullet,
#carousel-2:checked ~ .control-2 ~ .carousel-indicators li:nth-child(2) .carousel-bullet,
#carousel-3:checked ~ .control-3 ~ .carousel-indicators li:nth-child(3) .carousel-bullet{
    color: rgba(255, 255, 255, 0.9);
}

#title {
    width: 100%;
    position: absolute;
    padding: 0px;
    margin: 0px auto;
    text-align: center;
    font-size: 27px;
    color: rgba(255, 255, 255, 1);
    font-family: 'Open Sans', sans-serif;
    z-index: 9999;
    text-shadow: 0px 1px 2px rgba(0, 0, 0, 0.33), -1px 0px 2px rgba(255, 255, 255, 0);
}

#p
{
text-align:center;
font-weight:bold;}


.carousel-control { opacity: 0; }
.carousel:hover .carousel-control { opacity: 1; }
</style>


## Document n°1


<div class="carousel">
   <div class="carousel-inner">
      <input name="carousel" class="carousel-open" id="carousel-1" aria-hidden="true" type="radio" hidden="true" Checked/>
      <div class="carousel-item">
<img class="pic" src="./img/doc1/doc1_1.jpg">
      </div>
      <input name="carousel" class="carousel-open" id="carousel-2" aria-hidden="true" type="radio" hidden="true"/>
      <div class="carousel-item">
  <img class="pic" src="./img/doc1/doc1_2.jpg">
      </div>
      <input name="carousel" class="carousel-open" id="carousel-3" aria-hidden="true" type="radio" hidden="true"/>
      <div class="carousel-item">
<img class="pic" src="./img/doc1/doc1_1.jpg">
      </div>
      <label class="carousel-control prev control-1" for="carousel-3">‹</label>
      <label class="carousel-control next control-1" for="carousel-2">›</label>
      <label class="carousel-control prev control-2" for="carousel-1">‹</label>
      <label class="carousel-control next control-2" for="carousel-3">›</label>
      <label class="carousel-control prev control-3" for="carousel-2">‹</label>
      <label class="carousel-control next control-3" for="carousel-1">›</label>

      <ol class="carousel-indicators">
         <li>
            <label class="carousel-bullet" for="carousel-1">●</label>
            <div class="carousel-preview">
              <img src="./img/doc1/doc1_1.jpg" />
            </div>
         </li>
         <li>
            <label class="carousel-bullet" for="carousel-2">●</label>
            <div class="carousel-preview">
              <img src="./img/doc1/doc1_2.jpg" />
            </div>
          </li>  
         <li>
            <label class="carousel-bullet" for="carousel-3">●</label>
            <div class="carousel-preview">
              <img src="./img/doc1/doc1_1.jpg" />
            </div>
         </li>
    </ol>
</div>
</div>


### Cartel

**Titre** : ????  
**Date de publication** : ????  
**Editeur** : ??????  
**Cote** : ??????  

[Consulter le document numérisé](https://bibliotheque-numerique.inha.fr/collection/item/13543-lettres-familieres-de-m-winckelmann-premiere-partie?offset=2)



### Description de l'objet
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque ac vestibulum metus, ac suscipit tellus. Nullam suscipit risus mollis ultricies semper. Aliquam imperdiet risus ac quam congue, eget volutpat sem porttitor[^1]. Fusce condimentum dolor vel metus scelerisque pharetra. Aenean bibendum semper libero, nec aliquet justo mattis a. Nam a ipsum posuere, accumsan ipsum eu, vestibulum odio. Vestibulum rutrum lectus nisi, at accumsan est euismod non. Suspendisse tincidunt sodales posuere. Ut condimentum finibus neque, eu ornare nisi dignissim et. Praesent aliquet mi sed nibh dictum, non eleifend sapien fermentum. Morbi eget sem vel tellus vulputate auctor. Proin vitae elementum tortor. Nulla nec fermentum urna.

Donec vitae enim efficitur metus tincidunt viverra. Phasellus ut turpis ante. Nulla at gravida orci, et sagittis neque. Integer feugiat lorem vitae sapien efficitur, eu porttitor nisi congue. Aliquam condimentum mollis ligula vel pellentesque. Vestibulum sollicitudin velit magna, quis consequat ex rhoncus eget. Integer eu tristique lacus. Nullam vitae enim efficitur, rutrum nunc ultricies, finibus nisl.

<p>
<small>
[^1]: Note de bas de page
</small>
</p>
