# MultiScene360 Dataset  
**A Real-World Multi-Camera Video Dataset for Generative Vision AI**  

## 📌 Overview  
The MultiScene360 Dataset is designed to advance generative vision AI by providing synchronized multi-camera footage from real-world environments.  

💡 **Key Applications**:  
✔ Video generation & view synthesis  
✔ 3D reconstruction & neural rendering  
✔ Digital human animation systems  
✔ Virtual/augmented reality development  

## 📊 Dataset Specifications (Public Version)  
| Category            | Specification                          |
|---------------------|----------------------------------------|
| Scenes              | 10 base + 3 extended scenes           |
| Scene Duration      | 10-20 seconds each                   |
| Camera Views        | 4 synchronized angles per scene      |
| Total Video Clips   | ~144                                 |
| Data Volume         | 20-30GB (1080p@30fps)               |

*Commercial version available with 200+ scenes and 6-8 camera angles*

## 🌆 Complete Scene Specification  
| ID   | Environment | Location        | Primary Action             | Special Features          |
|------|-------------|-----------------|----------------------------|---------------------------|
| S001 | Indoor      | Living Room     | Walk → Sit                 | Occlusion handling        |
| S002 | Indoor      | Kitchen         | Pour water + Open cabinet  | Fine hand motions         |
| S003 | Indoor      | Corridor        | Walk → Turn                | Depth perception         |
| S004 | Indoor      | Desk            | Type → Head turn           | Upper body motions       |
| S005 | Outdoor     | Park            | Walk → Sit (bench)         | Natural lighting         |
| S006 | Outdoor     | Street          | Walk → Stop → Phone check  | Gait variation           |
| S007 | Outdoor     | Staircase       | Ascend stairs              | Vertical movement        |
| S008 | Indoor      | Corridor        | Two people passing         | Multi-person occlusion   |
| S009 | Indoor      | Mirror          | Dressing + mirror view     | Reflection surfaces      |
| S010 | Indoor      | Empty room      | Dance movements            | Full-body dynamics       |
| S011 | Indoor      | Window          | Phone call + clothes adjust| Silhouette + semi-reflections |
| S012 | Outdoor     | Shopping street | Walking + window browsing  | Transparent surfaces + crowd |
| S013 | Indoor      | Night corridor  | Walking + light switching  | Low-light adaptation     |

## 🎥 Camera Configuration  
**Physical Setup**:  
 cam01──────cam02
    \         /
      Subject
    /         \
  cam04──────cam03

**Technical Details**:  
- **Cameras**: DJI Osmo Action 5 Pro (4 identical units)  
- **Mounting**: Tripod-stabilized at ~1.5m height  
- **Distance**: 2-3m from subject center  
- **FOV Overlap**: 20-30% between adjacent cameras  

## 🔍 Suggested Research Directions  
1. Cross-view consistency learning  
2. Novel view synthesis from sparse inputs  
3. Dynamic scene reconstruction  
4. Human motion transfer between viewpoints  

## 🚀 Access Information  
✨ **Free Public Download**: [https://maadaa.ai/multiscene360](https://maadaa.ai/multiscene360)  
💼 **Commercial Inquiries**: contact@maadaa.ai  
🎯 **Usage Rights**:  
✔ Free for academic/commercial use  
✔ No registration required  
✔ Includes basic annotations 

## About maadaa.ai
We pioneer **production-ready Generative AI solutions** specializing in multi-modal content generation and synthetic data services:  

🚀 **Core Offerings**:  
- **Multi-view Video Generation**: Turn sparse inputs into 360° dynamic scenes  
- **Scene Reconstruction as a Service**: Instant 3D environments from video inputs  
- **Synthetic Data Engine**: Custom datasets for vision models (automatically labeled)  


💡 **Why Choose Us**:  
✓ Reduce real-world data collection costs by 70%+  
✓ Generate perfectly labeled training data at scale  
✓ API-first integration for synthetic pipelines  

*"Empowering the next generation of interactive media and spatial computing"*  
 
