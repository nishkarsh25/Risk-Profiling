# Difficulty viewing large code files?

If you're having trouble viewing large code files on GitHub, you may find it helpful to download a ZIP file containing the entire repository. To do so, follow these steps:

1. Click on the green "Code" button on the repository page.
2. Select "Download ZIP" from the dropdown menu.
3. Save the ZIP file to your computer.

This can be particularly useful if you're experiencing issues with GitHub's web interface or if you need to access the repository without an internet connection. If you have any questions or concerns, please don't hesitate to contact us. 
<img width="624" alt="image" src="https://user-images.githubusercontent.com/117291117/231703905-7469ae09-6d82-4f77-ad05-fa29142ac9a8.png">
<h2 style="color: navy">Risk Profiling</h2>

<h3 style="color: darkcyan">Simulation of Temperature Distributions:</h3>

<p style="color: darkgreen">We have simulated the temperature distribution of a location by generating 80 normal distributions. Each normal distribution represents the temperature at a specific degree from 0 to 39.5 in steps of 0.5 degrees. The mean of each distribution is taken as the degree number divided by 2, while the standard deviation is a random value between 0.2 and 0.4. We have generated 10,000 samples for each distribution using the numpy random normal function. Then, we have plotted the histograms of the distributions for the degrees 15, 30, 19, 14.5, and 9 using the matplotlib library.</p>

<img width="311" alt="image" src="https://user-images.githubusercontent.com/117291117/228687587-7abd6acb-6ab8-4474-8ef1-7bbd79fb07b9.png">
<img width="314" alt="image" src="https://user-images.githubusercontent.com/117291117/228687680-ab8de013-3cdc-4357-a720-fa0ff9ceedf6.png">
<img width="314" alt="image" src="https://user-images.githubusercontent.com/117291117/228687745-19ed4368-e734-43b5-9468-08bd2a85350e.png">


<h3 style="color: darkcyan">Probability of Error:</h3>

<p style="color: darkgreen">We have calculated the probability of error in temperature measurement for each degree from 0 to 39.5. To do this, we have counted the number of samples that fall outside the range of mean ± 0.3 for each distribution. Then, we have divided this count by the total number of samples (10,000) to get the probability of error for that degree. We have stored these probabilities in a list and plotted their histogram using the matplotlib library.</p>

<img width="543" alt="image" src="https://user-images.githubusercontent.com/117291117/228687831-450a61ba-3f71-47e5-90b8-a67772b4d6fa.png">


<h3 style="color: darkcyan">Expected Cost:</h3>

<p style="color: darkgreen">We have calculated the expected cost of an error in temperature measurement for each degree from 0 to 39.5. To do this, we have used the probabilities of error and the cost of error for each degree. We have assumed that the cost of error follows a similar distribution as the probability of error for each degree. We have generated random values for the cost of error for each degree based on the range of probabilities. Then, we have calculated the expected cost by multiplying the probability of error, probability of occurrence, and the cost of error for each degree. We have stored these expected costs in a list.</p>

<img width="488" alt="image" src="https://user-images.githubusercontent.com/117291117/228687984-7d7315b1-8c3b-46fd-adc8-6e62c88c1fa0.png">

<h3 style="color: darkcyan">Results:</h3>

<p style="color: darkgreen">The simulation of temperature distribution shows that the temperature readings are centered around the expected mean for each degree with a normal distribution. The histograms show a bell-shaped curve for all degrees, except for the degrees with extreme values. The probability of error histogram shows that the probability of error increases with the distance from the expected mean. The expected cost histogram shows that the cost of error increases with the probability of error.</p>

<h3 style="color: darkcyan">Conclusion:</h3>

<p style="color: darkgreen">In this project, we have simulated the temperature distribution of a location, calculated the probability of error and expected cost, and plotted their histograms. The results show that the temperature readings are normally distributed around the expected mean for each degree. The probability of error increases with the distance from the expected mean, and the cost of error increases with the probability of error. These results can be used to evaluate the risk associated with temperature measurements and make decisions accordingly.</p>
