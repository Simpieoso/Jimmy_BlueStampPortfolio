# My Portfolio
My main project is the Air Pollution Monitor. This project provides accurate and real-time data on air quality using a sophisticated network of integrated sensors and complex softwares. It is an initiative that marks a significant step forward to fight against environmental pollution and promote a clearner and healhier Earth. I chose this project because it delves into the statstics of air pollution, this is vital to raising awareness of the polluted air that we breath in. This project also teached me the background of climate change and the effects caused by air polluton. For example, humid air traps pollutants close to the ground and prevents them from dispersing into the atmosphere, this increases the pollutants in the air that we breath and it is extremely harmful to our lungs, this effect is significantly increased in urban areas.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Jimmy C | Aliso Niguel High School | Engineering | Incoming Senior

<!-- 
**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone


Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.
<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

```For your final milestone, explain the outcome of your project. Key details to include are:```
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE -->

<!-- 
# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

```For your second milestone, explain what you've worked on since your previous milestone. You can highlight:```
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone -->

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/kjlHnoHY3A0?si=sTwXQprJ3-yaH7-C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<!-- For your first milestone, describe what your project is and how you plan to build it. You can include: -->
My first milestone for my main project in creating a DIY air quality monitor involves the physical assembly of the device. I began by gathering all necessary hardware components, including sensors and a microcontroller. The assembly started with soldering headers onto the Feather boards and sensors for secure connections. Next, I wired these components together according to the detailed circuit diagram provided in the guide. Later, I will secure the finished hardware components into a secure box, this step will be done after the software has been coded. I will print this secure box using 3d printing programs. This step is crucial as it ensures the stability and durability of the monitor under various environmental conditions.

# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/FpjrL7eSlqs?si=uih6pWuu2X0zysOI&amp;controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

HU 054A Calculator
Components Used: 1x Intergraded Circuit, 1x Display, 17x Input Buttons, 1x Capacitor, 1x Circuit Board, 1x Battery, 1x Battery Holder, 1x Diodes

The assembly of my starter project the HU054A Calculator involved many complications. As a result, I studied about each component and how they contributed to the functions of the calculator. First, I learned about intergrated circuits (IC) which serves as the central processing unit, processing all of the arithmetic calculations. Secondly, I implimented keypads and labeled them with numbers to identify them. Upon pressing a button on the keypad, a signal will be transmitted to the IC. Amazingly, with its pre-set programming, it conducts basic arithmetic operations in seconds, and the outcomes of which are shown on an LCD screen. This entire operational sequence is powered by a battery.

Through the construction of my starter project, I learned many crucial lessons and gained invaluable educational experiences. To be able to successfully assemble my project, I honed my soldering techniques, and deepened my understanding of the roles of each electronic components that I will use such as resistors which limit the amount of voltages that go through the circuit, and capacitors that temporarily store electrical energy. Additionally, I developed essential troubleshooting skills to resolve any possible setbacks during my project. These steps formed a critical foundation for me towards the assembly of components in this project.

Throughout the assembly process of the HU054A Calculator, I faced a series of challenges and setbacks that tested my technical abilities and patience. A significant obstacle emerged when I improperly installed the battery. To resolve this issue, I carefully inspected and adjusted the battery’s placement within its compartment. Additionally, mounting the integrated circuit into the protective casing proved challenging; it required careful installation and exact alignments with the pin configuration on the circuit board, as any deviation could potentially break the fragile pins.

Lastly, upon reinstalling the battery, and careful installation of the integrated circuit,  I conducted multiple power tests and functionality checks to ensure that my calculator is working correctly.

# Schematics 
<img src="https://i.ibb.co/s3NJJN6/Copy-of-Calculator.png" alt="Calculator Image">

# Code

This code is made by 
<a href="https://www.geeksforgeeks.org/make-simple-calculator-using-python/">Geeks for Geeks</a>

```ruby
# Function to add two numbers
    def add(num1, num2):
        return num1 + num2

# Function to subtract two numbers
def subtract(num1, num2):
    return num1 - num2

# Function to multiply two numbers
def multiply(num1, num2):
    return num1 * num2

# Function to divide two numbers
def divide(num1, num2):
    return num1 / num2

print("Please select operation -\n" \
        "1. Add\n" \
        "2. Subtract\n" \
        "3. Multiply\n" \
        "4. Divide\n")

# Take input from the user
select = int(input("Select operations form 1, 2, 3, 4 :"))

number_1 = int(input("Enter first number: "))
number_2 = int(input("Enter second number: "))

if select == 1:
    print(number_1, "+", number_2, "=",
                    add(number_1, number_2))
elif select == 2:
    print(number_1, "-", number_2, "=",
                    subtract(number_1, number_2))
elif select == 3:
    print(number_1, "*", number_2, "=",
                    multiply(number_1, number_2))
elif select == 4:
    print(number_1, "/", number_2, "=",
                    divide(number_1, number_2))
else:
    print("Invalid input")
```

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Adafruit Feather M4 Express | Microcontroller Board | $22.95 | <a href="https://www.amazon.com/Adafruit-Feather-M4-Express-Featuring/dp/B07FB365TQ/ref=sr_1_1?crid=2FKMNXNN4WFSM&dib=eyJ2IjoiMSJ9.RcVg2ylFF85s17cYBRQ3E0LiOrgFDOg1Nc9Nnvs4fkKL06mtLBpRg6Q8SMOKfY93xgI2psomqlg1jG80YSajXJDDiAT8cnurmcbTbXirBBTzE66w2iISLA_P8NZU5BQYcSCYhZ9jscGcGi1RkXglIvQnres-_2rqrYlGNULqIMJBMrGdRnsoa6HlQtvqy3ZN6CS54hqqAvLkR04cXa3UYS-K5DgjIX8-7-WGHEoa0OE.UT19JpofY43Aowx7UWdMJRmM-KbZaCbAVaw22vRIYBM&dib_tag=se&keywords=Adafruit+Feather+M4+Express&qid=1718292758&sprefix=%2Caps%2C165&sr=8-1">Link</a> |
| Adafruit AirLift FeatherWing | Add-on board Designed To Provide Wi-Fi Capabilities to Microcontroller Projects | $12.95 | <a href="https://www.amazon.com/Adafruit-Feather-M4-Express-Featuring/dp/B07FB365TQ/ref=sr_1_1?crid=2FKMNXNN4WFSM&dib=eyJ2IjoiMSJ9.RcVg2ylFF85s17cYBRQ3E0LiOrgFDOg1Nc9Nnvs4fkKL06mtLBpRg6Q8SMOKfY93xgI2psomqlg1jG80YSajXJDDiAT8cnurmcbTbXirBBTzE66w2iISLA_P8NZU5BQYcSCYhZ9jscGcGi1RkXglIvQnres-_2rqrYlGNULqIMJBMrGdRnsoa6HlQtvqy3ZN6CS54hqqAvLkR04cXa3UYS-K5DgjIX8-7-WGHEoa0OE.UT19JpofY43Aowx7UWdMJRmM-KbZaCbAVaw22vRIYBM&dib_tag=se&keywords=Adafruit+Feather+M4+Express&qid=1718292758&sprefix=%2Caps%2C165&sr=8-1">Link</a>
| PM2.5 Air Quality Sensor and Breadboard Adapter Kit | Measure and Monitor the Concentration of Particulate Matter in The Air | $39.95 | <a href="https://www.amazon.com/PMS5003-Detection-Particle-Concentration-Conditioning/dp/B0BHZTCK8J/ref=sr_1_1 crid=1MTC4BPFGF7YP&dib=eyJ2IjoiMSJ9.Q5l9KVfoO64sWIyO7qsyM0GcCPshkMrn_Weu5F2PIn23f8d6b2h9XQPTN8xWQHmy.Dzrwiy4e4nkRlmfB6bQRW1RK2i8YGG48ojwiBAyZsJM&dib_tag=se&keywords=PM2.5+Air+Quality+Sensor+and+Breadboard+Adapter+Kit&qid=1718292832&sprefix=pm2.5+air+quality+sensor+and+breadboard+adapter+kit%2Caps%2C164&sr=8-1">Link</a> |
| Adafruit BME280 I2C | Measuring Environmental Condition | $14.95 | <a href="https://www.amazon.com/Adafruit-BME280-Temperature-Humidity-Pressure/dp/B013W1AJUY/ref=sr_1_1?crid=22XKT4EI6O3OH&dib=eyJ2IjoiMSJ9.oeZY4mNmH8Va9ODhjTA2CTFM7DP8o2WHvwCKsIa9N8sUChLpZD14RJZPrGGmml_p-bPppjz0UMe88JdVoRJy_n_szLZWR2xR8R7399NiwRMlSJ9hKhv7ppn-rxhrueVci455iLgV2Zy-jF5h2v0ECfpwj9gndDY63yEpg4ujUgkw354EQkgMvr5tjyb6ypuLdeXVLFzwOnlAG2WzD0yly9C8p8hpzYqlW-17WkMF3Dc.omSIxoc0xIJYtVbjd2BoMkuC5xnfWWkAj6vJWrYiQbM&dib_tag=se&keywords=Adafruit+BME280+I2C&qid=1718292855&sprefix=pm2.5+air+quality+sensor+and+breadboard+adapter+kit%2Caps%2C129&sr=8-1">Link</a> |
| FeatherWing Doubler | Extend The Functionality of Adafruit Feather Boards | $7.50 | <a href="https://www.amazon.com/FeatherWing-Doubler-Prototyping-Add-Feather/dp/B01B2GZF64/ref=sr_1_1?crid=2L1DAIHPE8XUY&dib=eyJ2IjoiMSJ9.Ts6UwLVLy6DpVXyU82IK0T-kAE_QXWjHP-UohHSD4wjGjHj071QN20LucGBJIEps.ahIec1G_1-xkqKioH5hcjtljz4To8MEXtN-oUbjf3Kg&dib_tag=se&keywords=FeatherWing+Doubler&qid=1718292880&sprefix=adafruit+bme280+i2c%2Caps%2C906&sr=8-1">Link</a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1] [https://trashytuber.github.io/YimingJiaBlueStamp/](https://deringur.github.io/BSE_Derin_Portfolio/)
- [Example 2] [(https://sviatil0.github.io/Sviatoslav_BSE/)](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 3] [(https://arneshkumar.github.io/arneshbluestamp/)](https://sviatil0.github.io/Sviatoslav_BSE/)

To watch the BSE tutorial on how to create a portfolio, click <a href="https://sites.google.com/bluestampengineering.com/student-wiki/portfolio-milestone-video-instructions?authuser=0">here</a>
