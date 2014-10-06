## JavaScript - Literale und Typen

JavaScript ist eine dynamische Script-Sprache. Wir müssen (und können) Variablen bei der Deklaration nicht typisieren.

Es existieren aber selbstverständlich Typen und insbesondere auch primitive Literale und Typen wie folgt:

*    Number
*    String
*    Boolean
*    null
*    undefined

Deklariert werden Variablen mit dem Keyword var, typisiert durch Zuweisung.

    var zahl = 42;
    var piGrob = 3.14;

    var name = "Alt";
    var vorname = 'Michael';

    var wahr = true;

    var leer = null;
    var nix1;
    var nix2 = undefined;

    log("zahl (Typ: " + typeof(zahl) + ") " + zahl);
    log("piGrob (Typ: " + typeof(piGrob) + ") " + piGrob);
    log("name (Typ: "+ typeof(name) + ") " + name);
    log("vorname (Typ: "+ typeof(vorname) + ") " + vorname);
    log("wahr (Typ: "+ typeof(wahr) + ") " + wahr);
    log("leer (Typ: "+ typeof(leer) + ") " + leer);
    log("nix1 (Typ: "+ typeof(nix1) + ") " + nix1);
    log("nix2 (Typ: "+ typeof(nix2) + ") " + nix2);
