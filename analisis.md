# Rufino Lab — análisis (27-oct-2026)

## Datos confirmados (fuente)
- Instagram @rufino_lab · 5,656 seguidores · 194 publicaciones · categoría "Restaurante de comida rápida" (perfil)
- Bio: "Rufino Lab. #TrueFastFoodLovers 🍗🍟🍔 · 📍Trujillo · 📞 906-755-197" (perfil)
- Destacadas: 🍗 (ícono átomo con R) · Promos 💥 · Carta 🤤 · Delivery 📍 (perfil)
- Sin link en la bio, sin web. Todo pasa por IG + llamada/WhatsApp.
- **Trujillo:** Borgoño 396 · 906 755 197 (captions + destacada Delivery)
- **Iquitos:** Yavarí 334 · 940 725 231 (destacada Delivery)
- Horario: 6:00 PM a 11:00 PM (caption 6-sep-2026, solo uno lo dice)
- Modalidades: "Salón, Delivery & Take out" (pie de las promos)
- Productos: Wings (alitas), Boneless ("piezas de pollo sin hueso"), papas, combos, Wing Box (captions + carta)

## Carta — Fórmulas (destacada Carta, 4-ago-2025): "12 salsas a elección"
- BBQ — clásica o BBQ picante
- Honey Mustard — miel y mostaza, dulce y ligeramente picante
- Maracuyá — "para este verano", más tropical
- Crispy Wings — crujientes por fuera, jugosas por dentro *(solo alitas)*
- Acevichada
- Lemon Pepper — pimienta y limón *(no válida para Boneless)*
- Garlic Parmesan — ajo, perejil, parmesano
- Tocino — "uno de nuestros experimentos"
- Huacatay
- **Spice Zone:** Hot Garlic · Hot Peruvian (4 ajíes nativos, "¡Puro fuego!") · Hot BBQ · Mango Habanero · Buffalo
- (la pág. Boneless dice "+11 fórmulas")

## Promos con precio
- **Duo Lab S/35** (combo para 2): 10 alitas (2 sabores) + papa grande + 4 boneless gratis + 1 fórmula 2 oz + bebida 500 ml
- **Wing Box S/39**: 10 alitas (2 sabores) + papa grande + 5 alitas gratis (1 sabor). "Válido solo para delivery o para llevar" (25-ago)
- Hallowings (19–31 oct): Combo 01 S/89 (30 alitas + 2 papas grandes + bebida 1 L gratis) · Combo 02 S/59 (20 alitas + 1 papa grande + 5 alitas gratis) · Combo 03 S/39 (10 alitas + 1 papa regular + 5 alitas gratis)
- En la grilla se ven otras promos sin leer bien: Box S/57, Combo UFC S/39, Duo Lab S/32, combo mundialero S/29, "Wings Day".

## Observaciones crudas
1. Le dicen **"fórmulas"** a las salsas: "elige tu fórmula", "uno de nuestros experimentos", "experimentando nació…". El nombre es *Lab*.
2. El papel de sus canastas está estampado con **moléculas/hexágonos de química**, átomos con R, "true fast food lovers" y el logo. Sale en casi todas las fotos.
3. El ícono de destacada principal es una **R dentro de un átomo** con órbitas.
4. **Mascota:** personaje redondo con lentes de laboratorio (goggles) y gorrito de chef, caminando con una bolsa "R" — en la bolsa y en las cajas.
5. La bolsa dice **"WINGS · FRIES · FLAVOR · REPEAT"** en un cartel tipo letrero de calle, y al costado "ALITAS · BONELESS · FRIES".
6. **Borde de cuadros rojo/blanco** (ajedrezado) en la bolsa, en la fachada y al pie de cada pieza de la carta.
7. Las fórmulas picantes viven en una zona aparte con línea punteada roja: **"SPICE ZONE"**.
8. Paleta: rojo intenso + blanco + amarillo mostaza (destacada Delivery, Duo Lab). Titulares en condensada pesada (tipo Bebas/Anton), el logo es script blanco "Rufino" con "LAB" pequeño.
9. El cliente pide por llamada/WhatsApp leyendo promos de historias: no hay carta con precios por cantidad de alitas en un solo lugar.

## Pendiente de confirmar
- Precios de la carta normal (alitas x 6/10/…, boneless, papas, bebidas, extras de fórmula). No se ven en el material.
- ¿906 755 197 tiene WhatsApp? ¿Iquitos entra en la web?
- Horario real por día; ¿abren todos los días?
- Delivery: zonas y costo. ¿Cuántas fórmulas por pedido (por cada 5/10 alitas)?
- Logo original (vector o PNG grande) y fotos originales.
- ¿Es propuesta o ya lo pidió el dueño?

## Carta confirmada (imágenes que pasó el usuario, 27-oct)
- Alitas con papas: 5 (1 fórmula) S/18 · 10 (2) S/29 · 20 (3) S/57 · 30 (4) S/87
- Boneless con papas: 5 (1) S/18 · 10 (2) S/27 · 20 (3) S/55 · 30 (4) S/79
- Fórmulas sin picante: Original BBQ, Crispy Wings, Garlic Parmesan, Honey Mustard, Acevichada, Tocino, Maracuyá, Lemon Pepper, Hawaiian, Huacatay
- Picantes (nivel): Hot Peruvian 5, Buffalo 4, Asian Spicy 4 (AGOTADO en la imagen), Mango Habanero 3, Hot BBQ 2
- Ojo: el título dice "12 fórmulas" pero lista 15.

## Boceto v1 (web/_src.html → web/index.html, servido en :8799)
Concepto: "Elige tu fórmula" — el muñeco (redibujado por nosotros, inspirado en el de la bolsa) baña las alitas con la fórmula elegida.
Asumido sin confirmar: WhatsApp en ambos números; mismos precios en Iquitos; horario 6–11 pm todos los días; colores de cada salsa (nuestros); Hallowings se oculta solo después del 31-oct.

## v3 (28-oct) — feedback del usuario
- Muñeco volteado a la derecha (sin la bolsa en la mano, ahí agarra el frasco); fuente: raw/muneco/sil2/lines2 (scratchpad nobag.py).
- Logo re-vectorizado de la foto nítida que pasó (raw/logo2/).
- Pila de alitas = cantidad real (5/10/20/30; promos 10 y 15), papas detrás, salsa en cortina por pieza.
- Iquitos BORRADO (pedido del usuario): solo Trujillo, WhatsApp 906 755 197.
- Presentación "Empezar a formular" al entrar (se salta con ?dry, ?static, ?t, ?nointro).
- Respaldo de v2: web/v2-muneco-bolsa.html

## v4 (28-oct)
- Muñeco = matraz rojo (cuello, cuerpo, base, brazos, piernas) + guantes, lentes y zapatillas blancas, líneas #2B0A0B (raw/muneco/red.pbm, regiones en reg.npy).
- Logo en PNG (web/assets/img/logo.png): el SVG trazado salía con un bloque blanco en Safari.
- Una sola alita (plana, curva, con puntitas de hueso); boneless aparte.
- 20 y 30 piezas → 2 canastas. Respaldo v3: web/v4-matraz.html (antes del cambio).

## v5 (28-oct)
- Personaje redibujado en vector (raw/chef/chef.js → constante CHEF en _src.html): matraz Erlenmeyer rojo, lentes, guantes, zapatillas, R en la panza. El usuario pidió este estilo (referencia de personaje matraz) porque el trazo de la bolsa salía cortado. El trazo viejo quedó en v5-trazo.html.
- Sostiene el matraz chico desde la base (bottleArt desplazado -100; TIPL=150).
- Celular: escena 40svh, etiqueta compacta (descripción a 1 línea) con sombra.

## v6 (28-oct)
- Personaje en línea, transparente (como su papel de empaque, foto del usuario): lentes con rayas, rulitos en la cara, marcas de medida, brazos de manguera, guante abierto, zapatillas con rayas. raw/chef/chef2.js → función chef(ink,fill,glass,clip). Escena: línea roja + vidrio con moléculas; presentación: línea blanca sobre rojo. Respaldo con relleno: web/v6-relleno.html

## v7 (28-oct)
- Personaje redibujado por el modelo Fable a pedido del usuario (raw/chef/chef3.js, preview3.png): calcado de su papel de empaque (foto 19), agarra el matraz por el cuello con los dedos encima. flaskArt() reemplaza a #bottleArt; TIPL=48; armB gira en (94,216). Respaldo previo: web/v7-linea-mia.html

## v8 (28-oct)
- El usuario pidió el muñeco IGUAL al de su bolsa (foto IMG_2368 + video SaveClip en raw/user/ref2). Volvimos al trazo real de la bolsa (sil3/lines3: sin la bolsita, lado tapado completado con curva de matraz; scratchpad complete.py), blanco con línea roja. El matraz de fórmula cuelga del puño (flaskArt de Fable, TIPL=48), detrás del muñeco. Respaldo con el dibujo de Fable: web/v8-fable.html

## v9 (28-oct)
- Trazo de la bolsa limpiado: línea central (skeletonize, venv en scratchpad) con grosor parejo, lentes redibujados con 2 rayas, resto del corte borrado, puntitos conservados. Partes separadas: .legs (caminan), .armB (balancea), .eyes (parpadean). Fuente: raw/chef/bagchef.frag.svg (scripts clean.py/parts.py/build2.py en scratchpad). Presentación: halo blanco. Respaldo: web/v9-trazo-grueso.html

## Destacadas de IG (raw/user/destacadas.png, 28-oct)
- 🍗 (principal): logo "R" dentro de un átomo + destellos ✱, rojo sobre blanco texturado.
- Promos: escarapela ondulada con "%", amarillo mostaza sobre rojo + destellos de 4 puntas.
- Carta: alitas dibujadas en línea blanca (irregulares, crocantes, con migas) + vasito de salsa con rayitas, sobre rojo.
- Delivery: el muñeco sentado, en línea roja sobre amarillo, levantando el matraz chico en el puño (misma pose del papel de empaque).
- Sistema: íconos de línea gruesa redondeada, monocromos; fondos rojo / amarillo / blanco texturado; destellos ✱ como acento.
- v11: alitas de canasta en el estilo de su destacada "Carta" (borde en ondas, pliegue, rayitas, migas); íconos de sus destacadas en la web: átomo R (Tus fórmulas), alita+vasito (¿Cuántas?), escarapela % (Promos y precios), destellos ✱ (título promos + ráfaga al elegir fórmula y al agregar), vasito con rayitas (2 oz). Respaldo: web/v11-antes-iconos.html

## v12 (28-oct)
- Muñeco = calco de Fable línea por línea sobre el cuadro nítido del video (raw/chef/traced.svg, overlay traced_overlay.png), volteado; puño (265,620) encajado en el pivote del matraz. Inventado por necesidad: brazo corto entre puño y cuerpo, cierre del puño (lo tapaba la bolsa). Grupos armT/legsT listos para animar si se quiere. Respaldo: web/v12-trazo-suave.html

## v13 (28-oct)
- El usuario descartó el muñeco ("está feo"): ahora el protagonista es un matraz grande con el átomo R que vierte la fórmula (flaskArt escalado FLASK_K=2.05, pivote en el cuerpo, TIPL=88*K). Alitas de vuelta a la alita curva con puntitas de hueso (las de ondas "parecen boneless"). Respaldo con el muñeco calcado: web/v13-muneco-calco.html
