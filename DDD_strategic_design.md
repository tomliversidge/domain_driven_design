# Domain Driven Design - where should it be used?

Take from Greg Young's class. 

Context  | Competetive advantage | Development effort |
 ------------ | :-----------: | :-----------: |
Public Web|M|M||
Intranet|S|S|
Warehousing|M|M
Internal Tracking|L|L

Apply DDD where you have a LL, a complex domain where you have competetive advantage. Buy an off the shelf product when you have SL 
i.e. no competetive advantage but high development cost.

How long does it need to live? A product that lives for a week has much different tradeoffs to one that needs to live for years.

The hard part about programming is not the programming it is getting the right model. Favour lots of small systems over a large system. This way, you worry less about tech debt, or wrong decisions and rewrites are less expensive.

