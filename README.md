# QTM 350 - Quiz 03

## Python Data Wrangling

In this quiz, you will practice how to manipulate data in Python using the Pandas library. You will be looking at a cool dataset of real passwords (made available from actual data breaches) sourced and compiled from [Information is Beautiful](https://informationisbeautiful.net/visualizations/top-500-passwords-visualized/) and contributed to [R's Tidy Tuesday project](https://github.com/rfordatascience/tidytuesday). These passwords are common (that is, "bad") passwords that you should avoid using! But we are going to use this dataset to practice some data wrangling skills.

The dataset is available in this repository as `passwords.csv`. The dataset has the following columns:

| Variable | Class | Description |
|:---------|:------|:------------|
| rank     | int   | Rank of password popularity |
| password | chr   | Actual text of the password |
| category | chr   | Password category |
| value    | int   | Time to crack by online guessing |
| time     | chr   | Time units (seconds, minutes, hours, days, weeks, months, years) |
| offline_crack_sec | int | Time to crack by offline cracking in seconds (e.g., using a hash table) |
| rank_alt | int   | Alternative rank of password popularity |
| strength | chr   | Password strength (10 = highest, 1 = lowest) |
| font_size | int   | Font size for word cloud visualisation |

Please fork this repository and complete the included Jupyter Notebook with your code and answers. Push your completed notebook to your forked repository and submit the repository link on Canvas.

Best of luck! 😉
