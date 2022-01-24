# V-DESIRR: Very Fast Deep Embedded Single Image Reflection Removal
### B H Pawan Prasad, Green Rosh K S, Lokesh R. Boregowda, Kaushik Mitra, Sanjoy Chowdhury
#### Published at International Conference on Computer Vision (ICCV) - 2021 

## Abstract

Real world images often gets corrupted due to unwanted reflections and their removal is highly desirable. A major share of such images originate from smart phone cameras capable of very high resolution captures. Most of the existing methods either focus on restoration quality by compromising on processing speed and memory requirements or,  focus on removing reflections at very low resolutions, there by limiting their practical deploy-ability. We propose a light weight deep learning model for reflection removal using a
novel scale space architecture. Our method processes the corrupted image in two stages, a Low Scale Sub-network (LSSNet) to process the lowest scale and a Progressive Inference (PI) stage to process all the higher scales. In order to reduce the computational complexity, the sub-networks in PI stage are designed to be much shallower than LSSNet. Moreover, we employ weight sharing between various scales within the PI stage to limit the model size. This also allows our method to generalize to very high resolutions without explicit retraining. Our method is superior both qualitatively and quantitatively compared to the state of the art methods and at the same time 20× faster with 50× less number of parameters compared to the most recent state-of-the-art algorithm RAGNet. We implemented our method on an android smart phone, where a high resolution 12 MP image is restored in under 5 seconds.

## Datasets

We provide a high resolution dataset for training and benchmarking of future works. 

### Training Data

TBD

### Validation Data

TBD

### Testing Data

TBD


## Benchmarking Results

We provide top 10 methods here on the testing set.

##Citation

If you find our work useful, please cite our work.

    @InProceedings{Prasad_2021_ICCV,
    author    = {Prasad, B H Pawan and S, Green Rosh K and Boregowda, Lokesh R. and Mitra, Kaushik and Chowdhury, Sanjoy},
    title     = {V-DESIRR: Very Fast Deep Embedded Single Image Reflection Removal},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2021},
    pages     = {2390-2399}
    }
