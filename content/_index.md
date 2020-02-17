+++
[banner]
  image = "img/bannerb.png"

  [[banner.button]]
      url = "/contact"
      text = "Contactanos"
      type = "primary"

  [[banner.button]]
      url = "#feature-icons"
      text = "Conoce mas!"

#Details for the box below the banner
[services]
  title = "Este verano!"
  text = "Del 15 de Julio al 16 de Agosto [Universidad de oriente y Arboterra](https://www.openstreetmap.org/#map=17/19.02627/-98.18799)."
  map_location = "Cathédrale Notre-Dame de Paris"

[feature_icons]
  #These feature icons look best if there's an even number of them.
  enable = true

  #Accent is a colour defined in the CSS file. Choose between 1 and 5
  [[feature_icons.tile]]
    icon = "/img/story.png"
    icon_pack = "fas"
    accent = "1"
    title = "Pre-produccion"
    text = "Historia, Story-board, animatic... "

  [[feature_icons.tile]]
    icon = "/img/prod.png"
    icon_pack = "fas"
    accent = "2"
    title = "Produccion"
    text = "Animacion, iluminacion, render..."

  [[feature_icons.tile]]
    icon = "/img/pos.png"
    icon_pack = "fas"
    accent = "5"
    title = "Post-produccion"
    text = "Composicion, correccion..."

  [[feature_icons.tile]]
    icon = "/img/fin.png"
    icon_pack = "fas"
    accent = "3"
    title = "Final"
    text = "Producto final"

[feature_images]
#These feature images look best if there's an even number of them.
  enable = true

  [[feature_images.tile]]
    image = "img/freely-10057.jpg"
    title = "Contenido del curso"
    text = "¿Que aprenderan mis hijos?"
    url = "/contenido"
    button_text = "Ver el documento"

  [[feature_images.tile]]
    image = "img/freely-26905.jpg"
    title = "Staff"
    text = "¡Conóce a los maestros!"
    url = "/maestros"
    button_text="¡Lista de profesorado!"

[CTA]
  heading = "Contactanos!"
  message = "Queremos oir de ti."
+++
