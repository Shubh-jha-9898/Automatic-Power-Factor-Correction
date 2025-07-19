# Automatic-Power-Factor-Correction
Automatic Power Factor Correction (APFC) is a system used in electrical networks to improve power factor (PF) automatically by switching capacitor banks in and out based on real-time load conditions.

Add files via upload
Problem Statement:
 A textile mill in India has a peak demand of 5 MW, with an average power factor of 0.65 lagging. The mill operates 24/7, and the utility company charges a penalty for low power factor. The mill's management wants to improve the power factor to 0.95 or higher to reduce the penalty and minimize energy losses. 
Current System The mill's electrical distribution system consists of: 

*33 kV supply: The mill receives power from the utility company at 33 kV. 
*Transformers: Two 5 MVA, 33/6.6 kV transformers step down the voltage to 6.6 kV. 
*Distribution board: A 6.6 kV distribution board supplies power to various loads, including motors, lighting, and heating systems efficiently and effectively.


*Calculation of Required Capacitor Bank Rating:
The goal is to improve the power factor (PF) from 0.65 lagging to 0.95 lagging.

Given:
•	Active power (P) = 5 MW = 5000 kW
•	Initial PF (cosφ₁) = 0.65 → φ₁ = 49.46°, tanφ₁ = 1.169
•	Desired PF (cosφ₂) = 0.95 → φ₂ = 18.19°, tanφ₂ = 0.329

*Reactive Power Calculation:
•	Initial reactive power (Q₁) = P × tanφ₁ = 5000 × 1.169 = 5845 kVAR
•	Desired reactive power (Q₂) = P × tanφ₂ = 5000 × 0.329 = 1645 kVAR
•	Required capacitive kVAR (Qc) = Q₁ - Q₂ = 5845 - 1645 = 4200 kVAR

Existing Capacitor Bank:
•	Additional kVAR needed: 4200 

*Recommendation:
Install a new capacitor bank of 4200 kVAR at the 6.6 kV bus.
