/// organizacion de carpetas sass

/// sass/
/// |
/// |– base/
/// |   |– _reset.scss       # Reset/normalize
/// |   |– _typography.scss  # Reglas tipográficas
/// |   |– _animation.scss   # Reglas para animaciones si hay muchas
/// |
/// |– components/ --> comps pequeños, widgets, slider, loader, widget,
/// |   |– _buttons.scss     # Botones
/// |   |– _carousel.scss    # Carousel
/// |   |– _cover.scss       # Cubierta
/// |   |– _dropdown.scss    # Dropdown
/// |   …                    # Etc.
/// |
/// |– layout/(o partials)  --> distribucion del sitio. estilo de las partes principales del sitio, sistema de grid, o css para forms
/// |   |– _navigation.scss  # Navegación
/// |   |– _grid.scss        # Sistema de retícula
/// |   |– _header.scss      # Encabezamiento
/// |   |– _footer.scss      # Pie de página
/// |   |– _sidebar.scss     # Barra lateral
/// |   |– _forms.scss       # Formularios
/// |   …                    # Etc.
/// |
/// |– pages/
/// |   |– _home.scss        # Estilos específicos para la página de inicio
/// |   |– _contact.scss     # Estilos específicos para cualquier pagina(contact en  este caso)
/// |   …                    # Etc.
/// |
/// |– themes/ puede ser usado para light/dark, etc
/// |   |– _theme.scss       # Tema por defecto
/// |   |– _admin.scss       # Tema del administrador
/// |   …                    # Etc.
/// |
/// |– utils/ --> reune todas las herramientas y helpers. funciones, mixin, global, placeholder. solo addons, nada de codigo.
/// |   |– _variables.scss   # Variables Sass
/// |   |– _functions.scss   # Funciones Sass
/// |   |– _mixins.scss      # Mixins Sass
/// |   |– _helpers.scss     # Clases & placeholders
/// |
/// |– vendors/--> archivos de librerias y framworks.
/// |   |– _bootstrap.scss   # Bootstrap
/// |   |– _normalize.scss   # normalize
/// |   |– _jquery-ui.scss   # jQuery UI
/// |   …                    # Etc.
/// |
/// |
/// `– main.scss             # Archivo principal de Sass


/// En cada carpeta se añade un archivo '_index', que reciba mediante un @forward todas las modificaciones y archivos contenidos en la carpeta, sin el '_x' de cada archivo