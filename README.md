/* Базовый мобильный вид (по умолчанию) */
div {
  width: 90%;
  margin: 10px auto;
  display: block;
}

img {
  width: 100%;
  height: auto;
}

/* Планшетный вид: ≥772px */
@media screen and (min-width: 772px) {
  div {
    width: 45%;
    display: inline-block;
    vertical-align: top;
  }

  img {
    max-height: 30vh; /* 30% от высоты области просмотра */
    width: 100%;
  }
}

/* Широкоэкранный вид: ≥998px */
@media screen and (min-width: 998px) {
  div {
    width: 30%;
    display: inline-block;
    vertical-align: top;
  }

  /* Изображения остаются как в планшетной версии или базовой */
}

