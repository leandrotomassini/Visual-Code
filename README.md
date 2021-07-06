![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Visual_Studio_Code_1.18_icon.svg/512px-Visual_Studio_Code_1.18_icon.svg.png)
# Visual Code
El editor de código fuente desarrollado por Microsoft para Windows, Linux y macOS. 

## Extensiones

* [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)

* [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)

* [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

* [Liveserver](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

* [Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme)

* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

* [TODO Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

## Atajos del teclado

* [shortcuts-linux](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf)

## Tips  

*   Objetivo:  
        ***Ordenar las listas***  
    Tips:  
        ⌥ ↓ / ⌥ ↑  
        Alt + ↑ / ↓  
        
* Quitar tabulacion: shit + tab  

* Objetivo:  
        ***Comentar un bloque de código***  

    Tips:  
        ⌘ /  
        Ctrl + /  
*  Comentar varias lineas  
        Ctls + shit + A  
        
*  Objetivo  
        ***Crear carpeta assets***  
        ***Crear carpeta js***  
        ***Crear archivo app.js***

    Tips:   
        ⌥ click derecho   
        Ctrl + click derecho  sobre el enlace src="assets/js/app.js"  

*  Objetivo:  
        ***Ir a la definición de la función 'saludar' rápidamente***  

    Tips:  ctrl + click  
    
*  Objetivo:  
        ***Seleccionar una palabra***  

    Tips:  shit + alt   


* Objetivo:  
        ***Borrar un bloque de código***  

    Tips:  
        Ctrl + Shift + K  

    PRO:  
        Seleccionar todas las ocurrencias de la selección  
        Ctrl + Shift + L  
* Objetivo:  
        ***Corregir tabulaciones***  

    Tips:          
        shit + tab  
        
* Objetivo:  
        ***Deshacer y rehacer el código***  

    Tips:  
        Ctrl +Z  
        Ctrl + Shift + Z  

* Objetivo:  
        ***Cero distracciones***  
        ***Ocultar Mostrar sidebar*** 
    
    tips:  
        Ctrl + B  
        
* Objetivo:  
        ***Ocultar Mostrar terminal***  
    
    tips:  
        Ctrl + `  
        
*     Objetivo:  
        ***Utilizar emmet wrap***  
        ***Crear atajo (shortcut) para el mismo***  
    
    tips:  
        ⇧ ⌘ P  
        Ctrl + SHIFT + P  

        Buscar: Wrap with abbreviation  
                debe de quedar el ng serve así  
                <code>ng serve</code>  

*  Objetivo:  
        ***Abrir, reabrir, cerrar tabs, cambair de tab***  
    
    tips:  

        Ctrl + W            Cerrar tab  
        Ctrl + K  Ctrl + W  Cerrar todas  
        Ctrl + Shift + T    Reabrir anterior  
        Ctrl + TAB          Cambiar de tab  
        
*     Tips: Copiar lineas
        * Puede cambiar, revisar los shortcuts  

    Pro: (Revisar shortcuts)  
        Copy line down  
        ⌘ K ⌘ S   
        Ctrl + K Ctrl + S  
        
*  Objetivo:  
        ***Crear múltiples cursores usando el "Next find match"***  
     
    Tip:   
        Ctrl + D  
 
 * Objetivo:  
        ***Ver rápidamente las definiciones de la clase***  
        ***También funciona con archivos HTML y otros***  

    Tips:  

        Ctrl + P => luego escribir la @  
        Ctrl + Shift = O  

        Se pueden agrupar si después de la @, se escriben :  
        
 *  Objetivo:
        ***Manejar (ir a una linea) TODOS:***   

    Tips:  
        ⌃ G  
        ⌘ P => luego escribir :  

        Ctrl + G  
        Ctrl + P => luego escribir la :  

* ctr + shif + f // Buscar palabra seleccionada  

*  Replace Symbol  
        F2  
*   Objetivo:  
        ***Vista previa markdown***  
    Tips:  
       ctrl + shif + p buscar >markdown
       
# Snippets basicos

* ***ir a  preferencias / user snippets, y debajo escribir por ejemplo:***    
     "Mostrar log": {  

        "prefix": "clg",  
        "body": [  
            "console.log('${1:Hola mundo}');",  
            "$2"  
        ],  
        "description": "Mostrar un log en la consola..."  
    },  
 
 
    "Clase": {  
        "prefix": "clase",  
        "body": [  
            "export class ${1:NombreClase} {",  
            "",  
            "	constructor(){",  
            "		$2",  
            "	}",  
            "}"  
        ],
        "description": "Mostrar la estructura de una clase"  
    }  
    
  ## Extensiones  
 
* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
*  [pokeapi.co](https://pokeapi.co/) 
 
* // [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)  
// [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)  
// TODO y FIXME  
Clic en el Arbol de la izquierda, y marcara todos los TODO  
Para que no aparezcan TODO de Node y otros desarrolladores ir a   
File/Preferences/Settings/extensions/TODO y y en exlude, editinsettings.json  
Pegar:  
 "todo-tree-excludeGlobs":[  
        "**/node_modules/**",  
        "**/vendor/**", 
        "**/brower_components/**",  
        "**/dist/**"  
    ],    
    ***Son como un recordatorio***  
  // TODO arreglar esto  
// FIXME: corregir el problema de la funcion  
    
* [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)  
  Ctrl + Alt + K : crea un toggle   
  Revisar la documentacion para mas funcionalidades.  
  
* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)  
   Paquete con iconos, para el explorador de visualcode.  
   
* [Material theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme)  
  Para cambiar un tema, teclear: Ctrl +k Ctrl + T , se abre el menu, ir bajando para elegir.
  
* [Live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) 
    En un archivo .hmlt, hacer clic abajo en Go Live, y te muestra la previa en un servidor de prueba :5500.  

* ***Para que el ColorHigLight no aparezca en el background*** de la palabra, ir a file, settings, extensions, color HghtLight, Marker Type, escribir: dot-before, y el color estara en un cuadrado al costado izquierdo de la palabra.  

* [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)  
  Para editar el color de las llaves, ir a file, preference, settings, extensions, Bracket Pair Colorizer, colors edditconfig.json, y debajo pegar por ejemplo:  
"bracket-pair-colorizer-2.colors": [
            "#fafafa",
            "#9F51B6",
            "#F7C244",
            "#F07B50"
            
        ]



# Tema que estoy usando:
* [Monokai Night](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-monokai-night)
* [Monokai Pro](https://www.youtube.com/watch?v=C3xl8Nah1Eo)  
* [app.js Crack monokai pro](https://github.com/leandrocosmetomassini/Visual-Code/blob/master/carpetas/workspace/master/app.js)

# Plugins

* [AB HTML Formatter](https://marketplace.visualstudio.com/items?itemName=zovorap.ab-html-formatter)

* [Activitus Bar](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar)

* [Angular Snippets](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)

* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)

* [Angular2-inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)

* [Awesome Flutter Snippets](https://marketplace.visualstudio.com/items?itemName=Nash.awesome-flutter-snippets)

* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

* [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)

* [Bootstrap 4, FontAwesome 5](https://marketplace.visualstudio.com/items?itemName=thekalinga.bootstrap4-vscode)

* [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)

* [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

* [Dart](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code)

* [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)

* [Gist](https://marketplace.visualstudio.com/items?itemName=kenhowardpdx.vscode-gist)

* [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)

* [ionic 4 Snippets](https://marketplace.visualstudio.com/items?itemName=fivethree.vscode-ionic-snippets)

* [JavaScript (ES6)](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)

* [jshint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.jshint)

* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

* [Prettier - Code Formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

* [PWA Tools](https://marketplace.visualstudio.com/items?itemName=johnpapa.pwa-tools)

* [Terminal](https://marketplace.visualstudio.com/items?itemName=formulahendry.terminal)

* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

* [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

* [TSLint](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin)

* [TypeScript Importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)



 
 

    

