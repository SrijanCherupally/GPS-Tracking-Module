# GPS-Tracking-Module

I am working on making a GPS-Tracking Module Project, where I want to be able to find the absolute location very precisely, along with imu data for acceleration and orientation, and barometer for altitude sensing.

I want to integrate all of these into one PCB that can work for ALL of my sensor related projects in the future, so no need to redesign. Mostly also, the main reason I wanted to make this PCB was so that I could learn how to do GPS related stuff, and get more experience with the RP2350A chip, which is very popular and powerful.

I had a lot of fun designing this PCB and learnt a lot of things along the way as well.

Here are some pictures from my progress regarding my PCB. <img width="918" height="811" alt="image" src="https://github.com/user-attachments/assets/ef2ae898-7a0b-4348-88c1-818bdfc2bc2a" />

<img width="686" height="633" alt="image" src="https://github.com/user-attachments/assets/fb1d7e75-25b0-43de-b43a-359e960bd3fe" />

<img width="668" height="688" alt="image" src="https://github.com/user-attachments/assets/3ad13ab8-2fdb-4ba4-bdc3-4f4db61b842d" />
<img width="751" height="734" alt="image" src="https://github.com/user-attachments/assets/4eeea463-a772-4f10-a200-7a006861da3f" />
<img width="743" height="758" alt="image" src="https://github.com/user-attachments/assets/53779806-fadc-4764-9963-e387348b4f32" />


## BOM

| **Item Name**       | **Purpose**                                      | **Link**                                                                                                                                                                                                                                                                                                                                                                                                                              | **Cost (USD)** | **Note**                                                                                   | **Quantity** |
|---------------------|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|--------------------------------------------------------------------------------------------|--------------|
| PCB                 | To control the motor, and get to right altitude  | Online Quotation *(Can't share)*                                                                                                                                                                                                                                                                                                                                                                                                       | 130.66         | 2 boards included due to MOQ (Minimum Order Quantity)                                      | 1            |
| GPS Module          | For location and velocity                        | [Amazon Listing](https://www.amazon.com/YELUFT-GY-NEO6MV2-Control-Support-Raspberry/dp/B0F2DKWJ4J/ref=sr_1_1_sspa?crid=35K7705MVXDT6&keywords=gps+module+for+arduino&qid=1754018281&sprefix=gps+module+for+arduin%2Caps%2C195&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)                                                                                                                 | 11.00          |                                                                                           | 1            |
| 3× 3-pin Headers    | For manual soldering to save PCB assembly costs  | Online Quotation *(Can't share)*                                                                                                                                                                                                                                                                                                                                                                                                       | 10.00          | Cheaper than having JLCPCB wave-solder them                                                 | 1            |

#Total Cost - 151.66
