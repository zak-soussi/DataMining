<!DOCTYPE html>
<html>


<body>
<h1>TP N°3: Supervised Classification - Learning and Evaluation</h1>
<h2>Objective:</h2>
    <p>This TP aims to:</p>
    <ul>
        <li>Familiarize with Python's scikit-learn library for machine learning.</li>
        <li>Understanding the evaluation of supervised classification models.</li>
    </ul>
<h2>Contents:</h2>
 <h3>I- Datasets:</h3>
    <ol>
        <li><strong>Iris:</strong>
            <ul>
                <li>Description: Dataset introduced by Ronald Aylmer Fisher in 1936, comprising 150 examples of observed criteria on different species of Iris from Gaspésie.</li>
                <li>Attributes:  Four attributes per instance (sepal length and width in cm, petal length and width in cm) and a class label (species).</li>
            </ul>
        </li>
        <li><strong>Exploration Tasks:</strong>
            <ul>
                <li>Understanding the dataset's structure.</li>
                <li>Plotting data distribution based on different attribute pairs.</li>
                <li>Exploring the possibility of a 2D space separating classes.</li>
            </ul>
        </li>
        <li><strong>Other Datasets:</strong>
            <ul>
                <li>Additional datasets available in scikit-learn and methods for retrieval.</li>
            </ul>
        </li>
    </ol>
    <h3>II- Initial Classifier Learning:</h3>
    <ul>
        <li><strong>Naïve Bayes Multinomial:</strong>
            <ul>
                <li>Understanding and implementing Multinomial Naïve Bayes algorithm with Iris dataset.</li>
            </ul>
        </li>
    </ul>
 <h3>III- Evaluating Classifier Performance:</h3>
    <ol>
        <li><strong>Performance on Training Set:</strong>
            <ul>
                <li>Computing training set performance metrics: Error rate and accuracy.</li>
            </ul>
        </li>
        <li><strong>Generalization Performance:</strong>
            <ul>
                <li>Estimating real errors via train/test split, custom functions, and <code>train_test_split</code>.</li>
                <li>Cross-validation using <code>cross_val_score</code>.</li>
            </ul>
        </li>
    </ol>
<h3>IV- Reporting:</h3>
    <ol>
        <li><strong>Summaries and Analysis:</strong>
            <ul>
                <li>Organizing summaries of errors calculated and estimated on the Iris dataset.</li>
            </ul>
        </li>
        <li><strong>Alternative Method:</strong>
            <ul>
                <li>Implementing and analyzing the Decision Tree Classifier with default parameters.</li>
            </ul>
        </li>
    </ol>

</body>

</html>
