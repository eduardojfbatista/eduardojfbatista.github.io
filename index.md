## My Portfolio

---

### Subtitle Removal with Deep Learning
<!--(/sample_page)(/pdf/sample_presentation.pdf)(https://medium.com/@eduardobatista.batista/removing-embedded-subtitles-from-gregg-arakis-three-bewildered-people-in-the-night-using-deep-429661eec998) -->

This project applies deep learning to remove hardcoded subtitles from video frames. Approximately 170,000 frames were processed using Python, TensorFlow, OpenCV, and MoviePy. The workflow included CNN-based subtitle detection, U-Net segmentation of subtitle regions, and inpainting for background reconstruction, followed by video reassembly with synchronized audio. This demonstrates proficiency in applied computer vision, deep learning, and large-scale video processing pipelines.

<img src="images/filled_clip.gif?raw=true"/>

<a href="https://github.com/eduardojfbatista/Restored-Araki-Three-Bewildered-People-In-The-Night">View code on Github</a> | 
<a href="https://medium.com/@eduardobatista.batista/removing-embedded-subtitles-from-gregg-arakis-three-bewildered-people-in-the-night-using-deep-429661eec998">See article on Medium</a>

### Stock Portfolio Allocator 
<!--(/sample_page)(/pdf/sample_presentation.pdf)(http://example.com/) -->

This project focused on financial data analysis, employing statistical modeling, deep learning, quantum computing. Utilizing the yfinance library to extract the data, I used normal and Lévy-stable distributions for statistical modeling of stock price movements, which were filtered using moving averages and Kalman filters. I employed deep learning implementations including LSTM and CNN models to try to predict the next price of the stocks (with no great success, as expected because of the efficient markets hypothesis). Quantum computing is explored through Qiskit, applying VQE and QAOA algorithms for portfolio optimization, but classical algorithms were also used for this purpose. This collection underscores my proficiency in deploying diverse technologies for advanced financial analytics, encompassing classical statistical approaches, cutting-edge quantum algorithms, and efficient filtering techniques.


<img src="images/stocks_img.png?raw=true"/>

<a href="https://github.com/eduardojfbatista/Stock-Portfolio-Allocator/">View code on Github</a>

---

### Superconductors Critical Temperature

This project revolves around predicting superconductor critical temperatures using Python, leveraging a mix of NumPy, SciPy, scikit-learn, and TensorFlow. There was applied feature engineering, such as creating new features, handling zero values, managing duplicate indices, analyzing distributions, utilizing clustering techniques for grouping materials, custom activation functions, parameter uniformization, and autoencoders for dimensionality reduction. The final model integrates power law regression and employs random forests for fitting the residuals, resulting in a RMSE of 9.712 (3rd best on <a href="https://www.kaggle.com/c/superconductivity/leaderboard">Kaggle</a> competition).


<img src="images/superconductivity_hist.png?raw=true"/>
<img src="images/superconductivity_errors.png?raw=true"/>


<a href="https://github.com/eduardojfbatista/Superconductors-Critical-Temperature">View code on Github</a>

---

### Nuclear Fusion Reactor Sensors Data Analysis

In this project, I applied data science methodologies to analyze nuclear fusion reactor sensor data. Techniques such as Dynamic Time Warping (DTW), autocorrelation analysis, and Fast Fourier Transform (FFT) were employed to uncover patterns within the time-series data. Machine learning tools, including K-means clustering and dimensionality reduction through Principal Component Analysis (PCA), t-Distributed Stochastic Neighbor Embedding (t-SNE), and Uniform Manifold Approximation and Projection (UMAP), were utilized to identify clusters and reduce high-dimensional data. Additionally, gradient analysis and Markov Transition Field (MTF) visualizations provided insights into the reactor's behavior. The project demonstrates proficiency in data science, covering signal processing, statistical analysis, machine learning, and dimensionality reduction, offering valuable insights into the dynamics of nuclear fusion reactions.

<a href="https://drive.google.com/file/d/1TXZEMbmxqT-62jdaO84i9jwJeJdaKlX7/view?usp=sharing">View report</a>

<a href="https://github.com/eduardojfbatista/Fusion-Reactor-Sensor-Data">View code on Github</a>

---

### Keith Haring GAN

In this project, a convolutional generative adversarial network (CGAN) was developed to emulate the visual style of Keith Haring's artwork. Utilizing color classification and clustering algorithms, the color profiles of a diverse collection of artworks were systematically characterized. These profiles were then used to associate latent vectors with each image, enabling the GAN to generate novel pieces reminiscent of Haring's iconic aesthetic. The code seamlessly integrates machine learning methodologies, such as Random Forest classifiers and K-means clustering, with generative modeling powered by a sophisticated GAN architecture. The project demonstrates the application of computational artistry in analyzing and generating art, offering a nuanced exploration at the intersection of art and data science.

<a href="https://github.com/eduardojfbatista/Keith-Haring-GAN">View code on Github</a>



<!--
#---
#<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
-->
