---
layout: paper
id: tongue-anim
categories: papers
permalink: tongue-anim
title: "Speech Driven Tongue Animation"
authors: 
    - Salvador Medina
    - Denis Tome
    - Carsten Stoll
    - Mark Tiede
    - Kevin Munhall
    - Alex Hauptmann
    - Iain Matthews
venue: IEEE/CVF Conference on Computer Vision and Pattern Recognition
venue-shorthand: CVPR
location: New Orleans, LA, USA
year: 2022
code: https://www.github.com/salmedina/SpeechDrivenTongueAnimation
data: https://drive.google.com/file/d/1AkbLsj41ftc56HNPWAI-Y26-QK4Bqbo9/view?usp=sharing
pdf: https://drive.google.com/XYZ/paper.pdf
video: /videos/tongue-anim.mp4

selected: true
type: conference
figure: /images/papers/22-tongue-anim.png
featured: true
feature-order: 1
feature-title: Speech Driven Tongue Animation
feature-description: Animating tongue and jaw from only speech signal
image: /images/featured/22-tongue-anim.png
bibtex: |-

  @inproceedings{medina2022speechtongue,
    title={Speech Driven Tongue Animation},
    author={Medina, Salvador and Tome, Denis and Stoll, Carsten and Tiede, Mark and Munhall, Kevin and Hauptmann, Alex and Matthews, Iain},
    booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    year={2022},
    organization={IEEE/CVF}
  }
---
    
Advances in speech driven animation techniques now allow creating convincing animations of virtual characters solely from audio data. While many approaches focus on facial and lip motion, they often do not provide realistic animation of the inner mouth. 
Performance or motion capture of the tongue and jaw from video alone is difficult because the inner mouth is only partially observable during speech.

In this work, we collected a large-scale speech to tongue mocap dataset that focuses on capturing tongue, jaw, and lip motion during speech . This dataset enables research on data-driven techniques for realistic inner mouth animation. We present a method that leverages recent deep-learning based audio feature representations to build a robust and generalizable speech to animation pipeline.

We find that self-supervised deep learning based audio feature encoders are robust and generalize well to unseen speakers and content. To demonstrate the practical application of our approach, we show animations on a high-quality parametric 3D face model driven by the landmarks generated from our speech-to-tongue animation method.
