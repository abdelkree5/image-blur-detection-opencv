<h1 align="center">📸 Blur Detection using Laplacian</h1>
<h3 align="center">Computer Vision Quality Assessment Tool</h3>

<hr/>

<h2>🚀 Project Overview</h2>
<p>
This project implements an image blur detection system using 
the Variance of Laplacian method in OpenCV.
</p>

<p>
The system determines whether an image is blurry or sharp 
by analyzing edge intensity variance.
</p>

<hr/>

<h2>🧠 Core Concept</h2>

<p>
The Laplacian operator highlights regions of rapid intensity change.
Sharp images produce higher variance values,
while blurry images result in lower variance.
</p>

<p>
Blur Score = Variance(Laplacian(Image))
</p>

<hr/>

<h2>📊 Workflow</h2>

<ol>
<li>Load image</li>
<li>Convert to grayscale</li>
<li>Apply Laplacian operator</li>
<li>Compute variance</li>
<li>Compare with threshold</li>
<li>Classify as Sharp or Blurry</li>
</ol>

<hr/>

<h2>📂 Project Structure</h2>

<pre>
blur-detection-laplacian-cv/
│
├── Blur_detection_using_laplacian.py
├── sample_images/
└── README.md
</pre>

<hr/>

<h2>⚙️ Installation</h2>

<pre>
pip install opencv-python numpy
python Blur_detection_using_laplacian.py
</pre>

<hr/>

<h2>🛠 Tech Stack</h2>

<ul>
<li>Python</li>
<li>OpenCV</li>
<li>NumPy</li>
</ul>

<hr/>

<h2>📈 Use Cases</h2>

<ul>
<li>Image Quality Assessment</li>
<li>Camera autofocus validation</li>
<li>Dataset cleaning before training ML models</li>
<li>Computer Vision preprocessing pipeline</li>
</ul>

<hr/>

<h2>💡 Engineering Highlights</h2>

<ul>
<li>Edge-based blur quantification</li>
<li>Threshold-based classification</li>
<li>Lightweight and fast processing</li>
<li>Can be extended to real-time webcam feed</li>
</ul>

<hr/>

<h2>🔮 Future Improvements</h2>

<ul>
<li>Real-time webcam blur monitoring</li>
<li>Automatic threshold tuning</li>
<li>Deep Learning based blur classification</li>
<li>Integration with image upload API</li>
</ul>

<hr/>

<div align="center">
<h3>👨‍💻 Developed by abdelkreem abdelhaleem frahat</h3>
<p>AI Engineer | Computer Vision</p>
</div>
