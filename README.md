# datasciencecoursera
tab_freq &lt;- function(data, v1, v2) { data %>% tabyl({{ v1 }}, {{ v2 }}) %>% adorn_totals(c("row", "col")) %>% adorn_percentages("all") %>% adorn_pct_formatting(2) %>% adorn_ns() 
