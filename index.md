## Welcome to 'Bayesian deep learning for large scale environmental data modelling'

Thanks for following the QR link - some things are better viewed on screen than on paper!

###  7 days of deep-learned surface air temperature

The below animation shows the predictive mean surface air temperature by hour for one week:

<video width="540" height="720" autoplay loop muted playsinline>
  <source type="video/mp4" src="https://github.com/charliekirkwood/AI_UK_poster/blob/main/SRFC_AIR_TMPR_696k_gauss_uniform_network_86_animation_WOW_robust_v2_2020_11_06-2020_11_12.mp4?raw=true">
</video>

\
Our deep model learns detailed spatio-temporal fields by combining global location and time information from weather station observations (station sites below left) with relevant local terrain context information learned through observation-centred convolution of the digital elevation model (below right).

<p float="left">
  <img src="https://raw.githubusercontent.com/charliekirkwood/AI_UK_poster/main/UKweatherstations.png" width="270" />
  <img src="https://raw.githubusercontent.com/charliekirkwood/AI_UK_poster/main/UKelevation.png" width="270" />
</p>

While this may seem like a basic example, in fact the approach may have big implications for how we model environmental variables in the future. This is because Bayesian deep learning allows us to bring the benefits of well-calibrated statistical modelling to systems in which the processes at work are (in theory) arbitrarily complex, all in a framework that is workable for extremely large datasets.

Even for systems that are mathematically well understood, such as in meteorology, where numerical models are the mainstay, there is great interest in the potential of machine learning to improve the accuracy and utility of forecasts (for example see the recent [Machine learning for weather and climate modelling](https://royalsocietypublishing.org/toc/rsta/2021/379/2194) theme issue of Philosophical Transactions of the Royal Society A, in which I have two contributions).

For environmental disciplines that tend to work via empirical observation rather than physical modelling, for example geological and ecological mapping, machine learning brings uncontested utility for its ability to discover previously uncharacterised relationships and apply these to provide better information about the environment (for example see manuscript [a machine learning approach to geochemical mapping](https://doi.org/10.1016/j.gexplo.2016.05.003))

For more information contact Charlie Kirkwood at c.kirkwood@exeter.ac.uk
