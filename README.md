# computational-physics
Mercury’s precession &amp; double pendulum simulation  
This Jupyter notebook based project can give one experience in computational physics solving numerically for the dynamics of the systems.  
Four formulas describing the Keplerian orbit of a test particle around the Sun will be needed:  
i. $$r(\theta) = \frac{a(1-e^2)}{1+ecos(\theta-\theta_{E})} $$  
where $$r$$ is its radius, $$\theta$$ is its angle, $$a$$ is the semimajor axis, $$e$$ is the eccentricity, and $$\theta_E$$ is the orientation of
the ellipse; specifically, it gives the angle of closest approach to the Sun("periapse").  
ii. Its energy per unit mass is  
$$u = -\frac{GM_{s}}{2a}$$  
where $$M_{s}$$ is the Sun's mass.  
iii. Its angular momentum per unit mass is  
$$h=\sqrt{GM_{S}a(1-e^2)}$$  
iv. Its orbital period is   
$$T=2\pi (\frac{a^3}{GM_S})^{\frac{1}{2}}$$
