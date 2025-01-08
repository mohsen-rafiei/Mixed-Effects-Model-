
# Mixed Effects Model Analysis Project

This project explores how to analyze repeated measures data using mixed-effects models. The dataset contains participant performance over time, along with task difficulty levels. Mixed-effects models allow us to account for both fixed effects (e.g., difficulty) and random effects (e.g., individual variability).

---

## What’s Included

1. **`mixed_effects_data.csv`**  
   - A simulated dataset of 50 participants with 5 repeated observations each.  
   - Includes:
     - **Participant_ID**: Unique identifier for each participant.
     - **Time**: Time points for repeated measures.
     - **Difficulty**: Task difficulty increasing over time.
     - **Performance**: Observed performance scores.  

2. **`mixed_effects_analysis.Rmd`**  
   - An R Markdown file demonstrating:
     - Data visualization.
     - Fitting a mixed-effects model using the `lme4` package.
     - Interpreting fixed and random effects.
     - Model diagnostics.

---

## Steps to Run the Analysis

1. **Download the Files**:  
   Clone this repository or download the files manually.

2. **Install Required R Packages**:  
   Install the necessary R libraries:  
   ```R
   install.packages(c("tidyverse", "lme4"))
   ```

3. **Open and Run the R Markdown File**:  
   Open `mixed_effects_analysis.Rmd` in RStudio. Follow the steps to visualize the data, fit the model, and interpret the results.

---

## Why Use Mixed Effects Models?

Mixed-effects models are ideal for analyzing repeated measures data. They account for:
- **Fixed Effects**: Systematic influences like increasing task difficulty.
- **Random Effects**: Individual differences, such as varying baseline performance or response to time.

This approach allows you to separate population-level effects from participant-specific variability, making it a powerful tool for behavioral and psychological research.

---

## Contribution

Have ideas or improvements? Feel free to open an issue or submit a pull request. Contributions are welcome!

---

## License

This project is licensed under the [MIT License](LICENSE). Use it, adapt it, and share it with proper attribution.

