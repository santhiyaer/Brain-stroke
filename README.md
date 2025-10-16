# Multi-Modal CNN based Stroke Detection from CT images and Clinical Data

<h1 >Objective</h1>
<ul>
  
  <li>To improve stroke detection accuracy by integrating brain CT images and 
      patient clinical data using machine learning-based multi-modal inputs. </li>

<li>To provide better risk assessment and early diagnosis by identifying key 
     stroke predictors through the analysis of CT scans and clinical data.</li>
</ul>

<h1>Proposed System</h1>
  <ul>
  <li>Data Preparation: CT images are pre-processed and clinical parameters are recorded for each patient.</li>
  <li>Image Segmentation: U-Net segments lesion areas from brain CT scans.</li>
  <li>Feature Extraction and Prediction: 3D DenseNet-169 predicts outcomes from images (Model A) and Random Forest predicts from clinical data (Model B).</li>
  <li>Outcome Aggregation: Predictions from Model A and B are combined; conflicts or unfavorable cases are re-evaluated by Model C.</li>
  <li>Final Prediction: Final mRS score is determined based on model consensus or Model C refinement.</li>
</ul>

<h1>Application Screenshots</h1>
<p>The following images showcase the application:</p>
<p>
  
</p>
