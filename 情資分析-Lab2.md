# 2017/07/05 情資分析

### Lab2：looking data

We get 126 features in our data.



> ##### [data](https://goo.gl/k7tqyY)



> **Field name**

| **CVE_ID**             | **exploit_date**       | **label**                 | **zeroday_price** |
| ---------------------- | ---------------------- | ------------------------- | ----------------- |
| **firstdateontwitter** | **date_entry_created** | **original_release_date** | **overview**      |

| **CVSS_V3_base_score**        | **CVSS_V3_impact_score**                 | **CVSS_V3_exploitability_score** |
| :---------------------------- | ---------------------------------------- | -------------------------------- |
| **CVSS_V3_attack_vector**     | **CVSS_V3_attack_complexity**            | **CVSS_V3_privileges_required**  |
| **CVSS_V3_user_interaction**  | **CVSS_V3_scope**                        | **CVSS_V3_confidentiality**      |
| **CVSS_V3_integrity**         | **CVSS_V3_availability**                 | **CVSS_V2_base_score**           |
| **CVSS_V2_impact_subscore**   | **CVSS_V2_exploitability_subscore**      | **CVSS_V2_access_vector**        |
| **CVSS_V2_access_complexity** | **CVSS_V2_authentication**               | **CVSS_V2_impact_type**          |
| **NVD_reference_count**       | **NVD_vulnerable_software_and_versions_count** | **NVD_CWEID**                    |

| **cvedetail_affected  total number(all products and versions)** | **cvedetail_affected vender**         | **cvedetail_affected vender number** |
| ---------------------------------------- | ------------------------------------- | ------------------------------------ |
| **cvedetail_affected  product**          | **cvedetail_affected product number** | **cvedetail_vultype**                |

| **advisory** | **beware**    | **sample**  |
| ------------ | ------------- | ----------- |
| **exploit**  | **go**        | **xp**      |
| **ie**       | **poc**       | **web**     |
| **java**     | **working**   | **fix**     |
| **bug**      | **blog**      | **pc**      |
| **reading**  | **iis**       | **ssl**     |
| **post**     | **day**       | **bash**    |
| **ok**       | **mcafee**    | **windows** |
| **w**        | **microsoft** | **info**    |
| **rce**      | **patch**     | **piyolog** |
| **tested**   |               |             |

| **tweet_u_followers** | **tweet_u_friends**  | **tweet_u_listed**   |
| --------------------- | -------------------- | -------------------- |
| **tweet_u_favorites** | **tweet_u_statuses** | **tweet_u_timezone** |
| **tweet_u_lang**      | **tweet_retweet**    | **tweet_favorite**   |
| **tweet__lang**       |                      |                      |

| **retweet_u_followers** | **retweet_u_friends**     | **retweet_u_listed**      | **retweet_u_favorites**  |
| ----------------------- | ------------------------- | ------------------------- | ------------------------ |
| **retweet_u_statuses**  | **retweet_u_timezone**    | **retweet_u_lang**        | **retweet_retweet**      |
| **retweet_favorite**    | **retweet_lang**          | **retweet_reu_followers** | **retweet_reu_friends**  |
| **retweet_reu_listed**  | **retweet_reu_favorites** | **retweet_reu_statuses**  | **retweet_reu_timezone** |
| **retweet_reu_lang**    | **retweet_re_retweet**    | **retweet_re_favorite**   | **retweet_count**        |

| **quote_u_followers**  | **quote_u_friends**     | **quote_u_listed**      | **quote_u_favorites**   |
| ---------------------- | ----------------------- | ----------------------- | ----------------------- |
| **quote_u_statuses**   | **quote_u_timezone**    | **quote_u_lang**        | **quote_retweet**       |
| **quote_favorite**     | **quote_lang**          | **quote_reu_followers** | **quote_reu_friends**   |
| **quote_reu_listed**   | **quote_reu_favorites** | **quote_reu_statuses**  | **quote_reu_timezone**  |
| **quote_reu_lang**     | **quote_re_retweet**    | **quote_re_favorite**   | **quote_qou_followers** |
| **quote_qou_friends**  | **quote_qou_listed**    | **quote_qou_favorites** | **quote_qou_statuses**  |
| **quote_qou_timezone** | **quote_qou_lang**      | **quote_qo_retweet**    | **quote_qo_favorite**   |
| **quote_count**        |                         |                         |                         |