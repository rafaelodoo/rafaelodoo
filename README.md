## Bienvenido a Rafapolis

:computer: **Ingeniero en tecnologías de la información y comunicación**
:pencil: **Odooer**

![Website](https://img.shields.io/website?url=https%3A%2F%2Fgithub.com%2Frafaelodoo%2Frafaelodoo
)

classDiagram
    Animal <|-- Duck
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
      +String beakColor
      +swim()
      +quack()
    }
    class Fish{
      -int sizeInFeet
      -canEat()
    }
    class Zebra{
      +bool is_wild
      +run()
    }