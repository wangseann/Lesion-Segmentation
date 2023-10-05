
**Topic: Automated Segmentation Task**

**Summary**: Diabetic Retinopathy is an ever growing and problematic disease, especially with raising incidence of diabetes in some human populations. In the current state,  artificial neural networks are able to learn patterns about data and sometimes even provide novel insights to researchers and clinicians. This has been observed in https://doi.org/10.1093/pnasnexus/pgad290, where CNNs were utilized to classify Sex based on retinal images (a task not obvious to opthalmology experts) and then used to determine novel infomormation and patterns about biomarkers that were used by the model in this classification task. These novel patterns were then validated quantitatively, showing that neural network explanability can give rise to new information and scientific insights. 

**Task Description**: Given a labeled dataset of fundus images, develop a model that can return an accurate mask segmentation of retinal lesions present in the current given image. 

**Dataset Description*: 
        **Data Name**: Retinal-Lesions Dataset from Kaggle DR Detection dataset
        **Data Size**: Over 1.5K images
        **Data Format**: Not specified
        **Data Storage Size**: Not specified
        **Link**: https://github.com/WeiQijie/retinal-lesions
        **Lesion Classes**: Microaneurysm, intraretinal hemorrhage, hard exudate, cotton-wool spot, vitreous hemorrhage, preretinal hemorrhage, neovascularization.
        **Paper**: https://arxiv.org/abs/1912.11619



