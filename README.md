# The Necessity of Complex Data: Object Importance by Removing for High-Dimensional Structured Objects

This project investigates the importance of Airbnb property images for the prediction of Airbnb listing prices.

The data was obtained from https://public.opendatasoft.com/explore/dataset/airbnb-listings/information/?flg=en-us&disjunctive.host_verifications&disjunctive.amenities&disjunctive.features
and downloaded as a csv file. The analysis was performed on a Linux GPU compute server with 192GB memory and 40 physical cores at 3.1 GHz provided by the Humboldt Lab for Empirical
and Quantitative Research. Use the Code_Thesis_Vincent_Karpf.ipynb file to reproduce the results.

# Abstract

The age of big data has given rise to high-dimensional datasets, opening up new opportunities
to use this data to make more accurate predictions or inferences. However, the use of such data
can make tasks significantly more complex, leading to the question of whether it is practical
to consider this data for a given problem. This thesis explores the impact of high-dimensional
structured data on the prediction of a scalar-valued output. Specifically, it examines the predictive
effect of property images on the accuracy of Airbnb listing price predictions. By framing
the research question as a conditional independence problem, the goal is to examine whether
listing prices are independent of property images, given tabular listing data. A novel supervised
learning-based approach is used to assess the conditional dependence of price on images in the
presence of tabular data. Advancements in deep learning are leveraged to incorporate image
information in the form of embeddings into the conditional independence test. The analysis consideres
various predictive models to approximate the optimal prediction functional. Challenges
arise from the dimensionality of the preprocessed dataset, and uncertainty remains regarding
the optimal prediction functional, which may bias the test results. Surprisingly, linear regression
models perform comparatively well, suggesting a more linear than nonlinear relationship between
the variables and the listing price. Attempts are made to increase the robustness of the analysis
with respect to several aspects of the analysis, including sample size and image embeddings. Under
corresponding assumptions and approximations, the findings indicate a predictive impact of
image data in pricing models. This suggests that incorporating images into predictive analytics
can refine pricing strategies within companies. In future work, it would be interesting to investigate
whether another type of high-dimensional structured object, such as textual information,
also has a predictive impact.
