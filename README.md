# bleachbot
Plays Bleach Online, based on Automate the Boring Stuff's Sushi Bot

import pyautogui, time

print('Starting Home Automation..2...1...')
time.sleep(2)
pyautogui.click(1270, 7) #bring browser into focus

time.sleep(3)
pyautogui.click(1375, 700) #home icon
time.sleep(2)
print('Lucky Cat time')
for i in range(4):
    pyautogui.click(570, 287) #lucky cat icon
    time.sleep(1)#wait
    i += 1

print('Butterfrees!')
time.sleep(2)
pyautogui.click(780, 710)
time.sleep(2)
pyautogui.click(1071, 612)
time.sleep(2)
pyautogui.click(514, 357)   
time.sleep(2)
pyautogui.click(854, 266)


print('Konso Time!')
i = 0
for i in range(8):
    print('Round ' + str(i + 1))
    time.sleep(2)
    pyautogui.click(811, 448)#konso icon   
    time.sleep(30)
    pyautogui.click(828, 475) #loot all button
    time.sleep(2) #wait
    pyautogui.click(828, 475) #loot all button

    
print('Interact with waifu')
pyautogui.click(1320, 339) #girlfriend icon
pyautogui.click(1257, 220) #buy something for her
time.sleep(1)
pyautogui.click(1032, 336) #house icon
for i in range(12):
    pyautogui.click(1032, 336) #house icon
    time.sleep(2)
    pyautogui.click(924, 298) #soul interaction tab
    time.sleep(2)
    pyautogui.click(843, 518) #normal interaction button
    time.sleep(3)
    pyautogui.click(1116, 270) #x to close
    pyautogui.click(1116, 246) #x to close    
    time.sleep(62) #1 minute cooldown plus wait time
    i += 1
    
print('Party time')    
pyautogui.click(1032, 336) #house icon
time.sleep(2)
pyautogui.click(836, 304) # party tab
for i in range(7):
    time.sleep(1)
    pyautogui.click(913, 559)
    i += 1
pyautogui.click(1116, 270) #x to close
pyautogui.click(1116, 246) #x to close    

print('Friend\'s house time!')
pyautogui.click(1403, 623) #expand friend list
time.sleep(2)
pyautogui.click(1365, 588) #pick friend
time.sleep(2)
for i in range(8):
    pyautogui.click(811, 448)#konso icon
    time.sleep(30) #wait
    pyautogui.click(828, 475) #loot all button
    time.sleep(2) #wait
    pyautogui.click(828, 475) #loot all button
    i += 1
    
print('Friend\'s girlfriend time!')
pyautogui.click(1026, 349)
time.sleep(2)
pyautogui.click(844, 308)
time.sleep(2)
for i in range(8):
    pyautogui.click(917, 563)
    time.sleep(1)
    i += 1
pyautogui.click(1113, 266)


print('Go Back Home')
pyautogui.click(213, 252) #my home button
time.sleep(3)

print('Butterfrees!')
pyautogui.click(780, 710) #butterfly icon
time.sleep(2)
pyautogui.click(514, 357) # feed butterflies  
time.sleep(2)
pyautogui.click(854, 266) #x to close



