 ​from​ ​telethon​ ​import​ ​events 
 ​import​ ​asyncio 
 ​import​ ​os 
 ​import​ ​sys 
  
  
 ​@​borg​.​on​(​events​.​NewMessage​(​pattern​=​r"\.pol2"​, ​outgoing​=​True​)) 
 ​async​ ​def​ ​_​(​event​): 
 ​    ​if​ ​event​.​fwd_from​: 
 ​        ​return 
 ​        
  
 ​    ​await​ ​event​.​edit​(​"🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​) 
 ​    ​await​ ​event​.​edit​(​"🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​) 
 ​    ​await​ ​event​.​edit​(​"🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​) 
​     await​ ​event​.​edit​(​"🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​) 
     ​await​ ​event​.​edit​(​"🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​)
     ​await​ ​event​.​edit​(​"🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​) 
 ​    ​await​ ​event​.​edit​(​"🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​)
     ​await​ ​event​.​edit​(​"🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​) 
 ​    ​await​ ​event​.​edit​(​"🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​)
     ​await​ ​event​.​edit​(​"🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​) 
 ​    ​await​ ​event​.​edit​(​"🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​)
     ​await​ ​event​.​edit​(​"🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴​\n​🔵🔵🔵⬜⬜⬜🔴🔴🔴"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​) 
 ​    ​await​ ​event​.​edit​(​"🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵​\n​🔴🔴🔴⬜⬜⬜🔵🔵🔵"​) 
 ​    ​await​ ​asyncio​.​sleep​(​0.5​)
 ​    ​await​ ​event​.​edit​(​"`** ❄❄❄❄❄Идут сборы участников сообщества KYS❄❄❄❄ `**"​)
