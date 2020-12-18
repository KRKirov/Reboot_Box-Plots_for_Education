# Reboot_Box-Plots_for_Education
DrivenData Competition

Reboot: Box-Plots for Education is a re-run of DrivenData's first ever competition. The competition was hosted by the Education Resource Strategies (ERS). The goal of the competition is to attach canonical labels to freeform text in school budget line items. This helps the ERS understand how schools spend their money and recommend the best spending strategy [1].


This is a very interesting competition because:
1. It is a cross between a tabular and a natural language processing competition. There are only two numeric features. The other fourteen features contain short phrases, e.g. salaries for support personnel, teacher elementary 2nd bil, etc.
2. It is a multi-class-multi-label classification competition. The y-vector has nine features and a total of 104 labels are predicted simultaneously.
3. The evaluation metric for predictions is the log-loss. Since the log-loss penalises correct but overly confident predictions more than wrong but less confident predictions, tuning the predicted label probabilities is harder than just predicting the correct label.

[1] Reboot: Box-Plots for Education, DrivenData, accessed from https://www.drivendata.org/competitions/46/box-plots-for-education-reboot/ on 18.12.2020.
