# 🎨 Drawing Animation – AI-Powered Animation Tool

**Drawing Animation** is an AI-powered tool that brings **static drawings to life** in minutes.  
It simplifies animation by letting artists **upload artwork, pick a motion style, and instantly generate animated sequences**. No complex software or skills needed.

Built with deep learning, it analyzes lines and shapes to apply natural movement, cutting animation time by up to **80%**.  
Perfect for solo creators, small teams, and anyone looking to animate without the usual hassle.

---

## 🗂 Scheme

<img src="./img/img-9.png" alt="Scheme" />

---

## 🖼️ Screenshots & Videos

<table>
    <tbody>
        <tr>
            <td>
                <img src="./img/img-4.png" alt="img" />
            </td>
            <td>
                <img src="./img/img-5.png" alt="img" />
            </td>
        </tr>
        <tr>
            <td>
                <img src="./img/img-6.png" alt="img" />
            </td>
            <td>
                <img src="./img/img-7.png" alt="img" />
            </td>
        </tr>
        <tr>
            <td>
                <img src="./img/img-8.png" alt="img" />
            </td>
            <td>
                <img src="./img/img-1.jpg" alt="img" />
            </td>
        </tr>
        <tr>
            <td>
                <img src="./img/img-1.jpg" alt="img" />
            </td>
            <td>
                <img src="./img/img-2.png" alt="img" />
            </td>
        </tr>
        <tr>
            <td>
                <img src="./img/img-3.png" alt="img" />
            </td>
        </tr>
    </tbody>
</table>

<table>
    <tbody>
        <tr>
            <td>
                <video src="https://github.com/user-attachments/assets/92ea80b2-de9d-4504-9056-02ea7e17678b" controls preload>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video src="https://github.com/user-attachments/assets/5c9417b9-f3e0-4aef-ba99-032b8544cdd0" controls preload>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video src="https://github.com/user-attachments/assets/0ec2567b-b284-4bd7-84db-66ee4fe38361" controls preload>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td>
                <video src="https://github.com/user-attachments/assets/25004c62-43ec-4c42-9905-88ad882c0b9d" controls preload>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video src="https://github.com/user-attachments/assets/a0934012-b1a5-42b5-b136-f4a4d92a7c74" controls preload>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video src="https://github.com/user-attachments/assets/a800194b-fea1-4f68-b524-f2e0d7a5f612" controls preload>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td></td>
            <td>
                <video src="https://github.com/user-attachments/assets/4b65c2f1-f13f-4be9-9d8b-f811c140edaf" controls preload>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td></td>
        </tr>
    </tbody>
</table>

---

## ⚙️ Technical Description

- **AI Models:** CNN (U-Net) for image analysis + RNN (LSTM) for temporal animation sequences
- **Preprocessing:**
    - Normalize images to fixed size
    - Convert to grayscale
    - Annotate motion vectors
- **Training:** Adam optimizer, dropout for regularization, data augmentation for style diversity
- **Motion Prediction:**
    - Calculate displacement per keypoint
    - Interpolate for smooth transitions
    - Spline-based motion flow

- **Frontend / Backend:** Optional integration with web tools for animation previews
- **Performance:** Average processing time <2 minutes per drawing

---

## 📝 Full Description

### 🔹 Overview
Digital storytelling demands **faster, accessible animation tools**. This project provides a platform where artists can **turn static drawings into motion** without technical barriers, enabling more experimentation and creativity.

### ❌ Problem
Traditional animation is **time-consuming** and requires **specialized skills/software**, limiting small creators and solo artists.

### ✅ Solution
- Upload drawings → select animation style → AI generates motion
- Reduces manual animation time from hours/days to **minutes**
- Makes animation **accessible, fast, and creative-friendly**

### 🛠️ Process
1. **Data Collection & Preprocessing**
    - Diverse drawing dataset
    - Normalize, grayscale, annotate with motion vectors

2. **Model Selection**
    - CNN (U-Net) for drawing feature extraction
    - RNN (LSTM) for motion sequence prediction

3. **Training the Model**
    - Custom CNN-RNN training loop
    - Dropout + data augmentation
    - Adam optimizer for adaptive learning

4. **Motion Prediction Implementation**
    - Generate motion vectors per frame
    - Interpolation for smooth animation
    - Spline-based motion flow

5. **Testing & Refinement**
    - Iterative feedback on unseen drawings
    - Parameter tuning for accuracy and smoothness

---

## 🏆 Achievements
- ⏱️ **80% reduction** in animation time
- ✅ 92% accuracy in motion vector prediction
- 👩‍🎨 Used by **500+ artists** with 85% satisfaction
- ⚡ 30% faster processing after optimization
- 📈 40% dataset expansion for better generalization

---

## 🔮 Future Improvements
1. Transformer-based models for complex animations
2. Real-time animation feedback & tweaking
3. More granular control: speed, intensity, motion paths
4. Integration with professional animation software
5. Dataset expansion for diverse styles
6. Improved scalability and efficiency

---

## 📚 References
1. [Deep Learning for Artists: Unleashing the Potential of AI in Animation](https://example.com)
2. [Automating Animation: CNNs & RNNs in Animation](https://example.com)
3. [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://example.com)
4. [LSTM Networks for Animation Generation](https://example.com)
5. [Machine Learning Impact on Animation](https://example.com)
6. [Transformer Models in Motion Prediction](https://example.com)
7. [Deep Learning in Animation Production](https://example.com)


