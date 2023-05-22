# SCO - Self checkout system - Software Engineer course project
SCO - self checkout system based on AI

**NOTE - IF YOU WANT TO LAUNCH THE PROJECT FILE YOU NEED TO OPEN IT THROUGH ITEMIS (YAKINDU) IN YOUR COMPUTER AND RUN IT**

This system is based on self checkout system. 
What we wanted to implement is a new way to use the self checkout machine, using AI.
We made a State Chart, that includes the AI itself, regular machine (in case something goes wrong with the AI system while it runs)
and also implemented the coupon state alongside with the payment method, receipt and deleting items.

Basically, when a customer wants to check out with his groceries, all he have to do is to place his items in a small box, this box have scanners and cameras, that is supposed to take a picture of the items, and define throught its data mining and AI (machine learning algorithm - usually based on K means) the products that the customer have chosen, to put it in his grocereis bag. Note that if one of the sensors or camera doesnt work, the machine automatically goes to the regular scanning machine where the customer scanning and wheighting his own products before checkout.

We also implemented errors, in case something goes wrong with the coupon, payment method, machine goes off in case of no electricy etc.

During this semester we were asked to make a small machine but we wanted to implement a big machine that can cover all states it can have, while making a new innovation that right now is only on its start in Taiwan

credits goes to:
https://www.prnewswire.com/news-releases/caper-launches-plug-and-play-autonomous-checkout-counter-for-mini-market-and-small-retail-stores-301151982.html
https://www.caper.ai/2021-designs/counter-2021#wf-form-Contact-Form
https://stackoverflow.com/questions/64089827/advice-on-which-uml-diagram-to-choose-for-self-service-checkout
https://mobidev.biz/blog/how-to-implement-ai-self-checkout-in-retail-if-you-are-not-amazon
