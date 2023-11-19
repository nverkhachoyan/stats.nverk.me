1. **Population vs. Sample**
   - **Population**: The entire group of individuals or instances about whom we hope to learn.
     - Population Mean: $$ \mu $$
     - Population Variance: $$ \sigma^2 = \frac{1}{N} \sum_{i=1}^{N} (x_i - \mu)^2 $$
   - **Sample**: A subset of the population, selected for study in some prescribed manner.
     - Sample Mean: $$ \bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i $$
     - Sample Variance: $$ s^2 = \frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2 $$

2. **Describing Samples**
   - **Sample Proportion**: The ratio of members of the sample with a particular characteristic to the total number in the sample.
     - Formula: $$ \hat{p} = \frac{\text{Number of individuals in the sample with the characteristic}}{\text{Total number in the sample}} $$

3. **Distribution of Sample Mean and Proportion**
   - **Central Limit Theorem (CLT)**
     - For Sample Means: $$ \bar{x} \sim N\left(\mu, \frac{\sigma^2}{n}\right) $$
     - For Proportions: $$ \hat{p} \sim N\left(p, \frac{p(1-p)}{n}\right) $$

4. **Point Estimates**
   - A single value (statistic) used to estimate a population parameter.
   - Example: Using the sample mean $$ \bar{x} $$ to estimate the population mean $$ \mu $$.

5. **Biased vs Unbiased Estimates**
   - **Unbiased Estimate**: The estimator's expected value equals the true population parameter.
     - $$ E(\hat{\theta}) = \theta $$
   - **Biased Estimate**: The estimator consistently overestimates or underestimates the parameter.
     - $$ \text{Bias}(\hat{\theta}) = E(\hat{\theta}) - \theta $$
