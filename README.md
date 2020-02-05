# Gröbner Solitaire
This is a one-person game that visualizes Buchberger's algorithm to find the reduced Gröbner basis of a set of binomials over ℤ₂[𝑥,𝑦].

Haley Dozier and John Perry published a paper [Androids Armed With Poisoned Chocolate Squares: Ideal Nim and Its Relatives](https://www.tandfonline.com/doi/abs/10.4169/math.mag.89.4.235)
in *Mathematics Magazine* in December of 2017. This project is a visualization of the idea of *Gröbner Nim*, in a one-person mode.
That is, the player needs to reach the reduced Gröbner basis of the initially given set of segments.

The implementation is written in HTML/JavaScript and uses GeoGebra for rendering the graphical objects.
An [installed version](http://prover-test.geogebra.org/~kovzol/groebner-solitaire/groebner-solitaire.html) can be tried out.
A [video](https://www.youtube.com/watch?v=Xbpr2Fp_NvY) describes how a typical game flow looks like.

This project is a work-in-progress. Currently only four game levels are included. The level can be selected by
appending `?level=0` or `?level=1`, and so on, to the URL.

Three languages are supported in the gameplay: English, German and Hungarian. Language selection is possible by
appending e.g. `&lang=German` after the level selection. (See more on this at the description of
[query string](https://en.wikipedia.org/wiki/Query_string) and
[HTTP GET request](https://www.w3schools.com/tags/ref_httpmethods.asp).)

Author: Zoltán Kovács <zoltan@geogebra.org>

German translation: Benedek Kovács <kovben2004@gmail.com>
