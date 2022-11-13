# Datathon FME 2022 ⌨️


We are a team composed by freshman students from Data Science (Gerard, Joan and Laia)📊 and Computer Science (Álex)💻

## Problem statements

<details>
  <summary>
    Accenture
  </summary>
  👉 This challenge 🔨 presented by the consulting company "accenture" aimed to predict which orders could get to the customer later ⌛ than expected so they could avoid that on a suply chain 📦.
</details>

<details>
  <summary>
    Qualcomm
  </summary>
  
  👉 After a really extense talk about Qualcomm's operations and fields of research, the presented problem.  <br />
  
  The problem was related to pin connection management and routes 🛤️. They explained how processors worked and how routes affed the consumption of the processors. The optimization of those routes adding a bus of signals instead of only one signal would make the trick, but we should know how to connect them in the most efficient way.
  
  We could not find this challenge appropiete for us since it was too technical to the few time we had (32 hours) although it was quite interesting.
</details>

<details>
  <summary>
    AED (Association of Data Science)
  </summary>
  👉 The challenge propossed by AED aimed to help our seniors 👴 in their daily life such as lonelyness, digital education, staying active...
  The datasets given were open access and they also allowed us to use many other different sources of data if we wanted to
</details>

## Challenge choosing and brainstorming

After considering Accenture's and AED's challenges, we decided to tackle Accenture's challenge due to being more restricted to an existing problem. We devided the tasks in a way we could all work at the same time on different things and be productive 👷. The tasks were splitted in the following way:

- Laia and Álex did some Feature Engineering, extracting interesting features from the many datasets we had and joining them to the one we considered to be the main one (orders.csv)📉.
- Gerard and Joan on the other hand started doing some plots and getting which data relations were the best📊.

## Procedure

When making the code to solve the problem, we found several difficulties. One of them beeing the data cleaning and preprocessing process, where we had to handle cathegorical values, NaNs and also join data from many different datasets that were not sorted in the same way the main one (orders.csv) was.

After that data cleaning was done, we built a model to predict the likelyhood of a parcel arriving late⏱️.

## Conclusions

After an in-depth analysis of the results, we got to the conclusion that given the nature of the data, predictions with that data "as it is" with the True and False labels counts being equal would not produce a well fitted model (Giving scores of about 20% of accuracy). If we used the whole dataset (>87000 False labels and < 28000 True labels) produced an overfitted model, giving a 70% of accuracy but always ansering the same (False).

We believe that more carefuly chosen training variables and also joining several of them together would produce a better model, but individually, the produced model gives poor results.
