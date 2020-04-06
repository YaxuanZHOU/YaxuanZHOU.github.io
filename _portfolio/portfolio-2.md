---
title: "Endoscope and AR system for imaging of dental decay"
excerpt: "In this work, we developed an advanced endoscope system for dental decay imaging; an AR-based visualization system that can help train the dentists to use such newly developed systems; and lastly an AR-based guidance system so that dentists or general users can easily use the endoscope.<br/><img src='/images/YZ-dentAR-2.png'>"
collection: portfolio
---

Untreated dental decay is the most prevalent dental problem in the world. But there are problems of current tooth decay management. Once the decay develops to an irreversible stage, you would need to drill and fill the tooth with restorative material or even need a root canal treatment, which is expensive and destructive. Thus ideally, we should detect the early-stage decay and heal it before it’s too late. However, decay detection methods in the clinics, such as visual and tactile examination or x-ray are not reliable on early decays. And also, when dentists prescribe instructions on cleaning or medicine for a long-term therapy, there is no way to monitor the dental condition between the limited times of visits to clinics.

Due to these problems, there are advanced imaging system under development that can reliably detect early decay, for example, the optical coherence tomography which can generate the 3D volumetric scan, almost like an optical CT scan. Since these different imaging systems may have their own pros and cons, collaborative use of these system in different scenarios may be more beneficial. Also we need an assistant system for training dentists to use the newly developed imaging system. The emerging augmented reality technology can be used for this.

With the above needs in mind, we developed the dentAR system shown in the following diagram. 

<p align="center">
  <img src="/images/YZ-dentAR-1.png" title="diagram of dentAR system">
</p>

Advanced 3D imaging system such as the OCT can get the volumetric view of the tooth condition, however, the system is costly and fragile, also a good 3D scan requires expert operation and may take tens of minutes. Thus it should be used in high-resource dental clinics during an one-time and thorough examination for diagnosis of all suspicious teeth. We generate the virtual display of the 3D image in AR headset, then with the 3D scan of tooth, dentists can spot suspicious decay areas which then can be used for generating a virtual guidance for the 2D imaging of the decay. 2D imaging can quickly examine the tooth from a certain view and thus can also be used by non-expert users for monitoring of tooth decay condition.  We developed the near-infrared scanning fiber endscope (NIR SFE) which is so far  the smallest dental imaging device and it can detect dental decay under tooth layer as thick as 3mm and from multiple view angles. The small probe tip also minimizes discomfort especially for pediatric patients. The only concern here is that the user needs to image the tooth from  exactly the same view angle during the repeated imaging, which would be hard without any guidance., Thus AR-based guidance can help users localize the 2D imaging scope at the desired perspective every time. And since we used the 3D image for generating the virtual guidance, we can also display the acquired 2D image in the AR headset and registering it with the 3D image using the spatial relation between the two, which would help dentists better interpret the multi-modal data. 

<p align="center">
  <img src="/images/YZ-dentAR-2.png" title="illustration of AR-based visualization, guidance and fused 2D-3D dental images">
</p>


Reference
--------------

1. ***Zhou Y.*** et. al., Towards AR-assisted visualisation and guidance for imaging of dental decay. Healthcare Technology Letters, 6(6):243–248, 2019. [[paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6952244/)]

1.  ***Zhou Y.*** et. al., Near-infrared multispectral endoscopic imaging of deep artificial interproximal lesions in extracted teeth. Lasers in Surgery and Medicine, 51(5):459–465, 2019. [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/lsm.23065)]

1.  Lee, R., ***Zhou Y.*** et. al., Near-infrared imaging of artificial enamel caries lesions with a scanning fiber endoscope. Sensors, 19(6), 2019. [[paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6471210/pdf/sensors-19-01419.pdf)]

1. A. Rajiv, ***Y. Zhou***, J. Ridge, P. G. Reinhall, E. J. Seibel, Electromechanical model-based design and testing of fiber scanners for endoscopy, Journal of Medical Devices 12 (4), 2018 [[paper](https://asmedigitalcollection.asme.org/medicaldevices/article/366205/Electromechanical-Model-Based-Design-and-Testing)]

1. ***Y. Zhou***, R. Lee, S. Finkleman, A. Sadr, E. J. Seibel, Near-infrared endoscopic imaging of deep artificial approximal lesions in extracted teeth, SPIE Photonics West Proceeding, Lasers in Dentistry XXV 10857, 108570I, 2019 [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10857/108570I/Near-infrared-endoscopic-imaging-of-deep-artificial-approximal-lesions-in/10.1117/12.2510310.full?webSyncID=9a0ce46e-9e6e-c7a4-9dab-6a0cbad05932&sessionGUID=9ad883c9-d902-bc99-93ce-d268bead49a2)]

1. ***Y. Zhou***, R. Lee, A. Sadr, E. J. Seibel, Near-infrared dental imaging using scanning fiber endoscope, SPIE Photonics West Proceeding, Lasers in Dentistry XXIV 10473, 1047308, 2018 [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10473/1047308/Near-infrared-dental-imaging-using-scanning-fiber-endoscope/10.1117/12.2295080.full?sessionGUID=3c9d902b-c999-3ced-268b-ead49a28531a&webSyncID=46e9e6ec-7a49-dab6-a0cb-ad059329ad88&sessionGUID=3c9d902b-c999-3ced-268b-ead49a28531a&SSO=1)]

1. ***Y. Zhou***, Y. Jiang, A. S. Kim, Z. Xu, J. H. Berg, E. J. Seibel, Developing laser-based therapy monitoring of early caries in pediatric dental settings,  SPIE Photonics West Proceeding, Lasers in Dentistry XXIII 10044, 100440D, 2017 [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10044/100440D/Developing-laser-based-therapy-monitoring-of-early-caries-in-pediatric/10.1117/12.2256533.full?sessionGUID=d883c9d9-02bc-9993-ced2-68bead49a285&webSyncID=0ce46e9e-6ec7-a49d-ab6a-0cbad059329a&sessionGUID=d883c9d9-02bc-9993-ced2-68bead49a285)]



