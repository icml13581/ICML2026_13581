# ICML 2026 Submission 13581 Rebuttal Materials

<table>
  <tr>
    <td width="48%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_noise_0.001_step_1_lr_n_1000_d_1000_h_1000_lrmax_30_100_step_5_plot.png" alt="Figure 1" width="100%" />
      <p>(a) 1-step(&rho;=0.001) </p>
    </td>
    <td width="48%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_noise_0.001_step_2_lr_n_1000_d_1000_h_1000_lrmax_30_100_step_5_plot.png" alt="Figure 2" width="100%" />
      <p>(b) 2-step(&rho;=0.001) </p>
    </td>
  </tr>
</table>

<p align="center"><em><strong>Figure 11: 3-layer NN with label noise  ξ ~ N(0, ρ) under orthogonal initialization.</strong>  Here we set η₁ + η₂ ≤ O(h²ᐟ³) with h=1000 and ρ=0.001.</em></p>

<table>
  <tr>
    <td width="48%" align="center" valign="top">
      <img src="figures/2-NN-diagonal-multicurve_rho_0.001_step_1_n_1000_d_1000_h_1000_lrmax_7000_33000_step_1000.png" alt="Figure 1" width="100%" />
      <p>(a) 1-step(&rho;=0.001) </p>
    </td>
    <td width="48%" align="center" valign="top">
      <img src="figures/2-NN-diagonal-multicurve_rho_0.001_step_2_n_1000_d_1000_h_1000_lrmax_7000_33000_step_1000.png" alt="Figure 2" width="100%" />
      <p>(b) 2-step(&rho;=0.001) </p>
    </td>
  </tr>
</table>

<p align="center"><em><strong>Figure 12: 2-layer NN with label noise  ξ ~ N(0, ρ) under orthogonal initialization.</strong> Here we set η₁ + η₂ ≤ O(h³⁄²) with h=1000 and ρ=0.001.</em></p>

<table>
  <tr>
    <td width="24%" align="center" valign="top">
      <img src="figures/4-NN-diagonal-multicurve_step_1_lr_n_1000_d_1000_h_1000_lrmax_30_50_step_2_plot.png" alt="Figure 1" width="100%" />
      <p>(a) 4-Layer 1-step </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/4-NN-diagonal-multicurve_step_2_lr_n_1000_d_1000_h_1000_lrmax_30_50_step_2_plot.png" alt="Figure 2" width="100%" />
      <p>(b) 4-Layer 2-step  </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/8-NN-diagonal-multicurve_step_1_lr_n_1000_d_1000_h_1000_lrmax_30_50_step_2_plot.png" alt="Figure 3" width="100%" />
      <p>(c) 8-Layer 1-step </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/8-NN-diagonal-multicurve_step_2_lr_n_1000_d_1000_h_1000_lrmax_30_50_step_2_plot.png" alt="Figure 4" width="100%" />
      <p>(d) 8-Layer 2-step  </p>
    </td>
  </tr>
</table>

<p align="center"><em><strong>Figure 13: 4-layer and 8-layer NN under orthogonal initialization for 1 and 2-step updates. </strong> For 4-NN, we set η₁ + η₂+  η₃  =C ≤ O(h²ᐟ³) with h=1000 and we set η₂ = η₃ = (C − η₁)/2. For 8-NN, we set η₁ + η₂+  η₃+ η₄ + η₅ + η₆ + η₇ =C ≤ O(h²ᐟ³) with h=1000 and we set η₂ = η₃ = η₄ = η₅ = η₆ = η₇ = (C − η₁)/6.</em></p>

<table>
  <tr>
    <td width="48%" align="center" valign="top">
      <img src="figures/3-NN-Nonlinear-diagonal-multicurve_step_1_lr_n_1000_d_1000_h_1000_lrmax_14_20_step_1_plot.png" alt="Figure 1" width="100%" />
      <p>(a) 1-step </p>
    </td>
    <td width="48%" align="center" valign="top">
      <img src="figures/3-NN-Nonlinear-diagonal-multicurve_step_8_lr_n_1000_d_1000_h_1000_lrmax_14_20_step_1_plot.png" alt="Figure 2" width="100%" />
      <p>(b) 8-step </p>
    </td>
  </tr>
</table>

<p align="center"><em><strong>Figure 14: 3-NN nonlinear under orthogonal initialization for 1 and 8-step updates.</strong> Here we consider student model is f(xᵢ) = (1/√h)σ(σ(xᵢᵀW₁)W₂)a, and the teacher model is yᵢ = σ(β*ᵀxᵢ), with σ being the ReLU activation.</em></p>

<table>
  <tr>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_step_2_lrmax_2_30_step_4_n_1000_d_1000_h_1000_star.png" alt="Figure 1" width="100%" />
      <p>(a)  2-step </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_step_4_lrmax_2_30_step_4_n_1000_d_1000_h_1000_star.png" alt="Figure 2" width="100%" />
      <p>(b) 4-step  </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_step_8_lrmax_2_30_step_4_n_1000_d_1000_h_1000_star.png" alt="Figure 3" width="100%" />
      <p>(c) 8-step </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_step_16_lrmax_2_30_step_4_n_1000_d_1000_h_1000_star.png" alt="Figure 4" width="100%" />
      <p>(d) 16-step  </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_step_32_lrmax_2_30_step_4_n_1000_d_1000_h_1000_star.png" alt="Figure 1" width="100%" />
      <p>(e) 32-step</p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_step_64_lrmax_2_30_step_4_n_1000_d_1000_h_1000_star.png" alt="Figure 2" width="100%" />
      <p>(f) 64-step</p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_step_128_lrmax_2_30_step_4_n_1000_d_1000_h_1000_star.png" alt="Figure 3" width="100%" />
      <p>(g) 128-step</p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_step_512_lrmax_2_30_step_4_n_1000_d_1000_h_1000_star.png" alt="Figure 4" width="100%" />
      <p>(h) 512-step</p>
    </td>
  </tr>
</table>

<p align="center"><em><strong>Figure 15: 3-layer NN  from 2-step to 512-step updates.</strong> Here we set η₁ + η₂ ≤ O(h²ᐟ³) with h=1000.</em></p>

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_step_2_lr_n_1000_d_1000_h_1000_lrmax_100_107_step_1_plot_special_first_step.png" alt="Figure 1" width="100%" />
      <p>(a) 2-step </p>
    </td>
  </tr>
</table>

<p align="center"><em><strong>Figure 16: 3-layer NN under orthogonal initialization for special 2-step update.</strong> Here we set η₁ + η₂ =C ≤ O(h²ᐟ³) with h=1000.  We set the first update step to use an asymmetric learning-rate allocation: the first layer is updated with learning rate C, while the second layer is not trained. For the second update step, we then optimize under the constraint η₁ + η₂ =C.</em></p>

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_noise_0.0_step_1_lr_n_1000_d_1000_h_1000_lrmax_100_300_step_20_plot.png" alt="Figure 1" width="100%" />
      <p>(a) 1-step </p>
    </td>
  </tr>
</table>

<p align="center"><em><strong>Figure 17: 3-layer NN under orthogonal initialization for 1-step update.</strong> We consider a larger learning-rate range than that in Figure 2 of our paper.</em></p>

<table>
  <tr>
    <td width="24%" align="center" valign="top">
      <img src="figures/2-NN-theoretical-diagonal-multicurve_step_1_n_1000_d_1000_h_1000_lrmax_27000_63000_step_2000.png" alt="Figure 1" width="100%" />
      <p>(a)  1-step(theory) </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/2-NN-diagonal-multicurve_step_1_n_1000_d_1000_h_1000_lrmax_27000_63000_step_2000.png" alt="Figure 2" width="100%" />
      <p>(b) 1-step(experiment)  </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/2-NN-theoretical-diagonal-multicurve_step_2_n_1000_d_1000_h_1000_lrmax_27000_63000_step_2000.png" alt="Figure 3" width="100%" />
      <p>(c) 2-step(theory) </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/2-NN-diagonal-multicurve_step_2_n_1000_d_1000_h_1000_lrmax_27000_63000_step_2000.png" alt="Figure 4" width="100%" />
      <p>(d) 2-step(experiment)  </p>
    </td>
  </tr>
</table>

<p align="center"><em><strong>Figure 18: 2-layer NN under orthogonal initialization for 1 and 2-step updates.</strong> Compared with Figure 1 in our paper, we additionally mark the points with η₁ = η₂ using stars.</em></p>

<table>
  <tr>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-theoretical-diagonal-multicurve_step_1_n_1000_d_1000_h_1000_lrmax_30_100_step_5.png" alt="Figure 1" width="100%" />
      <p>(a)  1-step(theory) </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_step_1_lr_n_1000_d_1000_h_1000_lrmax_30_100_step_5_plot.png" alt="Figure 2" width="100%" />
      <p>(b) 1-step(experiment)  </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-theoretical-diagonal-multicurve_step_2_n_1000_d_1000_h_1000_lrmax_30_100_step_5.png" alt="Figure 3" width="100%" />
      <p>(c) 2-step(theory) </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/3-NN-diagonal-multicurve_step_2_lr_n_1000_d_1000_h_1000_lrmax_30_100_step_5_plot.png" alt="Figure 4" width="100%" />
      <p>(d) 2-step(experiment)  </p>
    </td>
  </tr>
</table>

<p align="center"><em><strong>Figure 19:3-layer NN under orthogonal initialization for 1 and 2-step updates.</strong> Compared with Figure 2 in our paper, we additionally mark the points with η₁ = η₂ using stars.</em></p>

<table>
  <tr>
    <td width="24%" align="center" valign="top">
      <img src="figures/training_loss_lin.png" alt="Figure 1" width="100%" />
      <p>(a)  train loss(lin-lin) </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/test_loss_lin.png" alt="Figure 2" width="100%" />
      <p>(b) test loss(lin-lin)  </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/training_loss_log.png" alt="Figure 3" width="100%" />
      <p>(c) train loss(log-log) </p>
    </td>
    <td width="24%" align="center" valign="top">
      <img src="figures/test_loss_log.png" alt="Figure 4" width="100%" />
      <p>(d)  test loss(log-log)  </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="35%" align="center" valign="top">
      <img src="figures/F_norm.png" alt="Figure 1" width="100%" />
      <p>(e) Frobenius norm Gap </p>
    </td>
  </tr>
</table>

<p align="center"><em><strong>Figure 20: Insights for designing layer-wise lr scheduler </strong>.  Here, we consider W₁ ∈ R⁶⁰ˣ¹⁰⁰, W₂ ∈ R¹⁰⁰ˣ⁶⁰, and M ∈ R⁶⁰ˣ⁶⁰, with ‖W₁‖F = 1 and ‖W₂‖F = 6 at initialization. We use 100 training samples and 20 test samples, base lr=0.0001, adopt the MSE loss, and train the model using gradient descent for 200 iterations.</em></p>
