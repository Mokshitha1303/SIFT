<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="SIFT Keypoint Detection and Visualization">
   
</head>
<body>
    <header>
        <h1>Scale-Invariant Feature Transform (SIFT)</h1>
    </header>

   <div class="container">
        <h2>About the Project</h2>
        <p>
            This project demonstrates the use of the <strong>Scale-Invariant Feature Transform (SIFT)</strong> algorithm to detect and 
            visualize keypoints in a grayscale image. SIFT is widely used in computer vision for identifying features that are invariant to 
            scale, rotation, and lighting changes, making it ideal for applications like object detection and image matching.
        </p>

  <h2>Key Features</h2>
        <ul>
            <li>Detects distinctive keypoints in a grayscale image using the SIFT algorithm.</li>
            <li>Computes descriptors for each keypoint to represent their local appearance.</li>
            <li>Visualizes keypoints on the image using rich feature representation.</li>
            <li>Displays the number of detected keypoints and the dimensions of their descriptors.</li>
        </ul>

  <h2>How It Works</h2>
        <ol>
            <li>Loads a sample grayscale image using the <code>skimage.data</code> module.</li>
            <li>Initializes the SIFT detector using OpenCV's <code>SIFT_create()</code> method.</li>
            <li>Detects keypoints and computes their descriptors using <code>detectAndCompute()</code>.</li>
            <li>Draws the detected keypoints on the image for visualization.</li>
            <li>Outputs the number of detected keypoints and the shape of the descriptor array.</li>
        </ol>

  
<h2>View the Code</h2>
<p>You can view the complete code on GitHub: 
    <a href="https://github.com/Mokshitha1303/SIFT/blob/main/SIFT.ipynb" target="_blank">GitHub Repository</a>
</p>

  <h2>Sample Output</h2>
        <p><strong>Example of printed output:</strong></p>
        <pre><code>
Number of keypoints: 312
Descriptors shape: (312, 128)
        </code></pre>

   <h2>Applications</h2>
        <ul>
            <li>Object recognition and matching in images.</li>
            <li>Feature-based image alignment and stitching.</li>
            <li>Tracking and motion detection in video frames.</li>
        </ul>

   

   <h2>Contributing</h2>
        <p>Contributions are welcome! Fork the repository and submit a pull request with improvements or fixes.</p>
    </div>

   <footer>
        <p> 2024 Mokshitha Mohan</p>
    </footer>
</body>
</html>
