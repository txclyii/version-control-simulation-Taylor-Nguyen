# Version Control Simulation
**Issue 1:** I had no problem creating branches for the header and footer branches, but ironically enough, I had issues trying to simulate an error for merging those two branches with the main branch (Part 3, Step 3).
<br>
<br>
**Solution:** I believe I was more confused on the wording on here from the instructions: "Now, switch back to the `feature/header` branch and modify the index.html file by **changing something in the footer section** to simulate a conflict." After discussing with my peers, I have added another (faux) footer section in the `feature/header` branch. After merging, I finally got the conflict to simulate, which leads to the next issue I have faced.
<br>
<br>
**Issue 2:** The next issue I have faced was editing the conflict. After manually editing the conflict, I pressed "Accept Current Change". Because of this, it made the code in my `feature/footer` disappear. I was able to bring back the code again by basically backpedalling my steps, constantly using `git status` to see if anything looked wrong, and I've successfully solved the simulated conflict by pressing the "Accept Both Changes" Option.
<br>
After that, everything was pretty smooth sailing at this point. I was able to successfully make a pull request and added an extra line (line 16) of code in my footer through it.
<br>
<br>
My biggest takeaways after completing this assignment is just how detail-oriented you have to be while using gitbash and pushing your local repository to a remote one. Throughout my time completing it, I occasionally forgot I had to `ctrl + s` before I could even use the `git add` command, giving me an extra layer of difficulties on top of learning how to solve a conflict correctly. However, I do feel a lot more confident in my abilities to navigate around GitHub and using GitBash after this.
