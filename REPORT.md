# Explaining our demand model - Lab 2 report

*Two people, one model, two kinds of explanation. Replace every arrow line with a real sentence;
every number gets a unit.*

## 1. The quick answer: built-in importances
![built-in importances](images/importances_builtin.png)

=> One sentence: which feature does the model lean on most, by magnitude alone?

## 2. The honest answer: SHAP global (beeswarm)
![SHAP beeswarm](images/shap_global.png)

=> One sentence: which feature is #1, and does a HIGH value push demand up or down?

## 3. Is the model any good?
![predicted vs actual](images/predicted_vs_actual.png)

=> One sentence: does it track the diagonal? roughly how far off is a typical hour?

## 4. Explaining one hour: SHAP local (waterfall)
![SHAP waterfall for the peak hour](images/shap_local.png)

=> One sentence: for the peak hour, what pushed the prediction up, and what pulled it down?

## 5. (Optional) Global meets local
![SHAP dependence](images/shap_dependence.png)

=> One sentence tying Lab 1 to Lab 2: *"it's the clock as much as the thermometer"* - say it in your words.

## What this explanation can't tell us
=> One honest sentence. (SHAP explains THIS model, not the real world; one summer, one region; correlation, not proof.)
