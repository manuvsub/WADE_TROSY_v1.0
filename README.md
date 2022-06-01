NMR pulse sequences and RF shapes for the experiments in PCCP(2022)

Cite Reference articles @  PNAS-nexus(2022) and PCCP(2022)

The script and algorithms are patented @ https://patentcenter.uspto.gov/#!/applications/16861506



WADE-TROSY Pulse sequence in Bruker format is 'wadetrosy_v5_3.mpp'. The RF shapes are listed below 

| Shape Name| Operation Type  | Nuclei | Pulse Length factor | Pulse Length | Max RF amplitude | Bandwidth |
| -------------   | ------------- | ------------- | ------------- | ------------- | ------------- |------------- |
| wade_pix_25.900p1_bw1.75B1.mrf   | WADE-π    | 1H 	| 25.9| 25.9*50us = 1295us	| 5 kHz	| 1.75*B1  |
| wade_pix_37.250p1_bw2.82B1.mrf   | WADE-π    | 1H 	| 37.25| 37.25*50us = 1862.5us	| 5 kHz	| 2.82*B1 |
| wade_pix_47.200p1_bw3.85B1.mrf   | WADE-π    | 1H 	| 47.2| 47.2*50us = 2360us	| 5 kHz	| 3.85*B1 |
| pix_7.984p1_bw0.70B1.mrf   | Amide π    | 1H 	| 7.984| 7.984*10us = 79.84us	| 25 kHz	| 0.7*B1 |
| z2iz_4.610p1_bw0.80B1.mrf   | Inversion    | 15N 	|4.610|4.610*35us = 161.35us	| 7.1429 kHz	| 0.8*B1 |
| pix_7.093p1_bw0.80B1.mrf   | π    | 15N 	|7.093|7.093*35us = 248.255us	| 7.1429 kHz	| 0.8*B1 |

Water selectivity and bandwidth can be tuned by changing the RF power, the correponding pulse length is calculated by multiplying the 90 degree pulse length with the pulse length factor for each pulse. 

consider the 'wade_pix_25.900p1_bw1.75B1.mrf' shape,

for RF amplitude 25kHz (=> 90 pulse length = 10us), pulse length = 25.9*10us = 259 us 

for RF amplitude 5kHz (=> 90 pulse length = 50us), pulse length = 25.9*50us = 1295us 
 

------------------------------------------------------------------------------




Copyright & License Statement

RF pulse shapes are copyrighted by Regents of the University of Minnesota and the software for generating RF shapes covered by US patent 11,221,384. Regents of the University of Minnesota will license the use of RF shapes solely for educational and research purposes by non-profit institutions and US government agencies only. For other proposed uses, contact umotc@umn.edu. The software may not be sold or redistributed without prior approval. One may make copies of the software for their use provided that the copies, are not sold or distributed, are used under the same terms and conditions. As unestablished research software, this code is provided on an "as is'' basis without warranty of any kind, either expressed or implied. The downloading, or executing any part of this software constitutes an implicit agreement to these terms. These terms and conditions are subject to change at any time without prior notice.
