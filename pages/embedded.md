---
layout: page
title: Embedded Systems Lab Reports
---

 Below is the report for the final project: Tetris on STM32F429i.

### Final Project: Tetris on STM32F429i
In this project, I developed a functional Tetris game on the STM32F429i development board, demonstrating skills in embedded programming, touchscreen interfaces, and timer-based scheduling. The game includes a main menu, interactive gameplay, and a game-over screen with gameplay statistics.  

<object data="/assets/pdf/embed/finalreport.pdf" type="application/pdf" width="700px" height="700px">  
    <embed src="/assets/pdf/embed/finalreport.pdf">  
        <p>Your browser does not support PDFs. Please download the PDF to view it:  
        <a href="/assets/pdf/embed/finalreport.pdf">Download PDF</a>.  
        </p>  
    </embed>  
</object>

**Project Features:**  
- **Main Menu Screen**: Displays a "Start" button and randomized Tetris blocks.  
- **Game Screen**: Allows interaction via touchscreen for block movement and the user button for block rotation. Blocks fall at 4 squares per second.  
- **Game Over Screen**: Displays gameplay statistics, including survival time and rows cleared.  

**Technical Highlights:**  
- RNG peripheral for randomized block generation.  
- Timers for gameplay timing and block falling rates.  
- LCD touchscreen for game interaction.  
- Modular C code implementation with separate files for application logic, game mechanics, and menu management.

Check out the detailed project report for a comprehensive breakdown, challenges faced, and future improvements.

Youtube video with gameplay demonstration coming soon.