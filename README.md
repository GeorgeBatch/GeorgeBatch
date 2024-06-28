### Hi there 👋

I am a PhD Student in [Health Data Science at Oxford](https://www.bdi.ox.ac.uk/study/cdt)
supervised by [Professor Jens Rittscher](https://dartlunghealth.co.uk/team/prof-jens-rittscher/) and funded
by [Professor Fergus Gleeson](https://www.oncology.ox.ac.uk/team/fergus-gleeson).
I am focusing on applications of **Computer Vision** 👀💻 to improving diagnostics and treatment of patients with lung
cancer as part of the [DART](https://dartlunghealth.co.uk/) lung health project (
see [my role](https://dartlunghealth.co.uk/team/george-batchkala/) in the project).

**February 2024: my first main conference paper ([pre-print](https://ora.ox.ac.uk/objects/uuid:4966840e-ccef-4fbf-b5fb-6cf0376d9aaa) 📝, [code](https://github.com/GeorgeBatch/dependency-mil) 💻) got accepted
to [ISBI-2024](https://biomedicalimaging.org/2024/) conference!🚀** In
our work "Accurate Subtyping of Lung
Cancers by Modelling Class Dependencies", we (1) construct a weakly-supervised multi-label lung cancer histology dataset
from three public ([TCGA](https://www.cancer.gov/tcga),
[TCIA-CPTAC](https://wiki.cancerimagingarchive.net/display/Public/CPTAC+Imaging+Proteomics), [DHMC](https://bmirds.github.io/LungCancer/)),
and one in-house dataset [DART](https://dartlunghealth.co.uk/), (2) propose a class-dependency injection method
allowing the learning of robust bag representations suitable for multi-label problems under weakly-supervised settings.
Dataset creation, model building, and training code is available in
the [dependency-mil](https://github.com/GeorgeBatch/dependency-mil) repository.

**September 2022: my first workshop [paper](https://link.springer.com/chapter/10.1007/978-3-031-17979-2_12)
📝 ([pre-print](https://ora.ox.ac.uk/objects/uuid:160f9962-06c0-441d-a92a-b2a77c4d01c3) 📝, [code](https://github.com/GeorgeBatch/active-data-enrichment) 💻) got
published at [MICCAI 2022 CaPTion](https://caption-workshop.github.io/) workshop! 🚀** In our work "Active Data
Enrichment by Learning What to Annotate in
Digital Pathology", we (1) proposed a new comprehensive annotation protocol for lung cancer pathology, (2) proposed a
new metric for comparing how well a retrieval methods can prioritize examples from underrepresented classes, and (3)
demonstrated that annotating and adding top-runked examples into the training set results in greater improvements to the
algorithm performance than annotating and adding random
examples. Links: [published paper](https://link.springer.com/chapter/10.1007/978-3-031-17979-2_12), [open-access paper](https://ora.ox.ac.uk/objects/uuid:160f9962-06c0-441d-a92a-b2a77c4d01c3), [code](https://github.com/GeorgeBatch/active-data-enrichment).

**December 2020: my first mini-conference working notes [paper](https://ceur-ws.org/Vol-2882/paper30.pdf)
📝 ([code](https://github.com/GeorgeBatch/kvasir-seg) 💻) got published
at [MediaEval 2020 Multimedia Benchmark](https://ceur-ws.org/Vol-2882/) workshop 🚀**. In our work "Real-Time Polyp
Segmentation Using U-Net with IoU Loss"
we explored how using a combination of differentiable IoU and BCE losses affects the segmentation performance measured
by meanIoU and DiceScore when training a simple U-Net. Links: [published open-access paper](https://ceur-ws.org/Vol-2882/paper30.pdf), [code](https://github.com/GeorgeBatch/kvasir-seg).


<!---
reproducing a CVPR'21 work called "Multiple Instance Captioning: Learning Representations From Histopathology Textbooks and Articles" ([CVPR'21 link](https://openaccess.thecvf.com/content/CVPR2021/html/Gamper_Multiple_Instance_Captioning_Learning_Representations_From_Histopathology_Textbooks_and_Articles_CVPR_2021_paper.html)). I found the work interesting and I wanted to use the pre-trained visual backbone in my future research. It uses the methods described in another CVPR'21 work "VirTex: Learning Visual Representations from Textual Annotations" ([CVPR'21 link](https://openaccess.thecvf.com/content/CVPR2021/html/Desai_VirTex_Learning_Visual_Representations_From_Textual_Annotations_CVPR_2021_paper.html)) to train a ResNet visual 👀 encoder and a transformer textual 💬 decoder on the new [ARCH dataset](https://warwick.ac.uk/fac/cross_fac/tia/data/arch). You can see my work here: [GeorgeBatch/arch-pre-training](https://github.com/GeorgeBatch/arch-pre-training).
--->

----

**Public histology data sources.** If you also want to start working with histopathology images, but do not have or are
waiting
for your own data, consider starting with "Dartmouth Lung Cancer Histology
Dataset" [DHMC](https://bmirds.github.io/LungCancer/),
the "The Cancer Genome Atlas" ([TCGA](https://www.cancer.gov/tcga)), and "The Cancer Imaging
Archive" [TCIA-CPTAC](https://wiki.cancerimagingarchive.net/display/Public/CPTAC+Imaging+Proteomics).
Downloading large volumes of data is not a trivial task, so I documented my process
for [TCGA-lung-histology-download](https://github.com/GeorgeBatch/TCGA-lung-histology-download),
[TCIA-CPTAC-lung-histology-download](https://github.com/GeorgeBatch/TCIA-CPTAC-lung-histology-download).

**Public natural images sources.** Another thing you can do
if you are lacking medical data is to simulate parts of your future workflow on natural images, e.g. classifying medical
images for
presence or absence of particular patterns can be similar to classifying natural images for presence or absence of
particular objects. I used images from the [COCO dataset](https://cocodataset.org/#home). You can see my work
here: [GeorgeBatch/cocoapi](https://github.com/GeorgeBatch/cocoapi).

----

**Education**

- 🎓 Previously, I
  studied [Mathematics and Statistics at Warwick](https://warwick.ac.uk/study/undergraduate/courses/mathsstatsbsc) for
  my Bachelors and did
  my [Masters in Statistics at Oxford](http://www.stats.ox.ac.uk/study-here/taught-postgraduate/msc-in-statistical-science/).
- 🌱 Separately from my PhD program, I learnt cool **CV** and **NLP** techniques taught by
  the [Deep Learning School](https://dls.samcs.ru/) from [MIPT](https://mipt.ru/english/). Both courses are only taught
  in Russian 🇷🇺.
- 🚀 I also found the YouTube playlist
  on [Structuring Machine Learning Projects](https://www.youtube.com/playlist?list=PLkDaE6sCZn6E7jZ9sN_xHwSHOdjUxUW_b) (
  Course 3 of the Deep Learning Specialization on Coursera) extremely useful. I started watching the videos to answer
  some of the questions related to the multilabel classification project I was working on at the
  time ([GeorgeBatch/cocoapi](https://github.com/GeorgeBatch/cocoapi)). I liked the explanations and Andrew Ng's
  delivery style so much that I enrolled
  and [completed](https://www.coursera.org/account/accomplishments/specialization/4HEL4XDPPGPF)
  the [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning).

----

Here are some of the best free online resources to boost your ML/DL knowledge 🚀 I am currently doing it, while skipping
the repetitive parts ⏰

- English 🇬🇧
    - [Deep Learning](https://atcold.github.io/NYU-DLSP21/) from [NYU](https://www.nyu.edu/admissions.html)
      by [Yann LeCun](https://twitter.com/ylecun) and [Alfredo Canziani](https://twitter.com/alfcnz) (next on my list
      ⏭️)
    - [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)
      from [Stanford](https://www.stanford.edu)
    - [CS224n: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/)
      from [Stanford](https://www.stanford.edu)

- Russian 🇷🇺
    - [Deep Learning (part 1)](https://stepik.org/course/91157/syllabus) similar to CS231n ✅
    - [Deep Learning (part 2)](https://stepik.org/course/92488/syllabus) similar to CS224n ⏳

----

- 📫 How to reach me
    - LinkedIn: [george-batchkala](https://www.linkedin.com/in/george-batchkala/) 🔗
    - My page on DART: [george-batchkala](https://dartlunghealth.co.uk/team/george-batchkala/) 🔗
    - GitHub: [GeorgeBatch](https://github.com/GeorgeBatch) 🔗
    - Kaggle: [George Batchkala](https://www.kaggle.com/gbatchkala) 🔗

<!--
**GeorgeBatch/GeorgeBatch** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
