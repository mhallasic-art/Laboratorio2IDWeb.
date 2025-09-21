echo "<h1>Ejercicio 03</h1>" > index.html
git add index.html
git commit -m "Primer commit: index.html"
git push -u origin main
echo "body {background: lightblue;}" > styles.css
git add styles.css
git commit -m "Segundo commit: styles.css"
git push origin main
echo "<p>Archivo de prueba</p>" > prueba.html
git add prueba.html
git commit -m "Tercer commit: prueba.html"
git push origin main
echo "<p>Nuevo párrafo agregado</p>" >> index.html
git add index.html
git commit -m "Cuarto commit: párrafo agregado en index.html"
git push origin main
