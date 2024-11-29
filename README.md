I'm a researcher at Universitas Airlangga<br>
I'm interested in Data-Driven Dynamical Systems<br>
Ph.D. in Applied Mathematics

### Email
mohammad.ghani2013@gmail.com

### Personal Websites
<a href="https://www.linkedin.com/in/mohammad-ghani-7b8b0b302/" target="_blank">LinkedIn</a>

<a href="https://rpubs.com/mghani" target="_blank">RPubs</a>

<a href="https://sciprofiles.com/profile/mohammadghani" target="_blank">SciProfiles</a>

<a href="https://scholar.unair.ac.id/en/persons/mohammad-ghani" target="_blank">Scholar UNAIR</a>

<a href="https://scholar.google.com/citations?user=L_c7x9YAAAAJ&hl=id&authuser=3" target="_blank">Google Scholar Author ID: L_c7x9YAAAAJ</a>

<a href="https://orcid.org/0000-0003-3085-8668" target="_blank">ORCID Author ID: 0000-0003-3085-8668</a>

<a href="https://sinta.kemdikbud.go.id/authors/profile/6771231" target="_blank">SINTA Author ID: 6771231</a>

<a href="https://www.scopus.com/authid/detail.uri?authorId=57204973352" target="_blank">Scopus Author ID: 57204973352</a>

### E-Books
<a href="https://play.google.com/store/books/details?id=zlatEAAAQBAJ" target="_blank">https://play.google.com/store/books/details?id=zlatEAAAQBAJ</a>

<a href="https://play.google.com/store/books/details?id=BcUYEQAAQBAJ" target="_blank">https://play.google.com/store/books/details?id=BcUYEQAAQBAJ</a>

### Reviewers
<b>Invited Reviewer of MethodsX</b><br>
Issued by Elsevier · Oct 2024<br>

<b>Invited Reviewer of MethodsX</b><br>
Issued by Elsevier · Aug 2024<br>

<b>Invited Reviewer of Fractals</b><br>
Issued by World Scientific · May 2024<br>

<b>Invited Reviewer of MethodsX</b><br>
Issued by Elsevier · May 2024<br>

### Conferences
<a href="https://github.com/mhghani/All-Published-Papers/blob/main/638622_1_En_BookFrontmatter_OnlinePDF.pdf" target="_blank">Book Front ICATAM: October 17-18 2024</a>, <a href="https://www.atlantis-press.com/proceedings/icatam-24" target="_blank">Proceedings</a>

### Publications
<a href="https://www.sciencedirect.com/science/article/pii/S2215016124004825" target="_blank">Ocean wave prediction using Long Short-Term Memory (LSTM) and Extreme Gradient Boosting (XGBoost) in Tuban Regency for fisherman safety</a><br>
2 November 2024: Riswanda Ayu Dhiya'ulhaq, Anisya Safira, Indah Fahmiyah, <b>Mohammad Ghani</b>

<a href="https://www.atlantis-press.com/proceedings/icatam-24/126004732" target="_blank">Forecasting The Number of Foreign Tourism Visits to Indonesia using Seasonal Autoregressive Integrated Moving Average (SARIMA) and Holt-Winters Approach</a><br>
1 November 2024: Indah Fahmiyah, Lidya Septi Andini, <b>Mohammad Ghani</b>

<a href="https://www.sciencedirect.com/science/article/pii/S2215016124003194" target="_blank">Spatial impact on inflation of Java Island prediction using Autoregressive Integrated Moving Average (ARIMA) and Generalized Space-Time ARIMA (GSTARIMA)</a><br>
17 July 2024: Anisya Safira, Riswanda Ayu Dhiya'ulhaq, Indah Fahmiyah, <b>Mohammad Ghani</b>

<a href="https://www.sciencedirect.com/science/article/pii/S2588933824000189" target="_blank">Kalman filter based on a fractional discrete-time stochastic augmented CoVid-19 model</a><br>
24 April 2024: <b>Mohammad Ghani</b>, Dwi Rantini, Maryamah

### Discussions
#### Estimation of Angle of Velocities and Positions for ARM model using Extended Kalman Filter 
![EKF_ARM_Model_2](https://github.com/user-attachments/assets/f795f8e3-36cb-4df5-b97d-14b9528d063d)
<img src="https://latex.codecogs.com/svg.image?\tau_{\theta_1}=\tau_{\theta_2}=0.5*cos(t)&space;" /><br>
ARM model is shown below:<br>
<img src="https://latex.codecogs.com/svg.image?M(\theta)\ddot{\theta}+C(\theta,\dot{\theta})\dot{\theta}+B\dot{\theta}=\tau&space;" /><br>
<img src="https://latex.codecogs.com/svg.image?\theta=[\theta_1;\theta_2],\;\dot{\theta}=[\dot{\theta}_1;\dot{\theta}_2]=[\omega_1;\omega_2],\;\ddot{\theta}=[\dot{\omega}_1;\dot{\omega}_2]&space;" /><br>
<img src="https://latex.codecogs.com/svg.image?M=[\alpha+2\beta\;cos(\theta_2)\;\;\;\delta+\beta\;cos(\theta_2);\delta+\beta\;cos(\theta_2)\;\;\;\delta]&space;" /><br>

#### fminsearch VS lsqcurvefit to estimate the parameters of infection rate and recovery rate for the SIR model

<img src="https://latex.codecogs.com/svg.image?\left\{\begin{matrix}&\dot{S}=-\beta\cdot&space;S\cdot&space;I,\\&\dot{I}=\beta\cdot&space;S\cdot&space;I-\alpha\cdot&space;I,\\&\dot{R}=\alpha\cdot&space;I.\end{matrix}\right." /><br>

<b>Initial values of parameters (before estimated by fminsearch and lsqcurvefit)</b>:<br>
<img src="https://latex.codecogs.com/svg.image?\beta=1:infection\;rate&space;" /><br>
<img src="https://latex.codecogs.com/svg.image?\alpha=0.2:recovery\;rate&space;" />

![fminsearch lsqcurvefit](https://github.com/user-attachments/assets/fb20a68f-4a80-4392-b9b8-801122dc6796)

<b>Estimated parameters by fminsearch and lsqcurvefit</b>:<br>
<img src="https://latex.codecogs.com/svg.image?\beta=1.6926:infection\;rate&space;" /><br>
<img src="https://latex.codecogs.com/svg.image?\alpha=0.4485:recovery\;rate&space;" />

<b>Main part of fminsearch</b>: fminsearch(@error_sum_of_squares_fminsearch,param)<br>
<b>Main part of lsqcurvefit</b>: lsqcurvefit(@sir_rhs_lsqcurvefit,param,tspan,data)<br>
<li>param is the parameters of infection rate and recovery rate</li>
<li>tspan is time (number of data)</li><br>
The data is based on the article entitled "On parameter estimation approaches for predicting disease transmission through optimization, deep learning and statistical inference methods":<br>
data=[3;6;25;73;222;294;258;237;191;125;69;27;11;4] and [S0,I0,R0]=[760,3,0]

#### Estimation of parameters infection rate and recovery rate for the SIR model using Extended Kalman Filter

![WORKFLOW_001](https://github.com/user-attachments/assets/89371969-abdc-46a9-b697-9a3dc5e0b85b)

<img src="https://latex.codecogs.com/svg.image?\left\{\begin{matrix}&\dot{S}=-\beta\cdot&space;S\cdot&space;I,\\&\dot{I}=\beta\cdot&space;S\cdot&space;I-\alpha\cdot&space;I,\\&\dot{R}=\alpha\cdot&space;I.\end{matrix}\right." /><br>
<img src="https://latex.codecogs.com/svg.image?\beta:infection\;rate&space;" /><br>
<img src="https://latex.codecogs.com/svg.image?\alpha:recovery\;rate&space;" />

![SIR_model](https://github.com/user-attachments/assets/d1ee1a1a-14e9-4edb-930b-32619557072a)

![estimate_state_SIR](https://github.com/user-attachments/assets/e2b32176-4f4d-475c-9b12-01639872018b)

![estimate_parameter_SIR](https://github.com/user-attachments/assets/df3f49b2-a6f9-4afe-b11d-b9dad149446b)

#### Estimations of parameters for the Mass-Spring-Damper Dynamical Systems using Extended Kalman Filter (Case 1: for the estimation of mass (m) only, Case 2: for the estimations of mass (m), damping (b), and spring (k))

![WORKFLOW2_001](https://github.com/user-attachments/assets/b3de3fcc-f511-44be-9cc6-3e254c12a661)

<img src="https://latex.codecogs.com/svg.image?\left\{\begin{matrix}&\dot{x}_1=x_2,\\&\dot{x}_2=-(k/m)\cdot&space;x_1-(b/m)\cdot&space;x_2&plus;(1/m)\cdot&space;F(t).\end{matrix}\right." /><br>
<img src="https://latex.codecogs.com/svg.image?k:spring&space;" /><br>
<img src="https://latex.codecogs.com/svg.image?b:damper&space;" /><br>
<img src="https://latex.codecogs.com/svg.image?m:mass&space;" /><br>
<img src="https://latex.codecogs.com/svg.image?F:force\;and\;assumed\;to\;be\;constant&space;" />

![WhatsApp Image 2024-11-20 at 16 41 59](https://github.com/user-attachments/assets/7fb490d6-c71b-4a1b-a2fc-0cd1792ef845)

![WhatsApp Image 2024-11-20 at 16 41 48](https://github.com/user-attachments/assets/db8efbd8-8bba-4429-bd8f-d692cbc3e330)

![WhatsApp Image 2024-11-20 at 19 19 08](https://github.com/user-attachments/assets/84242c33-34e5-4822-b7bf-935ecd432659)

![WhatsApp Image 2024-11-20 at 19 19 07](https://github.com/user-attachments/assets/7213d6aa-5eec-4053-bd40-87e3ec168e72)
