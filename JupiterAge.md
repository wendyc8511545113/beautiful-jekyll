---
layout: page
title: Jupiter Age
subtitle: Find out your age in Jupiter!
---

# 🚀 How Old Are You on Jupiter? 🌌  

Ever wondered how many years you've been around *if you lived on Jupiter*? 🪐 Well, wonder no more!  

This **C# program** calculates your **Jupiter age** based on Earth's years. Since Jupiter takes **11.86 Earth years** to orbit the Sun, you're *technically* much younger over there!  


```csharp
     
      int userAge = 11;  // Your Age
      Console.WriteLine($"I am {userAge} Earth years old.");
      
      double jupiterYears = 11.86;   // Length of years on Jupiter (in Earth years)
      Console.WriteLine($"Jupiter in 1 Earth year is {jupiterYears} Jupiter years.");
     
      double jupiterAge = userAge / jupiterYears;    // Age on Jupiter
      Console.WriteLine($"I would be {jupiterAge} Jupiter years old.");
      
      double journeyToJupiter = 6.142466;   // Time to Jupiter
      Console.WriteLine($"It will take {journeyToJupiter} years to get to Jupiter.");
      
      double newEarthAge = userAge + journeyToJupiter;   // New Age on Earth
      Console.WriteLine($"My new Earth age would be {newEarthAge}.");
      
      double newJupiterAge = newEarthAge / jupiterYears;   // New Age on Jupiter
      Console.WriteLine($"And my name Jupiter age would be {newJupiterAge}."); 
