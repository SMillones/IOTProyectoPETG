# Problemática: Exceso de botellas plásticas PETG sin un real uso en reciclaje.
Se ha decidido fabricar una máquina que forme filamento para impresión 3D en base a botellas plásticas del material PETG. Esto se lograría al cortar las paredes de la
botella, luego serían ingresadas a un sistema de calor junto a una boquilla de 1.5mm aproximadamente la cual extruiría el filamento listo para ser insertado en alguna 
impresora 3D de FDM que soporte la impresión de este material.
Para llevar a cabo la recolección del filamento se utilizará una bobina unida a engranajes junto a un motor paso a paso que recogerá el filamento 
extruido permitiendo una extracción constante y así evitar deformaciones en el material por deterioro de material a causa de la exposición prolongada a una
alta temperatura.
## Los materiales por usar serían:
    - Boquilla pistola de silicona
    - Tornillos cortos M3
    - Rodamientos 608ZZ
    - Barra roscada M8
    - Tuercas y arandelas M8
    - Placa de madera
    - Motor paso a paso (por ejemplo, Nema 17)
    - Arduino
    - Driver A4988
    - Capacitor 100 micro faradios
    - Engranajes y bobinas impresas en 3D
Cabe mencionar que las piezas impresas y partes del proyecto serán sacadas del modelo creado por ‘ELECTRONOOBS’ en el proyecto:
"Filament Maker from PET Bottle - Share Project - PCBWay" [Proyecto y STL](https://www.youtube.com/watch?v=dN2qp1ihuto&t=273s&ab_channel=ELECTRONOOBSenEspa%C3%B1ol), 
ademas el modelo de coneccion y comprencion del funcionamiento se encuentran gracias a "BitWise Ar" [Modelo y funcionamiento](https://www.youtube.com/watch?v=u0SG681s8aA&t=11s&ab_channel=BitwiseAr).
Algunos codigos e instrucciones se pueden encontrar en [Tutorial motor nema 17 y driver A4988](https://www.makerguides.com/a4988-stepper-motor-driver-arduino-tutorial/)
## Motor paso a paso Nema 17
El motor NEMA 17 es un tipo de motor paso a paso que generalmente tiene 200 pasos por revolución, lo que significa que cada paso es de 1.8 grados y 
opera típicamente a bajos voltajes (4-12V) y requieren una corriente de alrededor de 1 a 2 amperios por fase, energía que consume incluso cuando
está en reposo para mantener la posición.
## Driver A4988
El A4988 permite controlar el motor paso a paso mediante dos señales: una para el paso (cuántos pasos dar el motor) y otra para la dirección (sentido de giro del motor),
incluye protecciones contra sobrecorriente, sobrecalentamiento y bajo voltaje, lo que ayuda a garantizar la durabilidad del motor y del controlador.
EL A4988 necesita un voltaje de suministro lógico (3-5.5V) para el controlador y un voltaje de suministro del motor (8-35V) para el motor

## Diagrama 
![Screenshot 2024-11-25 083418](https://github.com/user-attachments/assets/a3671aa2-0334-475b-a1b3-2c8f04ef371b)

## Profesor guia
- Ignacio Pérez

## Integrantes 
- Ethan Araya
- Sergio Millones
