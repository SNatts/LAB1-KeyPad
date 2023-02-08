# LAB1-KeyPad
## Description
Build system that **get input from HC-35 Matrix Button** to **match with student ID** in system.
If input ID match with ID in system, LD2 on Nucleo F411RE will turn on.
![image](https://user-images.githubusercontent.com/122529018/216011376-a624a931-b4cf-4a7f-abbe-556557c80f82.png)    
HC-35 Matrix Button - image by [amazon](https://www.amazon.com/Liyafy-Buttons-Keyboard-Marquee-Independent/dp/B07TFFL1JX "HC-35")    
## System Requirement
### Pad Layout
![image](https://user-images.githubusercontent.com/122529018/216014040-b2c3454e-9604-4113-95d0-2306f9ed8494.png)
1. 0-9 numeric pad: user number input
2. CC: Clear Content, Clear all input
3. BKSP: Backspace, clear most right-hand position of the sequence.
4. OK: Submit ID to match in system.
### ID structure
![image](https://user-images.githubusercontent.com/122529018/216016541-eb8f7a68-ce0b-494a-b46e-6ccc0713e36f.png)
ID will have 11 Digits.
### Restrictions
1. System will allowed user to input number as most at 11 digit, input that user key after it full it will not accepted.
2. When user push CC button after LD2 is turned on, System will automatically turn off LD2.
