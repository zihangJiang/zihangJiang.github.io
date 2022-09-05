---
title: "AvatarGen: a 3D Generative Model for Animatable Human Avatars"
collection: publications
permalink: /publication/2022-08-05-avatargen
excerpt: 'Introduce a novel pipeline for controllable 3D human avatar generation.'
date: 2022-08-05
venue: 'ECCV Workshop'
---
Unsupervised generation of clothed virtual humans with various appearance and animatable poses is important for creating 3D human avatars and other AR/VR applications. Existing methods are either limited to rigid object modeling, or not generative and thus unable to synthesize high-quality virtual humans and animate them. In this work, we propose AvatarGen, the first method that enables not only non-rigid human generation with diverse appearance but also full control over poses and viewpoints, while only requiring 2D images for training. Specifically, it extends the recent 3D GANs to clothed human generation by utilizing a coarse human body model as a proxy to warp the observation space into a standard avatar under a canonical space. To model non-rigid dynamics, it introduces a deformation network to learn pose-dependent deformations in the canonical space. To improve geometry quality of the generated human avatars, it leverages signed distance field as geometric representation, which allows more direct regularization from the body model on the geometry learning. Benefiting from these designs, our method can generate animatable human avatars with high-quality appearance and geometry modeling, significantly outperforming previous 3D GANs. Furthermore, it is competent for many applications, e.g., single-view reconstruction, reanimation, and text-guided synthesis. Code and pre-trained model will be available.

[Download paper here](https://arxiv.org/pdf/2208.00561.pdf)
