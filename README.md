# Starbie
making a totally not starboy

Current state: <br />
<img width="617" height="380" alt="image" src="https://github.com/user-attachments/assets/600765c1-07a0-4264-bb6f-b08b0e864301" /> <br />
the schematic is complete!!

However the wiring is not ready yet, I will try to fix it later, hopefully the esp32 will be wired soon!!!
<img width="756" height="645" alt="image" src="https://github.com/user-attachments/assets/ab9d797a-009d-4646-a435-79156d65fa5a" />

I will make my unique stuff to the project be the shape of my pcb and the code i put onto it in a bit.

UPDATE:

<img width="728" height="637" alt="Screenshot 2026-10-12 004409" src="https://github.com/user-attachments/assets/8e22e3fa-1378-4b05-a080-e9d93f34605e" />

<img width="757" height="224" alt="image" src="https://github.com/user-attachments/assets/ddf19084-822f-4e80-ae78-232cdea9154e" />

I present to you a working, properly wired rubbish pcb that has my beautiful chud star in the code

<img width="32" height="32" alt="chudStar" src="https://github.com/user-attachments/assets/bb91624d-a09b-4f8e-91e5-dfbc7ca33cd7" /> <br/>


To assemble this I am going to solder the parts I get delivered to me together myself, then I'll flash the esp32. To do that, I will be following a guide from Seeed studio here: https://wiki.seeedstudio.com/XIAO_ESP32C3_Getting_Started/ and it will just use the arduino code + ide I used towards the end of my project.

BOM:


| Part | What it's for | Qty | Unit | Total | Vendor |
| --- | --- | --- | --- | --- | --- |
| [XIAO ESP32 C3](https://www.aliexpress.com/item/1005008791664713.html?spm=a2g0o.cart.0.0.4aa338daOut1Kk&mp=1&pdp_npi=6%40dis%21GBP%21GBP+8.93%21GBP+5.51%21%21GBP+5.51%21%21%21%402103956a17917658002171668e0fb0%2112000046678458240%21ct%21UK%21-1%21%211%210%21&pdp_ext_f=%7B%22cart2PdpParams%22%3A%7B%22pdpBusinessMode%22%3A%22retail%22%7D%7D) | Has all of the code in it | 1 | $7.30 | $7.30 | [aliexpress](https://www.aliexpress.com/item/1005008791664713.html?spm=a2g0o.cart.0.0.4aa338daOut1Kk&mp=1&pdp_npi=6%40dis%21GBP%21GBP+8.93%21GBP+5.51%21%21GBP+5.51%21%21%21%402103956a17917658002171668e0fb0%2112000046678458240%21ct%21UK%21-1%21%211%210%21&pdp_ext_f=%7B%22cart2PdpParams%22%3A%7B%22pdpBusinessMode%22%3A%22retail%22%7D%7D) |
| [0.96 OLED](https://www.aliexpress.com/item/1005005462085489.html?spm=a2g0o.cart.0.0.642a38daemhb93&mp=1&pdp_npi=6%40dis%21GBP%21GBP+2.15%21GBP+2.15%21%21GBP+2.15%21%21%21%402103956a17917653368926100e0fb0%2112000049496537372%21ct%21UK%21-1%21%211%210%21) | Screen for my chud star (i have to buy this in a bunch of 4) | 1 | $2.85 | $2.85 | [aliexpress](https://www.aliexpress.com/item/1005005462085489.html?spm=a2g0o.cart.0.0.642a38daemhb93&mp=1&pdp_npi=6%40dis%21GBP%21GBP+2.15%21GBP+2.15%21%21GBP+2.15%21%21%21%402103956a17917653368926100e0fb0%2112000049496537372%21ct%21UK%21-1%21%211%210%21) |
| [MPU6050](https://www.aliexpress.com/item/1005010057794277.html?spm=a2g0o.cart.0.0.603538darDm0ze&mp=1&pdp_npi=6%40dis%21GBP%21GBP+5.05%21GBP+4.80%21%21GBP+4.80%21%21%21%402103956a17917654480246860e0fb0%2112000050979433011%21ct%21UK%21-1%21%211%210%21) | allows starbie to sense itself being moved around | 1 | $6.42 | $6.42 | [aliexpress](https://www.aliexpress.com/item/1005010057794277.html?spm=a2g0o.cart.0.0.603538darDm0ze&mp=1&pdp_npi=6%40dis%21GBP%21GBP+5.05%21GBP+4.80%21%21GBP+4.80%21%21%21%402103956a17917654480246860e0fb0%2112000050979433011%21ct%21UK%21-1%21%211%210%21) |
| [DHT11](https://www.aliexpress.com/item/1005006296553760.html?spm=a2g0o.cart.0.0.4aad38daeHaqi1&mp=1&pdp_npi=6%40dis%21GBP%21GBP+3.06%21GBP+3.06%21%21GBP+3.06%21%21%21%402103956a17917655290597367e0fb0%2112000036654804037%21ct%21UK%21-1%21%211%210%21) | moisture and temp sensor | 1 | $4.05 | $4.05 | [aliexpress](https://www.aliexpress.com/item/1005006296553760.html?spm=a2g0o.cart.0.0.4aad38daeHaqi1&mp=1&pdp_npi=6%40dis%21GBP%21GBP+3.06%21GBP+3.06%21%21GBP+3.06%21%21%21%402103956a17917655290597367e0fb0%2112000036654804037%21ct%21UK%21-1%21%211%210%21) |
| [MX Switches](https://www.aliexpress.com/item/1005013018072298.html?spm=a2g0o.cart.0.0.4aad38daeHaqi1&mp=1&pdp_npi=6%40dis%21GBP%21GBP+3.48%21GBP+1.71%21%21GBP+1.71%21%21%21%402103956a17917655290597367e0fb0%2112000060011087503%21ct%21UK%21-1%21%211%210%21) | the buttons switches | 1 | $2.27 | $2.27 | [aliexpress](https://www.aliexpress.com/item/1005013018072298.html?spm=a2g0o.cart.0.0.4aad38daeHaqi1&mp=1&pdp_npi=6%40dis%21GBP%21GBP+3.48%21GBP+1.71%21%21GBP+1.71%21%21%21%402103956a17917655290597367e0fb0%2112000060011087503%21ct%21UK%21-1%21%211%210%21) |
| [Keycaps](https://www.aliexpress.com/item/1005009031620916.html?spm=a2g0o.cart.0.0.4aad38daeHaqi1&mp=1&pdp_npi=6%40dis%21GBP%21GBP+3.23%21GBP+3.23%21%21GBP+3.23%21%21%21%402103956a17917655290597367e0fb0%2112000047649050620%21ct%21UK%21-1%21%211%210%21) | keycaps for the buttons | 1 | $4.28 | $4.28 | [aliexpress](https://www.aliexpress.com/item/1005009031620916.html?spm=a2g0o.cart.0.0.4aad38daeHaqi1&mp=1&pdp_npi=6%40dis%21GBP%21GBP+3.23%21GBP+3.23%21%21GBP+3.23%21%21%21%402103956a17917655290597367e0fb0%2112000047649050620%21ct%21UK%21-1%21%211%210%21) |
| PCB | Starbie PCB!! I will be covering this as I am not in a high enough tier to do so | 1 | $17.76 | $17.76 |  <img width="1017" height="277" alt="Screenshot 2026-10-21 120622" src="https://github.com/user-attachments/assets/0ccae88a-bbe0-4026-8f8f-611e43c9dc86" /> |
| **Parts subtotal** | — | — | — | **$27.17** | — |
| **Tax & shipping** | — | — | — | **$3.72** | — |
| **Total (for Hackclub) ** | — | — | — | **$30.89** | — |
| **Total (for me) ** | — | — | — | **$17.76** | — |
