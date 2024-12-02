As an emerging edge device aimed at consumers,
Unmanned Aerial Vehicle(UAV) has attracted significant at-
tention in the consumer electronics market, particularly for
intelligent imaging applications. However, aerial image detec-
tion tasks face two major challenges: first, there are numerous
small and overlapping objects that are difficult to identify from
the aerial perspective; Secondly, if the detection frame rate
is not high enough, missed detections may occur when the
UAV is moving quickly, which can negatively impact the user
experience. To address these challenges, this paper proposes a
novel YOLO framework, named YOLOFLY, which includes a
C4f feature extraction module and a DWcDetect head designed
for model light weighting, as well as the MPSA attention
mechanism and the ACIoU loss function, aimed at improving
detection accuracy and performance for consumer-grade UAV.
Extensive experiments on the public dataset VisDrone2019
demonstrate that YOLOFLY outperforms the latest state-
of-the-art model, YOLO11n, by 3.2% in mAP50-95, reduces
detection time by 27.2 ms, decreases the number of parameters
by 0.6M, and cuts floating-point operations by 1.8B. Finally,
testing YOLOFLY in real-world environments also yielded the
best results, including a 3.75% reduction in missed detections
at high speeds. These findings validate the superiority and
effectiveness of YOLOFLY.
##2 This is the overall architecture of YOLOFLY.
![Logo](p1.png)

![Logo](p2.png)
![Logo](p3.png)
![Logo](p4.png)
![Logo](p5.png)
![Logo](p6.png)
![Logo](p7.png)
![Logo](p8.png)
