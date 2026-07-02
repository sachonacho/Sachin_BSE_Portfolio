# Tendon-Driven Robotic Hand
This project is a robotic hand driven by servos attached to rope tendons. The hand is controlled by a glove with flex sensors which sends numeric output to the robotic hand. The robotic hand then receives that numeric input and converts it into motion by flexing the tendons and therefore the fingers.
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Sachin S | The College Preparatory School | Mechanical Engineering | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](Sachin S.png)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

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
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| 1x Arduino Uno Rev3 | The Arduino Uno controls the several servos connected to the hand, controlling how much each tendon is pulled, and therefore how much the finger is flexed. | $33.98/unit | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://store.arduino.cc/products/arduino-uno-rev3)"> Link </a> |
| 6x MG996R 55g Metal Gear Torque Digital Servo Motor | These servos wind up the rope tendons attached to the hand, thus flexing the fingers depending on the Arduino input | $26.98/6 units | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/6-Pack-MG996R-Torque-Digital-Helicopter/dp/B0BMM1G74B/ref=sr_1_3_sspa?crid=3IKWW61WANINS&dib=eyJ2IjoiMSJ9.HAru7Zjv6UHS76wqocnm-ErEpMlnonBzf_eUh5W7RNvUrHls2zjpI0F_DoNHxF-fK-QlRjXKUjSMa7o-QTXBKMCWu1RmSX-sOaT1prqcz62W0yIse56Qm7Y9tGUQF_WWmry4C-ZXXhArFoEaVXY0BQNjELvotDWADWkDucvVhD_xvLzgeswbspKw5tzQa-IoUUnV63GiDsuzXNZyEqCkLYFrGq382CsHngjfbSLvdxdBi4WQkrTGy1mS-UWPbiX_Vs6ySAsIrPLCR2CZh77KeU57ojgUMXAdQkumfaIFeQ8.raG0zCHBuWMWZJhFQcTFXkhHhp5tzeqm2Wl5JAm4AXM&dib_tag=se&keywords=MG996R%2BHigh%2BTorque%2BServo%2BMotor&qid=1779668225&sprefix=mg996r%2Bhigh%2Btorque%2Bservo%2Bmotor%2Caps%2C163&sr=8-3-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1)"> Link </a> |
| 6x Flex sensors | The flex sensors are used in the glove to sense how much the users hand flexes in order to assign that amount a number. This number is then sent to the Arduino, which tells the servos how much to rotate to mimic the movement in the glove. | $7.95/unit | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| 1x Fishing Line | What the item is used for | $9.99/unit | <a href="https://www.amazon.com/Reaction-Tackle-Moss-Green-150yd/dp/B01JVKUOQ4/ref=sr_1_1_sspa?crid=CWJLB3QQXS70&dib=eyJ2IjoiMSJ9.spSYgmxS3aBQLGcgI8qqSND6lYKoo5c9t0eEj1RkZ3vsbY9JFpA1XS48fIZdkBaC3TRXt_AYzhegmP9JgNIt9SGjDHWPrYVPgxvMu-WWNlkvOEcApch8SicXKaOvuALK0-Pgu8FY20-OOlID8j4Tqv4ifdSFlYWDSRsCf3rQl3-2Y2rYV9cj5_bX6kAVxvqQFdLxi17_3j6JekQdpMnkrxit0V15Mu4NM-K769tW7IgW5VIwyG3IeBN959cb4TX3d1nNdo_eC554nMoQLOrexcDrd4zrjsg-Mh9R9txSoPk.1Ek9z79wp0B-gWKva3TtPKy-NWL7Dtgnse8zJL514Ac&dib_tag=se&keywords=braided%2Bfishing%2Bline&qid=1779670766&sprefix=briaded%2Bfishing%2Blin%2Caps%2C168&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| 15x 1in. Extension Springs | What the item is used for | $6.99/ a lot of units | <a href="https://www.amazon.com/PPFEITOU-Extension-Springs-Stainless-1-5inch/dp/B0G5836DQ5/ref=sr_1_2_sspa?crid=V1MU1RKJKXPE&dib=eyJ2IjoiMSJ9.PoFc8_AxlwHurG_ylaYqU8H2YhAP6OfO-lYuYwwxrfzvoDB4YsrLzsKHtnQ6YH_z5FwiNCqMoJiJGx8xl6jM3YJTM3lFCAuT9h56c-f3Q9yuheZHbvXAiKFl-AJ_9hlZyzuOm5Gt9WYMS4TEFxnx5pKVT9QVMjlR4yAJdLCCK2LH8Fx6vFR1lk630VdEjmlXRetsz5f5WQbuPJER1Tm370CdI-5XptwFtaMYR2_it2Q.b1M7i050pylIbhh0655zM2kc9kbzfww89oTYTHfuFgA&dib_tag=se&keywords=small%2Bextension%2Bsprings&qid=1779670847&sprefix=small%2Bextension%2Bsprings%2Caps%2C143&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| 2mm Metal Pins | What the item is used for | $7.29/a lot of pins | <a href="https://www.amazon.com/MECCANIXITY-Support-Stainless-Cabinets-Furniture/dp/B0F37D84KM/ref=sr_1_1_sspa?dib=eyJ2IjoiMSJ9.cc92aJRXaBV8Faoe9EhewiREOAlc8FsO1E4zMFLtLVxSwiRZij-hd8jS3o1nQ7aZoKyN8PbNCpnFYLD2k1NccKmNG1HZjd0Sj4FLZVX6Hi-OXOSaEshbKeWju70KPAKmghuNcKEqqh12ThbE-3iZxR9pgxcIdZA0CHVzrCwhnU_NQC93iN3FY7n7mrPZEtKxqLh-IQo0ODRHimu0-_TRo8H54e5jORYCed2RIBaqm_-N5HPv7Fed2eKrJiE5N4NLDvsg7gpIAG7TTm3yapsfebLNUcg8S_r96lXpJw2c-sY.v2jzEgC7GNDoE4fs-4VVuRTqGhfumMdERIMmfm9w9jU&dib_tag=se&keywords=SMALL%2Bmetal%2Bpins&qid=1779671236&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| PLA filament | What the item is used for | $22.53/spool | <a href="https://www.homedepot.com/pep/Wellco-1-16-in-Dia-8-in-W-White-3D-Printer-Filament-PLA-Materail-No-Tangling-for-3D-Printing-2-2-lbs-PF1751W/328385877?source=shoppingads&locale=en-US&fp=ggl&pla=&mtc=SHOPPING-BF-CDP-GGL-D25P-025_009_PORTABLE_POWER-NA-Multi-NA-PMAX-NA-NA-NA-NA-NBR-NA-NA-NA_PrioTest3BAU_National&cm_mmc=SHOPPING-BF-CDP-GGL-D25P-025_009_PORTABLE_POWER-NA-Multi-NA-PMAX-NA-NA-NA-NA-NBR-NA-NA-NA_PrioTest3BAU_National-20424844709--&gclsrc=aw.ds&gad_source=1&gad_campaignid=20283669755&gbraid=0AAAAADq61UfVEkXiHljmaz3ltFeowzXbZ&gclid=Cj0KCQjww8rQBhDjARIsAE43KPOKzSY06J5t-2UHtqE_EJNUQ1VfHEiH_-Wdc7XMCWrYA_ujNHCMMSkaAo6yEALw_wcB"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
