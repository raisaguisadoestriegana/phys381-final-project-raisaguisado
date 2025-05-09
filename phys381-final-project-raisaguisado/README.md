In my proyect I'm going to talk about how radiation therapy uses ionizing radiation (X-rays, gamma rays) to kill cancer cells. I will use Beer-Lambert Law to simulate how radiation dose falls off with depth inside tissue.

I(x) = Ioe^(-mu x)
mu = depends on tissue type
 
Using Python, NumPy, Matplotlib I will
1. Fit simulated noisy data to extract the attenuation coefficient μ.
2. Perform uncertainty and chi-squared analysis.

If I have time I also want to simulate different materials (bone vs. soft tissue).
