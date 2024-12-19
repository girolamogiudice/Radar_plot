# Radar_plot
Since I received many requests, I am sharing the code to plot a radar plot with a pie chart inside.
You can see the final results in figure 2a here: https://www.mcponline.org/article/S1535-9476(24)00061-6/fulltext 
The data file should be formatted in this way:
method\tauthor\trank\pathway all tabs separated
if the rank is > 11 then it is treated as an outlier.
The annoying part is position the label on the outer circle since these can have different lenght you need to try different settings.


# Radar Plot

This repository contains the code to plot a radar plot with a pie chart inside. The project was created in response to multiple requests for this functionality.

## Description

The code generates a radar plot combined with a pie chart. It can be used to visualize data similar to the one shown in **Figure 2a** of the following article:  
[https://www.mcponline.org/article/S1535-9476(24)00061-6/fulltext](https://www.mcponline.org/article/S1535-9476(24)00061-6/fulltext)

### Data Format

The data file should be formatted as follows, with all values separated by **tabs**:
method author rank pathway

- **`rank`**: If the rank is greater than 11, it will be treated as an outlier.

### Label Positioning

Positioning the labels on the outer circle can be tricky, as the lengths of the labels may vary. You may need to experiment with different settings to achieve the desired alignment.

## Features

- Generates radar plots with embedded pie charts.
- Handles outliers based on configurable rank thresholds.
- Customizable label positions for enhanced visualization.

# Usage
Prepare your data file using the format described above.
Run the script:
python radar_plot.py your_data_file.txt
e.g.:python radar_plot.py Ochoa.txt
# Example Output
<img width="1035" alt="image" src="https://github.com/user-attachments/assets/99d6d47d-2043-4c80-83a1-8c9a24299aeb" />

