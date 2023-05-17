# EngenheiroDados

#Neste momento vou passar os comando para ele abrir o navegador chrome e abrir o sistema no qual ele terá que fazer o dowmload 
#do arquivo.

pyautogui.press("win")
pyautogui.write("chrome")
pyautogui.press("enter")
pyautogui.write("https://pages.hashtagtreinamentos.com/aula1-intensivao-sistema")

time.sleep(1)
pyautogui.press("enter")
pyautogui.click(x=549, y=348)
pyautogui.write("jessica.treinamentos@gmail.com")
pyautogui.press("enter")

time.sleep(3)
pyautogui.click(x=605, y=426)
pyautogui.press("enter")
pyautogui.write("Treinamento@Python202")
pyautogui.press("enter")

time.sleep(3)
pyautogui.click(x=640, y=483)
pyautogui.click(x=297, y=309)
time.sleep(2)
pyautogui.click(x=930, y=306)
time.sleep(1)
pyautogui.click(x=984, y=571)
