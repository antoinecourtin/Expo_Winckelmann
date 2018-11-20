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
    height:690px;
  border-width:3px;
  border-radius:2px;
  border-color:#FCFCFC;
}

.carousel-inner {
    position: relative;
    overflow: hidden;
    width: 100%;
    height:690px;
}

.carousel-open:checked + .carousel-item {
    position: absolute;
    opacity: 100;
    background-color:black;
    width:100%;
    height:690px;
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
    max-width:40px;
    max-height:80px;
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


### Document n°1 - Anton Francesco Gori (1691-1757)

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
<img class="pic" src="./img/doc1/doc1_3.jpg">
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
              <img src="./img/doc1/doc1_3.jpg" />
            </div>
         </li>
    </ol>
</div>
</div>

***

**Document n°1 - Anton Francesco Gori (1691-1757)**

**_Museum florentinum exhibens insigniora vetustatis monumenta quae Florentiae sunt, Ioanni Gastoni Etruriae Magno Duci dedicatum._**

**_I, Gemmae antiquae ex thesauro mediceo et privatorum dactyliothecis Florentiae exhibentes tabulis_**
**_c. Imagines virorum illustrium et deorum cum observationibus Antonii Francisci Gorii publici historiarum professoris, Florence,_**

**_ex typographia Michaelis Nestenus et Francisci Moücke, 1731-1732_**

**Brunet, t.2, col. 1670. [Cote FOL Res 399 (1-6)](http://bibliotheque.inha.fr/iguana/www.main.cls?surl=search&p=74469586-3948-11e2-a8f1-ac6f86effe00#recordId=1.226416)**

***

[exemplaire numérisé d'une autre bibliothèque](http://gallica.bnf.fr/ark:/12148/bpt6k888083n){:target="_blank"}


2 volumes in-folio (47 x 36 cm).

Reliure en maroquin rouge, encadrement doré sur les plats avec au centre du premier plat de chaque volume des armes frappées or, dos à six nerfs cloisonné de filets dorés, titre et tomaison (interversion volumes I et II).
Ex-libris gravé _The Marquis of Stafford_ avec la devise _Honi soit qui mal y pense_, collé sur le premier contreplat de chaque volume.
Estampille sur la page de titre : _Bibliothèque d'art et d'archéologie, 19 rue Spontini, 19 Paris._

Entièrement réglés à l'encre rouge ; marges d'origine conservées. Les planches sont intercalées au regard des explications dans le texte.

***

Anton Francesco Gori est un célèbre antiquaire de Florence, une des grandes figures de la première moitié du XVIIIe siècle.
Elève d'Anton Maria Salvini (1653-1729) et inspiré par les études de Filippo Buonarroti (1661-1733), il fut l'un des fondateurs de la _Società Colombaria Fiorentina en 1735._
Historien et antiquaire, il publie de nombreux ouvrages sur les découvertes archéologiques
en Italie, sur les inscriptions grecques et latines, sur les antiquités étrusques, et sur les collections de Toscane.

Le projet du _Museum Florentinum_, qui le rend célèbre dans l’Europe entière, est très ambitieux : il s’agit de dresser pour la première fois
le catalogue des collections antiques de Florence, principalement de la collection Médicis. Il comprendra au final dix volumes
parus entre 1731 et 1762 et organisés par typologie : les pierres gravées (deux volumes), les statues (un volume), les monnaies (trois volumes), puis
les portraits peints d’artistes de la galerie des Médicis (quatre volumes). Ce sont des publications luxueuses, _in-folio_, où chaque œuvre est représentées ;
Gori fait appel à de nombreux artistes pour effectuer les dessins et gravures des volumes. L’ensemble formait ainsi un formidable répertoire de dessins variés
pour les amateurs et savants, mais aussi pour les artistes et on retrouve l’influence de ces gravures dans des productions contemporaines très diverses.

Les catalogues illustrés de collections particulières apparaissent en Italie au XVIIe siècle (souvent dans un souci mercantile plus ou moins assumé).
Gori applique ici le principe aux musées florentins, et quelques années plus tard paraîtront les volumes du  _Museo Capitolino_ (1741-1755).
Ces beaux ouvrages largement illustrés sont très prisés de toute l’aristocratie européenne, particulièrement en Angleterre où on rassemble véritables fragments d’antiques et grands volumes de reproductions ;
ainsi cet exemplaire, acheté pour la bibliothèque Jacques Doucet de la rue Spontini, provient de la bibliothèque de George Granville Leveson-Gower, premier duc de Sutherland,
second Marquis de Stafford (1758-1833), fait chevalier de l’ordre de la Jarretière en 1806. Ce diplomate était l’un des hommes les plus riches d’Angleterre, et il a hérité
et développé la bibliothèque familiale bâtie par son grand-père Sir John Leveson Gower (1694-1754) à Trentham Hall, Staffordshire.

Les deux premiers volumes, sur lesquels Gori travaille depuis 1728, sont consacrés aux _Gemmae antiquae_, les pierres gravées antiques, et comprennent 200 planches.
Ce type d’œuvres, principalement les intailles, sont extrêmement prisées, collectionnées et étudiées au XVIIIe siècle.
Ce succès s’explique par de nombreux facteurs : ces pierres subsistent en nombre, et sont largement intactes, contrairement à la grande sculpture ; elles offrent ainsi
un accès direct au _dessin._

des anciens, et permettent une étude aussi bien des sujets que, de plus en plus, des styles.
Ce sont de petits objets précieux, dont on peut facilement faire des empreintes ou même des reproductions (en pâte de verre) : ces dernières sont alors largement échangées
entre les amateurs de toute l’Europe, permettant de constituer des cabinets montrant toute la diversité des productions et des sujets.
Le livre de Gori fait suite à d’autres études comme celle de Leonardo Agostini, _Gemme antiche figurate_, 1636, réédité en 1657
avec des annotations de Giovan Pietro Bellori, et celle de Philip de Stosch, _Gemmae Antiquae Caelatae_, paru en 1724.
Les analyses très développées, en latin, cherchent avant tout à faire le lien entre les images et les textes antiques connus, et à expliquer les sujets représentés.
Le travail sur les planches était tout aussi important que le texte : reproduire ces motifs de très petites dimensions, parfois difficile à comprendre, par des dessins agrandis
et donc facilement déformés était difficile, et Gori veillait de près à la réalisation de ces planches.

CC

Bibliographie : Micheli 1986 ; Gallo 1997 ; Masci 2003 ; Cagianelli 2006 ; Balleri 2007 ; Gambaro 2008 ; Bruni 2008 ; Bruni 2014.