## Difficulty viewing large code files?

If you're having trouble viewing large code files on GitHub, you may find it helpful to download a ZIP file containing the entire repository. To do so, follow these steps:

1. Click on the green "Code" button on the repository page.
2. Select "Download ZIP" from the dropdown menu.
3. Save the ZIP file to your computer.

This can be particularly useful if you're experiencing issues with GitHub's web interface or if you need to access the repository without an internet connection. If you have any questions or concerns, please don't hesitate to contact us. 
<img width="624" alt="image" src="https://user-images.githubusercontent.com/117291117/231703905-7469ae09-6d82-4f77-ad05-fa29142ac9a8.png">
<h2 style="color: navy">Risk Profiling</h2>

<h3 style="color: darkcyan">Introduction:</h3>

<p style="color: darkgreen">In this report, we will discuss the simulation of temperature distribution, probability of error, and expected cost for a thermometer risk cost analysis. The project aims to analyze the risk involved in using a thermometer to measure the temperature of a certain object. The temperature distribution is simulated using the numpy and matplotlib libraries in Python, and the probability of error and expected cost are calculated using a set of randomly generated probabilities and costs for each temperature.</p>

<h3 style="color: darkcyan">Simulation of Temperature Distributions:</h3>

<p style="color: darkgreen">The simulation of temperature distribution involves generating a set of random normal distributions for each temperature between 0 and 39. The mean of the normal distribution is set to the temperature value, and the standard deviation is randomly generated between 0.2 and 0.4. The generated data is then plotted using the matplotlib library. We plotted the distribution of 15, 30, 19, 14.5, and 9 in the graph, which is shown above. From the graph, we can observe that the temperature distributions are centered around the expected temperature values.</p>

<img width="488" alt="image" src="https://user-images.githubusercontent.com/117291117/228687587-7abd6acb-6ab8-4474-8ef1-7bbd79fb07b9.png">
<img width="488" alt="image" src="https://user-images.githubusercontent.com/117291117/228687680-ab8de013-3cdc-4357-a720-fa0ff9ceedf6.png">
<img width="488" alt="image" src="https://user-images.githubusercontent.com/117291117/228687745-19ed4368-e734-43b5-9468-08bd2a85350e.png">


<h3 style="color: darkcyan">Probability of Error:</h3>

<p style="color: darkgreen">The probability of error is calculated by comparing the simulated temperature values with the expected temperature values. A temperature measurement is considered to be an error if it deviates from the expected temperature value by more than 0.3 degrees. The probability of error is calculated for each temperature using the generated data, and a histogram is plotted using the matplotlib library. The histogram of the probability of error is shown in the graph above. From the graph, we can observe that the probability of error is highest for temperatures that are far from the expected temperature values. </p>

<img width="488" alt="image" src="https://user-images.githubusercontent.com/117291117/228687831-450a61ba-3f71-47e5-90b8-a67772b4d6fa.png">


<h3 style="color: darkcyan">Expected Cost:</h3>

<p style="color: darkgreen">The expected cost is calculated by multiplying the probability of error with the cost of error for each temperature. The cost of error is randomly generated for each temperature, and the cost varies based on the probability distribution of the temperature. The expected cost is calculated for each temperature, and the total expected cost is obtained by summing up the expected costs for all temperatures. The calculated expected cost is shown in the output.</p>

<img width="488" alt="image" src="https://user-images.githubusercontent.com/117291117/228687984-7d7315b1-8c3b-46fd-adc8-6e62c88c1fa0.png">



<h3 style="color: darkcyan">Conclusion:</h3>

<p style="color: darkgreen">In conclusion, the simulation of temperature distribution, probability of error, and expected cost for a thermometer risk cost analysis was performed using Python libraries. The generated data for the temperature distribution was used to calculate the probability of error, and the cost of error was randomly generated for each temperature. The results obtained from the simulation can be used to analyse the risk involved in using a thermometer to measure the temperature of an object. The expected cost can also be used to evaluate the cost-benefit of using a thermometer with the given set of probabilities and costs.</p>
