<h1>Early Detection of Parkinson's Disease using Hand Drawing and Speech </h1>
    <h2>Project Overview</h2>
    <p>This project is part of my graduation thesis from the Faculty of Computer and Information Science, Scientific Computing Department, Ain Shams University. The primary objective is the early detection of Parkinson's disease by leveraging two key features: <strong>Hand Drawing Analysis</strong> and <strong>Speech </strong>. The project has been implemented in a mobile application using <strong>Flutter</strong> for the front-end and <strong>Flask</strong> for the back-end.</p>
    <h3>Key Features</h3>
    <ul>
        <li><strong>Hand Drawing Analysis</strong>:
            <ul>
                <li>Users are prompted to draw three shapes: a spiral, a meander, and a circle. These shapes are then fused into one image with three channels.</li>
                <li>This combined image is fed into a <strong>Convolutional Neural Network (CNN)</strong> model to detect any indications of Parkinson's disease based on the irregularities in the drawing.</li>
            </ul>
        </li>
        <li><strong>Speech </strong>:
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
                <li>Random Forest for Speech  Analysis</li>
            </ul>
        </li>
    </ul>
    <h3>Project Structure</h3>
    <p>The project is organized into two main folders, each containing the relevant code and resources:</p>
    <ul>
        <li><strong>model_code</strong>: This folder contains the Python code for the machine learning models, including:
            <ul>
                <li><strong>hand_drawing_model</strong>: Contains the code and trained CNN model for analyzing hand drawings (spiral, meander, circle) to detect signs of Parkinson's disease.</li>
                <li><strong>speech_model</strong>: Contains the code and trained Random Forest model for analyzing speech recordings to detect signs of            Parkinson's disease.</li>
            </ul>
        </li>
        <li><strong>app_code</strong>: This folder contains the Flutter code for the mobile application.
        </li>
</ul>
    <h3>Dataset</h3>
    <p>The datasets used for this project are publicly available and can be accessed as follows:</p>
    <ul>
        <li><strong>Hand Drawing Analysis:</strong> We used the <a href="https://wwwp.fc.unesp.br/~papa/pub/datasets/Handpd/" target="_blank">NewHandPD</a> dataset, which includes various hand-drawn shapes                           collected from Parkinson's patients and healthy individuals.</li>
        <li><strong>Speech :</strong> We utilized the dataset available at <a href="https://zenodo.org/records/2867216" target="_blank">Zenodo</a>, which contains audio recordings of individuals                            reading a set text aloud, used to analyze speech patterns indicative of Parkinson's disease.</li>
    </ul>
    <h2>Usage</h2>
    <ol>
        <li><strong>Hand Drawing Analysis:</strong>
            <ul>
                <li>Open the app and navigate to the drawing screen.</li>
                <li>Draw the required shapes: spiral, meander, and circle.</li>
                <li>Submit the drawing for analysis.</li>
            </ul>
        </li>
        <li><strong>Speech :</strong>
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
