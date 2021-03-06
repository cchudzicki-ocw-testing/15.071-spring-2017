---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: '2.2 The Statistical Sommelier: An Introduction to Linear Regression'
parent_type: CourseSection
parent_uid: 4495fb48-3934-3c33-23b2-2ef2104af559
title: '2.2 The Statistical Sommelier: An Introduction to Linear Regression'
uid: 04ad6920-c418-b28f-1259-8538cd8136cf
---

*   {{% resource_link 9b500b6f-7f1d-17af-5de0-ab9946895858 "\<Video 7: Making Predictions" %}}
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
*   {{% resource_link df5ef364-59d3-2e3f-98ec-9d920d6c5e1d "\>Video 8: Comparing the Model to the Experts" %}}

Quick Question
--------------

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\-7.0&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;\-0.3&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;0.0&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;0.6&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;1.0&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;2.4&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}Explanation

The formula for R?? is

R?? = 1 - SSE/SST,

where SST is calculated using the average value of the dependent variable on the training set.

Since SSE and SST are the sums of squared terms, we know that both will be positive. Thus SSE/SST must be greater than or equal to zero. This means it is not possible to have an out-of-sample R?? value of 2.4.

However, all other values are valid (even the negative ones!), since SSE can be more or less than SST, due to the fact that this is an out-of-sample R??, not a model R??.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   {{% resource_link 9b500b6f-7f1d-17af-5de0-ab9946895858 "BackVideo 7: Making Predictions" %}}
*   {{% resource_link df5ef364-59d3-2e3f-98ec-9d920d6c5e1d "ContinueVideo 8: Comparing the Model to the Experts" %}}