# Convolutional Neural Network for Diabetic Retinopathy Detection (Pytorch)

<div style="color:white;display:fill;border-radius:8px;
            background-color:#03112A;font-size:150%;
            letter-spacing:1.0px;background-image: url(https://i.imgur.com/GVd0La1.png)">
    <p style="padding: 8px;color:white;"><b><b><span style='color:#e61227'>1. </span></b> Diabetic Retinopathy: A Threat to Vision Health</b></p>
</div>

Diabetic retinopathy, a prevalent complication of diabetes, poses a significant threat to vision health. This condition arises when prolonged exposure to elevated blood sugar levels weakens the delicate blood vessels in the retina, the light-sensitive tissue at the back of the eye. 

Initially, the impact may be subtle, with changes occurring in the retinal blood vessels, particularly the delicate capillaries, leading to potential bleeding and fluid leakage. As the condition progresses, more severe manifestations emerge, such as the growth of abnormal blood vessels on the retina's surface. These vessels can bleed and exert traction on the retina, ultimately jeopardizing vision and potentially leading to blindness if left untreated.
![](https://static.wixstatic.com/media/d9e2f2_bdef7bf6e73342e5a065f474477d7606~mv2.jpg/v1/fill/w_708,h_625,al_c,lg_1,q_85,enc_auto/d9e2f2_bdef7bf6e73342e5a065f474477d7606~mv2.jpg)

## <b>1.1 <span style='color:#e61227'>|</span> Types of Diabetic Retinopathy</b> 


Diabetic retinopathy encompasses two main types:

1. **Non-Proliferative Diabetic Retinopathy:** Characterized by changes in retinal blood vessels and potential bleeding and fluid leakage.
2. **Proliferative Diabetic Retinopathy:** Involves the growth of abnormal blood vessels on the retina's surface, posing a significant risk to vision.

Additionally, diabetic macular edema, characterized by swelling in the macula, can further complicate the condition.


## <b>1.2 <span style='color:#e61227'>|</span> Causes and Risk Factors</b> 

The development and progression of diabetic retinopathy are influenced by various factors, including:

- **Duration of diabetes:** Longer duration of diabetes increases the risk of diabetic retinopathy.
- **Blood sugar control:** Poor blood sugar control exacerbates the condition, while better control can help mitigate its progression.
- **Blood pressure and cholesterol levels:** Uncontrolled high blood pressure and cholesterol levels increase the risk of diabetic retinopathy.
- **Lifestyle factors:** Smoking, in particular, is a major risk factor for diabetic retinopathy, along with race and pregnancy status.

## <b>1.3 <span style='color:#e61227'>|</span> Prevention and Management</b> 

Regular monitoring and management of blood sugar levels, blood pressure, and cholesterol are crucial for individuals with diabetes to mitigate the risk of diabetic retinopathy. Furthermore, timely eye examinations are essential for early detection and intervention, as early-stage diabetic retinopathy may not present noticeable symptoms.

By prioritizing proactive measures and adopting a comprehensive approach to diabetes management, individuals can safeguard their vision and mitigate the potentially devastating effects of diabetic retinopathy.

## <b>1.4 <span style='color:#e61227'>|</span> Why we Use Machine Learning for Such Case?</b> 
Diabetic Retinopathy is a common problem among people who have had diabetes for a long time. It's really important to catch it early and treat it quickly to stop people from losing their vision. But right now, doctors have to look at lots of eye pictures one by one, which takes a long time and sometimes they make mistakes. We need a tool that can help them do this job faster and more accurately. The current ways of finding and grading Diabetic Retinopathy rely on doctors' opinions and take a lot of time and effort. This can cause problems in diagnosing the disease correctly and can slow down getting treatment to people who need it. With more and more people getting diabetes and not enough eye doctors to check everyone, it's even harder to find and treat Diabetic Retinopathy in time. So, we need a new system that uses machines to do this job instead. This system would be fast and reliable, helping doctors find and grade Diabetic Retinopathy quickly and accurately. It would make sure people get the right treatment as soon as possible, which could save their vision.

## <b>1.4 <span style='color:#e61227'>|</span> Data Description</b> 
This dataset comprises numerous high-quality images of the retina captured using different imaging settings. Each image has been evaluated by a medical expert to identify the presence of Diabetic Retinopathy, and a score ranging from 0 to 4 has been assigned accordingly.
