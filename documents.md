<style type="text/css">
.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  flex: 25%;
  max-width: 25%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    flex: 100%;
    max-width: 100%;
  }
}
</style>

## Voir tous les documents

<div class="row">
  <div class="column">
    <a href="./document1.html"><img src="./img/doc1/doc1_1.jpg"></a>
    <img src="./img/doc1/doc1_2.jpg">
    <img src="./img/doc1/doc1_2.jpg">
    <img src="./img/doc1/doc1_2.jpg">

  </div>
  <div class="column">
    <img src="./img/doc1/doc1_2.jpg">
    <img src="./img/doc1/doc1_1.jpg">
    <img src="./img/doc1/doc1_2.jpg">
    <img src="./img/doc1/doc1_2.jpg">
  </div>
  <div class="column">
  <img src="./img/doc1/doc1_2.jpg">
  <img src="./img/doc1/doc1_1.jpg">
  <img src="./img/doc1/doc1_2.jpg">
  <img src="./img/doc1/doc1_2.jpg">
  </div>
  <div class="column">
  <img src="./img/doc1/doc1_2.jpg">
  <img src="./img/doc1/doc1_1.jpg">
  <img src="./img/doc1/doc1_2.jpg">
  <img src="./img/doc1/doc1_2.jpg">
  </div>
</div>
