# Awesome Zero-Shot Object Detection

## Contents

- [Contributing](#Contributing)
- [Datasets](#Datasets)
- [Paper List](#PaperList)
  - [2021](#2021)
  - [2020](#2020)
  - [2019](#2019)
  - [2018](#2018)
  - [2009](#2009)
- [Zero-shot Learning: a survey](#survey)

## Contributing

Please feel free to contact me via email (liqianzhong2017@ia.ac.cn) or open an issue or submit a pull request.

To add a new paper via pull request:

1. Fork the repo, edit `README.md`.

1. Put the new paper at the correct chronological position as the following format:

   ```
   - **Paper Title**. *Author(s)*. Conference, Year. [[Paper]](link) [[Code]](link) [[Website]](link)
   ```

1. Send a pull request. Ideally, I will review the request within a week.

## Datasets

- [Fashion-MNIST](https://github.com/berkandemirel/fashion-zero-shot-detection-dataset)
- [ILSVRC2017 DET](https://github.com/salman-h-khan/ZSD_Release)
- Microsoft COCO: [65/15-seen/unseen split](https://github.com/salman-h-khan/PL-ZSD_Release), [20/60, 40/40, 60/20-seen/unseen split](https://github.com/pengkaizhu/zsd_dataset)
- Pascal VOC: [16/4-seen/unseen split](https://github.com/salman-h-khan/PL-ZSD_Release), [5/15, 10/10, 15/5-seen/unseen split](https://github.com/pengkaizhu/zsd_dataset)

## <span id="PaperList">Paper List</span>

### 2021

- **Incrementally Zero-Shot Detection by an Extreme Value Analyzer.** *Z. Sixiao, F. Yanwei and H. Yanxi.* Arxiv, 2021. [[Paper]](https://arxiv.org/pdf/2103.12609) 

### 2020

- **Context-Aware Zero-Shot Recognition.** R. Luo, N. Zhang, B. Han and L. Yang. AAAI, 2020.[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/download/6841/6695) 
- **Dont Even Look Once: Synthesizing Features for Zero-Shot Detection.** *P. Zhu, H. Wang and V. Saligrama.*  CVPR, 2020. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhu_Dont_Even_Look_Once_Synthesizing_Features_for_Zero-Shot_Detection_CVPR_2020_paper.pdf) 
- **A Multi-Space Approach to Zero-Shot Object Detection.** *D. Gupta, A. Anantharaman, N. Mamgain, V. N. Balasubramanian and C. Jawahar*.  WACV, 2020. [[Paper]](https://openaccess.thecvf.com/content_WACV_2020/papers/Gupta_A_Multi-Space_Approach_to_Zero-Shot_Object_Detection_WACV_2020_paper.pdf) 
- **Synthesizing the Unseen for Zero-shot Object Detection.** *N. Hayat, M. Hayat, S. Rahman, S. Khan, S. Waqas Zamir and F. Shahbaz Khan*. ACCV, 2020. [[Paper]](https://openaccess.thecvf.com/content/ACCV2020/papers/Hayat_Synthesizing_the_Unseen_for_Zero-shot_Object_Detection_ACCV_2020_paper.pdf) [[Code]](https://github.com/nasir6/zero_shot_detection)
- **Context-Guided Super-Class Inference for Zero-Shot Detection.** *Y. Li, Y. Shao and D. Wang.* CVPR Workshops, 2020. [[Paper]](http://openaccess.thecvf.com/content_CVPRW_2020/papers/w54/Li_Context-Guided_Super-Class_Inference_for_Zero-Shot_Detection_CVPRW_2020_paper.pdf) 
- **Zero-Shot Object Detection with Attributes based Category Similarity.** *Q. Mao, C. Wang, S. Yu, Y. Zheng and Y. Li.* IEEE Transactions on Circuits and Systems II: Express Briefs, 2020. [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9043901) 
- **Improved Visual-Semantic Alignment for Zero-Shot Object Detection.** *S. Rahman, S. Khan and N. Barnes*. AAAI, 2020.  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6868/6722) [[Code]](https://github.com/salman-h-khan/PL-ZSD_Release) 
- **Any-Shot Object Detection.** *S. Rahman, S. Khan, N. Barnes and F. Shahbaz Khan.* ACCV, 2020. [[Paper]](https://openaccess.thecvf.com/content/ACCV2020/papers/Rahman_Any-Shot_Object_Detection_ACCV_2020_paper.pdf) 
- **Zero-Shot Object Detection: Joint Recognition and Localization of Novel Concepts.** *S. Rahman, S. H. Khan and F. Porikli.* IJCV, 2020.[[Paper]](https://link.springer.com/content/pdf/10.1007/s11263-020-01355-6.pdf) 
- **Learning Latent Semantic Attributes for Zero-Shot Object Detection.** *K. Wang, L. Zhang, Y. Tan, J. Zhao and S. Zhou.* ICTAI, 2020. [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9288224) 
- **Semantics-Preserving Graph Propagation for Zero-Shot Object Detection.** *C. Yan, Q. Zheng, X. Chang, M. Luo, C. Yeh and A. G. Hauptmann.* TIP, 2020. [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9153181) 
- **Zero-Shot Object Detection via Learning an Embedding from Semantic Space to Visual Space**. *L. a. W. Zhang, Xianzhi and Yao, Lina and Wu, Lin and Zheng, Feng.* IJCAI, 2020. [[Paper]](https://www.ijcai.org/Proceedings/2020/0126.pdf) 
- **GTNet: Generative Transfer Network for Zero-Shot Object Detection.** *S. Zhao, C. Gao, Y. Shao, L. Li, C. Yu, Z. Ji, et al*. AAAI, 2020. [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/download/6996/6850) 
- **Background Learnable Cascade for Zero-Shot Object Detection**. *Y. Zheng, R. Huang, C. Han, X. Huang and L. Cui*. ACCV, 2020. [[Paper]](https://openaccess.thecvf.com/content/ACCV2020/papers/Zheng_Background_Learnable_Cascade_for_Zero-Shot_Object_Detection_ACCV_2020_paper.pdf) [[Code]](https://github.com/zhengye1995/BLC)

### 2019

- **Transductive Learning for Zero-Shot Object Detection.** *S. Rahman, S. Khan and N. Barnes.* ICCV, 2019.  [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Rahman_Transductive_Learning_for_Zero-Shot_Object_Detection_ICCV_2019_paper.pdf) 
- **Zero-Shot Object Detection with Textual Descriptions.** *Z. Li, L. Yao, X. Zhang, X. Wang, S. Kanhere and H. Zhang.* AAAI, 2019. [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4891/4764) 
- **Zero-Shot Object Detection for Indoor Robots.** *A. Abdalwhab and H. Liu*. IJCNN, 2019.  [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8852423) 
- **zero-shot object detection method comparison and analysis.** *Peining Che.* Thesis, 2019. [[Paper]](https://etd.ohiolink.edu/apexprod/rws_olink/r/1501/10?clear=10&p10_accession_num=miami1567160037757546) 
- **Image Captioning with Unseen Objects.** *B. Demirel, R. G. Cinbis and N. Ikizler-Cinbis.* BMCV, 2019. [[Paper]](https://bmvc2019.org/wp-content/uploads/papers/0124-paper.pdf) 
- **Zero-Shot Detection with Transferable Object Proposal Mechanism.** *Y. Shao, Y. Li and D. Wang*. ICIP, 2019.  [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8803655) [[Code]](https://github.com/ylshaooo/keras-zero-shot-detection)
- **Zero Shot Detection.** *Zhu P, Wang H, Saligrama V.* TCSVT, 2019.  [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8803655) [[Code(Dataset)]](https://github.com/pengkaizhu/zsd_dataset) [[Code(Paper recurrence)]](https://github.com/howBiGaStorm/ZeroShot-YOLO) 

### 2018

- **Polarity Loss for Zero-shot Object Detection.** *Rahman S, Khan S, Barnes N.* arXiv. 2018. [[Paper]](https://arxiv.org/pdf/1811.08982.pdf) [[Code]](https://github.com/salman-h-khan/PL-ZSD_Release) 
- **Zero-Shot Object Detection: Learning to Simultaneously Recognize and Localize Novel Concepts.** *Rahman S, Khan S, Porikli F.* ACCV, 2018.  [[Paper]](https://link.springer.com/content/pdf/10.1007%2F978-3-030-20887-5_34.pdf) [[Code]](https://github.com/salman-h-khan/ZSD_Release) 
- **Zero-shot object detection. Proceedings of the European Conference on Computer Vision**. *Bansal A, Sikka K, Sharma G, Chellappa R, Divakaran A.* ECCV, 2018. [[Paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ankan_Bansal_Zero-Shot_Object_Detection_ECCV_2018_paper.pdf) [[Code]](https://github.com/asaaditya8/Zero-Shot-Object-Detection-Segmentation) [[Website]](http://ankan.umiacs.io/zsd.html)
- **Zero-Shot Object Detection by Hybrid Region Embedding**. *Demirel B, Gokberk Cinbis R, Ikizler-Cinbis N.* A. BMCV, 2018. [[Paper]](https://arxiv.org/pdf/1805.06157.pdf) [[Code]](https://github.com/berkandemirel/zero-shot-detection) 

### 2009

- **Learning to detect unseen object classes by between-class attribute transfer.** *C. H. Lampert, H. Nickisch and S. Harmeling.* CVPR, 2009.  [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.165.9750&rep=rep1&type=pdf)

## <span id="survey">Zero-shot Learning: a survey</span>

- **A Survey of Zero-Shot Learning: Settings, Methods, and Applications.** *Wang W, Zheng V W, Yu H, Miao C*. ACM Trans. Intell. Syst. Technol, 2019. [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3293318)

- **Zero-Shot Learning—A Comprehensive Evaluation of the Good, the Bad and the Ugly**. *Xian Y, Lampert C H, Schiele B, Akata Z.* TPAMI, 2019. [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8413121)
