**TEST WEBSITE , PERSONAL WEBSITE SOON :)**

# Welcome to Astrobot's GitHub Page


> Hello This is me Astrobot , 12th grade Student passionate about Space, Science & Tech

## Some Famous Quotes 

* The greatest glory in living lies not in never falling, but in rising every time we fall. -_Nelson Mandela_

* The way to get started is to quit talking and begin doing. -_Walt Disney_

* Your time is limited, so don't waste it living someone else's life. Don't be trapped by dogma – which is living with the results of other people's thinking. -_Steve Jobs_

* If life were predictable it would cease to be life, and be without flavor. -_Eleanor Roosevelt_

* If you look at what you have in life, you'll always have more. If you look at what you don't have in life, you'll never have enough. -_Oprah Winfrey_

* If you set your goals ridiculously high and it's a failure, you will fail above everyone else's success. -_James Cameron_

* Life is what happens when you're busy making other plans. -_John Lennon_

# Mathematical Calculations Using Python

### Python Program to Print Fibonacci numbers

```python
x=0
y=1
count=0
while count<5:
  print(x)
  z=x+y
  x=y
  y=z
  count=count+1
```

### Python Program to Find Factorial 
```python
y = 1
num = int(input('Enter you number--'))
for x in range(1,num+1):
    y=y*x
print('factorial of '+ str(num) +' is ='+ str(y))

```

### Python Program to Find an Year is Leap year or Not
```python
x = int(input("Enter The year in format eg-2020--"))
if(x%100 == 0):
    if(x%400 == 0):
        print(str(x) +' is a leap year')
    else:
        print(str(x) +' is not a leap year')
else:
    if(x%4 == 0):
        print(str(x) +" is a Leap Year")
    else:
        print(str(x) +" is not a Leap year")
```
### Program to Download YT Videos 
```python
import youtube_dl


downlaod_qualities = { 
    "720p":"136",
    "480p":"135",
    "Audio-Only":"140",
    "1080p":"137"
}

ydl_opts = {
    'format': '136',      
    
}
#ydl_opts = {}
'''
with youtube_dl.YoutubeDL(ydl_opts) as ydl:
    ydl.list_thumbnails(info_dict=["https://youtu.be/r7EiKiwZH5s"])

print(downlaod_qualities.keys())'''


with youtube_dl.YoutubeDL(ydl_opts) as ydl:
    ydl.download(['https://youtu.be/r7EiKiwZH5s'])



```


## Link to Other Repositories 

> ### [Number Guessging Game Using Python](https://github.com/Astrobot-me/NUMBER_GUESSING_GAME)
> ### [Basic Discord Bot With 10 Plus Commands & with Fun comds](https://github.com/Astrobot-me/Basic_Discord_Bot-Discord.py-)
> ### [Some More Program Based on Basic Maths](https://github.com/Astrobot-me/Some-mathematical-calculations)

##### [My Youtube Channel 📺 - @Micro Gravity Wrokshop](https://www.youtube.com/channel/UCXcgqPN7rEx6IeeJQcTcaaQ)

##### [My Discord Server](https://discord.gg/b6h2GhCp)

##### [Another Discord Server Based on Space Theme Filled With 100s of Space Enthusiasts **NEW SPACE INDIA**](https://discord.gg/FSTW4FahvT)

##### [My Twitter- @Astrobot-me](https://twitter.com/Astrobot_me)

# Model Rocket Schmetics
#### **Project Micro Gravity Space**

![Not Found](https://discord.com/channels/817001090314403840/855387903953731624/855427310668742726)


#### **Gravity Model Rocket**

![Not Found](https://discord.com/channels/817001090314403840/855387903953731624/855431947492130836)


![Not Found](https://discord.com/channels/817001090314403840/855387903953731624/855432071244677150)

#### **Flight Computer Schemetic (Basic Data Logger)**
![Not Found](https://discord.com/channels/833966171555495946/834104870179962900/842027201331462174)


```markdown

Technical Details:- 
1st Resistor (from Left Side) - 330 ohms
2nd Resistor (in middle):-- 1k      ohm
3rd Resistor(right side)-- 100 ohm
Transistor -- NPN BC337
-----------------------------------------------
Parts Specification :- 
BMP180
MPU6050
HMC5883L
Micro Servo FS90R
TF card Reader
Buzzer 
led
Arduino UNO(You can aslo go with Mini)
```


