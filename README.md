
## E-TRON

Project cloned on the one already available by senisonn on the following link:

https://github.com/senisonn/E-TRON



- Armagetron-Advanced Like designed to be played on a movie room.

/---------------------------------------------------------------------------------------------------------------------------------
This project was carried out in partnership with a cinema, each player connecting via a web page and playing from a single screen *---------------------------------------------------------------------------------------------------------------------------------*/

#### Team Members
- bonsoirlina
- senisonn (Lead Dev)
- TheAxeblack
- asmaev (asmaenoufoussi)
- ryuma695



### Goal of the Game

- **Objective:** The goal is to be the last player alive.
- **Player Features:**
  - You have **3 lives**, a **trail**, and a **speed**.
- **Lose a Life By:**
  - Colliding with the window borders.
  - Colliding with another player’s trail or an obstacle.
- **Gain a Life Point If:**
  - Someone hits your trail.
- **Bonus Spawn:**
  - Every **20 seconds**, a bonus spawns on the map:
    - Trail length bonus.
    - Speed bonus.
    - +1 HP bonus.
- **Starting Advantage:**
  - Each player has **60 seconds of invincibility** at the beginning of the game.


### User Manual

If you want to play on your own computer:

- **Replace the IP Address:**
  - Replace the IP address specified in `App.java` and `App.js` with your Wi-Fi IP address.
- **Compile the Project:**
  - Use Gradle to compile the project with the command:
    ```bash
    ./gradlew shadowJar
    ```
    - [Install Gradle](https://gradle.org/install/).
- **Execute the Project:**
  - Run the compiled jar file using the command:
    ```bash
    java -jar build/libs/yourJar.jar
    ```
- **Run the Website:**
  - You will need Apache or LiveShare (VSCode) to run your website on your Wi-Fi.
- **Connecting Other Players:**
  - If someone wants to play with you, they must be on the same Wi-Fi and go to:
    ```
    http://yourIpAddress:yourPort/yourFilePath/index.html
    ```

Every resources in master branch !

![image](https://github.com/user-attachments/assets/32e94cb3-b5bb-421a-ba08-214a4d05dd06)
