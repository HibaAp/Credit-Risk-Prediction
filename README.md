# Credit-Risk-Prediction
# Internal Banking Data Features

This dataset contains several features related to customer accounts in the banking sector. Below is a description of each variable included in the dataset:

| Variable Name                    | Description                                           |
|----------------------------------|-------------------------------------------------------|
| **Total_TL**                     | Total trade lines/accounts in Bureau                   |
| **Tot_Closed_TL**                | Total closed trade lines/accounts                       |
| **Tot_Active_TL**                | Total active accounts                                   |
| **Total_TL_opened_L6M**          | Total accounts opened in the last 6 months            |
| **Tot_TL_closed_L6M**            | Total accounts closed in the last 6 months            |
| **pct_tl_open_L6M**              | Percent of accounts opened in the last 6 months       |
| **pct_tl_closed_L6M**            | Percent of accounts closed in the last 6 months       |
| **pct_active_tl**                | Percent of active accounts                              |
| **pct_closed_tl**                | Percent of closed accounts                              |
| **Total_TL_opened_L12M**         | Total accounts opened in the last 12 months           |
| **Tot_TL_closed_L12M**           | Total accounts closed in the last 12 months           |
| **pct_tl_open_L12M**             | Percent of accounts opened in the last 12 months      |
| **pct_tl_closed_L12M**           | Percent of accounts closed in the last 12 months      |
| **Tot_Missed_Pmnt**              | Total missed payments                                  |
| **Auto_TL**                      | Count of automobile accounts                            |
| **CC_TL**                        | Count of credit card accounts                           |
| **Consumer_TL**                  | Count of consumer goods accounts                        |
| **Gold_TL**                      | Count of gold loan accounts                             |
| **Home_TL**                      | Count of housing loan accounts                          |
| **PL_TL**                        | Count of personal loan accounts                         |
| **Secured_TL**                   | Count of secured accounts                               |
| **Unsecured_TL**                 | Count of unsecured accounts                             |
| **Other_TL**                     | Count of other accounts                                 |
| **Age_Oldest_TL**                | Age of the oldest opened account                       |
| **Age_Newest_TL**                | Age of the newest opened account                       |

# External CIBIL Data Features

This dataset contains several features related to customer credit history and profile. Below is a description of each variable included in the dataset:

| Variable Name                            | Description                                           |
|------------------------------------------|-------------------------------------------------------|
| **time_since_recent_payment**            | Time since the most recent payment made                |
| **time_since_first_delinquency**         | Time since the first delinquency (missed payment)     |
| **time_since_recent_delinquency**        | Time since the most recent delinquency                 |
| **num_times_delinquent**                 | Number of times delinquent                             |
| **max_delinquency_level**                | Maximum delinquency level                              |
| **max_recent_level_of_deliq**            | Maximum recent level of delinquency                    |
| **num_deliq_6mts**                       | Number of times delinquent in the last 6 months       |
| **num_deliq_12mts**                      | Number of times delinquent in the last 12 months      |
| **num_deliq_6_12mts**                    | Number of times delinquent between the last 6 months and last 12 months |
| **max_deliq_6mts**                       | Maximum delinquency level in the last 6 months        |
| **max_deliq_12mts**                      | Maximum delinquency level in the last 12 months       |
| **num_times_30p_dpd**                   | Number of times 30+ days past due                      |
| **num_times_60p_dpd**                   | Number of times 60+ days past due                      |
| **num_std**                              | Number of standard payments                             |
| **num_std_6mts**                         | Number of standard payments in the last 6 months      |
| **num_std_12mts**                        | Number of standard payments in the last 12 months     |
| **num_sub**                              | Number of substandard payments (not making full payments) |
| **num_sub_6mts**                         | Number of substandard payments in the last 6 months    |
| **num_sub_12mts**                        | Number of substandard payments in the last 12 months   |
| **num_dbt**                              | Number of doubtful payments                             |
| **num_dbt_6mts**                         | Number of doubtful payments in the last 6 months       |
| **num_dbt_12mts**                        | Number of doubtful payments in the last 12 months      |
| **num_lss**                              | Number of loss accounts                                 |
| **num_lss_6mts**                         | Number of loss accounts in the last 6 months           |
| **num_lss_12mts**                        | Number of loss accounts in the last 12 months          |
| **recent_level_of_deliq**                | Recent level of delinquency                            |
| **tot_enq**                              | Total enquiries                                        |
| **CC_enq**                               | Credit card enquiries                                   |
| **CC_enq_L6m**                           | Credit card enquiries in the last 6 months             |
| **CC_enq_L12m**                          | Credit card enquiries in the last 12 months            |
| **PL_enq**                               | Personal loan enquiries                                 |
| **PL_enq_L6m**                           | Personal loan enquiries in the last 6 months           |
| **PL_enq_L12m**                          | Personal loan enquiries in the last 12 months          |
| **time_since_recent_enq**                | Time since the most recent enquiry                      |
| **enq_L12m**                             | Enquiries in the last 12 months                        |
| **enq_L6m**                              | Enquiries in the last 6 months                         |
| **enq_L3m**                              | Enquiries in the last 3 months                         |
| **MARITALSTATUS**                        | Marital status                                         |
| **EDUCATION**                            | Education level                                        |
| **AGE**                                  | Age                                                   |
| **GENDER**                               | Gender                                                |
| **NETMONTHLYINCOME**                    | Net monthly income                                     |
| **Time_With_Curr_Empr**                 | Time with current employer                             |
| **pct_of_active_TLs_ever**              | Percent of active accounts ever                        |
| **pct_opened_TLs_L6m_of_L12m**          | Percent of accounts opened in the last 6 months to last 12 months |
| **pct_currentBal_all_TL**                | Percent of current balance of all accounts             |
| **CC_utilization**                       | Credit card utilization                                |
| **CC_Flag**                              | Credit card flag                                      |
| **PL_utilization**                       | Personal loan utilization                              |
| **PL_Flag**                              | Personal loan flag                                     |
| **pct_PL_enq_L6m_of_L12m**              | Percent of PL enquiries in the last 6 months to last 12 months |
| **pct_CC_enq_L6m_of_L12m**              | Percent of CC enquiries in the last 6 months to last 12 months |
| **pct_PL_enq_L6m_of_ever**              | Percent of PL enquiries in the last 6 months to ever   |
| **pct_CC_enq_L6m_of_ever**              | Percent of CC enquiries in the last 6 months to ever   |
| **max_unsec_exposure_inPct**            | Maximum unsecured exposure in percent                  |
| **HL_Flag**                              | Housing loan flag                                     |
| **GL_Flag**                              | Gold loan flag                                        |
| **last_prod_enq2**                      | Latest product enquired for                            |
| **first_prod_enq2**                     | First product enquired for                             |
| **Credit_Score**                         | Applicant's credit score                               |
| **Approved_Flag**                        | Priority levels                                       |

