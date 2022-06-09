gantt
    title Platform Engineering
    dateFormat  MM-DD-YYYY

    section Edge Routing 
      Streamlined AGCDN WAF Issues - Test Fastly’s Loop detection fix and unblock Streamlined AGCDN WAF migrations           :a1, 2022-06-01, 30d
      Fastly POP Migration     :a2, after a1, 15d
      Fastly Realtime Metrics  :a3, after a2, 7d
      Decoupled  :b1, 2022-0601, 120d
    section Platform Routing
      Drupal Steward - Enforcement      : rout1, 2022-06-15  , 15d
      ygg-dns to CloudDNS      : rout2, 2022-07-01, 45d
      ygg-route readDB : rout3, after rout2, 45d
    section Platform Workloads
      UJR Automated Backups      :2022-06-01  , 30d
      Site Image Factory      :2022-07-01, 90d
            
