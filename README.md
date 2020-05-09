# QML-Icon-Image-Unicode
In this file you can find a lot of icon image in UNICODE standard in order to used in your QT/QML project


How to use:

QML code:
/**************************************************/
import "../fontawesome.js" as FontAwesome

ButtonDefault {
              id: id_buttonZoomIn
              class_name: "dark"
              text: ""
              opacity: 0.4
              icon: FontAwesome.icons_Guardian200.fa_up_white_arrow_up
              onClicked: on_ButtonZoomIn()
              Image {
                      anchors.fill: parent
                      //source: "qrc:/Exit-removebg-preview.png"
                      fillMode: Image.Tile
                      rotation: 180    
                  }
              } 
/**************************************************/
