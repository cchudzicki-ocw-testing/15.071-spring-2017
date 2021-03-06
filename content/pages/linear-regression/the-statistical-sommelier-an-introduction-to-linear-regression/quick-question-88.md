---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: '2.2 The Statistical Sommelier: An Introduction to Linear Regression'
parent_type: CourseSection
parent_uid: 4495fb48-3934-3c33-23b2-2ef2104af559
title: '2.2 The Statistical Sommelier: An Introduction to Linear Regression'
uid: 20a0ee2d-c563-bbc1-243a-facac65c21f3
---

*   {{% resource_link 6111ddea-9e02-70be-a097-8feb66c8bf60 "\<Video 5: Understanding the Model" %}}
*   {{% resource_link 4495fb48-3934-3c33-23b2-2ef2104af559 "2.2.1Video 1: Predicting the Quality of Wine" %}}
*   {{% resource_link ef446456-afa1-894f-834f-a9ae8908c9a2 "2.2.2Quick Question" %}}
*   {{% resource_link 1f0b61bb-a29b-5ee7-5d26-5ed940cc2d1d "2.2.3Video 2: One-Variable Linear Regression" %}}
*   {{% resource_link a15d356c-50bc-b55a-2cbd-e1c66378ef25 "2.2.4Quick Question" %}}
*   {{% resource_link 505bba75-964b-7b2c-74d8-ebcee23c8259 "2.2.5Video 3: Multiple Linear Regression" %}}
*   {{% resource_link d97e0bd0-54ac-d9a6-df59-9f1b2e2daf73 "2.2.6Quick Question" %}}
*   {{% resource_link 9f456e81-561b-ed0d-7c0a-516cd7739d20 "2.2.7Video 4: Linear Regression in R" %}}
*   {{% resource_link dba3745d-05fd-fdd2-c5cc-f0b06194ed26 "2.2.8Quick Question" %}}
*   {{% resource_link 6111ddea-9e02-70be-a097-8feb66c8bf60 "2.2.9Video 5: Understanding the Model" %}}
*   {{% resource_link 20a0ee2d-c563-bbc1-243a-facac65c21f3 "2.2.10Quick Question" %}}
*   {{% resource_link 1ab830be-7abc-5468-421c-996f95e8e252 "2.2.11Video 6: Correlation and Multicollinearity" %}}
*   {{% resource_link bef58e98-6cee-f682-d32a-bfab033deaf6 "2.2.12Quick Question" %}}
*   {{% resource_link 9b500b6f-7f1d-17af-5de0-ab9946895858 "2.2.13Video 7: Making Predictions" %}}
*   {{% resource_link 04ad6920-c418-b28f-1259-8538cd8136cf "2.2.14Quick Question" %}}
*   {{% resource_link df5ef364-59d3-2e3f-98ec-9d920d6c5e1d "2.2.15Video 8: Comparing the Model to the Experts" %}}
*   {{% resource_link 1ab830be-7abc-5468-421c-996f95e8e252 "\>Video 6: Correlation and Multicollinearity" %}}

Quick Question
--------------

Use the dataset wine.csv to create a linear regression model to predict Price using HarvestRain and WinterRain as independent variables, like you did in the previous quick question. Using the summary output of this model, answer the following questions:

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;Yes&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;No&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;I can't answer this question using the summary output.&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}Explanation

You can create the model and look at the summary output with the following command:

model = lm(Price ~ WinterRain + HarvestRain, data=wine)

summary(model)

From the summary output, you can see that HarvestRain is significant (two stars), but WinterRain is not (no stars).{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}{{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;Yes&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;No&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;I can't answer this question using the summary output.&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}Explanation

You can create the model and look at the summary output with the following command:

model = lm(Price ~ WinterRain + HarvestRain, data=wine)

summary(model)

From the summary output, you can see that HarvestRain is significant (two stars), but WinterRain is not (no stars).{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

Note that you will need to answer both questions before checking your answers.

*   {{% resource_link 6111ddea-9e02-70be-a097-8feb66c8bf60 "BackVideo 5: Understanding the Model" %}}
*   {{% resource_link 1ab830be-7abc-5468-421c-996f95e8e252 "ContinueVideo 6: Correlation and Multicollinearity" %}}