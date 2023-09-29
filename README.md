# fanuc_virtual_milling_Exam
_Examen de control de fresado mediante codigo de simulacion para control de maquinaria CNC_

## Examen (_INICIALES DE MI NOMBRE_)
_Utilizando 4 letras de mi nombre: Gaddiel Zamora Flores_
_GAZF_

![image](https://github.com/Gaddiel0710/fanuc_virtual_milling_Exam/assets/135661300/967ff385-f9fb-42fe-b603-c8d7669625a7)

## Codigo en C++ para la frensadora CNC

```C++
[BILLET X100 Y80 Z30;
[TOOLDEF T1 D2;
N10 | G21 G94;
N20 | G90 G28 X0 Y0 Z0;
N30 | M06 T1 D2;
N40 | M03 S600;
N50 | G90 G00 X5 Y15 Z30;
N60 | G01 Z-20 F120;
N70 | G02 X5 Y15 R10;
N80 | G01 X145;
N90 | G02 X155 Y15 R10;
N100 | G01 Y75;
N110 | G02 Y85 X145 R10;
N120 | G01 X15;
N130 | G02 X5 Y75 R10;
N140 | G01 Y15;
N150 | G00 Z30;
N160 | G90 G28 X0 Y0 Z0;
N170 | M06 T2 D4;
N180 | M03 S600;
N190 | G90 G00 X30 Y70;
N200 | G01 Z-20;
N210 | G03 X35 Y15 R30;
N220 | X50 Y25 R20;
N230 | G01 Y40;
N240 | X35;
N250 | G00 Z33;
N260 | G90 G00 X30 Y70;
N270 | G01 Z-20;
N280 | G02 X50 Y65 R15;
N290 | G00 Z30;
N300 | G90 G00 Y15 X60;
N310 | G01 Z-20;
N320 | X65 Y35;
N330 | X85;
N340 | X65;
N350 | X75 Y70;
N360 | X87.5 Y15;
N370 | G00 Z30;
N380 | G90 G00 Y70 X95;
N390 | G01 Z-20;
N400 | X115;
N410 | X95 Y15;
N420 | X115;
N430 | G00 Z30;
N440 | G90 G00 X130 Y70;
N450 | G01 Z-20;
N460 | X145;
N470 | X130;
N480 | Y15;
N490 | Y35;
N500 | X120;
N510 | X145;
N520 | G00 Z30;
N530 | G90 G28 X0 Y0 Z0;
N540 | M28;
```

## CNC CODE RESULT
_Resultado en 2D_

![image](https://github.com/Gaddiel0710/fanuc_virtual_milling_Exam/assets/135661300/483b5cb2-7e3c-48ed-a533-b28c90cc4707)


_Resultado en 3D_

![image](https://github.com/Gaddiel0710/fanuc_virtual_milling_Exam/assets/135661300/6009a03b-1712-4487-8472-35eb4134d6db)
