# 8x8_MIMO_freq_indoor
_this repo has the experimental data sets for freq. resp. of 8x8 MIMO._

***1. Purpose of the Test:***

         - The purpose of this test is to measure the channel response of an indoor wireless

           environment over 25 MHz bandwidth in 2.1 GHz band.

         - We have also used IEEE 802.11 legacy frame in our test.

***2. Equipment:***

         - 16 USRP N210 (8 synchronized USRPs at the Tx side and 8 unsynchronized USRPs at Rx side)

         - 1 OctoClock-G CDA-2990 (to synchronize USRP by default clock rate and 1 PPS)



***3. Antenna Configuration:***

         - Shape of antenna array: We have considered two different configurations at the

           Tx and Rx nodes, namely rectangular and linear. In rectangular setup, we have 

           put the antennas at both sides in the two rows with four antenna (8 in total)

         - Antenna separation: Two cases have been considered: 5cm  between adjacent antennas

           in a array, and 15cm for separation. 



***4. Collected data:***

         - We have collected the data for 12 different placments of Tx. Rx was fixed in the blue spot.

           Information of this locations can be found in floor_plan.pdf

         - The data stored in .mat files with full name of locX_c.mat or locX_f.mat, where X denotes 

           the location index of Tx node, "_c" denotes 5 cm separation, and "_f" denotes 15 cm separation.

         - Each .mat file contains a 8x8x52 three-dimensional matrix where the first index is related to

           Rx antennas, second index is for the Tx-side antenna, and third index is related to subcarrier.



***5. Contents of each folder:***

         - \rect_12_locations: rectangular configurations over 12 different places. (24 files in total, 
            12 for each sepaaration)

         - \Linear arrays: linear configuration at locations 8 (LOS) and 13 (NLOS). (4 files in total,
              2 for each separation)
