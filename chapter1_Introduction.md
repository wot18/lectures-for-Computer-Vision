# Computer Vision(Machine Vision) for Oversea Phd Candidate

## Chapter 1 Introduction

### **What is Computer Vision?**

Fig.1 is a simple diagram illustrating the basic principles of computer vision. It shows how computer vision works, starting with the acquisition of image or video information through sensing devices, which is then passed to an interpreter for processing and analysis, ultimately leading to an understanding and description of the scene.

Specifically:

- Image (or Video): This is the source of input data, which can be any type of digital image or video.
- Sensing Devices: These are hardware devices used to capture images or videos, such as cameras.
- Interpreter: This refers to a software program or algorithm responsible for parsing the data from the sensing devices and extracting useful information. In this example, the brain icon represents the human process of understanding and cognition; in practical applications, this could be a computer running deep learning models or other forms of artificial intelligence technology to achieve similar functions.
- Semantics: The final step involves interpreting and summarizing the raw data so that it can be understood by humans or used for further operations. In the given example, “garden,” “spring,” “bridge,” “water,” “trees,” “flowers,” and “green” are key elements or feature points identified from the image.

In summary, Fig.1 aims to illustrate how modern technology can simulate the way human eyes observe the world to perform automatic image analysis and understanding tasks.


<center> <image src='.//figures//fig1-1.jpg' ></center>

<center>Fig1 A simple diagram of computer vision</center>

 Computer Vision, as the name suggests, is a discipline that teaches computers how to 'see' the world. Under the promising prospects of machine learning, Computer Vision, along with Natural Language Processing (NLP) and Speech Recognition, stands out as one of the three major hotspots in the field of machine learning. The methods and techniques of Computer Vision overlap to some extent with many disciplines, including Artificial Intelligence, Digital Image Processing, Machine Learning, Deep Learning, Pattern Recognition, Probabilistic Graphical Models, Scientific Computing, and a series of mathematical calculations. 

<center> <image src='.\\figures\\fig1-2.jpg' ></center>

 <center>Fig. 2 Related areas with computer vision</center>

The relationship between image processing, computer vision and computer graphics is demenstrated in Fig. 3.

<center> <image src='.\\figures\\fig1-3.jpg' ></center>

 <center>Fig. 3 The relationship between image processing, computer vision and computer graphics</center>




### **The Differences between Machine Vision and Computer Vision.**

* Machine Vision focuses on the engineering application of computer vision technology, capable of automatically acquiring and analyzing specific images to control corresponding behaviors. A machine vision system is one that can automatically obtain one or more images of target objects, process, analyze, and measure various features of the acquired images, and make qualitative analyses and quantitative interpretations of the measurements, thereby gaining some understanding of the target objects and making corresponding decisions.

* The Purpose of Machine Vision: The study of machine vision aims to provide the manufacturing industry with better technical support that contributes to improving product quality and production efficiency.

* Functions of Machine Vision Include: Object localization, feature detection, defect judgment, target recognition, counting, and motion tracking.

Due to the ability of machine vision systems to rapidly acquire large amounts of information, which is easy to process automatically and integrate with design information as well as processing control information, they are widely used in modern automated production processes for condition monitoring, finished product inspection, and quality control.


* Computer Vision is an interdisciplinary field that combines techniques from image processing, pattern recognition, and artificial intelligence, focusing on the computer analysis of one or more images. Specifically, computer vision provides the theoretical foundations and algorithms for image and scene analysis that underpin machine vision, while machine vision offers sensor models, system architecture, and implementation methods for the realization of computer vision.

The purpose of studying computer vision is to bring "light" to computers based on human visual characteristics, enabling them to work in place of humans or accomplish tasks beyond human capability, thereby significantly enhancing productivity and continuously improving the quality of life.

<center> Table 1 Comparison of machine vision and computer vision</center>

| Aspects | Machine Vision | Computer Vision |
|-------|-------------------|-----------------|
| Application Field | Smart Manufacturing | Future Consumer, Service, and Other Intelligent Living Fields                 |  |
| Functional Goals  | Mainly solves repetitive tasks such as positioning, measurement, and inspection that require human eyes | Endows intelligent robots with vision to achieve recognition and judgment of external position and image information |                |
| Hardware Requirements | Higher requirements, need to select industrial cameras based on frame rate, resolution, etc., according to needs | Most do not have high requirements for cameras or cameras |                |
| Algorithm Requirements | Often focuses on improving accuracy | More complex, emphasizes the use of mathematical logic or deep learning for object calibration and recognition |                |
| Industry Maturity | Higher, with widespread application in measurement and inspection in industries such as semiconductors and packaging | Overall still in the initial exploration stage, with numerous emerging startups |                |

### **Why Computer Vision is so Hard?**

* Main difficulty is to bridge the ‘semantic gap’ to establish a mapping from pixels to semantics.

In computer vision, the 'semantic gap' refers to the disparity between pixel-level information in images and high-level semantic concepts, as shown in Fig. 4. Pixel-level information provides a detailed view of the image, while semantic-level information encompasses higher-order concepts such as object categories or actions. The existence of this gap makes it difficult for computers to accurately infer high-level semantic information from low-level pixel data. 

<center> <image src='.\\figures\\fig1-4.jpg' ></center>

<center>Fig. 4 The semantic gap in computer vision</center>



---

<image src='.\\figures\\HubelandWiesel.jpg' width='200' alt='' style="float: right;">

Dr. Hubel said: "There has been a myth that the brain cannot understand itself. 
It is compared to a man trying to lift himself by his own bootstraps. 
We feel that is nonsense. 
The brain can be studied just as the kidney can."

---

Part of the reason is that computer vision is an inverse problem, where we try to recover some unknown quantities to provide a complete solution under conditions of insufficient information. 

We must resort to physics-based and probability-based models to resolve the ambiguity of potential solutions.

<center> <image src='.\\figures\\fig1-5.jpg' > </center>
<center> <image src='.\\figures\\fig1-5-2.jpg' ></center>

<center>Fig.5 Typical human visual illusions.</center> 

In the field of computer vision, we attempt to reverse the process, which means describing the world we see from one or more images, such as shapes, lighting, and color distribution. 

It is remarkable that humans and animals can accomplish this effortlessly, whereas computer vision algorithms are prone to errors. 

People who have not worked in this field often underestimate the difficulty of the problem. 

Initially, it was believed that the cognitive aspects of intelligence (such as logical proofs and planning) were inherently more challenging than the perceptual aspects.

### **Applications of Computer Vision**

AI vision is a technology that leverages deep learning and other related techniques with computer vision to understand and interpret images or videos. 
Since the breakthrough in deep learning, AI vision has entered a phase of large-scale commercial deployment, rapidly empowering sectors such as security, broad finance, retail, healthcare, autonomous driving, broad industry, and broad agriculture.

* In the security sector, AI vision is used for static facial comparison and dynamic video analysis, including functions like identity verification and risk management. 

* In the broad finance sector, AI vision is applied to account login, facial payment, remote account opening, and other scenarios. 

* In the retail industry, AI vision can be used for product/action recognition, supply chain digitization, and display analysis/automatic checkout. 

* In the healthcare sector, AI vision can be applied to image recognition, lesion analysis, and lesion area segmentation. 
  
* In the autonomous driving sector, AI vision provides functionality for environmental perception, vehicle positioning, and map creation. 
  
* In the broad industry and broad agriculture sectors, AI vision is used for product quality inspection, patrol safety management, live identification monitoring, product information management, and agricultural process automation.

Overall, AI vision technology is gradually permeating various industries, bringing convenience and efficiency improvements to each sector.

In 2021, AI vision accounted for a significant share of China's AI market, reaching 49.6%, indicating that AI vision has become an important component of China's AI development.

It is expected that the core product market size of AI vision will show a continuous growth trend over the next few years. From 143.9 billion yuan in 2019, it is projected to grow to 673.3 billion yuan in 2026, with a Compound Annual Growth Rate (CAGR) of 17.4%.

Similarly, the scale of related industries driven by AI vision will also continue to expand. From 86.2 billion yuan in 2019, it is expected to grow to 673.3 billion yuan in 2026, with a CAGR of 16.9%.

The entire AI vision market, including both core products and related industries, is expected to grow rapidly over the next few years, reflecting the increasing application of AI vision technology in China and its expanding influence.

AI vision technology not only has significant market potential but also drives the development of related industries, contributing positively to economic growth.

Compared to other AI technologies, although AI vision currently holds a relatively smaller market share, it is expected to grow at a faster rate during the forecast period, demonstrating strong growth momentum.

In conclusion, AI vision has a broad development prospect in China and is likely to become one of the key drivers of China's economic growth.

The challenges of AI vision technology in different industries is the following:

- Security: The "14th Five-Year Plan" calls for active promotion of comprehensive intelligentized security construction, adjusting and optimizing industrial structure, and reflects the industry's transition from point-to-point distributed construction to comprehensive and structured development, intersecting with smart city construction systems.
  
- Finance: The People's Bank of China and the China Banking and Insurance Regulatory Commission's requirements for remote account opening, financial management, and agency sales behavior double recording, as well as continued stimulation of the biometric market through face scanning; entering a new stage of unified image recognition platform construction.
  
- Medical: The industry has strict approval standards and prudence characteristics. Although COVID-19 made AI medical applications enter public awareness, signals for large-scale release of AI medical imaging demand are unclear, and traditional product entry methods and decision chains have not changed.
  
- Industry, Energy & Manufacturing: High demands for product stability and durability, strict control of investment return indicators; requires early involvement in feasibility consultation and verification to meet real needs.

- Retail: Provides new technical means to help industry enterprises reduce costs, improve operational efficiency, and solve development bottlenecks; market motivation remains economic benefits; requires edge or endpoint computing power optimization.
  
- Agriculture: Current livestock farming and breeding focus on large customers, while large customers' share in planting is low; pilot projects are deployed based on investment recovery situations.

### **Research Aerea Included in Computer Vision**

In computer vision, two important research areas are **3D scene reconstruction** and **semantic information acquisition**. Both aim to enable computers to understand and interpret real-world scenes.

**3D Scene Reconstruction** refers to the process of constructing a depth-informed 3D model from 2D images. This process typically involves several steps, including feature detection, matching, disparity calculation, and ultimately, stereo reconstruction. Through this method, we can obtain a 3D model that contains important information about the shape, size, and position of objects. This technology is widely used in virtual reality, augmented reality, and robot navigation.

**Semantic Information Acquisition** involves identifying various objects in an image and their relationships. This is not just a simple pixel classification task but also includes understanding the overall structure and content of the scene. For example, in a photograph, we need to know which areas belong to buildings, which belong to roads, and which belong to the sky. Additionally, we need to understand how these elements are related—such as their positional relationships and motion states.

In the Fig.6, the results of 3D scene reconstruction using deep learning techniques are shown. The entire street scene is divided into several large regions (outlined with yellow lines), each corresponding to a specific object type. On the right, the corresponding semantic label distribution is displayed. Each small square represents a different class label, with darker colors indicating a higher probability of that class. This allows us to visually see the main elements present in the entire image and the proportion of space they occupy.

<center> <image src='.\\figures\\fig1-6.jpg' width='800'></center>

<center>Fig.6 Two main research area included in computer vision.</center> 


Fig.7 is to demenstrate industrial application efficacy curve of AI vision technology. Accorading to the timeline, it can be divided into five stages:

- 2012-2019: Basic technologies reach the level of industrial application, and typical application scenarios emerge.

- 2020-2021: Transition from image processing to video processing; accuracy in semantic perception tasks surpasses human performance; existing models are optimized for greater efficiency and to address more granular issues.

- 2022-2023: Development of low-power deep learning technologies and lightweight model design; breakthroughs in 3D object perception and visual SLAM.

- 2024-2025: Quantification, alignment, and fusion of multi-modal data; proactive visual perception and natural adaptation to complex changes in the real world.

- 2026 and beyond: True implementation of neural-symbolic learning; rapid development of self-supervised and unsupervised learning related to vision.

<center> <image src='.\\figures\\fig1-7.jpg' width='800' ></center>

<center>Fig.7 Industrial application efficacy curve of AI vision technology.</center> 

With the emergence of Transformer, which has shone brightly in the field of Natural Language Processing (NLP), being applied to the Computer Vision (CV) domain, hybrid model architectures combining Transformers with Convolutional Neural Networks (CNNs) are gradually becoming a key focus of research for visual tasks. These hybrid models aim to reduce the complexity of model structures while enhancing scalability and training efficiency.

Visual technology still needs to make breakthroughs in adapting to the three-dimensional world, overcoming the limitations of reliance on labeled data inputs, reducing computational power consumption, integrating and analyzing multi-modal information, combining with knowledge and common sense to solve high-level problems, and actively perceiving and adapting to complex changes.

"Technological homogenization" does not mean "algorithmic homogenization"; the engineering capabilities of AI vision algorithms remain the litmus test for the industrial application of technology.

### **The Developement History of Computer Vision**

Fig.8 demenstrate the development history of computer vision.

<center> <image src='.\\figures\\fig1-8.jpg' width='800' ></center>

<center>Fig.8 The development history of computer vision.</center>


The very start point of computer vision can be looked back to the 1960s, when a summer vision project is launched by the MIT Artificial Intelligence Laboratory. The project was aimed at developing a computer vision system that could recognize and track moving objects in a video. The project was led by Marvin Minsky and was one of the first attempts to apply computer vision techniques to real-world problems.

<center> <image src='.\\figures\\fig1-9.jpg' width='800' ></center>

<center>Fig.9 The summer vision project launched by MIT.</center> 

At that time, perception is thought be trivial problem compared to congnition problem. So that the method applied is quite simple, the main idea is to buld a 3D world model by accumulate varies blocks, as shown in Fig.10.

<center> <image src='.\\figures\\fig1-10.jpg' width='800' ></center>

<center>Fig.10 The world of building blocks .</center> 

Pioneer in the Field: David Marr (1945-1980), known as the father of computer vision.

The Marr Prize is a significant award in the field of computer vision, presented by the International Conference on Computer Vision (ICCV) committee. It is one of the highest honors in computer vision research.

---

<image src='.\\figures\\DavidMarr.jpg' width='200' style="float: right;">

David Marr was born on January 19, 1945. 

In his early years, he studied at the University of Cambridge, where he obtained a Master's degree in mathematics and a Ph.D. in neurophysiology. He also received rigorous training in areas such as neuroanatomy, psychology, and biochemistry. 

In the UK, he engaged in theoretical research on the neocortex, hippocampus, and particularly the cerebellum. 

In 1974, he visited the United States and, at the invitation of Professor M. Minsky, stayed at the Massachusetts Institute of Technology (MIT) to conduct research on perception and memory. 

From the perspective of computer science, he integrated mathematics, psychophysics, and neurophysiology, pioneering the theory of human visual computation, which brought about a fresh outlook on visual research. Marr passed away in Boston on November 17, 1980, at the age of 35 due to illness.

---

In Marr's computational vision theory, computer vision is divided into three levels:

1. **Computational Theory**: What is the goal of the computation? What are the known or applicable constraints for the problem?
   
2. **Representation and Algorithms**: How are inputs, outputs, and intermediate information represented? What algorithms are used to compute the desired results?
   
3. **Hardware Implementation**: How are representations and algorithms mapped onto actual hardware, whether it is a biological visual system or a specialized silicon chip? Conversely, how can the constraints of the hardware be used to guide the selection of representations and algorithms? With the increasing use of graphics chips and multi-core architectures in computer vision, this question has become particularly important once again.

Fig.11 is a demenstration of Marr's computational vision theory. Besides the three levels, Marr also proposed that the core problem of computer vision is to understand the structure of the visual world, which is the basis for the development of computer vision algorithms. Although Marr's theory has been criticized for its lack of empirical evidence, it has had a profound impact on the field of computer vision and has inspired many researchers to explore the underlying principles of human vision.

<center> <image src='.\\figures\\fig1-11.jpg' width='800' ></center>

<center>Fig.11 The process of understanding the srtucture of the visual world in Marr's theory.</center> 

After the death of David Marr, his work was continued by his students, including his son, who became a prominent figure in the field of computer vision. From then on, the timeline of computer vision can be summarized as in Fig.12.

<center> <image src='.\\figures\\fig1-12.jpg' width='800' ></center>

<center>Fig.12 The timeline of computer vision.</center>

---

<image src='.\\figures\\vision.jpg' width='200' alt='' style="float: right;">

Vision: A computational Investigation into the human representation and processing of visual information

“ Vision will be seen as a milestone in the history of the subject. 
Even if no single  one of Marr’s detailed hypotheses ultimately survives, which is unlikely, 
the questions he raises can no longer be ignored and methodology he proposes seems to be the only one that has any hope of illustrating the bewildering circuitry of the central nervous system” -----Science

---

In the 1980s, much research focused on more sophisticated mathematical methods for quantitative image and scene analysis. 

* Image pyramids began to be widely used for tasks such as image blending and coarse-to-fine correspondence searches. The concept of scale-space processing also led to continuous versions of pyramids. Wavelets started to replace or enhance standard image pyramids in some applications.

* Stereo vision, used as a quantitative cue for shape, expanded to a variety of methods from X to shape, including shape from shading, photometric stereo, texture to shape, and focus to shape.

* The search for better edge and contour detection methods was also an active area of research, including the introduction of dynamic contour trackers, such as snakes, and the introduction of models based on three-dimensional physical quantities.

* Researchers found that many stereo vision, flow, from-X-to-shape, and edge detection algorithms, when treated as variational optimization problems, could be unified or at least described within the same mathematical framework, and made more robust using regularization methods. Such problems could also be well expressed using discrete Markov Random Field (MRF) models, allowing for the use of better (global) search and optimization algorithms, such as simulated annealing. Later, online variants of MRF algorithms emerged that utilized Kalman filters to model and update uncertainties. There were also attempts to map regularization and MRF algorithms onto parallel hardware.

* The processing of 3D range data (acquisition, merging, modeling, and recognition) continued to be a very active research area throughout the decade.

A well-known theorical result is Canny edge detector, which is proposed in 1986. The following main steps is included in the algorithm:
1. Gaussian smoothing
2. Gradient computation
3. Non-maximum suppression
4. Double thresholding
5. Edge tracking by hysteresis

<center> <image src='.\\figures\\fig1-13.jpg' width='800' ></center>

<center>Fig.13 The result of applying Canny edge detector.</center> 

In the mid-1980s, geometric vision began to emerge.

<center> <image src='.\\figures\\fig1-14.jpg' width='800' ></center>

<center>Fig.14 Geometric vision began to emerge.</center> 

Another controversial theory is active vision, which is proposed in 1988. The main idea of active vision is that vision should interact with the environment. As to how to interact? Due to the lack of a thorough understanding of human visual mechanisms, a systematic theoretical framework has not been formed.

Nevertherless, the point of view of active vision can summarized as follows:

- Controlling movement can simplify visual problems.
  
- Vision is a process driven by specific tasks.

---

<image src='.\\figures\\activeVision1.jpg' width='120' alt='' style="float: right;"><image src='.\\figures\\activeVision2.jpg' width='120' alt='' style="float: right;">

Three individuals who are representative figures in the field of active vision.

J. Yiannis Aloimonos from Maryland University is associated with purposive vision and qualitative vision.

R. Bajcsy from the University of Pennsylvania is involved in active perception.

A. K. Jain from Michigan State University is linked with practicing vision

---

A great debate is caused by active vision. The closure is a special debate on the purpose of vision was organized in CVGIP: Image Understanding in july 1994. A paper, named "A Computational and EvolutionaryPerspective on the Role of Representation in Vision", writtern by Micheal J. Tarr from Yale university and Michael J. Black from Brown univeristy, critisized the active vision theory. 

However, the theory of active vision is not dead. With the development of imaging techniques and the emergence of non-invasive methods, people have gained a new understanding of how brain mechanisms work, infusing new vitality into the research on active vision. It is estimated that there will be significant progress in this area of research over the next few years.

---

**Astract**: Recently, the assumed goal of computer vision, reconstructing a representation of the scene, has been criticized as unproductive and impractical. Critics have suggested that the reconstructive approach should be supplanted by a new purposive approach that emphasizes functionality and task driven perception at the cost of general vision. In response to these arguments, we claim that the recovery paradigm central to the reconstructive approach is viable, and, moreover, provides a promising framework for understanding and modeling general purpose vision in humans and machines. An examination of the goals of vision from an evolutionary perspective and a case study involving the recovery of optic flow support this hypothesis. In particular, while we acknowledge that there are instances where the purposive approach may be appropriate, these are insufficient for implementing the wide range of visual tasks exhibited by humans (the kind of flexible vision system presumed to be an end-goal of artificial intelligence). Furthermore, there are instances, such as recent work on the estimation of optic flow, where the recovery paradigm may yield useful and robust results. Thus, contrary to certain claims, the purposive approach does not obviate the need for recovery and reconstruction of flexible representations of the world.

---

In the 1990s, while many of the aforementioned topics were still under investigation, some issues became notably more active. 

* Research on using projection invariants for recognition experienced explosive growth, evolving into a collaborative effort to address problems from motion to structure. 

* The precise measurement of color and brightness, combined with accurate radiative transfer and the physical models that form colored images, gave rise to a subfield known as "physics-based vision." 

* Optical flow methods continued to be refined. 

* Significant progress was also made in dense stereo vision correspondence algorithms, with perhaps the most substantial breakthrough being the global optimization algorithms that utilized "graph cut" methods.

* Regarding multi-view stereo vision algorithms, methods for generating 3D volumetric descriptions from binary contours, as well as approaches based on tracking and reconstructing smooth occluding contours, remain under investigation. 
  
* Tracking algorithms have seen numerous improvements, including contour tracking techniques that employ "active contours" such as snakes, particle filters, and level set methods, alongside brightness-based (direct) methods, which are often used for tracking faces and entire objects. 
  
* In the field of image segmentation, developments have led to energy minimization-based methods, minimum description length methods, normalized cuts, and mean shift techniques.

* Statistical learning methods began to gain popularity, initially applied to principal component analysis for eigenfaces in face recognition and linear dynamic systems for curve tracking. 
  
* Interactions with computer graphics increased, particularly in the interdisciplinary field of image-based modeling and rendering.

In the early 1990s, ICP was introduced by Z. Zhang in an article, named "terative Point Matching for Registration of Free-Form Curves and Surface" published in JCV in 1994. 

From then on, SLAM can be represented as a combination of SfM, 3D reconstruction, motion estimation, uncertainty estimation, and ICP. It means that computer vision has been related with robotics.

Another important result is the camera calibration method proposed by Zhang in 1998. This method is based on the use of a single checkerboard pattern and can be used to calibrate the camera parameters.

<center> <image src='.\\figures\\fig1-15.jpg' width='800' ></center>

<center>Fig.15 The camera calibration method proposed by Zhang.</center> 

Stratified Reconstruction theory is another important theoritical result in 1990s. The representatives are:

* R. Hartley, GE, USA ( currently Australia)
  
* O. Faugeras, INRIA, France
  
* M. Pollefeys, Leuven University, Belgium ( currently ETH, Zurich, Switzerland)
  
* A. Zisserman, Oxford University, UK

<center> <image src='.\\figures\\fig1-16.jpg' width='800' ></center>

<center>Fig.16 The representatives of stratified reconstruction theory.</center> 

Stratified reconstruction theory is considered as the greatest theoretical achievement since 1992. The main idea is to imply 3D reconstruction in 3 steps:

* Projective reconstruction: reconstructing the 3D structure in the projective space.

* Affine reconstruction: reconstructing the 3D structure in the affine space.

* Euclidean reconstruction: reconstructing the 3D structure in the Euclidean space.
  
<center> <image src='.\\figures\\fig1-17.jpg' width='800' ></center>

<center>Fig.17 The main idea of Stratified reconstruction.</center> 

Stratified reconstruction theory is supported by congnitive psychology experiments.

<center> <image src='.\\figures\\fig1-18.jpg' width='800' ></center>

<center>Fig.18 The priority of reconstruction.</center>

* Projective reconstruction: Reconstruction does not require information about the camera matrix or the geometry of the scene. The fundamental matrix $F$ is computed based on point correspondences between images, the camera matrices are retrieved from $F$, and then 3D points are calculated through triangulation based on the correspondences.

* Affine reconstruction: Projective reconstruction can be upgraded to affine using parallel scene lines. The affine camera matrix can be obtained from the fundamental matrix and the intrinsic matrix. The 3D points are calculated through triangulation based on the correspondences.

* Metric reconstruction: By computing the image of the absolute conic, affine reconstruction can be upgraded to metric. The information used includes the orthogonality of the directions of sets of parallel lines in the image, as well as the constraint that both images have square pixels.

<center> <image src='.\\figures\\fig1-19.jpg' width='800' ></center>

<center>Fig.19 From projective reconstruction to metric reconstruction.</center>


In the first decade of the 21st century, there was an increasing interplay between vision and graphics. 

* Many topics were introduced under the heading of image-based rendering, such as image stitching, light field acquisition and rendering, and high dynamic range (HDR) image capture through exposure bracketing, which were later rebranded as computational photography.

* Feature-based methods (often in conjunction with learning approaches) emerged in object recognition. Feature-based methods also dominated other recognition tasks, including scene recognition, panorama creation, and location recognition. While block-based interest point features tend to dominate current research, some research groups are also engaged in contour-based and region segmentation-based recognition studies.

* The development of more efficient algorithms for solving complex global optimization problems. Although this trend began with work on graph cuts, significant progress has also been made in message-passing algorithms.

* The application of sophisticated machine learning methods to computer vision problems now dominates much of the visual recognition research in the field. This trend aligns with the increasing availability of large, partially labeled datasets on the Internet, making it more feasible to learn object categories without the need for meticulous human supervision.

A fast object detection method proposed by Viola and Jones in 2001, which employs an enhanced cascade of simple feature classifiers. The left side of the image illustrates the Harr-like features used in this method, which can be selected through the AdaBoost algorithm. The right side shows the workflow of a cascade classifier, where all sub-windows undergo a series of tests (T or F), and only those that pass all tests proceed to the next processing stage. The advantage of this method is its ability to rapidly screen a large number of candidate regions, thereby enhancing the speed and accuracy of object detection.

[1] Paul Viola and Michael J. Jones, "Rapid object detection using a boosted cascade of simple features," IEEE Computer Vision and Pattern Recognition, 2001.

<center> <image src='.\\figures\\fig1-20.jpg' width='800' ></center>

<center>Fig.20 Haar-like features and cascade classifier.</center>


Different types of feature detection methods were proposed, such as:

* SIFT is a commonly used feature detection method that can extract scale-invariant features and describe them using a robust histogram descriptor. However, its drawback is that it is relatively slow.

* FAST is an efficient feature detector that can quickly detect keypoints in an image, but it lacks orientation detection capability.

* BRIEF is an efficient descriptor that can rapidly describe features, but it is highly sensitive to rotation.

<center> <image src='.\\figures\\fig1-21.jpg' width='800' ></center>

<center>Fig.21 Feature detection and matching.</center>

A new understanding about computer vision was developed in the 2000s, which is called view-base recognition. The main idea is that the core task of computer vision is not reconstruct the 3D surface of an object, but to save a series images for the object from different viewpoints, and then use these images to recognize the object. 

<center> <image src='.\\figures\\fig1-22.jpg' width='800' ></center>

<center>Fig.22 View-based recognition.</center>

In the beginning of 2010s, deep learning methods started to dominate computer vision. The main reason is that deep learning methods can automatically learn features from data, which is a major bottleneck in traditional computer vision methods.

In 2012, Alex Krizhevsky proposed a deep convolutional neural network (CNN) called AlexNet, which won the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) in 2012. This breakthrough marked the beginning of the deep learning era in computer vision.

<center> <image src='.\\figures\\fig1-23.jpg' width='800' ></center>

<center>Fig.23 The invention of AlexNet.</center>

In 2015, ResNet was proposed by Kaiming He et al. ResNet is a deep convolutional neural network that uses residual learning to solve the problem of vanishing gradients. ResNet won the ILSVRC in 2015, and its residual structure has become the backbone of many subsequent deep learning models in computer vision. 

It is the first time that artificial neural networks have surpassed human performance in image classification tasks.

<center> <image src='.\\figures\\fig1-24.jpg' width='800' ></center>

<center>Fig.24 The invention of AlexNet.</center>

Fig.25 is a comparison chart about deep learning methods and traditional machine learning methods.

<center> <image src='.\\figures\\fig1-25.jpg' width='800' ></center>

<center>Fig.25 Comparison of deep learning methods and traditional machine learning methods.</center>


Some possible reasons for the success of Deep Neural Networks (DNN) in image recognition tasks:

* The layered structure of DNNs may be fundamental to their success.
  
* Unsupervised learning techniques such as Restricted Boltzmann Machines (RBMs) may not be essential to the success of DNNs.
  
* The receptive field of a Convolutional Neural Network (CNN) is fixed while an RBM's receptive field is data-driven. Combining RBMs with DNNs results in DNNs with adaptive receptive fields, which could be another reason for their success.

* Human visual processing is also a multi-layered network processing, which supports the idea that DNNs' success comes from their multi-layered structure and hierarchical learning algorithms.

As research progresses, an increasing number of tasks are beginning to rely on deep learning techniques, due to their ability to automatically learn complex feature representations, thereby improving performance. These tasks are interconnected and influence each other, collectively forming the foundation of modern computer vision.


<center> <image src='.\\figures\\fig1-26.jpg' width='800' ></center>

<center>Fig.26 An increasing number of tasks are beginning to rely on deep learning techniques.</center>

Three foudamental factors for the success of deep learning are shown in Fig.27.

<center> <image src='.\\figures\\fig1-27.jpg' width='800' ></center>

<center>Fig.27 Three foudamental factors for the success of deep learning.</center>

The limitations of deep learning include:

1. Supervised learning requires labeled data: Deep learning typically relies on supervised learning, which means a large amount of labeled data is needed for training. Collecting and annotating data can be time-consuming and expensive, especially when dealing with certain types of data or scenarios.

2. It is essentially a mapping function: Deep learning models aim to establish a mapping relationship between inputs and outputs rather than truly understanding the underlying principles behind the data. This mapping capability might lead to poor generalization to new situations, particularly when input distributions change.

3. Lack of common sense and inability to reason: Although deep learning models excel in many tasks, they often perform poorly when faced with tasks requiring common sense and logical reasoning. They cannot apply prior knowledge to solve problems like humans do.

4. Failure to incorporate domain knowledge: Deep learning models are often black boxes that don't effectively utilize expert knowledge from specific domains. This can result in poor interpretability and robustness, limiting their use in critical applications.

While deep learning has achieved great success in various tasks, there are still inherent challenges and limitations that need further research and development to overcome.

A typical engineering approach in visual research involves the following steps:

1. Define the problem in detail and determine the constraints and technical parameters of the issue at hand.

2. Explore known effective methods, implement some of them, and evaluate their performance.

3. select the most suitable method and make necessary improvements according to the specific requirements of the problem.

To ensure the effectiveness of this process, it is crucial to have practical and feasible data: **This includes both synthetic data, which can be used to verify correctness and analyze noise sensitivity, and real-world data of the type that the system will ultimately work with.**

Three major conferences:
* International Conference on Computer Vision (ICCV) (every two years)
* European Conference on Computer Vision (ECCV) (every two years)
* Conference on Computer Vision and Pattern Recognition (CVPR) (annually)

Two major publications:
* IEEE Trans PAMI
* International Journal of Computer Vision

One important award: Marr Prize

These are significant academic events and publications in the field of computer vision where researchers often present their latest findings, and the Marr Prize recognizes outstanding contributions to the field.