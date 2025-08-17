# Impressora 3D Caseira 


Projeto pessoal de **impressora 3D feita com materiais recicláveis e de fácil acesso**.  
O objetivo foi aprender mais sobre o funcionamento de impressoras 3D e, ao mesmo tempo, ter acesso a uma máquina própria para uso em projetos futuros.


![1755462619664](https://github.com/user-attachments/assets/b056b86a-a524-412b-9dc5-ba4ccc7ff9f7)

---


Durante o desenvolvimento, alguns desafios surgiram:
- Falta de informações e manuais de funcionamento claros.
- Dificuldade de acesso a certos materiais no Brasil.
- Alto custo de peças novas, o que me levou a importar alguns componentes ou comprar usados em ferro-velho.

---

##  Especificações Técnicas
- **Estrutura:** madeira reciclada.  
- **Eixo X/Y:** 2 motores **Nema 17** com correia dentada e tensor.  
- **Eixo Z:** 2 motores **Nema 17** + fusos trapezoidais para estabilidade.  
- **Guias lineares:** substituídas por **corrediças de gaveta**, devido ao custo elevado de barras lisas + rolamentos.  
- **Fonte de alimentação:** chaveada de 30A, suprindo bem a demanda energética.  
- **Eletrônica:**  
  - Placa **RAMPS 1.4**  
  - **Arduino Mega 2560**  
  - Drivers **A4988**  
- **Firmware:** [Marlin](https://marlinfw.org/) (firmware open-source para impressoras 3D, com modificações para este projeto).  
- **Software de impressão:** Repetier-Host.



---

##  Lista de Materiais 

| Item                              | Quantidade | Preço (R$) |
|----------------------------------|------------|------------|
| Arduino Mega 2560                 | 1          | 106,00     |
| RAMPS 1.4                         | 1          | 33,51      |
| Drivers A4988                     | 4          | 40,97      |
| Motores Nema 17                   | 4          | 104,92 (usados) |
| Mesa aquecida                     | 1          | 79,00      |
| Fuso trapezoidal TR8 (2mm × 300)  | 2          | 79,88      |
| Corrediças de gaveta 30 cm        | 6          | 39,00      |
| Filamento PLA (1kg)               | 1          | 60,00      |
| Termistor 100k Ohm                | 1          | 15,00      |
| Sensor de fim de curso (endstop)  | 3          | 29,80      |
| Fonte chaveada 30A                | 1          | 49,99      |
| Acoplamento para fusos TR8        | 2          | 30,75      |
| Correia dentada + polias Nema     | 2          | 33,88      |
| Extrusora + Hotend completo       | 1          | 150,00     |

---

##  Montagem
1. Montagem da estrutura de madeira.  
2. Instalação das corrediças de gaveta como guias lineares.  
3. Fixação dos motores Nema 17 e fusos trapezoidais (eixo Z).  
4. Instalação das correias dentadas para os eixos X e Y.  
5. Conexão da eletrônica (Arduino + RAMPS 1.4 + A4988).  
6. Upload e configuração do firmware **Marlin**.  
7. Ajustes finos de calibração.  

---

##  Galeria
![1755462619670](https://github.com/user-attachments/assets/8d82be1d-51de-4de3-b1f4-d8176217d387)
<img width="1440" height="940" alt="Creation_Image_1755463234356_1" src="https://github.com/user-attachments/assets/422b5f16-04b7-49a4-80f7-64bfedf4a2b5" />

![1755462619723](https://github.com/user-attachments/assets/c0cf7253-9173-4a21-adfa-6577aae9fe19)
![1755462619716](https://github.com/user-attachments/assets/180f1a6d-e644-42bb-8809-2a528ae5889f)
*Impressão de um projeto para robô sumô*
  

---

##  Referências
- [Firmware Marlin](https://marlinfw.org/)  
- [Repetier-Host](https://www.repetier.com/)  

---

##  Licença
Este projeto é **open-source** sob a licença MIT — sinta-se livre para usar, modificar e compartilhar.
