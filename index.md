# Gesture Controlled Robotic Car
I have been working to make a gesture controlled rover. After hours of concentrated effort, I was able to create a robotic car that can move according to the movement of one's hand. I loved where the two worlds of physical engineering and software met to create a versatile and unique rover. This project has furthered my passion in the field as I have now gained a new understanding and appreciation of circuitry, motors, and coding. My biggest challenges were understanding the concepts of energy transfer, breadboarding, and soldering, but once I mastered the skills, creating a functional product was far easier. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Joel A. | Monroe Township High School, NJ | Mechanical/Software Engineering | Incoming Junior

![Controller Schematic](GitHubProfilePic.png)

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/RnTC0cEu_lU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation of the different components of your project and how they will all integrate together
- Chasies, motors, motor drivers, battery packs, batteries, screws, power and ground cables, Arduino, breadboard
- Without using any code, the rover is able to transfer energy from the batteries in order to move the wheels forward.
- Had to reposition the motors to have the copper pads facing outward, consolidation of wires, and wire configuration
- Will upload code to the Arduino and Arduino micro. Must connect Bluetooth to the handpiece and makes sure Bluetooth and accelerometer are correctly connected to the Arduino micro.  

# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/RnTC0cEu_lU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

![Car Schematic](CarSchematic.jpg)
![Controller Schematic](ControllerSchematic.png)

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Smart Car Kit | The chasies and motors of the car | $18.99 | <a href="https://www.amazon.com/gp/product/B06VTP8XBQ"> Link </a> |
| 2 Bluetooth Modules | Used for communicating between the Arduino uno and micro | $20.78 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Arduino Uno | Controlls the car | $27.60 | <a href="https://store.arduino.cc/products/arduino-uno-rev3"> Link </a> |
| Arduino Micro | Controlls the handpiece | $25.50 | <a href="https://www.amazon.com/Arduino-Micro-Headers-A000053-Controller/dp/B00AFY2S56/ref=sr_1_3?keywords=Arduino%2BMicro&qid=1691589817&s=electronics&sr=1-3&th=1"> Link </a> |
| Motor Driver | Controlls the motors | $6.99 | <a href="https://www.amazon.com/Qunqi-Controller-Module-Stepper-Arduino/dp/B014KMHSW6/ref=asc_df_B014KMHSW6/?tag=hyprod20&linkCode=df0&hvadid=167139094796&hvpos=&hvnetw=g&hvrand=13469222211329594770&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032008&hvtargid=pla-306436938191&psc=1"> Link </a> |
| Breadboards | Circuts that mediate energy transfers | $9.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Soldering Kit | To prevent energy leakage | $30.00 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Velcro | To fasten parts together | $9.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Wires | Electrically connects all parts | $6.98 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Batteries | Power source | $9.70 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Battery Holder | Power source carrier | $6.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Sourcing Guide
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Smart Car Kit | The chasies and motors of the car | $18.99 | <a href="https://www.amazon.com/gp/product/B06VTP8XBQ"> Amazon </a> |
| 2 Bluetooth Modules | Used for communicating between the Arduino uno and micro | $20.78 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Amazon </a> |
| Arduino Uno | Controlls the car | $27.60 | <a href="https://store.arduino.cc/products/arduino-uno-rev3"> Arduino </a> |
| Arduino Micro | Controlls the handpiece | $25.50 | <a href="https://www.amazon.com/Arduino-Micro-Headers-A000053-Controller/dp/B00AFY2S56/ref=sr_1_3?keywords=Arduino%2BMicro&qid=1691589817&s=electronics&sr=1-3&th=1"> Amazon </a> |
| Motor Driver | Controlls the motors | $6.99 | <a href="https://www.amazon.com/Qunqi-Controller-Module-Stepper-Arduino/dp/B014KMHSW6/ref=asc_df_B014KMHSW6/?tag=hyprod-20&linkCode=df0&hvadid=167139094796&hvpos=&hvnetw=g&hvrand=13469222211329594770&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032008&hvtargid=pla-306436938191&psc=1"> Amazon </a> |
| Breadboards | Circuts that mediate energy transfers | $11.99 | <a href="https://www.amazon.com/dp/B07DL13RZH/ref=redir_mobile_desktop?_encoding=UTF8&aaxitk=b163d500edcc33b8ecdb35867663512a&content-id=amzn1.sym.53aae2ac-0129-49a5-9c09-6530a9e11786%3Aamzn1.sym.53aae2ac-0129-49a5-9c09-6530a9e11786&hsa_cr_id=4991273630901&pd_rd_plhdr=t&pd_rd_r=e6730cd8-8e3e-463d-932b-2c49d394f510&pd_rd_w=jX1If&pd_rd_wg=pAAek&qid=1656710515&ref_=sbx_be_s_sparkle_mcd_asin_0_img&sr=1-1-a094db1c-5033-42c6-82a2-587d01f975e8"> Amazon </a> |
| Soldering Kit | Melting metal to prevent energy leakage | $16.99 | <a href="https://www.amazon.com/Soldering-Kit-Temperature-Desoldering-Electronics/dp/B07GTGGLXN/ref=asc_df_B07GTGGLXN/?tag=hyprod-20&linkCode=df0&hvadid=241999416883&hvpos=&hvnetw=g&hvrand=137463208067721732&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9031525&hvtargid=pla-590653449503&psc=1"> Amazon </a> |
| Velcro | To fasten parts to the car | $9.99 | <a href="https://www.amazon.com/GOHOOK-Inch-Sticky-Back-Hook/dp/B08GSHFZYP/ref=sr_1_4?crid=3NVEKHZB0VS4&keywords=1+inch+strenco&qid=1688157474&s=hi&sprefix=1+inch+strenco%2Ctools%2C135&sr=1-4-catcorr"> Amazon </a> |
| Dupont/ Jumper Wires | Electrically connects all parts | $6.98, 8.56 | <a href="https://www.amazon.com/Elegoo-EL-CP-004-Multicolored-Breadboard-arduino/dp/B01EV70C78/ref=sxin_16_pa_sp_search_thematic_sspa?content-id=amzn1.sym.1c86ab1a-a73c-4131-85f1-15bd92ae152d%3Aamzn1.sym.1c86ab1a-a73c-4131-85f1-15bd92ae152d&crid=1W8VOCW8VRTMK&cv_ct_cx=arduino%2Bwires&keywords=arduino%2Bwires&pd_rd_i=B01EV70C78&pd_rd_r=218cf583-d57e-41b5-a4ec-d2a314453f6b&pd_rd_w=2SIL7&pd_rd_wg=fH7js&pf_rd_p=1c86ab1a-a73c-4131-85f1-15bd92ae152d&pf_rd_r=0DND7VXEDEY7YWT0M00Q&qid=1689707684&s=hi&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=arduino%2Bwire%2Ctools%2C145&sr=1-1-364cf978-ce2a-480a-9bb0-bdb96faa0f61-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9zZWFyY2hfdGhlbWF0aWM&th=1" > Amazon </a>, <a href="https://www.amazon.com/ALMOCN-Assorted-Preformed-Breadboard-Prototyping/dp/B08JP7K7RF/ref=sr_1_9?crid=12LAUBW58PGMU&keywords=arduino+wire+kit&qid=1691591636&s=hi&sprefix=arduino+wire+kit%2Ctools%2C111&sr=1-9" > Amazon </a> |
| Batteries | Power source | $9.70 | <a href="https://www.amazon.com/AmazonBasics-Performance-Alkaline-Batteries-20-Pack/dp/B00NTCH52W/ref=sr_1_1_ffob_sspa?keywords=20+AA+batteries&qid=1688157701&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Amazon </a> |
| Battery Holder | Power source carrier | $6.99 | <a href="https://www.amazon.com/Pack-Battery-Holder-Bundle-QTEATAK/dp/B07WY3VMNN/ref=sr_1_1_sspa?crid=3PY05FESGZNC8&keywords=battery+holders&qid=1689707792&sprefix=battery+holder%2Caps%2C150&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Amazon </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Step By Step Guide]([(https://docs.sunfounder.com/projects/3in1-kit/en/latest/car_project/car_move_by_code.html)])
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
