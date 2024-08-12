<h1>Early Detection of Parkinson's Disease using Hand Drawing and Speech Recognition</h1>
    <h2>Project Overview</h2>
    <p>This project is part of my graduation thesis from the Faculty of Computer and Information Science, Scientific Computing Department, Ain Shams University. The primary objective is the early detection of Parkinson's disease by leveraging two key features: <strong>Hand Drawing Analysis</strong> and <strong>Speech Recognition</strong>. The project has been implemented in a mobile application using <strong>Flutter</strong> for the front-end and <strong>Flask</strong> for the back-end.</p>
    <h3>Key Features</h3>
    <ul>
        <li><strong>Hand Drawing Analysis</strong>:
            <ul>
                <li>Users are prompted to draw three shapes: a spiral, a meander, and a circle. These shapes are then fused into one image with three channels.</li>
                <li>This combined image is fed into a <strong>Convolutional Neural Network (CNN)</strong> model to detect any indications of Parkinson's disease based on the irregularities in the drawing.</li>
            </ul>
        </li>
        <li><strong>Speech Recognition</strong>:
            <ul>
                <li>Users are required to read a text displayed on the screen, and their speech is recorded.</li>
                <li>The recorded audio is analyzed using a <strong>Random Forest model</strong> to identify potential signs of Parkinson's disease through speech pattern analysis.</li>
            </ul>
        </li>
    </ul>
    <h3>Results</h3>
    <ul>
        <li><strong>Achieved Grade:</strong> A+</li>
        <li><strong>Recognition:</strong> Awarded for innovation in early detection methodologies.</li>
    </ul>
    <h2>Tech Stack</h2>
    <ul>
        <li><strong>Mobile App:</strong> Flutter</li>
        <li><strong>Back-End:</strong> Flask</li>
        <li><strong>Machine Learning Models:</strong>
            <ul>
                <li>Convolutional Neural Network (CNN) for Hand Drawing Analysis</li>
                <li>Random Forest for Speech Recognition Analysis</li>
            </ul>
        </li>
    </ul>
    <h2>Project Structure</h2>
    <ul>
        <li><code>mobile_app/</code>: Contains the Flutter code for the mobile application.</li>
        <li><code>backend/</code>: Contains the Flask back-end code responsible for handling the ML models and API.</li>
        <li><code>models/</code>: Contains the trained models (CNN and Random Forest) used for predictions.</li>
        <li><code>data/</code>: Contains the datasets used for training and validation of the models.</li>
        <li><code>notebooks/</code>: Contains Jupyter notebooks with the code for model training and evaluation.</li>
        <li><code>README.md</code>: This file.</li>
    </ul>
    <h2>Installation and Setup</h2>
    <h3>Prerequisites</h3>
    <ul>
        <li><strong>Python 3.7+</strong></li>
        <li><strong>Flutter 2.0+</strong></li>
        <li><strong>pip</strong> for Python package management</li>
    </ul>
    <h3>Steps</h3>
    <ol>
        <li><strong>Clone the Repository:</strong>
            <pre><code>git clone https://github.com/YourUsername/parkinsons-detection.git cd parkinsons-detection</code></pre>
        </li>
        <li><strong>Backend Setup:</strong>
            <ol>
                <li>Navigate to the backend directory:
                    <pre><code>cd backend</code></pre>
                </li>
                <li>Install the required Python packages:
                    <pre><code>pip install -r requirements.txt</code></pre>
                </li>
                <li>Run the Flask server:
                    <pre><code>flask run</code></pre>
                </li>
            </ol>
        </li>
        <li><strong>Mobile App Setup:</strong>
            <ol>
                <li>Navigate to the <code>mobile_app</code> directory:
                    <pre><code>cd ../mobile_app</code></pre>
                </li>
                <li>Get the Flutter dependencies:
                    <pre><code>flutter pub get</code></pre>
                </li>
                <li>Run the mobile app:
                    <pre><code>flutter run</code></pre>
                </li>
            </ol>
        </li>
    </ol>
    <h3>Dataset</h3>
    <p>The dataset used for this project is not publicly available due to privacy concerns. However, you can use similar datasets available for Parkinson's research or create your own dataset by capturing user drawings and audio.</p>
    <h2>Usage</h2>
    <ol>
        <li><strong>Hand Drawing Analysis:</strong>
            <ul>
                <li>Open the app and navigate to the drawing screen.</li>
                <li>Draw the required shapes: spiral, meander, and circle.</li>
                <li>Submit the drawing for analysis.</li>
            </ul>
        </li>
        <li><strong>Speech Recognition:</strong>
            <ul>
                <li>Read the text displayed on the screen aloud.</li>
                <li>The app will automatically record and analyze your speech.</li>
            </ul>
        </li>
        <li><strong>Results:</strong>
            <ul>
                <li>The app will provide a probability score indicating the likelihood of Parkinson's disease.</li>
            </ul>
        </li>
    </ol>
    <h2>Contributing</h2>
    <p>Contributions are welcome! Please open an issue or submit a pull request for any improvements.</p>
    <h2>Acknowledgments</h2>
    <ul>
        <li><strong>Advisors:</strong> Manal Tantawi and Manar Sultan</li>
        <li><strong>University:</strong> Ain Shams University, Faculty of Computer and Information Science, Scientific Computing Department</li>
    </ul>

    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
