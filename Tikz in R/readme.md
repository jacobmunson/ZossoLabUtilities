### Tikz in R

- This folder contains a brief walkthrough for using tikz in R/RStudio
- A quality walkthrough can be found here: 
    - https://iltabiai.github.io/tips/latex/2015/09/15/latex-tikzdevice-r.html
- Briefly, 
        1. We want to output tikz files from R graphics
                a. For tikz, we'll need the "tikzDevice" package
                b. For graphics, we can use "ggplot2" 
                        i. Extending ggplot graphics, such as with ggarrange() via "ggpubr" also works directly
        2. Produce graphics as usual, while following instructions in the walkthrough above
        3. Take the tikz files that is output and put it into the appropriate folder for your other latex work (e.g., your project folder or Overleaf project)
        4. Enjoy. 
- Important note: for MiKTeX installation, "on-the-fly" package installation much be either "Always" or "Never" but not "Ask me"
