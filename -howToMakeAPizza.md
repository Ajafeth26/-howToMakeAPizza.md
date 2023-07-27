echo "# -howToMakeAPizza.md" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 
git branch -M main 
git remote add origin https://github.com/Ajafeth26/-howToMakeAPizza.md.git
 git push -u origen principal
git init
git checkout -b main
git clone <//github.com/Ajafeth26/-howToMakeAPizza.md.git>
cd <-howToMakeAPizza.md.git>

git checkout -b ada-lovelace
# Cómo hacer una deliciosa pizza 🍕

1. Preparar los ingredientes:
   - Masa de pizza
   - Salsa de tomate
   - Queso mozzarella rallado
   - Toppings (jamón, pepperoni, champiñones, etc.)

2. Estirar la masa:
   - Espolvorea harina sobre una superficie plana.
   - Con un rodillo, estira la masa hasta obtener el grosor deseado.

3. Agregar la salsa y el queso:
   - Unta una capa de salsa de tomate sobre la masa.
   - Espolvorea generosamente el queso mozzarella.

4. Añadir los toppings:
   - Coloca tus ingredientes favoritos sobre el queso.

5. Hornear:
   - Precalienta el horno a temperatura alta.
   - Coloca la pizza en una bandeja para hornear y métela en el horno.
   - Hornea durante 10-15 minutos o hasta que el queso esté dorado y burbujeante.

6. Disfrutar:
   - Saca la pizza del horno y córtala en porciones.
   - ¡Disfruta tu deliciosa pizza casera!

¡Buen provecho!
git add howToMakeAPizza.md
git commit -m "Agrega receta para hacer pizza"
git push origin ada-lovelace
git checkout main
git log  # Busca el hash de commit que quieres retroceder (por ejemplo, "abc123")
git checkout HEAD~2  # Reemplaza "abc123" con el hash de commit que deseas

