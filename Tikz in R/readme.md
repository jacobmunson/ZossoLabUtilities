### Tikz in R

- This folder contains a brief walkthrough for using tikz in R/RStudio
- A quality walkthrough can be found here: 
    - https://iltabiai.github.io/tips/latex/2015/09/15/latex-tikzdevice-r.html
- Briefly, 
    1. We want to output tikz files from R graphics
        - For tikz, we'll need the "tikzDevice" package
        - For graphics, we can use "ggplot2" 
            - Extending ggplot graphics, such as with ggarrange() via "ggpubr" also works directly
    2. Produce graphics as usual, while following instructions in the walkthrough above
        - Basically just a few lines of code
            - tikz(file = "path_to_place_you_want_graphic.tex", width = 5, height = 5)
	        - plot <- ggplot(...) + ...
		    - print(plot)
	        - dev.off()
    4. Take the tikz file that is output and put it into the appropriate folder for your other latex work (e.g., your project folder or Overleaf project)
    5. Enjoy. 
- Important note: for MiKTeX installation, "on-the-fly" package installation must be either "Always" or "Never" but not "Ask me"

