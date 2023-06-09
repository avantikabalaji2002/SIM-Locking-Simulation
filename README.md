# SIM-Locking-Simulation
T-Mobile Data Breach Case Study | Simple Sim Locking Simulation

SIM locking involves adding a PIN or password to the SIM card. This security feature requires the user to provide the correct PIN or password before the SIM card can be accessed or activated on a different device. It acts as a barrier against unauthorized SIM swaps because the attacker would need to know the PIN or password to successfully transfer the phone number.

CODE:
- The code simulates a process of locking and unlocking a SIM card and performing security checks during SIM swapping.
- It uses two simulated databases: user_database for storing user information (username, password, and OTP) and sim_database for storing SIM numbers and secret keys.
- The simulate_sim_lock function is the main function that runs the simulation. It prompts the user for their username and password, validates the credentials, sends an OTP, and validates it.
- If the OTP is validated successfully, the SIM card is unlocked, and the user is prompted to answer security questions. If the security questions are answered correctly, a SIM swap is performed by generating old and new SIM numbers and storing them in the sim_database.
- Finally, the user is given the option to freeze the new SIM with a secret key. If chosen, the SIM is locked again, and the secret key is generated and associated with the new SIM in the sim_database.

**TEAM MEMBERS**

Avantika Balaji     - CB.EN.U4CSE20309

Charitha Uppalapati - CB.EN.U4CSE20311

Kausalyaa Sri       - CB.EN.U4CSE20326

Sanjay Balaji P     - CB.EN.U4CSE20354

Sherwin Akshay J G  - CB.EN.U4CSE20358



