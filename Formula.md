# Formulas of ITG in kappa plasma
- Drift dispersion relation for kappa plasma
$$ \varepsilon = 1 + \frac{1}{k^2 \lambda_{De}^2} (1+K_e)+\frac{1}{k^2 \lambda_{Di}^2} (1+K_{1}+K_{2}) =0$$
where
$$ K_{e} = \int_0^\infty db_e G_1(b_e) \zeta_e \sqrt{b_e}Z(\zeta_e\sqrt{b_e})\Lambda_0\left(\frac{k_y^2\rho_e^2}{b_e}\right)$$
$$ K_{1} = \int_0^\infty db_i \left[G_1(b_i) \zeta_i - G_2(b_i) \zeta_{ni}+G_2(b_i) \frac{\zeta_{Ti}}{2}\right] \sqrt{b_i}Z(\zeta_i\sqrt{b_i})\Lambda_0\left(\frac{k_y^2\rho_i^2}{b_i}\right)$$
$$ K_{2} = \int_0^\infty db_i G_2(b_i) \zeta_{Ti} \left\{
\frac{\zeta_i b_i}{2}Z'(\zeta_i\sqrt{b_i})\Lambda_0\left(\frac{k_y^2\rho_i^2}{b_i}\right)-Z(\zeta_i \sqrt{b_i})\frac{k_y^2\rho_i^2}{\sqrt{b_i}}\left[\Lambda_1\left(\frac{k_y^2\rho_i^2}{b_i}\right)-\Lambda_0\left(\frac{k_y^2\rho_i^2}{b_i}\right)\right]
\right\} $$
- Plot dispersion $\omega/\Omega_i$ vs $k_y\rho_i$ with independent parameters $m_i/m_e$, $v_e/v_i$, $\rho_i/L_T$, $\rho_i/L_N$, $\omega_{pi}/\Omega_i$, $k_z\rho_i$
$$\zeta_i = \frac{\omega}{\sqrt{2}k_zv_i} = \frac{\omega/\Omega_i}{\sqrt{2}k_z\rho_i}$$
$$\zeta_{ni} = \frac{k_yv_n}{\sqrt{2}k_zv_i} = \frac{1}{\sqrt{2}} \frac{v_n}{v_i} \frac{k_y}{k_z} = \frac{1}{\sqrt{2}} \frac{\rho_i}{L_N} \frac{k_y}{k_z}\frac{\kappa_i}{\kappa_i-1.5}$$
$$\zeta_{Ti} = \frac{k_yv_T}{\sqrt{2}k_zv_i} = \frac{1}{\sqrt{2}} \frac{v_T}{v_i} \frac{k_y}{k_z}  = \frac{1}{\sqrt{2}} \frac{\rho_i}{L_T} \frac{k_y}{k_z}\frac{\kappa_i}{\kappa_i-1.5}$$

$$\frac{\rho_e}{\rho_i} = \frac{v_{e}}{v_{i}} \frac{m_e}{m_i} $$
$$\lambda_{Di} = \sqrt{\frac{\kappa_i}{\kappa_i-1/2}\frac{m_i v_i^2}{n_i q_i^2}} = \frac{\rho_i\Omega_i}{\omega_{pi}} \sqrt{\frac{\kappa_i}{\kappa_i-1/2}}$$
$$\lambda_{De} = \lambda_{Di} \frac{v_{e}}{v_{i}} \sqrt{\frac{m_e}{m_i}}\sqrt{\frac{\kappa_i-1/2}{\kappa_i}}\sqrt{\frac{\kappa_e}{\kappa_e-1/2}}$$
- Theoretical appromaxtion
$$ \frac{\omega}{\Omega_i} = \left(\frac{1}{2}+i\frac{\sqrt{3}}{2}\right)\left|\frac{\omega_{Ti}(k_z c_s)^2}{\Omega_i^3}\right|^{1/3} = \left(\frac{1}{2}+i\frac{\sqrt{3}}{2}\right) \left|\frac{v_T}{v_i} k_y\rho_i (k_z\rho_i)^2 \frac{m_e v_e^2}{m_i v_i^2}\frac{\kappa_e}{\kappa_e-1/2}\right|^{1/3}$$