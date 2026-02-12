---
title: "Yuxuan Wu - Projects"
date: 2022-10-03T08:45:26-04:00
draft: false
---

<head>
  <meta charset="utf-8">
  <link rel="stylesheet" href="card.css" media="all">
</head>

<!-- ## FA Physics -->
<div class="card">
    <div class="card-image" style="background-image: url(fa-physics.png)"></div>
    <div class="card-content">
        <h1>Function Alignment between Perceptual and Analytic Dynamics</h1>
        <p>We study how heterogeneous predictive dynamics can be preserved and coupled through bidirectional alignment at the level of functions. We consider a setting with two representations of the same process paired in time: a high-dimensional perceptual sequence and a compact analytic state sequence, each governed by its own autoregressive dynamics. Rather than collapsing them into a unified model, we align their predictive functions using lightweight adapter modules that allow each dynamics to incorporate signals from the other during rollout. We conduct experiments on two physical prediction tasks exhibiting different functional roles of the two dynamic processes, and demonstrate that function alignment significantly improves long-horizon stability during joint rollout in both perceptual and analytic domains.</p>
        <div class="card-details">
        <div class="card-details-inner">
            <div class="read-more">
            <a class="button" href="">Paper (TBD)</a>
            </div>
        </div>
        </div>
    </div>
</div>
<br />

<!-- ## Melody Reduction -->
<div class="card">
    <div class="card-image" style="background-image: url(amra.png)"></div>
    <div class="card-content">
        <h1>Automatic Melody Reduction</h1>
        <p>Melody reduction serves not only as a tool for music analysis but also as an intermediate representation for structured music generation. Prior computational theories are not fully automatic and usually limited to the classical genre. We propose a novel and conceptually simple method for melody reduction using a graph-based representation inspired by principles from computational music theories, where the reduction process is formulated as finding the shortest path. We evaluate our algorithm on pop, folk, and classical genres, and experimental results show that the algorithm produces melody reductions that are more faithful to the original melody and more musically coherent than other common melody downsampling methods. As a downstream task, we use melody reductions to generate symbolic music variations. Experiments show that our method achieves higher quality than state-of-the-art style transfer methods.</p>
        <div class="card-details">
        <div class="card-details-inner">
            <div class="read-more">
            <a class="button" href="https://arxiv.org/pdf/2508.01571">Paper</a>&nbsp;&nbsp;&nbsp;<a class="button" href="https://auto-melody-reduction.github.io/AMRA-demo/">Website</a>
            </div>
        </div>
        </div>
    </div>
</div>
<br />

<!-- ## Variance-versus-invariance -->
<div class="card">
    <div class="card-image" style="background-image: url(v3.png)"></div>
    <div class="card-content">
        <h1>Variance Versus Invariance</h1>
        <p>We contribute an unsupervised method V3 (variance-versus-invariance) that learns disentangled content and style representations from sequences of observations. Unlike most methods that rely on domain-specific labels or knowledge, our method is based on the domain-general statistical differences between content and style --- content varies more among different fragments within a sample but maintains an invariant vocabulary across data samples, whereas style remains relatively invariant within a sample but exhibits more significant variation across different samples. V3 outperforms existing unsupervised methods in disentanglement and surpasses supervised models in out-of-distribution generalization under few-shot adaptation. Also, the learned content codebook exhibits symbolic-level interpretability, aligning machine representations closely with human knowledge.</p>
        <div class="card-details">
        <div class="card-details-inner">
            <div class="read-more">
            <a class="button" href="https://arxiv.org/abs/2407.03824">Paper</a>&nbsp;&nbsp;&nbsp;<a class="button" href="https://v3-content-style.github.io/V3-demo/">Website</a>
            </div>
        </div>
        </div>
    </div>
</div>
<br />

<!-- ## Motif Representation Learning, Master Thesis -->
<div class="card">
    <div class="card-image" style="background-image: url(motif.png)"></div>
    <div class="card-content">
        <h1>Motif-Centric Music Representation Learning</h1>
        <p>The formation of music structure heavily relies on repetitions and variations of music motifs. Understanding the manifestations and behaviors of these motifs is crucial for effective music structure analysis and high-quality automatic music composition. However, capturing music motifs' implicit nature is often challenging. In this study, we employ deep learning techniques to explore an efficacious method for learning robust representations of music motifs.</p>
        <div class="card-details">
        <div class="card-details-inner">
            <div class="read-more">
            <a class="button" href="https://arxiv.org/abs/2309.10597">Paper</a>
            </div>
        </div>
        </div>
    </div>
</div>
<br />

<!-- ## SingStyle -->
<div class="card">
    <div class="card-image" style="background-image: url(singstyle.png)"></div>
    <div class="card-content">
        <h1>SingStyle111: A Multilingual Singing Dataset with Style Transfer</h1>
        <p>Singing voice research has long lacked publicly accessible data, especially in language and style diversity. We introduce SingStyle111, a studio-quality singing dataset featuring 111 songs by eight professional singers across English, Chinese, and Italian, spanning 12.8 hours. It includes bel canto opera, Chinese folk, pop, jazz, and children's singing, with 80 songs performed in multiple styles by the same singer. All recordings are clean, dry mono tracks (44.1 kHz) from professional studios, segmented into phrases with lyrics, MIDI, scores, and phoneme alignment. Acoustic features such as Mel-Spectrogram, F0 contour, and loudness curves are also provided. SingStyle111 supports various MIR tasks, including Singing Voice Synthesis, Singing Transcription, Score Following, and Singing Style Transfer.</p>
        <div class="card-details">
        <div class="card-details-inner">
            <div class="read-more">
            <a class="button" href="https://www.cs.cmu.edu/~music/shuqid/SingStyle111__A_Multilingual_Singing_Dataset_With_Style_Transfer.pdf">Paper</a>&nbsp;&nbsp;&nbsp;<a class="button" href="https://dsqvival.github.io/singstyle111/#abus">Website</a>
            </div>
        </div>
        </div>
    </div>
</div>
<br />

<!-- ## The Jazz Tutor -->
<!-- <div class="card">
    <div class="card-image" style="background-image: url(jazztutor.jpg)"></div>
    <div class="card-content">
        <h1>The Jazz Tutor</h1>
        <p>We use generative models and careful HCI design to help improve novices' practicing experience/efficiency on jazz improvisation.</p>
        <div class="card-details">
        <div class="card-details-inner">
            <div class="read-more">
            <a class="button" href="">Building...</a>
            </div>
        </div>
        </div>
    </div>
</div>
<br /> -->

<!-- ## Expressive Performance Generation -->
<!-- <div class="card">
    <div class="card-image" style="background-image: url(performance.jpg)"></div>
    <div class="card-content">
        <h1>Expressive Performance Generation</h1>
        <p>To generate stylistic expressive performance from MIDI, we first do performance analysis on the control signal level, and then use generative models to generate control signals. In the end, we will use an instrument model to synthesize music performance.</p>
        <div class="card-details">
        <div class="card-details-inner">
            <div class="read-more">
            <a class="button" href="">Building...</a>
            </div>
        </div>
        </div>
    </div>
</div>
<br /> -->

<!-- ## Timbre Transfer with Flexible Timbre Control  -->
<div class="card">
    <div class="card-image" style="background-image: url(transplayer.png)"></div>
    <div class="card-content">
        <h1>Timbre Transfer with Flexible Timbre Control</h1>
        <p>Timbre style transfer has been an intriguing but mysterious sub-topic in music style transfer. We use a concise autoencoder model with one-hot representations of instruments as the condition, and a Diffwave model trained especially for music synthesis. The results proved that our method is able to provide one-to-one style transfer outputs comparable with the existing GAN-based method, and can transfer among multiple timbres with only one single model.</p>
        <div class="card-details">
        <div class="card-details-inner">
            <div class="read-more">
            <a class="button" href="https://ieeexplore.ieee.org/document/10096233">Paper</a>
            </div>
        </div>
        </div>
    </div>
</div>
<br />

<!-- ## A to I -->
<div class="card">
    <div class="card-image" style="background-image: url(3+i.jpg)"></div>
    <div class="card-content">
        <h1><i>A to I</i></h1>
        <div class="subtitle">For AI Song Contest 2022, with team 3+i</div>
        <p>Nowadays, AI models excel with impressive performance on various tasks that were once only considered humans-exclusive. As AI models grow more powerful, their role in co-creation expands. However, ethical concerns arise with the rise of AI: will AI models replace or be harmful to humans? In this song, we try to answer those open questions by exploring the possible roles AI models could play in the co-creation process and try to resolve the ethical concern from the perspective of AI themselves. The AI models in this song act not only as tools but also as collaborators, song and lyrics writers, performers, storytellers, and even the mentor and first-person narrator.</p>
        <div class="card-details">
        <div class="card-details-inner">
            <div class="read-more">
            <a class="button" href="https://www.aisongcontest.com/participants-2022/3i">Project Page</a>
            </div>
        </div>
        </div>
    </div>
</div>
<br />

<!-- ## Speech Anonymization  -->
<div class="card">
    <div class="card-image" style="background-image: url(deid_vc.jpg)"></div>
    <div class="card-content">
        <h1>Speech Anonymization with Pseudo Voice Conversion</h1>
        <div class="subtitle"></div>
        <p>The widespread adoption of speech-based online services raises security and privacy concerns regarding the data that they use and share. If the data were compromised, attackers could exploit user speech to bypass speaker verification systems or even impersonate users. To mitigate this, we propose DeID-VC, a speaker de-identification system that converts a real speaker to pseudo speakers, thus removing or obfuscating the speaker-dependent attributes from a spoken voice.</p>
        <div class="card-details">
        <div class="card-details-inner">
            <div class="read-more">
            <a class="button" href="https://arxiv.org/pdf/2209.04530.pdf">Paper</a>
            </div>
        </div>
        </div>
    </div>
</div>
<br />

<!-- ## Project Ming -->
<div class="card">
    <div class="card-image" style="background-image: url(project_ming.png)"></div>
    <div class="card-content">
        <h1>Project Ming</h1>
        <div class="subtitle"></div>
        <p>Project Ming is a Cycling 74 Max/MSP program that can simulate the sound ambience in ancient Chinese cities. By moving your mouse on the map and pressing different keys on the keyboard, you can experience through the colorful and realistic soundscape in ancient China. It was completed during my time at Berkeley summer school in 2019, and a variety of synthesizing techniques were adopted.</p>
        <div class="card-details">
        <div class="card-details-inner">
            <div class="read-more">
            <a class="button" href="https://drive.google.com/file/d/1RO0CLQU-DuB6bjO2We0h0V2WVvcp9bqA/view?usp=sharing">Video Demo</a>
            </div>
        </div>
        </div>
    </div>
</div>
<br />
