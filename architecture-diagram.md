                Internet Users
                       |
                 Load Balancer
                       |
        --------------------------------
        |              |              |
   Web Server 1   Web Server 2   Web Server 3
        |              |              |
        --------------------------------
                       |
                API Gateway
                       |
         --------------------------
         |                        |
   Application Services     Authentication Service
         |
    Redis Cache
         |
   Database Layer
         |
  Primary Database
         |
   Read Replicas
         |
      Backup Storage
