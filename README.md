# A VAE-ry Ordinary Audio Synthesizer

## Project Overview
This project explores the use of Autoencoders and Variational Autoencoders (VAEs) for the analysis and synthesis of audio waveforms. The study investigates waveform generation, interpolation, and reconstruction quality using VAEs with a modified loss function.

## Author
**Purushotham Koduri**  
Internship Report submitted on **February 12, 2025**  
Supervisors: **Johannes Zeitler, Prof. Dr. Meinard Müller**  
International Audio Laboratories Erlangen  

## Institution
**Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU) & Fraunhofer-Institut für Integrierte Schaltungen IIS**  

---

## Contents
1. Theoretical Foundations
2. Experiments With Simple Waveforms
3. Single Note Database (SNDB)
4. Conclusion

---

## Theoretical Foundations
- Introduction to neural networks, autoencoders, and VAEs.
- Explanation of loss functions, including reconstruction loss and Kullback-Leibler (KL) divergence.
- Description of VAE architecture and the reparameterization trick.

## Experiments With Simple Waveforms
- The dataset consists of basic waveform shapes: **sine, square, triangle, and sawtooth**.
- VAEs are trained to analyze and synthesize these waveforms, balancing reconstruction quality and latent space continuity.
- Experiments include **waveform interpolation in period and shape**.
- Evaluations performed using Mean Squared Error (MSE) and Cosine Similarity.

## Single Note Database (SNDB) Experiment
- Trained VAEs on a **more complex dataset** consisting of single-note samples from **seven different instruments**.
- Investigated the ability of VAEs to **reconstruct and interpolate real-world musical sounds**.
- Results showed that **simpler waveforms (e.g., wind instruments) are easier to model than complex harmonic structures (e.g., piano, violin)**.

## Key Findings
- VAEs can generate **smooth waveform interpolations** when properly balanced between KL divergence and reconstruction loss.
- Higher **KL divergence prioritization** leads to better latent space structuring but poorer reconstructions.
- Simple artificial waveforms are easier to model compared to complex, real-world instrument sounds.

## Challenges & Future Work
- Handling **complex audio datasets** requires larger training sets and more sophisticated architectures.
- Future improvements could include **GAN-based or hybrid models** to enhance reconstruction fidelity.

## References
For an in-depth explanation, refer to the full internship report and cited references.

## Contact
For any inquiries or further discussion about this work, feel free to reach out to **Purushotham Koduri**.
