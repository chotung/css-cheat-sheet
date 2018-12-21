<!-- Types of CSS -->

inline CSS: DIrectly in the html element (NO!!!!!!)

Internal CSS: Using <style></style> tags within a single document

External CSS: Linking an external .css file# css-cheat-sheet


<!-- Colors -->

Color Names red

HTML5 color names coral

Hexadecimal #00ff00

RGB rgb(0,0,255)

<!-- fonts -->
Special fonts you have to bring it in i.e. Google Fonts

<!-- Web Safe Fonts -->
sans serif flat
serif is pointy

Web Safe Fonts are builted in and don't need to be import

<!-- Class vs Id -->
ids are unique
-only once
Reuse classes
-always use classes


-Use percentage on containers

<!-- BOX MODEL -->
margin => border => padding => content
margin { 
    border { 
        padding { 
            content 
        }
    }
}
<!-- Margin -->
auto = puts margin on all sides

ex:
p  {
    margin-top: 5px
    margin-bottom: 5px
    margin-right: 10px
    margin-left: 10px
}

p {
    margin: 5px 10px 5px 10px
    <!-- top right bottom left -->
}
p {
    margin: 5px 10px
    <!-- if top===bot = 5 and right===left = 10-->
}

CAN DO THE SAME FOR PADDING


<!-- Border -->
size color type


<!-- POSITIONING -->
- Static: default renders in order of the document flow
- Relative: falls naturally but you can add properties like top, left, bot, right and push it anywhere
- Absolute: Target a position within a relative element
- Fixed: Fixed position in the browser window
- Intial: Sets to default value
- Inherit: inherit parent elements
