# 🎨 Generative Adversarial Networks (GANs) Experiments

This repository contains a comprehensive collection of **GAN-based experiments and implementations** that I explored as part of my learning journey in deep generative modeling. These Jupyter notebooks span from foundational models like **Vanilla GANs** to advanced architectures like **Wasserstein GANs**, **Conditional GANs**, and **FID evaluation techniques**.

> 💡 Whether you're a student, researcher, or enthusiast — these notebooks are designed to be intuitive, easy to run, and highly modifiable for your own explorations.

---

## 📁 Repository Structure

```bash
gan-experiments/
│
├── Vanilla_GAN.ipynb                              # Basic GAN training loop and visualization
├── DCGAN_Experiments.ipynb                        # Deep Convolutional GANs with image generation
├── conditional-GAN.ipynb                          # Conditional GAN using one-hot label embeddings
├── GAN_with_decoder_network.ipynb                 # GAN with decoder added for reconstruction loss
├── discriminator_trained_5_times_generator.ipynb  # Experiment: Training discriminator more frequently
├── generator_trained_5_times_discriminator.ipynb  # Experiment: Training generator more frequently
├── wasserstein_GAN_animals.ipynb                  # WGAN with animal image dataset
├── wasserstein_GAN_gradient_clipping.ipynb        # WGAN with weight clipping and gradient penalties
├── interpolating_latent_space.ipynb               # Smooth transitions in latent space
├── FID_calculation.ipynb                          # Frechet Inception Distance metric implementation
├── finetuning_resnet_on_imagenet.ipynb            # Fine-tuning ResNet for image quality eval
└── README.md                                      # You're here!
```
🔍 Highlights
🎛️ Core GAN Architectures
Vanilla GAN: Minimal implementation to understand adversarial training.

DCGAN: Uses convolutional layers for stable image generation.

Conditional GAN: Trains the generator and discriminator using label conditioning.

Wasserstein GANs: Experiments with both basic WGAN and improved WGAN with gradient clipping.

🧪 Experimental Ideas
GAN with Decoder: Adds a decoder to reconstruct inputs, enforcing additional structure.

Discriminator vs Generator Training Frequency: Studies the impact of unbalanced training schedules.

Latent Space Interpolation: Visualizes the continuity of learned latent spaces.

📈 Evaluation
FID Score: Implements Frechet Inception Distance to evaluate generated image quality.

ResNet Fine-tuning: Fine-tunes a ResNet classifier to improve FID calculation relevance.

🛠️ How to Use
Clone the repository:

```bash
Copy
Edit
git clone https://github.com/yourusername/gan-experiments.git
cd gan-experiments
```
Install requirements:
```
bash
Copy
Edit
pip install -r requirements.txt
```
Run the notebooks in Jupyter or Google Colab:

Open in Colab

Or locally:
```
bash
Copy
Edit
jupyter notebook
```
📚 Learn More
GANs (Goodfellow et al., 2014)

DCGAN (Radford et al., 2015)

Wasserstein GAN (Arjovsky et al., 2017)

Improved Training of Wasserstein GANs (Gulrajani et al., 2017)

Conditional GAN (Mirza & Osindero, 2014)

FID Metric (Heusel et al., 2017)

🙌 Contribution & Credits
These experiments were conducted as part of hands-on learning assignments in generative modeling. You’re welcome to fork this repo, add new experiments, or raise issues if you'd like to discuss or collaborate!

📬 Contact
Feel free to connect via:

GitHub Issues

LinkedIn

Building better GANs — one experiment at a time. 🧠









