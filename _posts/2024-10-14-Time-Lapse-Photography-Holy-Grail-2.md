---
layout: post  
title: "Time Lapse Photography - Holy Grail - Part 2"  
categories: photography  
author:  
- Jia Shen  
---

#### **Intro**

Well, I didn't think I would do a time lapse this soon. But I did it at home on Sept 26 again to try out the new settings summarized from last time. Again, I encountered some problems.

---

#### **Camera and Settings**

Camera           | Lens                  | Focal Length     | Aperture         | ISO              | Shutter Speed     | White Balance
---------------- | --------------------- | ---------------- | ---------------- | ---------------- | ------------------| --------------
Sony A6600       | SEL50F18              | 50mm(APS-C)      | 1.8              | 100              | varies (auto)     | Auto

The interval was set to 6 seconds.
Shooting time was from 18:09 - 18:49, and the shutter speed varied from 1/320 to 1/3 respectively.

---

#### **Problems Encountered**

##### Sudden Color Shift
The white balance was always set to auto during my recent time lapse shootings. **White Balance**, according to ChatGPT, adjusts the color temperature in photos to make whites appear neutral, compensating for the color of the light source (warm or cool). This ensures colors look natural, mimicing what human eyes see.

In addition to the auto setting, the Sony A6600 provides a few other settings:

Setting         | Color Temperature
----------------| ------------------
Daylight        | 5500 - 6500 K
Shade           | 6500 - 8000 K
Cloudy          | 6500 - 8000 K
Incandescent    | 2500 - 3000 K

The color temperature (measured in Kelvin, K) describes the warmth or coolness of light. Lower numbers are warmer, higher numbers are cooler.

Regarding the time lapse, when the white balance was set to auto, the color tone may change drastically from frame to frame if a critical value in temeprature tiers is hit. For example, the two photos took at 18:29:30 PM and 18:29:36 PM appear drastically different. As result, there is a drastic color jump in the final composite time lapse video.

![first image](/assets/DSC03427.jpg)
![second image](/assets/DSC03428.jpg)

IMG Time       | Temperature     | Tint
---------------| ----------------| ------
18:29:30 PM    | 6800            | +14
18:29:36 PM    | 5350            | -5

The solution is to adjust all photos with the same selected temperature and tint.

##### Colorgrading
According to the a few video I consulted, photos need to be more saturated in order for the time lapse video to look natural. I have simply bring saturation up for +20% this time.

For post processing, I used the workflow LRT -> LR -> LRT -> FCP -> export.

LRT is the time lapse processing software, which is made for time lapse photo processing. It's great at identifying key frames, mass processing batch photos based on the key frame photos, deflicker (not existing problems for me but good to know!), smooth exposure, etc.

LR is Adobe Lightroom. It's used to color grade the key frames.

FCP is Final Cut Pro used to composite all photos into a time-lapse video.


---

#### **Final Results**

<iframe width="560" height="315" src="https://www.youtube.com/embed/WrsFUDQFKyA?si=Fwy6Ss4Z0fSQne63" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

#### **Summary**

##### Updated Settings

**Aperture priority**

- f/1.8 (to allow as much light in as possible)

**ISO**

- Auto 100-400 (if planning to use individual photos) or Auto 100-3200 (if only making the time-lapse video)
- ISO auto min. shutter speed: 4" (pushing shutter speed to a certain limit before ramping up the ISO)

**Interval Shooting Functions**

- Shooting interval: 6 seconds
- Shoot interval priority: On (prioritize interval over shutter speed)

**White Balance**
- Adjusted to suit the weather, but not auto

---

#### **Useful Resources**

[“荣获五星保姆教程”梦幻延时摄影后期全流程｜还附赠调色的，哈哈哈哈哈哈哈哈哈哈](https://www.bilibili.com/video/BV1SY4y1x7DA/?share_source=copy_web&vd_source=33d738271be75c7c8a4e2a998c000291)  
[LRTimelapse - Advanced Time Lapse Photography Made Easy](https://lrtimelapse.com/)

---

And again, I look forward to my next time lapse shooting! Maybe instead of a day-to-night shift, I will do a night-to-day shift. And I also heard that it's bird migration season in Shenzhen now. It would be fun to document that as well!
